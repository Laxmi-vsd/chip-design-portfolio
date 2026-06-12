# Skills

---

## Programming & Hardware Languages

| Language | Proficiency | Use Case |
|----------|-------------|----------|
| **Verilog** | ★★★★★ | RTL design, FSM, FIFO, digital circuits |
| **SystemVerilog** | ★★★★☆ | Verification testbenches, UVM |
| **VHDL** | ★★★☆☆ | Digital design |
| **TCL** | ★★★☆☆ | EDA scripting |
| **C / C++** | ★★★☆☆ | Programming fundamentals |
| **Unix / Shell** | ★★★☆☆ | Tool automation |
| **MATLAB** | ★★★☆☆ | Simulation, analysis |

---

## EDA & Design Tools

<div class="tools-grid" markdown>

<div class="tool-card" markdown>
### Cadence Virtuoso
Analog IC design and simulation. Designed PLL components (Phase Detector, Charge Pump, VCO, Loop Filter) and Miller OTA. Performed AC analysis, gain-bandwidth, phase margin measurements.
</div>

<div class="tool-card" markdown>
### Xilinx ISE / Vivado
Digital design and FPGA implementation. Used for FSM, FIFO/LIFO, vending machine, and sequence detector projects.
</div>

<div class="tool-card" markdown>
### LTspice / HSPICE
Analog circuit simulation. PLL and OTA design, transient and AC analysis.
</div>

<div class="tool-card" markdown>
### Silvaco TCAD
Device-level simulation for AlN/β-Ga₂O₃ MOSHEMT biosensor research.
</div>

<div class="tool-card" markdown>
### Magic VLSI / OpenLane
Open-source physical design flow. Layout editing, DRC, LVS, RTL-to-GDSII.
</div>

<div class="tool-card" markdown>
### EDA Playground / OpenSTA
Online HDL simulation and static timing analysis for open-source flows.
</div>

</div>

---

## Hardware Verification

=== "SystemVerilog"
    - Layered testbench architecture (Generator, Driver, Monitor, Scoreboard)
    - Class-based verification components
    - Randomized stimulus generation with constraints
    - Interface-based DUT connection
    - Self-checking scoreboard mechanism
    - Assertions and waveform analysis

=== "UVM"
    - UVM testbench architecture: test, env, agent, driver, monitor, sequencer, scoreboard
    - `uvm_config_db` for configuration and virtual interfaces
    - TLM connections using analysis ports and exports
    - Sequence and sequence item classes with randomization
    - Component registration with `uvm_component_utils`
    - UVM phasing: build, connect, run, report
    - Reporting macros: `uvm_info`, `uvm_error`

---

## Analog IC Design

| Topic | Details |
|-------|---------|
| **PLL Design** | Phase Detector, Charge Pump, VCO, Loop Filter — LTspice & Cadence Virtuoso |
| **Miller OTA** | AC analysis, Input Offset Voltage, ICMR, Output Swing, GBW, Phase/Gain Margin |
| **MOSHEMT Devices** | AlN/β-Ga₂O₃, GaN heterostructure, pH sensor sensitivity analysis |

---

## Certifications & Workshops

- :fontawesome-solid-certificate: **INUP-i2i 18th User Awareness Workshop** — Device Fabrication & Characterization, IIT Delhi (Dec 2024)
- :fontawesome-solid-certificate: **Digital Electronics** — NPTEL (Completed)
- :fontawesome-solid-certificate: **SystemVerilog for Verification** — Udemy (Completed)
