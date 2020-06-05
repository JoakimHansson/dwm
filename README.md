# DWM - Dynamic Window Manager

My configuration of DWM.
This is basically a clone of Luke Smiths config, but with some modifications to the keybindings etc.

Luke Smiths Github: https://github.com/LukeSmithxyz/dwm

Suckless website: https://dwm.suckless.org/

## Installing DWM

To install dwm, follow these steps:

Clone project:
```
git clone https://github.com/JoakimHansson/dwm.git
```

Move into dwm folder:
```
cd dwm
```

Install dwm:
```
sudo make clean install
```

Uninstall dwm:
```
sudo make clean uninstall
```
## Using DWM

Please check links at the top of this README for usage information.

### Keybindings

super = window/mod key

`super+RET` - open terminal(st)

`super+q` - kill focused window

`super+f` - fullscreen

`super+a` - toggle gaps

`super+w` - open firefox 

`super+e` - open emacsclient

`super+c` - open calendar

`super+shift+r` - open htop

More keybindings can be found inside `dwm/config.h`
