Debian
======

This directory contains files used to package megabytecoind/megabytecoin-qt
for Debian-based Linux systems. If you compile megabytecoind/megabytecoin-qt yourself, there are some useful files here.

## megabytecoin: URI support ##

megabytecoin-qt.desktop (Gnome / Open Desktop)

To install:

	sudo desktop-file-install megabytecoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your megabytecoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/megabytecoin128.png` to `/usr/share/pixmaps`

megabytecoin-qt.protocol (KDE)