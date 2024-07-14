---
description: |
  Returns a set of temporary security credentials that you can use to access AWS resources.
command: |
  aws sts assume-role --role-arn <Role ARN> --role-session-name AssumeRole
items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Exploitation
references:
  - https://docs.aws.amazon.com/cli/latest/reference/sts/assume-role.html
---
