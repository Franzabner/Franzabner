<div align="center">

<img src="assets/logo.png" alt="YOSO-YAi" width="200"/>

# Francisco Abner

**Electrical Engineer | CEO & Founder, YOSO-YAi LLC**

Electrician turned EE. I do surgery on open-weights models and measure **Energy Per Intelligence** on the hardware that runs them.

`Fluor Corporation` · `Tesla Gigafactory` · `Meta Data Centers` · `YOSO-YAi`

[![Website](https://img.shields.io/badge/yoso--yai.com-C9A84C?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0IiBmaWxsPSJub25lIiBzdHJva2U9IiMwQTBBMEEiIHN0cm9rZS13aWR0aD0iMiIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIj48Y2lyY2xlIGN4PSIxMiIgY3k9IjEyIiByPSIxMCIvPjxwYXRoIGQ9Ik0yIDEyaDIwIi8+PHBhdGggZD0iTTEyIDJhMTUuMyAxNS4zIDAgMCAxIDQgMTAgMTUuMyAxNS4zIDAgMCAxLTQgMTAgMTUuMyAxNS4zIDAgMCAxLTQtMTAgMTUuMyAxNS4zIDAgMCAxIDQtMTAiLz48L3N2Zz4=&logoColor=0A0A0A)](https://yoso-yai.com)
[![GitHub Org](https://img.shields.io/badge/YOSO--YAi_Org-0A0A0A?style=for-the-badge&logo=github&logoColor=C9A84C)](https://github.com/YOSO-YAi)
[![Location](https://img.shields.io/badge/New_Albany,_Ohio-0A0A0A?style=for-the-badge&logo=googlemaps&logoColor=C9A84C)](https://github.com/Franzabner)

</div>

---

<div align="center">

*"The future of labor is compute."*

</div>

---

## About

I started as an electrician. I pulled wire on Fluor Corporation job sites across the country, learned instrumentation and controls at Tesla's Gigafactory, and wired Meta's NightCrawler data center. I have always thought in watts.

Now I apply that lens to AI models. Every token a model generates is a physical event — a specific quantity of energy flowing through a specific piece of silicon. The AI industry treats tokens as abstract units of text. I measure what they actually cost: **joules**.

I design every schematic, every PCB layout, and every enclosure for every product YOSO-YAi ships. Self-taught in KiCad 9.0 and Fusion 360. Every board starts on an exposed breadboard where every wire is visible, then moves to production PCB.

YOSO-YAi builds autonomous AI agents that replace human roles — not assist them, not augment them, **replace** them. Each agent is sold exclusively on custom Raspberry Pi hardware with an ATECC608B cryptographic wallet soldered to the board. No agent leaves without silicon.

---

## The EPI Research Pipeline

**Energy Per Intelligence (EPI)** is a metric I created to fill a gap nobody else occupies:

> **EPI = Joules per Token / Task Accuracy**

The people who do surgery on models never measure the energy cost of the result. The people who measure energy never touch the models. I do both — on the actual production hardware where the models run.

| Research Community | What They Do | What They Don't Do |
|---|---|---|
| Model Surgery (MoE-Pruner, NAEE, SparseGPT, Wanda) | Prune experts, remove heads, quantize weights | Measure energy. No joules/token. No edge hardware. |
| Energy Benchmarking (ML.ENERGY, EuroMLSys 2025) | Measure joules/token on stock models | Perform surgery. No model modification. No ARM. |
| **YOSO-YAi EPI Pipeline** | **Surgery + Energy + Efficiency Ratio + ARM Hardware + Custom Instrument** | **This is the gap we fill.** |

### The Research Loop

```
┌─────────────┐     ┌─────────────┐     ┌─────────────┐     ┌─────────────┐
│   SURGEON   │────▶│   PATIENT   │────▶│ INSTRUMENT  │────▶│  CALCULATE  │
│  DGX Spark  │     │ Pi Cluster  │     │  epi-meter  │     │  epi-bench  │
│  GB10 128GB │     │ 4x Pi 5     │     │ RP2350 + CT │     │  EPI Score  │
└─────────────┘     └─────────────┘     └─────────────┘     └──────┬──────┘
       ▲                                                           │
       │                    FEEDBACK LOOP                          │
       └───────────────────────────────────────────────────────────┘
              DGX learns to predict EPI before deploying
```

---

## YOSO-YAi FACTORY Architecture

The lab that powers everything. Four machines. Four AI employees. Zero overlap.

```
╔══════════════════════════════════════════════════════════════════════════════════╗
║                          YOSO-YAi FACTORY                                      ║
║                    The Engine Behind the Product                                ║
╠══════════════════════════════════════════════════════════════════════════════════╣
║                                                                                ║
║  ┌─────────────────────────────┐    ┌──────────────────────────────────────┐   ║
║  │       DGX SPARK             │    │         Pi 5 CLUSTER                 │   ║
║  │    GB10 · 128GB · 1 PFLOP   │    │    4x Pi 5 16GB · 64GB Total        │   ║
║  │                             │    │                                      │   ║
║  │  Autonomous Systems Eng.    │    │  Data Engineer                       │   ║
║  │  ├─ NemoClaw (AI Employee)  │    │  ├─ Academic DB Scraping             │   ║
║  │  ├─ Model Surgery (EPI)     │───▶│  ├─ Component/Company DB            │   ║
║  │  ├─ Fine-tuning (NeMo)      │    │  ├─ distributed-llama Inference     │   ║
║  │  ├─ n8n Orchestration       │    │  └─ EPI Measurement Target          │   ║
║  │  ├─ Kalshi Trading          │    │                                      │   ║
║  │  └─ Content Gen (ComfyUI)   │    │  Orchestrator Pi (10" Display)       │   ║
║  └─────────────────────────────┘    │  └─ Live Telemetry Dashboard         │   ║
║                                     └──────────────────────────────────────┘   ║
║  ┌─────────────────────────────┐    ┌──────────────────────────────────────┐   ║
║  │       LENOVO M70q           │    │         iMAC                         │   ║
║  │   i7-14700T · 32GB          │    │    Alexandra's Station               │   ║
║  │                             │    │                                      │   ║
║  │  Hardware Engineer (Abner)  │    │  3D Printing Engineer                │   ║
║  │  ├─ KiCad Board Review      │    │  ├─ Enclosure Design Review          │   ║
║  │  ├─ Schematic QC            │    │  ├─ Bambu Lab H2D Control            │   ║
║  │  ├─ BD Agent (Upwork)       │    │  ├─ Prototype Manufacturing          │   ║
║  │  └─ Senior Engineer Agent   │    │  └─ Commodities Trading              │   ║
║  └─────────────────────────────┘    └──────────────────────────────────────┘   ║
║                                                                                ║
║  ┌──────────────────────────────────────────────────────────────────────────┐  ║
║  │                     EXPOSED BREADBOARD (Center of Lab)                   │  ║
║  │          Pico 2 (RP2350) · NTC Thermistors · PID Fan Control            │  ║
║  │      Agent Heartbeat GPIO · UART Telemetry · Every Wire Visible         │  ║
║  │                                                                          │  ║
║  │   Validates: WRK-IN BMC subsystems + epi-meter power measurement        │  ║
║  │   Same silicon as production safety planes on WRK-IN & Controller       │  ║
║  └──────────────────────────────────────────────────────────────────────────┘  ║
║                                                                                ║
║  Command: CEO >>> Autonomous Sys. Eng. (DGX) >>> Data Eng. (Pi Cluster)       ║
║  Bambu Lab H2D ─── Prints all enclosure prototypes from CEO's designs         ║
╚══════════════════════════════════════════════════════════════════════════════════╝
```

---

## EPI Research Repos

> Each paper is a GitHub repository. README.md is the paper. `/data/` has raw results. `/code/` has reproduction scripts.

| # | Repository | Status | Core Contribution |
|:-:|---|:-:|---|
| 1 | [`energy-per-intelligence`](https://github.com/Franzabner/energy-per-intelligence) | `Upcoming` | Defines the EPI metric. Baseline measurements on Pi cluster. Introduces the epi-meter board. |
| 2 | [`epi-meter`](https://github.com/Franzabner/epi-meter) | `Upcoming` | Open-source power measurement board. RP2350 + 4x metering ICs + CT clamps. Full KiCad + firmware. |
| 3 | [`epi-bench`](https://github.com/Franzabner/epi-bench) | `Upcoming` | Shared tooling: EPI calculator, Pareto plotter, power trace logger, benchmark runner. Community CSV format. |
| 4 | [`expert-pruning-epi`](https://github.com/Franzabner/expert-pruning-epi) | `Upcoming` | MoE expert removal measured by EPI. Where is the efficient operating point? |
| 5 | [`mixed-quant-epi`](https://github.com/Franzabner/mixed-quant-epi) | `Upcoming` | Per-layer quantization evaluated by EPI. Two configs, identical perplexity, different joule costs. |
| 6 | [`attention-head-surgery-epi`](https://github.com/Franzabner/attention-head-surgery-epi) | `Upcoming` | Removing attention heads: does the energy actually drop, or do remaining heads compensate? |

---

## YOSO-YAi Product Ecosystem

> Hardware-bound autonomous AI agents. No agent is sold without silicon.

```
                    ┌───────────────────────────────┐
                    │      YOSO-YAi FACTORY          │
                    │   DGX Spark · Pi Cluster · n8n │
                    │   Fine-tune · Surgery · EPI    │
                    └───────────────┬───────────────┘
                                    │
                     Models ship on hardware ▼
          ┌─────────────────────────┼─────────────────────────┐
          │                         │                         │
   ┌──────▼──────┐          ┌──────▼──────┐          ┌───────▼──────┐
   │  Community   │          │ AGNT Board  │          │ WRK-STATION  │
   │    FREE      │          │   $1,800    │          │    $8,999    │
   │              │          │             │          │              │
   │ Fine-tuned   │          │ 1 Agent     │          │ 6 Agents     │
   │ models on    │          │ CM5 16GB    │          │ WRK-IN mgmt  │
   │ your own Pi  │          │ 1TB NVMe    │          │ Controller   │
   │              │          │ USB-C + Bat │          │ Silicon Moat │
   │ YOSO-YAi     │          │ Phone App   │          │ 10" Touch    │
   │ Terminal     │          │ ATECC608B   │          │ Mesh + eSIM  │
   └──────────────┘          └─────────────┘          └──────────────┘
```

<details>
<summary><b>Four Custom Boards — All Designed in KiCad 9.0 by the CEO</b></summary>

<br>

| Board | PARD | Silicon | Role | Fabrication |
|---|---|---|---|---|
| **WRK-IN** | PARD-WRKIN-001 | CM5 + RP2350A BMC | System management: 6x TPS54202 power, PID thermal, 90-min battery, mesh, graceful shutdown. 44 connectors. | JLCPCB |
| **WRK-AGNTs** | PARD-AGNT-001 | CM5 16GB | Worker blade: 1TB NVMe, ATECC608B wallet (factory-locked), TMP117 thermal. 85x77.5mm, 6-layer. 6 per WRK-STATION. | PCBWay |
| **WRK-STATION Controller** | PARD-WRKC-001 | CM5 + RP2350 BMC | Owner's terminal: 10" touchscreen, dual-slot ATECC608B (cold vault + operational), eSIM + SX1262 mesh, vault mode. | PCBWay |
| **AGNT Board** | PARD-AGNT-002 | CM5 16GB | Standalone consumer product: USB-C + battery, display, phone app, single ATECC608B wallet. | PCBWay |

</details>

<details>
<summary><b>The Silicon Moat — 87 Cents. Five Locks. Physics, Not Code.</b></summary>

<br>

Every WRK-AGNT blade carries a Microchip ATECC608B — a $0.87 cryptographic chip that physically locks every agent's economic activity to the YOSO-YAi factory. The key was born inside the chip during manufacturing and can never come out.

| Lock | What It Does | If Compromised |
|---|---|---|
| Agent Identity | Unique key pair signs every transaction. Born in silicon. | Factory rejects signature. Transaction denied. |
| Encrypted Channel | Chip connects to one server only: YOSO-YAi factory. | No channel forms. Data cannot flow. |
| Factory Certificate | Factory fingerprint sealed into chip at manufacturing. | Factory rejects destination. Transaction denied. |
| Model Integrity | Hash of AI model. Detects tampering. | Wallet locks. Agent economically dead. |
| Factory Public Key | Factory's crypto identity burned into chip. | No peer to connect to. Communication impossible. |

Bypass requires replacing the chip — destroying the agent's identity, wallet balance, and transaction history. The cost of circumvention exceeds the cost of compliance. That is a moat.

</details>

<details>
<summary><b>The epi-meter Board — Open Source Power Measurement</b></summary>

<br>

A custom PCB designed to instrument the Pi cluster with dedicated energy metering hardware. The first YOSO-YAi board design that is fully public.

| Parameter | Specification |
|---|---|
| MCU | RP2350 (Pico 2 silicon) — same as production BMC |
| Energy Metering | 4x dedicated ICs (ATM90E26/ADE7753 class) over SPI |
| Current Sensing | 4x CT clamps (SCT-013 class) — non-invasive |
| Measurement | True RMS voltage + current, real power, power factor |
| Output | UART to Orchestrator Pi, 115200 baud, JSON |
| Measurement Point | AC side — captures total system draw including PSU losses |

**Why not software measurement?** The Pi 5 has no GPU telemetry. Software power estimation on ARM Linux is unreliable. An electrician does not trust a device's self-reported power draw. An electrician puts a meter on the circuit.

**What gets published:** Full KiCad schematic, PCB layout, Gerber files, complete BOM, RP2350 firmware in C, 3D-printed enclosure, assembly guide, calibration procedure. Everything needed to build one.

</details>

---

## Model Surgery Toolchain

| Tool | Role in EPI Pipeline | License |
|---|---|---|
| `mergekit` | Model merging, DARE/TIES, expert manipulation | Open Source |
| `llama.cpp` | GGUF quantization, mixed-quant, Pi inference | MIT |
| `transformers` | Load/modify/save weights, head pruning, layers | Apache 2.0 |
| `safetensors` | Tensor-level weight surgery | Apache 2.0 |
| `distributed-llama` | Pi cluster inference engine | MIT |
| `NeMo` | Enterprise fine-tuning on DGX at FP8 | Apache 2.0 |
| `PEFT` | LoRA fine-tuning for energy payback analysis | Apache 2.0 |

---

## Background

```
2014-2017  Fluor Corporation     Industrial electrical · Conduit bending · Journeyman
2017-2019  Independent           Bitcoin trading · Project management (online coursework)
2020-2021  Tesla Gigafactory     Instrumentation & Controls · Sensor integration · PLC logic
2022-2024  Meta NightCrawler     Electrical Foreman · Power distribution · Data center wiring
2025-now   YOSO-YAi LLC          CEO & Founder · PCB design · AI hardware · EPI research
```

---

## Hardware & Software

<div align="center">

![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-C51A4A?style=flat-square&logo=raspberrypi&logoColor=white)
![KiCad](https://img.shields.io/badge/KiCad_9.0-314CB0?style=flat-square&logo=kicad&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![NVIDIA](https://img.shields.io/badge/DGX_Spark-76B900?style=flat-square&logo=nvidia&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Fusion 360](https://img.shields.io/badge/Fusion_360-FF6600?style=flat-square&logo=autodesk&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![MicroPython](https://img.shields.io/badge/MicroPython-2B2728?style=flat-square&logo=micropython&logoColor=white)

</div>

---

<div align="center">

**The future of labor is compute. Measured in energy per intelligence.**

[![YOSO-YAi](https://img.shields.io/badge/YOSO--YAi-C9A84C?style=for-the-badge&logo=github&logoColor=0A0A0A)](https://github.com/YOSO-YAi)

</div>
