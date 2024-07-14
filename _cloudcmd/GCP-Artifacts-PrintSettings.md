---
description: |
  Prints settings for a Python package in an Artifact repository in GCP.
command: |
  gcloud artifacts print-settings python --repository <repo-name> --location <location>
items:
  - Access Keys
services:
  - GCP
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://cloud.google.com/sdk/gcloud/reference/artifacts/print-settings
---
