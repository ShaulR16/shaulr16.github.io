---
description: |
  AWS CLI command to get the admin password for an EC2 instance in the AWS account.

command: |
  aws ec2 get-password-data --instance-id $id

items:
  - Admin Password
services:
  - AWS EC2
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/ec2/get-password-data.html
---