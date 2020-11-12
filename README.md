# AsRock-H410M-OpenCore
[![GitHub version](https://img.shields.io/badge/OpenCore-0.6.3-brightgreen)](https://github.com/acidanthera/OpenCorePkg)
This is the files and configuration for setting up the AsRock H410M desktop using OpenCore.

OpenCore EFI file and Shell included. Basically you could just download, copy, paste, modify few things, and use.

I use MacOS primarily for music works. 

**Specs**
- MacOS Catalina 10.15.6 (should be fine from 10.15.4)
- Intel i5 10400F, 16 GB RAM, ASUS AMD RX 5500XT 4GB. 256 GB SATA SSD: Mac, 240 GB M.2 SSD: Windows. Both have their EFI partition (separate bootloaders, less worries. F11 to choose bootloader, go to OpenCore and boot Mac).
- I only use OpenCore to boot Mac. Easiest and works for me. Windows often modifies the EFI partition when updating. I am aware there's a way to prevent this. I'm just using the simplest solution.
- APFS partition.
- Please take care of your own MLB, Serial Number, and UUID.

**Few Highlights**
- CPU Profile set to mostly High Performance, since my CPU and GPU temp never really exceed 80℃ (full load).
- No bluetooth, a USB Wi-fi dongle.
- No FileVault.
- iServices works.

**BIOS Settings**
- Just follow the guide on Dortania's.

**Limitations**
- Shutdown needs me to press the power button after screen off (forced).
- I don't check things like Continuity, since I don't own an iDevice and use bluetooth (planning to buy one though).
- https://dortania.github.io/OpenCore-Post-Install/)

**BENCHMARK COMING UP, IGNORE BELOW**
![Image of CPU](https://github.com/felixyonathan/Asus-TUF-FX504GE-OpenCore/raw/master/CPU.png)
![Image of OpenCL](https://github.com/felixyonathan/Asus-TUF-FX504GE-OpenCore/raw/master/OpenCL.png)
