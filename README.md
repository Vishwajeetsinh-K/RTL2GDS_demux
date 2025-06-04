# RTL2GDS_demux

This repository contains the complete RTL-to-GDSII ASIC flow for designing, simulating, synthesizing, and physically implementing a 1×8 demultiplexer (demux) handling 8-bit data. The project covers all stages from Verilog RTL coding through to final GDSII layout.

---

## Project Overview

- **Design**: Parameterized 1×8 demux module with 8-bit data inputs
- **Simulation**: Testbenches to verify functional correctness
- **Synthesis**: Logic synthesis using Synopsys Design Compiler (DC)
- **Physical Implementation**: Floorplanning, placement, and routing using Synopsys ICC2
- **Timing Analysis**: Static timing analysis (STA) with Synopsys PrimeTime (PT)
- **Outputs**: Final GDSII layout files ready for fabrication

---

## Repository Structure

- `rtl/` — Verilog RTL source code for the demux
- `rtl_simulation/` — Testbench files and simulation scripts
- `CONSTRAINTS/` — Design constraints files for synthesis and implementation
- `DC/` — Scripts and files for synthesis using Design Compiler
- `ICCII/` — Physical implementation scripts using ICC2
- `PT/` — Static timing analysis scripts and reports
- `WORK/` — Working directory for intermediate files
- `images/` — Visual illustrations and design flow snapshots
- `ref/` — Reference materials and documentation

---

## Getting Started

### Prerequisites

- Synopsys Design Compiler
- Synopsys ICC2
- Synopsys PrimeTime
- A Linux environment with required tool licenses

### Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/Vishwajeetsinh-K/RTL2GDS_demux.git
   cd RTL2GDS_demux
