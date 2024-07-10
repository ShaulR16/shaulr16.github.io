---
description: |
  AWS CLI command to list private AMIs in the AWS account.

command: |
  aws ec2 describe-images --filters "Name=is-public,Values=false"

items:
  - Private AMIs
services:
  - AWS EC2
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/ec2/describe-images.html
---
