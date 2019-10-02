
Debian
====================
This directory contains files used to package aikrwd/aikrw-qt
for Debian-based Linux systems. If you compile aikrwd/aikrw-qt yourself, there are some useful files here.

## aikrw: URI support ##


aikrw-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install aikrw-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your aikrw-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

aikrw-qt.protocol (KDE)

