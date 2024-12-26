# HP-au146tx-Hackintosh
This is an OPENCORE efi spacifically for HP Pavilion au146tx to boot into macOS ventura.

## Warning
1. This efi is strictly for ventura only, for now.
Want Sequoia? See [here](https://github.com/brlse/hp-au146tx-sequoia-efi)!
2. Since I had remove the battery off from my laptop, I haven't install the SMCBatteryManager.kext. Add into both folders and plist if needed.
3. Generate a set of S/N, MLB and UUID yourself.
4. You might need to build your own USBMap kext.
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
- dGPU NV GTX 940MX
- Airdrop, as the Wi-Fi vendor is intel
- The amazing chime at startup
- A tray-icon of the SDXC reader, can be closed manually though.

## Credits
- dortania.github.io
- github.com/acidanthera
- elitemacx86
