<p align="center">
 <img width="129px" src="https://rallybr.com.br/logo-hacklegion.png" align="center" />
 <h2 align="center">MacOS on MSI Alpha 15-B5EEK - Ryzen 5800H &amp; Radeon RX 6600M </h2>
 <p align="center">MSI Alpha 15-B5EEK Opencore EFI and some info for running MacOS Sonoma. </p>
</p>
<p align="center"><img src="https://img.shields.io/badge/Bios-E158LAMS.10B-blue?logo=lenovo&amp;logoColor=%23fff" alt="" />&nbsp;<img src="https://img.shields.io/badge/Opencore-1.0.1 DEV-black" alt="" />&nbsp;<img src="https://img.shields.io/badge/MacOS-Sonoma%2014.5-green?logo=apple&amp;logoColor=%23fff" alt="" /></p>


## Considerations

_Information available only for possible references. I do not recommend following all the information presented here._

## Table of Contents

*   [Specifications](#specifications)
*   [What's Working](#whats-working)
*   [What's not Working](#whats-not-working)
*   [Bios Options](#bios-options)
*   [Kexts Used](#kexts-used)
*   [SSDTs Used](#ssdts-used)
*   [Credits](#credits)
*   [Useful Apps & Scripts](#useful-apps--scripts)
*   [Screenshots](#screenshots)


## Specifications

| Item  | Info  |
| ------------ | ------------ |
| Model  | Alpha 15 B5EEK  |
| Bios Version  | E158LAMS.10B  |
| CPU  |  AMD Ryzen™ 5 5800H Processor |
|  DGPU | AMD Radeon RX 6600M 8GB  |
| RAM  | 40GB Kingston DDR4 2400/3200 MHz  |
| NVMe  | Kingston SNV2S1000G 1TB for macOS / WD 512gb for Windows 11  |
| Ethernet  | Realtek RTL8111  |
| Audio  | Realtek ALC287  |
| LCD Panel  | 15.6 FHD IPS 120Hz  |
| Opencore Version  | 1.0.1 (DEV)  |
| SMBIOS used  | MacBookPro16,3 (Need to enter your information generated by [GenSMBIOS](http://https://github.com/corpnewt/GenSMBIOS "GenSMBIOS"))  |
| Target MacOS Version  | macOS Sonoma 14.5 <br/>_- For macOS Sonoma 14.5 Update: Temporary disable BlueToolFixup.kext, restart and run on Terminal: sudo softwareupdate -i -a -R_<br/>_- To update to MacOS Sonoma 14.4, you need to set config.plist > Misc > Security > SecureBootModel to Disabled_|
