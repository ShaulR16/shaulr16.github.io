---
description: |
  AWS CLI command to retrieve the latest console output from an EC2 instance in the AWS account.

command: |
  aws ec2 get-console-output --instance-id $id --output text

items:
  - Console Output
services:
  - AWS EC2
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/ec2/get-console-output.html
---
