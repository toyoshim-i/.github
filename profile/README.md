# `toyoshim-i // the wired` — Experimental AI & Systems Lab

> 🌐 **Web Portal (THE WIRED INDEX)**: **[https://toyoshim-i.github.io/](https://toyoshim-i.github.io/)**  
> Experimental AI, WebGPU inference runtimes, retro architecture operating systems, and autonomous agent playground.

---

## ⚡ `SEC_01` // Interactive Browser Demos

Zero-install live demos running directly in the browser. Browse the interactive index at **[toyoshim-i.github.io](https://toyoshim-i.github.io/)**.

| ID | Project | Live Demo | Runtime / Stack | Overview |
| :--- | :--- | :--- | :--- | :--- |
| **`SYS-01`** | **[PiPAPo](https://github.com/toyoshim-i/PiPAPo)**<br><sub>`pipapo // the wired`</sub> | **[▶ Launch CRT Demo](https://toyoshim-i.github.io/PiPAPo/)** | `v86` · `xterm.js` · `POSIX` · `Retro CPU` | Portable UNIX-like micro OS for bare-metal microcontrollers & retro CPUs. Boots into a dual-CRT emulator with the `push` shell, ~50 from-scratch POSIX utilities, and `Rogue 5.4.4`. |
| **`SYS-02`** | **[🪴 hachiue](https://github.com/toyoshim-i/hachiue)**<br><sub>`WebGPU LLM Runtime`</sub> | **[▶ Launch WebGPU](https://toyoshim-i.github.io/hachiue/)** | `WebGPU` · `GGUF Direct` · `OPFS` | Zero-dependency, mobile-optimized WebGPU LLM & translation runtime supporting PrismML Bonsai 1/2 (1-bit/ternary) and PFN PLaMo 3 Translate straight from `.gguf`. |
| **`SYS-03`** | **[🛠️ diorama](https://github.com/toyoshim-i/diorama)**<br><sub>`Weight-Space Patcher`</sub> | **[▶ Launch Playground](https://toyoshim-i.github.io/diorama/)** | `WebGPU` · `.safetensors` · `hachiue` | Weight-space modding playground for PLaMo 3 Translate. Hot-swaps ~792 KiB `.safetensors` sparse row patches directly in GPU storage buffers in ~5 ms. |
| **`SYS-04`** | **[neo](https://github.com/toyoshim-i/neo)**<br><sub>`WETWARE // NEURAL OVERCLOCK`</sub> | **[▶ Launch Trainer](https://toyoshim-i.github.io/neo/)** | `WebGPU LLM` · `Gemma` · `Cognitive` | Cognitive-science speed-reading trainer with 4 specialized modes and an in-browser WebGPU LLM comprehension benchmark scoring effective throughput (`eWPM`). |
| **`SYS-05`** | **[Fabre](https://github.com/toyoshim-i/Fabre)**<br><sub>`Flow-based Agent Engine`</sub> | **[▶ Launch Canvas](https://toyoshim-i.github.io/Fabre/)** | `Vanilla JS` · `MCP` · `Node Canvas` | Serverless, zero-dependency visual workflow editor and runtime harness for building and debugging LLM agents with MCP and tool sandboxes. |
| **`SYS-06`** | **[Argonventure](https://github.com/toyoshim-i/Argonventure)**<br><sub>`ADVs by Argon`</sub> | **[▶ Vol.1 SILENT PULSE](https://toyoshim-i.github.io/Argonventure/)**<br>**[▶ Vol.2 PASTEL VOID](https://toyoshim-i.github.io/Argonventure/pastel.html)** | `Web Audio ECG` · `PWA` · `ADV` | Two-volume psychological interrogation adventure anthology featuring real-time ECG biometric monitors and Web Audio heartbeat synthesis. |
| **`SYS-07`** | **[Karakuri](https://github.com/toyoshim-i/Karakuri)**<br><sub>`Visual Instrument`</sub> | **[▶ Launch WebGPU Demo](https://toyoshim-i.github.io/Karakuri/demo/index.html)** | `WebGPU / WGSL` · `.kir DSL` · `Rust` · `MCP` | GPU-native, AI-native real-time visual performance instrument that dynamically compiles procedural `.kir` shaders to WGSL for human + AI co-performance. |

---

## 📖 `SEC_02` // Documentation & Spec Portals

| ID | Project | Documentation | Overview |
| :--- | :--- | :--- | :--- |
| **`DOC-01`** | **[kinema](https://github.com/toyoshim-i/kinema)** | **[📖 Online Manual](https://toyoshim-i.github.io/kinema/)** | Offline hardware description toolchain for designing PCBs in a strict structural subset of Verilog (`.v`) with KiCad netlist generation and equivalence verification. |
| **`DOC-02`** | **[agent-man](https://github.com/toyoshim-i/agent-man)** | **[📖 Online Manual](https://toyoshim-i.github.io/agent-man/)** | Context-engineering-free, agent-native documentation and MCP engine that turns Markdown into on-demand CLI guides (`guide <topic>`), `SKILL.md`, and `llms.txt`. |

---

## 🧰 `SEC_03` // Experimental Repositories & Tooling

- **[Rhas](https://github.com/toyoshim-i/Rhas)** — Cross-assembler port of the X68000 M68000 macro assembler `HAS060X.X` written in Rust.
- **[Rhlk](https://github.com/toyoshim-i/Rhlk)** — Host-native Rust port of the X68000 high-speed object linker `HLK / HLKX`.
- **[execon](https://github.com/toyoshim-i/execon)** — Native macOS GUI application in Swift for parsing Windows `.exe` (PE) binaries and extracting embedded icons.
- **[vrealone](https://github.com/toyoshim-i/vrealone)** — Apache-2.0-licensed SteamVR (OpenVR direct-display HMD) driver for XREAL One glasses.
- **[agent-man-mg](https://github.com/toyoshim-i/agent-man-mg)** — Motion graphics and VJ craft knowledge packaged as a CLI and MCP server for AI agents.
