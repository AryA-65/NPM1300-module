# NPM1300-module
The nPM1300 is a power management ic created and sold by Nordic Semi, intended to be paired with their nRF lineup but can be used by any microcontroller. The nPM1300-module, based on the provided pcb reference layout by Nordic, allows the implementation of a power management whilst being cost effective.

<img src="https://github.com/user-attachments/assets/f5d8a17e-70c5-4a86-808a-44ebfa528137" width="300"/>
<img src="https://github.com/user-attachments/assets/bd7bcb2e-3bf9-4db7-8470-77d1425b2a1c" width="300"/>

## Disclaimer
I OWN NONE OF THE RIGHTS TO THE NPM1300, IT IS A PRODUCT MADE AND SOLD BY NORDIC SEMI. THIS BOARD IS INTENDED TO MAKE INTEGRATION OF THE IC SIMPLER AND HASTLE FREE.

## Board Info
Current specs of the board:
- 26.5mm*29.5mm footprint
- 8 breakout pins per side
- 9 ground pins and 3 Vout2 pins (for orientation independent wiring)
- Buck converters and LDOs enabled (buck converter voltage is set by placing a resistor on the appropriate Vset pin, check page 47 in the nPM1300 datasheet provided below)
- 3 led pins (programmable via host device)
- 5 GPIO pins (GPIO0 & GPIO1 are in use, set respectively as reset and interrup)
- charging speed of 32-800mA (provided from the nPM1300 datasheet)

## Documents and Links
List of all documents used to make the board:
- [Reference layout used for the board - property of Nordic Semi](https://github.com/AryA-65/NPM1300-module/blob/main/Docs/npm1300_qeaa_config1_pcb.pdf)
- [Schematic used for the board - property of Nordic Semi](https://github.com/AryA-65/NPM1300-module/blob/main/Docs/npm1300_qeaa_config1_schematic.pdf)
- [BOM used for the board - property of Nordic Semi](https://github.com/AryA-65/NPM1300-module/blob/main/Docs/npm1300_qeaa_config1_bom.xls)
- [nPM1300](https://www.nordicsemi.com/Products/nPM1300)
- [nPM1300 reference layouts, production files and BOM](https://www.nordicsemi.com/Products/nPM1300/Downloads#infotabs)
- [Other documentation related to the nPM1300](https://docs.nordicsemi.com/category/npm1300-category)

## 3rd Party Parts
All third party parts are accessible in the [3rd Party Components folder](https://github.com/AryA-65/NPM1300-module/tree/main/3rd%20Party%20Components). This folder also includes the symbol and footprint of the module itself.

## License
[MIT License](https://github.com/AryA-65/NPM1300-module/blob/main/LICENSE)
