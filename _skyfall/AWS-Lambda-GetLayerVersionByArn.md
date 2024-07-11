---
description: |
  AWS CLI command to get the version details of a Lambda layer by ARN in the AWS account.
command: |
  aws lambda get-layer-version-by-arn --arn $layer_arn
items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/lambda/get-layer-version-by-arn.html
---
