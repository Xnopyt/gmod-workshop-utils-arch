# Garry's Mod Workshop Utilities for Arch Linux
## How to use
1. Clone this repo and enter it
```bash
git clone https://github.com/Xnopyt/gmod-workshop-utils-arch
cd gmod-workshop-utils-arch
```
2. Copy the required files from your Garry's Mod installation
```bash
cp /PATH/TO/STEAM/steamapps/common/GarrysMod/bin/gmad_linux ./
cp /PATH/TO/STEAM/steamapps/common/GarrysMod/bin/gmpublish_linux ./
cp /PATH/TO/STEAM/steamapps/common/GarrysMod/bin/libsteam_api.so ./
```
3. Build and install with `makepkg -si`
4. Both the commands `gmad` and `gmpublish` should now be avalible