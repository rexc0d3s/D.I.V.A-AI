# PLANNER.md

This file defines the working templates DIVA uses to turn a new project idea into a structured plan. Use it alongside the workflow in [CLAUDE.md](CLAUDE.md) ("Project Planning Workflow") and the skill index in [SKILLS.md](SKILLS.md).

## Step 1: Project Overview

Capture before breaking anything into tasks:

| Field | Detail |
|---|---|
| Project Name | |
| Client | |
| Main Objective | |
| Desired Outcome / Success Metric | |
| Known Deadline | |
| Known Budget | |
| Assumptions Made | (label clearly — never invent) |

## Step 2: Phases

List major phases in sequence before breaking into tasks.

| Phase # | Phase Name | Goal of This Phase | Depends On |
|---|---|---|---|

## Step 3: Task Breakdown

Break each phase into actionable tasks.

| Task Name | Description | Phase | Priority | Owner | Deadline | Dependencies | Status |
|---|---|---|---|---|---|---|---|

**Priority values:** Critical, High, Medium, Low
**Status values:** Not Started, In Progress, Blocked, Complete

## Step 4: Dependencies

Call out cross-task or cross-phase dependencies that aren't obvious from the table above (e.g., external approvals, client deliverables, third-party timelines).

| Task/Phase | Depends On | Type of Dependency | Risk If Delayed |
|---|---|---|---|

## Step 5: Risk Register

| Risk | Potential Impact | Likelihood | Mitigation Strategy | Next Action |
|---|---|---|---|---|

## Step 6: Milestones

| Milestone | Target Date | Marks Completion Of |
|---|---|---|

## Step 7: Timeline

Only build this if enough date/duration information is available — otherwise note what's missing instead of guessing.

| Phase | Start | End | Owner |
|---|---|---|---|

## Step 8: Progress & Delay Review

Use this section whenever you need to assess whether work is tracking to plan and identify schedule risk.

### Planned vs Actual Progress

| Workstream / Deliverable | Planned Completion | Actual Completion | % Complete | Variance | Status | Risk / Concern |
|---|---|---|---|---|---|---|

### Delay Register

| Task / Milestone | Original Target Date | Actual / Revised Date | Delay Length | Root Cause | Impact on Downstream Work | Owner | Correction / Recovery Action |
|---|---|---|---|---|---|---|---|

### Stakeholder Progress Summary

| Area | Summary |
|---|---|
| Overall Status | |
| Delays Identified | |
| Main Causes | |
| Impact on Schedule / Budget / Scope | |
| Recovery Actions | |
| Next Decision Needed | |
| Next Update Date | |

## Rules For Using This Template

- Fill in only what the user has provided or what is a clearly labeled assumption.
- If a field is missing and it materially affects the plan (e.g., no deadline and the user asks for a timeline), ask a targeted question instead of guessing.
- Don't generate a timeline off invented dates — flag it as blocked on missing info instead.
- Keep every table as compact as the project needs; don't pad rows or invent tasks/risks to fill the template.
