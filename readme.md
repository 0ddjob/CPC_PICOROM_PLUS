# CPC+ ROM Emulator using Raspberry Pi Pico
Based on [Matt Callow's](https://github.com/mattcallow/CPC_PICOROM) original design for the CPC.

## Current Status: UNTESTED!
18-Nov-2024: initial design done

## Instructions
Please refer to Matt's page for firmware & instructions on how to initialise the Pico & transfer/use Amstrad CPC ROMs.

## Parts
- Raspberry Pi Pico
- 50-way male Centronics connector (NorComp 111-050-113L001?)
- 2 x tactile switch (for reset)
- 5 x 1N4148 diodes

## Design
Designed using Kicad.<br>
Files, including Gerbers for production, can be found [here.](/Hardware/CPC_PICOROM_PLUS/)<br>
Centronics connector [Kicad symbol.](/Hardware/Centronics_Connector/)<br>
Raspberry Pi Pico [Kicad symbol.](https://github.com/ncarandini/KiCad-RP-Pico)<br>

![Schematic](/CPC_PICOROM_PLUS_Schematic.png)

![PCB layout](/CPC_PICOROM_PLUS_PCB.png)
