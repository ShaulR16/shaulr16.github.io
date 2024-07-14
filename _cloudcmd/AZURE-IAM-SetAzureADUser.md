---
description: |
  Azure CLI command to set other emails for an Azure Active Directory (AD) user.
command: |
  Set-AzureADUser -ObjectId <OBJECT-ID> -OtherMails <Username>@<TENANT NAME>.onmicrosoft.com -Verbose
items:
  - Access Keys
services:
  - Azure
OS:
  - Internal
attack_types:
  - Configuration Change
references:
  - https://docs.microsoft.com/en-us/powershell/module/azuread/set-azureaduser
---
