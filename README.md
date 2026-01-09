### Hikae Marketplace

#### Installation

```bash
claude plugin marketplace add HikaruEgashira/hikae-claude-code-marketplace
claude plugin install wf
```

#### Skill Chain

| Skill | When to use | Behavior |
|-------|-------------| -------- |
| `assign` | When context is missing | Load context from PR |
| `commit-push-pr-flow` | After task completion | Create PR |
| `review-flow` | After PR creation | Review PR |

#### Additional Claude Code Plugins

- https://github.com/fumiya-kume/claude-code
- ...
