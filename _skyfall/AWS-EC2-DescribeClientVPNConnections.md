---
description: |
  AWS CLI command to list active client VPN connections in the AWS account.

command: |
  aws ec2 describe-client-vpn-connections --client-vpn-endpoint-id $id

items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/ec2/describe-client-vpn-connections.html
---
