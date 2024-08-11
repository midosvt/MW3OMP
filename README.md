# Call Of Duty - Modern Warefare 3
## Overview
Call Of Duty Modern Warefare 3 or MW3 is a TDM SA:MP gamemode. The aim of the game is to choose a team, capture zones, kill enemies, level up, unlock more classes and many more fun activities.

This gamemode has been maintained and developed by Battlezone aka Seif_Tounes since 2013, later on they decided to open source the project on 05/15/2018.

We now decided to convert this gamemode to [Open Multiplayer](https://open.mp/faq) if anyone still wishes to use this gamemode.

![A screenshot from the good old days, server peaked at 245 players](https://i.imgur.com/cLzbzzt.png)

## Getting started
Before you can get started, there are dependencies you need on your server folder:
- [open.mp server](https://github.com/openmultiplayer/open.mp/releases/latest) - Since this gamemode has been converted to open.mp you need to download the open.mp server files.
- [omp-stdlib](https://github.com/openmultiplayer/omp-stdlib) - Improved versions of the original Pawn includes, more functions, more correctness, more compile-time checks etc.
- [Latest YSI](https://github.com/pawn-lang/YSI-Includes/releases/tag/v5.10.0006) - YSI library.
- [crashdetect](https://github.com/Y-Less/samp-plugin-crashdetect/releases/tag/v4.22) - Crash/error reporting plugin.
- [MapAndreas](https://github.com/philip1337/samp-plugin-mapandreas/releases/tag/v1.2.1) - MapAndreas plugin.
- [MySQL](https://github.com/pBlueG/SA-MP-MySQL/releases/tag/R41-4) - MySQL plugin.
- [FileManager](https://github.com/JaTochNietDan/SA-MP-FileManager/releases/tag/1.5.1) - A file management plugin.
- [streamer](https://github.com/samp-incognito/samp-streamer-plugin/releases/tag/v2.9.6) - Streamer to bypass most of SA-MP limits.
- [WhirlPool](https://github.com/Southclaws/samp-whirlpool/releases/tag/v1.0.0) - Please convert it to Bcrypt if you can. 

All other libraries with no dependecies are shipped in the `qawno\include` directory.

## Changelog
- Adapted the gamemode to open.mp stdlib.
- All dependencies have been updated.
- Removed dumb macros from the code.
- Removed some useless RakNet related hooks.
- Removed unused functions from the code.
- Fixed some sql injections.

## Credits
All credit goes to edgyaf for converting this. And of course the original gamemode creators.

For people who want to host their a server using this script; Please keep the names that are in /credits, or at least add a separate command called /scriptcredits.