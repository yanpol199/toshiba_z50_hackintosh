# toshiba z50 hackintosh loader
loader for start mac os

for install need add new macmodel and serial
## Hardware

| Type          | Name                                            |
| ------------- | ----------------------------------------------- |
| CPU           | Intel i5\i7 4xxxU                               |
| RAM           | 2xDDR3l 1600MHz                                 |
| GPU           | Intel HD Graphics 4400                          |
| Drive         | mSATA\SATA drive                                |
| Sound card    | Realtek ALC283                                  |
| WLAN          | Apple Broadcom BCM94360CS2                      |
| LAN           | Intel                                           |
| WWAN          | Sierra Wireless Airprime EM7305                 |
| Display       | LVDS or eDP display   (for fullHD del AAPL00)   |

## Used kexts

## Prerequisites

> **BIOS/UEFI settings**

Change the following settings before you boot into the macOS installer:

- Exit → System Defaults [F9]: Yes
- Security → Secure Boot: Disabled
- Power Managements → Wake Up LAN: Disabled
- Power Managements → Wake On Keyboard: Disabled
- Power Managements → Critical Battery Wake Up: Enabled
- Power Managements → Panel Open Power On: Disabled
- Power Managements → Power On By AC: Disabled
- Power Managements → Dynamic CPU Frequency Mode: Dynamic Switch
- Power Managements → Intel Turbo Boost: Enabled
- Power Managements → SATA Interface Technology: Performance
- Advanced → USB Power in Sleep Mode: Disabled
- Advanced \ System Configuration → Boot Mode: UEFI Boot

## Credits

- [Apple](https://apple.com) for [macOS](https://www.apple.com/macos/)
- [Acidanthera](https://github.com/acidanthera) for [OpenCore](https://github.com/acidanthera/OpenCorePkg), [Lilu](https://github.com/acidanthera/Lilu), [AppleALC](https://github.com/acidanthera/AppleALC), [VoodooPS2](https://github.com/acidanthera/VoodooPS2), [WhateverGreen](https://github.com/acidanthera/WhateverGreen), [VirtualSMC](https://github.com/acidanthera/VirtualSMC).
- [Dortania](https://github.com/dortania) for the [OpenCore install guide](https://dortania.github.io/OpenCore-Install-Guide), [Pre-built kexts](https://dortania.github.io/builds)

## LICENSE

- This project is licensed under the MIT License - see the LICENSE file for details.
