---
description: |
  AWS CLI command to get details about a specific policy attached to an IAM role.

  Command Reference:

  	Role Name: replace_with_role_name
  	Policy Name: replace_with_policy_name

command: |
  aws iam get-role-policy --role-name replace_with_role_name --policy-name replace_with_policy_name

items:
  - Role Policy Details
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/iam/get-role-policy.html
---
