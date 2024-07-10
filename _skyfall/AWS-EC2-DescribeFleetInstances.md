---
description: |
  AWS CLI command to get EC2 instances that are part of a fleet in the AWS account.

command: |
  aws ec2 describe-fleet-instances

items:
  - Fleet Instances
services:
  - AWS EC2
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/ec2/describe-fleet-instances.html
---
