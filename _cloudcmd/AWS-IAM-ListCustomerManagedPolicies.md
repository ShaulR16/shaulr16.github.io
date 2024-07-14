---
description: |
  AWS CLI command to list customer-managed policies in the AWS account.

command: |
  aws iam list-policies --scope Local | grep -A2 PolicyName

items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/iam/list-policies.html
---