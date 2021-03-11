
Debian
====================
This directory contains files used to package krypttocoind/krypttocoin-qt
for Debian-based Linux systems. If you compile krypttocoind/krypttocoin-qt yourself, there are some useful files here.

## krypttocoin: URI support ##


krypttocoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install krypttocoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your krypttocoinqt binary to `/usr/bin`
and the `../../share/pixmaps/krypttocoin128.png` to `/usr/share/pixmaps`

krypttocoin-qt.protocol (KDE)

