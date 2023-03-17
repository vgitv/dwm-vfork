# dwm-vfork

## Introduction

This is a fork of dwm, see [https://dwm.suckless.org/](https://dwm.suckless.org/) for original project.

Updated from original project in march 2022.

## Changes

### Mod key

Set modkey to Mod4Mask (super).

Allow Alt key (Mod1Mask) for this specific actions :

* close window
* drag window around with the mouse
* resize window with the mouse

### Miscellaneous changes in config.h

* Invert terminal spawn and zoom shortcut (modkey+return for terminal spawn and modkey+shift+return for zoom)
* Switch tag view with MODKEY + `&é"'(-è_ç` keys (french layout)
* Make a more noticable border color for active window by defining a `col_border` variable in config.h
* Audio key mapping (Lower, Raise an Mute) whith the X11/XF86keysym.h library
* Shutdown system with modkey+pause
* allow modkey+right/left for resize master (along with modkey+h/l)

## Shortcuts

| shortcut | action |
|------|------|
| Mod+SystemPause | launch [systempause](https://github.com/vgitv/dwm-utils/blob/master/bin/systempause) |
| Mod+Shift+p | launch passmenu |
| Mod+x | screenshot |
| Mod+r | refresh status bar |
| Mod+c | open copyq menu |
| Mod+s | launch [sshterm](https://github.com/vgitv/zenscript/blob/master/bin/sshterm) |
