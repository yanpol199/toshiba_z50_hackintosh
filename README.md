# toshiba_z50_hackintosh
Open core loader for start mac os
## Hardware

| Type          | Name                                            |
| ------------- | ----------------------------------------------- |
| CPU           | Intel i5-4310U 2.0GHz/3MB                       |
| RAM           | DDR3l 1600MHz 16GB (2 x 8GB)                    |
| GPU           | Intel HD Graphics 4400                          |
| Drive         | mSATA SSD                                       |
| Sound card    | Realtek                                         |
| Wireless card | Apple Broadcom BCM94360CS2                      |
| Display       | LVDS display connected to internal converter    |

## Prerequisites

> **BIOS/UEFI settings**

Change the following settings before you boot into the macOS installer:

- Exit → System Defaults [F9]: Yes
- Security → Secure Boot: Disabled
- Power Managements → Wake Up LAN: Disabled
- Power Managements → Wake On Keyboard: Disabled
- Power Managements → Critical Battery Wake Up: Disabled
- Power Managements → Panel Open Power On: Disabled
- Power Managements → Power On By AC: Disabled
- Power Managements → Dynamic CPU Frequency Mode: Dynamic Switch
- Power Managements → Intel Turbo Boost: Enabled
- Power Managements → SATA Interface Technology: Performance
- Advanced → USB Power in Sleep Mode: Disabled

## Credits

- [Apple](https://apple.com) for [macOS](https://www.apple.com/macos/)
- [Acidanthera](https://github.com/acidanthera) for [OpenCore](https://github.com/acidanthera/OpenCorePkg), [Lilu](https://github.com/acidanthera/Lilu), [AppleALC](https://github.com/acidanthera/AppleALC), [VoodooPS2](https://github.com/acidanthera/VoodooPS2), [WhateverGreen](https://github.com/acidanthera/WhateverGreen), [VirtualSMC](https://github.com/acidanthera/VirtualSMC).
- [Dortania](https://github.com/dortania) for the [OpenCore install guide](https://dortania.github.io/OpenCore-Install-Guide), [Pre-built kexts](https://dortania.github.io/builds)

## LICENSE

- This project is licensed under the MIT License - see the LICENSE file for details.
