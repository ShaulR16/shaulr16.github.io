---
description: |
  AWS CLI command to get user data of EC2 instances and look for secrets.

command: |
  aws ec2 describe-instance-attribute --instance-id $id --attribute userData --output text --query "UserData.Value" | base64 --decode

items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/ec2/describe-instance-attribute.html
---
