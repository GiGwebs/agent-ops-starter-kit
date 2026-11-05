# Agent-Ops Starter Kit

**Run a one-person software company where AI agents do the work.**

This is the operating system for agent-driven development: the documents that keep agents honest, the scripts that keep you informed, and the workflow that keeps the pipeline running while you sleep. It was extracted from a live setup that runs real OSS bounty work — not a theory PDF.

## Get the kit

**[Buy on Polar — $39](https://buy.polar.sh/polar_cl_d4n2E6i7piZkdAaOWLGXjkZua3hdD8UTNSWG02aYRsv)**

Instant download after checkout. This repository is the product page — the full kit ships as a zip.

**Free sample:** [`samples/AGENTS.md`](samples/AGENTS.md) — one of the six core operating documents, exactly as it ships.

## What's inside

| Path | What it is |
|------|-----------|
| `templates/` | The core documents: `AGENTS.md`, `OPS.md`, `AI_HANDOVER.md`, `DECISIONS.md`, `OPPORTUNITIES.md`, `WORKER_BRIEF.md` — fill in and drop at your repo root |
| `scripts/` | Bash + Python3 comms and pipeline scripts (Telegram, Slack, bounty radar, service installer) |
| `workflows/bounty-radar.yml` | GitHub Actions cron that scans for funded issues daily and opens a report issue |
| `docs/` | `SETUP.md` (checklist), `ARCHITECTURE.md` (how it fits together), `INTEGRATION.md` (wire into an existing repo) |

## The problem it solves

AI coding agents are cheap and fast — and completely amnesiac. Every session starts from zero: no memory of what shipped, what failed, what was decided, or what to do next. This kit is the missing discipline layer:

- **`AGENTS.md`** — the contract your agent reads first. Conventions, guardrails, where things live.
- **`AI_HANDOVER.md`** — verified current state, updated at closeout. The next session starts where the last one ended.
- **`OPS.md`** — the operating model: routing rules, delegation contracts, when to escalate.
- **`DECISIONS.md` + `OPPORTUNITIES.md`** — approval log and scored option pipeline, so agents stop re-litigating settled questions.
- **`WORKER_BRIEF.md`** — the delegation template that gets delegated subagents useful output on the first try.
- **`bounty-radar`** — a working example of an always-on pipeline: scans GitHub for funded bounty issues, dedupes, filters, and reports.

## Requirements

- macOS or Linux, `bash`, `python3`, `curl`
- [`gh` CLI](https://cli.github.com) authenticated for the radar
- An agent runner of your choice — Devin, Codex, Claude Code, T3 Code, OpenCode — anything that can read a repo and take a brief
- Optional: Telegram bot and/or Slack app for the comms layer

## FAQ

**Is this a course?** No. It's the actual file set — templates, scripts, workflow — with docs explaining how they connect.

**Does it work with \<my agent\>?** The documents are agent-agnostic Markdown. If your runner reads repo files, it works.

**Can I see before I buy?** Yes — [`samples/AGENTS.md`](samples/AGENTS.md) ships unmodified in the kit.

**License?** Single-user commercial license — use it on your own projects, don't resell or republish the kit itself. Full text ships in the zip.

---

Built and dogfooded by [Money Ventures](https://gigwebs.org) — the same system that runs this operation.
