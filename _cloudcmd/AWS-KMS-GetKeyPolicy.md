---
description: |
  Retrieves a key policy attached to the specified customer master key (CMK).
command: |
  aws kms get-key-policy --policy-name name --key-id ID
items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/kms/get-key-policy.html
---
