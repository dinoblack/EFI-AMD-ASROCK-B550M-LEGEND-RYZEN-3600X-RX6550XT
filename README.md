# Asrock B550M Steel Legend + RYZEN5 3600x + RX 6550XT + Fenvi BCM94360CD

![about-13 1](https://raw.githubusercontent.com/dinoblack/EFI-AMD-GIGABYTE-X570-GAMING-X-RYZEN-3600X-RX6550XT/main/About.png)

**Latest working macOS**: 13.1
<br>
**Current OpenCore**: 0.8.7

## Complete hardware specs
- AMD Ryzen 5 3600X 3.8 GHz, 4.4GHz Max Turbo, Socket AM4, 32MB Cache - 100-100000022BOX
- Asrock B550M Steel Legend @ BIOS 2.50
- RX 6650 XT - XFX AMD Radeon RX 6650 XT ULTRA QICK 308 (spoofed device id RX6600xt)
- 2x 16Gb DDR4 3000Mhz Kingston KHX3000C15/16GX with XMP Enabled
- Wifi/BT Fenvi BCM94360CD

## What works
- macOS Ventura
- Audio
- HDMI/DP (eGPU)
- All USB ports
- Everything iCloud related (Drive, iMessage, Facetime, unlock with Apple Watch, etc)
- Temperature monitoring for everything except GPU
- DRM content (Netflix, ATV+, Airplay 2 mirroring etc)
- Shutdown/Reboot/Update to newer macOS builds over time
- CPU Temperature
- GPU Temperature

## What doesn't work
- Unknown

## Kexts used:
- AppleALC.kext
- AMDRyzenCPUPowerManagement.kext
- AppleMCEReporterDisabler.kext
- Lilu.kext
- RealtekRTL8111.kext
- RestrictEvents.kext
- SMCAMDProcessor.kext
- SMCRadeonGPU.kext
- RadeonSensor.kext
- USBMap.kext
- VirtualSMC.kext
- WhateverGreen.kext

## Geekbench Results:
- https://browser.geekbench.com/v5/cpu/19402568 (CPU)
- https://browser.geekbench.com/v5/compute/6099503 (OpenCL)
- https://browser.geekbench.com/v5/compute/6099242 (Metal)

## Thanks/Credits
- [Opencore Team](https://dortania.github.io/getting-started/)
- [BASE EFI - for Ryzen and Threadripper (https://github.com/luchina-gabriel/BASE-EFI-AMD-RYZEN-THREADRIPPER)
- youtube.com - Gabriel Luchina - Universo Hackintosh
- tonymacx86.com - in special @vandroiy

## Warning
- Don't forget to change the MLB, ROM, SystemSerialNumber and SystemUUID.