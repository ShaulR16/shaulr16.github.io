---
description: |
  AWS CLI command to list all S3 buckets in the AWS account.

command: |
  aws s3api list-buckets --query "Buckets[].Name"

items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/s3api/list-buckets.html
---