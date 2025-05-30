# First_Credential_Report
This repository contains my first AWS IAM Credential Report, as well as any subsequent. It is generated as part of my hands-on security auditing practice. This is a foundational exercise in identifying and understanding IAM user risk exposure across an AWS account.

---

# Purpose
The goal of this report is to:

- Understand the IAM **Credential Report** structure.
- Identify potential security risks and compliance issues with user credentials.
- Practice safe auditing and visibility into access management on AWS.
---

# File Included

- `credential-report.csv`: The raw IAM Credential Report downloaded from the AWS Console.
---
# Key Audit Checks Performed

This report includes data on:

- Password last used
- Access key usage
- MFA status
- Root account status
- Account age and activity

This allows me to identify things like:

- Stale access keys
- Missing MFA on user accounts
- Root account usage 
- Inactive credentials still enabled

---
# What I Learned

- How to generate and interpret AWS credential reports.
- The security value of regular user access audits.
- The importance of least privilege and credential hygiene in cloud environments.

---
# Next Steps

- Automate this credential auditing with **Python + boto3**.
- Build a security alerting system using **AWS Lambda** and **CloudWatch**.
- Write IAM policies that enforce secure configurations at scale.

---
# Disclaimer

This report was generated in a **test AWS environment** for learning and development purposes only. No sensitive or production-level data is included.

