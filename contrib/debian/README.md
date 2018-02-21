
Debian
====================
This directory contains files used to package dagrad/dagra-qt
for Debian-based Linux systems. If you compile dagrad/dagra-qt yourself, there are some useful files here.

## dagra: URI support ##


dagra-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install dagra-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your dagra-qt binary to `/usr/bin`
and the `../../share/pixmaps/dagra128.png` to `/usr/share/pixmaps`

dagra-qt.protocol (KDE)

