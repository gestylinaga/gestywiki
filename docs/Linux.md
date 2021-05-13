# Linux
> "What you're referring to as Linux, is in fact, GNU/Linux, or as I've recently 
> taken to calling it, GNU plus Linux." - [Richard Stallman](https://www.lurkmore.com/view/GNU/Linux_rant)
 
That quote is half true, because 'Linux' isn't the only thing responsible for a
complete operating system, but it's an important part. By itself, the Linux kernel simply
acts as the "middle-man" between the hardware in your computer, and your software. For 
example, when opening ***another*** Chrome tab, 'Linux' allocates whatever resources are needed,
in this case RAM, and gives those to 'Chrome', the program. This means that 'Linux' alone 
is not the whole picture, but colloquially when people say 'Linux' they mean the 
overall complete operating system.

* Software comes in "packages" 
    - All installed packages can be upgraded at once, with one command
        + see [APT](APT.md) and [Pacman](Pacman.md) package managers

* Free/Open Source
    - "Free" as in $$$ and "Free" as in freedom
    - The source code for the kernal is publicly available
        + this means no nefarious code
        + anyone can add/copy/build on the code for their own use

## Architectures
* amd64 -- x86_64, 64-bit, most modern
* i386 -- x86, 32-bit, seen on older laptops/hardware
* ARM -- see [Raspberry Pi](RaspberryPi.md)

## Distributions
* aka Distros
    - [Arch](Arch.md) -- "Rolling release"
        + Manjaro -- uses pacman, 
        + Arco
    - [Debian](Debian.md) -- "Stable release"
        + Raspbian/ Raspberry Pi OS
        + [Kali](Kali.md)-- Security/Penetration Testing
    - Fedora -- "Linux for 'Enterprise'"
    - Gentoo -- "Compile everything yourself"
    - Android -- phone OS

## Advantages/Disadvantages

* Used on majority of servers in the world
    + Learning Linux means pretty much learning how "computers" work
    + Learning Linux means pretty much learning how "the internet" works
    + Learning Linux means pretty much learning how "the modern world" works

* Desktop use not as popular as [Windows](Windows.md)
    - Hassle to get your favorite Windows programs working on Linux
    - "Gaming" on Linux, while getting better, does not beat Windows

* Command Line not beginner friendly
    + With all the different distributions, this isn't *really* a problem tho

* Customizability
    + **Endless** options in "ricing" your desktop

## " Ricing "
> "Ricing" refers to customizing the cosmetic aspects of your desktop. Things like fonts, 
> terminal colors, wallpapers, window behavior, preferred programs/apps and overall 
> user-experience can all be fully customized in Linux and therefore "riced".

* Full Desktop Environments -- come with a status bar/menu system/preinstalled apps
    - GNOME
    - KDE Plasma
    - XFCE

* Window Managers -- just like the name says, Window Managers just manage windows, nothing else
    - Tiling
        - i3wm
        - qtile
    - Floating
        - openbox

| Desktop Environments                             | vs    | Window Managers          |
| :---:                                            | :---: | :---:                    |
| Complete                                         |       | Lightweight              |
| Limited customizability; no configuration needed |       | **Full** customizabilty  |
| Preinstalled programs/apps                       |       | Minimal Install          |
| Trust the devs, it's gonna work                  |       | You built it, you fix it |

---

[back to Index/Table of Contents](index.md)
