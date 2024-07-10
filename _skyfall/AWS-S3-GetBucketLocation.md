---
description: |
  AWS CLI command to check the location of an S3 bucket.

  Command Reference:

  	Bucket Name: replace_with_bucket_name

command: |
  aws s3api get-bucket-location --bucket replace_with_bucket_name

items:
  - Bucket Location
services:
  - AWS S3
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/s3api/get-bucket-location.html
---