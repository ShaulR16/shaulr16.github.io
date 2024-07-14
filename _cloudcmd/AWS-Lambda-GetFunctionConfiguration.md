---
description: |
  AWS CLI command to get configuration details of a Lambda function in the AWS account.
command: |
  aws lambda get-function-configuration --function-name $name
items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/lambda/get-function-configuration.html
---
