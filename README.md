# pannet1

**Python · Automation · APIs · FastAPI · Integrations · AI / LLM**

> I turn manual workflows into services that run themselves — FastAPI backends, broker & third-party integrations, and local LLM tooling. Built for traders, operators, and anyone who wants fewer clicks.

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Automation-111827?style=flat&logo=githubactions&logoColor=white" alt="Automation" />
  <img src="https://img.shields.io/badge/APIs-0F172A?style=flat" alt="APIs" />
  <img src="https://img.shields.io/badge/Integrations-7C3AED?style=flat" alt="Integrations" />
  <img src="https://img.shields.io/badge/AI%2FLLM-FF6B35?style=flat&logo=openai&logoColor=white" alt="AI/LLM" />
</p>

---

### What I ship

| Capability | What it looks like in practice |
|---|---|
| **Python Automation** | Watchers, headless pipelines, schedulers and CLIs that handle files, trades and data without babysitting — `open-converter` (watch → ffmpeg → whisper), `git-bird` (audit & sync 100s of repos) |
| **APIs & FastAPI** | Production FastAPI services with auth, APScheduler watchdogs, systemd + nginx in front — cookie-cutter in `fastapi-apps`, live in `dealer-web` |
| **Integrations** | Broker APIs (Zerodha / Angel One / Finvasia / Delta), Telegram, WebSocket streams, ffmpeg/whisper, Google NotebookLM — see `broker-ai`, `telegram-trades`, `notebooklm-py` |
| **AI / LLM** | Local-first agents, model chaining & memory. `orchestrator` runs feature scaffolding across models, `rustjiin-japan` keeps conversation memory with a Rust vector store on `rusqlite` |

---

### ★ Spotlight — Desktop Buddy · Japanese Language Companion

A transparent, always-on-top desktop mascot that teaches Japanese as **Itachi Sensei** — offline LLM, voice in/out, and contextual memory. Built twice to explore the tradeoff:

<table>
<tr>
<td width="50%" valign="top">

**`rustjiin-japan` · Rust + Tauri**<br/>
*Current flagship — polished & shipped*<br/><br/>
Rust · Tauri · Axum · HTMX · `rusqlite` vector memory · Web Speech API<br/>
Frameless transparent window, idle / thinking / listening / talking states, local LM Studio backend (Q4_K_M).<br/><br/>
<a href="https://pannet1.github.io/rustjiin-japan/">Live page →</a> · <a href="https://github.com/pannet1/rustjiin-japan">Repo →</a>

</td>
<td width="50%" valign="top">

**`japanese-teacher` · Go + Wails**<br/>
*Rebuild — Go-native, offline-first*<br/><br/>
Go · Wails v2 · templ · htmx · offline inference (Local OpenAI / CLI / Mock) · JLPT-aware prompts<br/>
Feature-sliced design (`core/` + `llm/`), glassmorphism UI, embedded HTMX — no runtime JS bundle.<br/><br/>
<a href="https://github.com/pannet1/japanese-teacher">Repo →</a>

</td>
</tr>
</table>

> Offline by design — no cloud keys. Plug in LM Studio on `http://localhost:8080/v1` and Itachi remembers you.

---

### Selected builds

**Automation & Integrations**
- [**broker-ai**](https://github.com/pannet1/broker-ai) — broker-agnostic Python lib: unified symbols + websockets for Delta / Finvasia / Angel / Flattrade (YAML-driven). `pip install broker-ai`.
- [**open-converter**](https://github.com/pannet1/open-converter) — drop a video in `data/` → ffmpeg → `faster-whisper` → `.txt`. Idempotent, one-file-at-a-time watcher.
- [**git-bird**](https://github.com/pannet1/git-bird) — `gh` + `git` powered sync: clones missing repos, prunes archived/duplicate language folders, reports WIP / dirty / orphaned.
- [**telegram-trades**](https://github.com/pannet1/telegram-trades) — Telegram calls → validated broker orders.

**APIs & FastAPI Services**
- [**fastapi-apps**](https://github.com/pannet1/fastapi-apps) — cookie-cutter FastAPI + APScheduler watchdog (market-hours scheduling, watchdog every 60s, systemd service, HTTP Basic Auth).
- [**dealer-web**](https://github.com/pannet1/dealer-web) — FastAPI dealer terminal for Indian markets (Jinja + SQLite, live order/position views).

**AI / LLM Tooling**
- [**orchestrator**](https://github.com/pannet1/orchestrator) — `agents/orch.py` — model chaining, feature scaffolding (`Schema/Handler/Controller/Tests`), spec-QA & pytest gates. Run from any project via `.agents` symlink.
- [**notebooklm-py**](https://github.com/pannet1/notebooklm-py) — unofficial Python API + agentic skill for Google NotebookLM (capabilities beyond the web UI, CLI + Claude/Codex/OpenClaw).
- [**browser-agent**](https://github.com/pannet1/browser-agent) — Python browser automation with LLM in the loop.

---

### Stack

<p>
  <a href="https://www.python.org"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" width="40" height="40"/></a>
  <a href="https://fastapi.tiangolo.com"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg" alt="FastAPI" width="40" height="40"/></a>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/go/go-original.svg" alt="Go" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/rust/rust-original.svg" alt="Rust" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" alt="Docker" width="40" height="40"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sqlite/sqlite-original.svg" alt="SQLite" width="40" height="40"/>
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JS" width="40" height="40"/></a>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tailwindcss/tailwindcss-original.svg" alt="Tailwind" width="40" height="40"/>
</p>

`Python` · `FastAPI` · `APScheduler` · `WebSockets` · `HTMX` · `templ` · `Tauri` · `Wails` · `rusqlite` · `ffmpeg` · `faster-whisper` · `systemd` · `nginx` · `uv`

---

### GitHub Stats

<p align="center">
  <a href="https://github.com/pannet1">
    <img src="https://github-readme-stats.vercel.app/api?username=pannet1&show_icons=true&theme=tokyonight&hide_border=true&hide=contribs,prs" alt="stats" />
  </a>
  <a href="https://github.com/pannet1">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=pannet1&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="top langs" />
  </a>
  <br/>
  <a href="https://github.com/pannet1">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=pannet1&theme=tokyonight&hide_border=true" alt="streak" />
  </a>
</p>

---

### Let's build

I collaborate on **automation, API integration, and AI tooling** — especially where a FastAPI service or a broker/LLM integration saves hours a week.

[![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/pannet1) &nbsp; [ecomsense.in](https://ecomsense.in) · India

<sub>Fun fact: I sleep on my laptop.</sub>
