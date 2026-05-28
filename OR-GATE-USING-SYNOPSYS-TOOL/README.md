# CMOS OR Gate Design using Synopsys

This project demonstrates the design and simulation of a CMOS OR gate using Synopsys tools.

---

# Tools Used

* Synopsys Custom Compiler
* Synopsys PrimeWave

---

# Project Contents

* CMOS OR gate schematic
* Symbol design
* Simulation waveform
* Testbench configuration

---

# Testbench Configuration

The testbench for the CMOS OR gate design uses VPULSE voltage sources to generate the input signals. These pulse voltages switch between 0 V and 1 V to represent logic LOW and logic HIGH conditions.

## Key Parameters of VPULSE

* V1 (Initial Voltage): 0 V
* V2 (Pulsed Voltage): 1 V
* Period: 20 ns
* Rise Time: 1 ns
* Fall Time: 1 ns
* Pulse Width: 10 ns

A 1 V VDC supply powers the PMOS network, while the NMOS source terminals are connected to ground.

This setup validates the OR gate logic operation.

---

# Output Verification

The simulation waveform confirms correct OR gate behavior:

* Output becomes HIGH when any one of the inputs is HIGH
* Output becomes LOW only when both inputs are LOW

---

# Output Images

## Schematic

![OR Schematic](or_schematic.jpeg)

---

## Symbol

![OR Symbol](or_symbol.jpeg)

---

## Waveform

![OR Waveform](or_waveform.jpeg)

---


