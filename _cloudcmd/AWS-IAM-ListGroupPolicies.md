---
description: |
  AWS CLI command to list policies attached to an IAM group.

  Reference:

  	Group: replace_with_group_name

command: |
  aws iam list-group-policies --group-name replace_with_group_name

items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/iam/list-group-policies.html
---