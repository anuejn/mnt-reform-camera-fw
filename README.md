# MNT Reform Camera Firmware

This repository contains firmware for the [MNT Reform Camera](https://shop.mntre.com/products/mnt-reform-camera).
This project is not affiliated with mnt-research.

The code here is a modified version of the Cypress FX3 SDK example `cycx3_uvc_ov5640` which is the
stock firmware that is shipped by mnt-research.

## Building

To build the code, you should have a copy of the Cypress FX3 SDK under
`~/Downloads/FX3_SDK_1.3.4_MacOS/` or change the paths in the `.envrc` according to your setup.
After that, make sure you have [direnv](https://direnv.net/) installed and execute `direnv allow`.
Then you should be able to build the firmware using `make`.

## Additions / Changes

* None at the moment
