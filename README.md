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

---

### 🚀 FleetQ — open source

The core of [FleetQ](https://fleetq.net) is open source (AGPL-3.0): a self-hosted mission control for autonomous multi-agent systems, with every feature exposed over MCP.

| Project | What it is |
|---|---|
| [**agent-fleet-o**](https://github.com/escapeboy/agent-fleet-o) | The FleetQ platform — Laravel, Livewire, MCP server, multi-agent crews |
| [**harbormaster**](https://github.com/FleetQ/harbormaster) | MCP server that routes questions and tasks to any of your projects, locally or over SSH |
| [**fleetq-bridge**](https://github.com/escapeboy/fleetq-bridge) | Connects FleetQ cloud agents to your local LLMs, coding agents and MCP servers (Go) |
| [**plugin-sdk**](https://github.com/FleetQ/plugin-sdk) | Contracts and DTOs for building FleetQ plugins |

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
| [**servanda-protocol**](https://github.com/escapeboy/servanda-protocol) | An open protocol for commitments (draft spec) |

### 📚 Sharing what works

- [**ai-prompts**](https://github.com/escapeboy/ai-prompts) — project-agnostic guides and agents for getting more out of Claude Code
- [**nra-audit-generator**](https://github.com/escapeboy/nra-audit-generator) — NRA orders audit XML generator for Bulgarian e-shops ([OpenCart module](https://github.com/escapeboy/nra-opencart))
- [**claude-limit-notifier**](https://github.com/escapeboy/claude-limit-notifier) — warns you before you hit your Claude subscription's weekly limit; one Python file, stdlib only

### 🧪 Side projects

- [**SlotForge**](https://github.com/escapeboy/casino-builder) — a factory for slot games: a spec goes in, a playable PixiJS game comes out, every claim checked by a script
- [**party-sim**](https://github.com/escapeboy/party-sim) — Bulgarian election simulation with real CIK data and Monte Carlo modeling (Go)
- [**skb-aed**](https://github.com/escapeboy/skb-aed) — national AED defibrillator map; source of [AED Karlovo](https://github.com/escapeboy/aed-karlovo) is open too
- [**servanda**](https://github.com/escapeboy/servanda) — reference implementation of the Servanda protocol

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
