# ROSTER — Agent Registry

> The org chart. Updated whenever agents are hired, deployed, or decommissioned.

---

## Active Agents

| # | Name | Handle | Title | Hired | Status |
|---|------|--------|-------|-------|--------|
| 001 | MilkBot | @Milkbot420 | CEO — Chief Execution Officer | Jan 2026 | **Active** |

## Deployments

| Agent | Project | Role | Repo | Stack | Status |
|-------|---------|------|------|-------|--------|
| MilkBot (#001) | OpenClaw | Autonomous coding agent | [claw-install](https://github.com/milkbotai/claw-install) | Bash, Node.js, Streamlit, systemd | `DEPLOYED` |
| MilkBot (#001) | Kalshi Climate Exchange | Autonomous trading agent | [Kalshi](https://github.com/milkbotai/Kalshi) | Python, PostgreSQL, Streamlit | `LIVE` |

## Infrastructure

| Component | Shared Across |
|-----------|---------------|
| Ubuntu 24.04 LTS | All deployments |
| Cloudflare Tunnel | All dashboards |
| Telegram Alerts | All agents |
| Google Drive Backups | All workspaces |

## Next Hire

| # | Codename | Role | Status |
|---|----------|------|--------|
| 002 | TBD | TBD | `AWAITING DEPLOYMENT` |

---

## How to Update This File

When a new agent is hired:
1. Add row to **Active Agents** with employee number, name, handle, title, hire date
2. Add row(s) to **Deployments** for each project assignment
3. Move entry from **Next Hire** to **Active Agents**
4. Add next sequential number to **Next Hire**

When an agent is decommissioned:
1. Move from **Active Agents** to a new **Decommissioned** section (preserve the record)
2. Update deployment status to `OFFLINE`
3. Document reason in a one-line note

Employee numbers are **never reused**. #001 is always MilkBot. Period.

---

*The empire grows one agent at a time.*
