---
description: |
  AWS CLI command to get details about a specific IAM policy.

  Command Reference:

  	Policy ARN: replace_with_policy_arn

command: |
  aws iam get-policy --policy-arn replace_with_policy_arn

items:
  - Policy Details
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/iam/get-policy.html
---
