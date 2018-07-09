
Debian
====================
This directory contains files used to package schaind/schain-qt
for Debian-based Linux systems. If you compile schaind/schain-qt yourself, there are some useful files here.

## schain: URI support ##


schain-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install schain-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your schainqt binary to `/usr/bin`
and the `../../share/pixmaps/schain128.png` to `/usr/share/pixmaps`

schain-qt.protocol (KDE)

