
Debian
====================
This directory contains files used to package demosd/demos-qt
for Debian-based Linux systems. If you compile demosd/demos-qt yourself, there are some useful files here.

## demos: URI support ##


demos-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install demos-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your demos-qt binary to `/usr/bin`
and the `../../share/pixmaps/demos128.png` to `/usr/share/pixmaps`

demos-qt.protocol (KDE)

