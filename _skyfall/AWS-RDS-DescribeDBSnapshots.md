---
description: |
  Retrieves information about RDS DB snapshots of type manual in the us-east-1 region.
command: |
  aws rds describe-db-snapshots --region us-east-1 --snapshot-type manual --query=DBSnapshots[*].DBSnapshotIdentifier
items:
  - Access Keys
services:
  - AWS
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.aws.amazon.com/cli/latest/reference/rds/describe-db-snapshots.html
---
