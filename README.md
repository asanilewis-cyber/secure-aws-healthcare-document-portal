# Screenshot evidence checklist

**Do not publish unredacted AWS console screenshots.** Remove account ID, account-specific URLs, email, usernames where sensitive, full ARNs, secrets, passwords, MFA codes, and private object contents. Use only fictional data.

| Filename to add | What screenshot should show | Email subject |
|---|---|---|
| `01-iam-mfa.png` | IAM user MFA enabled | AWS Lab \| IAM User MFA Enabled |
| `02-iam-three-policies.png` | Three distinct group inline policies | AWS Lab \| IAM Least-Privilege Policies |
| `03-s3-public-access.png` | Block all public access On | AWS Lab \| S3 Public Access Blocked |
| `04-s3-encryption-versioning.png` | SSE-S3 and versioning enabled | AWS Lab \| S3 Encryption and Versioning |
| `05-authorized-download.png` | Approved object listing or download evidence | AWS Day 6 \| Authorized S3 Access |
| `06-denied-deletion.png` | Actual Access Denied after delete attempt | AWS Day 6 \| Unauthorized Deletion Blocked |
| `07-cloudtrail-events.png` | CloudTrail management events visible | AWS Day 6 \| CloudTrail Audit Evidence |
| `08-cloudwatch-objects.png` | S3 NumberOfObjects graph | AWS Day 5 \| CloudWatch S3 Monitoring |
| `09-budget.png` | $5 monthly AWS budget | AWS Lab \| Cost Governance |

### Email body template for each screenshot

**Project:** Secure AWS Healthcare Document Portal  
**Evidence:** [Name of screenshot]  
**Objective:** [What security control or AWS feature is being validated]  
**Action:** [Exactly what you did]  
**Observed result:** [What AWS actually showed]  
**Security relevance:** [Why it matters for access control, encryption, monitoring, or cost]  
**Skills demonstrated:** [Relevant AWS services and security concepts]  

Only report verified results. Do not claim S3 object-level events are present in CloudTrail Event history unless separately configured and observed.
