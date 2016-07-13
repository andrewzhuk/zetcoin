
Debian
====================
This directory contains files used to package zetcoind/zetcoin-qt
for Debian-based Linux systems. If you compile zetcoind/zetcoin-qt yourself, there are some useful files here.

## zetcoin: URI support ##


zetcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install zetcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your zetcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/zetcoin128.png` to `/usr/share/pixmaps`

zetcoin-qt.protocol (KDE)

