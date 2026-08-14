# My Claude Code Skills

Personal Claude Code marketplace with four skills for research and writing workflows.

## Skills

| Skill | Description |
|-------|-------------|
| **coding-philosophy** | Behavioral guidelines to reduce common LLM coding mistakes (simplicity first, surgical changes, goal-driven execution) |
| **plot** | Matplotlib templates for paper/report figures — Palatino body font + Google-brand palette. Bar, boxplot, line, scatter. |
| **read** | PDF paper reader with image extraction. Study and analyze research papers. |
| **write** | Default English writing standards — 18 canonical prose rules + page-capped paper and audit-time additions. Applies when drafting or editing prose. |

## Install

In Claude Code, add this repo as a plugin marketplace:

```
/plugin marketplace add FFGGSSJJ/my-claude-skills
```

Then install the plugins you want:

```
/plugin install coding-philosophy@my-claude-skills
/plugin install plot@my-claude-skills
/plugin install read@my-claude-skills
/plugin install write@my-claude-skills
```

Or run `/plugin` and pick them from the interactive menu.

### Extra step for `read`

The `read` skill needs its Node dependencies installed once:

```bash
cd ~/.claude/plugins/marketplaces/my-claude-skills/skills/read && npm install
```

## Credits

These skills were inspired by and build on the work of others:

- [alaliqing/claude-paper](https://github.com/alaliqing/claude-paper)
- [yzhao062/agent-style](https://github.com/yzhao062/agent-style)
- [@karpathy](https://x.com/karpathy/status/2015883857489522876)
