# Projects

---

## Analog IC Design

### PLL (Phase-Locked Loop) Design
**Tools:** LTspice, Cadence Virtuoso · March 2024 – present

Designed a complete Phase-Locked Loop from scratch, implementing all key building blocks:

- **Phase Detector** — compares input and feedback clock phases
- **Charge Pump** — converts phase error to current pulses
- **Loop Filter** — converts current to control voltage
- **Voltage-Controlled Oscillator (VCO)** — generates output frequency

---

### Operational Transconductance Amplifier (OTA)
**Tools:** LTspice, Cadence Virtuoso

Designed and simulated a **Miller OTA** with complete characterization:

| Parameter | Measured |
|-----------|---------|
| Input Offset Voltage | Simulated |
| Input Common Mode Range (ICMR) | Measured |
| Maximum Output Voltage Swing | Measured |
| Open-Loop Gain | Simulated |
| Gain-Bandwidth Product (GBW) | Extracted |
| Phase Margin & Gain Margin | Verified |

---

## Digital RTL Design

### Vending Machine (FSM-based)
**Tools:** Xilinx ISE, Verilog HDL

Designed a vending machine controller using **Finite State Machine (FSM)** concepts in Verilog HDL.

### FIFO and LIFO RTL Design
**Tools:** Xilinx ISE, Verilog HDL

Designed and simulated a synchronous **FIFO** and **LIFO** using Verilog HDL.

### Finite State Machine — Sequence Detector
**Tools:** Verilog HDL

Designed a sequence detector using both **Moore** and **Mealy** FSM models in Verilog.

### Positive Edge Detector
**Tools:** Verilog HDL

Designed a Positive Edge Detector circuit using Verilog HDL.

---

## Hardware Verification (SystemVerilog Testbenches)

All testbenches use a **layered class-based architecture**: Generator → Driver → Monitor → Scoreboard.

| Design Under Test | GitHub |
|-------------------|--------|
| D Flip-Flop | [d-flipflop-sv](https://github.com/Blaxmidhar/verilog-and-systemverilog) |
| T Flip-Flop | [t-flipflop-sv](https://github.com/Blaxmidhar/verilog-and-systemverilog) |
| Full Adder | [full-adder-sv](https://github.com/Blaxmidhar/verilog-and-systemverilog) |
| 8:1 Multiplexer | [8x1-mux-sv](https://github.com/Blaxmidhar/verilog-and-systemverilog) |
| 1:8 Demultiplexer | [1x8-demux-sv](https://github.com/Blaxmidhar/verilog-and-systemverilog) |
| 4:2 Priority Encoder | [priority-encoder-sv](https://github.com/Blaxmidhar/verilog-and-systemverilog) |
| 4:16 Decoder | [decoder-4x16-sv](https://github.com/Blaxmidhar/verilog-and-systemverilog) |

---

## UVM Implementation

Currently implementing a **UVM-based testbench** to verify a simple adder, including:

- Custom transaction class with randomization and constraints
- Sequence and sequencer for stimulus generation
- Driver, monitor, and scoreboard with TLM connections
- Factory registration and UVM phasing

---

## Device Research

### AlN/β-Ga₂O₃ MOSHEMT pH Biosensor
**Tools:** Silvaco TCAD, OriginPro

Simulated and analysed sensitivity of an **AlN/β-Ga₂O₃ MOSHEMT** as a pH sensor. Work led to multiple publications including a journal paper communicated to *Sensing and Imaging*.

### GaN MOSHEMT with Embedded Cavity
Analysis of GaN heterostructure-based MOSHEMT with an embedded cavity for neutral biomolecule detection. Published at **IEEE DevIC 2025**.
