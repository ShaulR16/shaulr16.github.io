---
description: |
  AWS CLI command to list profile associations for each EC2 instance in the AWS account.

command: |
  aws ec2 describe-iam-instance-profile-associations

items:
  - IAM Instance Profile Associations
services:
  - AWS EC2
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/ec2/describe-iam-instance-profile-associations.html
---