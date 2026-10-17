# LinkedIn and resume wording

## LinkedIn project entry

**Secure AWS Healthcare Document Portal | AWS Cloud Security Lab**  
Personal Project | October 2026

Built a hands-on AWS security lab modeling secure document storage for a fictional healthcare office. Configured IAM user MFA, group-based least-privilege policies, and Amazon S3 with blocked public access, versioning, and SSE-S3 encryption. Validated permitted document downloads and denied deletion attempts. Reviewed CloudTrail management events and visualized S3 storage metrics with CloudWatch. Set a $5 monthly AWS budget for cost awareness. Documented the architecture and security test evidence.

**Skills:** AWS IAM · Amazon S3 · CloudTrail · CloudWatch · AWS Budgets · MFA · Least Privilege · Encryption at Rest · Cloud Security

## Resume bullets — choose one or two

- Built an AWS cloud-security lab with IAM MFA, group-based least-privilege JSON policies, and protected S3 storage using Block Public Access, SSE-S3 encryption, and versioning.
- Validated IAM access controls by confirming authorized S3 document retrieval and blocked deletion; reviewed CloudTrail management events and graphed S3 storage metrics in CloudWatch.

## Interview answer

“I built a personal AWS security lab around a fictional healthcare document. I configured IAM users, MFA, and restricted group policies, secured an S3 bucket with encryption and blocked public access, and tested the results. The user could download an approved document but received Access Denied when attempting to delete it. I also configured read-only CloudTrail and CloudWatch access to review management activity and graph S3 storage metrics. One lesson was that a policy change accidentally replaced an existing policy, so I restored it and separated permissions into purpose-specific policies. That reinforced the importance of verifying every security change.”
