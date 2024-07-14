---
description: |
  AWS CLI command to get details about a specific version of an IAM policy.

  Reference:

  	Policy ARN: replace_with_policy_arn
  	Version ID: replace_with_version_id

command: |
  aws iam get-policy-version --policy-arn replace_with_policy_arn --version-id replace_with_version_id

items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/iam/get-policy-version.html
---