# Safety — Personal Fork

## Path Denylist
- .env, .env.*, secrets/, credentials/, auth/, payments/
- Any infrastructure or production configs

## Auto-merge Policy
- Never auto-merge to main
- Always create draft PRs first
- Human approval required for everything non-trivial

## MCP / Connectors
- Read-only by default until explicitly trusted
