---
description: |
  AWS CLI command to enumerate objects within an S3 bucket.

  Reference:

  	Bucket Name: replace_with_bucket_name

command: |
  aws s3 ls replace_with_bucket_name

items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/s3api/list-objects-v2.html
  - https://docs.aws.amazon.com/cli/latest/reference/s3/ls.html
---
