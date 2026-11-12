# Skills

A collection of reusable, task-focused skills for AI agents.

Each skill packages focused instructions and any supporting resources needed for a specific kind of work. Skills live in their own directories and can be used independently.

## Repository structure

```text
<skill-name>/
├── SKILL.md
├── references/   # optional
├── scripts/      # optional
└── assets/       # optional
```

The `SKILL.md` file describes the skill's purpose, when it applies, and how to use it. Supporting folders are included only when a skill needs them.

## Use a skill

1. Choose a skill directory in this repository.
2. Copy the entire directory into the skills location configured for your AI agent, preserving its internal structure.
3. Use your agent's supported skill discovery or invocation method.

Installation paths and activation vary by tool. Follow your AI agent's documentation.

## Design goals

- Focused guidance for a specific task
- Reusable across projects and teams
- No assumptions about a particular brand or client
- Clear links to any supporting resources
- Careful handling of private and client information
