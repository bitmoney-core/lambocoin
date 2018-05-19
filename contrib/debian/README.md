
Debian
====================
This directory contains files used to package lambocoind/lambocoin-qt
for Debian-based Linux systems. If you compile lambocoind/lambocoin-qt yourself, there are some useful files here.

## lambocoin: URI support ##


lambocoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install lambocoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your lambocoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

lambocoin-qt.protocol (KDE)

