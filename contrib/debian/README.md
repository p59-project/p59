
Debian
====================
This directory contains files used to package p59d/p59-qt
for Debian-based Linux systems. If you compile p59d/p59-qt yourself, there are some useful files here.

## p59: URI support ##


p59-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install p59-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your p59qt binary to `/usr/bin`
and the `../../share/pixmaps/p59128.png` to `/usr/share/pixmaps`

p59-qt.protocol (KDE)

