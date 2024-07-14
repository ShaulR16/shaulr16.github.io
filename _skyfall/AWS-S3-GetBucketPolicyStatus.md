---
description: |
  AWS CLI command to check the status of the bucket policy for an S3 bucket.

  Reference:

  	Bucket Name: replace_with_bucket_name

command: |
  aws s3api get-bucket-policy-status --bucket replace_with_bucket_name --output text | python -m json.tool

items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/s3api/get-bucket-policy-status.html
---