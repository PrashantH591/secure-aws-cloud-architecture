# AWS Cloud Threat Model

## Assets

- EC2 instances
- EBS data
- IAM identities
- VPC infrastructure
- CloudTrail logs
- Security configuration

## Threats

### 1. Unauthorised Access

**Risk:** An attacker gains access to cloud resources.

**Controls:**
- IAM least privilege
- MFA
- Restricted permissions
- Strong authentication

### 2. Exposed SSH

**Risk:** Publicly exposed SSH could increase attack surface.

**Controls:**
- Restrict SSH source IPs
- Avoid unnecessary public exposure
- Use secure administration methods

### 3. Data Exposure

**Risk:** Sensitive data could be accessed without authorisation.

**Controls:**
- EBS encryption
- AWS KMS
- IAM permissions

### 4. Suspicious API Activity

**Risk:** Unauthorised AWS API calls.

**Controls:**
- AWS CloudTrail
- IAM
- GuardDuty

## Security Principles

- Confidentiality
- Integrity
- Availability
- Least privilege
- Defence in depth
- Network segmentation
