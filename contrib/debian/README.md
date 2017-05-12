
Debian
====================
This directory contains files used to package ipod/ipo-qt
for Debian-based Linux systems. If you compile ipod/ipo-qt yourself, there are some useful files here.

## ipo: URI support ##


ipo-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ipo-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ipo-qt binary to `/usr/bin`
and the `../../share/pixmaps/ipo128.png` to `/usr/share/pixmaps`

ipo-qt.protocol (KDE)

