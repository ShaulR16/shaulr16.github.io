---
description: |
  AWS CLI command to get invocation configurations of a Lambda function in the AWS account.
command: |
  aws lambda get-function-event-invoke-config --function-name $name
items:
  - Lambda Function Invocation Configurations
services:
  - AWS Lambda
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/lambda/get-function-event-invoke-config.html
---

