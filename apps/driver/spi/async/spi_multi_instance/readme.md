[![MCHP](https://www.microchip.com/ResourcePackages/Microchip/assets/dist/images/logo.png)](https://www.microchip.com)

# SPI driver asynchronous - multi instance

This example application demonstrates the multi instance feature of the asynchronous mode of the SPI driver by reading and writing to two EEPROMs connected to two different SPI bus.

## Description

This application uses the asynchronous mode of the SPI driver and demonstrates the multi instance feature by reading and writing to two EEPROMs connected to two different SPI bus.

The application communicates with two [EEPROM 3 click boards](https://www.mikroe.com/eeprom-3-click) that has AT24CM02 EEPROM on it.

## Downloading and building the application

To clone or download this application from Github, go to the [main page of this repository](https://github.com/Microchip-MPLAB-Harmony/core_apps_sam_c20_c21) and then click Clone button to clone this repository or download as zip file.
This content can also be downloaded using content manager by following these [instructions](https://github.com/Microchip-MPLAB-Harmony/contentmanager/wiki).

Path of the application within the repository is **apps/driver/spi/async/spi_multi_instance/firmware** .

To build the application, refer to the following table and open the project using its IDE.

| Project Name      | Description                                    |
| ----------------- | ---------------------------------------------- |
| sam_c21n_xpro.X | MPLABX project for [SAMC21N Xplained Pro Evaluation Kit](https://www.microchip.com/developmenttools/ProductDetails/atsamc21n-xpro) |
|||

## Setting up the hardware

The following table shows the target hardware for the application projects.

| Project Name| Board|
|:---------|:---------:|
| sam_c21n_xpro.X | [SAMC21N Xplained Pro Evaluation Kit](https://www.microchip.com/developmenttools/ProductDetails/atsamc21n-xpro) |
|||

### Setting up [SAMC21N Xplained Pro Evaluation Kit](https://www.microchip.com/developmenttools/ProductDetails/atsamc21n-xpro)

- To run the demo, the following additional hardware are required:
  - Two [EEPROM 4 click boards](https://www.mikroe.com/eeprom-4-click)
  - Two [mikroBUS Xplained Pro boards](https://www.microchip.com/developmenttools/ProductDetails/ATMBUSADAPTER-XPRO)

- Install [EEPROM 4 click boards](https://www.mikroe.com/eeprom-4-click) on to the [mikroBUS Xplained Pro boards](https://www.microchip.com/developmenttools/ProductDetails/ATMBUSADAPTER-XPRO)
- Connect the [mikroBUS Xplained Pro boards](https://www.microchip.com/developmenttools/ProductDetails/ATMBUSADAPTER-XPRO) on EXT1 and EXT2 headers
- Connect the Debug USB port on the board to the computer using a micro USB cable

## Running the Application

1. Build and program the application using its IDE
2. The LED indicates success or failure
    - The LED turns ON when the data read from the EEPROMs matches with the data written to the EEPROMs

Refer to the following table for LED name:

| Board | LED Name |
| ----- | -------- |
|  [SAMC21N Xplained Pro Evaluation Kit](https://www.microchip.com/developmenttools/ProductDetails/atsamc21n-xpro) | LED0 |
|||
