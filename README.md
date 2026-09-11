# ESP32 Custom Board

A custom ESP32-based development board designed and routed using EasyEDA.
This project is designed as a compact and reusable ESP32 development platform for IoT, embedded systems, automation, sensor, Wi-Fi, and Bluetooth-based projects.
The board includes an ESP32 module, USB interface, control buttons, power and supporting circuitry, and GPIO headers for connecting external components.

## Features
- ESP32-based custom development board
- Wi-Fi connectivity
- Bluetooth connectivity
- USB interface for programming and power
- GPIO header pins for external components
- Reset/boot control buttons
- Custom PCB layout
- Compact development-board design
- Designed and routed in EasyEDA
- Editable PCB source files included

## Board Overview

The custom PCB contains:
- ESP32 module
- USB connector
- USB-to-serial/programming circuitry
- Power regulation and supporting components
- BOOT/RESET control buttons
- GPIO header pins
- Passive components required for the board
- Custom PCB traces and routing

## Project Files
- `PCB_PCB_ESP32_2026-09-11.json` - Main EasyEDA PCB design/source file.
- `Autorouter_PCB_ESP32_2026-09-11.dsn` - Autorouter design file.

## Software Required
To modify or view the PCB design:
- EasyEDA

## PCB Preview

![ESP32 PCB Front](Images/pcb-3d-front.png)

## How to Open the PCB Design

1. Download the `.json` PCB source file from this repository.
2. Open EasyEDA.
3. Import/open the downloaded EasyEDA source file.
4. The PCB layout can then be viewed and modified in EasyEDA.
5. Check the schematic, footprints, PCB dimensions, layers, and design rules before making changes.

## How to Manufacture the PCB

### Step 1 - Open the Design in EasyEDA
Download the PCB source file from this repository and open it in EasyEDA.

### Step 2 - Check the Design
Before manufacturing, verify:

- PCB dimensions
- Component footprints
- Track routing
- Drill holes
- Component orientation
- Power connections
- USB connections
- ESP32 module footprint
- GPIO headers
- Design Rule Check (DRC)

Run the DRC in EasyEDA and fix any errors that need to be corrected.

### Step 3 - Generate Gerber Files
In EasyEDA, generate the PCB fabrication/manufacturing files.
The manufacturer normally uses the Gerber files to manufacture the bare PCB.
The generated Gerber package should contain the required PCB layer information such as:

- Copper layers
- Solder mask
- Silkscreen
- Board outline
- Drill information

### Step 4 - Generate the BOM
Generate a Bill of Materials (BOM) containing the components required to assemble the board.
The BOM should include information such as:
- Component value
- Component/package
- Quantity
- Part number or manufacturer part number where applicable

### Step 5 - Order the PCB
Upload the generated Gerber ZIP file to a PCB manufacturing service.
Select the required PCB specifications such as:

- PCB quantity
- Number of layers
- PCB thickness
- Surface finish
- Solder mask
- PCB color
