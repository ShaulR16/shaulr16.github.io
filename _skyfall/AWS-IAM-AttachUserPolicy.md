---
description: |
  Attaches the specified managed policy to the specified IAM user.
command: |
  aws iam attach-user-policy --user-name <User Name> --policy-arn <ARN>
items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Exploitation
references:
  - https://docs.aws.amazon.com/cli/latest/reference/iam/attach-user-policy.html
---
