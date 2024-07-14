---
description: |
  Deletes a Docker image from GCP Artifact Registry.
command: |
  gcloud artifacts docker images delete <location>-docker.pkg.dev/<proj-name>/<repo-name>/<img-name>:<tag>
items:
  - Access Keys
services:
  - gcp
OS:
  - Internal
attack_types:
  - PostExp
references:
  - https://cloud.google.com/sdk/gcloud/reference/artifacts/docker/images/delete
---
