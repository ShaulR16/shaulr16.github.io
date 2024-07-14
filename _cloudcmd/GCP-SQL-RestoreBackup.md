---
description: |
  Restores a backup to a GCP SQL instance.
command: |
  gcloud sql backups restore <backup-id> --restore-instance <instance-id>
items:
  - Access Keys
services:
  - GCP
OS:
  - Internal
attack_types:
  - PostExp
references:
  - https://cloud.google.com/sdk/gcloud/reference/sql/backups/restore
---
