# NPM1300-module
The nPM1300 is a power management ic created and sold by Nordic Semi, intended to be paired with their nRF lineup but can be used by any microcontroller. The nPM1300-module, based on the provided pcb reference layout by Nordic, allows the implementation of a power management whilst being cost effective.

![image](https://github.com/user-attachments/assets/508cc0fe-5f17-4452-b109-873b0bea11c9)

## Disclaimer
I OWN NONE OF THE RIGHTS TO THE NPM1300, IT IS A PRODUCT MADE AND SOLD BY NORDIC SEMI. THIS BOARD IS INTENDED TO MAKE INTEGRATION OF THE IC EASIER INTO PROJECTS.

## Board Info
Current specs of the board:
- 26.5x29.5mm footprint
- 8 breakout pins per side
- Buck converters and LDOs enabled (buck converter voltage is set by placing a resistor on the appropriate Vset pin, check page 47 in the nPM1300 datasheet provided below)
- 3 led pins (programmable via host device)
- 5 GPIO pins (GPIO0 & GPIO1 are in use, set respectively as reset and interrup)
- charging speed of 32-800mA (provided from the nPM1300 datasheet)

## Documents
List of all documents used to make the board:
- doc1
- doc2
- doc3

## License
MIT License
