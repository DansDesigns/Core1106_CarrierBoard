
# Core1106_CarrierBoard
 Carrier Board for LuckFox Core1106 Linux SBC
![LuckFox_Core1106_EasyRead_Pinout](https://github.com/user-attachments/assets/b2130b50-3a8a-4c69-81b6-4ffb267ba8a8)
## Features:

* All usable GPIO's are connected to 2.54mm Pin Headers (all 3.3v Logic EXCEPT Pin20 (1.8v MAX))
* ALL SMD Pads are 1.8v, EXCEPT for ENET (Ethernet)
* USB-C Programming/USB Host
* USB Mode Switch connects 3.3v & USB_VBUSDET (Enable to enter USB Device Mode, PRESS BOOT + RESET to enter Flash Mode)
* 2N2222 Transistor with ENABLE on Pin27 does same ^^^^^^ (when Pin27 is HIGH (1.8v))
* 5v pins on H6 are directly connected to USB - can be used for In/Out
* 3v3 pins are powered by "3v3" LDO (shared with 3v3SYS) (max 500ma)
* User LED connected to Pin20 (GPIO3_C6d)
	- Connect Solder Pads to ENABLE
* 
