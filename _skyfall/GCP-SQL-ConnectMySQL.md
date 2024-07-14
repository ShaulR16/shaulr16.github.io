---
description: |
  Connects to a GCP SQL MySQL instance.
command: |
  gcloud sql connect mysql --user=root --quiet
items:
  - Access Keys
services:
  - GCP
OS:
  - Internal
attack_types:
  - PostExp
references:
  - https://cloud.google.com/sdk/gcloud/reference/sql/connect
---
