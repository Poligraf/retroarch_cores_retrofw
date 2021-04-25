# Retroarch cores for Retrofw

##Important

Grab retroarch from https://github.com/Poligraf/retroarch-retrofwunofficial/releases

Add bios to the `/home/retrofw/.retroarch/system` or equivalent folder

Add cores to the `/home/retrofw/.retroarch/cores` or equivalent folder

##Known Issues

AmstradCPC - 'Start + y' opens virtual keyboard. Press `select` in virtual keyboard menu to move mouse.

Atari 800/5200 requires bios. See https://docs.libretro.com/library/atari800/
```
Important

Select 5200/800 or XL/XE after you run the core.

The core does not autodetect the game properly.

Otherwise core stays on  Atari Computer - Memo Pad` screen.

Change RetroPad to Atari Joystick or Atari Keyboard. Otherwise you cant move
```
Atari Lynx requires `lynxboot.img`. Core is too unstable without it

Cave story. Grab and unload zip https://github.com/Poligraf/retroarch_cores_retrofw/blob/main/Cave%20Story%20(En).zip. Zip file obtained from retroarch buildbot `https://buildbot.libretro.com/assets/cores/Cave%20Story/` does not contain copyright material.

Commodore64- `Sound gitch` - Start game without headphones. Plug headphones after audio starts.

Dos - very slow

ColecoVision  - requires bios. Download from http://bluemsx.msxblue.com/rel_download/blueMSXv282full.zip and add  `Databases` and `Machines` folders from zip to `/home/retrofw/.retroarch/system` or equivalent - `Same steps as SG1000`  


Dubithawr - Grab game form https://buildbot.libretro.com/assets/cores/Dinothawr/

Flashback -reminiscence Watch video https://www.youtube.com/watch?v=46S-FDjSjfo for set up

Intellivision - requires bios. See https://docs.libretro.com/library/freeintv/

Lowresnx - some games are slow to run

MSX - needs bios otherwise `black screen` is present. See https://docs.libretro.com/library/fmsx/

Odyssey2 - requires bios. See https://docs.libretro.com/library/o2em/

PC88 - requires bios. See https://docs.libretro.com/library/quasi88/

SG1000  - requires bios. Download from http://bluemsx.msxblue.com/rel_download/blueMSXv282full.zip and add  `Databases` and `Machines` folders from zip to `/home/retrofw/.retroarch/system` or equivalent - `Same steps as ColecoVision`  

Snes - Sound issues kind of fixed.


Vectrex - some slowdown is present

Wonderswan - make sure you `Rewind Frames` is set to a high number over 17. Otherwise it lags.

ZX spectrum- Requires bios. See https://docs.libretro.com/library/fuse/ for details
