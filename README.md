# Hackintosh-EFI-OpenCore-B550M-5600X-RX6600

## Specification

| **Component** | **Model**                          |
| ------------- | ---------------------------------- |
| CPU           | AMD Ryzen 5 5600X                  |
| Motherboard   | ASUS TUF GAMING B550M-PLUS WIFI II |
| GPU           | AMD Radeon RX6600                  |
| Ethernet      | RTL8111&8125                       |

**macOS version**: macOS Ventura 13.4

**OpenCore version**: 0.9.3

**SMBIOS**: MacPro7,1

## Drivers & Kexts
- [Based on Qinruiy/Opencore-Gigabyte-B550M](https://github.com/Qinruiy/Opencore-Gigabyte-B550M)
- [[Bootloader] OpenCore](https://github.com/acidanthera/OpenCorePkg)
- [[Patch] AMD_Vanilla](https://github.com/AMD-OSX/AMD_Vanilla)
- [[Driver] HfsPlus](https://github.com/acidanthera/OcBinaryData/blob/master/Drivers/HfsPlus.efi)
- [[Kext] Lilu](https://github.com/acidanthera/Lilu)
- [[Kext] VirtualSMC](https://github.com/acidanthera/VirtualSMC)
- [[Kext] WhateverGreen](https://github.com/acidanthera/WhateverGreen)
- [[Kext] AppleALC](https://github.com/acidanthera/AppleALC)
- [[Kext] AppleMCEReporterDisabler](https://github.com/AMD-OSX/AMD_Vanilla/blob/opencore/Extra/AppleMCEReporterDisabler.kext.zip)
- [[Kext] AMDRyzenCPUPowerManagement](https://github.com/trulyspinach/SMCAMDProcessor)
- [[Kext] SMCAMDProcessor](https://github.com/trulyspinach/SMCAMDProcessor)
- [[Kext] USBPorts](https://dortania.github.io/OpenCore-Post-Install/usb/manual/manual.html#usb-mapping-the-manual-way)

## Important Notes

- Please replace **PlatformInfo** > **MLB**,**SystemSerialNumber**,**SystemUUID**
