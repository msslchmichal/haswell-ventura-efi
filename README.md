# OpenCore EFI for HASWELL MacOS Ventura Hackintosh

##My configuration 

| Component | Description |
| --- | --- |
| Motherboard | MSI Z97M-G43 |
| CPU | Intel Core i5-4690K |
| RAM | 16GB |
| iGPU | **Disabled** Intel HD4600 |
| dGPU | Sapphire Radeon RX580 8GB with 3 Displays connected |
| Audio | Realtek ALC892 (ALCID = 1) |
| Ethernet |	Realtek RTL8111 |

macOS version: 13.3.1 (22E261) 
OpenCore version: 0.9.1

## USB

If you are not using the same motherboard you should **delete Kexts/USBToolBox.kext and Kext/UTBMap.kext and map USB on your own**.

## Additional information

Generate your own **MLB**, **SystemSerialNumber** and **SystemUUID** and add it to config.plist



