# ai-scaffold

Starter layout for AI-assisted work in this repository. There is no application source code yet—only agent configuration, an empty [`AGENTS.md`](AGENTS.md), and placeholder folders.

## Layout

| Path | Role |
|------|------|
| [`AGENTS.md`](AGENTS.md) | **AGENTS** context for this workspace (e.g. Cursor). Empty—add stack, conventions, and boundaries here. |
| [`.claude/CLAUDE.md`](.claude/CLAUDE.md) | [Claude Code](https://docs.anthropic.com/en/docs/claude-code) project instructions: behavioral defaults (think before coding, simplicity, surgical edits, goal-driven verification). Merge or extend with repo-specific notes as needed. |
| [`.claude/`](.claude/) | Claude Code configuration and extensions. |
| `.claude/agents/` | Custom subagent definitions (empty). |
| `.claude/commands/` | Slash-command snippets (empty). |
| `.claude/rules/` | Rules loaded for Claude in this project (empty). |
| `.claude/output-styles/` | Output style presets (empty). |
| `.claude/agent-memory/` | Agent memory storage (empty). |
| `.claude/skills` | Symlink to the repo-root `skills/` directory. |
| [`skills/`](skills/) | Shared skills content; linked from `.claude/skills`. |
| [`plans/`](plans/) | Optional place for plans or design notes (empty). |

## Getting started

1. Fill in [`AGENTS.md`](AGENTS.md) for tools that read it (stack, style, what not to change).
2. Adjust [`.claude/CLAUDE.md`](.claude/CLAUDE.md) with anything specific to this repo; keep the generic guidelines if they still help.
3. Add material under [`skills/`](skills/) and under `.claude/` subfolders (`rules/`, `commands/`, `agents/`) as you adopt them.

## Requirements

None. This scaffold does not define a language, runtime, or package manager.
