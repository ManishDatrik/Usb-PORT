# USB Hub 

## About the Project

This project is a USB Hub PCB designed using EasyEDA. The goal of this project was to understand how a USB hub works and how a complete PCB is designed from a schematic to a manufacturable board.

The PCB allows one USB connection to be shared with multiple USB ports. While designing this board, I learned how to connect USB data lines, provide stable power to every port, and organize components on a compact PCB.

---

## Why I Built This

I wanted to learn the complete PCB design process instead of only reading about it. This project helped me understand how USB communication works and how different electronic components work together on a real circuit board.

---

## Features

- 1 USB Hub Controller IC
- 3 USB Type-C Connectors
- 2 USB-A Output Ports
- USB 2.0 Data Communication
- Stable 5V Power Distribution
- Decoupling Capacitors for Power Filtering
- CC Resistors for USB Type-C
- Compact PCB Layout

---

## Tools Used

- EasyEDA
- EasyEDA Component Library
- PCB Design Editor
- Gerber File Generator

---

## Components Used

- USB Hub Controller IC
- USB Type-C Connectors
- USB-A Connectors
- 56kΩ Resistors
- 100nF Capacitors
- 1µF Capacitors
- Power and Ground Connections

---

## What I Did

### 1. Created the Schematic

Started the project in EasyEDA and created the complete schematic by placing all the required components.

---

### 2. Connected the Circuit

Connected the USB data lines (D+ and D-), power (5V), ground, and USB Type-C CC pins according to the circuit design.

---

### 3. Added Supporting Components

Added resistors and capacitors for proper USB operation and stable power supply.

---

### 4. Assigned Footprints

Assigned suitable footprints to every component before converting the design into PCB.

---

### 5. Converted to PCB

Imported the schematic into the PCB editor and arranged the components in a compact layout.

---

### 6. Routed the PCB

Completed the routing by connecting all the tracks carefully while keeping the layout clean and organized.

---

### 7. Design Check

Verified all connections and ensured the PCB was ready for manufacturing.

---

### 8. Generated Manufacturing Files

Generated the Gerber files and drill files required for PCB fabrication.

---

## What I Learned

Through this project, I learned:

- Creating USB schematics
- Selecting PCB components
- USB Type-C connections
- PCB routing
- Component placement
- Power distribution
- Design Rule Check (DRC)
- Generating Gerber files


---

## Project Files

```text
USB-Hub-PCB
│
├── Schematic
├── PCB Layout
├── Gerber Files
├── Drill Files
├── Manufacturing Files
└── README.md
```

---

## Schematic

The schematic includes:

- USB Hub Controller IC
- Three USB Type-C connectors
- Two USB-A output connectors
- Power filtering capacitors
- USB data line connections
- 5V and Ground distribution
- USB Type-C CC resistors


---


**Manish Vanjari**



GitHub: https://github.com/ManishDatrik/Usb-PORT.git
