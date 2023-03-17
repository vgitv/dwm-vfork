# dwm-vfork

## Introduction

This is a fork of dwm, see [https://dwm.suckless.org/](https://dwm.suckless.org/) for original project.

Updated from original project in march 2022.

## Changes

### Mod key

Set modkey to Mod4Mask (super).

To be consistent with classics desktop environments, allow Alt key (Mod1Mask)
for this specific actions :

* close window (when combined with F4)
* drag window around with the mouse
* resize window with the mouse

### Miscellaneous changes in config.h

* Invert terminal spawn and zoom shortcut (modkey+return for terminal spawn and modkey+shift+return for zoom)
* Switch tag view with MODKEY + `&é"'(-è_ç` keys (french layout)
* Make a more noticable border color for active window by defining a `col_border` variable in config.h
* Audio key mapping (Lower, Raise an Mute) whith the X11/XF86keysym.h library
* Shutdown, reboot (and more) with modkey+pause
* allow modkey+right/left for resize master

## Shortcuts

| shortcut | action |
|------|------|
| Mod+SystemPause | launch [systempause](https://github.com/vgitv/dwm-utils/blob/master/bin/systempause) |
| Mod+Shift+p | [passmenu](https://github.com/vgitv/dwm-utils/blob/master/bin/notify-passmenu) with autotype |
| Mod+Ctrl+p | [passmenu](https://github.com/vgitv/dwm-utils/blob/master/bin/notify-passmenu) copy to clipboard |
| Mod+x | take [screenshot](https://github.com/vgitv/zenscript/blob/master/bin/screenshot) |
| Mod+r | [refresh](https://github.com/vgitv/dwm-utils/blob/master/bin/refresh-status) status bar (dwmblocks) |
| Mod+c | open copyq menu |
| Mod+s | launch [sshterm](https://github.com/vgitv/zenscript/blob/master/bin/sshterm) |
| Mod+l | lock screen with [screenlock](https://github.com/vgitv/dwm-utils/blob/master/bin/screenlock) |
