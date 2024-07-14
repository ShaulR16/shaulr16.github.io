---
description: |
  Adds the specified IAM role to the specified instance profile.
command: |
  aws iam add-role-to-instance-profile --instance-profile-name <Instance Profile> --role-name <Role Name>
items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Exploitation
references:
  - https://docs.aws.amazon.com/cli/latest/reference/iam/add-role-to-instance-profile.html
---
