---
description: |
  SSH into a specific instance of an App Engine service in GCP.
command: |
  gcloud app instances ssh --service <app-name> --version <version-id> <ID>
items:
  - Access Keys
services:
  - gcp
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://cloud.google.com/sdk/gcloud/reference/app/instances/ssh
---
