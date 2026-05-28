# CMOS Half Adder Design using Synopsys

This project demonstrates the design and simulation of a CMOS Half Adder using Synopsys tools.

A Half Adder performs binary addition of two single-bit inputs and produces SUM and CARRY outputs.

---

# Tools Used

* Synopsys Custom Compiler
* Synopsys PrimeWave

---

# Project Contents

* CMOS Half Adder schematic
* Symbol design
* Simulation waveform
* Testbench configuration

---

# Testbench Configuration

The testbench for the CMOS Half Adder design uses VPULSE voltage sources to generate the input signals. These pulse voltages alternate between 0 V and 1 V to represent logic LOW and logic HIGH conditions.

## Key Parameters of VPULSE

* V1 (Initial Voltage): 0 V
* V2 (Pulsed Voltage): 1 V
* Period: 20 ns
* Rise Time: 1 ns
* Fall Time: 1 ns
* Pulse Width: 10 ns

A VDC supply of 1 V powers the CMOS circuit, while the NMOS transistor network is connected to ground.

This setup verifies the SUM and CARRY outputs for all possible binary input combinations.

---

# Output Verification

The simulation waveform confirms correct Half Adder operation:

## SUM Output

* SUM becomes HIGH when the two inputs are different
* SUM becomes LOW when both inputs are the same

This behavior follows the EXOR logic operation.

## CARRY Output

* CARRY becomes HIGH only when both inputs are HIGH
* CARRY remains LOW for all other input combinations

This behavior follows the AND logic operation.

Thus, the CMOS Half Adder correctly performs single-bit binary addition.

---

# Output Images

## Schematic

![Half Adder Schematic](halfadder_schematic.jpeg)

---

## Symbol

![Half Adder Symbol](halfadder_symbol.jpeg)

---

## Waveform

![Half Adder Waveform](halfadder_waveform.jpeg)

---

