---
description: |
  PowerShell command to get and export specific Automation DSC Configuration.
command: |
  Get-AzAutomationAccount | Get-AzAutomationDscConfiguration | where {$_.name -match $DSCName} | Export-AzAutomationDscConfiguration -OutputFolder (get-location) -Debug
items:
  - Access Keys
services:
  - Azure
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://docs.microsoft.com/en-us/powershell/module/az.automation/export-azautomationdscconfiguration
---
