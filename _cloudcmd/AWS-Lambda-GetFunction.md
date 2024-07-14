---
description: |
  AWS CLI command to get details of a specific Lambda function in the AWS account.
command: |
  aws lambda get-function --function-name $name
items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/lambda/get-function.html
---