---
description: |
  AWS CLI command to get the policy of a specific version of a Lambda layer in the AWS account.
command: |
  aws lambda get-layer-version-policy --layer-name $layer_name --version-number $version
items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/lambda/get-layer-version-policy.html
---

