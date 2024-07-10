---
description: |
  AWS CLI command to list signing certificates for a specific IAM user.

  Command Reference:

  	User: replace_with_username

command: |
  aws iam list-signing-certificates --user-name replace_with_username

items:
  - Signing Certificates
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/iam/list-signing-certificates.html
---
