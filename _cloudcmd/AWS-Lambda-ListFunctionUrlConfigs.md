---
description: |
  AWS CLI command to list URL configurations for a Lambda function in the AWS account.
command: |
  aws lambda list-function-url-configs --function-name $name
items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/lambda/list-function-url-configs.html
---

