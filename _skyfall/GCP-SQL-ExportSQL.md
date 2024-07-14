---
description: |
  Exports a SQL dump from a GCP SQL instance to a Cloud Storage bucket.
command: |
  gcloud sql export sql <instance-id> <gs://bucketName/fileName>
items:
  - Access Keys
services:
  - GCP
OS:
  - Internal
attack_types:
  - PostExp
references:
  - https://cloud.google.com/sdk/gcloud/reference/sql/export/sql
---
