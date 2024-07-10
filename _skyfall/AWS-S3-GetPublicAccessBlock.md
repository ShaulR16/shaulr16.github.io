---
description: |
  AWS CLI command to get public access block settings for an S3 bucket.

  Command Reference:

  	Bucket Name: replace_with_bucket_name

command: |
  aws s3api get-public-access-block --bucket replace_with_bucket_name

items:
  - Public Access Block
services:
  - AWS S3
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/s3api/get-public-access-block.html
---