# Claude Skills

Skills for Claude AI agent workflows.

## Skills

| Skill | Description |
|-------|-------------|
| [glean-mcp](./glean-mcp/) | Glean MCP as primary enterprise search tool |

## Installation

Copy a skill folder to `~/.claude/skills/` or your project's `.claude/skills/` directory.

```bash
cp -r glean-mcp ~/.claude/skills/
```

## Structure

```
skill-name/
├── SKILL.md      # Instructions with YAML frontmatter
├── scripts/      # Optional executables
└── resources/    # Optional supporting files
```

## Resources

- [Awesome Claude Skills](https://github.com/travisvn/awesome-claude-skills)
- [Official Skills](https://github.com/anthropics/skills)
