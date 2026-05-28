# CMOS NAND Gate Design using Synopsys

This project demonstrates the design and simulation of a CMOS NAND gate using Synopsys tools.

---

# Tools Used

* Synopsys Custom Compiler
* Synopsys PrimeWave

---

# Project Contents

* CMOS NAND gate schematic
* Symbol design
* Simulation waveform
* Testbench configuration

---

# Testbench Configuration

The testbench for the CMOS NAND gate design uses VPULSE voltage sources to generate the input signals. These pulse voltages switch between 0 V and 1 V to represent logic LOW and logic HIGH conditions.

## Key Parameters of VPULSE

* V1 (Initial Voltage): 0 V
* V2 (Pulsed Voltage): 1 V
* Period: 20 ns
* Rise Time: 1 ns
* Fall Time: 1 ns
* Pulse Width: 10 ns

A 1 V VDC supply powers the PMOS transistor network, while the NMOS source terminals are connected to ground.

This setup validates the NAND gate logic operation for all input combinations.

---

# Output Verification

The simulation waveform confirms correct NAND gate behavior:

* Output becomes LOW only when both inputs are HIGH
* Output remains HIGH for all other input combinations

Thus, the CMOS NAND gate performs proper logical NAND operation.

---

# Output Images

## Schematic

![NAND Schematic](nand_schematic.jpeg)

---

## Symbol

![NAND Symbol](nand_symbol.jpeg)

---

## Waveform

![NAND Waveform](nand_waveform.jpeg)

---


