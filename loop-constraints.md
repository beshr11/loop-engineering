# Loop Constraints — Personal Fork (Execution Mode)

> Binding rules for every run. Updated 2026-08-02 after explicit user approval.

## Push & Merge
- Auto-push: **ALLOWED** (user approved 2026-08-02)
- Auto-merge: **ALLOWED** (user approved 2026-08-02)
- Still create draft PRs first when the change is non-trivial
- Medium+ risk or denylist paths → escalate to human

## Paths
- Never edit `.env`, secrets, credentials, auth, payments
- Denylist in gate.yaml remains strictly enforced

## Code
- One fix per run
- Max 3 fix attempts then escalate
- Prefer smallest possible diff

## Budget
- If 80% of daily cap reached → switch to report-only
- If loop-pause-all is active → exit immediately
