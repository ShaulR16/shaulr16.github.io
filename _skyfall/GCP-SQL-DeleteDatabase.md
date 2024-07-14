---
description: |
  Deletes a database from a GCP SQL instance.
command: |
  gcloud sql databases delete <db-name> --instance <instance-id>
items:
  - Access Keys
services:
  - gcp
OS:
  - Internal
attack_types:
  - PostExp
references:
  - https://cloud.google.com/sdk/gcloud/reference/sql/databases/delete
---
