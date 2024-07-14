---
description: |
  Deletes a backup from a GCP SQL instance.
command: |
  gcloud sql backups delete <backup-id> --instance <instance-id>
items:
  - Access Keys
services:
  - GCP
OS:
  - Internal
attack_types:
  - PostExp
references:
  - https://cloud.google.com/sdk/gcloud/reference/sql/backups/delete
---
