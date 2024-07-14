---
description: |
  AWS CLI command to get details about a specific IAM policy.

  Reference:

  	Policy ARN: replace_with_policy_arn

command: |
  aws iam get-policy --policy-arn replace_with_policy_arn

items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/iam/get-policy.html
---
