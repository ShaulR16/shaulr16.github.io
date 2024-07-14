---
description: |
  Creates a new user for a GCP SQL instance.
command: |
  gcloud sql users create <username> --instance <instance-name> --password <password>
items:
  - Access Keys
services:
  - GCP
OS:
  - Internal
attack_types:
  - PostExp
references:
  - https://cloud.google.com/sdk/gcloud/reference/sql/users/create
---
