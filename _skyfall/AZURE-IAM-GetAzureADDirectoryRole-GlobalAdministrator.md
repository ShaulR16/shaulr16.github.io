---
description: |
  Azure CLI command to get members of the Global Administrator role in Azure Active Directory (AD).
command: |
  Get-AzureADDirectoryRole -Filter "DisplayName eq 'Global Administrator'" | Get-AzureADDirectoryRoleMember
items:
  - Access Keys
services:
  - Azure
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.microsoft.com/en-us/powershell/module/azuread/get-azureaddirectoryrole
---

