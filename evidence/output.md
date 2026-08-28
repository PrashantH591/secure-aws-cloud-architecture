# Project Evidence & Output

## Current Project Status

This repository documents a secure cloud architecture based on AWS security and networking principles.

The project is currently being developed as a practical learning and architecture exercise.

## Architecture Components

The proposed architecture covers:

- Amazon VPC
- Public and private subnet design
- Security Groups
- Amazon EC2
- IAM least-privilege access
- AWS KMS encryption
- AWS CloudTrail logging
- Amazon GuardDuty threat detection

## Network Design

Proposed VPC:

```text
VPC
10.0.0.0/16
│
├── Public Subnet
│   └── EC2
│
└── Private Subnet
    └── Internal workloads
