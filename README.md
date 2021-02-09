# AsRock-H410M-OpenCore
[![GitHub version](https://img.shields.io/badge/OpenCore-0.6.6-brightgreen)](https://github.com/acidanthera/OpenCorePkg)

This is the files and configuration for setting up the AsRock H410M desktop using OpenCore.

OpenCore EFI file and Shell included. Basically you could just download, copy, paste, modify few things, and use.

I use MacOS primarily for music works. 

**Specs**
- MacOS Catalina 10.15.6 (should be fine from 10.15.4)
- Intel i5 10400F, 16 GB RAM, ASUS AMD RX 5500XT 4GB. 256 GB SATA SSD: Mac, 240 GB M.2 SSD: Windows. Both have their EFI partitions (separate bootloaders, less worries).
- I only use OpenCore to boot Mac. Easiest and works for me. Windows often modifies the EFI partition when updating. I am aware there's a way to prevent this. I'm just using the simplest solution.
- APFS.
- Please take care of your own MLB, Serial Number, and UUID.

**Few Highlights**
- CPU Profile set to mostly High Performance (CPUFriend), since my CPU and GPU temp never really exceed 80℃ (full load).
- No bluetooth, wi-fi using TP-Link USB dongle.
- No FileVault.
- iServices works (I only checked iMessage using an iPhone 5S).
- USB Mapped. If you plan to clone this repo, make sure you USB Map again.
- Shutdown is working normally.

**BIOS Settings**
- Just follow the guide at Dortania.

**Limitations**
- I don't check things like Continuity, since I do not use bluetooth (not planning to fix).

**BENCHMARK: SIMILAR TO SYSTEMS WITH SIMILAR SPECS. DO NOT BOTHER TO DO.**
