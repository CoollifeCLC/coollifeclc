<!-- HERO -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:14041E,40:2A0B3D,100:5B1A68&height=220&section=header&text=Sheron%20Gibson&fontSize=48&fontColor=ffffff&animation=fadeIn&desc=Platform%20Engineering%20%E2%80%A2%20AI%2FML%20Systems%20%E2%80%A2%20Deterministic%20Compute&descAlignY=68" width="100%"/>
</p>

<h2 align="center">
Building AI infrastructure, deterministic systems, developer platforms, and production software.
</h2>

<p align="center">
Platform Engineering • AI/ML Infrastructure • Distributed Systems • Developer Tooling
</p>

---

# 👨🏾‍💻 About Me

<img src="https://readme-typing-svg.herokuapp.com?color=3ECF8E&width=900&lines=Platform+Engineer.;AI%2FML+Systems+Builder.;Deterministic+Systems+Engineer.;Developer+Tooling+Engineer.;Full+Stack+Systems+Builder." />

I'm a systems-focused software engineer building platforms across AI/ML infrastructure, deterministic compute, developer tooling, distributed systems, and full-stack applications.

My work spans:

* AI training, benchmarking & local inference infrastructure
* Deterministic and replayable execution systems
* Distributed compute architecture
* Developer platforms & tooling
* GPU/CPU-aware execution systems
* Full-stack applications
* Internal tools & workflow automation
* Operational and logistics software

I like owning difficult problems end-to-end — from architecture and runtime behavior to APIs, infrastructure, desktop applications, and user-facing interfaces.

---

# 🚀 Featured Projects

## 🧠 Atlas Lab — Local AI Training & Lifecycle Platform

Atlas Lab is a deterministic machine learning platform for creating, training, benchmarking, promoting, running, and evolving AI residents locally.

Rather than treating a model as a static artifact, Atlas Lab provides an end-to-end lifecycle:

**curriculum → train → benchmark → promote → inference → evolve**

### Highlights

* Local CPU and GPU-aware training architecture
* Resident-specific training and learned-state management
* Dataset and curriculum pipelines
* Benchmark suites and promotion workflows
* Local inference without requiring a hosted inference API
* Deterministic resident lifecycle management
* Seed-based resident identity and lineage
* Hardware capability discovery and execution selection
* Electron desktop application connected to the Atlas web platform
* Resident evolution and lifecycle visualization

Atlas Lab currently includes multiple specialized residents, including **Nexus**, its coding resident.

**Tech:** TypeScript, React, Electron, Node.js, Python, PyTorch, llama.cpp, Supabase, PostgreSQL, AWS

---

## 🤖 Nexus — Locally Trainable Coding Resident

Nexus is Atlas Lab's coding-focused AI resident, built on a frozen 30B multimodal foundation with lightweight trainable resident adapters.

### Architecture

* 30B frozen foundation model
* 52-layer language stack
* Rank-8 LoRA adapters across attention projections
* ~7.3M trainable resident parameters
* Local CPU inference through llama.cpp
* Hardware-aware training execution
* Benchmark → promotion → inference lifecycle
* Persistent resident identity and learned state

The architecture separates the large frozen foundation from the resident's comparatively small learned state, allowing Nexus to evolve without reproducing or retraining the entire foundation model.

**Focus:** local AI, parameter-efficient training, inference infrastructure, model lifecycle systems

---

## ⚙️ Contract OS — Deterministic Compute & Runtime Platform

Contract OS is an experimental deterministic compute and platform architecture built around reproducible execution, distributed scheduling, runtime orchestration, and observable system behavior.

Its compute architecture includes **Nine Compute**, a deterministic execution layer designed around isolated compute regions and runtime instances.

### Highlights

* Deterministic runtime execution
* Distributed scheduler architecture
* Nine Compute regions and execution instances
* Replayable execution
* Deterministic pseudo-random execution primitives
* Runtime orchestration
* Developer platform tooling
* Platform administration systems
* Self-healing architecture experiments
* Deterministic execution verification

Previous compute benchmarks have demonstrated multi-million-action-per-second raw execution throughput under controlled workloads.

**Tech:** TypeScript, Node.js, AWS, PostgreSQL, Supabase, PM2, distributed runtime architecture

---

## 🎮 Elemental Arena — Custom WebGPU Game Architecture

Elemental Arena is an experimental game and simulation platform being developed around a custom rendering and runtime architecture rather than a traditional game engine.

### Engineering Focus

* WebGPU rendering
* C++ systems
* Custom renderer architecture
* GPU lifecycle management
* Hardware capability detection
* Deterministic simulation
* Performance and content budgets
* Explicit GPU readiness contracts
* Reproducible execution
* Engine-level architecture

The project is being developed using explicit engine contracts, performance budgets, lifecycle boundaries, and evidence-backed architecture decisions.

**Tech:** C++, WebGPU, TypeScript, CMake, custom engine architecture

---

## 🏗️ Shipyard Operational Software *(Used in Production)*

Internal software built to support material accountability and warehouse operations in an active shipyard environment.

### Highlights

