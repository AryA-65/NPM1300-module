# NPM1300-module (General Doc)
The nPM1300 is a power management IC created and sold by Nordic Semi, intended to be paired with their nRF lineup but can be used by any microcontroller. The nPM1300-module, based on the provided pcb reference layout by Nordic, allows the implementation of a power management whilst being cost effective.

## Board Info
<table>
  <tr>
    <td>

Current specifications:

- 25.8mm x 25.8mm footprint  
- 7 breakout pins per side  
- Buck converters and LDOs enabled (buck converter voltage is set by placing a resistor on the appropriate Vset pin, check page 47 in the nPM1300 datasheet provided below)  
- Onboard programmable LED

    </td>
    <td>

<img src="https://github.com/user-attachments/assets/556ab214-c438-42d7-bac3-bc9d08069bf9" width="300"><br>
<img src="https://github.com/user-attachments/assets/7cc15b91-ac2f-4b15-a4f8-3c513186fc7b" width="300">

    
  </tr>
</table>

## Updates
Older revisions can be found in "archive" branch:
- Reduced footprint from 26.5mm x 29.5mm to 25.8mm x 25.8mm
- Added onboard led
- Simplified layout, reducing number of total pins
- Added footprints for I2C pullup resistors
- Flipped board layout

## Schematic
Based off of Nordic's own reference schematic
<img src="https://github.com/user-attachments/assets/5c73cb99-c88d-4623-a224-951afa9a0610" height=720px>

## Symbol and Footprint
*In progress*

## Software
*Software example code in progress*

## Disclaimer
I OWN NONE OF THE RIGHTS TO THE NPM1300, IT IS A PRODUCT MADE AND SOLD BY NORDIC SEMI. THIS BOARD IS INTENDED TO MAKE INTEGRATION OF THE IC SIMPLER AND HASTLE FREE.

## Documents and Links
List of all documents used to make the board:
- [Nordic Semi nPM1300](https://www.nordicsemi.com/Products/nPM1300)
- [nPM1300 reference layouts, production files and BOM](https://www.nordicsemi.com/Products/nPM1300/Downloads#infotabs)
- [Other documentation related to the nPM1300](https://docs.nordicsemi.com/category/npm1300-category)

## License
[MIT License](https://github.com/AryA-65/NPM1300-module/blob/main/LICENSE)
