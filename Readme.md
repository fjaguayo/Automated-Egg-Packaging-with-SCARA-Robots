# Automated Egg Packaging with SCARA Robots

A theoretical engineering project exploring the full automation of an egg classification and packaging line using SCARA robotic arms, conveyor systems, vision sensors, and PLC control.

Developed as an integrated project for the Robotics department at Colegio San José (Málaga), together with Guillermo Carrión Caballero, under the supervision of Rubén Martín Antolín.

## What the project covers

The core idea is replacing manual egg sorting with a system built around two SCARA robots, a circular conveyor belt, and a vision scanner. Eggs come in through a hopper, travel along the belt, get scanned and picked up by the robot arm, and are dropped into one of two egg trays depending on their classification. Once a tray is full, it moves onto a palletizing line.

The full document covers the theoretical design from end to end: system architecture, component selection, sensor types, PLC programming logic, Modbus communication between devices, safety considerations, cost estimates, and a GRAFCET control sequence diagram. It also includes the Omron ACE 4.4 robot programming used for the SCARA arm movements.

## Key specs

The conveyor belt runs at roughly 0.1 m/s so eggs complete one full loop per minute. The system is designed to handle around 1,200 eggs per hour, with a target classification efficiency above 90%. Cycle time per egg sits at approximately 2.2 seconds.

Estimated total implementation cost: €71,000 – €149,000 depending on component choices and installation complexity.

## Project document

The full technical report (in Spanish) is available in this repository as a PDF. It includes system diagrams, wiring schematics, the GRAFCET sequence, PLC input/output tables, robot simulation screenshots, and the complete cost breakdown.

## Tools used

Robot programming was done in Omron ACE 4.4. Electrical schematics were drawn in a PLC wiring tool with a Siemens S7-1200 as the control unit. Communication between components runs over Modbus RTU/TCP.

## Authors

Francisco Javier Aguayo Hernández and Guillermo Carrión Caballero
Colegio San José, Málaga — Robotics Department, 2023
