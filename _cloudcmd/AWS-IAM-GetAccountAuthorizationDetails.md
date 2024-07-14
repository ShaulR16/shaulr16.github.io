---
description: |
  Retrieves details about IAM resources in the AWS account.
command: |
  aws iam get-account-authorization-details --filter User Group LocalManagedPolicy Role
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
