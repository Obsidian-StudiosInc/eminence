# Eminence - Purple/Violet them for E
[![License](https://img.shields.io/badge/license-GPLv3-9977bb.svg?style=plastic)](https://github.com/Obsidian-StudiosInc/ebuild-bumper/blob/master/LICENSE)
[![Build Status](https://img.shields.io/travis/Obsidian-StudiosInc/eminence/master.svg?colorA=9977bb&style=plastic)](https://travis-ci.org/Obsidian-StudiosInc/eminence)

A bash script and some modified edc files to convert default 
Enlightenment and Terminology themes from blue to Purple. The script 
will unpack the default theme, process the edc and png files. Then 
repack the theme as eminence. After it will clean up after itself 
leaving just the script. The resulting eminence.edj is placed is your 
home elementary and terminology themes directory.

The modified edc files are based on work
[from Matthias Wauer/@LeBlue](https://github.com/LeBlue) on the
[Enlightenment Arc theme](https://github.com/LeBlue/enlightenment-arc-theme).
The colors and eventually the reset will deviate heavily from the 
Enlightenment Arc theme, and Arc themes in general.

This theme has evolved to more than just color modifications to the 
default them. It will be a semi hybrid between the default them, Arc, 
and personal preferences.

```
~/.elementary/themes/eminence.edj
~/.config/terminology/themes/eminence.edj
```

## Usage
Addiontional instructions and maybe help/options output will be added 
later. For now simply

```
chmod 775 eminence.sh
./eminence.sh

```

## Building
For the time being you will need to copy the
[assets directory](https://github.com/LeBlue/enlightenment-arc-theme/tree/master/assets),
at minimum the assets/other and assets/whitened folders, into the root 
folder next to eminence script and src dirs. They assets are in the 
process of being replaced/removed. Binaries will not be committed to 
this repo!

Without such the script/build will fail!
