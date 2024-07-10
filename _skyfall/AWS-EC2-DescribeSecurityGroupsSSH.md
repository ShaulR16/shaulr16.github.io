---
description: |
  AWS CLI command to list security groups that allow SSH from the internet in the AWS account.

command: |
  aws ec2 describe-security-groups --filters Name=ip-permission.from-port,Values=22 Name=ip-permission.to-port,Values=22 Name=ip-permission.cidr,Values='0.0.0.0/0'

items:
  - Security Groups Allowing SSH from Internet
services:
  - AWS EC2
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/ec2/describe-security-groups.html
---
