# AWS Security Evidence

This folder documents the security controls and test results from my Secure AWS Healthcare Document Portal personal lab.

## Verified Security Tests

| Test | Result | Security Principle |
| --- | --- | --- |
| Authorized S3 document download | PASS — Allowed | Least-privilege access |
| Unauthorized S3 object deletion | PASS — Access Denied | Restricted permissions |
| CloudTrail IAM user event lookup | PASS — Management events found | Security auditing |

## Additional Security Controls
- IAM user and root MFA enabled
- IAM group-based restricted S3 permissions
- S3 Block Public Access enabled
- S3 versioning enabled
- Default SSE-S3 encryption enabled
- CloudWatch S3 NumberOfObjects metric reviewed
- AWS $5 monthly budget configured

## Screenshot Safety
Only sanitized screenshots should be published. Remove AWS account IDs, account-specific URLs, emails, full ARNs, credentials, MFA codes, and sensitive data. All sample healthcare documents contain fictional information.

## Audit Logging Note
CloudTrail Event history was used to review management events. S3 object-level data-event logging was not separately configured.
