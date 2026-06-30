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

**From:** security-alert@sbi-verification.in

**Subject:** URGENT: Your SBI Account Has Been Temporarily Blocked

```text
Dear Customer,

We have detected unusual activity in your State Bank of India account. As a security precaution, your online banking access has been temporarily suspended.

To reactivate your account immediately, please verify your account details by clicking the secure link below:

http://sbi-secure-account-verification.in/login

Failure to verify your account within the next 12 hours will result in permanent suspension of your Internet Banking services.

Please do not reply to this email as this is an automated notification.

Thank you,
SBI Security Department
State Bank of India
```

---

## Phishing Indicators Identified

| Indicator | Description |
|-----------|-------------|
| Suspicious Sender | The sender domain "sbi-verification.in" impersonates the State Bank of India. |
| Urgency | The email creates panic by claiming account suspension. |
| Threatening Language | Warns of permanent account suspension within 12 hours. |
| Suspicious URL | The link does not belong to the official SBI website. |
| Spoofing | Attempts to impersonate State Bank of India. |
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
