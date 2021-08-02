# Putol's slstatus - suckless status

## About
- slstatus is a suckless status monitor for window managers that use WM_NAME
(e.g. dwm) or stdin to fill the status bar.


## Features
- Battery percentage/state/time left
- CPU usage
- CPU frequency
- Custom shell commands
- Date and time
- Disk status (free storage, percentage, total storage and used storage)
- Available entropy
- Username/GID/UID
- Hostname
- IP address (IPv4 and IPv6)
- Kernel version
- Keyboard indicators
- Keymap
- Load average
- Network speeds (RX and TX)
- Number of files in a directory (hint: Maildir)
- Memory status (free memory, percentage, total memory and used memory)
- Swap status (free swap, percentage, total swap and used swap)
- Temperature
- Uptime
- Volume percentage
- WiFi signal percentage and ESSID


## Requirements
- Xlib header files.


## Installation
```sh
git clone https://github.com/pwhitecat/slstatus ~/.local/share/slstatus
cd ~/.local/share/slstatus
sudo make clean install
```
###### END
- Check [suckless website](https://tools.suckless.org/slstatus/) for more information about slstatus
