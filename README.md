[![GitHub latest release version](https://img.shields.io/github/v/release/Project-Mega-Pack/a330-300.svg?style=for-the-badge)](https://github.com/Project-Mega-Pack/a330-300/releases/latest)
[![Github All Releases download count](https://img.shields.io/github/downloads/Project-Mega-Pack/a330-300/total?style=for-the-badge)](https://github.com/Project-Mega-Pack/a330-300/releases/latest)
[![GitHub contributors](https://img.shields.io/github/contributors/Project-Mega-Pack/a330-300.svg?style=for-the-badge)](https://github.com/Project-Mega-Pack/a330-300/graphs/contributors)

[![Discord](https://img.shields.io/discord/746450820077453393?label=Discord&style=for-the-badge)](https://discord.com/invite/kAAfYpjsbF)

# Project Mega Pack A330-300

Welcome to the Project Mega Pack A330-300 Project! This is a open source project to create a free Airbus A330-300 in Microsoft Flight Simulator and is based on the FlyByWire A32NX and Headwind A330-900neo. If you only want to use the aircraft in MSFS please download the Addon here: https://www.projectmegapack.com/aircraft/a330

## How to build
Make sure docker are isntalled. Prefferably with WSL2 backend.

#### 1. First, run following command on powershell. This will install the A32NX docker images and node modules.

For powershell:
```shell
.\scripts\dev-env\run.cmd ./scripts/setup.sh
```
For Git Bash/Linux:
```shell
./scripts/dev-env/run.sh ./scripts/setup.sh
```
#### 2. As next step we will copy the original source files and copy-over our source files.

For powershell:
```shell
.\scripts\dev-env\run.cmd ./scripts/copy.sh
```
For Git Bash/Linux:
```shell
./scripts/dev-env/run.sh ./scripts/copy.sh
```

#### 3. Build all A32NX module by running following command on powershell. 

For powershell:
```shell
.\scripts\dev-env\run.cmd ./scripts/build.sh
```
For Git Bash/Linux:
```shell
./scripts/dev-env/run.sh ./scripts/build.sh
```

#### 4. The package is now ready to use. Copy the folder "headwind-aircraft-a330-900" to your CommunityPackage folder in MSFS.

#### (Optional) If you want to use the MSFS Dev Tools you can run the following command (after build completed) to copy the files to the PackageSources.

For powershell:
```shell
.\scripts\dev-env\run.cmd ./scripts/package.sh
```
For Git Bash/Linux:
```shell
./scripts/dev-env/run.sh ./scripts/packge.sh
```

## Open source
Open Source Projects contributing to the realisation of this MSFS A330-900 Neo :

Systems, cockpit, cockpit texture, sound : FlyByWire - https://github.com/flybywiresim
FBW integration : Tyler58546 - https://github.com/tyler58546/pmp-a330-fbw-compatibility
Cockpit 3D parts, learning : Project Mega Pack - https://github.com/Project-Mega-Pack

## Licences

The original contents of this repository are DUAL LICENSED. Original textual-form source code in this file is licensed under the GNU General Public License version 3.

Creative Commons License Artistic Assets (Models, Textures) are licenced under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.

You are free to:
    Share — copy and redistribute the material in any medium or format
    Adapt — remix, transform, and build upon the material

The licensor cannot revoke these freedoms as long as you follow the license terms.
asures that legally restrict others from doing anything the license permits.

Microsoft Flight Simulator © Microsoft Corporation. The Project Mega Pack A330 was created under Microsoft's "Game Content Usage Rules" using assets from Microsoft Flight Simulator 2020, and it is not endorsed by or affiliated with Microsoft.

Microsoft Flight Simulator © Microsoft Corporation. The FlyByWire Simulations A32NX was created under Microsoft's "Game Content Usage Rules" using assets from Microsoft Flight Simulator, and it is not endorsed by or affiliated with Microsoft.

We are not affiliated, associated, authorized, endorsed by, or in any way officially connected with the Airbus brand, or any of its subsidiaries or its affiliates.
