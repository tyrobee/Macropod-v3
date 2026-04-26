# Macropod-v3

I made a hackboard based on the pretty well known Sayo Device.

My Hackboard has a rotary encoder for volume control, 3 keys for macros/inputs. Currently in the QMK firmware it's been coded so the left key will press W on the keyboard, the middle key will do copy, and the right key will do paste. To make this Hackboard yourself you will need all the electronics in BOM plus get the custom PCB board made, the files for that are in gerbers in the production folder. After that you will need to 3d print all 3 of the parts for the case. Next you assemble the PCB board by sautering all of the pieces together. Finally you flash the Firmware into the RP2040 micro-controller and assemble the case for the sayo device.

## Schematics
![S1](./PCB/PHOTOS/s1.png)

## PCB
![P1](./PCB/PHOTOS/p1.png)

## CAD
![C1](./PCB/PHOTOS/c1.png)

## BOM
| Name | Purpose | Quantity | Total Cost (USD) | Link | Distributor |
|------|--------|----------|------------------|------|------------|
| Rotary Encoder | Dial input | 1 | 1.03 | [Link] | Robocraze |
| RP2040 | Microcontroller | 1 | 1.39 | [Link] | — |
| Hot-Swappable Mechanical Keyboard Switches | Keys | 1 | — | [Link] | — |
| Keycaps (Round Domes) | Keys | 1 | — | [Link] | — |
| PCB | Circuit board | 1 | 3.94 | — | JLCPCB |
