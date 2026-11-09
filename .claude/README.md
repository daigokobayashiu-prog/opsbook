# Opsbook agent setup

Subagents live in `.claude/agents/`:

| Agent | Role |
|---|---|
| `ops-orchestrator` | Plans, delegates, merges; enforces approval gates |
| `copy-agent` | Marketing copy in Opsbook's voice |
| `webflow-agent` | Webflow + `home-embed.html` changes (stages only) |
| `site-audit-agent` | Read-only SEO / a11y / perf audits |
| `social-agent` | Buffer drafts, scheduling, metrics |

Use: `@ops-orchestrator refresh the home page hero copy, then draft 3 LinkedIn posts announcing it`.
Nothing publishes or schedules without explicit user approval.
