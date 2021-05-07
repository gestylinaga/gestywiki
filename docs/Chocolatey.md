# Chocolatey

Package Manager for Microsoft [Windows](Windows.md)

> Commands should be run as admin
>> right click on Start icon
>
>> Windows Powershell (Admin) 

## Commands

* Install packages:
```powershell
choco install vim neovim
```

* Remove packages:
```powershell
choco uninstall vim neovim
```

* Upgrade packages:
```powershell
choco upgrade all -y
```

* List installed packages:
```powershell
choco list --local-only
clist -l
```
