# The Ultimate Arch Tutorial:

### (<b>*</b>) indicates this is a required part

###  <b>*</b> Programs/Operating System
- [Ventoy](https://www.ventoy.net/en/download.html), [balena ectcher](https://www.balena.io/etcher), [rufus](https://rufus.ie)
##### (I recomend Ventoy because you can have multiple ISOs on 1 USB!)
- [Arch Linux](https://archlinux.org/download)

### <b>*</b> Physical Stuff:
- USB (Atleast 16 GB)

### <b>*</b> Packages to install:
- `iwd` (if it is not installed already)

## Install tutorial:
- run `archinstall`
#### <b>*</b> Connect to wifi (do this before doing `archinstall`):
1. `iwctl`
2. `iwctl device list`
3. `iwctl device <device_name> set-property Powered on`
4. `iwctl station <device_name> scan`
5. `iwctl station <device_name> get-networks`
6. `iwctl station <device_name> connect <SSID>` (SSID is ur WiFi name)

## Post Install
### Do these commands when you get asked if you want to do any post install commands:
- `sudo pacman -S fastfetch`
- `fastfetch`
#### You should see something like this after doing that:
![Fastfetch](https://raw.githubusercontent.com/DevHollo/DevHollo/refs/heads/main/pfetch-screenfetch-neofetch-fastfetch-imagen-contenido-4-blog-ubunlog-4065787658.jpg)

### (If you code in Python, don't get Visual Studio Code, get <b>[PyCharm](https://www.jetbrains.com/pycharm/)</b> !!)
