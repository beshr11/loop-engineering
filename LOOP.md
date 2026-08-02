# LOOP.md — Personal Fork (beshr11/loop-engineering)

This is a **personal fork** of the official Loop Engineering reference repository.

Primary purpose: Experimental playground and personal patterns using **Grok** as the main tool.

## Active Loops (Personal)

| Pattern          | Cadence     | Level | Status          | Notes                              |
|------------------|-------------|-------|-----------------|------------------------------------|
| Daily Triage     | Manual / on-demand | L1  | Report-only     | Primary loop for now               |
| PR Babysitter    | Manual      | L2    | Not activated   | Enable when needed                 |
| Dependency Sweeper | Manual    | L2    | Not activated   | —                                  |

## Human Gates (Personal Rules)

- No auto-push / no auto-merge without explicit confirmation
- All code changes require human review
- Report-only by default (L1)
- Prefer Grok as primary tool

## Budget

See `loop-budget.md`. Keep conservative until real usage patterns emerge.

## Safety

- Respect `gate.yaml` denylist
- Never touch secrets, credentials, or infrastructure without explicit approval
- Always create draft PRs first

## How to operate

```bash
# Doctor
npx @cobusgreyling/loop doctor .

# Triage
# (run the loop-triage skill against current STATE)

# Cost estimate
npx @cobusgreyling/loop-cost --pattern daily-triage --level L1
```

---
*Personal fork — not the upstream reference.*
