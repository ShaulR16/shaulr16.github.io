---
description: |
  Updates the password for the specified IAM user.
command: |
  aws iam update-login-profile --user-name <User Name> --password <Password>
items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Exploitation
references:
  - https://docs.aws.amazon.com/cli/latest/reference/iam/update-login-profile.html
---
