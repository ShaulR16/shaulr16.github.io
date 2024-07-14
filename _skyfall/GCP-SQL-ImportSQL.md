---
description: |
  Imports a SQL dump from a Cloud Storage bucket to a GCP SQL instance.
command: |
  gcloud sql import sql <instance-id> <gs://bucketName/fileName>
items:
  - Access Keys
services:
  - gcp
OS:
  - Internal
attack_types:
  - PostExp
references:
  - https://cloud.google.com/sdk/gcloud/reference/sql/import/sql
---
