---
description: |
  AWS CLI command to download an object from an S3 bucket to a local path.

  Command Reference:

  	Bucket Name: replace_with_bucket_name
  	File Name: replace_with_file_name
  	Local Path: replace_with_local_path

command: |
  aws s3 cp s3://replace_with_bucket_name/replace_with_file_name replace_with_local_path

items:
  - Download Object
services:
  - AWS S3
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/s3/cp.html
---