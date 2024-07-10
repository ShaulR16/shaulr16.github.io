---
description: |
  AWS CLI command to list NAT gateways in the AWS account.

command: |
  aws ec2 describe-nat-gateways

items:
  - NAT Gateways
services:
  - AWS EC2
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/ec2/describe-nat-gateways.html
---
