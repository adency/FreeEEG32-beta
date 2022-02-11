# FreeEEG32-beta

### FreeEEG32 Beta, launching soon on [Crowd Supply](https://www.crowdsupply.com/neuroidss/freeeeg32)!

![basic_layout](https://github.com/neuroidss/FreeEEG32-beta/blob/master/basic_layout.jpg)

### Setup

Docker container setup (Linux). Extract the following and run:
- Compilation: `./gcc-arm-none-eabi_run.sh`
- Flashing: `sudo ./openocd_flash.sh`


[Flashing via AC6 with STM32 Blue Pill](https://github.com/neuroidss/FreeEEG32-beta/blob/master/SetupGuides/FreeEEG32_Flashing_via_AC6_w_STM32F103_BluePill.md)

The AC6 stuff is deprecated but the blue pill is still needed.

[OpenVIBE Setup](https://github.com/neuroidss/FreeEEG32-beta/blob/master/SetupGuides/FreeEEG32_OpenVibe_Docker_Readme.md)

### Production files
Gerber:   https://github.com/neuroidss/FreeEEG32-beta/blob/master/AssemblyFiles/KiCAD/out/gerber.zip

Assembly: https://github.com/neuroidss/FreeEEG32-beta/blob/master/AssemblyFiles/KiCAD/out/assembly.zip

BOM:      https://github.com/neuroidss/FreeEEG32-beta/blob/master/AssemblyFiles/bom/components%20FreeEEG32%20beta.csv

PCB fabrication constraints:
* Dims: 70mm x 70mm
* Layers: 4
* Thickness: 1.6mm (can vary, thicker = sturdier)
* Surface finish: HASL Lead free or ENIG (more expensive)
* Material: FR4

Assembly constraints:
* Unique parts: 33 (27 without pin headers)
* SMT Pads:  169
* Thruhole: 23 (pin headers only)
* Assembly sides: both


This project is being launched with the help of [HEG Alpha](hegalpha.com) to make science more accessible.
Custom 2 channel and 19 channel headsets are available by Bernard Markus.

### More

Neuroidss home: https://neuroidss.com

[Alpha 1.5 repo with more content and tests](https://github.com/neuroidss/FreeEEG32-alpha1.5)

[BrainFlow support](https://brainflow.readthedocs.io/en/stable/)

[Webapp (WIP)](https://github.com/moothyknight/eegpwa)

