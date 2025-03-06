UART VERIFICATION USING SYSTEMVERILOG

This project implements the verification module for the UART (Universal Asynchronous Receiver-Transmitter) communication protocol using SystemVerilog (SV). It consists of two main components:

Design_UART: This file contains the RTL design for the UART transmitter (TX) and receiver (RX) modules. The transmitter sends serial data, while the receiver captures and reconstructs the original parallel data based on UART protocol specifications.
Verification_UART: This file contains the testbench code, which verifies the UART communication using SystemVerilog classes such as generators, drivers, monitors, and scoreboards. The testbench ensures proper data transmission and reception under different scenarios.
The verification environment follows an object-oriented approach, making use of SystemVerilog classes to build a structured and reusable testbench. While UVM is not used, the methodology ensures a scalable and modular verification strategy.

Steps to Run the Simulation:
Copy & Run the Code in EDA Playground
Go to EDA Playground.
Select a SystemVerilog simulation environment (e.g., QuestaSim, VCS, or Xcelium).
Create Two Files:
Design_UART.sv → Copy & paste the UART design code.
Verification_UART.sv → Copy & paste the verification testbench code.
Run the Simulation and verify correct UART data transmission and reception.
This setup ensures the UART transmitter and receiver communicate accurately, verifying data integrity and protocol adherence.
