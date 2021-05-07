# APT (Advanced Package Tool)

Package Manager for [Debian Linux](Debian.md), and Debian based distros ie:
* Ubuntu
* Raspbian(Raspberry Pi OS)
* Kali

## Commands

* Install packages:
```
sudo apt install vim neovim
```

* Remove packages:
```
sudo apt remove neovim 
```

* Updates sources list && upgrades system:
```
sudo apt update
sudo apt upgrade
```
* or 
```
sudo apt update && sudo apt upgrade
```

* List installed packages:
```
apt list --installed
```

* Search for a package:
```
apt search vim 
```

* Show package info:
```
apt show vim 
```

* Remove package w/ associating config files:
```
sudo apt purge vim
```

* Remove unneeded/orphaned packages
```
sudo apt autoremove
```

* Edit sources list
```
sudo apt edit-sources
```

## Config
