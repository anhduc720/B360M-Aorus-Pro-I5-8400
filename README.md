# EFI Opencore 0.7.4

## Hardware Info
 - Mainboard: Gygabyte B360 M AORUS PRO (rev. 1.0)
 - CPU : Intel(R) Core(TM) i5-8400 CPU @ 2.80GHz
 - Hard Disk: Crucial MX500 500GB
 - Wifi: BCM94360CS2
 - GPU : None. iGPU only

 ## What work:
 - Audio
 - IServices like: Facetime/iMess... (Need to fake SN with [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)
 - IGPU With dual monitor ( 4K - Displayport and 1080p - HDMI). Both dual monitor at boot time and hot plug.
 - Wifi/Bluetooth/Airdrop

 ## How to
  1. Create an USB Install follow [Dortania Guide](https://dortania.github.io/OpenCore-Install-Guide/installer-guide/)
  2. Generator SN with [GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)
  3. Copy EFI here into EFI partition in USB ( need to mount it first)

 ## Credit
 - https://dortania.github.io/OpenCore-Install-Guide/installer-guide/
 - https://www.tonymacx86.com/threads/an-idiots-guide-to-lilu-and-its-plug-ins.260063/