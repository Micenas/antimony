
Debian
====================
This directory contains files used to package premiumcoind/premiumcoin-qt
for Debian-based Linux systems. If you compile premiumcoind/premiumcoin-qt yourself, there are some useful files here.

## premiumcoin: URI support ##


premiumcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install premiumcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your premiumcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/premiumcoin128.png` to `/usr/share/pixmaps`

premiumcoin-qt.protocol (KDE)

