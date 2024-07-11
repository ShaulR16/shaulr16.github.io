---
description: |
  Get Tenant ID for a target domain.
command: |
  https://login.microsoftonline.com/<target domain>/v2.0/.well-known/openidconfiguration
items:
  - None
services:
  - Azure
OS:
  - External
attack_types:
  - Enumeration
references:
  - https://docs.microsoft.com/en-us/powershell/module/az.keyvault/get-azkeyvaultsecret
---
