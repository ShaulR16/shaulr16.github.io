---
description: |
  Retrieves a list of Azure SQL Databases for a specified server and resource group.
command: |
  Get-AzSqlDatabase -ServerName $ServerName -ResourceGroupName $ResourceGroupName
items:
  - Access Keys
services:
  - Azure
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://learn.microsoft.com/en-us/powershell/module/az.sql/get-azsqldatabase
---
