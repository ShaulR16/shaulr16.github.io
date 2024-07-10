---
description: |
  AWS CLI command to get details of a specific version of a Lambda layer in the AWS account.
command: |
  aws lambda get-layer-version --layer-name $layer_name --version-number $version
items:
  - Lambda Layer Version Details
services:
  - AWS Lambda
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/lambda/get-layer-version.html
---

