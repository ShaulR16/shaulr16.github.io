---
description: |
  Azure CLI command to get scoped role membership in Azure Active Directory (AD) by ID.
command: |
  Get-AzureADMSScopedRoleMembership -Id <ID> | fl
items:
  - Access Keys
services:
  - Azure
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.microsoft.com/en-us/powershell/module/azuread/get-azureadmsadminstrativerolescopedrolemembership
---

