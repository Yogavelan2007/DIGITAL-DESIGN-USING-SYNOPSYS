# CMOS Full Adder Design using Synopsys

This project demonstrates the design and simulation of a CMOS Full Adder using Synopsys tools.

A Full Adder performs binary addition of three single-bit inputs: A, B, and Carry-in (Cin). It produces two outputs: SUM and Carry-out (Cout).

---

# Tools Used

* Synopsys Custom Compiler
* Synopsys PrimeWave

---

# Project Contents

* CMOS Full Adder schematic
* Symbol design
* Simulation waveform
* Testbench configuration

---

# Testbench Configuration

The testbench for the CMOS Full Adder design uses VPULSE voltage sources to generate the input signals. These pulse voltages alternate between 0 V and 1 V to represent logic LOW and logic HIGH conditions.

## Key Parameters of VPULSE

* V1 (Initial Voltage): 0 V
* V2 (Pulsed Voltage): 1 V
* Period: 20 ns
* Rise Time: 1 ns
* Fall Time: 1 ns
* Pulse Width: 10 ns

A VDC supply of 1 V powers the CMOS circuit, while the NMOS transistor network is connected to ground.

This setup verifies the SUM and Carry-out outputs for all possible binary input combinations.

---

# Output Verification

The simulation waveform confirms correct Full Adder operation.

## SUM Output

* SUM becomes HIGH when an odd number of inputs are HIGH
* SUM becomes LOW when an even number of inputs are HIGH

This behavior follows the EXOR logic operation among the three inputs.

## Carry Output (Cout)

* Carry-out becomes HIGH when two or more inputs are HIGH
* Carry-out remains LOW when fewer than two inputs are HIGH

This verifies proper carry generation and propagation in binary addition.

Thus, the CMOS Full Adder correctly performs single-bit binary addition with carry input support.

---

# Output Images

## Schematic

![Full Adder Schematic](fulladder_schematic.jpeg)

---

## Symbol

![Full Adder Symbol](fulladder_symbol.jpeg)

---

## Waveform

![Full Adder Waveform](fulladder_waveform.jpeg)

---

