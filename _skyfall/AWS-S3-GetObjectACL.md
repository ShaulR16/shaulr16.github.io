---
description: |
  AWS CLI command to get ACLs (Access Control Lists) for an object in an S3 bucket.

  Command Reference:

  	Bucket Name: replace_with_bucket_name
  	File Name: replace_with_file_name

command: |
  aws s3api get-object-acl --bucket replace_with_bucket_name --key replace_with_file_name

items:
  - Object ACLs
services:
  - AWS S3
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/s3api/get-object-acl.html
---