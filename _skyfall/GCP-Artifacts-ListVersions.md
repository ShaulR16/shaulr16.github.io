---
description: |
  Lists versions of packages in an Artifact repository in GCP.
command: |
  gcloud artifacts versions list --repository=<repo-name> --location <location> --package <package-name>
items:
  - Access Keys
services:
  - GCP
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://cloud.google.com/sdk/gcloud/reference/artifacts/versions/list
---
