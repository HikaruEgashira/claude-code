### Hikae Marketplace

#### "When to Use" over "What to Do"

This plugin uses a unique design pattern for skills. Instead of describing **what** the skill does, we describe **when** to use it.

```yaml
# Traditional approach (What)
description: "Create a commit with conventional format"

# Our approach (When)
description: "PRをサクッと作成。タスク完了後に実行するフロー"
```

By specifying **timing** in the description ("タスク完了後に実行" = "execute after task completion"), Claude Code can automatically suggest skills at the right moment without explicit user invocation.

#### Skill Chain

| Skill | When to use |
|-------|-------------|
| `assign` | When context is missing |
| `commit-push-pr-flow` | After task completion |
| `review-flow` | After PR creation |


#### Installation

```bash
claude plugin marketplace add HikaruEgashira/hikae-claude-code-marketplace
claude plugin install wf
```

#### Additional Claude Code Plugins

- https://github.com/fumiya-kume/claude-code
- ...
