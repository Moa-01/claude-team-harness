# AI tools and setup declaration

Required by the rules: "Any AI tools are allowed. Declare your tools and setup at the start."
"Personal templates or harness repos must be public and declared at registration."

**Harness repo (public):** <github URL of this repo>

## Member 1 — Moataz
- **Agent:** Claude Code (CLI), model Claude Opus 5.5
- **Plugins/skills:** superpowers, caveman, ponytail, claude-mem (local memory across sessions), watch
- **Hooks:** RTK (rewrites shell commands through `rtk` to shorten their output)
- **MCP servers:** Linear, claude-in-chrome
- **Other:** <editor, extensions>

## Member 2 — <name>
- **Agent:** <fill in>
- **Plugins/skills/hooks:** <fill in>
- **MCP servers:** <fill in>
- **Other:** <fill in>

## Shared setup (this repo)
- `CLAUDE.md`, `.claude/rules/`, `.claude/docs/` — rules and workflow for our agents
- `.claude/settings.json` — command allow/deny/ask lists (see README)
- `install.sh` — installs the harness into the project, excluded from git
- herdr (terminal multiplexer for agents) — `herdr/up.sh` and `herdr/task.sh` open our workspaces
- Coordination between agents and people via Linear (Linear MCP server)
