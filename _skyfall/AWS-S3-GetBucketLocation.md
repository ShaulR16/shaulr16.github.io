---
description: |
  AWS CLI command to check the location of an S3 bucket.

  Reference:

  	Bucket Name: replace_with_bucket_name

command: |
  aws s3api get-bucket-location --bucket replace_with_bucket_name

items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/s3api/get-bucket-location.html
---