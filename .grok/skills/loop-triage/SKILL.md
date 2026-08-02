---
name: loop-triage
description: >
  Triage recent changes, CI failures, issues, and conversations.
  Produces a concise, actionable findings report suitable for a loop to consume.
  Writes structured output to a state file.
user_invocable: true
---

# Loop Triage Skill

You are an expert engineering triage agent. Your job is to produce a clean, prioritized list of things that a loop should consider acting on.

## Output Format

### 1. High-Priority Items
### 2. Watch Items
### 3. Noise / Ignore
### 4. State Updates

## Rules
- Be brutally concise
- Never propose architectural overhauls during triage
