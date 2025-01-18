# pxt-apds9960 + RGB LED module

#### Description
microbit@makecode editor: APDS9960 color detect interfaced to RGB LED module.

#### Sources
https://github.com/KittenBot/pxt-apds9960
https://docs.broadcom.com/doc/AV02-4191EN
https://wiki.keyestudio.com/Ks0032_keyestudio_RGB_LED_Module

#### Install Guide
Load this package by coping the ulr and paste into the add package panel.

#### User Guide
Read the Chip's ID first, if it return 0x0 or 0xff check your wirings. If it read something other than 0xAB (171) you may got an APDS9930 or 9900 or a cloned chips. 
The gesture engine won't work on 9930 and 9900, but the proximity and color sensing should be ok. 
The RGB LED module is Keyestudio's RGB LED module (pins: GRBV)

## License
MIT

## Supported targets
* for PXT/microbit
(The metadata above is needed for package search.)

```package
APDS9960RGB=github:delistavrou/pxt-APDS9960RGB
```
