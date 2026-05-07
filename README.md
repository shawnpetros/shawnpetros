# Hey, I'm Shawn 👋

**Builder · TypeScript · Python · Rust · AI tooling · MCP**

> Master Builder. Making tools that think.

Cofounder at [Avistar AI](https://avistar.ai). We ship [Astrolayb](https://astrolayb.com), the non-human-identity (NHI) scanner that gives MSPs an auditor-ready inventory of every service account, IAM role, and access key across their clients' AWS / Azure / GCP estates. Wildcard policies, orphaned keys, externally-trusted roles without MFA, mapped to CMMC / HIPAA / SOC 2 / CIS / NIST CSF evidence.

On the side I run [Petros Industries](https://petrosindustries.com), an AI tooling + automation shop for SMBs. 15 years shipping to production; the last few hijacked by agent-native infrastructure.

[shawnpetros.com](https://shawnpetros.com) · [petrosindustries.com](https://petrosindustries.com) · [LinkedIn](https://www.linkedin.com/in/spetros)

## 🚀 What I ship

- **Agent-driven build harnesses.** Linear-polling daemons that dispatch Claude / Codex agents per issue, with adversarial pre-PR review. Rust where latency matters, TypeScript where the LLM does the work.
- **Spec-driven workflow layers.** PRDs that translate directly into harness queues. The agent runs the build; the human shapes the spec.
- **MCP servers + CLI tools designed for LLM consumption.** Memory, retrieval, observability, integration glue. Deterministic, audit-friendly.
- **Production AI for SMBs.** Voice bots, content pipelines, workflow automation. The operations layer the buyer can't afford to hire for.

## 🏆 Highlighted work

**Harness family.** Agent-driven build tooling, each piece scoped to a different posture:

- **Smithy + Anvil** - Reimagined [OpenAI Symphony](https://github.com/openai/symphony) as a Rust daemon. Polls Linear, dispatches one worker per issue, supports both Claude Code AND Codex agents and swaps between them by issue state. Anvil bolts on a new `Adversarial Review` Linear state between `In Progress` and `Human Review` for cross-model audit before any PR lands in front of a human.
- **Whetstone** - Rust executor for wave-protocol runs. Disposable `claude -p` + state.json + commit-on-waves. In production; drives POCaaS and a multi-wave advisory site rollout.
- **[Salazar](https://github.com/shawnpetros/salazar)** - Autonomous coding orchestrator on the Claude Agent SDK. Planner / generator / evaluator loop with hard validator gates (tsc, eslint, build, test).

**Tooling + infra.**

- **[Lithium](https://github.com/shawnpetros/lithium)** - Cross-provider LLM-spend aggregator (Anthropic / OpenAI / OpenRouter). Local Rust daemon, SQLite-backed, multiple UI surfaces (CLI, status line, menubar, harness hooks). Mood stabilizer for your AI bill.
- **[QMD Recall](https://github.com/shawnpetros/qmd-recall)** - Deterministic memory recall plugin for OpenClaw. Replaces brittle agent-driven RAG with cited, indexed retrieval. No 20-second pre-answer séance.
- **[deAIify](https://github.com/shawnpetros/deaiify)** - OpenClaw plugin. Strips em-dashes from assistant prose by re-writing the surrounding sentence; fails open if the rewrite breaks.
- **[Claude Context](https://github.com/shawnpetros/claude-context)** - Code search MCP for Claude Code. Makes the entire codebase the context for any coding agent.
- **[Claude Skills](https://github.com/shawnpetros/claude-skills)** - Opinionated skills that earn their keep. Process skills, anti-slop voice rules, build-in-public scaffolding.
- **[GAAI Framework](https://github.com/shawnpetros/GAAI-framework)** - Drop `.gaai/` into any project; Discovery defines what to build, Delivery runs until criteria pass. Markdown + YAML + bash. Claude Code / Codex CLI / Gemini CLI / Cursor compatible.

**Shipped + building.**

- **POCaaS** - Building. Concept-to-shareable-landing-page generator powered by Whetstone. Describe a product, get a spec, get a barebones POC URL you can send stakeholders to validate intent before committing to the full build.
- **[mediascribe](https://github.com/shawnpetros/mediascribe)** - TUI for transcribing, translating, analyzing audio / video. On [PyPI](https://pypi.org/project/mediascribe/) and [Homebrew](https://github.com/shawnpetros/homebrew-mediascribe).
- **[WindWatts](https://windwatts.nlr.gov)** - Open-source wind energy assessment for the National Lab of the Rockies. React + TypeScript + FastAPI. [25 PRs merged](https://github.com/NatLabRockies/windwatts/pulls?q=is%3Apr+author%3Ashawnpetros).
- **[PennyBot](https://github.com/shawnpetros/pennybot)** - Voice bot that joins your Zoom call and speaks. Recall.ai + OpenAI Realtime, built in an evening. MIT.
- **[ShinyOps](https://pokemon-shiny-guide.vercel.app)** - Shiny-hunting planner for Pokémon Legends: Z-A + Scarlet/Violet. Search-first target picker, ranked methods, deep planners for ZA donuts and SV sandwiches. ([code](https://github.com/shawnpetros/pokemon-shiny-guide))
- **[claude-code-clone](https://github.com/shawnpetros/claude-code-clone)** - Minimal Claude Code clone built from scratch. 42 features, zero hand-written code, three agent sessions. The agentic loop is just `send → detect → execute → feed back → repeat`.

## 🤔 What I actually care about

Spec-driven development. Tight feedback loops. Real eval suites instead of vibes. CLI tools designed for LLM consumption, not human ergonomics. The unglamorous plumbing that makes agents trustworthy at scale.

## 🛠 Tech

![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-191919?style=flat&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-7C3AED?style=flat)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Linear](https://img.shields.io/badge/Linear-5E6AD2?style=flat&logo=linear&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000?style=flat&logo=next.js&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonwebservices&logoColor=white)

## 📫 Connect

[![Website](https://img.shields.io/badge/shawnpetros.com-000?style=for-the-badge&logo=safari&logoColor=white)](https://shawnpetros.com)
[![Petros Industries](https://img.shields.io/badge/petrosindustries.com-7C3AED?style=for-the-badge&logo=safari&logoColor=white)](https://petrosindustries.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/spetros)

---

📍 Los Angeles · cofounder @ [Avistar AI](https://avistar.ai) · running [Petros Industries](https://petrosindustries.com) · currently building POCaaS and Avistar's agent-native workflow layer in the open.
