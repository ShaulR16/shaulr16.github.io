---
description: |
  Azure CLI command to get an Azure Active Directory (AD) group by display name.
command: |
  Get-AzADGroup -DisplayName '<GROUP-NAME>'
items:
  - Access Keys
services:
  - Azure
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.microsoft.com/en-us/powershell/module/az.resources/get-azadgroup
---