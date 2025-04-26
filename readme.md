# Backup drivers (current machine)  
* create folder first  
* Run as admin  

```batch
dism /online /export-driver /destination:"D:\drivers"
```

# Win8.1 Remove Modern Apps  

```shell
Get-AppxPackage -AllUsers | Remove-AppxPackage
Get-AppXProvisionedPackage -online | Remove-AppxProvisionedPackage –online
```