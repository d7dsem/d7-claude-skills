# Third-Party Skills

Skills used alongside this collection, NOT vendored here.

| Skill | Source | License | Purpose | Notes |
|-------|--------|---------|---------|-------|
| `codebase-onboarding` | https://github.com/affaan-m/everything-claude-code/blob/main/skills/codebase-onboarding/SKILL.md | MIT | Onboarding guide + starter CLAUDE.md (architecture, entry points, conventions) | Instructions only, no scripts or network calls |
| `session-handoff` | https://github.com/NotThatRob/Claude-Skill-Session-Handoff | MIT | Writes HANDOFF.md (done / current state / next steps) for session continuity | Instructions only, uses local git commands |

## Installing Third-Party Skills

Before installing a third-party skill, review it for:
- Network calls and external service dependencies
- Scripts and command execution
- Telemetry or data collection
- Prompt injection risks
- Filesystem writes outside the repo

Read the skill's SKILL.md file and verify it meets your security and project requirements before installation.
