---
description: |
  AWS CLI command to take a screenshot of the terminal of an EC2 instance and return it as base64.

command: |
  aws ec2 get-console-screenshot --instance-id $id

items:
  - Console Screenshot
services:
  - AWS EC2
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/ec2/get-console-screenshot.html
---
