# Phishing Red Flags Checklist

## Quick Reference Guide for Identifying Phishing Emails

---

## The 10 Most Common Phishing Red Flags

### 1. Suspicious Sender Domain
**What to Look For:**
- Typosquatting (e.g., paypa1.com, amaz0n.com)
- Extra words added (e.g., paypal-security.com)
- Completely unrelated domains
- Subdomain spoofing (e.g., paypal.com.scam-site.com)

**Example:**
```
❌ security@paypa1-secure.com
✅ service@paypal.com
```

**Risk Level:** CRITICAL

---

### 2. Urgency and Fear Tactics
**What to Look For:**
- "Your account will be suspended in 24 hours"
- "Immediate action required"
- "Final notice"
- "Legal action will be taken"
- "Act now or lose access"

**Why It's Dangerous:**
Urgency reduces critical thinking and pressures victims to act without verifying.

**Risk Level:** HIGH

---

### 3. Generic Greetings
**What to Look For:**
- "Dear Customer"
- "Dear User"
- "Dear Valued Member"
- "Hello" (without your name)
- No greeting at all

**Why It's Suspicious:**
Legitimate companies usually personalize emails with your actual name.

**Example:**
```
❌ "Dear Customer, your account needs verification"
✅ "Dear John Smith, here's your monthly statement"
```

**Risk Level:** MEDIUM

---

### 4. Suspicious Links
**What to Look For:**
- URLs that don't match the claimed sender
- URL shorteners (bit.ly, tinyurl, etc.)
- IP addresses instead of domain names
- Misspelled domain names

**How to Check:**
Hover over links (DON'T CLICK) to see the actual destination URL.

**Example:**
```
❌ Link text: "paypal.com" → Actual URL: "paypal-verification-scam.com"
✅ Link text: "amazon.com" → Actual URL: "amazon.com/order/12345"
```

**Risk Level:** CRITICAL

---

### 5. Unexpected Attachments
**What to Look For:**
- Files you didn't request
- Executable files (.exe, .scr, .bat)
- Office documents with macros (.docm, .xlsm)
- Password-protected archives
- ZIP files from unknown senders

**Dangerous File Types:**
- .exe, .scr, .bat, .cmd (executables)
- .js, .vbs, .ps1 (scripts)
- .docm, .xlsm, .pptm (macros)
- .zip, .rar, .7z (archives)

**Risk Level:** HIGH

---

### 6. Requests for Sensitive Information
**What to Look For:**
- Requests for passwords or PINs
- Requests for full Social Security Numbers
- Requests for credit card details
- Requests for bank account information
- "Verify your account" requests

**Remember:**
Legitimate companies NEVER ask for passwords or sensitive information via email.

**Example:**
```
❌ "Please confirm your password to continue"
❌ "Enter your SSN to verify your identity"
✅ "Log in to your account to update settings"
```

**Risk Level:** CRITICAL

---

### 7. Too Good To Be True Offers
**What to Look For:**
- "You've won a prize!"
- "Free gift card"
- "Lottery winnings"
- "Unexpected inheritance"
- "Get rich quick" schemes

**Remember:**
If it sounds too good to be true, it IS too good to be true.

**Example:**
```
❌ "Congratulations! You've won a $500 gift card! Click to claim"
❌ "You've inherited $1,000,000 from a distant relative"
```

**Risk Level:** HIGH

---

### 8. Poor Grammar and Spelling
**What to Look For:**
- Spelling mistakes
- Grammar errors
- Awkward phrasing
- Unusual word choices
- Inconsistent formatting

**Why It's Suspicious:**
Professional companies proofread their communications carefully.

**Example:**
```
❌ "We noticed suspicious activitys on your account"
❌ "Please verify you're identity immediately"
❌ "Your account will be suspend in 24 hours"
```

**Risk Level:** MEDIUM

---

### 9. Unusual Requests from Leadership
**What to Look For:**
- CEO asking for urgent wire transfer
- Executive requesting to bypass procedures
- "Confidential" requests without documentation
- Pressure to act without verification
- Requests outside normal business hours

**Why It's Dangerous:**
This is often a Business Email Compromise (BEC) attack - the most financially damaging type of phishing.

**Example:**
```
❌ "I'm in meetings, wire $50,000 to this account immediately"
❌ "Bypass normal approval - this is urgent and confidential"
```

**Risk Level:** CRITICAL

---

### 10. Email Authentication Failures
**What to Look For:**
- Missing DKIM signature
- SPF check failures
- DMARC failures
- "Sent from" domain doesn't match "From" address

**What These Mean:**
- **DKIM** - Verifies email hasn't been tampered with
- **SPF** - Verifies sender is authorized to send from domain
- **DMARC** - Policy for handling authentication failures

**Risk Level:** HIGH

---

## Quick Checklist

Before taking any action on an email, ask yourself:

- [ ] Do I recognize the sender's email address?
- [ ] Is the domain spelled correctly?
- [ ] Does the email address my by name?
- [ ] Am I being pressured to act urgently?
- [ ] Are there spelling or grammar mistakes?
- [ ] Does the link URL match the claimed sender?
- [ ] Was I expecting this email/attachment?
- [ ] Is the request unusual or bypassing normal procedures?
- [ ] Does the offer seem too good to be true?
- [ ] Do email authentication checks (DKIM/SPF) pass?

**If you answered YES to any question, be suspicious!**

---

## Remember

> "When in doubt, don't click. Verify through a trusted channel."

---

**Document Version:** 1.0  
**Last Updated:** March 22, 2026  
**Classification:** Security Awareness Material
