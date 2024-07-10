---
description: |
  AWS CLI command to list versions of a Lambda function in the AWS account.
command: |
  aws lambda list-versions-by-function --function-name $name
items:
  - Lambda Function Versions
services:
  - AWS Lambda
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/lambda/list-versions-by-function.html
---

