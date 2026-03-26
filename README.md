# Claude Commands

Shared [Claude Code](https://docs.anthropic.com/en/docs/claude-code) slash commands for Growth engineering.

## Setup

Clone this repo and `cd` into it before opening Claude Code:

```bash
git clone https://github.com/dcashin-png/claude-commands.git
cd claude-commands
```

Claude Code automatically picks up commands from `.claude/commands/`. Type `/` in Claude Code to see available commands.

## Available Commands

| Command | Description |
|---|---|
| `/jira-edit` | Create or edit JIRA issues from the terminal via `slack-uberproxy-curl` |

## Prerequisites

- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) installed
- `slack-uberproxy-curl` (comes with Slack dev environment)
- Corp VPN connected
- Valid Kerberos ticket (run `kinit` if you get auth errors)
