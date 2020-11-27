# ASRock-H310-Hackintosh
* Motherboard: ASRock H310CM-DVS (latest bios version).
* CPU: Core i with iGPU (for non-iGPU user, remove PciRoot(0x0)/Pci(0x2,0x0) PCIe path).
* GPU: RX4xx/5xx (Navi RX5xxx user, you should add `agdpmod=pikera` boot-arg).
* You must fill SMBIOS with model `iMac19,1`.
* Currently sleep/wake worked well ʕ•ᴥ•ʔゝ☆
