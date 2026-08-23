# STM32 Biomedical Triage Interface - KiCad

KiCad schematic concept for an STM32-based biomedical monitoring and triage interface integrating sensor acquisition, communication and alert functions.

## Design Overview

The schematic includes:

- Temperature, pulse and respiration sensor interfaces
- Analog RC filtering for sensor signals
- STM32 interface headers
- I2C sensor/display interface with pull-up resistors
- UART interface for ESP8266 communication
- Green, orange and red status LEDs
- Buzzer alert output
- User push button
- Test points for power, sensor and communication signals

## Interfaces

- **Analog inputs:** temperature, pulse and respiration signals
- **I2C:** sensor/display communication
- **UART:** ESP8266 communication
- **GPIO:** status LEDs, buzzer and user button

## Validation

KiCad Electrical Rules Checker was run on the schematic.

- **ERC errors: 0**
- Warnings remain for review

## Tools

**KiCad | STM32 | Analog/Digital Interfaces | I2C | UART**

## Files

- `STM32_Biomedical_Triage_Interface.kicad_sch` - editable KiCad schematic
- `STM32_Biomedical_Triage_Interface_Schematic.pdf` - schematic export
- `KiCad-ERC-Check.png` - ERC result

## Scope

This repository documents the **schematic and interface-design stage** of the project. It does not represent a completed PCB layout or fabricated board.
