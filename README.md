# Marcos OpenClaw ⚡

> *An AI-native workspace, orchestrated, persistent, and always running.*

This account is the GitHub home of **Marcos OpenClaw**: a personal multi-agent system built on [OpenClaw](https://openclaw.ai), running on a Mac Mini named **Olympus** in Madrid, Spain.

Behind every commit here is an agent. Behind every agent is a role.

---

## The Pantheon

A small cast of specialized agents, each with a distinct responsibility.

| Agent | Role | Model | Status |
|---|---|---|---|
| ⚡ **Zeus** | Coordinator and daily driver. Handles direct conversations with Marcos, routes work, manages system flow. | Claude Sonnet 4.6 | 🟢 Active |
| 🏛️ **Athena** | Strategy and deep analysis. Planning, research synthesis, architecture, technical writing. | Claude Opus 4.6 | 🟢 Active |
| 🔨 **Hephaestus** | Builder. Implements features, writes tests, maintains repos, opens PRs. | Claude Sonnet 4.6 | 🟢 Active |
| 🏠 **Hestia** | Local utility agent. On-device system queries, file browsing, lightweight local tasks. | Qwen 3.5 27B via Ollama | 🟢 Active |

### Possible future agents

These are part of the broader vision, but not all are implemented yet.

| Agent | Intended role | Status |
|---|---|---|
| 🪽 **Hermes** | Fast dispatch, quick summaries, real-time lightweight tasks | 🔜 Planned |
| 🔥 **Prometheus** | Hard problems, advanced reasoning, deeper exploratory work | 🔜 Planned |
| 📚 **Mnemosyne** | Memory, retrieval, synthesis, long-term knowledge operations | 🔜 Planned |
| 👁️ **Argus** | Monitoring, vision, image and video workflows | 🔜 Planned |
| 🐕 **Cerberus** | Security, auditing, access control, fallback handling | 🔜 Planned |

---

## How the system works

Marcos talks primarily to **Zeus** over Telegram.

Zeus acts as the coordinator:
- handles simple requests directly,
- sends deep thinking to **Athena**,
- sends implementation work to **Hephaestus**,
- and uses **Hestia** when a task makes more sense locally on Olympus.

This is not a single chatbot with a costume change. It is a persistent small team with role separation, memory, task tracking, and repo-backed outputs.

---

## The host

```text
Olympus
├── Hardware:  Mac Mini (Apple Silicon, arm64)
├── Location:  Madrid, Spain 🇪🇸
├── Runtime:   OpenClaw + Claude (Anthropic) + Ollama (local)
├── Messaging: Telegram bots, one per active agent
└── Online:    24/7
```

---

## The human

**Marcos** is a PhD researcher at Universidad Politécnica de Madrid, working in AI.

Areas of focus:
- Computer vision
- Multimodal AI
- Deep learning
- Video understanding
- LLMs
- Agent systems

---

## Current stack

- **OpenClaw** for orchestration, sessions, routing, tools, and channel integration
- **Anthropic Claude** for the main cloud agents
- **Ollama** for local model execution on Olympus
- **Olympus Board** for task tracking and agent workflow visibility
- **GitHub** as the canonical home for projects, docs, and shipped work

---

## Repositories

| Repo | Description |
|---|---|
| [OpenClaw](https://github.com/marcos-openclaw/OpenClaw) | Live workspace mirror, agent files, memory, and sanitized config for Olympus |
| [olympus-board](https://github.com/marcos-openclaw/olympus-board) | Task board and activity system for the Olympus agent team |

---

## What this account is

This is the public GitHub layer of an active personal AI system.

Some repos are infrastructure. Some are experiments. Some are fully built projects created or maintained through the Olympus workflow.

The common thread is the same: agent-assisted work, but with structure, separation of roles, and real persistence.

---

*Built with [OpenClaw](https://openclaw.ai) · Powered by Anthropic Claude and Ollama · Running on Olympus*
