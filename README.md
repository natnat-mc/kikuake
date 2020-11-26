# Kikuake
A [yakuake](https://github.com/KDE/yakuake) equivalent, using [kitty](https://github.com/kovidgoyal/kitty), [xdotool](https://github.com/jordansissel/xdotool), [wmctrl](https://www.freedesktop.org/wiki/Software/wmctrl/) and xrandr

## Installing
First, make sure you're using KWin as your window manager (by default if you're using KDE)  
Second, install all the dependencies (lua5.3, xdotool, wmctrl and xrandr)  
Third, copy the `kikuake` script somewhere in your PATH and make it executable  
Fourth, setup some shortcuts, the most useful are `kikuake --toggle` and `kikuake --togglefullscreen`

## Using kikuake
Kikuake is controlled from the command line or through keyboard shortcuts, using the `--show`, `--hide`, `--toggle`, `--togglefullscreen` and `--setopacity` flags.  
Additionally, it is possible to start `kitty` hidden using `kikuake --start`, but all the other flags will do it for you.
