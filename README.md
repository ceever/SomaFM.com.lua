# SomaFM.com Lua Plugin for VLC

<img src="https://somafm.com/img/LogoFP2010.gif" style="background:black;" />

 SomaFM.com stations lua script (service discovery)

 Copyright © 2020 Andrew Jackson (https://github.com/ceever ... ceever@web.de)

 This program is free software; you can redistribute it and/or modify
 it under the terms of the GNU General Public License as published by
 the Free Software Foundation; either version 2 of the License, or
 (at your option) any later version.

 This program is distributed in the hope that it will be useful,
 but WITHOUT ANY WARRANTY; without even the implied warranty of
 MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
 GNU General Public License for more details.

 You should have received a copy of the GNU General Public License
 along with this program; if not, write to the Free Software
 Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston MA 02110-1301, USA.

---
**BUGS & REQUESTS:**

Send me an email or open a ticket on github.

---
**INSTALLATION:**

Put the .lua file into the according subfolder of the VLC lua directory, by default:
* Windows (all users): %ProgramFiles%\VideoLAN\VLC\lua\sd\
* Windows (current user): %APPDATA%\VLC\lua\sd\
* Linux (all users): /usr/lib/vlc/lua/sd/
* Linux (current user): ~/.local/share/vlc/lua/sd/

Create directories if they don't exist.

Restart VLC.

---
**EXPLANATION & USAGE:**

* Stations are listed on the left panel under "Internet"
* Explore and crawls through all radio stations
* After having found one or more list(s) of specific stations it is best to copy them into the playlist and continue searching and sorting there, since the Service Discovery zone is a little limited in its capabilities, especially after having found several list of sub categories.
