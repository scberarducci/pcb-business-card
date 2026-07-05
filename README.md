# PCB Business Card
Design for Altium Academy's PCB Business Card Design Challenge (2026). Original design by Sara Berarducci. 
Open Hardware for educational use.

## License
*The hardware design files in this repository are licensed under the CERN Open Hardware Licence Version 2 - Weakly Reciprocal (CERN-OHL-W-2.0).*
*See LICENSE.txt for the full license text.*
*Educational use is encouraged, including use in classrooms and workshops.*
*Name, logo, and personal branding are **not** licensed for reuse except for attribution/reference purposes.*

## Description

This PCB business card is a functional 7-stage transistor loop oscillator visualized with LEDs. The loop oscillator is powered while a pushbutton is held and otherwise remains off.

The design includes startup asymmetry at the first stage using a capacitor and diode, which helps ensure consistent startup and quick reset when power is removed.

The included BOM contains all parts used in the original fabricated card, rev 1.0, except the coin cell holder, which is a Keystone 3000 CR1220 clip.

## Build Notes

The card was designed with JLCPCB's manufacturing capabilities in mind. It is powered by a CR1220 coin cell battery.

Voltage sag during extended use is expected. If the circuit is powered for long stretches of time, oscillation may slow and the LEDs may dim.

Rev 2.0 is currently in progress and will be added to this repository once completed. See the demos folder for images and videos of the fabricated card.

If you use this design to create a PCB of your own, I would love to see it! Feel free to email me at scberarducci@gmail.com or contact me on LinkedIn with your design.

## Repository Contents
* hardware/ — KiCad hardware design files and BOM
* demos/ — images and videos of the fabricated card
* logo/ — logo/reference assets used in the design - *not licensed for use other than for attribution purposes*
 

## Attribution
When using or sharing this design, attribution is requested.
**Sara Berarducci**
https://www.saraberarducci.com/hardware/altium-business-card-challenge

## Copyright
**Copyright (c) 2026 Sara Berarducci**

