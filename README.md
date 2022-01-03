
This is fork of https://github.com/waveshare/LCD-show.

Changes in this fork make it possible to use Waveshare 3.5 LCD(A)
with _64-bit_ beta Raspberry PI OS.

The code was tested with: https://downloads.raspberrypi.org/raspios_arm64/images/raspios_arm64-2021-11-08/ release.

Sorce code for device tree's can be found here: https://github.com/swkim01/waveshare-dtoverlays/blob/master/dtc.sh
`dtb` files can be decomposed using `dtc` command:
```
dtc -I dtb -O dts /boot/overlays/waveshare35a.dtbo
```

:warning: I made this code changes for my personal purposes. Bug reports and PRs will be ignored. :warning:

# 3.5inch RPi LCD (A)

### Description:

This is a 3.5inch TFT LCD with resistive touch panel, has 480x320 resolution. Can support any revision of Raspberry Pi. Driver is provided for Raspbian/Ubuntu Mate/kali. 

### Website:

CN:http://www.waveshare.net/shop/3.5inch-RPi-LCD-A.htm

EN:https://www.waveshare.com/product/3.5inch-rpi-lcd-a.htm

### WIKI:

CN:http://www.waveshare.net/wiki/3.5inch_RPi_LCD_(A)

EN:https://www.waveshare.com/wiki/3.5inch_RPi_LCD_(A)

### Driver install:

sudo ./LCD35-show