---
description: |
  AWS CLI command to get the download link for the code of a Lambda function in the AWS account.
command: |
  aws lambda get-function --function-name $name --query 'Code.Location'
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
