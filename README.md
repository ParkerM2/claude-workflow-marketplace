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
| `claude-workflow` | Multi-agent workflow orchestration -- branch-per-task development with automated QA, codebase guardian, crash recovery, and 14 workflow commands |

## What You Get

- **14 slash commands**: `/implement-feature`, `/resume-feature`, `/hotfix`, `/refactor`, `/review-pr`, `/generate-tests`, `/create-feature-plan`, `/discover-agents`, `/scaffold-agent`, `/audit-agents`, `/audit-performance`, `/status`, `/track`, `/claude-new`
- **3 specialist agents**: Team Leader, QA Reviewer, Codebase Guardian
- **6 hooks**: branch guard, config guard, destructive command guard, session start, file tracker, git tracker
- **2 skills**: workflow setup, workflow usage

## Documentation

See the [claude-workflow plugin repository](https://github.com/ParkerM2/create-claude-workflow) for full documentation, command reference, and configuration guide.

## License

MIT
