# T480-Hackintosh-Clover-Bootloader


MacOS 10.15.5 tested on Thinkpad T480 with 2K Screen, i7-8650U Processer and 16 GB RAM.

Put the BOOT and CLOVER folder inside the EFI folder on your EFI partition.
The Clover used here is version 5119.

All external ports, the keyboard, trackpad and screen work well.
Hibernation function is also enabled, and works fine.

The camera, facial recognition fuction and fingerprint sensor are incompatable with macOS, and are disabled.
The original intel wifi card won't work. The DW1820A or DW1560 card will work, with the right config.plist file included here. 

Do notice that the trackpad may not work if macOS is installed on a NVMe SSD other than a SATA one, and I don't know why.


