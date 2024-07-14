---
description: |
  Retrieves details about locally managed policies in the AWS account.
command: |
  aws iam get-account-authorization-details --filter LocalManagedPolicy
items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/iam/get-account-authorization-details.html
---
