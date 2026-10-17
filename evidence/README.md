# AWS Security Evidence

## Secure AWS Healthcare Document Portal

This evidence gallery documents security controls and validation tests performed in a personal AWS cloud security lab using fictional healthcare data.

### 1. Amazon S3 — Block Public Access

![Amazon S3 Block Public Access](Block%20public%20Access.png)

**Evidence:** Verified that Block all public access was enabled on the lab S3 bucket.

**Security Benefit:** Helps prevent unintended public exposure of stored documents.

**Result:** PASS — Public access blocking enabled.

---

### 2. AWS IAM — Least-Privilege Access

![AWS IAM Least-Privilege Policies](least-privilege%20IAM%20policy.png)

**Evidence:** Configured group-based IAM policies for restricted S3 access and limited CloudTrail and CloudWatch read-only permissions.

**Security Benefit:** Limits access to authorized operations and supports least-privilege security.

**Result:** PASS — Restricted policies configured.

---

### 3. AWS CloudTrail — Audit Event History

![AWS CloudTrail Audit Events](CloudTrail%20Audit%20Evidence.png)

**Evidence:** Reviewed AWS CloudTrail management events associated with IAM and AWS configuration activity.

**Security Benefit:** Supports security auditing and investigation of management API activity.

**Result:** PASS — Management events visible.

**Technical Note:** S3 object-level data-event logging was not separately configured.

---

### 4. Amazon CloudWatch — S3 Monitoring

![Amazon CloudWatch S3 Metrics](Cloud%20Wacth%20Monitoring.png)

**Evidence:** Viewed the Amazon S3 NumberOfObjects metric using a one-week time range.

**Security Benefit:** Provides storage metric visibility to support operational monitoring.

**Result:** PASS — S3 metric graph displayed.

---

### 5. Amazon S3 — Unauthorized Deletion Blocked

![S3 Unauthorized Deletion Blocked](../Unauthorized%20Deletion%20Block.png)

**Evidence:** Tested an unauthorized S3 object deletion using the restricted IAM user. AWS returned Access Denied.

**Security Benefit:** Demonstrates enforcement of restricted object permissions.

**Result:** PASS — Unauthorized deletion denied.

---

## Privacy and Scope

This is an educational project using fictional data only. Screenshots must be reviewed and sanitized before public publication. No production healthcare system or HIPAA certification is claimed.
