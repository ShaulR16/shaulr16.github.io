---
description: |
  AWS CLI command to check client VPN authorization rules in the AWS account.

command: |
  aws ec2 describe-client-vpn-authorization-rules --client-vpn-endpoint-id $id

items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/ec2/describe-client-vpn-authorization-rules.html
---
