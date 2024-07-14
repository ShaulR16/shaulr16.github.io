---
description: |
  Displays a list of available IAM commands related to listing, getting, or generating resources.
command: |
  aws iam help | grep -E "list-|get-|generate-"
items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/iam/index.html
---
