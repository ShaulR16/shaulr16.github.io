---
description: |
  Sets the password for a GCP SQL user.
command: |
  gcloud sql users set-password <username> --instance <instance-name> --password <password>
items:
  - Access Keys
services:
  - GCP
OS:
  - Internal
attack_types:
  - PostExp
references:
  - https://cloud.google.com/sdk/gcloud/reference/sql/users/set-password
---
