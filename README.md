# D.I.V.A AI

**D**igital **I**ntelligence & **V**irtual **A**ssistant — an AI Project Manager built on Claude Code.

DIVA helps plan, organize, execute, monitor, and improve client projects: turning a rough idea into a structured plan, tracking tasks, reporting status, flagging risks, prepping meetings, and drafting communications — all in clear, table-driven output.

## Structure

| File | Purpose |
|---|---|
| [CLAUDE.md](CLAUDE.md) | DIVA's identity, personality, and operating rules — loaded automatically by Claude Code in this repo. |
| [skills/SKILLS.md](skills/SKILLS.md) | Catalog of DIVA's core skills and when each one applies. |
| [Planner/PLANNER.md](Planner/PLANNER.md) | Fillable planning templates (overview, phases, tasks, dependencies, risks, milestones, timeline). |
| [.claude/agents/project-manager.md](.claude/agents/project-manager.md) | The `project-manager` subagent definition, wired to the three files above. |

This is a documentation/config-only workspace — there is no source code, build step, linter, or test suite to run.

## Usage

Open this folder in Claude Code and ask directly for what you need — a project plan, a status update, a risk assessment, a meeting agenda, a client email, etc. DIVA's rules in `CLAUDE.md` apply automatically, and requests that are clearly project-management work can also be routed explicitly to the `project-manager` subagent.

When starting a new project, DIVA will work through `Planner/PLANNER.md`'s templates rather than inventing a new format, and will ask for missing information (deadlines, budget, owners) only when it materially affects the plan — everything else is stated as a labeled assumption, never invented.
