# ADAR Designer

This repository is for distribution of ADAR Designer releases.

## Usage

Usage instructions can be found in ADAR User manual on [Sonair.com](https://www.sonair.com/resources)

<figure style="justify-items:center">
  
  ![Short gif demonstrating ADAR Designer](/docs/images/ADAR-Designer-mini-demo.gif "Configure Sonair ADAR with ADAR Designer")
  
  <figcaption style="text-align:center">Configure Sonair ADAR with ADAR Designer</figcaption>
</figure>

## Installation

> [!WARNING]
> The following instructions were extracted from "ADAR User manual" on 2025-09-10, and may be outdated.

The latest version of ADAR Designer can be downloaded from [Releases](https://github.com/Sonair-AS/adar-designer-releases/releases).

| **Operating system**                                 | **Installer name**                             |
| ---------------------------------------------------- | ---------------------------------------------- |
| Windows\*                                            | `ADAR.Designer_<version number>_x64-setup.exe` |
| Debian based Linux distributions\*<br/>(e.g. Ubuntu) | `ADAR.Designer_<version number>_amd64.deb`     |

_\* Only recent versions supported_

### Windows

Execute the installer and follow the instructions

### Linux

Open the terminal, navigate to the folder containing the installer. Run the following command (replace `<installer name>` with the specific name of the downloaded installer):

```bash
sudo dpkg -i <installer name>
```

Follow the instructions in the terminal.

When the installation is complete, you can type `adar-designer` to start the program or start it from the GUI.

## Update

> [!WARNING]
> Automatic updates are currently only supported on Windows. Linux users should regularly check for updates by visiting the link at the beginning of the Installation section.

ADAR Designer comes with an automatic update feature that checks for updates every time the program is started. To manually check for updates, click `About->Check for updates...`.

<figure style="justify-items:center">
  
  ![Click "About->Check for updates..." to manually check for updates](/docs/images/check-for-updates.png "Manually check for updates")
  
  <figcaption style="text-align:center">Manually check for updates</figcaption>
</figure>

If a new update is found, a green prompt will be shown in the bottom right corner, urging the user to “update now”. Make sure to save any unsaved changes before initiating an update.

<figure style="justify-items:center">
  
  ![Click "About->Check for updates..." to manually check for updates](/docs/images/update-available.png "A prompt is shown when a new update is available")
  
  <figcaption style="text-align:center">A prompt is shown when a new update is available</figcaption>
</figure>

Upgrades should be installed when available. Under normal circumstances, an upgrade takes less than a second.
