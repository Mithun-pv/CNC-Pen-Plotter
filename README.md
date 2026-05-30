# CNC Drawing Robot (DrawBot)

## Overview

Designed and assembled a CNC-based Drawing Robot capable of converting vector graphics into G-Code and automatically drawing images on paper. The system uses Arduino Uno, CNC Shield, A4988 stepper drivers, NEMA 17 motors, and GRBL firmware for motion control.

## Features

* X-Y axis motion control using stepper motors
* Servo-based pen lift mechanism (Z-axis)
* G-Code interpretation using GRBL firmware
* Vector image to G-Code conversion using Inkscape
* Automated drawing and plotting functionality
* Adjustable speed and motion parameters

## Hardware Used

* Arduino Uno
* CNC Shield
* A4988 Stepper Drivers
* NEMA 17 Stepper Motors
* SG90 Servo Motor
* GT2 Belt Drive System
* Linear Rods and LM8UU Bearings
* 12V Power Supply

## Software Used

* Embedded C / Arduino IDE
* GRBL Firmware
* Inkscape
* MI GRBL Extension
* Universal G-Code Sender (UGS)

## Working Principle

1. Create or import a drawing in Inkscape.
2. Convert the drawing into G-Code using the MI GRBL extension.
3. Upload GRBL firmware to Arduino Uno.
4. Send G-Code to the robot through Universal G-Code Sender.
5. The robot moves along X and Y axes while controlling pen up/down movement using a servo motor.

## My Contributions

* Mechanical assembly of the DrawBot frame.
* Integration of Arduino Uno, CNC Shield, and A4988 drivers.
* Stepper motor wiring and calibration.
* GRBL firmware configuration and parameter tuning.
* Testing and debugging of motion control and drawing accuracy.

## Results

Successfully built and tested a CNC Drawing Robot capable of reproducing vector graphics and text with repeatable positioning accuracy.

## Skills Demonstrated

Embedded Systems, Arduino, GRBL, CNC Systems, Stepper Motor Control, Motion Control, Hardware Integration, Firmware Configuration, G-Code, Debugging.
