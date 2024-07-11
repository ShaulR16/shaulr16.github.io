---
description: |
  Describes a secret in AWS Secrets Manager.
command: |
  aws secretsmanager describe-secret --secret-id name
items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/secretsmanager/describe-secret.html
---
