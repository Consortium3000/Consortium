
Debian
====================
This directory contains files used to package consortiumd/consortium-qt
for Debian-based Linux systems. If you compile consortiumd/consortium-qt yourself, there are some useful files here.

## consortium: URI support ##


consortium-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install consortium-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your consortium-qt binary to `/usr/bin`
and the `../../share/pixmaps/consortium128.png` to `/usr/share/pixmaps`

consortium-qt.protocol (KDE)

