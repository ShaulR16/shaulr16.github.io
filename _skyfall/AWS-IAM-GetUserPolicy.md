---
description: |
  AWS CLI command to get details about a specific policy attached to an IAM user.

  Command Reference:

  	User: replace_with_username
  	Policy Name: replace_with_policy_name

command: |
  aws iam get-user-policy --user-name replace_with_username --policy-name replace_with_policy_name

items:
  - User Policy Details
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/iam/get-user-policy.html
---