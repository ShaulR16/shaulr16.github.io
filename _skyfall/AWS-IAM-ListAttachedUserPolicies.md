---
description: |
  AWS IAM command to list attached user policies for a specified user.
command: |
  aws iam list-attached-user-policies --user-name user-name
items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/iam/list-attached-user-policies.html
---
