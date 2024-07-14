---
description: |
  Lists packages in an Artifact repository in GCP.
command: |
  gcloud artifacts packages list --repository <repo-name> --location <location>
items:
  - Access Keys
services:
  - gcp
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://cloud.google.com/sdk/gcloud/reference/artifacts/packages/list
---
