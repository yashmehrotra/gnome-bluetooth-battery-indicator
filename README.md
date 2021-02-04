# About

Gnome-Shell extension displaying battery percentage for bluetooth devices

## Requirements

* bluez (on ubuntu: sudo apt install bluez)
* python3 (on ubuntu: sudo apt install python3-dev)
* libbluetooth (on ubuntu: sudo apt install libbluetooth-dev)

```
sudo apt install bluez libbluetooth-dev python3-dev
```

## Manual Installation

1. Clone the repo
```sh
git clone git@github.com:MichalW/gnome-bluetooth-battery-indicator.git
```

2. Init submodules
```sh
git submodule update --init
```

3. Copy to extensions
```sh
cp -R gnome-bluetooth-battery-indicator ~/.local/share/gnome-shell/extensions/bluetooth-battery@michalw.github.com
```

## Debug
journalctl -f -o cat /usr/bin/gnome-shell


## Sources
### This script is based on the following sources

https://github.com/TheWeirdDev/Bluetooth_Headset_Battery_Level

https://github.com/bjarosze/gnome-bluetooth-quick-connect
