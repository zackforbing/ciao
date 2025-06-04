![GitHub](https://img.shields.io/badge/CC--BY--NC-test?style=flat-square&logo=creativecommons&logoColor=ffffff&label=%20&labelColor=8CBA04&color=8CBA04)

# Ciao!

![Chaz](/images%20ADD/front.png)
![Chaz](/images%20ADD/back.png)

Low Profile, Choc-spaced QAZ-alike, with NEW Hotswap Jank Xiao BLE Plus Flavor(tm)!

#fork in progress. get these made at your own mortal peril.

## Features

- QAZ Layout
- Choc Spaced
- Choc v1/v2 compatibility (v2 choc spaced caps are future me's problem)
- Hotswap/Solder combo footprint
- Jank++ sorta socket mounted xiao ble plus mcu
- Multiple reversible-polarity battery connections - universal (side) and JST-ACH (top and side)
- Someday maybe even a case!
- [Open Source](/pcb)

## Changelog

- v0.1 - unverified as of yet xiao ble plus mcu version
- v0.0.1-v0.0.1000 - kicad is hard

## Credits

- tominabox1 and whydobearsxplod for the original QAZ
- [Jason Hazel](https://github.com/hazels-garage) for bringing Ciao!'s big brother Chaz into the world and inspiring me to learn kicad finally

## original chaz readme bits below for me to crib from later

![Chaz](/images%20ADD/chaz03.jpg)
Low Profile, Choc Spaced QAZ-alike

## Materials

- 1x Chaz PCB & Switchplate - [Buy](https://shop.hazel.cc/products/chaz-v03) - [Source](/source)
- 2x 2U Kailh Choc Stabalizers
- 37x Kailh Choc v1 Switches
- 37x Keycaps
  - 31x 1u
  - 2x 1.25u
  - 1x 1.75u
  - 1x 1.5u
  - 1x 2u
  - 1x 2.25u
- 1x [Case](case/)
- 6x M2x6 countersunk screws

## Build Steps

- Insert switches into switchplate
  - **NOTE**: There are 3 switches rotated differently from the rest. Check the PCB to make sure you've got the correct orientation
- [Insert stabalizers](https://docs.keeb.io/choc-stabs)
- Place switchplate with switches onto PCB and press all the switches into their homes.
- Solder Switches
- Insert into case
- Screw Case to PCB from the bottom

## Firmware

To get into DFU, hold the DFU button on the bottom of the PCB while plugging in USB.

- [QMK](https://github.com/hazels-garage/qmk_firmware/tree/hazel/chaz)
- [VIAL](firmware/hazel_chaz_v03_vial.bin)
- [ZMK](https://github.com/hazels-garage/zmk-chaz)
