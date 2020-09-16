# Docker image for Mount & Blade Warband Servers within Pterodactyl Panel

## Automated Builds

This Docker image is automatically built and can be found on the Docker Hub at:  
https://hub.docker.com/r/masonr/pterodactyl-images/

To pull the pre-built Docker image:  
```bash
$ docker pull masonr/pterodactyl-images:mb-warband
```

## Mount & Blade: Warband Server Files

All server files for the modules below have been staged and made publicly available here:  
http://files.rowe.sh/pterodactyl/mb-warband/

## Supported Modules

**Important Notes**:
1. When selecting a Module to run in your server configuration, copy the text _exactly_ as shown from the "Module Name" column.
2. If a module is currently installed and a new one is selected, all config files and logs will be placed in the "Backups" directory (files currently backed up: _Config.txt_, _Logs/*_, and _ban\_list.txt_).
3. Only the main IP of the server can be used for M&B Servers due to the server listing mechanism. Alternate/alias IPs will not work correctly as allocations.

### Mount & Blade: Warband - Native

| Module Name | Comment | Version | MDB<sup>1</sup> | TW<sup>2</sup> |
| --- | --- | :---: | :---: | :---: |
| Native | [Main Site](https://www.taleworlds.com/en/Games/Warband) | 1.174 | | [Link](https://www.taleworlds.com/en/Games/Warband) |
| The Deluge | | 1.010 | [Link](http://www.moddb.com/mods/the-deluge) | [Link](https://forums.taleworlds.com/index.php?board=274.0) |
| FI2 Amber 2.0 | Full Invasion 2 | 2.0 | [Link](http://www.moddb.com/mods/full-invasion-2) | [Link](https://forums.taleworlds.com/index.php/board,325.0.html) |
| Full Invasion Osiris | | 1.21 | [Link](https://www.moddb.com/mods/full-invasion-2) | [Link](https://forums.taleworlds.com/index.php?forums/full-invasion-2-m.325/) |
| Mount and Gladius V1.0 | Mount & Gladius (formerly March of Rome) | 1.0 | [Link](https://www.moddb.com/mods/mount-and-gladius) | [Link](https://forums.taleworlds.com/index.php/board,268.0.html) |
| PW_4.5 | Persistent World | 4.5.1 | [Link](http://www.moddb.com/mods/persistent-world-mod) | [Link](https://forums.taleworlds.com/index.php/board,184.0.html) |

<sup>1 ModDB</sup>  
<sup>2 TaleWorlds Forums</sup>  

### Mount & Blade: Warband - Napoleonic Wars

| Module Name | Comment | Version | MDB<sup>1</sup> | TW<sup>2</sup> | FSE<sup>3</sup> |
| --- | --- | :---: | :---: | :---: | :---: |
| Napoleonic Wars | [Main Site](https://www.taleworlds.com/en/Games/NapoleonicWars) | 1.21 | [Link](http://www.moddb.com/games/mountblade-warband-napoleonic-wars) | [Link](https://forums.taleworlds.com/index.php/board,280.0.html) | |
| AZW Reloaded | Anglo-Zulu/Sudan War | 1.0 | [Link](http://www.moddb.com/mods/azw-reloaded) | | [Link](https://www.fsegames.eu/forum/index.php?board=95.0) |
| Bello Civili | Roman Civil War | 2 | [Link](http://www.moddb.com/mods/bello-civili-the-roman-civil-war) | | [Link](https://www.fsegames.eu/forum/index.php?board=118.0) |
| Blood and Iron Age of Imperialism | | 3.0 | [Link](http://www.moddb.com/mods/blood-and-iron) | | [Link](https://www.fsegames.eu/forum/index.php?board=111.0) |
| Iron Europe | World War I | 1.21 | [Link](http://www.moddb.com/mods/iron-europe-ww1-mod) | [Link](https://forums.taleworlds.com/index.php?board=352.0) | [Link](https://www.fsegames.eu/forum/index.php?board=127.0) |
| North and South First Manassas | American Civil War | 1.2 | [Link](http://www.moddb.com/mods/north-south-first-manassas) | [Link](https://forums.taleworlds.com/index.php/board,309.0.html) | [Link](https://www.fsegames.eu/forum/index.php?board=34.0) |
| PikeShotte | Pike & Shotte - English Civil War | 2.1 | [Link](http://www.moddb.com/mods/pike-shotte-english-civil-war) | | [Link](https://www.fsegames.eu/forum/index.php?board=183.0) |
| Red and Blue v3 | Spanish Civil  War | 2.1 | [Link](http://www.moddb.com/mods/red-and-blue-1936) | | [Link](https://www.fsegames.eu/forum/index.php?board=136.0) |
| War of 1812 | | Final | [Link](http://www.moddb.com/mods/the-war-of-1812) | | [Link](https://www.fsegames.eu/forum/index.php?board=139.0) |
| Whigs and Tories Final | American Revolution | Final | [Link](http://www.moddb.com/mods/whigs-and-tories) | | [Link](https://www.fsegames.eu/forum/index.php?board=150.0) |

<sup>1 ModDB</sup>  
<sup>2 TaleWorlds Forums</sup>  
<sup>3 Flying Squirrel Entertainment Forum</sup>      

## License
```
            DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
                    Version 2, December 2004

 Copyright (C) 2018 Mason Rowe <mason@rowe.sh>

 Everyone is permitted to copy and distribute verbatim or modified
 copies of this license document, and changing it is allowed as long
 as the name is changed.

            DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
   TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION

  0. You just DO WHAT THE FUCK YOU WANT TO.
```
