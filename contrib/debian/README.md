
Debian
====================
This directory contains files used to package galeriansd/galerians-qt
for Debian-based Linux systems. If you compile galeriansd/galerians-qt yourself, there are some useful files here.

## galerians: URI support ##


galerians-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install galerians-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your galeriansqt binary to `/usr/bin`
and the `../../share/pixmaps/galerians128.png` to `/usr/share/pixmaps`

galerians-qt.protocol (KDE)

