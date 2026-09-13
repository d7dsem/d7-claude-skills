# d7-claude-skills

Personal collection of reusable Claude Code skills.

## Skills

| Skill | Description |
|-------|-------------|
| `orchestrator` | Orchestration mode: plan, delegate subtasks to cheaper-model subagents, verify, report. Manual activation only (`/orchestrator`, `disable-model-invocation: true`). |

## Install

Copy a skill folder into `~/.claude/skills/<name>/` (user level) or `<project>/.claude/skills/<name>/` (project level).

### Bash
```bash
cp -r skills/orchestrator ~/.claude/skills/orchestrator
```

### PowerShell
```powershell
Copy-Item -Recurse -Path "skills/orchestrator" -Destination "$env:USERPROFILE\.claude\skills\orchestrator"
```

## Third-Party Skills

See [THIRD_PARTY_SKILLS.md](THIRD_PARTY_SKILLS.md) for additional skills used alongside this collection.

## License

MIT — Copyright (c) 2026 d7dsem
