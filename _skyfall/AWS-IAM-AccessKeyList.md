---
description: |
  AWS CLI command to list IAM access keys for a user. IAM access keys are credentials used for programmatic access to AWS services. It's important to monitor and rotate access keys regularly to maintain security and prevent unauthorized access.

  Reference:

  	User: replace_with_username

command: |
  aws iam list-access-keys --user-name replace_with_username

items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/iam/list-access-keys.html
---