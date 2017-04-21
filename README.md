# Eminence - Purple/Violet them based on the default Dark Theme for E
[![License](https://img.shields.io/badge/license-GPLv3-9977bb.svg?style=plastic)](https://github.com/Obsidian-StudiosInc/ebuild-bumper/blob/master/LICENSE)
[![Build Status](https://img.shields.io/travis/Obsidian-StudiosInc/eminence/master.svg?colorA=9977bb&style=plastic)](https://travis-ci.org/Obsidian-StudiosInc/eminence)

A bash script to convert default Enlightenment and Terminology themes 
from blue to Purple. The script will unpack the default theme, process 
the edc and png files. Then repack the theme as eminence. After it will 
clean up after itself leaving just the script. The resulting 
eminence.edj is placed is your home elementary themes directory.

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
