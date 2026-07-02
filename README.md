<h1 align="center">Hi 👋, I'm Eyal Schiff</h1>

<p align="center">
  <a href="https://www.linkedin.com/in/eyal-schiff-094694307/">
    <img src="https://img.shields.io/badge/LinkedIn-Profile-informational?style=flat&logo=linkedin&logoColor=white&color=0D76A8" alt="LinkedIn Profile"/>
  </a>
  <img src="https://komarev.com/ghpvc/?username=EyalSchiff&label=Profile%20views&color=0e75b6&style=flat" alt="EyalSchiff" />
</p>

<h3 align="center">B.Sc. Electrical Engineering Graduate @ Bar-Ilan University | Hardware Design & Verification</h3>

Welcome to my GitHub profile! I'm an Electrical Engineering graduate specializing in Nanoelectronics, digital systems, and chip design. This space serves as my portfolio for building, optimizing, and sharing advanced RTL designs, verification environments, and physical implementation flows.

## 👨‍💼 About Me

- 🎓 **Education:** **B.Sc. in Electrical Engineering** from **Bar-Ilan University**.
- 💡 **Focus Areas:** Chip Design, Hardware Architecture, RTL Design (Verilog / SystemVerilog), Design Verification (UVM/SystemVerilog), and Physical Design (RTL-to-GDSII).
- 🚀 **Mission:** Detail-oriented, highly analytical, and deeply passionate about hardware acceleration. I thrive on breaking down complex structural challenges—from core digital architectures and hardware resource allocators to high-performance AI processing engines.

## 🛠️ Hardware & Development Tools

<p align="left"> 
  <a href="https://isocpp.org/" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="C++" width="40" height="40"/> 
  </a>
  <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="C" width="40" height="40"/> 
  </a> 
  <a href="https://www.python.org" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="40" height="40"/> 
  </a> 
  <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="Linux" width="40" height="40"/> 
  </a> 
  <img src="https://img.shields.io/badge/SystemVerilog-000000?style=for-the-badge&logo=si-five&logoColor=white" alt="SystemVerilog" height="40"/>
  <img src="https://img.shields.io/badge/Cadence_Innovus_/_Virtuoso-E31837?style=for-the-badge&logo=cadence&logoColor=white" alt="Cadence Tools" height="40"/>
</p>

## 📂 Featured Projects

Here are the main repositories currently available on my profile:

* **[FPGA_Excellarator: HW/SW Co-Design CNN Accelerator](https://github.com/EyalSchiff/FPGA_Excellarator):** Design and rigorous cycle-accurate optimization of a full hardware acceleration subsystem for Convolutional Neural Networks (CNNs) tightly coupled with a custom RISC-V CPU. 
    * **The Breakthrough:** Slashed end-to-end simulation latency from **over 1,000,000 cycles (pure software baseline)** down to exactly **4,029 clock cycles**—achieving a **>250x hardware speedup**.
    * **Architectural Concept:** Re-architected a半-serial Output-Stationary baseline into a highly parallel **Input-Stationary / Broadcast-MAC Array** with 32 parallel 32-bit accumulators. Unified memory streaming to rigid 32-byte physical strides paired with high-speed software memory padding (`memset`) to eliminate FSM handshake bubbles and maximize 256-bit bus throughput.

* **[B.Sc. Final Project: GC-eDRAM DRT Optimization](https://github.com/EyalSchiff/Final-Project):** My graduation project focusing on optimizing Data Retention Time (DRT) for Gain-Cell embedded DRAM to maximize memory availability and energy efficiency. Designed Verilog behavioral volatility models and implemented a smart, LUT-based adaptive refresh controller with multiplexing logic to dramatically reduce refresh downtime and static power leakage.

* **[Self-Verilog-Projects](https://github.com/EyalSchiff/Self-verilog-projects):** A comprehensive collection of structural RTL designs and custom verification environments.
    * **16-Entry Hardware Resource Allocator (Locker System):** Implemented a state-dependent, hierarchical resource allocator from scratch, integrating SR flip-flops, encoders, and multi-stage muxes under strict priorities where reset overrides simultaneous operations.
    * **FIFO8 Buffer Verification:** A synchronous 64-bit wide, 8-entry FIFO. Demonstrates equivalence verification by checking 100% bit-accurate logical matching between behavioral dataflows and gate-level structural models.

* **[RISCV-RTL2GDS: Physical Design Implementation](https://github.com/EyalSchiff/RISCV-RTL2GDS):** A complete RTL-to-GDSII Physical Design flow of a low-power RISC-V SoC core utilizing **Cadence Innovus** and **TSMC 65nm** library cells.
    * **The Flow:** Executed the entire PnR implementation lifecycle: Floorplanning, Power Planning (Rings & Stripes), Cell Placement, Clock Tree Synthesis (CTS), and Detailed Routing.
    * **Signoff:** Closed post-route timing (Setup/Hold slack optimization) and successfully cleared physical signoff with **zero DRC, antenna, or connectivity violations**.

## 🤝 Let's Connect

I am actively looking for opportunities in **Digital Design, Design Verification, and Physical Design**. I'm always eager to talk chip design, hardware architectures, or microelectronics—let's connect on [LinkedIn](https://www.linkedin.com/in/eyal-schiff-094694307/)!
