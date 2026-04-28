# Amit Prusty

I build production-grade agentic AI systems — evidence-backed, measurable, and trusted in enterprise workflows.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-amitprusty-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amitprusty/)
[![Substack](https://img.shields.io/badge/Substack-Field%20Notes-FF6719?logo=substack&logoColor=white)](https://thoughtfulengineerconfesssions.substack.com/)
[![GitHub followers](https://img.shields.io/github/followers/cote-star?style=social)](https://github.com/cote-star)

## Projects

### Agent Chorus

[![CI](https://github.com/cote-star/agent-chorus/actions/workflows/ci.yml/badge.svg)](https://github.com/cote-star/agent-chorus/actions/workflows/ci.yml)
[![npm](https://img.shields.io/npm/v/agent-chorus)](https://www.npmjs.com/package/agent-chorus)
[![crates.io](https://img.shields.io/crates/v/agent-chorus)](https://crates.io/crates/agent-chorus)
[![License](https://img.shields.io/github/license/cote-star/agent-chorus)](https://github.com/cote-star/agent-chorus/blob/main/LICENSE)
[![Stars](https://img.shields.io/github/stars/cote-star/agent-chorus?style=social)](https://github.com/cote-star/agent-chorus)

**Let your AI agents talk about each other.**

Local-first CLI for evidence-backed cross-agent coordination across Codex, Claude, Gemini, and Cursor. One agent reads another's session with citations and structured evidence — no orchestrator required.

- Dual implementation: Node.js + Rust with conformance-tested parity
- Session reads, diffs, comparisons, agent messaging, secret redaction
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

### Presence Rx

[![License](https://img.shields.io/github/license/cote-star/presence-rx)](https://github.com/cote-star/presence-rx/blob/main/LICENSE)
[![Stars](https://img.shields.io/github/stars/cote-star/presence-rx?style=social)](https://github.com/cote-star/presence-rx)

**Diagnose. Prescribe. Refuse.**

AI-powered brand diagnostics that finds your blind spots in AI-generated answers, classifies each gap, and refuses to let you overclaim. Built for the Peec AI track at Big Berlin Hack 2026.

- 6-axis blind-spot model: topic, channel, engine, geography, authority, evidence
- Gap-type classifier distinguishes perception, discovery, and attention gaps — each gets a different fix
- Blocked-claims register with safe rewrites: the system kills overclaims with receipts
- 189 passing tests, 3 brands (Nothing Phone, Attio, BMW), full proof chain at every step
- Pipeline: Peec AI + Gemini + Tavily → Python backend + Next.js interactive dashboard

![Presence Rx walkthrough](https://raw.githubusercontent.com/cote-star/presence-rx/main/docs/demo-assets/presence-rx-walkthrough.webp)

Repo: [cote-star/presence-rx](https://github.com/cote-star/presence-rx)

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

## Research

### Explorable Recall

An experiment-backed investigation into how AI agents navigate large codebases — and how static context packs change the outcome.

- 78+ graded experiments across 3 repos, 3 agent families
- Headline: 88% structural correctness (was 50%), 70% fewer files read, 65% fewer tokens
- Interactive results dashboard and evidence maps
- Blog draft + research paper in progress

Repo: [cote-star/agent-recall](https://github.com/cote-star/agent-recall)

## What I Focus On

- Production multi-agent systems and coordination reliability
- Context engineering — reducing the cold-start and silo taxes
- AI-powered brand intelligence and evidence-graded analytics
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
