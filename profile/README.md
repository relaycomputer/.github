<div align="center">

<img src="https://relaycomputer.org/avatar.jpg" width="160" height="160" alt="The Relay Computer Project Logo" style="border-radius: 50%;" />

# The Relay Computer Project

**Discrete Electromechanical Architecture • Compiler Toolchains • Interactive Digital Twin**

[![Website](https://img.shields.io/badge/Website-relaycomputer.org-0284c7?style=flat-square&logo=google-chrome&logoColor=white)](https://relaycomputer.org)
[![YouTube](https://img.shields.io/badge/YouTube-@RelayComputerProject-red?style=flat-square&logo=youtube&logoColor=white)](https://www.youtube.com/@RelayComputerProject)
[![Simulator](https://img.shields.io/badge/Web_Simulator-Clack--Studio-f59e0b?style=flat-square&logo=webassembly&logoColor=white)](https://clack-studio.relaiscomputer.at/studio/)
[![License: MIT](https://img.shields.io/badge/License-MIT-emerald.svg?style=flat-square)](https://opensource.org/licenses/MIT)

</div>

---

### ⚡ Overview

**The Relay Computer Project** is an open-source initiative bridging historical electromechanical computer engineering with modern optimizing compiler toolchains and browser-based real-time simulation.

We design, build, and program discrete relay-based computing machinery:
* **Hardware Architecture:** 16-bit register datapath, discrete Tianbo relay boards, MAX1000 FPGA microcode sequencing bridge, and physical 32×32 LED matrix display.
* **Compiler & Toolchain:** **Clack-BASIC**, an optimizing compiler written in Go featuring a Pratt expression parser, static activation allocation (solving the 1-level return stack limitation), Q8.8 fixed-point, and Konrad Zuse-inspired CLACK-F16 floating-point arithmetic.
* **Digital Twin & IDE:** **Clack-Studio**, a cycle-accurate WebAssembly emulator with a real-time interactive frontpanel, memory inspector, disassembler, and acoustic relay click synthesis.

---

### 📦 Key Repositories

| Repository | Description | Primary Stack |
| :--- | :--- | :--- |
| **[`clack-basic`](https://github.com/relaycomputer/clack-basic)** | Optimizing BASIC compiler, lexer/parser, AST, static register allocator & disassembler | Go 1.23, Assembly |
| **[`clack-studio`](https://github.com/relaycomputer/clack-studio)** | Cycle-accurate web emulator, frontpanel simulation, interactive I/O & WebAssembly engine | Svelte 5, Vite, Go (WASM) |

---

### 👥 Engineering Team & Contacts

| Domain | Lead Engineer | Contact |
| :--- | :--- | :--- |
| **Hardware Architecture & Discrete Relays** | **Peter Prikasky** ([relaiscomputer.at](https://relaiscomputer.at)) | `hardware@relaycomputer.org` |
| **Software Architecture, Compiler & Simulation** | **Christian Buchhas** ([relaycomputer.org](https://relaycomputer.org)) | `software@relaycomputer.org` |
| **General Inquiries & Community** | **The Relay Computer Project** | `contact@relaycomputer.org` |

---

<div align="center">
  <sub>Open Hardware & Open Source Software under the MIT License.</sub>
</div>
