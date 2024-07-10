---
description: |
  AWS CLI command to get details about a specific IAM role.

  Command Reference:

  	Role Name: replace_with_role_name

command: |
  aws iam get-role --role-name replace_with_role_name

items:
  - Role Details
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/iam/get-role.html
---