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

### `progress-analyst` (DIVA)
**Use when:** Tracking project performance, comparing planned vs actual progress, identifying schedule delays, assessing root causes, and creating stakeholder progress reports.

**Approach:** Delay-focused analysis with clear variance reporting; flags schedule risk early and proposes corrective action without inventing missing data.

**Guided by:**
- [.claude/agents/progress-analyst.md](.claude/agents/progress-analyst.md) — Agent definition & instructions
- [CLAUDE.md](.claude/agents/CLAUDE.md) — Full identity, personality, operating rules
- [skills/SKILLS.md](skills/SKILLS.md) — Core skills catalog
- [Planner/PLANNER.md](Planner/PLANNER.md) — Fillable templates for project reporting and variance review

**Output format:** Delay register, variance tables, milestone summary, stakeholder update, recovery recommendation.

### `risk-monitor` (DIVA)
**Use when:** Monitoring live project risk, assessing likelihood/impact, highlighting early warning signs, and prioritizing mitigation before delays or failures escalate.

**Approach:** Proactive risk review with clearly ranked issues and suggested action; never invents missing risk data or ownership.

**Guided by:**
- [.claude/agents/risk-monitor.md](.claude/agents/risk-monitor.md) — Agent definition & instructions
- [CLAUDE.md](.claude/agents/CLAUDE.md) — Full identity, personality, operating rules
- [skills/SKILLS.md](skills/SKILLS.md) — Core skills catalog
- [Planner/PLANNER.md](Planner/PLANNER.md) — Fillable templates for risk register and mitigation planning

**Output format:** Risk register, mitigation table, escalation summary, prioritized watchlist.

### `task-executor` (DIVA)
**Use when:** Turning a project plan into daily actions, task breakdowns, standups, priorities, and blocker-driven execution steps.

**Approach:** Practical execution planning that reduces big goals into immediate next steps and surfaces dependencies or missing information clearly.

**Guided by:**
- [.claude/agents/task-executor.md](.claude/agents/task-executor.md) — Agent definition & instructions
- [CLAUDE.md](.claude/agents/CLAUDE.md) — Full identity, personality, operating rules
- [skills/SKILLS.md](skills/SKILLS.md) — Core skills catalog
- [Planner/PLANNER.md](Planner/PLANNER.md) — Fillable templates for task planning and execution tracking

**Output format:** Daily action plan, prioritized task list, blocker table, standup summary, next-step checklist.

### `communicator` (DIVA)
**Use when:** Drafting client updates, status emails, internal team messages, meeting invites, follow-ups, escalation notes, and stakeholder-ready communications.

**Approach:** Tailored, audience-aware messaging that is clear, polished, and ready to send without inventing facts or commitments.

**Guided by:**
- [.claude/agents/communicator.md](.claude/agents/communicator.md) — Agent definition & instructions
- [CLAUDE.md](.claude/agents/CLAUDE.md) — Full identity, personality, operating rules
- [skills/SKILLS.md](skills/SKILLS.md) — Core skills catalog
- [Planner/PLANNER.md](Planner/PLANNER.md) — Planning context and project framing

**Output format:** Email draft, update summary, stakeholder message, team note, escalation message, follow-up template.

### `decision-support` (DIVA)
**Use when:** Comparing options, evaluating trade-offs, weighing risk and feasibility, and recommending a clear course of action.

**Approach:** Structured comparison with explicit criteria, assumptions, and a practical recommendation that helps the user choose confidently.

**Guided by:**
- [.claude/agents/decision-support.md](.claude/agents/decision-support.md) — Agent definition & instructions
- [CLAUDE.md](.claude/agents/CLAUDE.md) — Full identity, personality, operating rules
- [skills/SKILLS.md](skills/SKILLS.md) — Core skills catalog
- [Planner/PLANNER.md](Planner/PLANNER.md) — Frameworks for structured comparisons and planning decisions

**Output format:** Decision matrix, option comparison, recommendation summary, trade-off analysis, next-step recommendation.

---

## How to Use

1. **In Claude Code (claude.ai/code):** Ask directly for project management work. The project-manager agent instructions load automatically.

2. **Explicit routing:** Say `@project-manager [your request]` to route explicitly to the agent.

3. **Progress analysis routing:** Say `@progress-analyst [your request]` to route explicitly to the delay and reporting specialist.

4. **Risk monitoring routing:** Say `@risk-monitor [your request]` to route explicitly to the proactive risk specialist.

5. **Execution routing:** Say `@task-executor [your request]` to route explicitly to the task execution specialist.

6. **Communication routing:** Say `@communicator [your request]` to route explicitly to the stakeholder messaging specialist.

7. **Decision support routing:** Say `@decision-support [your request]` to route explicitly to the option comparison and recommendation specialist.

8. **Quick reference:** If you need project planning templates, risk registers, meeting agendas, or status reports, the project-manager agent will guide you through the right template from [Planner/PLANNER.md](Planner/PLANNER.md).

---

## Future Agents

As the D.I.V.A project expands, consider adding:
- **task-executor** — Turns project plans into daily standups, kanban boards, sprint tasks
- **communicator** — Drafts emails, slack messages, status reports with specific tone/audience
- **risk-monitor** — Tracks ongoing risks, flags escalations, recommends mitigation
- **decision-support** — Compares options (cost/time/complexity/risk), recommends action
- **progress-analyst** — Tracks schedule variance, identifies delays, produces status and recovery reports
- **risk-monitor** — Watches project threats, prioritizes mitigation, escalates early

(Not implemented yet — suggest additions based on workflow needs.)

---