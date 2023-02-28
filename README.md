# hackintosh-i9-11900H

## Complete hardware specs

- Intel i9 11900H @ Overclocked (All cores 4.4Ghz)
- Mobo: Eryng HM570 Embedded cpu
- RX 6600 XT - Sapphire PULSE
- 2x 8Gb DDR4 3200Mhz T-Group XMP Enabled
- Wifi/BT Fenvi BCM94360NG - Work OOB

## What works

- macOS Monterey, macOS Ventura
- Audio
- HDMI/DP (in dGPU - Works OOB)
- All USB ports
- Everything iCloud related (Drive, iMessage, Facetime, unlock with Apple Watch, etc)
- Temperature monitoring for everything
- DRM content (Netflix, ATV+, Airplay 2 mirroring etc)
- Shutdown/Reboot/Update to newer macOS builds over time

## What doesn't work

- Sleep? Never got the chance to test it, my hackintosh is up 24/7

## Kexts used

- Lilu.kext
- RealtekRTL8111.kext
- RadeonSensor.kext
- RestrictEvents.kext
- SMCProcessor.kext
- SMCRadeonGPU.kext
- SMCSuperIO.kext
- USBMap.kext
- VirtualSMC.kext
- WhateverGreen.kext
