---
description: |
  AWS IAM Enumeration Script is a tool used to enumerate IAM users and roles in an AWS environment. This script can list all IAM users, roles, groups, and policies, providing insight into the permissions and configurations within the AWS account.

  Command Reference:

  	Profile: default

  	Region: us-east-1

command: |
  aws iam list-users --profile default --region us-east-1
items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/iam/list-users.html
---
