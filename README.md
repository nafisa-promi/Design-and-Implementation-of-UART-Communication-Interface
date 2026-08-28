# Design and Implementation of UART Communication Interface

## Overview

This project presents the **design, verification, and synthesis of an 8-bit Universal Asynchronous Receiver-Transmitter (UART) communication interface** using Verilog HDL.

The UART system consists of a transmitter, receiver, and baud rate generator. The transmitter converts 8-bit parallel data into a serial stream with start and stop bits, while the receiver reconstructs the transmitted data using **16× oversampling**. An internal loopback architecture connects the transmitter output directly to the receiver input for complete end-to-end verification. :contentReference[oaicite:0]{index=0}

## Key Features

- 8-bit UART transmitter and receiver
- 9600 bps baud rate
- 16× receiver oversampling
- Internal TX-to-RX loopback
- Counter-based baud rate generation
- FSM-based transmitter and receiver
- Directed functional verification
- SystemVerilog layered verification
- Constrained Random Verification (CRV)
- Functional coverage analysis
- Gate-level synthesis using Cadence Genus
- Physical design using Cadence Innovus

##Project Team

Bangladesh University of Engineering and Technology (BUET)
Department of Electrical and Electronic Engineering
EEE 468 — VLSI Laboratory
Members
-Sheikh Munkasir Ahmed Rafeed
-Nafisa Anjum Promi
-Md. Shahriar Rahman Siam
-Mst. Tasnim Mehedy

