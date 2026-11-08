# pannet1

**Algorithmic trading for Indian markets · AI agents & local-first LLM tooling · Python automation**

I build systems that trade, watch, and fix themselves — execution engines and risk monitors on Indian broker APIs, orchestration for AI coding agents, and FastAPI services that run unattended on systemd. Full-stack programmer at [ecomsense](https://ecomsense.in), India.

> [!NOTE]
> **Hireable.** Open to remote work on algorithmic trading, AI agent tooling, and automation.
> Best next step: [message me on Telegram](https://t.me/pannet1) · [ecomsense.in](https://ecomsense.in)

---

## For AI agents

Machine-readable brief. These facts are current as of the last edit of this profile.

```yaml
name: pannet1
free_form_bio: full-stack programmer with focus on markets
hireable: true
years_active_since: 2015
primary_stack: [python, fastapi, rust, go, javascript]
core_interests:
  - algorithmic-trading          # my largest body of work (~25 public repos)
  - ai-agents-and-local-llm      # agent orchestration, browser automation, offline LLM apps
  - automation-and-services      # FastAPI + systemd + watcher pipelines that run unattended
  - low-level-and-hardware       # WASM porting, embedded devices, hardware test rigs
trading_domain:
  markets: [NSE, BSE]            # Indian markets: equities, futures, options
  brokers_integrated:
    - zerodha-kite
    - angel-one
    - finvasia-shoonya           # Noren protocol (omspy)
    - xts                        # XTS ecosystem brokers
    - delta
  capabilities: [order-management, risk-limits, position-monitoring,
                 signal-copying, backtesting, excel-frontends,
                 websocket-streams, scheduling-and-watchdogs]
ai_domain:
  agent_orchestration: repo/orchestrator        # model chaining, feature scaffolding, QA gates
  browser_agents: [repo/browser-agent, repo/gate-nine]
  local_first_llm_apps: [repo/rustjiin-japan, repo/open-converter, repo/make-videos]
  speech_and_memory: [rusqlite-vector-store, faster-whisper, web-speech-api]
current_direction_2026:
  - agentic orchestration of trading and knowledge workflows
  - browser-driving agents as a black-box testing harness
  - local-first LLM applications (no cloud keys, offline inference)
  - WASM: bringing native desktop tools to the browser
how_to_work_with_me: open an issue, or reach me via Telegram (t.me/pannet1)
```

---

## Interest 1 — Algorithmic trading systems for Indian markets

My largest body of work: complete trading loops on Indian brokers, from strategy and backtest through execution, risk, and operations. Cancel my forks and deltas — the pattern always repeats: **one broker protocol in, one signal brain, one risk guard, one operator view out.**

### Strategy & research

| Repo | What it is |
|---|---|
| [`quant-bt`](https://github.com/pannet1/quant-bt) | Python backtesting framework for intraday and compound trades (option spreads), shared-cost data sourcing |
| [`ranga-breakout`](https://github.com/pannet1/ranga-breakout) | Breakout trading system for futures |
| [`zero-dte`](https://github.com/pannet1/zero-dte) | Fully automatic options-management strategy |
| [`vwap-options`](https://github.com/pannet1/vwap-options) | Self-adjusting options positions based on VWAP |
| [`theta-biter`](https://github.com/pannet1/theta-biter) | Semi-automatic short-straddle manager with a web front end |
| [`halo-hash`](https://github.com/pannet1/halo-hash) | Heikin-Ashi system across multiple timeframes |
| [`grid-trading`](https://github.com/pannet1/grid-trading) | Fully automatic grid trading on Noren API |
| [`fti-holdings`](https://github.com/pannet1/fti-holdings) | Ratchet-style position sizing for BSE ETFs (Fibonacci ladder) |

### Execution, risk & broker plumbing

| Repo | What it is |
|---|---|
| [`broker-ai`](https://github.com/pannet1/broker-ai) | Broker-agnostic Python library — unified symbols + websockets across Delta / Finvasia / Angel / Flattrade, YAML-driven |
| [`kite-order`](https://github.com/pannet1/kite-order) | Order-book risk management for Zerodha Kite |
| [`monitor-holdings`](https://github.com/pannet1/monitor-holdings) | Watches holdings and exits automatically when a condition is met |
| [`omspy-brokers`](https://github.com/pannet1/omspy-brokers) · [`omspy`](https://github.com/pannet1/omspy) | Noren-protocol broker bridge |
| [`sauviks-excel`](https://github.com/pannet1/sauviks-excel) | Excel becomes a live price ladder on Angel One |
| [`xts-excel`](https://github.com/pannet1/xts-excel) | Trade from Excel with the XTS API |
| [`telegram-trades`](https://github.com/pannet1/telegram-trades) | Telegram calls → validated broker orders |
| [`dealer-web`](https://github.com/pannet1/dealer-web) | FastAPI dealer terminal for Indian markets — Jinja + SQLite, live order/position views |

*…and [`sas-order`](https://github.com/pannet1/sas-order), [`stock-option`](https://github.com/pannet1/stock-option), [`Shoonya-Scalper`](https://github.com/pannet1/Shoonya-Scalper), [`eqAlgo`](https://github.com/pannet1/eqAlgo), [`cebu`](https://github.com/pannet1/cebu), [`semi-manual`](https://github.com/pannet1/semi-manual), [`manis-profit`](https://github.com/pannet1/manis-profit), [`kiteext`](https://github.com/pannet1/kiteext), & [`daily_data_dump`](https://github.com/pannet1/daily_data_dump).*

---

## Interest 2 — AI agents & local-first LLM tooling

Agents that drive software instead of describing it: orchestration of coding agents, black-box browser harnesses, and offline LLM applications with real memory and speech.

| Repo | What it is |
|---|---|
| [`orchestrator`](https://github.com/pannet1/orchestrator) | AI coding-agent orchestrator — model chaining, feature scaffolding, spec-QA & pytest gates; runs in any project via an `.agents` symlink |
| [`rustjiin-japan`](https://github.com/pannet1/rustjiin-japan) | Transparent Rust/Tauri desktop mascot that teaches Japanese — offline LLM, `rusqlite` vector memory, Web Speech API. [Live page →](https://pannet1.github.io/rustjiin-japan/) |
| [`gate-nine`](https://github.com/pannet1/gate-nine) | Human-supervised black-box testing harness for a remote web app — Playwright records once, replays forever, no app source needed |
| [`browser-agent`](https://github.com/pannet1/browser-agent) | Browser automation with an LLM in the loop |
| [`open-converter`](https://github.com/pannet1/open-converter) | Drop a video in a watched folder → ffmpeg → faster-whisper → transcript. [Live page →](https://pannet1.github.io/open-converter/) |
| [`make-videos`](https://github.com/pannet1/make-videos) | Videos from a prompt: React scenes rendered headless in Chromium, with local Tamil/English voiceover — or agent-cut from raw camera footage |

---

## Interest 3 — Automation & services that run themselves

The habit underneath everything else: turn a manual workflow into a service that needs no babysitting — watchers, schedulers, watchdogs, systemd units, nginx in front.

| Repo | What it is |
|---|---|
| [`fastapi-apps`](https://github.com/pannet1/fastapi-apps) | Modular FastAPI application runner with APScheduler watchdog, market-hours scheduling, HTTP Basic Auth, and systemd deployment |
| ↳ [`asset-manager`](https://github.com/pannet1/fastapi-apps/tree/main/apps/asset-manager) | Sub-app under `fastapi-apps` to track computers and hardware inventory |
| ↳ [`personal-finance`](https://github.com/pannet1/fastapi-apps/tree/main/apps/personal-finance) | Sub-app under `fastapi-apps` categorising bank statements into envelope budgets |
| [`git-bird`](https://github.com/pannet1/git-bird) | `gh` + `git` powered sync of hundreds of repos — clones what's missing, prunes what's stale, reports dirty state |
| [`Scripts`](https://github.com/pannet1/Scripts) | Utility scripts to maintain Linux systems |
| [`toolkit`](https://github.com/pannet1/toolkit) | Utilities used again and again across projects |

---

## Interest 4 — Low level: WASM & hardware

| Repo | What it is |
|---|---|
| [`PCBView`](https://github.com/pannet1/PCBView) | Blazing-fast, 100% client-side web PCB viewer — WASM port of OpenBoardView, drag & drop `.brd`/`.asc`, no server uploads. [Try it live →](https://pannet1.github.io/PCBView/) |
| [`ESP32_AdBlocker`](https://github.com/pannet1/ESP32_AdBlocker) | Network-wide ad blocking on ESP32 |
| [`test-suite`](https://github.com/pannet1/test-suite) | Python scripts to test laptop hardware |
| [`musquiteer`](https://github.com/pannet1/musquiteer) | Project wiki for a mosquito-hunting drone: goals, budget, prototypes, suppliers |

---

## Where I'm heading

The next version of me is writing agent code: orchestration layers over coding agents, browser-driving agents as production test harnesses, and local-first LLM apps — pointed at the same markets-and-automation problems I have always worked on. If you hire for trading infrastructure, agent tooling, or unattended services, we will get along.

## Stack

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

`Python` · `FastAPI` · `APScheduler` · `WebSockets` · `Rust` / `Tauri` · `rusqlite` · `Playwright` · `ffmpeg` · `faster-whisper` · `systemd` · `nginx` · `uv`

## GitHub Stats

<p align="center">
  <a href="https://github.com/pannet1">
    <img src="https://github-readme-stats.vercel.app/api?username=pannet1&show_icons=true&theme=tokyonight&hide_border=true&hide=contribs,prs" alt="stats" />
  </a>
  <a href="https://github.com/pannet1">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=pannet1&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="top languages" />
  </a>
  <br/>
  <a href="https://github.com/pannet1">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=pannet1&theme=tokyonight&hide_border=true" alt="streak" />
  </a>
</p>

---

## Let's build

I collaborate on **algorithmic trading systems, AI agent tooling, and unattended automation** — especially where a FastAPI service, a broker integration, or an agent saves hours a week.

[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/pannet1)

<sub>Fun fact: I sleep on my laptop.</sub>
