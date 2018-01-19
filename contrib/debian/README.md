
Debian
====================
This directory contains files used to package bitcoinlightd/bitcoinlight-qt
for Debian-based Linux systems. If you compile bitcoinlightd/bitcoinlight-qt yourself, there are some useful files here.

## dash: URI support ##


bitcoinlight-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bitcoinlight-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bitcoinlight-qt binary to `/usr/bin`
and the `../../share/pixmaps/dash128.png` to `/usr/share/pixmaps`

bitcoinlight-qt.protocol (KDE)

