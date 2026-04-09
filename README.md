# Project Management Template

A Claude-powered project management template that integrates with Linear to help teams plan, track, and execute projects.

## Prerequisites

- [Claude Code](https://claude.ai/claude-code) installed
- A Linear account

## Setup

### 1. Start a New Project

Copy and rename the template folder:

```bash
cp -r project-template my-project-name
```

### 2. Configure Your Project

Open `my-project-name/CLAUDE.md` and update:

- **Project name & description** — what this project is
- **Linear Team** — your Linear team name
- **Linear Project** — your Linear project name

### 3. Define Your Goals

Edit `my-project-name/project-goals.md` and write out your project goals. This is the source of truth Claude will reference for all AI-assisted work.

### 4. Start Working

Open the project folder in Claude Code:

```bash
cd my-project-name
claude
```

On first use, Claude will prompt you to authorize Linear via OAuth. After that, Linear is fully connected.

## Folder Structure

```
project-template/
├── .mcp.json              # Linear MCP config (pre-configured, no setup needed)
├── CLAUDE.md              # AI instructions — update this when you copy the template
├── project-goals.md       # Your project goals (start here)
├── docs/                  # Static reference materials (read-only for ai)
├── ai/                    # AI-generated outputs
│   ├── goal-breakdown.md  # Goal breakdowns
│   ├── plans/             # Plans and strategies
│   └── research/          # Research outputs
├── decisions/             # Key decisions and ADRs
└── notes/                 # Meeting notes and session summaries
```

## What Claude Can Help With

- **Break down project goals** into Linear issues and milestones
- **Create and update Linear items** following your team's standards (via the linear-handbook skill)
- **Draft plans and research** saved under `ai/`
- **Summarize meetings** and log decisions

## Tips

- Always run Claude from inside your project folder so it picks up the right `CLAUDE.md`
- Keep `project-goals.md` up to date — Claude uses it as the source of truth
- Commit `CLAUDE.md` and `project-goals.md` to version control so teammates share the same context
- The `docs/` folder is read-only for AI — put any reference docs there that Claude should read but never modify
# project-management-template
