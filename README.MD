# Project Title

RL78/I1C PMOD Programming Adaptor - Isolated

## Description

This piece of hardware alows connection between an E2-Lite and any of the RL78/I1C Metering PMOD's.
Providing 5kv isolation.

Gerbers, Schematics and BoM for the latest revision are included in the repository under the build directory.

## Getting Started

### Modifications
When using the RL78/I1C PMOD's their isolation transformer drive resistors must be updated to 1k8, this is R18 and R19.
This is necessary because this dongle pulls extra current from the PMOD power supply which, with the default resistors, the circuit cannot supply and it causes a VDD dip.

### Dependencies

* KiCad 7.0
* [Component Libraries](https://github.com/lwray-renesas/RL78-I1C-PMOD-Programming-Adaptor-KiCad-Libraries.)

## License

This project is licensed under the MIT License - see the LICENSE.md file for details

