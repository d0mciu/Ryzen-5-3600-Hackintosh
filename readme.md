![HACKINTOSH](https://user-images.githubusercontent.com/125405976/232249647-ea4fc0d2-3d44-4e62-8e89-3f9b72178d80.png)
# OpenCore EFI for AMD Ryzen Hackintosh

## Disclaimer
Using this EFI on your rig is solely at your own risk and I am not accountable for any mishaps, including rig explosions. It's crucial that you generate distinctive SMBios values for your rig and avoid duplicating values from the config.plist file.

## Verified Specification

| **Component**    | **Model**                                  |
| ---------------- | ------------------------------------------ |
| CPU              | AMD Ryzen 5 3600 @ 3.6GHz                  |
| Motherboard      | AS ROCK STEEL LEGEND B450M                 |
| RAM              | 16GB (2 x 8GB) Corsair Vengeance @ 3000MHz |
| GPU              | MSI RX 570                                 |
| Ethernet         | Realtek RTL8111                            |
| WiFi & Bluetooth | Still waiting for my FenviT919             |
| OS Disk (NVMe)   | Crucial P2 1000GB                          |

**macOS version**: 13.3 \
**OpenCore version**: 0.9.0

## Working

* iCloud
* iServices
*  Ethernet
* Sleep

## Not Working

* DRM (I do not need it, but it is really easy to fix)
* Sidecar
* Wi-Fi
* Bluetooth

Wi-Fi and Bluetooth would work with a right network card. 

### Kexts

* [AppleALC](https://github.com/acidanthera/AppleALC)
* [AppleMCEReporterDisabler](https://github.com/acidanthera/bugtracker/files/3703498/AppleMCEReporterDisabler.kext.zip)
* [Kernel Patches](https://github.com/AMD-OSX/AMD_Vanilla)
* [Lilu](https://github.com/acidanthera/Lilu)
* [OpenCore](https://github.com/acidanthera/OpenCorePkg)
* [RealtekRTL8111](https://github.com/Mieze/RTL8111_driver_for_OS_X)
* [VirtualSMC](https://github.com/acidanthera/VirtualSMC)
* [WhateverGreen](https://github.com/acidanthera/WhateverGreen)

## Recommended

* [SMCAMDProcessor](https://github.com/trulyspinach/SMCAMDProcessor)

## Credits and links

* [OpenCore install guide](https://dortania.github.io/OpenCore-Install-Guide)
* [Hackintool](https://www.hackintosh-forum.de/forum/thread/38316-hackintool-ehemals-intel-fb-patcher)
* [OpenCore-Legacy-Patcher](https://github.com/dortania/OpenCore-Legacy-Patcher)
* [OpenCore-Legacy-Patcher guide](https://dortania.github.io/OpenCore-Legacy-Patcher)


