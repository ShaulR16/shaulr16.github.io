---
description: |
  AWS CLI command to get configuration details of a Lambda function in the AWS account.
command: |
  aws lambda get-function-configuration --function-name $name
items:
  - Lambda Function Configuration
services:
  - AWS Lambda
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/lambda/get-function-configuration.html
---
