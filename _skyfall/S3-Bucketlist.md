---
description: |
  The `aws s3 ls` command is used to list all the Amazon S3 buckets in your account. This command helps in enumerating the S3 storage services and understanding the available buckets and their configurations. The following example lists all S3 buckets for the specified profile and region.

  Command Reference:

  	Profile: default

  	Region: us-east-1

command: |
  aws s3 ls --profile default --region us-east-1
items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/s3/ls.html
---
