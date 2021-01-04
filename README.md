# Hackintosh Catalina Setup for Gigabyte Z390 Aorus Elite

### Update 20210104
- Use GUI boot picker instead text mode with [this guide](https://dortania.github.io/OpenCore-Post-Install/cosmetic/gui.html)
- Use Binary resources with [this repo](https://github.com/acidanthera/OcBinaryData)
- Use BigSur Icons with [this repo](https://github.com/khronokernel/OpenCanopy-Big-Sur)
- Drivers upgrade to newest which adapted with OpenCore 0.6.4
- Changed [MISC] -> [Boot] -> [Picker Attributes] to "1" which means *Provides custom icons for boot entries*
- Changed [MISC] -> [Security] -> [Scan Policy] to "28248323"(0x1AF0903) which means *Allow OpenCore to Scan APFS, NTFS, SATA, SASEX, SCSI, NVME, USB, SDCARD, PCI* 


### Update 20201219
Update to opencore 0.6.4, now it supports MacOS Big Sur.

This build is "Vanilla", and you may follow [this guide](https://dortania.github.io/OpenCore-Install-Guide/)

### Hardware
- Gigabyte Z390 Aorus Elite (bios F10c)
- Intel i7 9700k (oc 4.7 GHz)
- 64GB Kinstone DDR4 3200 (16G X4)
- 1 x Sapphire RX 5700XT 8G 
- 1 x Samsung 970 EVO NVMe M.2 1T (Catalina Installation)
- 1 x TOSHIBA-RC500 500GB (Windows 10 Installation)
- 1 x Broadcom BCM94360CS PCIe (Wi-Fi + Bluetooth)

