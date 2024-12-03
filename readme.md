# CPC+ ROM Emulator using Raspberry Pi Pico
Based on [Matt Callow's](https://github.com/mattcallow/CPC_PICOROM) original design for the CPC.

## Current Status: UNTESTED!
- 18-Nov-2024: initial design done
- 20-Nov-2024: test PCBs on their way from PCBWAY
- 3-Dec-2024: PCBs arrived (eight working days)
- 3-Dec-2024: Initial testing ... not working!  (not really a surprise)

## Instructions
Please refer to Matt's page for firmware & instructions on how to initialise the Pico & transfer/use Amstrad CPC ROMs.<br>
ROMs can be found [here](https://www.cpcwiki.eu/index.php/ROM_List).

## Parts
- Raspberry Pi Pico
- 50-way male Centronics connector (NorComp 111-050-113L001?)
- 2 x tactile switch (for reset)
- 5 x 1N4148 diodes

## Design
Designed using Kicad.<br>
Files, including Gerbers for production, can be found [here.](/Hardware/)<br>
Centronics connector [Kicad symbol.](/Hardware/Centronics_Connector/)  I also made a custom version with signal names on the pins (see schematic image below).<br>
Raspberry Pi Pico [Kicad symbol.](https://github.com/ncarandini/KiCad-RP-Pico)<br>

![Schematic](/CPC_PICOROM_PLUS_Schematic.png)

![PCB layout](/CPC_PICOROM_PLUS_PCB.png)
