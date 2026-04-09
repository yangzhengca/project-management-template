# Project Assistant Guide

## Project Context

This is **[PROJECT NAME]** — update this line with your project name and a one-sentence description.

- **Linear Team:** [TEAM NAME] — update with your Linear team name
- **Linear Project:** [PROJECT NAME] — update with your Linear project name

## Folder Structure

```
[project-name]/
├── CLAUDE.md              # This file — AI instructions & project context
├── project-goals.md       # Source of truth for project goals (human-written)
├── resources/             # Static reference materials, do not modify
├── ai/                    # AI-generated outputs
│   ├── goal-breakdown.md  # AI breakdown of project goals
│   ├── plans/             # AI-generated plans and strategies
│   └── research/          # AI research outputs
├── docs/                  # Human-written documentation
├── decisions/             # Key decisions and ADRs
└── notes/                 # Meeting notes and session summaries
```

## How to Work With This Project

- Read `project-goals.md` first to understand the project before taking any action
- Save all AI-generated content under `ai/` — never overwrite files in `resources/`
- Use the `linear-handbook` skill whenever creating or updating Linear issues, projects, or initiatives
- When asked to break down goals, write output to `ai/goal-breakdown.md`
- When asked to create plans, write output under `ai/plans/`
- When asked to research, write output under `ai/research/`

## Linear Integration

This project uses the Linear MCP server. When interacting with Linear:

- Always use the `linear-handbook` skill to ensure issues follow team standards
- Reference `project-goals.md` for context when creating or updating Linear items
- Default to the Linear team and project specified above unless told otherwise

## Boundaries

- Do not modify anything in `resources/` — it is read-only reference material
- Do not create files outside the folders listed above without asking first
- When in doubt about scope or priority, refer back to `project-goals.md`
