---
description: |
  AWS CLI command to get details of a specific Lambda function in the AWS account.
command: |
  aws lambda get-function --function-name $name
items:
  - Lambda Function Details
services:
  - AWS Lambda
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/lambda/get-function.html
---