### Example 1: Creates an user assigned identity in the specified subscription and resource group
```powershell
PS C:\> New-AzUserAssignedIdentity -ResourceGroupName azure-rg-test -Name uai-pwsh01 -Location eastus

Location Name       ResourceGroupName
-------- ----       -----------------
eastus   uai-pwsh01 azure-rg-test
```

This command creates an user assigned identity in the specified subscription and resource group