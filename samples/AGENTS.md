# AGENTS.md — repo conventions (fill in, keep short)

- `AI_HANDOVER.md` = current verified state. **Read it first every session. Update it at closeout.**
- `OPS.md` = operating model, worker routes, guardrails. `OPPORTUNITIES.md` = scored pipeline. `DECISIONS.md` = append-only approval log.
- `_state/` = runtime logs + dedup state (gitignored, local-only). `scripts/` = reusable automation.
- Secrets live in `~/.agent-ops.env` (or `$AGENT_OPS_ENV`) — never in this repo. `.env*` is gitignored.
- **Verify before claiming done:** run the check, cite the result. "Tests pass" means you ran them this session.
- Before any publish / spend / submission: post the artifact to the ops chat and wait for approval (see OPS.md).
