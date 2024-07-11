---
description: |
  AWS CLI command to list allowed connections between VPC pairs in the AWS account.

command: |
  aws ec2 describe-vpc-peering-connections

items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/ec2/describe-vpc-peering-connections.html
---
