# SuperStation One - Automatic SD Card Installer

This repository hosts ready-to-flash SD card installer images for SuperStation (SS1).
Each release provides a zipped image that automates setup and boots into MiSTer FPGA when installation is complete.

## Installation

1. Download the latest release image zip from the Releases tab.
2. Flash the downloaded image to your SD card using balenaEtcher or Rufus.
3. Insert the SD card into your SS1.
4. Power on the console and wait for the automatic installer to complete.
5. The system will finish by rebooting into MiSTer FPGA.

If the system does not boot into MiSTer FPGA after the installer finishes, repeat the flashing process and try again.

If you are migrating an existing card with games and data:
Back up /games/, /saves/, and /savestates/ to your computer before flashing.
Copy them back after installation is complete.

## Special Thanks

Special thanks to the author of [mr-fusion](https://github.com/MiSTer-devel/mr-fusion) for their work, and to all [MiSTer FPGA developers](https://github.com/MiSTer-devel) for their continued contributions.

Please check [HOMEBREW_CREDITS.md](HOMEBREW_CREDITS.md) and [README_LICENSES.md](README_LICENSES.md) for additional contributions and credits.
