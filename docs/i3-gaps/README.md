# Installation instructions

## Install the Speed Ricer PPA
```
$ sudo add-apt-update ppa:kgilmer/speed-ricer
```

## Install the package
```
$ sudo apt install i3
```

## Prevent Gnome from hijacking the screen
```
$ gsettings set org.gnome.desktop.background show-desktop-icons false
```

## Reboot and login using the `i3` session

You'll be asked to create a default i3 session.  Once the desktop has loaded, $mod-Enter will launch a terminal.