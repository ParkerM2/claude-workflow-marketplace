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
| `claude-workflow` | Multi-agent workflow orchestration -- branch-per-task development with automated QA, codebase guardian, and crash recovery |

## What You Get

- **7 slash commands**: `/new-feature`, `/new-plan`, `/deep-research`, `/resume`, `/settings`, `/status`, `/track`
- **3 specialist agents**: Team Leader, QA Reviewer, Codebase Guardian
- **5 hooks**: safety guard, config guard, workflow gate, session start, compact reinject
- **2 skills**: workflow setup, workflow usage

## Documentation

See the [claude-workflow plugin repository](https://github.com/ParkerM2/create-claude-workflow) for full documentation, command reference, and configuration guide.

## License

MIT
