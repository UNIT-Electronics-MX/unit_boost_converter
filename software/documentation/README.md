---
title: "Boost Converter Module module"
version: "1.0"
modified: "2025-05-27"
output: "Boost_Converter_Module_module"
subtitle: "Boost Converter Module: a compact, efficient DC–DC boost regulator that increases low input voltages for reliable operation using the high-efficiency TPS61023 from Texas Instruments."
---

<!--
# README_TEMPLATE.md
Este archivo sirve como entrada para generar un PDF técnico estilo datasheet.
Edita las secciones respetando el orden, sin eliminar los encabezados.
-->
<!-- logo -->

# Boost Converter Module

![product](images/top.png)

## Introduction

The Boost Converter Module is a compact, adjustable DC–DC step-up (boost) regulator designed to increase a lower input voltage to a higher output voltage. It is powered by the TPS61023 high-efficiency switching regulator from Texas Instruments, enabling reliable operation even from low-voltage sources such as LiPo batteries or solar panels.  
A multi-turn potentiometer is included for precise output voltage adjustment, making the module ideal for battery-powered applications and compact embedded systems.

This makes it ideal for powering circuits from LiPo cells, USB power banks, solar panels, and other low-voltage sources in embedded projects and prototyping.

## Functional Description

- The module uses the TPS61023 to boost input voltages from as low as 0.5 V to a stable output voltage up to 5.5 V.
- It features a multi-turn potentiometer for fine-tuning the output voltage, allowing for precise control. 

## Electrical Characteristics & Signal Overview

- Regulator IC: Texas Instruments TPS61023 – high-efficiency boost converter
- Input Voltage Range: 0.5 V to 5.5 V
- Start-up Voltage: Operates from input as low as 0.7 V
- Adjustable Output: Up to 5.5 V (via onboard multi-turn potentiometer)
- Output Current: Up to 1 A (depending on input/output conditions)
- Efficiency: Up to 96 % under optimal conditions
- Switching Frequency: ~2 MHz for reduced external component size
- Protections: Overcurrent (OCP), thermal shutdown, undervoltage lockout (UVLO)
- Form Factor: Breadboard-friendly 20.3 mm × 17.78 mm PCB
- Applications: Ideal for LiPo boosts, USB power banks, solar panels, sensors, LEDs, prototyping
- Datasheet: [TPS61023 – Texas Instruments](https://www.ti.com/product/TPS61023)

## Applications

- Battery-powered systems: Boost 3.7 V LiPo to 5 V for microcontrollers or sensors.
- LED drivers: Drive high-voltage LED strings from 3 V or 3.7 V input.
- Portable electronics: Step-up for small regulated power in mobile designs.
- Sensor modules: Power 5 V+ sensors from 3.3 V systems.
- DIY projects & prototyping: Simple integration in breadboard or PCB-based designs.

## Features

- Ultra-compact module using high-efficiency TPS61023.
- Input as low as 0.5 V; startup from 0.7 V.
- Adjustable output via multi-turn potentiometer.
- Output up to 5.5 V and 1 A.
- Built-in protections: OCP, thermal shutdown, UVLO.
- 2 MHz switching for small component footprint.
- Breadboard-friendly layout.
- Ready-to-use for embedded development.

## Pin & Connector Layout

| Pin Group  | Label     | Function                                                              |
|------------|-----------|-----------------------------------------------------------------------|
| Input      | VIN       | Positive input voltage. Connect your supply’s positive terminal here. |
| Input      | GND Input | Ground reference for input. Connect the supply’s negative terminal here. |
| Output     | VOUT      | Boosted positive output. Provides regulated higher voltage.         |
| Output     | GND Output| Output ground. Connect to your load's ground or system ground.        |
| Adjustment | POT       | Multi-turn potentiometer to set the output voltage precisely.         |

## Settings

### Interface Overview

| Interface     | Signals / Pins      | Typical Use                                   |
|---------------|---------------------|-----------------------------------------------|
| Power Input   | VIN, GND Input       | Connect low-voltage power source              |
| Power Output  | VOUT, GND Output     | Connect regulated output to load              |
| Adjustment    | POT                  | Set desired output voltage                    |

### Supports

| Feature             | Description                                          |
|---------------------|------------------------------------------------------|
| Adjustable Output   | Set via onboard potentiometer                        |
| Low-Voltage Start    | Operates from <1 V input for energy harvesting       |
| Compact Footprint   | Fits in small enclosures and breadboards             |
| Plug-and-Play       | No configuration or firmware required                |

## Block Diagram

![Function Diagram](images/pinout.png)

## Dimensions

![Dimensions](images/dimension.png)

## Usage

Works with:

- Arduino interfaces (Uno, Mega, Nano)

## Downloads

- [Schematic PDF](docs/schematic.pdf)

## Purchase

- [Buy from UNIT Electronics](https://www.uelectronics.com)
