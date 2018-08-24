
Debian
====================
This directory contains files used to package brvd/brv-qt
for Debian-based Linux systems. If you compile brvd/brv-qt yourself, there are some useful files here.

## brv: URI support ##


brv-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install brv-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your brvqt binary to `/usr/bin`
and the `../../share/pixmaps/brv128.png` to `/usr/share/pixmaps`

brv-qt.protocol (KDE)

