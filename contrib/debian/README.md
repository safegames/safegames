
Debian
====================
This directory contains files used to package safegamesd/safegames-qt
for Debian-based Linux systems. If you compile safegamesd/safegames-qt yourself, there are some useful files here.

## safegames: URI support ##


safegames-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install safegames-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your safegamesqt binary to `/usr/bin`
and the `../../share/pixmaps/safegames128.png` to `/usr/share/pixmaps`

safegames-qt.protocol (KDE)

