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
| `growth-agent` | Weekly free traffic ideas, ranked; logs to `growth/backlog.md` |
| `agent-builder` | Builds an agent + skill for a chosen growth activity |

Content Desk dashboard: https://claude.ai/artifact/LdHiK4w8WNbzMjrbQvtVrb (source: `dashboard/content-approvals.html`). Cadence: 1 blog + 3 social posts per week.
