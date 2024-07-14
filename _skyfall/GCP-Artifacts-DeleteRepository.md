---
description: |
  Deletes an Artifact repository in GCP.
command: |
  gcloud artifacts repositories delete <repo-name> --location=<location>
items:
  - Access Keys
services:
  - GCP
OS:
  - Internal
attack_types:
  - PostExp
references:
  - https://cloud.google.com/sdk/gcloud/reference/artifacts/repositories/delete
---
