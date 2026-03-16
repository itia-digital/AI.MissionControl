# AI.MissionControl

> Mission Control dashboard for Itia Digital's AI agent organization.

Real-time visibility into what our AI agents are doing: pipeline status, ticket progress, costs, and team activity.

## Stack

- **Frontend:** React + TypeScript + Tailwind CSS
- **Data Sources:** Linear API, GitHub API, OpenClaw logs
- **Hosting:** TBD (Vercel / self-hosted)

## Features (planned)

- 🤖 **Team View** — Agent roster, roles, models, current activity
- 📊 **Pipeline Dashboard** — Epic progress, ticket flow, blocking status
- 📈 **Activity Feed** — Real-time log of agent actions and state transitions
- 💰 **Cost Tracker** — Spend by model, agent, and time period
- 🔔 **Alerts** — Stale tickets, failed runs, API errors

## Architecture

```
Linear API ──┐
GitHub API ──┤──→ Mission Control API ──→ React Dashboard
OpenClaw ────┘
```

## Development

```bash
npm install
npm run dev
```

## Team

- **Product Owner:** Manolo (blanks88)
- **Orchestrator:** Carlo (AI)
- **Implementers:** Benito (Codex), Mary K (Claude Code)

---

Part of [Itia Digital](https://github.com/itia-digital) · Powered by [OpenClaw](https://openclaw.ai)
