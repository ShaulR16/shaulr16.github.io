---
description: |
  AWS CLI command to get ACLs (Access Control Lists) for an S3 bucket.

  Command Reference:

  	Bucket Name: replace_with_bucket_name

command: |
  aws s3api get-bucket-acl --bucket replace_with_bucket_name

items:
  - Bucket ACLs
services:
  - AWS S3
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/s3api/get-bucket-acl.html
---
