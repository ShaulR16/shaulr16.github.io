---
description: |
  AWS CLI command to scan a DynamoDB table named "users" using a specific endpoint URL and format the output with jq.

    Command Reference:

  	URL: replace_with_url

command: |
  aws --endpoint-url http://s3.replace_with_url dynamodb scan --table-name users | jq -r '.Items[]'
items:
  - DynamoDB Table Items
services:
  - AWS DynamoDB
OS:
  - External
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/dynamodb/scan.html
  - https://stedolan.github.io/jq/
---
