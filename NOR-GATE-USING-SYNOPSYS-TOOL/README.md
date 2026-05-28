# CMOS NOR Gate Design using Synopsys

This project demonstrates the design and simulation of a CMOS NOR gate using Synopsys tools.

---

# Tools Used

* Synopsys Custom Compiler
* Synopsys PrimeWave

---

# Project Contents

* CMOS NOR gate schematic
* Symbol design
* Simulation waveform
* Testbench configuration

---

# Testbench Configuration

The testbench for the CMOS NOR gate design uses VPULSE voltage sources to generate the input signals. These pulse voltages switch between 0 V and 1 V to represent logic LOW and logic HIGH conditions.

## Key Parameters of VPULSE

* V1 (Initial Voltage): 0 V
* V2 (Pulsed Voltage): 1 V
* Period: 20 ns
* Rise Time: 1 ns
* Fall Time: 1 ns
* Pulse Width: 10 ns

A 1 V VDC supply powers the PMOS transistor network, while the NMOS source terminals are connected to ground.

This setup validates the NOR gate logic operation for all input combinations.

---

# Output Verification

The simulation waveform confirms correct NOR gate behavior:

* Output becomes HIGH only when both inputs are LOW
* Output remains LOW for all other input combinations

Thus, the CMOS NOR gate performs proper logical NOR operation.

---

# Output Images

## Schematic

![NOR Schematic](nor_schematic.jpeg)

---

## Symbol

![NOR Symbol](nor_symbol.jpeg)

---

## Waveform

![NOR Waveform](nor_waveform.jpeg)

---


