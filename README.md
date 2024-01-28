# Single-Cell 1S Charger Project

## Overview
This repository contains the design files for a simple and versatile single-cell 1S charger module. This charger is designed as an independent module with a battery holder, making it a plug-and-play solution for charging applications. It features a USB socket for power input and additional footprints for alternative connectors like JST, offering flexibility in power connection options.

The charger is based on the MCP73832, a highly integrated linear charge management controller suitable for use within a wide range of battery sizes and chemistries. Its compact form factor and simple functionality make it an ideal choice for portable applications.

## Features of MCP73832
- Linear charge management controller optimized for single-cell lithium-ion and lithium-polymer batteries.
- Programmable charge current from 15 mA to 500 mA.
- Preconditioning of deeply discharged batteries.
- Automatic end-of-charge control via charge termination and auto-recharge.
- Charge status output pin that can drive an LED.
- Thermal regulation to maximize charge rate without risk of overheating.

## Schematic
The schematic details the electrical design, showing how the MCP73832 is integrated to provide safe and efficient charging.

![Schematic](media/sch.png)

## PCB Layout
The PCB layout illustrates the component placement and routing, designed to be compact and efficient.

![PCB Layout](media/brd.png)

## Usage
To use the charger, connect a single-cell 1S battery to the battery holder, and power the charger via the USB socket or alternative power connector. An LED indicator provides real-time charging status based on the output from the MCP73832.
