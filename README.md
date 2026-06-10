# Awesome EDA 🛠️

> A curated list of **high-quality** Electronic Design Automation (EDA) tools, projects, tutorials, books, and resources.

This list focuses on **actively maintained, open-source, production-ready, or education-focused** EDA tools for PCB, FPGA, ASIC, and VLSI design — excellent for learning, hobby projects, or real silicon tape-outs in 2026.

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
- [SaaS & Hosted Platforms](#saas--hosted-platforms)
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
| [KiCad](https://www.kicad.org) | professional-grade schematic capture + PCB layout (industry standard open alternative) | — |
| [LibrePCB](https://librepcb.org) | modern, intuitive EDA suite with excellent library management | — |
| [eSim](https://github.com/FOSSEE/eSim) | full-stack circuit design, simulation, and PCB (KiCad + ngspice + Verilator) | — |

---

### HDL Simulation & Verification

| Tool | Description | Year Initialized |
|---|---|---|
| [Verilator](https://github.com/verilator/verilator) | fastest Verilog/SystemVerilog simulator (used in industry) | — |
| [Icarus Verilog](https://github.com/steveicarus/iverilog) | lightweight Verilog simulator & synthesizer | — |
| [GHDL](https://github.com/ghdl/ghdl) | VHDL simulator with excellent IEEE support | — |
| [sv2v](https://github.com/zachjs/sv2v) | SystemVerilog to Verilog translator widely used in FPGA flows | 2019 |

---

### Logic Synthesis & FPGA Tools

| Tool | Description | Year Initialized |
|---|---|---|
| [Yosys](https://github.com/YosysHQ/yosys) | extensible Verilog RTL synthesis suite | 2012 |
| [Berkeley-ABC](https://github.com/berkeley-abc/abc) | industrial-strength logic synthesis and verification system | 2005 |
| [nextpnr](https://github.com/YosysHQ/nextpnr) | FPGA place-and-route (Lattice, ECP5, iCE40, etc.) | — |
| [VTR (Verilog-to-Routing)](https://github.com/verilog-to-routing/vtr-verilog-to-routing) | academic FPGA CAD flow | 2012 |

---

### ASIC & Physical Design Flows

| Tool | Description | Year Initialized |
|---|---|---|
| [OpenROAD](https://github.com/The-OpenROAD-Project/OpenROAD) | autonomous RTL-to-GDSII flow | — |
| [OpenLane](https://github.com/The-OpenROAD-Project/OpenLane) | complete automated ASIC flow (used for real tape-outs) | — |
| [iEDA](https://github.com/OSCC-Project/iEDA) | full netlist-to-GDS infrastructure | — |
| [OpenSTA](https://github.com/The-OpenROAD-Project/OpenSTA) | static timing analysis engine used in modern open ASIC flows | 2018 |
| [RePlAce](https://github.com/The-OpenROAD-Project/RePlAce) | analytic global placement engine | 2018 |
| [TritonCTS](https://github.com/The-OpenROAD-Project/TritonCTS) | clock tree synthesis engine | 2018 |
| [OpenDP](https://github.com/sanggido/OpenDP) | detailed placement optimizer | 2018 |
| [OpenTimer](https://github.com/OpenTimer/OpenTimer) | high-performance timing analysis framework | 2015 |

---

### Layout Editors & Viewers

| Tool | Description | Year Initialized |
|---|---|---|
| [Magic VLSI](https://github.com/libresilicon/magic-8.22017) | venerable interactive layout editor | 2017 |
| [KLayout](https://github.com/KLayout/klayout) | powerful GDS/OASIS viewer, editor, and DRC tool | 2017 |
| [Qrouter](http://opencircuitdesign.com/qrouter/) | grid-based autorouter for IC layouts | 2013 |

---

### Analog & Mixed-Signal Tools

| Tool | Description | Year Initialized |
|---|---|---|
| [ngspice](https://github.com/imr/ngspice) | SPICE circuit simulator (industry-grade open source) | 1999 |
| [Xschem](https://github.com/stefanschippers/xschem) | schematic capture for analog/mixed-signal | — |
| [ALIGN](https://github.com/ALIGN-analoglayout/ALIGN-public) | automated analog layout synthesis framework | 2018 |

---

## SaaS & Hosted Platforms

| Product | Description | Pricing | Free Tier Limit |
|---|---|---|---|
| [Flux.ai](https://www.flux.ai) | Browser-based PCB design with AI Copilot and collaboration. | $20/mo (Starter) | 14-day trial; public projects only after |
| [EasyEDA](https://easyeda.com) | Cloud-based suite integrated with JLCPCB/LCSC parts library. | $7.99/mo (Pro) | Forever free for personal/commercial use |
| [Upverter](https://upverter.com) | Modular, browser-native PCB design tool by Altium. | Free | Unlimited use (no paid tier) |
| [CircuitMaker](https://circuitmaker.com) | Community-focused PCB design powered by Altium's engine. | Free | Unlimited public projects only |
| [Autodesk Fusion](https://www.autodesk.com/products/fusion-360) | Professional integrated CAD/CAM/CAE and PCB design. | ~$700/year (Pro) | Non-commercial use (limited to 2 layers) |
| [CircuitMind](https://circuitmind.io) | AI-driven schematic generation and BOM optimization. | $29/mo (Starter) | 1 project, 1 seat, 100 AI feedback items |
| [JITX](https://www.jitx.com) | Programmatic (Python-based) hardware design automation. | Sales-led | Free for public CERN OHL-licensed designs |
| [CADLAB.io](https://cadlab.io) | Visual diff and version control platform for hardware. | $6/mo (Indiv) | Unlimited public projects & collaborators |
| [InventHub](https://inventhub.io) | Git-based design management and collaboration platform. | Sales-led | Free for open-source community projects |

---

## Tools & Utilities

| Tool | Description | Year Initialized |
|---|---|---|
| [SkyWater 130nm PDK](https://github.com/google/skywater-pdk) | free manufacturable process design kit | — |
| [Open_PDKs](https://github.com/RTimothyEdwards/open_pdks) | open-source process design kits | — |
| [CVC](https://github.com/d-michail/cvc) | circuit verifier | 2009 |
| [Netgen](https://github.com/RTimothyEdwards/netgen) | LVS (Layout vs Schematic) | — |

---

## Experimental, Research & Specialized EDA Projects (From clin99 Awesome-EDA **See also**: https://github.com/clin99/awesome-eda)

| Tool | Primary Area | Description | Year Initialized |
|---|---|---|---|
| [PyMTL](https://github.com/cornell-brg/pymtl) | Hardware Modeling | Python-based hardware modeling and simulation framework used in academia | 2012 |
| [ILAng](https://github.com/Bo-Yuan-Huang/ILAng) | SoC Verification | Instruction-Level Abstraction modeling and verification platform | 2016 |
| [Galois Parallel Framework](https://github.com/IntelligentSoftwareSystems/Galois) | CAD Infrastructure | Parallel algorithm research framework used in EDA experimentation | 2010 |
| [HAMMER](https://github.com/ucb-bar/hammer) | Flow Orchestration | Modular ASIC flow generation and configuration framework | 2017 |
| [Lgraph](https://github.com/masc-ucsc/lgraph) | Synthesis Infrastructure | Graph-based synthesis and simulation infrastructure | 2018 |
| [MAGICAL](https://github.com/magical-eda/MAGICAL) | Analog Layout Automation | Machine-generated analog IC layout automation framework | 2019 |
| [AMPSE](https://github.com/USCPOSH/AMPSE) | Analog Design Automation | Analog parameter search and optimization engine | 2019 |
| [Analog Known Good Designs](https://github.com/USCPOSH/AMS_KGD) | Analog Reference Designs | Verified analog circuit design repository | 2019 |
| [Circuit IP Sanitizer](https://github.com/USCPOSH/Sanitizer) | Analog Verification | IP validation and sanitization tooling | 2019 |
| [AMC (Async Memory Compiler)](https://github.com/asyncvlsi/AMC) | Memory Design | Asynchronous memory compiler research project | 2019 |
| [PVT Sensors](https://github.com/scale-lab/PVTsensors) | Analog Test Infrastructure | Open PVT sensor development framework | 2019 |
| [UW IDEA Analog TestCases](https://github.com/uwidea/UW-IDEA_AnalogTestCases) | Analog Benchmarks | Analog testing and validation circuits | 2019 |
| [OpenPiton](https://github.com/PrincetonUniversity/openpiton) | Research SoC Platform | Manycore open research processor platform | 2018 |
| [PRGA](https://github.com/PrincetonUniversity/prga) | FPGA Workflow | Research FPGA architecture exploration workflow | 2018 |
| [OpenFPGA (FPGA-SPICE)](https://github.com/LNIS-Projects/OpenFPGA) | FPGA Modeling | FPGA architecture modeling and SPICE co-simulation | 2018 |
| [EPFL Logic Benchmark Suite](https://github.com/lsils/benchmarks) | Benchmarks | Widely used combinational logic synthesis benchmarks | 2018 |
| [Parser-SPEF](https://github.com/OpenTimer/Parser-SPEF) | Physical Design Utility | SPEF parasitic extraction file parser | 2018 |
| [UW BSG Pipecleaner Suite](https://github.com/bespoke-silicon-group/bsg_pipeclean_suite) | Verification Benchmarks | Microarchitecture testing framework | 2019 |
| [Graywolf](https://github.com/rubund/graywolf2014) | Placement | Academic ASIC placement research tool | 2014 |
| [BoxRouter](https://github.com/krzhu/BoxRouter) | Routing | Global routing academic prototype | 2016 |

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

[![Star History Chart](https://api.star-history.com/svg?repos=ishandutta2007/Awesome-EDA&type=date&legend=top-left)](https://www.star-history.com/#ishandutta2007/Awesome-EDA&type=date&legend=top-left)
