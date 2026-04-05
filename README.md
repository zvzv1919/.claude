# ~/.claude

Personal Claude Code configuration. Directory names follow the
[official Claude Code conventions](https://code.claude.com/docs/en/claude-directory).

## Structure

| Path | Purpose |
|---|---|
| `CLAUDE.md` | Global instructions loaded every session |
| `commands/*.md` | Custom slash commands (`/user:<name>`) |
| `skills/<name>/SKILL.md` | Reusable prompt workflows |
| `rules/*.md` | Topic-scoped instructions |
| `agents/*.md` | Subagent definitions |
| `output-styles/*.md` | Custom output style overrides |
| `settings.json.example` | Sanitized settings template (real `settings.json` is gitignored) |

## Setup

1. Clone this repo to `~/.claude`
2. Copy `settings.json.example` to `settings.json` and fill in your secrets
3. Claude Code will pick up everything automatically
