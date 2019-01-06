
Debian
====================
This directory contains files used to package quantisnetd/quantisnet-qt
for Debian-based Linux systems. If you compile quantisnetd/quantisnet-qt yourself, there are some useful files here.

## quantisnet: URI support ##


quantisnet-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install quantisnet-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your quantisnetqt binary to `/usr/bin`
and the `../../share/pixmaps/quantisnet128.png` to `/usr/share/pixmaps`

quantisnet-qt.protocol (KDE)

