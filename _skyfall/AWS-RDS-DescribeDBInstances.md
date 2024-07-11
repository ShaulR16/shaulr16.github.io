---
description: |
  Retrieves information about RDS DB instances in a specified region.
command: |
  aws rds describe-db-instances --region <region name>
items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/rds/describe-db-instances.html
---
