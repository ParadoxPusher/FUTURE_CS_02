# Phishing Email Detection & Awareness System

## Cyber Security Task 2 (2026)
**By Future Interns**

---

## Overview

This repository contains a comprehensive phishing email detection and awareness report, created as part of the Cyber Security Task 2 internship assignment. The project demonstrates how to identify phishing emails, analyze their characteristics, and create employee awareness materials.

---

## What is Phishing?

**Phishing** is a cyberattack where criminals send fake emails, messages, or create fake websites that impersonate legitimate organizations. The goal is to trick recipients into:

- Revealing passwords and login credentials
- Providing financial information (credit cards, bank accounts)
- Downloading malware or ransomware
- Transferring money to attacker-controlled accounts
- Disclosing sensitive company information

### Why Phishing Works

Phishing exploits human psychology rather than technical vulnerabilities. Attackers use tactics like:

- **Authority** - People tend to obey authority figures
- **Urgency** - Time pressure reduces critical thinking
- **Fear** - Threats of account closure or financial loss
- **Curiosity** - "You've won!" or "Package delivery failed"
- **Trust** - Exploiting trust in well-known brands

---

## Repository Structure

```
phishing_github_repo/
├── README.md                          # This file
├── report/
│   └── phishing_detection_report.pdf  # Full analysis report (16 pages)
├── email_samples/
│   ├── email_001_paypal_phishing.txt
│   ├── email_002_microsoft_phishing.txt
│   ├── email_003_amazon_suspicious.txt
│   ├── email_004_bec_whaling.txt
│   ├── email_005_amazon_safe.txt
│   └── email_006_netflix_phishing.txt
└── awareness_materials/
    ├── phishing_red_flags.md
    ├── dos_and_donts.md
    └── response_procedures.md
```

---

## Email Analysis Summary

| ID | Subject | Classification | Risk Level | Attack Type |
|----|---------|----------------|------------|-------------|
| EMAIL-001 | Urgent: Your Account Will Be Suspended | **PHISHING** | HIGH | Credential Harvesting (Typosquatting) |
| EMAIL-002 | Action Required: Password Expiration | **PHISHING** | HIGH | Corporate Credential Harvesting |
| EMAIL-003 | Invoice Payment Overdue | **SUSPICIOUS** | MEDIUM | Invoice Fraud |
| EMAIL-004 | URGENT: Wire Transfer Request | **PHISHING** | CRITICAL | Business Email Compromise (BEC) |
| EMAIL-005 | Your Amazon Order Has Shipped | **SAFE** | LOW | Legitimate Email |
| EMAIL-006 | You've Won a $500 Gift Card! | **PHISHING** | HIGH | Prize/Lottery Scam |

**Total Emails Analyzed:** 6  
**Phishing Detected:** 4  
**Suspicious:** 1  
**Safe:** 1

---

## Key Findings

### Most Critical Finding: Business Email Compromise (BEC)

**EMAIL-004** demonstrates a Business Email Compromise (BEC) attack - the most financially damaging type of phishing. The attacker impersonates the CEO to request an urgent wire transfer of $47,500, bypassing normal approval processes.

**BEC Attack Characteristics:**
- Impersonates executives or senior leaders
- Creates extreme urgency
- Requests wire transfers or sensitive data
- Bypasses normal procedures
- Has caused billions in global losses

### Common Phishing Indicators Identified

1. **Typosquatting Domains** - paypa1-secure.com (using number 1 instead of letter l)
2. **Urgency Tactics** - "24 hours", "account will be suspended"
3. **Generic Greetings** - "Dear Customer" instead of personalized names
4. **Suspicious Links** - URLs that don't match claimed sender
5. **Email Authentication Failures** - DKIM/SPF failures
6. **Too Good To Be True Offers** - Free prizes, lottery wins
7. **Authority Abuse** - Executives requesting unusual actions

---

## Top 10 Phishing Red Flags

