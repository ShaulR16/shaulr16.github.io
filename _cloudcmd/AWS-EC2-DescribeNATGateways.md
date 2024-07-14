---
description: |
  AWS CLI command to list NAT gateways in the AWS account.

command: |
  aws ec2 describe-nat-gateways

items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/ec2/describe-nat-gateways.html
---
