# ESP32 Custom Board
A custom ESP32-based development board designed and routed using EasyEDA.
This project is designed as a compact and reusable ESP32 development platform for IoT, embedded systems, automation, sensors, Wi-Fi, and Bluetooth-based projects.

## Features

- ESP32-based custom development board
- Wi-Fi connectivity
- Bluetooth connectivity
- USB interface for programming and power
- GPIO header pins for external components
- BOOT/RESET control buttons
- Custom PCB layout and routing
- Compact development-board design
- Designed and routed in EasyEDA
- Editable PCB design file included
- 3D OBJ model included
- Gerber manufacturing files included

## Board Overview

The custom PCB contains:

- ESP32 module
- USB connector
- USB-to-serial/programming circuitry
- Power and supporting circuitry
- BOOT/RESET control buttons
- GPIO header pins
- Passive components
- Custom PCB traces and routing

## Project Files

### PCB Design

- `PCB/PCB_PCB_ESP32_2026-09-11.json` - Main EasyEDA PCB design/source file.
- `Autorouter/Autorouter_PCB_ESP32_2026-09-11.dsn` - Autorouter design file.

### 3D Model

- `3D/ESP32.obj` - 3D OBJ model of the PCB.

### Manufacturing Files

- `Gerber/Gerber_ESP32_PCB.zip` - Gerber files for PCB manufacturing.

### Images

The `Images` folder contains PCB design, routing, and 3D preview images.

## PCB Preview

### PCB Design

![ESP32 PCB Design](Images/pcb-design.png)

### PCB Routing

![ESP32 PCB Routing](Images/pcb-routing.png)

### Front 3D View

![ESP32 PCB Front](Images/pcb-3d-front.png)

### Back 3D View

![ESP32 PCB Back](Images/pcb-3d-back.png)

### Build Photo: Not available yet

## Software Required

To view or modify the PCB design:

- EasyEDA

The OBJ model can be viewed using any software that supports `.obj` 3D files.

## How to Open the PCB Design

1. Download the PCB source file from the `PCB` folder.
2. Open EasyEDA.
3. Import/open the downloaded PCB design file.
4. View or modify the PCB layout in EasyEDA.
5. Check the component footprints, PCB dimensions, layers, routing, and design rules before making changes.

## How to Manufacture the PCB

### Step 1 - Download the Design

Download the PCB design file from the `PCB` folder.

You can also download the Gerber ZIP from the `Gerber` folder if you want to manufacture the PCB directly.

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

Run the DRC in EasyEDA and fix any errors before manufacturing.

### Step 3 - Generate or Use Gerber Files

The repository already contains a Gerber ZIP file in the `Gerber` folder.

The Gerber files contain the information required by a PCB manufacturer, including:

- Copper layers
- Solder mask
- Silkscreen
- Board outline
- Drill information

If you make changes to the PCB design, generate a new Gerber package from EasyEDA before ordering the PCB.

### Step 4 - Prepare the Components

Use the PCB design and component information to identify the components required for assembly.

A Bill of Materials (BOM) can be prepared containing:

- Component value
- Component/package
- Quantity
- Part number or manufacturer part number where applicable

### Step 5 - Order the PCB

Upload the Gerber ZIP file to a PCB manufacturing service.

Select the required manufacturing specifications, such as:

- PCB quantity
- Number of layers
- PCB thickness
- Surface finish
- Solder mask
- PCB color
