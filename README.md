# Coffee Lake Opencore Repository
Specs:

| Hardware | Name |
|----------|------|
| CPU | Intel(R) Core(TM) i7-8700 CPU @ 3.20GHz |
| (d)GPU | NVIDIA GeForce GT 1030 |
| (i)gpu | Intel(R) UHD Graphics 630 |
| Chipset | Intel(R) 300 Series Chipset (B365) |
| Audio Codec | Realtek ALC892 |
| Network Controllers (WiFi) | TP-Link 802.11ac Network Adapter |
| Network Controllers (Ethernet) | Intel(R) Ethernet Connection I219-V |
| Disk Drive | Samsung SSD 860 QVO 1TB|
| Disk Drive | CT1000BX 500SSD1 |


Kexts: 
- Lilu
- VirtualSMC
    - SMCProcessor
- WhateverGreen
- AppleALC
- IntelMausi
- USBToolBox
- IDK WiFi and Bluetooth

SSDT:
- SSDT-AWAC
- SSDT-EC-USBX
- SSDT-PLUG
- SSDT-PMC

config.plist:
- Booter/Quirks
    - EnableWriteUnprotector ; Disabled
    - RebuildAppleMemoryMap & SyncRuntimePermissions ; Enabled
- Kernel/Quirks
    - AppleXcpmCfgLock ; enabled


Credits: 
Thank you to dreamwhite#0001 on discord he helped me throughout the whole process. 