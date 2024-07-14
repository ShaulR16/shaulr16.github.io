---
description: |
  Retrieves a summary of IAM account details.
command: |
  aws iam get-account-summary | tee account-summary.json
items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/iam/get-account-summary.html
---
