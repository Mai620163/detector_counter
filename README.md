# Sequence Detector using Mealy FSM

This repository contains a digital design project implementing a synchronous Sequence Detector written in Verilog HDL. The design is modeled as a Mealy Finite State Machine (FSM), where the output depends on both the current state and the current input.

---

## Features
* Design Style: Mealy FSM (Output is a function of current state and inputs).
* Clock & Reset: Synchronous state transitions with an asynchronous active-high reset (rst).
* Implementation: Written in structured Verilog using parameters for clean state definitions (S0, S1, S2, S3).
* Verification: Fully simulated and verified using testbench waveforms to ensure precise sequence tracking.

---

## Hardware Description
* Inputs: 
  * clk: Clock signal.
  * rst: Asynchronous active-high reset.
  * in: Serial input data stream.
* Outputs: 
  * y: Output flag (asserts to 1 when the target sequence is detected).

---

## Simulation & Verification
The design has been simulated to verify its functional correctness. Below is the simulation waveform showing the state transitions and output generation:

*(Optional: You can drag and drop your simulation screenshot here to display the green waveforms)*
