
Debian
====================
This directory contains files used to package phantomd/phantom-qt
for Debian-based Linux systems. If you compile phantomd/phantom-qt yourself, there are some useful files here.

## phantom: URI support ##


phantom-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install phantom-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your phantom-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

phantom-qt.protocol (KDE)

