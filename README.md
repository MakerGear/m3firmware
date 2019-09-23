# Firmware for the MakerGear M3.

Built on the orginal Marlin Firmware
https://github.com/MarlinFirmware/Marlin



## Branch Information
This branch (1.1.6) is for M3SE Rev1 and M3ID Rev1

For M3SE Rev1 and M3IS REV1 see branch (master)
https://github.com/MakerGear/m3firmware/tree/master


##Firmware Configuration


Before you can compile, you must select your 3D printer configruation by editing the file

Marlin/Configuration_makergear.h

Uncomment one of the #define statements depending on your printer. For example if you have an M3-ID Rev1, find


`//Standard M3 ID Rev1 with Probe`

`// #define MAKERGEAR_MODEL_M3_ID_REV1_000`

and replace it with

`//Standard M3 ID Rev1 with Probe`

`#define MAKERGEAR_MODEL_M3_ID_REV1_000`


