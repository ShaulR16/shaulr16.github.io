---
description: |
  Retrieves a list of firewall rules for a specified Azure SQL Server and resource group.
command: |
  Get-AzSqlServerFirewallRule -ServerName $ServerName -ResourceGroupName $ResourceGroupName
items:
  - Access Keys
services:
  - Azure
OS:
  - Internal
attack_types:
  - Enumeration
references:
  - https://learn.microsoft.com/en-us/powershell/module/az.sql/get-azsqlserverfirewallrule
---
