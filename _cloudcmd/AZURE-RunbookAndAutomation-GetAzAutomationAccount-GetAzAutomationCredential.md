---
description: |
  PowerShell command to get all Automation Credentials from Automation Accounts.
command: |
  Get-AzAutomationAccount | Get-AzAutomationCredential
items:
  - Access Keys
services:
  - Azure
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.microsoft.com/en-us/powershell/module/az.automation/get-azautomationcredential
---
