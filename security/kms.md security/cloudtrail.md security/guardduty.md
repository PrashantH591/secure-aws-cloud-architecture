kms.md
# AWS KMS

AWS Key Management Service is used to manage encryption keys.

## Objective

Protect data stored on Amazon EBS volumes using encryption.

## Security Benefits

- Encryption at rest
- Centralised key management
- Controlled key access
- Improved protection of stored data

## Implementation

Document the KMS key configuration actually used in the AWS environment.

## Validation

Confirm that the relevant EBS volumes are encrypted.

cloudtrail.md

# AWS CloudTrail

AWS CloudTrail provides visibility into AWS API activity.

## Objective

Use CloudTrail to support auditing, monitoring and security investigations.

## Use Cases

- Investigate API activity
- Identify changes to AWS resources
- Support security investigations
- Maintain an audit trail

## Security Considerations

- Protect CloudTrail logs
- Consider appropriate retention
- Restrict access to logs
- Monitor important administrative events

## Validation

Document the CloudTrail configuration actually implemented.

guardduty.md

# Amazon GuardDuty

Amazon GuardDuty provides managed threat detection for AWS environments.

## Objective

Detect suspicious activity and potential security threats.

## Investigation Process

1. Identify a finding
2. Determine affected resource
3. Review relevant activity
4. Assess whether the activity is expected
5. Contain the issue when required
6. Document the investigation
7. Apply preventive controls

## Validation

Document the GuardDuty configuration and authorised testing performed.
