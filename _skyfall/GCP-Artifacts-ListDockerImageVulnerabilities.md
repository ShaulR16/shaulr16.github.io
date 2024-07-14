---
description: |
  Lists vulnerabilities of Docker images in GCP.
command: |
  gcloud artifacts docker images list-vulnerabilities projects/<proj-name>/locations/<location>/scans/<scan-uuid>
items:
  - Access Keys
services:
  - GCP
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://cloud.google.com/sdk/gcloud/reference/artifacts/docker/images/list-vulnerabilities
---
