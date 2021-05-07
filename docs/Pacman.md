# Pacman

Package manager for [Arch Linux](Arch.md), and distros based on Arch Linux ie:
* Manjaro
* Arco
* Alpine
    
## Commands

* Install packages:
```
pacman -S vim neovim
```

* Remove packages:
```
pacman -R vim neovim
```

* Upgrade all packages:
```
pacman -Syu
```

* List installed packages:
```
pacman -Qqe
```

* Write installed packages to txt file
```
pacman -Qqe > packageslist.txt
```

* Removes AUR packages from package list (Needed before Reinstalling)
```
sudo pacman -S --needed $(comm -12 <(pacman -Slq | sort) <(sort packageslist.txt))
```

* Reinstall from txt package list
```
sudo pacman -S --needed - < packageslist.txt
```

## Config
* Location -- /etc/pacman.conf
