---
description: |
  AWS CLI command to list SSH public keys for a specific IAM user.

  Reference:

  	User: replace_with_username

command: |
  aws iam list-ssh-public-keys --user-name replace_with_username

items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/iam/list-ssh-public-keys.html
---