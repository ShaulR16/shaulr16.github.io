---
description: |
  AWS CLI command to get the resource-based policy of a Lambda function in the AWS account.
command: |
  aws lambda get-policy --function-name $name
items:
  - Lambda Function Resource-Based Policy
services:
  - AWS Lambda
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/lambda/get-policy.html
---
