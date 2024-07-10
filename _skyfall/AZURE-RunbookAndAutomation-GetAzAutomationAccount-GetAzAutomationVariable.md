---
description: |
  PowerShell command to get all Automation Variables from Automation Accounts.
command: |
  Get-AzAutomationAccount | Get-AzAutomationVariable
items:
  - Access Keys
services:
  - Azure
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.microsoft.com/en-us/powershell/module/az.automation/get-azautomationvariable
---
