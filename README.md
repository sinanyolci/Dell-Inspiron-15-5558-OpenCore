# OpenCore EFI for Dell Inspiron 15 5558 Hackintosh (MacOS 10.13 - 11.0.1)
Big Sur Pub Beta 11.0.1 with OpenCore 0.6.3

Specification
Component	Model

CPU	Intel Core i5-5500U

GPU HD Graphics 5500 & Nvidia GT920M(Disabled)

Audio Chipset Realtek ALC 255

Wifi&Bluetooh Dell Wireless 1820A (DW1820A) - Broadcom BCM4350C5 (BT 4.1)

Ethernet Realtek RTL8106E PCI Express Fast Ethernet 

OS disk Samsung SSD 850 EVO 250GB

RAM 8 GB DDR3L 1600MHz

macOS version: 11.0.1 Release Candidate 2 (20B28)

OpenCore version: 0.6.3

Credits

[Bootloader] OpenCore

[Resources] Picker GUI

[Driver] OpenRuntime

[Driver] OpenCanopy

[Driver] HFSPlus

[Driver] ExFatDxe.efi

[Kext] AirportBrcmFixup

[Kext] AppleALC

[Kext] BrcmBluetoothInjector

[Kext] BrcmFirmwareData

[Kext] BrcmPatchRAM3

[Kext] CodecCommander

[Kext] CPUFriendDataProvider

[Kext] RealtekRTL8100

[Kext] SMCDellSensors

[Kext] SMCProcessor

[Kext] SMCSuperIO

[Kext] VirtualSMC

[Kext] VoodooPS2Controller

[Kext] Lilu

[Kext] WhateverGreen


  Compatible macOS versions

High Sierra (10.13.x)

Mojave (10.14.x)

Catalina (10.15.x)

Big Sur (10.16/11.0)


  How to use
  
1.Make your USB installer with this guide

2.Clone the repository and paste "BOOT" and "OC" directories into your's pendrive "EFI" folder

3.Download GenSMBIOS to generate unique SMBIOS information. Run it and select Generate SMBIOS, as the model select iMacBookPro12,1.

4.Open config.plist with ProperTree and go to PlatformInfo > Generic. Set MLB (Board Serial), SystemSerialNumber (Serial) and SystemUUID (SmUUID) to generated values. Change ROM to your network card's MAC address without the : character.

5.Boot it!

You CAN NOT use SMBIOS from this repository, it MUST be unique for every macOS installation

