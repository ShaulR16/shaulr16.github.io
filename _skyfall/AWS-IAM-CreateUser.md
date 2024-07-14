---
description: |
  Creates a new IAM user.
command: |
  aws iam create-user --user-name <User Name>
items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Exploitation
references:
  - https://docs.aws.amazon.com/cli/latest/reference/iam/create-user.html
---
