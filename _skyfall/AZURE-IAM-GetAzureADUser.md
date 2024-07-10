---
description: |
  Azure CLI command to get a user in Azure Active Directory (AD) by object ID.
command: |
  Get-AzureADUser -ObjectId <RoleMemberInfo.Id> | fl
items:
  - Access Keys
services:
  - Azure
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.microsoft.com/en-us/powershell/module/azuread/get-azureaduser
---