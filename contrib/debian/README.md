
Debian
====================
This directory contains files used to package CCIPd/CCIP-qt
for Debian-based Linux systems. If you compile CCIPd/CCIP-qt yourself, there are some useful files here.

## CCIP: URI support ##


CCIP-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install CCIP-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your CCIPqt binary to `/usr/bin`
and the `../../share/pixmaps/CCIP128.png` to `/usr/share/pixmaps`

CCIP-qt.protocol (KDE)

