---
description: |
  AWS CLI command to list security groups in the AWS account.

command: |
  aws ec2 describe-security-groups

items:
  - Security Groups
services:
  - AWS EC2
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/ec2/describe-security-groups.html
---