* Government Furnished Material (GFM) tracking
* Commercial material management
* Tool and equipment accountability
* Gas bottle tracking across yard locations
* Calibration and compliance workflows
* Certification/document management
* Operational inventory visibility
* Production usage by warehouse personnel

Built from direct operational experience to replace fragmented manual workflows with centralized, searchable systems.

**Outcome:** Used in daily operations and led to discussions around broader implementation across warehouse operations.

**Tech:** React, TypeScript, Node.js, AWS, Supabase, PostgreSQL

---

## 🦐 Shrimp Check — VS Code Developer Tool

A lightweight VS Code productivity extension built around an intentionally simple idea: developers shouldn't need to leave their workflow to remember to move.

### Highlights

* Organic Marketplace adoption
* Native VS Code status-bar integration
* Configurable movement reminders
* Snooze and timer state management
* Streak tracking
* Accessibility-aware UI
* Lightweight notification lifecycle
* Custom extension icon system

Built quickly, released publicly, and continuously improved based on real usage.

**Tech:** TypeScript, VS Code Extension API

---

## 🛍️ Craft & Cheer — Production E-Commerce Platform

A full-stack commerce platform built for a real small business to replace manual product and ordering workflows.

### Highlights

* Product and inventory management
* Secure payment processing
* Order lifecycle management
* Customer management
* Responsive storefront
* Mobile-focused purchasing experience
* Production deployment

**Tech:** React, TypeScript, Tailwind, Stripe, Supabase, PostgreSQL

---

# 🧰 Core Technologies

### Languages

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript)
![Python](https://img.shields.io/badge/Python-3670A0?logo=python)
![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus)
![Rust](https://img.shields.io/badge/Rust-000000?logo=rust)
![Go](https://img.shields.io/badge/Go-00ADD8?logo=go)
![SQL](https://img.shields.io/badge/SQL-336791?logo=postgresql)
![Lua](https://img.shields.io/badge/Lua-2C2D72?logo=lua)

---

### AI / ML

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch)
![Python](https://img.shields.io/badge/Python_ML-3776AB?logo=python)
![Local AI](https://img.shields.io/badge/Local-AI-14041E)
![LoRA](https://img.shields.io/badge/Parameter_Efficient-LoRA-5B1A68)
![llama.cpp](https://img.shields.io/badge/Inference-llama.cpp-000000)

**Focus:** local inference, parameter-efficient training, model lifecycle infrastructure, benchmarking, hardware-aware execution

---

### Frontend & Desktop

![React](https://img.shields.io/badge/React-20232A?logo=react)
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=next.js)
![Electron](https://img.shields.io/badge/Electron-47848F?logo=electron)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?logo=tailwindcss)
![Figma](https://img.shields.io/badge/Figma-000000?logo=figma)

---

### Backend & Infrastructure

![Node.js](https://img.shields.io/badge/Node.js-43853D?logo=node.js)
![Express](https://img.shields.io/badge/Express-000000?logo=express)
![AWS](https://img.shields.io/badge/AWS-FF9900?logo=amazonaws)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?logo=supabase)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?logo=postgresql)
![PM2](https://img.shields.io/badge/PM2-2B037A?logo=pm2)

---

### Systems & Graphics

![WebGPU](https://img.shields.io/badge/WebGPU-Graphics-005A9C)
![CMake](https://img.shields.io/badge/CMake-064F8C?logo=cmake)
![Deterministic Systems](https://img.shields.io/badge/Deterministic-Systems-14041E)
![Replay Systems](https://img.shields.io/badge/Replayable-Execution-5B1A68)
![Distributed Systems](https://img.shields.io/badge/Distributed-Systems-2A0B3D)

---

# ⚡ Engineering Philosophy

* Build systems that solve real problems
* Understand the architecture, not just the interface
* Treat determinism and observability as engineering tools
* Design explicit lifecycle boundaries
* Measure before optimizing
* Keep user workflows simple even when the underlying system is complex
* Build for failure, recovery, and reproducibility
* Own systems end-to-end
* Ship working software

---

# 🔬 Current Areas of Focus

I'm currently exploring and building around:

**Local AI & ML Infrastructure**
Training, inference, resident lifecycle management, learned-state persistence, and hardware-aware execution.

**Deterministic Compute**
Replayable execution, distributed scheduling, deterministic runtimes, and reproducible system behavior.

**GPU-Aware Systems**
Device discovery, capability negotiation, readiness lifecycles, execution selection, and WebGPU.

**Developer Platforms**
Tools and abstractions that make complex systems easier to operate, debug, and extend.

**Production Software**
Building practical applications around real operational workflows rather than isolated technical demos.

---

# 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats-sigma-five.vercel.app/api?username=CoollifeCLC&show_icons=true&theme=dark&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-readme-stats-sigma-five.vercel.app/api/top-langs/?username=CoollifeCLC&layout=compact&theme=dark" />
</p>

---

# 🌐 Connect

<p align="center">
<a href="https://linkedin.com/in/cxrbon">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin" />
</a>

<a href="https://github.com/CoollifeCLC">
<img src="https://img.shields.io/badge/GitHub-000000?logo=github" />
</a>
</p>

---

<p align="center">
<i>"Build useful things."</i>
</p>
