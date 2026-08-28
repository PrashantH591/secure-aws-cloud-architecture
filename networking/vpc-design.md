# VPC Design

## Objective

Design a secure AWS network using public and private subnet concepts.

## Network Components

- Amazon VPC
- Public subnet
- Private subnet
- Route tables
- Internet Gateway
- Security Groups

## Security Design

The network is designed to minimise unnecessary exposure of internal workloads.

Public-facing resources should only be exposed when required.

Private workloads should not be directly accessible from the public internet.

## Security Considerations

- Network segmentation
- Restricted inbound access
- Controlled outbound access
- Security Groups
- Least-privilege network access
- Restricted administrative access

## Validation

Document the actual VPC configuration and testing performed in your AWS environment.
