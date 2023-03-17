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
* Screenshot script shortcut with Mod+x
* Shutdown system with modkey+pause
* Refresh status bar with modkey+r
* launch sshterm script with modkey+x (launch remote ssh session from ssh config file in st)
