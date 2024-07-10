---
description: |
  AWS CLI command to get URL configuration details of a Lambda function in the AWS account.
command: |
  aws lambda get-function-url-config --function-name $name
items:
  - Lambda Function URL Configuration
services:
  - AWS Lambda
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/lambda/get-function-url-config.html
---

