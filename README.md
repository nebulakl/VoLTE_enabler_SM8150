# VoLTE Enabler for Snapdragon 855 devices

On some carriers, VoLTE would not work without the appropriate firmware. This magisk module aims to fix this problem by replacing the stock mbn files with the ones in the `Mi 9 (cepheus) V12.5.6.0.RFACNXM` firmware package.

This is especially useful if you are using e.g. a Pixel 4 phone in an unsupported country/carrier.

This module has only been tested on Snapdragon 855 (SM8150) devices. You can find a list of phones that use this chip at https://en.wikichip.org/wiki/qualcomm/snapdragon_800/855#Utilizing_devices.

Note that you may also need to manually edit your APN settings for the best online experience. You can often find this information by Googling `<your carrier> APN`. A list of APN settings from the same firmware package is also included in the `apns-conf.xml` file in this repo. Locate your APN settings by searching the Mobile Country Codes (MCC) and Mobile Network Codes (MNC). If your carrier is a Mobile Virtual Network Operator (MVNO), you will also need this information when creating APN entries.

## Acknowledgment

This module contains code from these projects:

https://github.com/edgd1er/voenabler

https://github.com/hyx0329/VoLTE-Patch-for-Pixel4
