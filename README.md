# HP-au146tx-Hackkintosh
This is an OPENCORE efi spacifically for HP Pavilion au146tx to boot into macOS ventura.

## Warning
1. This efi is strictly for ventura only, for now.
2. Since I had remove the battery off from my HP laptop, I haven't install the SMCBatteryManager.kext. Add into both folders and plist if needed.
3. Generate a S/N, MLB and UUID yourself.
4. Didn't map USB port, used USBInjectAll.kext instead and worked just fine for me. 
5. Deploy at your own risk!

## Specsheet
- Intel(R) Core(TM) i5-7200U @2.5GHz
- Intel HD Graphics 620, Total Shared Mem=4038MiB
- Realtek ALC295 [C1], alcid=77
- Intel(R) Dual Band Wireless-AC 3168 NGW
- Realtek RTL8139/810x Fast Ethernet Adapter | RTL810xE (100Mbps)
- Synaptics SMBus TouchPad (PS/2 in linux)
- Standard PS/2 Keyboard

## What won't work
- Well, dGPU NV GTX 940MX of course.
- Airdrop, as the Wi-Fi card vendor is intel.
- The amazing chime at startup, no matter what I did.
- Despite edited in DP, almost all of PCIe still unknown in system info app. (work fine)
- A tray-icon if you active the SDXC reader, can be closed manually though.

## Credits
- dortania.github.io
- github.com/acidanthera
- youtube.com/elitemacx86
