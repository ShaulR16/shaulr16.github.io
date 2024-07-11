---
description: |
  AWS IAM command to attach an inline policy to a specified user.
command: |
  aws iam put-user-policy --user-name example_username --policy-name example_name --policy-document file://AdminPolicy.json
items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Exploitation
references:
  - https://docs.aws.amazon.com/cli/latest/reference/iam/put-user-policy.html
---
