---
description: |
  AWS CLI command to list EBS snapshots in the AWS account.

command: |
  aws ec2 describe-snapshots

items:
  - EBS Snapshots
services:
  - AWS EC2
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/ec2/describe-snapshots.html
---
