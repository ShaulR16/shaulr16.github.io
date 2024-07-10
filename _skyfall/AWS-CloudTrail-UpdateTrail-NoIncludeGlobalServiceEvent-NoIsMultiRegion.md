---
description: |
  AWS CLI command to update a CloudTrail trail named "replace_with_CloudTrail_name" to exclude global service events and disable multi-region logging.

  Command Reference:

    Cloudguard Name: replace_with_CloudTrail_name

command: |
  aws cloudtrail update-trail --name replace_with_CloudTrail_name --no-include-global-service-event --no-is-multi-region --region=eu-west
items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - DefenseEvasion
references:
  - https://docs.aws.amazon.com/cli/latest/reference/cloudtrail/update-trail.html
---
