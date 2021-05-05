---
parent: Harmony 3 driver and system service application examples for SAM C20/C21 family
title: EEPROM Emulator library read write
has_children: false
has_toc: false
---

[![MCHP](https://www.microchip.com/ResourcePackages/Microchip/assets/dist/images/logo.png)](https://www.microchip.com)

# EEPROM Emulator library read write

This application example demonstrates how to read and write to the Emulated EEPROM memory space using the EEPROM Emulator library.

## Description

This example uses EEPROM Emulator library to read and write to the RWWEE Emulated EEPROM memory space. The application first checks if the library was initialized successfully or not. When running the application for the first time, the EEPROM
Emulator memory space will be formatted by the application. The application then writes data to EEPROM memory space using the APIs provided by the EEPROM Emulator library and then reads the data back and compares it with the written data.

## Downloading and building the application

To clone or download this application from Github, go to the [main page of this repository](https://github.com/Microchip-MPLAB-Harmony/core_apps_sam_c20_c21) and then click Clone button to clone this repository or download as zip file.
This content can also be downloaded using content manager by following these [instructions](https://github.com/Microchip-MPLAB-Harmony/contentmanager/wiki).

Path of the application within the repository is **apps/library/eeprom_emulator/eeprom_emulator_read_write/firmware**

To build the application, refer to the following table and open the project using its IDE.

| Project Name      | Description                                    |
| ----------------- | ---------------------------------------------- |
| sam_c21n_xpro.X | MPLABX project for [SAM C21N Xplained Pro Evaluation Kit](https://www.microchip.com/developmenttools/ProductDetails/atsamc21n-xpro) |
|||

## Setting up the hardware

The following table shows the target hardware for the application projects.

| Project Name| Board|
|:---------|:---------:|
| sam_c21n_xpro.X | [SAM C21N Xplained Pro Evaluation Kit](https://www.microchip.com/developmenttools/ProductDetails/atsamc21n-xpro) |
|||

### Setting up [SAM C21N Xplained Pro Evaluation Kit](https://www.microchip.com/developmenttools/ProductDetails/atsamc21n-xpro)

- No additional hardware is required to run this demo
- Connect the Debug USB port on the board to the computer using a micro USB cable

## Running the Application

1. Build and program the application using its IDE
2. LED indicates success or failure:
    - The LED is turned ON when the value read from the Emulated EEPROM memory region matches with the written value

Refer to the following table for LED name:

| Board | LED Name |
| ----- | -------- |
|  [SAM C21N Xplained Pro Evaluation Kit](https://www.microchip.com/developmenttools/ProductDetails/atsamc21n-xpro) | LED0 |
|||
