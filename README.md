# Task 2: Analyze a Phishing Email Sample

## Objective
The objective of this task is to identify phishing characteristics in a suspicious email sample by analyzing sender details, email content, URLs, and email headers.

---

## Tools Used

- Sample phishing email
- MXToolbox Email Header Analyzer
- Browser URL inspection
- Manual phishing analysis techniques

---

## Sample Phishing Email

**From:** support@paypa1-security.com

**Subject:** Urgent: Your Account Has Been Suspended

```
Dear Customer,

We detected unusual activity in your account. Your account has been temporarily suspended for security reasons.

To restore access immediately, please click the link below and verify your account information:

http://paypal-secure-verification-login.com/verify

Failure to verify your account within 24 hours will result in permanent account closure.

Thank you,
PayPal Security Team
```

---

## Phishing Indicators Identified

| Indicator | Description |
|-----------|-------------|
| Suspicious Sender | The sender domain "paypa1-security.com" impersonates PayPal using the number "1" instead of the letter "l". |
| Urgency | The email creates panic by claiming account suspension. |
| Threatening Language | Warns of permanent account closure within 24 hours. |
| Suspicious URL | The link does not belong to the official PayPal domain. |
| Spoofing | Attempts to impersonate PayPal. |
| Generic Greeting | Uses "Dear Customer" instead of the recipient's actual name. |
| Social Engineering | Manipulates the victim using fear and urgency. |
| Authentication Failure | SPF/DKIM/DMARC verification may fail or be absent. |

---

## Email Header Analysis

Email header analysis revealed possible spoofing attempts. The sender domain did not match the originating mail server. Authentication mechanisms such as SPF, DKIM, and DMARC were either missing or failed validation.

---

## Social Engineering Techniques Used

- Fear tactics
- Sense of urgency
- Authority impersonation
- Account suspension threats
- Psychological pressure

---

## Recommendations

- Never click suspicious links.
- Verify sender email addresses carefully.
- Inspect URLs before clicking.
- Enable multi-factor authentication.
- Report phishing emails immediately.
- Use email filtering and anti-phishing solutions.

---

## Conclusion

The analyzed email contains multiple phishing indicators, including spoofed sender information, malicious URLs, social engineering tactics, and urgency-based manipulation. This email should be classified as a phishing attempt and should not be trusted.

---
