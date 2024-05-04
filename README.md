# A plan9 xcursor theme

Originally found on https://xn--1xa.duncano.de. To ensure it does not get lost
should the original source ever go down, I reuploaded it here.

![preview](./preview.png)

## Installation

1. **Clone or Download Source**  
   Clone or download the latest version of the cursor pack source code.
   ```bash
   git clone https://github.com/<username>/xcursor-plan9.git
   cd xcursor-plan9
   ```

2. **Build and Install**
   For **NixOS** or Nix-enabled systems:
   ```bash
   nix-build
   nix-env -i ./result
   ```

   For **Other Linux Distributions**:
   - Copy the `plan9` directory to the appropriate cursor directory:
   ```bash
   sudo mkdir -p /usr/share/icons
   sudo cp -r plan9 /usr/share/icons/
   ```

#### Enable the Cursor Theme

1. **GNOME or Unity**:
   - Install GNOME Tweaks (`gnome-tweaks` package) and select the `plan9` cursor theme.

2. **XFCE**:
   - Go to Settings > Appearance > Icons and choose `plan9`.

3. **KDE**:
   - System Settings > Cursors > Select `plan9`.


## License

There was no license information for the original source. Accordingly, this
repo will stay without license.


