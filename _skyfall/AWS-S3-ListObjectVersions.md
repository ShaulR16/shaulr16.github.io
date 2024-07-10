---
description: |
  AWS CLI command to list object versions within an S3 bucket.

  Command Reference:

  	Bucket Name: replace_with_bucket_name

command: |
  aws s3api list-object-versions --bucket replace_with_bucket_name

items:
  - Object Versions
services:
  - AWS S3
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/s3api/list-object-versions.html
---