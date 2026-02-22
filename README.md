# Awesome EDA 🛠️

> A curated list of **high-quality** Electronic Design Automation (EDA) tools, projects, tutorials, books, and resources.

This list focuses on **actively maintained, open-source, production-ready, or education-focused** EDA tools for PCB, FPGA, ASIC, and VLSI design — excellent for learning, hobby projects, or real silicon tape-outs in 2026.

**See also**: [clin99/awesome-eda](https://github.com/clin99/awesome-eda) (the comprehensive open-source EDA project catalog).

---
## Contents

- [Getting Started](#getting-started)
- [Books](#books)
- [Hands-on Tutorials & Example Flows](#hands-on-tutorials--example-flows)
- [Open-Source EDA Tools & Flows](#open-source-eda-tools--flows)
  - [PCB & Schematic Design](#pcb--schematic-design)
  - [HDL Simulation & Verification](#hdl-simulation--verification)
  - [Logic Synthesis & FPGA Tools](#logic-synthesis--fpga-tools)
  - [ASIC & Physical Design Flows](#asic--physical-design-flows)
  - [Layout Editors & Viewers](#layout-editors--viewers)
  - [Analog & Mixed-Signal Tools](#analog--mixed-signal-tools)
- [Tools & Utilities](#tools--utilities)
- [Community & Learning Resources](#community--learning-resources)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

- [KiCad Official Tutorials](https://www.kicad.org/help/tutorials/) – start with PCB design in minutes
- [OpenLane Quickstart](https://openlane.readthedocs.io/en/latest/docs/source/quickstart.html) – complete RTL-to-GDSII flow
- [OpenROAD User Guide](https://openroad.readthedocs.io/) – foundations of autonomous ASIC design
- [Yosys Documentation](https://yosyshq.net/yosys/) – Verilog synthesis explained
- [SkyWater 130nm PDK + OpenLane](https://github.com/google/skywater-pdk) – free PDK for real tape-outs
- [eSim Tutorials](https://esim.fossee.in/tutorials) – integrated circuit + PCB workflow

## Books

- [Electronic Design Automation: Synthesis, Verification, and Test](https://www.sciencedirect.com/book/9780123743640/electronic-design-automation) by Lavagno, Markov, Scheffer – the definitive EDA reference
- [Essential Electronic Design Automation (EDA)](https://www.amazon.com/Essential-Electronic-Design-Automation-EDA/dp/0131828290) by Mark D. Birnbaum – easy-to-understand overview
- [CMOS VLSI Design: A Circuits and Systems Perspective](https://www.amazon.com/CMOS-VLSI-Design-Circuits-Perspective/dp/0321547748) by Weste & Harris – classic VLSI bible
- [Algorithms for VLSI Physical Design Automation](https://www.amazon.com/Algorithms-VLSI-Physical-Design-Automation/dp/0792394895) by Naveed Sherwani – physical design fundamentals
- [Digital Integrated Circuits: A Design Perspective](https://www.amazon.com/Digital-Integrated-Circuits-Design-Perspective/dp/0130909963) by Rabaey – RTL to silicon

## Hands-on Tutorials & Example Flows

- [Tiny Tapeout](https://tinytapeout.com/) – submit your design and get it fabricated on real silicon
- [OpenLane Example Designs](https://github.com/The-OpenROAD-Project/OpenLane/tree/master/designs) – ready-to-run examples
- [OpenROAD Flow Tutorials](https://github.com/The-OpenROAD-Project/OpenROAD-flow-scripts) – complete end-to-end flows
- [Yosys + nextpnr FPGA Workshop](https://github.com/YosysHQ/nextpnr) examples
- [KiCad + ngspice Simulation Labs](https://forum.kicad.info/) community projects

## Open-Source EDA Tools & Flows

---

### PCB & Schematic Design

| Tool | Description | Year Initialized |
|---|---|---|
| KiCad | professional-grade schematic capture + PCB layout (industry standard open alternative) | — |
| LibrePCB | modern, intuitive EDA suite with excellent library management | — |
| eSim | full-stack circuit design, simulation, and PCB (KiCad + ngspice + Verilator) | — |

---

### HDL Simulation & Verification

| Tool | Description | Year Initialized |
|---|---|---|
| Verilator | fastest Verilog/SystemVerilog simulator (used in industry) | — |
| Icarus Verilog | lightweight Verilog simulator & synthesizer | — |
| GHDL | VHDL simulator with excellent IEEE support | — |

---

### Logic Synthesis & FPGA Tools

| Tool | Description | Year Initialized |
|---|---|---|
| Yosys | extensible Verilog RTL synthesis suite | 2012 |
| nextpnr | FPGA place-and-route (Lattice, ECP5, iCE40, etc.) | — |
| VTR (Verilog-to-Routing) | academic FPGA CAD flow | 2012 |

---

### ASIC & Physical Design Flows

| Tool | Description | Year Initialized |
|---|---|---|
| OpenROAD | autonomous RTL-to-GDSII flow | — |
| OpenLane | complete automated ASIC flow (used for real tape-outs) | — |
| iEDA | full netlist-to-GDS infrastructure | — |

---

### Layout Editors & Viewers

| Tool | Description | Year Initialized |
|---|---|---|
| Magic VLSI | venerable interactive layout editor | 2017 |
| KLayout | powerful GDS/OASIS viewer, editor, and DRC tool | 2017 |

---

### Analog & Mixed-Signal Tools

| Tool | Description | Year Initialized |
|---|---|---|
| ngspice | SPICE circuit simulator (industry-grade open source) | 1999 |
| Xschem | schematic capture for analog/mixed-signal | — |

---

## Tools & Utilities

| Tool | Description | Year Initialized |
|---|---|---|
| SkyWater 130nm PDK | free manufacturable process design kit | — |
| Open_PDKs | open-source process design kits | — |
| CVC | circuit verifier | — |
| Netgen | LVS (Layout vs Schematic) | — |

---
## Community & Learning Resources

- [EDAboard](https://www.edaboard.com) – largest international EDA discussion forum
- [r/VLSI](https://www.reddit.com/r/VLSI/), [r/FPGA](https://www.reddit.com/r/FPGA/), [r/ECE](https://www.reddit.com/r/ECE/), [r/chipdesign](https://www.reddit.com/r/chipdesign/)
- [KiCad Discord](https://discord.com/invite/FANuKv8sZn) – official KiCad community
- [OpenROAD GitHub Discussions](https://github.com/The-OpenROAD-Project/OpenROAD/discussions) – active developer & user support
- [VLSIGuru / VLSI Academy](https://vlsiguru.com) – free/paid training resources
- [1BitSquared Community](https://1bitsquared.com/pages/community) – FPGA & open hardware

## Contributing

Contributions are **highly welcome**! Please read the rules below.

**Rules**:
- Only **high-quality, actively maintained** tools (recent commits, good documentation, real usage).
- One line per entry:
  ```markdown
  - [Tool Name](link) – Short, compelling one-sentence description.
  ```

## ✨ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=ishandutta2007/Awesome-EDA&type=date&legend=bottom-right)](https://www.star-history.com/#ishandutta2007/Awesome-EDA&type=date&legend=bottom-right)

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=ishandutta2007/Awesome-EDA&type=date&legend=top-left)](https://www.star-history.com/#ishandutta2007/Awesome-EDA&type=date&legend=top-left)
