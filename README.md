Sparky Backup System

This tool lets you create a hybrid ISO image from your SparkyLinux installation. The package provides a YAD-based GUI for the sparky-backup-core.

Copyright (C) 2012-2021 Paweł "pavroo" Pijanowski <pavroo@onet.eu> 
under GNU GPLv3

The tool is forked from Remastersys & Remastersys-GUI
Oryginaly created by Tony Brijeski under GNU GPLv2
Copyright (C) 2007,2008,2009

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

Dependencies:
---------------
apt
bash
coreutils
gawk
grep
sparky-backup-core (>= 20180607)
sparky-editor
sparky-remsu
sparky-xterm (>= 0.2.0)
yad

Suggests (for Advanced Installer =< Sparky 6):
--------------
gparted

Conflicts:
--------------
sparky-remastersys

Install:
-------------
su (or sudo) 
./install.sh

Uninstall:
-------------
su (or sudo)
./install.sh uninstall
