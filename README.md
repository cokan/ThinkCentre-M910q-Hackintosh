# ThinkCentre-M910q-Hackintosh

# System configuration
|Model  |iMac19,1  |Version	|BigSur 11.6|
| :----- | :----- |:----- |:----- |
|Processor |Intel Core i5-6600T	|Graphics	|Intel HD Graphics 530|
|Memory	   |Samsung 3200MHz DDR4 8GB	|OS Disk	|Micron 2200S NVMe 256GB|
|Audio	   |Realtek ALC294	|WiFi/Bluetooth	|Intel AC8265|
|BIOS      |Lenovo Inc. M1AKT34A  | Opencore| release 0.7.6


# BIOS

|Setting item|Var Store|Variable|Initial value|Modify value|
| :----- | :----- |:----- |:----- |:----- |
|DVMT|SaSetup|0x7AC|0x01|0x03（96MB）|
|CFG Lock|CpuSetup|0x503|0x01|0x00 |

# N. Log

+ [M910Q](https://github.com/gxz0233/M910Q_Hackintosh)
+ [OpenCore test](https://opencore.slowgeek.com/)
+ [ProperTree](https://github.com/corpnewt/ProperTree)
+ [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)
+ [SSDTTime](https://github.com/corpnewt/SSDTTime)
+ [Intel Bluetooth](https://github.com/OpenIntelWireless/IntelBluetoothFirmware)
+ [Intel WiFi](https://github.com/OpenIntelWireless/itlwm)
+ [Audio](https://github.com/acidanthera/appleALC/wiki/Supported-codecs)
+ [iGPU Intel processors](https://github.com/acidanthera/WhateverGreen/blob/master/Manual/FAQ.IntelHD.en.md)
+ [not read Nvme](https://zhuanlan.zhihu.com/p/371775428?ivk_sa=1024320u)
