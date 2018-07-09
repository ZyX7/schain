
Debian
====================
This directory contains files used to package saved/save-qt
for Debian-based Linux systems. If you compile saved/save-qt yourself, there are some useful files here.

## save: URI support ##


save-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install save-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your saveqt binary to `/usr/bin`
and the `../../share/pixmaps/save128.png` to `/usr/share/pixmaps`

save-qt.protocol (KDE)

