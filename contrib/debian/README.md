
Debian
====================
This directory contains files used to package cteamd/cteam-qt
for Debian-based Linux systems. If you compile cteamd/cteam-qt yourself, there are some useful files here.

## cteam: URI support ##


cteam-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cteam-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cteamqt binary to `/usr/bin`
and the `../../share/pixmaps/cteam128.png` to `/usr/share/pixmaps`

cteam-qt.protocol (KDE)

