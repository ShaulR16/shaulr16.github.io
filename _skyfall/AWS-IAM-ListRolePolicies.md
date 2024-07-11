---
description: |
  AWS CLI command to list policies attached to an IAM role.

  Command Reference:

  	Role Name: replace_with_role_name

command: |
  aws iam list-role-policies --role-name replace_with_role_name

items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/iam/list-role-policies.html
---