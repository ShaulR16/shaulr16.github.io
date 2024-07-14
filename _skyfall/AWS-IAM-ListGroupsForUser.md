---
description: |
  AWS CLI command to list groups associated with a specific IAM user.

  Reference:

  	User: replace_with_username

command: |
  aws iam list-groups-for-user --user-name replace_with_username

items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/iam/list-groups-for-user.html
---

