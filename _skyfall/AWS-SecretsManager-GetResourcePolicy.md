---
description: |
  Retrieves the resource-based policy attached to the secret.
command: |
  aws secretsmanager get-resource-policy --secret-id ID
items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/secretsmanager/get-resource-policy.html
---
