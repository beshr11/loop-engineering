# AGENTS.md — Personal Fork

## Conventions for this fork

- Primary tool: **Grok**
- Default mode: Report-only (L1) until explicitly promoted
- Never auto-merge or auto-push
- Prefer small, reviewable changes
- Keep upstream patterns intact; put personal experiments in clearly marked areas

## Test / Verify commands
```bash
npx @cobusgreyling/loop doctor .
npx @cobusgreyling/loop status .
```

## Review norms
- All changes that affect core tooling or scoring logic require human review
- Personal patterns / experiments should be clearly separated from upstream content
