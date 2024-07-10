---
description: |
  AWS CLI command to list SSH public keys for a specific IAM user.

  Command Reference:

  	User: replace_with_username

command: |
  aws iam list-ssh-public-keys --user-name replace_with_username

items:
  - SSH Public Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/iam/list-ssh-public-keys.html
---