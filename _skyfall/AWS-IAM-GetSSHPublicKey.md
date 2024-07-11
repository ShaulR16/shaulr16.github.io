---
description: |
  AWS CLI command to get details about an SSH public key for a specific IAM user.

  Command Reference:

  	User: replace_with_username
  	SSH Public Key ID: replace_with_ssh_public_key_id

command: |
  aws iam get-ssh-public-key --user-name replace_with_username --encoding PEM --ssh-public-key-id replace_with_ssh_public_key_id

items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/iam/get-ssh-public-key.html
---

