---
description: |
  AWS CLI command to get details about a specific version of an IAM policy.

  Command Reference:

  	Policy ARN: replace_with_policy_arn
  	Version ID: replace_with_version_id

command: |
  aws iam get-policy-version --policy-arn replace_with_policy_arn --version-id replace_with_version_id

items:
  - Policy Version Details
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/iam/get-policy-version.html
---