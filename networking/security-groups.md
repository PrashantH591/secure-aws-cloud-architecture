# Security Groups

Security Groups provide instance-level network access control for AWS resources.

## Objectives

- Allow only required traffic
- Minimise exposed ports
- Restrict administrative access
- Follow least-privilege principles

## Example Rules

| Protocol | Port | Source | Purpose |
|---|---:|---|---|
| TCP | 22 | Approved IP only | SSH administration |
| TCP | 80 | Required sources | HTTP |
| TCP | 443 | Required sources | HTTPS |

## SSH Security

SSH should never be unnecessarily exposed to the entire internet.

Where possible, administrative access should be restricted to approved IP ranges or controlled management mechanisms.

## Validation

Document the Security Group rules actually implemented and tested.
