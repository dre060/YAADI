
Debian
====================
This directory contains files used to package yaadid/yaadi-qt
for Debian-based Linux systems. If you compile yaadid/yaadi-qt yourself, there are some useful files here.

## yaadi: URI support ##


yaadi-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install yaadi-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your yaadiqt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

yaadi-qt.protocol (KDE)

