# Oscillar

Oscillar is an open-source, cheap, two output, RF signal generator covering from 12MHz to 6GHz, with an output 
power range of −60dBm to +15dBm on the main output.

This repository contains the complete system design, including block diagrams, schematics, 
PCB design files, firmware source code, documentation, and measurement results.

## Features

- Main output: 12MHz to 6GHz with IQ modulation and 12MHz to 8GHz CW operation
- Secondary output: 12M to 2GHz only in CW
- Main output power: −60 dBm to +15 dBm
- Secondary output power: -10 dBm to 10 dBm
- IQ bandwidth: 20MHz
- Two stackable PCBs in a machined aluminium enclosure
- Open-source hardware and firmware (GPLv3)

## Hardware overview

The system is built around two stackable PCBs housed in a machined aluminium enclosure:

- **Digital board** — hosts the main microcontrollers and handles central clock generation 
and distribution.
- **RF board** — contains all RF stages required for signal generation and output 
conditioning.

## Block diagram

![Block diagram](./SYS/BlockDiagram.png)

## License

This project is licensed under the GNU General Public License v3.0 — see the 
[LICENSE](./LICENSE) file for details.
