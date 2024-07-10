---
description: |
  PowerShell command to get all Automation Runbooks from Automation Accounts.
command: |
  Get-AzAutomationAccount | Get-AzAutomationRunbook
items:
  - Access Keys
services:
  - Azure
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.microsoft.com/en-us/powershell/module/az.automation/get-azautomationrunbook
---
