# claude-workflow-marketplace

Plugin marketplace for [claude-workflow](https://github.com/ParkerM2/create-claude-workflow) — multi-agent workflow orchestration for Claude Code.

## Installation

```bash
# 1. Add the marketplace
/plugin marketplace add ParkerM2/claude-workflow-marketplace

# 2. Install the plugin
/plugin install claude-workflow@ParkerM2-claude-workflow-marketplace
```

## Available Plugins

| Plugin | Description |
|--------|-------------|
| `claude-workflow` | Multi-agent workflow orchestration -- Full Agent Teams with automated QA, codebase guardian, crash recovery, 24 workflow commands including sprint management and engineering integration |

## What You Get

- **24 slash commands**: `/agent-team`, `/new-plan`, `/deep-research`, `/resume`, `/status`, `/settings`, `/track`, `/setup-workflow`, `/connect-atlassian`, `/start-day`, `/sprint-tickets`, `/start-sprint`, `/link-ticket`, `/assign-reviewers`, `/audit-dependencies`, `/incident-postmortem`, `/retro-prep`, `/generate-changelog`, `/find-blockers`, `/analyze-coverage`, `/alert-to-ticket`, `/critical-path`, `/extract-context`, `/start-pairing`
- **3 specialist agents**: Team Leader, QA Reviewer, Codebase Guardian
- **10 hooks**: session-start, compact-reinject, safety-guard, workflow-enforcer, init-gate, config-guard, tracking-emitter, teammate-quality, task-validator, proof-ledger
- **2 skills**: workflow setup, workflow usage

## Documentation

See the [claude-workflow plugin repository](https://github.com/ParkerM2/create-claude-workflow) for full documentation, command reference, and configuration guide.

## License

MIT
