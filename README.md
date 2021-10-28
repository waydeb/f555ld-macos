# Running macOS on an Asus F555LD laptop
______________
## System Specs:
* **CPU**: Intel i5-4210U @ 1.7GHz w/ 2.4GHz Boost clock, 2c/4t

* **GPU**: Nvidia Geforce 820M and Intel HD 4400

* **RAM**: 12GB DDR3 @ 1600MHz | 8GB SO-DIMM, 4GB Solidered

* **WiFi and Ethernet**: WiFi - Qualcomm Atheros AR9485 | Ethernet - Realtek PCIe GbE Family Controller
______________
## Software Info:
* **Bootloader**: [OpenCore](https://github.com/acidanthera/OpenCorePkg)
* **macOS Version**: macOS 12.0.1 - Monterey | Known working versions, macOS 10.14, macOS 10.15, macOS 11, macOS 12
______________
## Walkthrough
* See macOS/12/README.md
______________
## Issues:
* **Ethernet**: To have working Ethernet, you will need to use a kext injector to inject the kext either to S/L/E or L/E, loading the kext via OpenCore doesn't appear to work.
______________
## Ease of setup:
* Overall the setup for installing macOS using OpenCore was quite painless, with the only issue being Ethernet which is a quick fix within itself anyways.
______________
## Notes:
* If you want to update to macOS 12 on this system, you'll need to use MacBookPro11,4 or newer.
______________
## Questions?
* Please make an issue.
