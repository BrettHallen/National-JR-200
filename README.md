# National JR-200
Information about the National/Panasonic JR-200 computer.<br>

This machine uses a HN1800A which seems to be a mix of the MC6800 and MC6802: it requires an external clock (like the MC6800) but with has internal RAM (like the 6802).  In the JR-200 though the internal RAM disabled.<br>

It was exported to the US as the JR-200U and Europe as the JR-200UP (PAL).<br>

Its main parts are:
- MN1800A CPU
- HD61K201F CRT controller (also generates timing)
- MN1271 I/O interface (equivalent to two 6522 VIAs?)
- MN1544CJR 4-bit microprocessor for the keyboard & joystick I/O

## YouTube Videos
- [Part 1: First Look](https://youtu.be/wLMDZcOQIaI)
- [Part 2: Missing Φ2 Clock?](https://youtu.be/HDSBuGudi-w)
- [Part 3: A Second JR-200 Appears](https://youtu.be/Jg6vPXeS__c)

## [DIN to VGA Adaptor](/JR-200_DIN-to-VGA)
A simple board to convert the JR-200's 8-pin DIN socket for video output to a VGA socket (RGB) and RCA jack (composite).<br>

## [Troubleshooting Φ2 Clock](/Missing_PHI2_Clock)
My first JR-200 doesn't work - the HD61K201F isn't correctly generating the Φ2 clock signal, thus the machine won't boot.<br>

![Boot screen](/Missing_PHI2_Clock/JR-200_Boot_screen_missing_PHI2.jpg)

## Useful Links
- [yanataka60さん's SD interface (JP)](https://github.com/yanataka60/JR-200_SD)
- [JR-200 General Info (JP)](https://jr200.web.fc2.com/index.html)
- [Technical scans & ROMs (EN)](https://gitlab.com/retroabandon/panasonic-jr)
