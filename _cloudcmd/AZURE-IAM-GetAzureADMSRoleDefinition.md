---
description: |
  Azure CLI command to get non-builtin role definitions in Azure Active Directory (AD).
command: |
  Get-AzureADMSRoleDefinition | ?{$_.IsBuiltin -eq $False} | select DisplayName
items:
  - Access Keys
services:
  - Azure
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.microsoft.com/en-us/powershell/module/azuread/get-azureadmsroledefinition
---
