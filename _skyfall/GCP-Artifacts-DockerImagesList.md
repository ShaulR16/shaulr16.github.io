---
description: |
  Lists Docker images in an Artifact repository in GCP.
command: |
  gcloud artifacts docker images list us-central1-docker.pkg.dev/<proj-name>/<repo-name>
items:
  - Access Keys
services:
  - GCP
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://cloud.google.com/sdk/gcloud/reference/artifacts/docker/images/list
---
