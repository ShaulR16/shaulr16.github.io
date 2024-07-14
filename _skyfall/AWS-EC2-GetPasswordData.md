---
description: |
  AWS CLI command to get the admin password for an EC2 instance in the AWS account.

command: |
  aws ec2 get-password-data --instance-id $id

items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - PostExp
references:
  - https://docs.aws.amazon.com/cli/latest/reference/ec2/get-password-data.html
---