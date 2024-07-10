---
description: |
  AWS CLI command to list EBS volumes in the AWS account.

command: |
  aws ec2 describe-volumes

items:
  - EBS Volumes
services:
  - AWS EC2
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/ec2/describe-volumes.html
---
