### Hi, I'm Nikola 👋

Software engineer from Karlovo, Bulgaria. Long-time PHP/Laravel developer, and these days mostly **infrastructure for AI agents**: orchestration, durable memory, code intelligence, governance and audit trails.

The thread running through my recent work: agents should be **inspectable** — you should be able to see what they did, `git diff` what they remember, and stop a consequential action before it happens.

---

### 🛠️ What I'm building

| Product | What it does |
|---|---|
| [**FleetQ**](https://fleetq.net) | Mission control for AI agents — build, run and monitor autonomous multi-agent systems with visual DAG workflows, human-in-the-loop approvals and MCP integrations |
| [**FleetQ Accounting**](https://accounting.fleetq.net) | AI agents for accounting firms — classify documents, suggest ledger entries and track deadlines. OCR, VAT, SAF-T |
| [**Signalio**](https://signalio.app) | Real-time crisis alerts — fires, floods and disasters near you, so you can react in time |
| [**Actio**](https://actio.bg) | SaaS for volunteer organizations in Bulgaria — teams, tasks, events and campaigns in one place |
| [**Eventico**](https://eventico.live) | Event app — live agenda, Q&A, materials and post-event reports. One QR scan, no app to install |
| [**FleetQ Partners**](https://partners.fleetq.net) | Partner program for the whole FleetQ portfolio — promote any product, earn on every attributed sale |
| [**Localz.Events**](https://localz.events) | Discover events and places near you — concerts, meetups, sports and more across Bulgaria |
| [**Kvesta**](https://kvesta.app) | Outdoor escape games on your phone — routes in Karlovo, Plovdiv and anywhere you drop a marker. One ticket per team, no guide, no booking |
| [**Ploshtad**](https://ploshtad.bg) | Municipal decisions in plain language — reads council minutes and sends each person only what affects them |
| [**Diazoma**](https://diazoma.app) | Browse any list on the web as a wall — feeds, catalogs, galleries and archives as a curved, searchable wall, on screen or in a headset. The wall, adapters and spec are open source |
| [**Albion Trade Intelligence**](https://albionintel.com) | Market analysis and trading for Albion Online — live prices across cities, arbitrage, trade routes, backtested strategies and price alerts |
| [**Pravoto**](https://pravoto.app) | Bulgarian and EU law in force, consolidated and free — every act with its amendments applied in one text |
| [**FleetQ Office**](https://office.fleetq.net) | Invoices, expenses snapped with your phone and cash flow — everything reaches your accountant automatically |
| [**Agent Storefront**](https://storefront.fleetq.net) | Turns a business website into a verified profile AI agents can order from — prices, delivery and rules with sources; every request waits for the owner's approval |
| [**Poligon**](https://poligon.fleetq.net) | Attack-tests AI agents against planted attacks in the mail, files and tools they read, and signs the report |
| [**Utro**](https://utro.fleetq.net) | Every morning at 07:00 tells you what needs to happen today — from your calendar, AI sessions, git, mail and chats; raw content stays on your Mac |

---

### 🚀 FleetQ — open source

The core of [FleetQ](https://fleetq.net) is open source (AGPL-3.0): a self-hosted mission control for autonomous multi-agent systems, with every feature exposed over MCP.

| Project | What it is |
|---|---|
| [**agent-fleet-o**](https://github.com/escapeboy/agent-fleet-o) | The FleetQ platform — Laravel, Livewire, MCP server, multi-agent crews |
| [**harbormaster**](https://github.com/FleetQ/harbormaster) | MCP server that routes questions and tasks to any of your projects, locally or over SSH |
| [**fleetq-bridge**](https://github.com/escapeboy/fleetq-bridge) | Connects FleetQ cloud agents to your local LLMs, coding agents and MCP servers (Go) |
| [**plugin-sdk**](https://github.com/FleetQ/plugin-sdk) | Contracts and DTOs for building FleetQ plugins |
| [**website-plugin-\***](https://github.com/FleetQ?q=website-plugin) | Blocks for the FleetQ Website Builder — [core](https://github.com/FleetQ/website-plugin-core), [blog](https://github.com/FleetQ/website-plugin-blog), [forms](https://github.com/FleetQ/website-plugin-forms), [chatbot](https://github.com/FleetQ/website-plugin-chatbot), [e-commerce](https://github.com/FleetQ/website-plugin-ecommerce) (Stripe, Paddle) |

### 🧠 Agent memory & tooling

| Project | What it is |
|---|---|
| [**svod-engine**](https://github.com/FleetQ/svod-engine) | Auditable, git-backed memory for AI agents — memory you can read, diff and restore (Kotlin) |
| [**svod-ui-macos**](https://github.com/FleetQ/svod-ui-macos) | Native SwiftUI client for Svod |
| [**svod-foundry**](https://github.com/FleetQ/svod-foundry) | Lets agents synthesize new tools at runtime, verified in a sandbox and versioned in Svod |
| [**greda**](https://github.com/escapeboy/greda) | Code intelligence engine + MCP server — a local knowledge graph of your codebases (Rust) |

### 🛡️ Governance & determinism

| Project | What it is |
|---|---|
| [**boruna**](https://github.com/escapeboy/boruna) | Deterministic, policy-gated workflow execution with tamper-evident evidence bundles (Rust) |
| [**stozher**](https://github.com/escapeboy/stozher) | Accountability kernel: every agent effect is a signed event under a mandate traceable to a named human |
| [**lattice**](https://github.com/escapeboy/lattice) | Governance browser runtime for agents, firewalled by default |
| [**servanda**](https://github.com/escapeboy/servanda) | An open protocol for commitments — reference implementation; the draft spec lives in [servanda-protocol](https://github.com/escapeboy/servanda-protocol) |

### 📚 Sharing what works

- [**claude-code-kit**](https://github.com/escapeboy/claude-code-kit) — skills, mods, subagents, hooks, slash commands and guides for Claude Code, installable by your agent
- [**nra-audit-generator**](https://github.com/escapeboy/nra-audit-generator) — NRA orders audit XML generator for Bulgarian e-shops ([OpenCart module](https://github.com/escapeboy/nra-opencart))
- [**claude-limit-notifier**](https://github.com/escapeboy/claude-limit-notifier) — warns you before you hit your Claude subscription's weekly limit; one Python file, stdlib only

### 🧪 Side projects

- [**SlotForge**](https://github.com/escapeboy/casino-builder) — a factory for slot games: a spec goes in, a playable PixiJS game comes out, every claim checked by a script
- [**party-sim**](https://github.com/escapeboy/party-sim) — Bulgarian election simulation with real CIK data and Monte Carlo modeling (Go)
- [**skb-aed**](https://github.com/escapeboy/skb-aed) — national AED defibrillator map; source of [AED Karlovo](https://github.com/escapeboy/aed-karlovo) is open too
- [**chirak**](https://github.com/escapeboy/chirak) — an agent that turns a task description and a few examples into a small self-hosted specialist model: eval-first, LoRA on an AMD Instinct GPU, honest stop rules
- [**diazoma**](https://github.com/escapeboy/diazoma) — the open-source wall, adapters and spec behind Diazoma, plus [WordPress](https://github.com/escapeboy/diazoma-wordpress) and [Laravel](https://github.com/escapeboy/diazoma-laravel) plugins

<details>
<summary>🗄️ Older Laravel packages</summary>

- [**jraty**](https://github.com/escapeboy/jraty) — item ratings with optional microdata
- [**borica**](https://github.com/escapeboy/borica) · [**laravel-epay**](https://github.com/escapeboy/laravel-epay) — Bulgarian payment gateways (BORICA, ePay) for Laravel
- [**disqus**](https://github.com/escapeboy/disqus) — Disqus integration for Laravel 4
- [**ZeroController**](https://github.com/escapeboy/ZeroController) — Laravel ZeroController for faster development

</details>

---

**Stack:** PHP · Laravel · Livewire · Rust · Kotlin · Swift · TypeScript · Python · Go · PostgreSQL · Docker · MCP

**Also:** [pricex.app](https://pricex.app) · [KarlovoTech](https://github.com/KarlovoTech) · [LaraMod](https://github.com/LaraModulus) (archived)
