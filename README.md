This repository holds my custom changes to the MAME-2003-Plus project that are either specific changes for my setup or otherwise unlikely to be of interest to the greater community (i.e., not destined for pull requests).  It is kept as a public repository to allow easy transfer and compiling via RetroPie scripts.

Original MAME-2003-Plus readme follows:

## What is MAME 2003-Plus?
[![Build Status](https://api.travis-ci.org/libretro/mame2003-plus-libretro.svg?branch=master)](https://api.travis-ci.org/libretro/mame2003-plus-libretro)

MAME 2003-Plus (also referred to as MAME 2003+ and mame2003-plus) is a libretro arcade system emulator core with an emphasis on high performance and broad compatibility with mobile devices, single board computers, embedded systems, and similar platforms.

In order to take advantage of the performance and lower hardware requirements of an earlier MAME architecture, MAME 2003-Plus began with the MAME 2003 codebase which is itself derived from xmame 0.78. Upon that base, MAME 2003-Plus contributors have backported support for an additional 350 games, as well as other functionality not originally present in the underlying codebase.

**Authors:** MAMEdev, MAME 2003-Plus team, et al (see [LICENSE.md](https://raw.githubusercontent.com/libretro/mame2003-plus-libretro/master/LICENSE.md) and [CHANGELOG.md](https://raw.githubusercontent.com/libretro/mame2003-plus-libretro/master/CHANGELOG.md))

# Documentation
User documentation for MAME 2003-Plus can be found in the **[libretro core documentation library](https://docs.libretro.com/)**.

Developer documentation can be found in **[the MAME 2003-Plus wiki](https://github.com/libretro/mame2003-plus-libretro/wiki)**.

## Development chat
#programming channel of the [libretro discord chat server](https://discordapp.com/invite/C4amCeV).

## What Arcade romsets work with MAME 2003-Plus and how to build them

**mame2003-plus was originally built from the MAME 0.78 codebase, meaning that 95% or more of MAME 0.78 romsets will work as-is in mame2003-plus, where they immediately benefit from its bugfixes and other improvements.** In order to play the new games and games which received ROM updates in mame2003-plus, you will need to find or build the correct romsets.

**[Read more about rebuilding romsets in the libretro core documentation for mame2003-plus](https://docs.libretro.com/library/mame2003_plus/#Building-romsets-for-MAME-2003-Plus)**.
