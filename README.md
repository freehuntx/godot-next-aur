# Godot Next (Arch Linux Repository)

This repository provides daily builds of the latest Godot Engine development versions (beta/dev) for Arch Linux.  
> Note: Since aur is deleting packages for no reason, i deploy my packages via github.

## Installation

To install packages from this repository, add the following to your `/etc/pacman.conf`:

```ini
[godot-next]
SigLevel = Optional TrustAll
Server = https://freehuntx.github.io/godot-next-aur/x86_64
```

Then update your database and install the package:

```bash
sudo pacman -Syu godot-next-bin
```

## Package Details

- **godot-next-bin**: The latest development build of Godot Engine (repackaged from official GitHub releases).

## Updates

The repository is updated automatically via GitHub Actions whenever a new dev/beta release is published by the Godot team.
