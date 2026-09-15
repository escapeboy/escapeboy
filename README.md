### Hi, I'm Nikola 👋

Software engineer from Karlovo, Bulgaria. Long-time PHP/Laravel developer, and these days mostly **infrastructure for AI agents**: orchestration, durable memory, code intelligence, governance and audit trails.

The thread running through my recent work: agents should be **inspectable** — you should be able to see what they did, `git diff` what they remember, and stop a consequential action before it happens.

---

### 🚀 FleetQ — AI agent orchestration

**[FleetQ](https://fleetq.net)** is a self-hosted mission control for autonomous multi-agent systems — visual DAG workflows, human-in-the-loop approvals, budget controls, and every feature exposed over MCP. Open source (AGPL-3.0), with a managed cloud at [fleetq.net](https://fleetq.net).

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

---

**Stack:** PHP · Laravel · Livewire · Rust · Kotlin · Swift · TypeScript · Python · Go · PostgreSQL · Docker · MCP

**Also:** [PriceX](https://pricex.app) · [KarlovoTech](https://github.com/KarlovoTech) · [LaraMod](https://github.com/LaraModulus) (archived)
