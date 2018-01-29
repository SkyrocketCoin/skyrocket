
Debian
====================
This directory contains files used to package skyrocketd/skyrocket-qt
for Debian-based Linux systems. If you compile skyrocketd/skyrocket-qt yourself, there are some useful files here.

## skyrocket: URI support ##


skyrocket-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install skyrocket-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your skyrocketqt binary to `/usr/bin`
and the `../../share/pixmaps/skyrocket128.png` to `/usr/share/pixmaps`

skyrocket-qt.protocol (KDE)

