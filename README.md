# VynxOS
VynxOS is a developer oriented linux distrubtion which is based on NixOS 23.05 that follows Plug-and-Play Principle. So it comes with a variety of software that
Usually found in a enterprise-grade developer enviroment.

WARNING: VynxOS IS ALPHA QUALITY SOFTWARE. USE IT WITH CAUTION

## Installion
VynxOS does not have an ISO yet(We are planning to release one soon) so you need to use configuration.nix order to install it.

1. Install NixOS 23.05 GNOME
2. Clone Git Repo
3. Change contents of /etc/nixos/configuration.nix with repos configuration.nix'S content
4. change any ```vynxos``` in configuration.nix with your username of choice
5. do ```sudo nixos-rebuild boot``` then ```sudo nix-collect-garbage```
6. Vola!

## Migrating From 22.11
Existing VynxOS 22.11 users can update like this

1. Save any unsaved work
2. Open a terminal and run ```sudo nix-channel --add https://nixos.org/channels/nixos-23.05 nixos```
3. Then run ```sudo nix-channel --update```
4. Then Run ```sudo nixos-rebuild switch```
5. Reboot your system

# Licensing
VynxOS is licensed under GNU General Public License 3.0. See LICENSE for more information
