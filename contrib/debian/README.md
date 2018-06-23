
Debian
====================
This directory contains files used to package tioscoind/tioscoin-qt
for Debian-based Linux systems. If you compile tioscoind/tioscoin-qt yourself, there are some useful files here.

## tioscoin: URI support ##


tioscoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install tioscoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your tioscoinqt binary to `/usr/bin`
and the `../../share/pixmaps/tioscoin128.png` to `/usr/share/pixmaps`

tioscoin-qt.protocol (KDE)

