# My Arch Linux Installation Script  

I wanted an Arch installation script that only requires entering a master password. The ability to create profiles allows me to tailor the installation to my needs.

## Installation 
From archiso:
``` bash
loadkeys fr
mount --mkdir /dev/sdX arch
bash arch/install profile_name
```
