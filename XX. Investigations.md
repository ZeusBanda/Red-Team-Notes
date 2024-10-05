# Windows
## PowerShell
### Get-Process
```PowerShell
Get-Process
```
```PowerShell
Get-Process lsass
```
```PowerShell
Get-Process ;sass | Select-Object -Property *
```
```PowerShell
Get-Process lsass | Select-Object -Property Path,Name,Id
```
```PowerShell
Get-Process | Select-Object -Property Path,Name,Id | Where-Object -Property Name -eq explorer
```
```PowerShell
Get-Process | Select-Object -Property Path,Name,Id | Where-Object -Property Path -like "*temp*"
```

