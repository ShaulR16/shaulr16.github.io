---
description: |
  Creates a login profile for the specified IAM user, allowing them to access the AWS Management Console.
command: |
  aws iam create-login-profile --user-name <User Name> --password <Password>
items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Exploitation
references:
  - https://docs.aws.amazon.com/cli/latest/reference/iam/create-login-profile.html
---
