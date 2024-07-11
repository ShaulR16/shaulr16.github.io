---
description: |
  AWS CLI command to get login profile information for a specific IAM user.

  Command Reference:

  	User: replace_with_username

command: |
  aws iam get-login-profile --user-name replace_with_username

items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/iam/get-login-profile.html
---
