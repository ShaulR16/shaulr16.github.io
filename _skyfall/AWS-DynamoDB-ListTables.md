---
description: |
  AWS CLI command to list all DynamoDB tables using a specific endpoint URL.

  	URL: replace_with_url

command: |
  aws --endpoint-url http://s3.replace_with_url dynamodb list-tables
items:
  - DynamoDB Tables
services:
  - AWS DynamoDB
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/dynamodb/list-tables.html
---


