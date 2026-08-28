# 🔐 Secure AWS Cloud Architecture

A hands-on AWS cloud security project demonstrating secure infrastructure design, network segmentation, identity and access management, encryption, logging and threat detection.

## 🎯 Project Objectives

- Design a secure AWS network using Amazon VPC
- Implement public and private subnet architecture
- Apply least-privilege IAM
- Secure EC2 infrastructure
- Restrict administrative access
- Encrypt EBS volumes using AWS KMS
- Enable AWS CloudTrail logging
- Configure Amazon GuardDuty
- Develop a basic cloud threat model

---

## ☁️ AWS Services

| Service | Purpose |
|---|---|
| Amazon VPC | Network isolation and segmentation |
| Amazon EC2 | Compute infrastructure |
| IAM | Identity and access management |
| Security Groups | Network access control |
| AWS KMS | Encryption key management |
| Amazon EBS | Encrypted storage |
| AWS CloudTrail | API activity logging |
| Amazon GuardDuty | Threat detection |

---

## 🏗️ Architecture

The environment is designed around a segmented VPC containing public and private network areas.

```text
                         INTERNET
                            │
                            ▼
                  ┌──────────────────┐
                  │ Internet Gateway │
                  └────────┬─────────┘
                           │
                  ┌────────▼─────────┐
                  │     AWS VPC      │
                  │                  │
                  │ ┌──────────────┐ │
                  │ │ Public Subnet│ │
                  │ │              │ │
                  │ │    EC2       │ │
                  │ └──────┬───────┘ │
                  │        │         │
                  │ ┌──────▼───────┐ │
                  │ │Private Subnet│ │
                  │ │              │ │
                  │ │ Applications │ │
                  │ └──────────────┘ │
                  └──────────────────┘
                           
              ┌─────────────────────────┐
              │ AWS Security Services   │
              │                         │
              │ IAM | KMS | CloudTrail  │
              │ GuardDuty               │
              └─────────────────────────┘# secure-aws-cloud-architecture
Secure AWS cloud architecture demonstrating VPC, EC2, IAM, KMS, CloudTrail and GuardDuty.

