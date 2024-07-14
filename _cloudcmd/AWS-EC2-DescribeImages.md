---
description: |
  AWS CLI command to list private AMIs in the AWS account.

command: |
  aws ec2 describe-images --filters "Name=is-public,Values=false"

items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/ec2/describe-images.html
---
