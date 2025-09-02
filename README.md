![build](https://github.com/linuxmint/nemo/actions/workflows/build.yml/badge.svg) [![Total Downloads](https://img.shields.io/github/downloads/Partakithware/nemo-vulcania/total.svg)](https://github.com/Partakithware/nemo-vulcania/releases)

Vulcania 
====

Nemo Vulcania Changes: 

Allows setting of icons in places-sidebar but you must allow it via gsettings.schema

The option appears in the right-click context menu. Enjoy.

(If you wish to use .deb for installs and want to be exactly up-to-date with the repo, self build)
```
sudo cp ~/Documents/nemo-master/libnemo-private/org.nemo.gschema.xml /usr/share/glib-2.0/schemas/

sudo glib-compile-schemas /usr/share/glib-2.0/schemas/

If .deb installed, only use the below:

gsettings set org.nemo.sidebar-panels.custom-icons use-custom-sidebar-icons true

gsettings get org.nemo.sidebar-panels.custom-icons use-custom-sidebar-icons
```
[![Screenshot from 2025-07-08 21-51-07](https://i.ibb.co/Lzf0kKwB/Screenshot-from-2025-07-08-21-51-07.png)](https://ibb.co/1fx0vcVB)

[![Screenshot from 2025-07-08 13-38-59](https://i.ibb.co/RG7HCLWj/Screenshot-from-2025-07-08-13-38-59.png)](https://ibb.co/CpW0nxFP)

[![Screenshot from 2025-07-08 13-39-09](https://i.ibb.co/2Y7M0M4Z/Screenshot-from-2025-07-08-13-39-09.png)](https://ibb.co/zHh2W2v6)

Nemo
====
Nemo is a free and open-source software and official file manager of the Cinnamon desktop environment. 
It is a fork of GNOME Files (formerly named Nautilus).

Nemo also manages the Cinnamon desktop.
Since Cinnamon 6.0 (Mint 21.3), users can enhance their own Nemo with Spices named Actions.


History
====
Nemo started as a fork of the GNOME file manager Nautilus v3.4. Version 1.0.0 was released in July 2012 along with version 1.6 of Cinnamon,
reaching version 1.1.2 in November 2012.

Developer Gwendal Le Bihan named the project "nemo" after Jules Verne's famous character Captain Nemo, who is the captain of the Nautilus.

Vulcania is the secret island port of origin for the Nautilus and Captain Nemo's one land-based home. 

Features
====
Nemo v1.0.0 had the following features as described by the developers:
1. Ability to SSH into remote servers
2. Native support for FTP (File Transfer Protocol) and MTP (Media Transfer Protocol)
3. All the features Nautilus 3.4 had and which are missing in Nautilus 3.6 (all desktop icons, compact view, etc.)
4. Open in terminal (integral part of Nemo)
5. Open as root (integral part of Nemo)
6. Uses GVfs and GIO
7. File operations progress information (when copying or moving files, one can see the percentage and information about the operation on the window title and so also in the window list)
8. Proper GTK bookmarks management
9. Full navigation options (back, forward, up, refresh)
10. Ability to toggle between the path entry and the path breadcrumb widgets
11. Many more configuration options
