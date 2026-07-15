# Digital Voting Machine with Secure Memory using Verilog HDL

## Overview

This project implements a Digital Voting Machine using Verilog HDL. The design allows voting for four different candidates, stores the votes in digital registers (secure memory), and displays the final vote count after the voting process. The project was simulated using EDA Playground with Icarus Verilog.

---

## Features

- Verilog HDL Based Design
- Supports 4 Candidates
- Vote Counting Mechanism
- Secure Vote Storage using Registers
- Reset Functionality
- Result Display Mode
- Synthesizable Verilog Code
- Simulation using EDA Playground

---

## Inputs

| Signal | Description |
|--------|-------------|
| clk | System Clock |
| reset | Active High Reset |
| vote1 | Vote for Candidate 1 |
| vote2 | Vote for Candidate 2 |
| vote3 | Vote for Candidate 3 |
| vote4 | Vote for Candidate 4 |
| result | Displays Final Vote Count |

---

## Outputs

| Signal | Description |
|--------|-------------|
| candidate1 | Vote Count of Candidate 1 |
| candidate2 | Vote Count of Candidate 2 |
| candidate3 | Vote Count of Candidate 3 |
| candidate4 | Vote Count of Candidate 4 |

---

## Files

- digital_voting_machine.v
- voting_machine_tb.v
- waveform.png

---

## Software Used

- Verilog HDL
- EDA Playground
- Icarus Verilog
- EPWave

---

## Simulation

The design was successfully simulated using EDA Playground. The voting machine correctly counts votes for all candidates and stores them in secure memory registers. The final result is displayed after enabling the result signal.

---

## Simulation Waveform

![Waveform](waveform.png)

---

## Author

**Harshit Saini*

Internship Project - Codec Technologies
