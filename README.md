# termux-first-setup

## Termux
```
# apt update && apt upgrade

# termux-setup-storage

# termux-change-repo

# pkg install x11-repo tur-repo termux-x11-nightly tigervnc xfce4

# termux-x11 :0 -xstartup "dbus-launch --exit-with-session xfce4-session"
```

## Proot
```
pkg install proot-distro

proot-distro install debian

proot-distro login debian

apt update && apt upgrade

apt install dbus-x11 xfce4

termux-x11 :0 -xstartup "dbus-launch --exit-with-session xfce4-session"
```
