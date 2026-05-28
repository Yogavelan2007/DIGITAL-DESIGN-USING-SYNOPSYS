# CMOS EXNOR Gate Design using Synopsys

This project demonstrates the design and simulation of a CMOS EXNOR (XNOR) gate using Synopsys tools.

---

# Tools Used

* Synopsys Custom Compiler
* Synopsys PrimeWave

---

# Project Contents

* CMOS EXNOR gate schematic
* Symbol design
* Simulation waveform
* Testbench configuration

---

# Testbench Configuration

The testbench for the CMOS EXNOR gate design uses VPULSE voltage sources to generate the input signals. These pulse voltages switch between 0 V and 1 V to represent logic LOW and logic HIGH conditions.

## Key Parameters of VPULSE

* V1 (Initial Voltage): 0 V
* V2 (Pulsed Voltage): 1 V
* Period: 20 ns
* Rise Time: 1 ns
* Fall Time: 1 ns
* Pulse Width: 10 ns

A 1 V VDC supply powers the PMOS transistor network, while the NMOS source terminals are connected to ground.

This setup validates the EXNOR gate logic operation for all input combinations.

---

# Output Verification

The simulation waveform confirms correct EXNOR gate behavior:

* Output becomes HIGH when both inputs are the same
* Output becomes LOW when the two inputs are different

Thus, the CMOS EXNOR gate performs proper exclusive-NOR logic operation.

---

# Output Images

## Schematic

![EXNOR Schematic](exnor_schematic.jpeg)

---

## Symbol

![EXNOR Symbol](exnor_symbol.jpeg)

---

## Waveform

![EXNOR Waveform](exnor_waveform.jpeg)

---

