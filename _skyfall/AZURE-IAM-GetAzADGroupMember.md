---
description: |
  Azure CLI command to get members of an Azure Active Directory (AD) group by group display name.
command: |
  Get-AzADGroupMember -GroupDisplayName '<GROUP-NAME>' | select UserPrincipalName
items:
  - Access Keys
services:
  - Azure
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.microsoft.com/en-us/powershell/module/az.resources/get-azadgroupmember
---
