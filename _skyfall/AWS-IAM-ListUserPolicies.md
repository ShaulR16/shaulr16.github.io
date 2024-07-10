---
description: |
  AWS CLI command to list policies attached to a specific IAM user.

  Command Reference:

  	User: replace_with_username

command: |
  aws iam list-user-policies --user-name replace_with_username

items:
  - IAM Roles & Policies
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/iam/list-user-policies.html
---
