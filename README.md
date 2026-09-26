# Light-Sensor

## Overview

This project is a Light Sensor circuit based on an LDR (Light Dependent
Resistor) and an operational amplifier.

The circuit detects changes in the surrounding light intensity using an LDR.
The changing resistance of the LDR is converted into a voltage variation,
which is then processed by the op-amp circuit.

The schematic and PCB were designed using KiCad.

## Reference

This project was developed with reference to the following video:

**Light Sensor Circuit Using LDR & Op-Amp | PCB Design in KiCad**

YouTube:
https://youtu.be/qa-KR_7WG2g

The video was used as a reference for understanding the circuit concept,
schematic design, and PCB layout.

## Features

- LDR-based light sensing
- Op-amp based signal processing
- Adjustable light detection
- Custom PCB design
- KiCad schematic
- KiCad PCB layout
- Gerber files for PCB manufacturing
- 3D PCB visualization

## How It Works

An LDR (Light Dependent Resistor) changes its resistance depending on the
amount of light falling on it.

- In bright light, the resistance of the LDR decreases.
- In darkness, the resistance of the LDR increases.

The LDR is combined with a resistor to form a voltage divider. The voltage
produced by this divider changes according to the surrounding light level.

This changing voltage is supplied to the op-amp circuit, which processes the
signal and provides the required output.

## Main Components

| Component | Purpose |
|-----------|---------|
| LDR | Detects surrounding light intensity |
| Op-Amp | Processes and compares the sensor voltage |
| Resistors | Voltage division and biasing |
| Capacitors | Filtering and signal stability |
| Potentiometer | Adjusts the detection threshold |
| Connectors | Power and output connections |

## Circuit

The main parts of the circuit are:

1. LDR light sensing section
2. Voltage divider
3. Op-amp section
4. Threshold adjustment
5. Power supply section
6. Output section

## PCB Design

The PCB was designed using **KiCad**.

The design process includes:

1. Creating the schematic
2. Selecting the required components
3. Assigning footprints
4. Creating the PCB layout
5. Placing components
6. Routing PCB tracks
7. Checking the PCB design
8. Running Design Rules Check (DRC)
9. Generating Gerber files
10. Viewing the PCB in 3D

## Software Used

- KiCad
- KiCad Schematic Editor
- KiCad PCB Editor
- KiCad 3D Viewer

## Project Structure

```text
LDR-Light-Sensor/
│
├── doc/
│   ├── Schematic.png
│   ├── Layout.png
│   └── 3D_View.png
│
├── gerber/
│   ├── *.gbr
│   └── *.drl
│
├── LDR Light Sensor.kicad_pro
├── LDR Light Sensor.kicad_sch
├── LDR Light Sensor.kicad_pcb
│
└── README.md
