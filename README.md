# H22R2x-Hardware

Hexabitz LTE/GNSS Module Hardware Design.



Design this module using the STM32G0B1CEU6 MCU and NRF9160-SICA-R7. Include connectors 734120110 and SIM8050-6-0-14-01-A.



This design must use two hexagons with a 4-layer PCB stack-up.

## Design Notes

1. Could not find the correct part with the schematic file and pcb footprint inside of Altium Designer, so I referenced imported this one: https://www.digikey.com/en/models/10242085?tab=ultralibrarian
2. Referenced page 395 of the [nRF9160 datasheet](https://octopart.com/datasheet/nrf9160-sica-r7-nordic+semiconductor-102775108) for the schematic layout.
3. I could not find a X5R capacitor in Altium Designer, so I used a X6S. The package type, tolerance, and voltage remained the same.

