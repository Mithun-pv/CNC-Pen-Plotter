# CNC-Pen-Plotter
3-axis CNC pen plotter using Arduino UNO (ATmega328) and GRBL firmware — translating G-code commands into precise XY stepper motor movements and Z-axis pen lift via SG90 servo.

## Overview
A microcontroller-based CNC machine control system developed using Embedded C. The project controls motor movement and machine operations through firmware-driven control logic.

## Features
- Stepper motor control
- Timer-based pulse generation
- GPIO interfacing
- Motion sequencing
- Embedded firmware development
- Hardware-software integration

## Hardware Used

- Stepper motor driver
- Stepper motors
- Power supply
- Jumber pin
- servo motor
- Arduino Uno 

## Software Used
- Embedded C
- 

## Project Structure
```
Source_Code/
├── main.c
├── motor.c
├── motor.h
├── timer.c
└── timer.h
```

## Working
1. Initialize peripherals and timers.
2. Configure motor control pins.
3. Generate step pulses using firmware.
4. Control motor direction and movement.
5. Execute machine operations.

## Skills Demonstrated
- Embedded C
- Firmware Development
- GPIO
- Timers
- Interrupts
- Motor Control
- Hardware Interfacing
- Debugging

## Author
Mithun PV
