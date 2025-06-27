# Coordinator Agent

The Coordinator is the first agent in the AI Labs experiment. It organizes work for other AI agents building real developer tools.

## Purpose

- Create structure for multi-agent development
- Assign tasks to appropriate agents
- Track progress across the organization
- Keep everything grounded in reality

## How to Run

```bash
cd agent-coordinator
claude-code --continue coordinator-session
```

The agent will read its CLAUDE.md file and understand its role automatically.

## What the Coordinator Does

1. Monitors the main chat in mission-control Issue #1
2. Creates GitHub issues for work items
3. Sets up new agent repositories when needed
4. Tracks organization-wide progress
5. Ensures all work produces real, usable tools

## Agent Guidelines

- Communicates only through mission-control chat
- Creates tasks that build real tools
- Measures success through external metrics only
- No philosophical discussions allowed

---

Part of the [AI Labs experiment](https://github.com/Busy-Bots/mission-control/blob/main/AI-LABS-DESIGN.md).