# 📧 Phishing Email Analysis Report

## 🚨 Email Overview

- **Sender Email:** account-update@amaz0n-support.com
- **Subject:** Action Required: Your Amazon Account Has Been Restricted
- **Date:** Tue, 6 Aug 2025
- **Attachment:** Amazon_Verification_Form.exe
- **Suspicious Link:** https://amaz0n-account-verify.com/login

---

## 🔍 Phishing Indicators

### 1. 🕵️‍♂️ **Spoofed Sender Email**
- Domain: `amaz0n-support.com` — not a valid Amazon domain.
- Uses a zero (`0`) instead of the letter `o` in "amazon" — classic **typosquatting** technique.

---

### 2. 🔗 **Suspicious URL**
- Text: "Follow the secure link"
- Actual URL: `https://amaz0n-account-verify.com/login`
- **Mismatched domain** — not Amazon.com
- The domain likely hosts a fake login page for stealing credentials.

---

### 3. 📎 **Malicious Attachment**
- File: `Amazon_Verification_Form.exe`
- Type: Executable file (.exe)
- Executable attachments from unknown sources are a **major red flag** — could install malware, keyloggers, or backdoors.

---

### 4. ⏱️ **Urgent/Threatening Language**
- "Your Amazon account will be suspended in 24 hours"
- Common tactic in phishing to induce panic and force immediate action.

---

### 5. 🙈 **Generic Greeting**
- The email begins with "Dear Customer" instead of the recipient's name.
- Legitimate companies like Amazon usually personalize their communication.

---

### 6. 📝 **False Sense of Trust**
- Includes an **official-sounding signature**:  
  `"Amazon Security Team"` and a legitimate-looking link: `https://www.amazon.com`
- However, this is just placed as plain text — doesn’t link to the real site.

---

## 🛡️ Conclusion

This email is a **clear phishing attempt** designed to:
- Trick the recipient into entering Amazon credentials on a fake website.
- Possibly infect the victim's device with malware via the `.exe` attachment.

---

## 🧰 Recommendations

- **Do not click** any links in the email.
- **Do not open** the `.exe` attachment.
- Report the email as phishing to your provider or security team.
- If already clicked, change Amazon credentials immediately and run a malware scan.

---

## 🧪 Tools Used for Analysis

- **Header Analyzer**: Google Admin Toolbox, MXToolbox
- **URL Scanner**: VirusTotal
- **Domain Check**: WHOIS Lookup
- **Link Hovering**: Manual inspection to reveal hidden URL

---

## 📸 Suggested Screenshots for Supporting Evidence

- Screenshot of the phishing email in inbox view
- Screenshot of link hover showing mismatch
- Screenshot of online header analysis (SPF/DKIM fail)
- Screenshot of VirusTotal scan result


