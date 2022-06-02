
Debian
====================
This directory contains files used to package basemond/basemon-qt
for Debian-based Linux systems. If you compile basemond/basemon-qt yourself, there are some useful files here.

## basemon: URI support ##


basemon-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install basemon-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your basemonqt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

basemon-qt.protocol (KDE)

