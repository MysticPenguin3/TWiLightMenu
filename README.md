[![Build Status](https://travis-ci.org/RocketRobz/TWiLightMenu.svg?branch=master)](https://travis-ci.org/RocketRobz/TWiLightMenu)
# ![TWiLightMenu++](https://github.com/RocketRobz/TWiLightMenu/blob/master/logo.png)
TWiLight Menu++ is an open-source DSi Menu upgrade/replacement, and frontend for nds-bootstrap for DSi, 3DS, and flashcards.

# Building

Building this app by yourself requires devkitPRO with devkitARM and [RocketRobz libnds fork](https://github.com/RocketRobz/libnds). Make sure that grit and mmutil are installed.

# Building with Docker

TWiLight Menu++ comes included with a Docker image for easy building without having to manually set up the required version of devkitARM.

You can compile TWiLight Menu++ with Docker using the provided PowerShell (`.ps1`) scripts. First, install Docker at http://docker.com or through your package manager of choice.


Then run `compile_docker.ps1` or `compile_docker.sh`. The script accepts `make` arguments as well, for example `.\compile_docker.ps1 clean`. 

To build all artifacts, run `.\compile_docker.ps1 package`.

## Notes about Docker builds for Windows users

Note that Docker compilation is not compatible with native compilation (if on Windows). You should run `.\compile_docker.ps1 clean` to clean the artifacts before attempting to build with Docker.

If a notification appears to share your drive, you must choose to enable drive sharing for Docker to work on Windows.


# Credits
## Main Developers
- [RocketRobz](https://github.com/RocketRobz): Lead Developer, implementing the auto-reset power button function used in NTR-mode, and LED functions, to nds-bootstrap.
- Another World and Yellow Wood Goblin: The original akMenu/Wood UI.
- [chyyran](https://github.com/chyyran): Port of akMenu/Wood UI to TWiLightMenu++ as a theme.
- [Epicpkmn11](https://github.com/Epicpkmn11): Adding new features to the DSi/3DS Themes, new features & bug fixes to Acekard theme, and the Switch themes for the Acekard theme.
- [shutterbug2000](https://github.com/shutterbug2000): NDMA SD read code, and the muted sound/touchscreen fix for nds-bootstrap.
## App Launchers
- [ahezard](https://github.com/ahezard): [nds-bootstrap](https://github.com/ahezard/nds-bootstrap), and improved NDMA SD read code.
- [Drenn](https://github.com/Drenn1): [GameYob](https://github.com/Drenn1/GameYob)
- Coto & [Apache Thunder](https://github.com/ApacheThunder): [nesDS](https://sourceforge.net/projects/nesds/) ([TWL Edition](https://github.com/ApacheThunder/NesDS)).
- Lordus: [jEnesisDS](https://gamebrew.org/wiki/JEnesisDS)
- archeid (Loopy): [SNEmulDS](https://www.gamebrew.org/wiki/SNEmulDS)
## Graphics & Theme
- [spinal_cord](https://gbatemp.net/members/spinal_cord.90607/): [DSi4DS](https://gbatemp.net/threads/dsi4ds.173617/) and [DSision2](https://gbatemp.net/threads/dsision2.92740/) graphics.
- [StarvingArtist](https://www.deviantart.com/starvingartist/): Some game console icons used.
- [Vulpes-Vulpeos](https://www.deviantart.com/vulpes-vulpeos): MHGen and DS Menu themes for Acekard theme.
- [Daniel](https://github.com/XD-Daniel-XD): Loading screen for 3DS theme.
## Others
- [profi200](https://github.com/profi200): Improved SD code from fastboot3DS.
- [devkitPro](https://github.com/devkitPro), [WinterMute](https://github.com/WinterMute): Code used in nds-hb-menu, and the use of the bootloader, devkitARM, libnds, and libfat.
- [DeadSkullzjr](https://github.com/DeadSkullzJr): [Cheat Database](https://gbatemp.net/threads/deadskullzjrs-flashcart-cheat-databases.488711/)
