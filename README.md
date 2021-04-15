# Retroarch cores for Retrofw

##Important

Add bios to the `/home/retrofw/.retroarch/system` or equivalent folder

Add cores to the `/home/retrofw/.retroarch/cores` or equivalent folder

##Known Issues

Atari 800/5200 requires bios. See https://docs.libretro.com/library/atari800/
```
Important

Select 5200/800 or XL/XE after you run the core.

The core does not autodetect the game properly.
Otherwise core stays on  Atari Computer - Memo Pad` screen.

Change RetroPad to Atari Joystick or Atari Keyboard. Otherwise you cant move
```
Dos - very slow

ColecoVision  - requires bios. Download from http://bluemsx.msxblue.com/rel_download/blueMSXv282full.zip and add  `Databases` and `Machines` folders from zip to `/home/retrofw/.retroarch/system` or equivalent - `Same steps as SG1000`  

Intellivision - requires bios. See https://docs.libretro.com/library/freeintv/

Lowresnx - some games are slow to run

MSX - needs bios otherwise `black screen` is present. See https://docs.libretro.com/library/fmsx/

Odyssey2 - requires bios. See https://docs.libretro.com/library/o2em/

SG1000  - requires bios. Download from http://bluemsx.msxblue.com/rel_download/blueMSXv282full.zip and add  `Databases` and `Machines` folders from zip to `/home/retrofw/.retroarch/system` or equivalent - `Same steps as ColecoVision`  

Snes - sound issues present to improve snes speed. `WIP to improve sound quality but not sacrifice speed`.


Vectrex - some slowdown present

Wonderswan - make sure you `Rewind Frames` is set to a high number like 17 or more. Otherwise it lags.
