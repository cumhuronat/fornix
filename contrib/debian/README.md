
Debian
====================
This directory contains files used to package fornixd/fornix-qt
for Debian-based Linux systems. If you compile fornixd/fornix-qt yourself, there are some useful files here.

## fornix: URI support ##


fornix-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install fornix-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your fornixqt binary to `/usr/bin`
and the `../../share/pixmaps/fornix128.png` to `/usr/share/pixmaps`

fornix-qt.protocol (KDE)

