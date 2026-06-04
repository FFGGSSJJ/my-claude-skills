# My Claude Code Skills

Personal Claude Code marketplace with three skills for research and writing workflows.

## Skills

| Skill | Description |
|-------|-------------|
| **coding-philosophy** | Behavioral guidelines to reduce common LLM coding mistakes (simplicity first, surgical changes, goal-driven execution) |
| **plot** | Matplotlib templates for paper/report figures — Palatino body font + Google-brand palette. Bar, boxplot, line, scatter. |
| **read** | PDF paper reader with image extraction. Study and analyze research papers. |

## Install as Marketplace

On any machine:

```
/install-marketplace https://github.com/YOU/my-claude-skills
```

This registers all three skills at once. After install, run once for the `read` skill:

```bash
cd ~/.claude/plugins/marketplaces/my-claude-skills/skills/read && npm install
```

## Install Individual Plugins

```
/install-plugin https://github.com/YOU/my-claude-skills
```
