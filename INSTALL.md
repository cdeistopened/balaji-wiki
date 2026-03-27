# Installing Ask Balaji

## Prerequisites

- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) installed and working

## Installation

```bash
claude install-plugin github:cdeistopened/balaji-wiki
```

Or add the plugin directory manually:

```bash
# From your project directory
claude plugin add /path/to/balaji-wiki/plugin
```

## First Question to Try

```
Evaluate my startup idea
```

This routes to the Idea Maze Navigator — Balaji's core startup evaluation tool — and maps the dead companies, live competitors, technology shifts, and specific path through the maze for your concept.

## Other Good Starting Questions

- "Design a network state for my community"
- "Analyze this event through the tripolar framework"
- "Where are the technology opportunities right now?"
- "Should I try to fix this institution or build something new?"
- "What kind of truth is this claim?"

## Playbook Sequences

For a full build, run skills in playbook order:

1. **Startup Strategy** (5+1 skills) — Evaluate and build a technology startup
2. **Network State Design** (4 skills) — Design a network state from moral premise to recognition
3. **Geopolitical Analysis** (3 skills) — Analyze events through the tripolar lens

Plus 2 standalone skills for truth classification and narrative analysis.

## Troubleshooting

- **Skills not showing:** Make sure the plugin path is correct and Claude Code has been restarted
- **Generic answers:** Try invoking a specific skill directly: `/ask-balaji:idea-maze-navigator`
- **Want a full network state design?** Start with `/ask-balaji:one-commandment-generator` and work through the Network State Design playbook

## Learn More

Visit [creativeintel.agency](https://creativeintel.agency) for more Ask [Creator] plugins.
