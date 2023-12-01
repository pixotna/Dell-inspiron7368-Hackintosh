# Dell-inspiron7368-Hackintosh
- Opencore 0.9.4 release
- MacOS Big Sur 11.6.6 (20G624)
- CPU intel i5-6200U
- Wi-Fi adapter intel Ax210 (If your OS is Monterey or later, you should update AirportItlwm.kext and intel bluetooth driver.)
- The touchscreen and touchpad are functioning properly （VoodooI2CHID.kext is modified, [key]VoodooI2CHIDDevice[/key] and the following [dict][/dict] deleted.）
- Audio driver PciRoot(0x0)/Pci(0x1f,0x3) layout-id 33
- All exist USB ports mapped
- All functions work well except Airdrop (can find other devices, but cannot send files, waiting for the wifi driver update)
