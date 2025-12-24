# The WorkPad

A 3x3 macropad made with the help of [Hack Club](https://hackclub.com/)'s [Hackpad](https://hackpad.hackclub.com) program.\
The device features 8 backlit keys, a rotary encoder, an OLED screen, and an XIAO RP2040 as its microcontroller.
<img width="502" height="438" alt="Screenshot 2025-12-24 at 9 51 58 AM" src="https://github.com/user-attachments/assets/3c5077b8-cd2a-45e4-b47a-adc0f90291b5" />
<img width="709" height="570" alt="Screenshot 2025-12-24 at 9 52 16 AM" src="https://github.com/user-attachments/assets/8b89cc5d-790b-44bf-84f8-76a0a83ee80f" />

## Schematic
<img width="874" height="609" alt="Screenshot 2025-12-23 at 7 32 57 PM" src="https://github.com/user-attachments/assets/96de6ff6-db1a-421f-a7dc-65f70ea8e322" />

## PCB
<img width="898" height="634" alt="Screenshot 2025-12-23 at 7 32 41 PM" src="https://github.com/user-attachments/assets/2d3ac2f0-205f-4257-a3b4-88fee6328e7b" />

## Case
<img width="1197" height="603" alt="Screenshot 2025-12-24 at 3 42 01 PM" src="https://github.com/user-attachments/assets/9f82cce4-ae77-4bfb-bf01-447d4b63bbf2" />
<img width="1197" height="603" alt="Screenshot 2025-12-23 at 7 35 03 PM" src="https://github.com/user-attachments/assets/4f7e9165-f8da-43ca-926a-4c0cbed66dc0" />
<img width="1197" height="603" alt="Screenshot 2025-12-23 at 7 35 09 PM" src="https://github.com/user-attachments/assets/e8bb432d-ea33-4390-8cc1-f47ae891a24b" />

The case is assembled using four M3 bolts and four M3 heat-set inserts.
The case is made of three separate printed pieces.

## Firmware

This macropad uses [QMK](https://docs.qmk.fm/) for firmware.

- Rotary encoder knob adjusts the volume.
- By default, each key is bound to type out a number. The keys can type out the numbers 1 through 9. (There aren't enough keys to type out the number 0)
- This macropad is compatible with [VIA](https://caniusevia.com/), so that it can actually macro.
- The OLED screen should play the animation below at all times\
![a .gif file of the animation, which shows a ball that flies back and forth](firmware/assets/placeholder-animation.gif)
  - Still playing with the idea of displaying useful information.

## Bill of Materials (BOM)

Physical materials needed to make this macropad:

- 8x Cherry MX Switches
- 8x DSA Keycaps
- 1x EC11 Rotary Encoder
- 9x Through-hole 1N4148 Diodes
- 9x SK6812 MINI LEDs
- 4x M3x16mm Screws
- 4x M3x5mx4mm Heatset Inserts
- 1x 0.91" OLED Display
- 1x Seeed Studio XIAO RP2040
- 1x 3D printed knob for the rotary encoder
- 1x 3D printed case (3 separate pieces)

## Copyright

Copyright (C) 2025 Supratik

This Source Code Form is subject to the terms of the Mozilla Public License, v. 2.0. If a copy of the MPL was not distributed with this file, You can obtain one at <https://mozilla.org/MPL/2.0/>.
