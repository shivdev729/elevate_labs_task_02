# 📄 Task 2 of the Elevate Labs Cybersecurity Internship
# Phishing Email Analysis Report


- __Sample subject__ - _Claim Your Free ARB Airdrop from Binance!_
- __Sample source__ - _https://github.com/rf-peixoto/phishing_pot_
- __Sample name__ - _sample-1006.eml_

![Sample phishing mail](https://github.com/shivdev729/elevate_labs_task_02/blob/main/p1.JPG)
---

## 1. Sender Email Address
- **Content** BinanceMail2@onmailcloud.onmicrosoft.com (most likely spoofed)
- **Phishing Indicator**: The brand name **“Binance”** is crafted using **Unicode homoglyphs** (e.g., Greek letters such as `Β` instead of `B`), a known tactic to impersonate legitimate domains while bypassing security filters.

---

## 2. Email Header Discrepancies
- **Tools used**: MXtoolbox email header analyzer (https://mxtoolbox.com/EmailHeaders.aspx)
- **Header Analysis**:
  - **No DMARC record found** for the sending domain.
  - SPF/DKIM status is likely **failing or absent**, as headers are spoofed and don't match a legitimate Binance mail server.
- **Phishing Indicator**: Missing **DMARC** (Domain-based Message Authentication, Reporting, and Conformance) is a strong sign the domain is not properly secured and may be forged.
  
![Headers#1](https://github.com/shivdev729/elevate_labs_task_02/blob/main/p6.JPG)
![Headers#2](https://github.com/shivdev729/elevate_labs_task_02/blob/main/p7.JPG)
![Headers#3](https://github.com/shivdev729/elevate_labs_task_02/blob/main/p8.JPG)
![Headers#4](https://github.com/shivdev729/elevate_labs_task_02/blob/main/p9.JPG)
---

## 3. Suspicious Links
- **Phishing Link**: https://click.pstmrk.it/3s/sweedbuy.com%2Fblog%2F/ahc/k_CuAQ/AQ/44a54f89-410d-4729-b21c-32c30d6eb945/1/qOoKiS9V1s?/23687658rodrigofp
- The **actual URL or joining link is most probably a phishing link with the domain sweedbuy indicating a shopping website**, however, currently the target site is  **unavailable**.
- **Phishing Indicator**: This is a common **spoofing technique** to evade trick recipients into visiting malicious sites.

  
![Suspicious Links](https://github.com/shivdev729/elevate_labs_task_02/blob/main/p4.JPG)
---

## 4. Urgent or Threatening Language
- **Examples**:
  - “The first 2500 to apply can receive up to 80,000 ARB (~USD $80,000)”
  - “Limited-time airdrop”
  - “First come, first served”
- **Phishing Indicator**: Use of urgency and exclusivity to prompt impulsive behavior.

![Urgent language](https://github.com/shivdev729/elevate_labs_task_02/blob/main/p3.JPG)
---

## 5. Spelling and Grammar Issues
- Numerous grammatical errors and visual manipulation via **hidden characters and abnormal spacing**:
  - “pla‌‌‌‌‌‌tf‌‌‌‌‌‌o‌‌‌‌‌‌rm” instead of “platform”
  - “el‌‌‌‌‌‌i‌‌‌‌‌‌gib‌‌‌‌‌‌i lity” instead of “eligibility”
  - “a‌‌p‌‌p Ιy” instead of “apply” (note the use of Greek capital iota `Ι`)
- **Phishing Indicator**: These formatting tricks are designed to **evade filters** and confuse human readers.

  
![Spelling Issues](https://github.com/shivdev729/elevate_labs_task_02/blob/main/p2.JPG)
---

## 6. Spoofed Branding
- Brand Impersonated: **Binance**
- **Spoofing Method**: Use of visually similar but invalid characters to imitate real branding.
- **Phishing Indicator**: Homoglyphs and similar tactics are standard in phishing schemes involving known companies.


![Spoofed branding](https://github.com/shivdev729/elevate_labs_task_02/blob/main/p5.JPG)
---

## 7. Absence of Legitimate Email Elements
- No business contact information
- No privacy notice or unsubscribe link
- **Phishing Indicator**: Violates norms of legitimate corporate communications

---

__Submitted by__ :- Shivang Shukla
