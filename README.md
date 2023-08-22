# UART-protocol-using-system-verilog
Introduction
UART communication is essential in many embedded systems, allowing microcontrollers and other devices to communicate with each other. This repository provides SystemVerilog implementations for both the UART transmitter and receiver, enabling you to integrate UART communication into your hardware projects.

DESIGN:
UART Transmitter
The UART transmitter module takes parallel data and converts it into a serial bit stream for transmission. It handles data formatting, start and stop bits insertion, and timing synchronization.

UART Receiver
The UART receiver module receives the serial bit stream, extracts the data, and reconstructs it into parallel form. It handles start and stop bit detection, data sampling, and synchronization.

Testbench
The testbench directory contains SystemVerilog files used to simulate and verify the functionality of the UART transmitter and receiver modules.
