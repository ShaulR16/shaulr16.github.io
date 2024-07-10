---
description: |
  AWS CLI command to list event source mappings that invoke a Lambda function in the AWS account.
command: |
  aws lambda list-event-source-mappings --function-name $name
items:
  - Lambda Function Event Source Mappings
services:
  - AWS Lambda
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/lambda/list-event-source-mappings.html
---
