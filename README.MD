# MSI MS-7883 (X99A GODLIKE 2011-3) BIOS Mod

## Introduction

This repository contains BIOS modifications for the MSI MS-7883 (X99A GODLIKE 2011-3) motherboard.

The MSI MS-7883 (X99A GODLIKE 2011-3) BIOS Mod project aims to improve the functionality and performance of the motherboard through various BIOS modifications. The project is based on the original BIOS version 7883v1A1.zip and utilizes AMIBCP version 5.02.0031, UEFITool 28 & NE and HxD Hex Editor.

Special thanks to Winraid Level1techs forum (https://winraid.level1techs.com/)

### Original BIOS
- **Version**: 7883v1A1.zip
- **Download Link**: [7883v1A1.zip](https://download.msi.com/bos_exe/mb/7883v1A1.zip)
- **AMIBCP Version**: 5.02.0031
- **Source**: [ReBarUEFI](https://github.com/xCuri0/ReBarUEFI)

## Changelog

### Version 0.1

- Initial Release

#### Added
- M.2 Mode 0471
- CPU PCI-E Lanes Control 0BDD
- USB Speed Optimization
- DokT Branded Bios

### Version 0.2

- Updated Microcodes & Firmwares

### Version 0.3

#### Goals
- UEFI Custom Logo (1080p)
- ResizeBar Support (0.3.3)
- Hidden Menu into Overclocking Profiles (Pressing escape in the menu) (0.3.4)
- Custom UEFI setup logo (0.3.1)
- Custom Background in F11 Boot Menu (0.3.2)

#### Changes
- [Bug] UEFI setup logo
- [Bug] Custom Background in F11 Boot Menu not showing

### Version 0.3.1

- [PATCH] UEFI setup logo
- [BUG] Custom Background in F11 Boot Menu not showing
- [NEW] M-FLASH Disclaimer

### Version 0.3.2

- [PATCHED] F11 boot menu patched (doesn't support FHD resolution)
- Updated MOD version string
- UEFI + Secure Boot enabled by default
- Above 4G Decoding enabled by default (For ResizeBar full support coming next release)
- Enabled AMT (for server usages)
- Auto Power On when A/C is loss (Server usage)
- [NEW] Added SLIC Table Controller
- Fast Boot enabled by Default

### Version 0.3.3

- [NEW] Added ResizeBar 0.3 Support

### Version 0.3.4

- [NEW] PCIe Bifurcation for IOU0 / IOU1 (4x4x4x4)

### Version 0.3.5

- [Fix] MOD revision patched
- [WIP] Hidden menu

## How to Install

Follow the steps below to install the modified BIOS:

1. Download the original BIOS from the provided link.
2. Apply the modifications provided in the respective version's changelog.
3. Flash the modified BIOS to your MSI MS-7883 motherboard using the appropriate tools.

## Disclaimer

**Warning:** Flashing a modified BIOS carries risks. Ensure you understand the process and its implications before proceeding. Incorrect flashing can brick your motherboard.

## License

This project is licensed under the [MIT License](LICENSE).

## Contributors

- DokT
- xCuri0 (ResizeBar - https://github.com/xCuri0/ReBarUEFI)

