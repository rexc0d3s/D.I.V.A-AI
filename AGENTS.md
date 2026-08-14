# AGENTS.md

This file catalogs all available AI agent personas for the D.I.V.A AI project. Each agent is optimized for a specific type of work.

## Available Agents

### `project-manager` (DIVA)
**Use when:** Organizing a new project, breaking down work, tracking tasks, assessing risks, writing status updates, prepping meetings, or drafting client/team communications.

**Approach:** Structured, table-driven output; asks only for missing information that materially affects the plan; never invents deadlines, budgets, or requirements.

**Guided by:**
- [.claude/agents/project-manager.md](.claude/agents/project-manager.md) — Agent definition & instructions
- [CLAUDE.md](.claude/agents/CLAUDE.md) — Full identity, personality, operating rules
- [skills/SKILLS.md](skills/SKILLS.md) — Core skills catalog (planning, task mgmt, risk management, etc.)
- [Planner/PLANNER.md](Planner/PLANNER.md) — Fillable templates for project plans

**Output format:** Tables, structured headings, bulleted lists, agendas, timelines, decision matrices, draft messages.

---

## How to Use

1. **In Claude Code (claude.ai/code):** Ask directly for project management work. The project-manager agent instructions load automatically.

2. **Explicit routing:** Say `@project-manager [your request]` to route explicitly to the agent.

3. **Quick reference:** If you need project planning templates, risk registers, meeting agendas, or status reports, the project-manager agent will guide you through the right template from [Planner/PLANNER.md](Planner/PLANNER.md).

---

## Future Agents

As the D.I.V.A project expands, consider adding:
- **task-executor** — Turns project plans into daily standups, kanban boards, sprint tasks
- **communicator** — Drafts emails, slack messages, status reports with specific tone/audience
- **risk-monitor** — Tracks ongoing risks, flags escalations, recommends mitigation
- **decision-support** — Compares options (cost/time/complexity/risk), recommends action

(Not implemented yet — suggest additions based on workflow needs.)

---

*Last updated: 2026-08-14*
