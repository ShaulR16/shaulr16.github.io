---
description: |
  AWS CLI command to list names of SSH key pairs in the AWS account.

command: |
  aws ec2 describe-key-pairs

items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/ec2/describe-key-pairs.html
---