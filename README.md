# LDC Sensor Hub

Demo video: https://www.youtube.com/watch?v=cCiSEzKsWQc

## Repository Description (About)
Hardware-software system for 12 inductive sensors (LDC) with a PC GUI. The system includes a main controller board, up to 12 sensor modules with printed coils, and a cross-platform GUI for configuration, visualization, and real-time data logging. Designed for testing, tuning, and analyzing various inductive coil designs.

## Project Description
This project is a complete hardware-software complex for working with 12 inductive sensors based on LDC chips, intended for measurements, testing, and analysis of inductive coil parameters.

The system consists of a main controller board with a microcontroller and 12 removable sensor boards, each containing a printed coil. The coils are separate PCBs with a connector and a 0603-size pad, allowing easy replacement and experimentation with different coil geometries and PCB parameters without modifying the core electronics.

The microcontroller manages all LDC chips, collects measurements, and sends data to the PC via USB–UART. The firmware supports a LiveStream mode that outputs data from all 12 channels in real time and provides full access to LDC configuration registers.

A cross-platform GUI built with Python (PyQt5 + matplotlib) enables:

- real-time visualization of up to 12 channels;
- toggling individual plots on/off;
- configuring LDC registers directly from the UI;
- saving measurements to CSV for analysis;
- working with live data or saved logs when needed.

The project targets developers and engineers working with sensor systems, inductive measurements, and experimental electronics, and can be used as a platform for research, prototyping, and debugging inductive sensors.

## Contents
- `Programm.exe` — Windows application.

## Quick Start
1. Connect the device via USB–UART.
2. Run `Programm.exe`.

## System Requirements
- Windows 10/11
- USB–UART connection to the controller board

## License
No license file found. All rights reserved unless stated otherwise.

## Hashtags
#LDC #InductiveSensors #Hardware #DAQ #PyQt5 #Matplotlib #Electronics #SensorHub #Embedded #Instrumentation
