# tinydm-jovian

This repo contains a fork of [TinyDM](https://gitlab.com/postmarketOS/tinydm) for use in [Jovian-NixOS](https://github.com/Jovian-Experiments/Jovian-NixOS).
For other usecases, please use the upstream version instead.

---

# tinydm

Tiny wayland / x11 session starter for single user machines

More information:
https://gitlab.com/postmarketOS/pmaports/-/issues/823

Environment can be configured for both X11 and Wayland sessions by adding files
to source on startup to `/etc/tinydm.d/env-x11.d` and `/etc/tinydm.d/env-wayland.d`

tinydm logs to `~/.local/state/tinydm.log`.
