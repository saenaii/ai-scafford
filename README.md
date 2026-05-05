# ai-scaffold

Starter layout for AI-assisted work in this repository. There is no application source code yet—only folders and a placeholder file for agent instructions.

## Layout

| Path | Role |
|------|------|
| [`AGENTS.md`](AGENTS.md) | **AGENTS** context for this workspace. Currently empty—add project-specific guidance here. |
| [`.claude/`](.claude/) | [Claude Code](https://docs.anthropic.com/en/docs/claude-code) project configuration and extensions. |
| `.claude/agents/` | Custom subagent definitions (empty). |
| `.claude/commands/` | Slash-command snippets (empty). |
| `.claude/rules/` | Rules loaded for Claude in this project (empty). |
| `.claude/output-styles/` | Output style presets (empty). |
| `.claude/agent-memory/` | Agent memory storage (empty). |
| `.claude/skills` | Symlink to the repo-root `skills/` directory so skills stay in one place. |
| [`skills/`](skills/) | Shared skills content; linked from `.claude/skills`. |
| [`plans/`](plans/) | Optional place for plans or design notes (empty). |

**Note:** `.claude/CLAUDE.md` is currently an **empty directory**. Claude Code normally expects project instructions in a **`CLAUDE.md` file** (often at the repository root or as a single file under `.claude/`). If you use project instructions, replace that directory with a `CLAUDE.md` file or add instructions at the repo root per Claude Code’s docs.

## Getting started

1. Fill in [`AGENTS.md`](AGENTS.md) with how agents should behave in this repo (stack, conventions, boundaries).
2. Add skills under [`skills/`](skills/) and wire them in your tooling as needed.
3. Drop rules, commands, or agents under the matching `.claude/` subfolders if you use Claude Code here.

## Requirements

None. This scaffold does not define a language, runtime, or package manager.
