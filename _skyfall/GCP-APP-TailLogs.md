---
description: |
  Streams logs for a specific App Engine service in GCP.
command: |
  gcloud app logs tail -s <app-name>
items:
  - Access Keys
services:
  - gcp
OS:
  - Internal
attack_types:
  - PostExp
references:
  - https://cloud.google.com/sdk/gcloud/reference/app/logs/tail
---
