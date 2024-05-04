# A plan9 xcursor theme

Originally found on https://xn--1xa.duncano.de. To ensure it does not get lost
should the original source ever go down, I reuploaded it here.

![preview](./preview.png)

## Installation

### For NixOS or Nix-enabled systems:
Clone the source:
```bash
git clone https://github.com/wintermute-cell/xcursor-plan9.git
```

Install imperatively:
```bash
cd xcursor-plan9
nix-build
nix-env -i ./result
```

Or add this line to your package config where you would typically specify a
package name:
```nix
(callPackage ../path/to/plan9-cursor/default.nix {})
```

### For Other Linux Distributions:

Copy the `plan9` directory to the appropriate cursor directory:

```bash
git clone https://github.com/wintermute-cell/xcursor-plan9.git
sudo mkdir -p /usr/share/icons
sudo cp -r xcursor-plan9 /usr/share/icons/
```

### Enable the Cursor Theme

1. **GNOME or Unity**:
   - Install GNOME Tweaks (`gnome-tweaks` package) and select the `plan9` cursor theme.

2. **XFCE**:
   - Go to Settings > Appearance > Icons and choose `plan9`.

3. **KDE**:
   - System Settings > Cursors > Select `plan9`.


## License

There was no license information for the original source. Accordingly, this
repo will stay without license.

If you're the original creator of this theme and don't like it being hosted
here please notify me.
