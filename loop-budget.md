# Loop Budget — Personal Fork (beshr11)

## Daily limits (conservative starting point)

| Loop            | Max runs/day | Max tokens/day | Max sub-agents |
|-----------------|--------------|----------------|----------------|
| Daily Triage    | 3            | 150k           | 0 (L1)         |
| Any other loop  | 1            | 80k            | 1              |

## On budget exceed
1. Switch to report-only
2. Log the event
3. Notify human

## Kill switch
Set `loop-pause-all` in STATE.md or add the label on GitHub.

## Estimate
```bash
npx @cobusgreyling/loop-cost --pattern daily-triage --level L1
```
