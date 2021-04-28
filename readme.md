# Dynamic Window Manager
This is my build of suckless [dwm](https://dwm.suckless.org/), with some patches applied and dmenu disabled, you need rofi if you want to run commands like in dmenu.

Note that config.def.h is not the suckless default config, I have already patched and edited the default config.

## Installation
Install using 

```make
sudo make clean install
```
Uninstall via 

```make
sudo make clean uninstall
```
## Patches applied 
Urgent border patch

Actual full screen patch

Autostart patch

Per-tag patch

Push patch

Systray patch

## Keybindings
Mod Key is Alt.

Mod+Shift+Return = Alacritty

Mod+u = Firefox

Mod+u = Pcmanfm

Mod+p = rofi in run modi

Mod+c = Kill client window

Mod+q = quits dwm

For more, refer to config file.

## NOTE 
I have commented out the code relating to dmenu in config file and dwm.c, beware of that.

