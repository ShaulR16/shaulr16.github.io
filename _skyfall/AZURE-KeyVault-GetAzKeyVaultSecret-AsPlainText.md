---
description: |
  Azure CLI command to get a specific secret from a Key Vault as plain text.
command: |
  Get-AzKeyVaultSecret -VaultName <VaultName> -Name Reader -AsPlainText
items:
  - Access Keys
services:
  - Azure
OS:
  - Internal
attack_types:
  - Exploitation
references:
  - https://docs.microsoft.com/en-us/powershell/module/az.keyvault/get-azkeyvaultsecret
---
