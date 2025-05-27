# elevate_labs_task_02
Task 2 of the Elevate Labs Cybersecurity Internship

# 📄 Phishing Email Analysis Report

## Subject Line
_Claim Your Free ARB Airdrop from Binance!_ (Assumed)

---

## 1. Sender Email Address
- **Not Provided** (Required for full analysis. Based on content, likely spoofed or obfuscated)
- **Phishing Indicator**: The brand name **“Binance”** is crafted using **Unicode homoglyphs** (e.g., Greek letters such as `Β` instead of `B`), a known tactic to impersonate legitimate domains while bypassing security filters.

---

## 2. Email Header Discrepancies
- **Header Analysis**:
  - **No DMARC record found** for the sending domain.
  - SPF/DKIM status is likely **failing or absent**, as headers are spoofed and don't match a legitimate Binance mail server.
- **Phishing Indicator**: Missing **DMARC** (Domain-based Message Authentication, Reporting, and Conformance) is a strong sign the domain is not properly secured and may be forged.

---

## 3. Suspicious Links
- **Obfuscated Link**: Appears as reversed text:  
  `‮!eer‌‌‌‌‌‌f y‌‌‌‌‌‌l‌‌‌‌‌‌et‌‌‌‌‌‌e‌‌‌‌‌‌l‌‌‌‌‌‌‌‌‌‌‌‌pm‌‌‌‌‌‌o‌‌‌‌‌‌c`  
  When reversed, this reads: **“completely free!”**
- The **actual URL or joining link is hidden**, and based on context, it likely redirects to a **phishing site**.
- **Phishing Indicator**: This is a common **obfuscation technique** to evade link scanners and trick recipients into visiting malicious sites.

---

## 4. Urgent or Threatening Language
- **Examples**:
  - “The first 2500 to apply can receive up to 80,000 ARB (~USD $80,000)”
  - “Limited-time airdrop”
  - “First come, first served”
- **Phishing Indicator**: Use of urgency and exclusivity to prompt impulsive behavior.

---

## 5. Spelling and Grammar Issues
- Numerous grammatical errors and visual manipulation via **hidden characters and abnormal spacing**:
  - “pla‌‌‌‌‌‌tf‌‌‌‌‌‌o‌‌‌‌‌‌rm” instead of “platform”
  - “el‌‌‌‌‌‌i‌‌‌‌‌‌gib‌‌‌‌‌‌i lity” instead of “eligibility”
  - “a‌‌p‌‌p Ιy” instead of “apply” (note the use of Greek capital iota `Ι`)
- **Phishing Indicator**: These formatting tricks are designed to **evade filters** and confuse human readers.

---

## 6. Spoofed Branding
- Brand Impersonated: **Binance**
- **Spoofing Method**: Use of visually similar but invalid characters to imitate real branding.
- **Phishing Indicator**: Homoglyphs and similar tactics are standard in phishing schemes involving known companies.

---

## 7. Absence of Legitimate Email Elements
- No business contact information
- No privacy notice or unsubscribe link
- **Phishing Indicator**: Violates norms of legitimate corporate communications

---


