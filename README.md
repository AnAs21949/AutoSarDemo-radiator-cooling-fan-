# Radiator Cooling Fan AUTOSAR Demo

This repository illustrates a simplified AUTOSAR configuration for controlling a radiator cooling fan. It contains example software components, interface descriptions, and low level driver stubs to demonstrate how different layers of an AUTOSAR architecture interact.

## Repository Structure
- **ASW/**: Application software component source and ARXML.
- **ECUAbstraction/**: ECU abstraction layer sample implementation.
- **Interfaces/**: Shared interface and platform type definitions.
- **MCAL/**: Microcontroller abstraction layer stubs for ADC and DIO.
- **Composition.arxml**: Composition of the application and ECU abstraction components.

## Getting Started
This project is intended for educational purposes and does not include a full build system. The C sources illustrate how application code could interact through the AUTOSAR Runtime Environment (RTE). Integrate the sources into an AUTOSAR-compliant toolchain to compile and run the demonstration.

