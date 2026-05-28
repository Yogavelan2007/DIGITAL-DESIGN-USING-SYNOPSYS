# CMOS AND Gate Design using Synopsys

This project demonstrates the design and simulation of a CMOS AND gate using Synopsys tools.

---

# Tools Used

* Synopsys Custom Compiler
* Synopsys PrimeWave

---

# Project Contents

* CMOS AND gate schematic
* Symbol design
* Simulation waveform
* Testbench configuration

---

# Testbench Configuration

The testbench for the CMOS AND gate design uses VPULSE voltage sources to provide the input signals. These pulse voltages toggle between 0 V (logic LOW) and 1 V (logic HIGH) to simulate digital logic conditions.

## Key Parameters of VPULSE

* V1 (Initial Voltage): 0 V
* V2 (Pulsed Voltage): 1 V
* Period: 20 ns
* Rise Time: 1 ns
* Fall Time: 1 ns
* Pulse Width: 10 ns

A VDC supply of 1 V powers the CMOS circuit while the ground terminal acts as the common reference for NMOS transistors.

This setup verifies the logical AND operation for all input combinations.

---

# Output Verification

The simulation waveform confirms correct AND gate operation:

* Output becomes HIGH only when both inputs are HIGH
* Output remains LOW for all other input combinations

---

# Output Images

## Schematic

![AND Schematic](and_schematic.jpeg)

---

## Symbol

![AND Symbol](and_symbol.jpeg)

---

## Waveform

![AND Waveform](and_waveform.jpeg)

---


