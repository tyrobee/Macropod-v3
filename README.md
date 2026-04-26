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
| Rotary Encoder | Dial input | 1 | 1.03 | [Buy](https://robu.in/product/rotary-encoder-module/) | Robocraze |
| RP2040 | Microcontroller | 1 | 1.39 | [Buy](https://robu.in/product/raspberry-pi-rp2040-microcontroller/) | Robocraze |
| Hot-Swappable Mechanical Keyboard Switches | Keys | 1 | — | [Buy](https://www.amazon.in/dp/B0CKH9WJ9Q) | Amazon |
| Keycaps (Round Domes) | Keys | 1 | — | [Buy](https://www.amazon.in/dp/B0CJG7PZ79) | Amazon |
| PCB | Circuit board | 1 | 3.94 | [Order](https://jlcpcb.com/) | JLCPCB |
| USB Type-C to Type-C Cable (Zebronics) | Power & Data | 1 | 2.11 | [Buy](https://www.amazon.in/dp/B0FJ2LY2JN) | Amazon |
