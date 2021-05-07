# Pacman

Package manager for Arch Linux, and distros based on Arch Linux ie:
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
pacman -Qqe | less
pacman -Qqe > packageslist.txt
```

## Config
* Location -- /etc/pacman.conf
