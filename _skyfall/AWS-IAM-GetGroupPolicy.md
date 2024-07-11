---
description: |
  AWS IAM command to get a group policy for a specified group and policy.
command: |
  aws iam get-group-policy --group-name group-name --policy-name policy-name
items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/iam/get-group-policy.html
---
