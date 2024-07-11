---
description: |
  AWS IAM command to list policy versions for a specified policy.
command: |
  aws iam list-policy-versions --policy-arn policy-arn
items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/iam/list-policy-versions.html
---
