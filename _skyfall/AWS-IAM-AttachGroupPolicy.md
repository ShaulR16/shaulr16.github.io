---
description: |
  Attaches the specified managed policy to the specified IAM group.
command: |
  aws iam attach-group-policy --group-name <Group Name> --policy-arn <ARN>
items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Exploitation
references:
  - https://docs.aws.amazon.com/cli/latest/reference/iam/attach-group-policy.html
---
