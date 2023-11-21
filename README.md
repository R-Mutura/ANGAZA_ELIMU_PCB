# ANGAZA_ELIMU_PCB

This repo contains the Hardware design and production files for the `Angaza Elimu Smart Farm` board.
 ###  Version 1.0.0 Solarless_Board 
 please refer to the attached release for all the production files.

## Description
The board main features of this Board include:
- RP2040TR7 - Rpi-Pico as the main MCU
- ESP12F - to prvide BLE and WiFi capabilties
- Lora Module RA-02 - with SMA connector  for extrnal antenna support - frequency 868mHz
- RS485 for communication with ground based sensor.
- Relay isolated outputs
- Mosfet Output with selectable power source - Lowside driver configuration
- 24V and 5V output - with overcurrent protection
- 0mA - 20mA  / 4mA - 20mA sensor input (eg Platinum temeprature sensor)
- and other communication interfaces

POWER FEATURES
- 24V  input
- Battery charger interface - MCP Lipo/LiIon charger with upto 1A output
- 5V boost convertor via TPS61022 - upto 3A output. Smart heat decipation incorporated into the PCB design
- 5V output Buck , 3V3 output Buck
- Low battery Threshold Trigger
- USB power input with ability for programming and troubleshooting.
## Items
In the repo you will find:
- 📁 3D_FILES - step files for mechanical linkage, design and reference
- 📁 ASSETS - Helpful matterial pertaining to the project - Datasheet, Design guides etc
- 📁 BOM - bill of materials
- 📁 Gerber - PCB manufacturing files
- 📁 Images -  Images for ease visaul inspection
- 📁 Placement_Files - Component assembly CSV files for use with Pick-n-Place machines
- 📁 SCH_PDF - PDF version of the schematic Design
- 📁 src - Contains all the Design files with relation to KiCad and the project. Should be accessed and modified by a skilled personel.
![RpiPico_Agriboard 3](https://github.com/R-Mutura/ANGAZA_ELIMU_PCB/assets/85989401/b7e07d5f-58e6-4f2e-96d0-021b6e61bfde)
![RpiPico_Agriboard 4](https://github.com/R-Mutura/ANGAZA_ELIMU_PCB/assets/85989401/049f191a-b9ae-424b-9097-3bda700357a2)



- # THANK YOU.
