# Arctiva package repository (x86_64)

Signed pacman repository `[arctiva]` of [Arctiva](https://github.com/catlinux), a Linux distribution based on Arch Linux. The packages and the database are published as the files of the `x86_64` release and are built and signed automatically; do not upload anything by hand.

Arctiva systems already include it. To add it to another system, install `arctiva-keyring` (it ships the public key) and add to `/etc/pacman.conf`:

```
[arctiva]
Server = https://github.com/catlinux/arctiva-repo/releases/download/x86_64
```

Key fingerprint: `C0AE 9639 0DC2 0F79 3A38  0441 B216 D69A 3793 8267`.

The packages are licensed under GPL-3.0-or-later unless stated otherwise in each package.
