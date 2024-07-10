---
description: |
  AWS CLI command to delete a CloudTrail trail named "replace_with_CloudTrail_name" using the "administrator" profile.

  Command Reference:

    Cloudguard Name: replace_with_CloudTrail_name

command: |
  aws cloudtrail delete-trail --name replace_with_CloudTrail_name --profile administrator
items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - DefenseEvasion
references:
  - https://docs.aws.amazon.com/cli/latest/reference/cloudtrail/delete-trail.html
---
