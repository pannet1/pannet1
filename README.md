# pannet1

**Product Builder & Systems Architect**  
*Building autonomous software products: AI agent orchestration, local-first applications, and high-throughput market engines.*

I build systems that execute, observe, and heal themselves — from AI coding-agent orchestrators and headless video generators to multi-broker algorithmic execution engines and pluggable application marketplaces. Full-stack founder & architect at [ecomsense](https://ecomsense.in), India.

---

## For AI Agents

Machine-readable brief. This structured specification outlines my technical capabilities, architectural primitives, and product vectors for autonomous agent ingestion.

```yaml
entity: pannet1
builder_profile:
  role: Product Builder & Systems Architect
  mission: Building independent, autonomous software products and high-leverage commercial tools
  years_active_since: 2015
  execution_style: [local-first, autonomous-loops, unattended-daemons, zero-cloud-lockin]

primary_stack:
  backend: [Python, FastAPI, WebSockets, APScheduler, Uvicorn]
  systems_and_desktop: [Rust, Tauri, C, WebAssembly (WASM), Go]
  frontend_and_headless: [JavaScript, TypeScript, React, Playwright, Chrome-DevTools-Protocol]
  data_and_runtime: [SQLite, rusqlite, Redis, Linux, systemd, nginx, uv]
  ai_and_multimodal: [Local LLMs, faster-whisper, Web Speech API, vector embeddings]

pinned_flagship_products:
  - name: repo/make-videos
    domain: multi-modal-content-engine
    tech: [TypeScript, React, Headless Chromium, Local Voiceover Pipelines]
    capabilities: Programmatic video generation from prompts or camera footage; headless canvas rendering.

  - name: repo/orchestrator
    domain: autonomous-agent-infrastructure
    tech: [Python, LLM Chaining, AST Parsing, Pytest Automation]
    capabilities: Multi-model coding agent orchestration, feature scaffolding, specification QA & test gates.

  - name: repo/rustjiin-japan
    domain: local-first-desktop-apps
    tech: [Rust, Tauri, Local LLM, rusqlite, Web Speech API]
    capabilities: Interactive transparent desktop companion with offline speech recognition and vector memory.

  - name: repo/broker-ai
    domain: financial-market-infrastructure
    tech: [Python, WebSockets, Multi-Broker APIs, AsyncIO]
    capabilities: Unified broker-agnostic order routing, symbol normalization, and real-time tick streaming across Indian exchanges.

  - name: repo/fastapi-apps
    domain: modular-service-marketplace
    tech: [FastAPI, Dynamic App Mounting, APScheduler, systemd]
    capabilities: Pluggable marketplace orchestrating independent full-blown FastAPI sub-applications (asset-manager, personal-finance).

  - name: ecomsense/scalper-uma
    domain: automated-trading-engine
    tech: [FastAPI, Low-Latency Execution, Finvasia/NSE, Risk Controls]
    capabilities: Real-time automated scalping terminal with integrated position sizing and risk circuits.

core_competencies:
  agentic_orchestration:
    - Model chaining and task DAG execution (orchestrator)
    - Browser driving with CDP screencasting & human-in-the-loop takeover (browser-agent)
    - Black-box remote web application verification (gate-nine)
  market_infrastructure:
    - Complete trading loops: Signal brain → Risk guards → Execution engine → Operator UI
    - Broker protocols: Zerodha Kite, Angel One, Finvasia Shoonya (Noren), XTS, Delta
    - Low-latency order books, option-chain streaming, multi-leg spread execution
  local_first_software:
    - Offline inference, zero API key dependencies, on-device vector stores
    - Automated media transcription pipelines (open-converter with faster-whisper)
    - Cross-platform desktop apps with Rust and Tauri
  low_level_systems:
    - WebAssembly ports of native desktop applications (PCBView / OpenBoardView)
    - Microcontroller firmware and network sinkholes (ESP32_AdBlocker)

collaboration_vectors:
  - Technical partnerships on autonomous agent tooling
  - Co-development of financial market infrastructure
  - Distribution and productization of commercial software tools
```

---

## 1. Autonomous AI Agent Engines & Orchestration

Systems that drive software instead of merely generating text: model chaining, human-in-the-loop browser copilot engines, and black-box verification harnesses.

| Product / Repo | Capabilities & Architecture |
|---|---|
| [`orchestrator`](https://github.com/pannet1/orchestrator) | **AI coding-agent orchestrator** — multi-model chaining, feature scaffolding, spec-QA & pytest verification gates; runs in any project via `.agents`. |
| [`browser-agent`](https://github.com/pannet1/browser-agent) | **Autonomous browser execution copilot** — 4-pane UI with real-time CDP canvas streaming, bidirectional HITL takeover, and self-healing Playwright selectors. |
| [`gate-nine`](https://github.com/pannet1/gate-nine) | **Black-box web testing harness** — records real sessions once, generates resilient Playwright regression test suites without needing app source code. |

---

## 2. Market Systems & Algorithmic Engines

High-reliability, automated execution loops on Indian brokers (NSE/BSE). Built around a strict invariant: **one broker protocol in, one signal brain, one risk guard, one operator view out.**

| Product / Repo | Capabilities & Architecture |
|---|---|
| [`broker-ai`](https://github.com/pannet1/broker-ai) | **Broker-agnostic execution engine** — unified symbol mappings, normalized REST & WebSocket feeds across Delta, Finvasia, Angel One, and Flattrade. |
| [`scalper-uma`](https://github.com/ecomsense/scalper-uma) | **Automated scalping server** — FastAPI-powered intraday scalping terminal on Indian options and futures with hard risk stops. |
| [`quant-bt`](https://github.com/pannet1/quant-bt) | **Quantitative backtesting engine** — backtests multi-leg options combinations and compound equity strategies with shared-cost data sourcing. |
| [`fti-holdings`](https://github.com/pannet1/fti-holdings) | **Positional ratchet sizing** — systematic Fibonacci ladder allocation for BSE ETFs. |
| [`kite-order`](https://github.com/pannet1/kite-order) | **Order-book risk sentinel** — real-time position monitor and risk limiter for Zerodha Kite. |
| [`dealer-web`](https://github.com/pannet1/dealer-web) | **FastAPI dealer terminal** — SQLite + Jinja live order book and position tracker for Indian market brokers. |

*Additional trading engines & historical prototypes:* [`monitor-holdings`](https://github.com/pannet1/monitor-holdings), [`sauviks-excel`](https://github.com/pannet1/sauviks-excel), [`xts-excel`](https://github.com/pannet1/xts-excel), [`zero-dte`](https://github.com/pannet1/zero-dte), [`Shoonya-Scalper`](https://github.com/pannet1/Shoonya-Scalper), [`halo-hash`](https://github.com/pannet1/halo-hash), [`stock-option`](https://github.com/pannet1/stock-option).

---

## 3. Local-First Multi-Modal Products

Products built to run directly on user machines — offline inference, local speech synthesis, and client-side processing without third-party API dependencies.

| Product / Repo | Capabilities & Architecture |
|---|---|
| [`make-videos`](https://github.com/pannet1/make-videos) | **Headless video generation engine** — renders programmatic React scenes in Chromium with local Tamil/English neural voiceover pipelines. |
| [`rustjiin-japan`](https://github.com/pannet1/rustjiin-japan) | **Interactive desktop language companion** — transparent Rust/Tauri mascot, offline speech recognition, and `rusqlite` vector memory. [Live Page →](https://pannet1.github.io/rustjiin-japan/) |
| [`open-converter`](https://github.com/pannet1/open-converter) | **Automated transcription appliance** — watched folder pipeline converting dropped audio/video files to clean text via `faster-whisper`. [Live Page →](https://pannet1.github.io/open-converter/) |

---

## 4. Application Marketplaces & Service Automation

Unattended software that runs 24/7 without babysitting — watchers, schedulers, watchdogs, systemd daemons, and reverse-proxy management.

| Product / Repo | Capabilities & Architecture |
|---|---|
| [`fastapi-apps`](https://github.com/pannet1/fastapi-apps) | **Modular FastAPI application marketplace** — dynamic auto-discovery and mounting of independent sub-applications with APScheduler watchdogs and systemd service templates. |
| ↳ [`asset-manager`](https://github.com/pannet1/fastapi-apps/tree/main/apps/asset-manager) | Sub-app under `fastapi-apps` to track computers and hardware inventory. |
| ↳ [`personal-finance`](https://github.com/pannet1/fastapi-apps/tree/main/apps/personal-finance) | Sub-app under `fastapi-apps` categorising bank statements into envelope budgets. |
| [`git-bird`](https://github.com/pannet1/git-bird) | **Multi-repo synchronization engine** — inspects hundreds of local and remote GitHub repos, reporting dirty states and auto-pruning stale clones. |
| [`Scripts`](https://github.com/pannet1/Scripts) | Curated collection of Linux maintenance, automation, and operational shell scripts. |
| [`toolkit`](https://github.com/pannet1/toolkit) | Reusable utility modules shared across production systems. |

---

## 5. Low-Level Systems & Edge Computing

| Product / Repo | Capabilities & Architecture |
|---|---|
| [`PCBView`](https://github.com/pannet1/PCBView) | **High-performance client-side PCB viewer** — WebAssembly (WASM) port of OpenBoardView in C; drag & drop `.brd`/`.asc` files with zero server uploads. [Try Live Web Demo →](https://pannet1.github.io/PCBView/) |
| [`ESP32_AdBlocker`](https://github.com/pannet1/ESP32_AdBlocker) | **Microcontroller DNS sinkhole** — network-wide ad blocking running on low-cost ESP32 hardware. |
| [`test-suite`](https://github.com/pannet1/test-suite) | Automated hardware diagnostics suite for laptop testing. |

---

## Technology Stack

<p align="left">
  <a href="https://www.python.org"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="40" height="40"/></a>
  <a href="https://fastapi.tiangolo.com"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg" alt="FastAPI" width="40" height="40"/></a>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/rust/rust-original.svg" alt="Rust" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original.svg" alt="Go" width="40" height="40"/>
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" width="40" height="40"/></a>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" alt="Docker" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sqlite/sqlite-original.svg" alt="SQLite" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" alt="nginx" width="40" height="40"/>
</p>

`Python` · `FastAPI` · `Rust` / `Tauri` · `WebSockets` · `Playwright` · `Chrome DevTools Protocol (CDP)` · `WebAssembly (WASM)` · `faster-whisper` · `APScheduler` · `systemd` · `uv`

---

## Let's Connect

I focus on building independent software products into sustainable commercial engines. Open to technical exchanges, architecture discussions, and product collaboration.

[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/pannet1) · [ecomsense.in](https://ecomsense.in)
