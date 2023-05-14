# VynxOS
VynxOS is a developer oriented linux distrubtion which is based on NixOS 22.11 that follows Plug-and-Play Principle. So it comes with a variety of software that
Usually found in a enterprise-grade developer enviroment.

WARNING: VynxOS IS ALPHA QUALITY SOFTWARE. USE IT WITH CAUTION

## Installion
VynxOS does not have an ISO yet(We are planning to release one soon) so you need to use configuration.nix order to install it.

1. Install NixOS GNOME
2. Clone Git Repo
3. Change contents of /etc/nixos/configuration.nix with repos configuration.nix'S content
4. change any ```vynxos``` in configuration.nix with your username of choice
5. do ```sudo nixos-rebuild switch``` then ```sudo nix-collect-garbage```
6. Vola!

# Lıcensing
VynxOS is licensed under GNU General Public License 3.0. See LICENSE for more information
