# T480-Hackintosh-Clover-Bootloader


MacOS 10.15.5 tested on Thinkpad T480 with 2K Screen,IR camera, i7-8650U Processer, 16GB RAM, 256G NVMe SSD and 512 SATA SSD.

Put the BOOT and CLOVER folder inside the EFI folder on your EFI partition.
The Clover used here is version 5119.

Things work:  
>All external ports,  
>Keyboard,  
>Trackpad,  
>Screen,  
>Wifi (DW1820A or DW1560),  
>Bluetooth,  
>Camera,  
>Hibernation and other system functions.  

Things don't work:  
>IR facial recognition，  
>Fingerprint sensor.  
  
The default config files is for machines with DW1820A and a IR camera. Files for machines with a DW1560 and no IR camera are also included, or you can customize your own USBports.text with Hackintool.app.
Do notice that the trackpad may not work if macOS is installed on a NVMe SSD other than a SATA one, and I don't know why yet.


