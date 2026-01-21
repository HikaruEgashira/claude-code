<p align="center"><code>npx add-skill HikaruEgashira/agent-skills</code></p>

#### Skill Chain

| Skill | When to use | Behavior |
|-------|-------------| -------- |
| `assign` | When context is missing | Load context from PR |
| `commit-push-pr-flow` | After task completion | Create PR |
| `review-flow` | After PR creation | Review PR |

#### For Claude Code

```bash
claude plugin marketplace add HikaruEgashira/agent-skills
claude plugin install wf
```
