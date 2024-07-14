---
description: |
  Adds the specified user to the specified group.
command: |
  aws iam add-user-to-group --group-name <Group Name> --user-name <User Name>
items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Exploitation
references:
  - https://docs.aws.amazon.com/cli/latest/reference/iam/add-user-to-group.html
---
