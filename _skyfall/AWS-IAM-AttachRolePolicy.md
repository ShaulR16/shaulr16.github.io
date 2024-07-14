---
description: |
  Attaches the specified managed policy to the specified IAM role.
command: |
  aws iam attach-role-policy --role-name <Role Name> --policy-arn <ARN>
items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Exploitation
references:
  - https://docs.aws.amazon.com/cli/latest/reference/iam/attach-role-policy.html
---
