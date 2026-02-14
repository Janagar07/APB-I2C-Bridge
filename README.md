# APB-I2C-Bridge
APB to I2C Bridge – UVM Verification

This repository presents a fully developed class-based UVM verification environment built from scratch to validate the functionality of an APB to I2C Bridge, ensuring accurate protocol translation and reliable data integrity between the APB and I2C interfaces.

Development Environment:
Developed using UVM (SystemVerilog) and simulated in Synopsys VCS on a Linux platform.

It includes:

Complete UVM testbench code (sequence item, sequences, sequencer, driver, monitor, agent, environment, test, scoreboard, subscriber, and interface)

Implementation of factory override in sequences

Implementation of driver-level callbacks

9 functional test cases (APB write/read, I2C write/read, repeated write/read)

Corresponding simulation waveforms for all test cases

The project demonstrates constrained-random verification, modular testbench architecture, and reusable verification components.
