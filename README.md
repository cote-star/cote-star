# Amit Prusty

I build production-grade agentic AI systems — evidence-backed, measurable, and trusted in enterprise workflows.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-amitprusty-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amitprusty/)
[![Substack](https://img.shields.io/badge/Substack-Field%20Notes-FF6719?logo=substack&logoColor=white)](https://thoughtfulengineerconfesssions.substack.com/)
[![GitHub followers](https://img.shields.io/github/followers/cote-star?style=social)](https://github.com/cote-star)

## Projects

### Agent Chorus

[![CI](https://github.com/cote-star/agent-chorus/actions/workflows/ci.yml/badge.svg)](https://github.com/cote-star/agent-chorus/actions/workflows/ci.yml)
[![Version](https://img.shields.io/badge/version-0.8.0-green.svg)](https://github.com/cote-star/agent-chorus/releases)
[![License](https://img.shields.io/github/license/cote-star/agent-chorus)](https://github.com/cote-star/agent-chorus/blob/main/LICENSE)
[![Stars](https://img.shields.io/github/stars/cote-star/agent-chorus?style=social)](https://github.com/cote-star/agent-chorus)

**Let your AI agents talk about each other.**

Local-first CLI for evidence-backed cross-agent coordination across Codex, Claude, Gemini, and Cursor. One agent reads another's session with citations and structured evidence — no orchestrator required.

- Dual implementation: Node.js + Rust with identical conformance tests
- Session reads, diffing, comparisons, agent-to-agent messaging, secret redaction
- Context Pack: 5-doc agent-first repo briefing that eliminates cold-start re-reads
- Zero npm prod dependencies, works offline, nothing leaves your machine

![Before/after workflow](https://raw.githubusercontent.com/cote-star/agent-chorus/main/docs/silo-tax-before-after.webp)

![Handoff demo](https://raw.githubusercontent.com/cote-star/agent-chorus/main/docs/demo-handoff.webp)

| | agent-chorus | CrewAI / AutoGen | ccswarm / claude-squad |
| :--- | :---: | :---: | :---: |
| **Approach** | Read-only evidence layer | Full orchestration framework | Parallel agent spawning |
| **Agents** | Codex, Claude, Gemini, Cursor | Provider-specific | Usually Claude-only |
| **Dependencies** | Zero npm prod deps | Heavy Python/TS stack | Moderate |
| **Cold-start solution** | Context Pack | None | None |

Repo: [cote-star/agent-chorus](https://github.com/cote-star/agent-chorus)

### latchkeyd

[![CI](https://github.com/cote-star/latchkeyd/actions/workflows/ci.yml/badge.svg)](https://github.com/cote-star/latchkeyd/actions/workflows/ci.yml)
[![Version](https://img.shields.io/badge/version-0.1.0--alpha.3-green.svg)](https://github.com/cote-star/latchkeyd/releases)
[![License](https://img.shields.io/github/license/cote-star/latchkeyd)](https://github.com/cote-star/latchkeyd/blob/main/LICENSE)
[![Stars](https://img.shields.io/github/stars/cote-star/latchkeyd?style=social)](https://github.com/cote-star/latchkeyd)

**Choose the trust posture before a local tool gets credential-backed access.**

macOS-first local trust broker for agent-mediated tool execution. Secrets stay local, wrappers and binaries are trust-pinned, and you choose the trust mode per task.

- Three shipped modes: **handoff** (env injection), **oneshot** (bounded run), **brokered** (per-operation request)
- Swift 6.0, macOS Keychain-backed, JSONL audit trail with enforced preflight
- Fail-closed on drift, hijack, or bypass — defense in depth, not "secure agents solved"

![Trust modes](https://raw.githubusercontent.com/cote-star/latchkeyd/main/docs/assets/hero-before-after-trust-modes.png)

![Execution modes](https://raw.githubusercontent.com/cote-star/latchkeyd/main/docs/assets/diagram-execution-modes.png)

Repo: [cote-star/latchkeyd](https://github.com/cote-star/latchkeyd)

## What I Focus On

- Production multi-agent systems and coordination reliability
- LLM/VLM engineering with research-to-production translation
- Fine-tuning, structured generation, and inference optimization
- LLMOps, evaluation, and governance for enterprise deployment
- Local-first agent security and trust infrastructure

## Writing

Practical field notes on enterprise AI reliability and agent systems:

- [The Silo Tax](https://thoughtfulengineerconfesssions.substack.com/p/the-silo-tax) — why multi-agent workflows break
- [Why Agents Don't Fail Fast](https://thoughtfulengineerconfesssions.substack.com/p/why-agents-dont-fail-fastthey-fail) — they fail slow

More at [Confessions of a Thoughtful Engineer](https://thoughtfulengineerconfesssions.substack.com/)

## Engineering Principles

- Evidence over assumptions
- Reliability over demo polish
- Measurable outcomes over vague AI claims
- Simplicity first; orchestration only when needed

## Connect

- [LinkedIn](https://www.linkedin.com/in/amitprusty/)
- [GitHub](https://github.com/cote-star)
- [Substack](https://thoughtfulengineerconfesssions.substack.com/)
