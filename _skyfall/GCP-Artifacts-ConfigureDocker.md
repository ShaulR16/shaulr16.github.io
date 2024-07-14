---
description: |
  Configures Docker authentication for GCP Artifact Registry.
command: |
  gcloud auth configure-docker <location>-docker.pkg.dev
items:
  - Access Keys
services:
  - GCP
OS:
  - Internal
attack_types:
  - PostExp
references:
  - https://cloud.google.com/sdk/gcloud/reference/auth/configure-docker
---
