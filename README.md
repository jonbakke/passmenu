# passmenu

`passmenu` provides a convenient front-end for [`pass`](https://passwordstore.org). It looks for an appropriate selection tool depending on your environment, e.g. `rofi` in Wayland, `dmenu` in X11, or `fzf` when at a command line. It also looks for an appropriate output method, such as `wtype` or `xdotool`.

This script is a modified version of the original, which is distributed with `pass`. On Debian, see `/usr/share/doc/pass/examples/dmenu/passmenu`.
