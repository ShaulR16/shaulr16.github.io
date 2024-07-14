---
description: |
  Creates a new access key for the specified IAM user.
command: |
  aws iam create-access-key --user-name <user-name>
items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - PostExp
references:
  - https://docs.aws.amazon.com/cli/latest/reference/iam/create-access-key.html
---