| # | Red Flag | Example |
|---|----------|---------|
| 1 | Suspicious Sender Domain | security@paypa1-secure.com |
| 2 | Urgency & Fear Tactics | "Account will be suspended in 24 hours" |
| 3 | Generic Greetings | "Dear Customer" vs "Dear John Smith" |
| 4 | Suspicious Links | URL doesn't match claimed sender |
| 5 | Unexpected Attachments | Invoice_0342.zip from unknown sender |
| 6 | Requests for Sensitive Info | "Please confirm your password" |
| 7 | Too Good To Be True | "You've won a $500 gift card!" |
| 8 | Poor Grammar/Spelling | "We noticed suspicious activitys" |
| 9 | Unusual Executive Requests | CEO requesting wire transfer without docs |
| 10 | Email Authentication Failures | SPF/DKIM failures |

---

## Prevention Guidelines

### DO's - Security Best Practices

1. Verify the sender's email address carefully
2. Hover over links before clicking
3. Check email authentication (DKIM, SPF, DMARC)
4. Contact sender through trusted channels
5. Report phishing to IT security immediately
6. Use multi-factor authentication (MFA)
7. Keep software updated
8. Verify urgent requests through second channel
9. Check for personalized greetings
10. Look for grammar/spelling errors

### DON'Ts - Things to Avoid

1. Don't click links from unknown senders
2. Don't enter credentials from email links
3. Don't trust urgency or fear tactics
4. Don't reply to suspicious emails
5. Don't assume logos mean legitimacy
6. Don't provide sensitive info via email
7. Don't bypass security protocols
8. Don't trust "too good to be true" offers
9. Don't open unexpected password-protected attachments
10. Don't scan QR codes in unexpected emails

---

## Response Procedures

### If You Suspect a Phishing Email:

1. **STOP** - Do not click any links or download attachments
2. **VERIFY** - Contact sender through trusted channel
3. **REPORT** - Forward to IT security team
4. **DELETE** - Remove from inbox
5. **MONITOR** - Watch accounts for suspicious activity

### If You Clicked a Suspicious Link:

1. **DISCONNECT** - Disconnect from internet immediately
2. **SCAN** - Run full antivirus scan
3. **CHANGE PASSWORDS** - Change compromised account passwords
4. **REPORT** - Notify IT security immediately
5. **MONITOR** - Watch for unauthorized activity

---

## Tools Used

- **Browser Developer Tools** - For inspecting email elements
- **Email Header Analyzers** - For authentication verification
  - Google Admin Toolbox: https://toolbox.googleapps.com/apps/messageheader/
  - MXToolbox: https://mxtoolbox.com/EmailHeaders.aspx
- **Manual Analysis** - Domain verification, link inspection

---

## Report Contents

The full PDF report (16 pages) includes:

1. **Executive Summary** - Key findings and statistics
2. **Understanding Phishing** - What it is and why it works
3. **Email Analysis Summary** - Overview of all analyzed emails
4. **Detailed Email Analysis** - Complete breakdown of each email
5. **Phishing Red Flags** - Checklist for identifying phishing
6. **Prevention Guidelines** - Do's and Don'ts
7. **Response Procedures** - What to do if you encounter phishing
8. **Conclusion** - Key takeaways and references

---

## Statistics

- **Phishing accounts for over 90%** of successful cyberattacks
- **193,407 phishing complaints** reported to FBI in 2024
- **Most reported crime type** to the FBI
- **Billions in losses** from Business Email Compromise attacks

---

## References

- FBI Internet Crime Complaint Center (IC3): https://www.ic3.gov
- Anti-Phishing Working Group (APWG): https://apwg.org
- CISA Phishing Guidance: https://www.cisa.gov/phishing
- FTC Report Fraud: https://reportfraud.ftc.gov
- Google Email Header Analyzer: https://toolbox.googleapps.com/apps/messageheader/

---

## Disclaimer

This report is created for educational purposes as part of a cybersecurity internship task. All email samples are fictional and created for training purposes. No real phishing emails were collected or distributed.

---

**Prepared by:** Purnendu Rai  
**Date:** March 23, 2026  
**Classification:** Security Awareness Document
