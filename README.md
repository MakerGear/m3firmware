# Firmware for the MakerGear M3.

Built on the orginal Marlin Firmware
https://github.com/MarlinFirmware/Marlin



## Branch Information
This branch (master) is for M3SE Rev0 and M3ID Rev0

For M3SE Rev1 and M3IS REV1 see branch (1.1.6)
https://github.com/MakerGear/m3firmware/tree/1.1.6




## Firmware Configuration


Before you can compile, you must select your 3D printer configruation by renaming the correct configuration file.

### For The M3SE rename


*Configuration_makergear.h.m3SE*


to


*Configuration_makergear.h*




### For The M3ID rename


*Configuration_makergear.h.m3ID*


to


*Configuration_makergear.h*


## Building and Uploading

This firmware has been tested with the commandline version of PlatformIO

http://platformio.org/

It has not been tested with the latest version of the Arduino IDE, though there are no changes that should cause any conflicts. We reccomend you try Arduino 1.8 or higher.