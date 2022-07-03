# Mark's build of dwl

[dwl](https://github.com/djpohly/dwl) with customisations, including key bindings, sensible defaults, patches, etc. to suit my needs.

From the project page:

    > dwl is a compact, hackable compositor for Wayland based on [wlroots](https://gitlab.freedesktop.org/wlroots/wlroots/). It is intended to fill the same space in the Wayland world that dwm does in X11, primarily in terms of philosophy, and secondarily in terms of functionality.

# Quick setup

Make sure to install `wlroots` and `wayland-protocols` before building.

```
git clone https://github.com/markbunse/dwl
cd dwl
sudo make clean install
```

## Running dwl

For basic functionality (terminal, statusbar, launcher), install at the very least `alacritty`, `waybar`, and `bemenu`.
Kill your current Xorg or Wayland session (or switch to another tty) and run `dwl`.
You can launch programmes with `bemenu-run` by pressing `SUPER + SPACE`.
Check out the [config](https://github.com/markbunse/dwl/blob/main/config.def.h) for all keybindings and programmes that this build requires.

# Troubleshooting

My repo didn't build or launch? Try the more detailed instructions on the [original repo](https://github.com/djpohly/dwl#building-dwl).
