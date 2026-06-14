# Oscillar

Oscillar is an open-source IQ-modulated RF signal generator covering 1 MHz to 8 GHz, with an output power range of −80 dBm to +22 dBm.
This repository contains the complete system design, including block diagrams, schematics, PCB design files, firmware source code, documentation, and measurement results.
Hardware overview
The system is built around two stackable PCBs housed in a machined aluminium enclosure:

Digital board — hosts the main microcontrollers and handles central clock generation and distribution.
RF board — contains all RF stages required for signal generation and output conditioning.

## Block diagram

![Block diagram](./SYS/BlockDiagram.png)