# dwm-vfork

## Introduction

This is a fork of dwm, see [https://dwm.suckless.org/](https://dwm.suckless.org/) for original project.

## Changes

### French layout

Change tag with MODKEY + `&é"'(-è_ç` keys.

### Active border color

Make a more noticable border color by defining a `col_border` variable in config.h.

### Volume keys

Include the following lib in config.h :

```c
#include <X11/XF86keysym.h>
```

in order to use the following keys :

* `XF86XK_AudioLowerVolume`
* `XF86XK_AudioRaiseVolume`
* `XF86XK_AudioMute`

### Screenshot

Screenshot script shortcut with Mod+x.
