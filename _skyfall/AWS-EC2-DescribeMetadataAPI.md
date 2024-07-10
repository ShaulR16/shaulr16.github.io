---
description: |
  AWS CLI command to check if EC2 instances use Metadata API version 1 (easier to exfil access keys).

command: |
  aws ec2 describe-instances --filters Name=metadata-options.http-tokens,Values=optional

items:
  - Metadata API Version 1
services:
  - AWS EC2
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/ec2/describe-instances.html
---
