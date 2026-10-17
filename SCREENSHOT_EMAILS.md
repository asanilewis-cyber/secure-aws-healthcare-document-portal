# Screenshot email subjects and bodies

Use only after checking each screenshot matches the stated result. Redact account IDs, full ARNs, emails, sign-in URLs, and any sensitive details.

## 01. IAM User MFA Enabled
**Subject:** AWS Portfolio | IAM User MFA Enabled

**Body:**

**Project:** Secure AWS Healthcare Document Portal  
**Type:** Personal AWS cloud-security lab with fictional data  

Verified multi-factor authentication was enabled for the restricted IAM user. This adds a second authentication factor to protect console access.

**Skills demonstrated:** IAM, MFA, account security.

**Evidence:** Attached sanitized AWS console screenshot.

---

## 02. IAM Least-Privilege Policies
**Subject:** AWS Portfolio | IAM Least-Privilege Policies

**Body:**

**Project:** Secure AWS Healthcare Document Portal  
**Type:** Personal AWS cloud-security lab with fictional data  

Verified three separate group inline policies for restricted S3 access, read-only CloudTrail lookup, and read-only CloudWatch metrics.

**Skills demonstrated:** IAM, JSON policies, least privilege.

**Evidence:** Attached sanitized AWS console screenshot.

---

## 03. S3 Public Access Blocked
**Subject:** AWS Portfolio | S3 Public Access Blocked

**Body:**

**Project:** Secure AWS Healthcare Document Portal  
**Type:** Personal AWS cloud-security lab with fictional data  

Verified Block all public access was enabled on the fictional healthcare document bucket.

**Skills demonstrated:** S3, access controls, secure storage.

**Evidence:** Attached sanitized AWS console screenshot.

---

## 04. S3 Encryption and Versioning
**Subject:** AWS Portfolio | S3 Encryption and Versioning

**Body:**

**Project:** Secure AWS Healthcare Document Portal  
**Type:** Personal AWS cloud-security lab with fictional data  

Verified SSE-S3 default encryption and S3 bucket versioning were enabled.

**Skills demonstrated:** S3, encryption at rest, versioning.

**Evidence:** Attached sanitized AWS console screenshot.

---

## 05. Authorized S3 Access
**Subject:** AWS Portfolio | Authorized S3 Access

**Body:**

**Project:** Secure AWS Healthcare Document Portal  
**Type:** Personal AWS cloud-security lab with fictional data  

Successfully downloaded the fictional healthcare test document using the restricted IAM user.

**Skills demonstrated:** S3, GetObject, authorization testing.

**Evidence:** Attached sanitized AWS console screenshot.

---

## 06. Unauthorized Deletion Blocked
**Subject:** AWS Portfolio | Unauthorized Deletion Blocked

**Body:**

**Project:** Secure AWS Healthcare Document Portal  
**Type:** Personal AWS cloud-security lab with fictional data  

Attempted to delete the fictional test document and received Access Denied. The object was preserved.

**Skills demonstrated:** S3, least privilege, negative testing.

**Evidence:** Attached sanitized AWS console screenshot.

---

## 07. CloudTrail Audit Evidence
**Subject:** AWS Portfolio | CloudTrail Audit Evidence

**Body:**

**Project:** Secure AWS Healthcare Document Portal  
**Type:** Personal AWS cloud-security lab with fictional data  

Retrieved CloudTrail management events associated with the IAM user, showing recorded AWS account activity. This does not demonstrate S3 object-level data-event logging.

**Skills demonstrated:** CloudTrail, audit review, IAM.

**Evidence:** Attached sanitized AWS console screenshot.

---

## 08. CloudWatch S3 Monitoring
**Subject:** AWS Portfolio | CloudWatch S3 Monitoring

**Body:**

**Project:** Secure AWS Healthcare Document Portal  
**Type:** Personal AWS cloud-security lab with fictional data  

Viewed the NumberOfObjects metric for the lab S3 bucket over a one-week period; the graph showed one object.

**Skills demonstrated:** CloudWatch, metrics, S3.

**Evidence:** Attached sanitized AWS console screenshot.

---

## 09. Cost Governance
**Subject:** AWS Portfolio | Cost Governance

**Body:**

**Project:** Secure AWS Healthcare Document Portal  
**Type:** Personal AWS cloud-security lab with fictional data  

Verified a $5 monthly AWS budget was configured for cost awareness. The budget is not a hard spending cap.

**Skills demonstrated:** AWS Budgets, cloud cost governance.

**Evidence:** Attached sanitized AWS console screenshot.

---
