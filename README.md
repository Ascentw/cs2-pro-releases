<div align="center">

# CS2 PRO

**Gets your PC ready for Counter-Strike 2.**

Scans Windows, the BIOS and the hardware, runs one-click test routines (RAM, CPU, GPU, drive, network, stutters), tells
you what really weighs on your FPS and guides you step by step. English and Portuguese, every recommendation with a
source.

</div>

This repository only holds the installers and the update packages. The source code is private.

## Install

1. Download the installer:
   - **[CS2 PRO (general edition, for any PC)](https://github.com/Ascentw/cs2-pro-releases/releases/latest/download/CS2PRO.General-general-Setup.exe)**
   - [CS2 PRO (Gustavo) (personal edition)](https://github.com/Ascentw/cs2-pro-releases/releases/latest/download/CS2PRO.Personal-personal-Setup.exe)
2. Run it. No administrator rights are needed. It installs for your Windows user, adds a **CS2 PRO** shortcut to the
   Start menu and the desktop, and opens the app.
3. If "Windows protected your PC" shows up, click **More info › Run anyway**. The installer has no digital signature
   yet, hence the warning.

Requirements: Windows 10 (22H2) or 11, 64-bit.

## Updates

The app checks for a new version by itself (you can turn that off in the three-dot menu). When one exists, a strip at
the top shows **New version · see what changed · Update**. It downloads only what changed, restarts and shows what is
worth testing again. A test that is running is never cut off without asking.

## Your data

Your progress lives in `%LOCALAPPDATA%\CS2PRO_Geral` (personal edition: `%LOCALAPPDATA%\CS2PRO`), outside the install
folder. Updating, repairing or uninstalling never touches it, and a zip copy of the app uses the same folder, so
installing keeps everything.

## Uninstall

Windows Settings › Apps › Installed apps › **CS2 PRO** › Uninstall. To delete your progress too, delete the data folder
above.

## Every version

See [Releases](https://github.com/Ascentw/cs2-pro-releases/releases) for what changed in each version.
