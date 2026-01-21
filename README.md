### Agent Skills Plugins

## Quick Start

```bash
npx add-skill HikaruEgashira/agent-skills
```

#### Installation

```bash
claude plugin marketplace add HikaruEgashira/agent-skills
claude plugin install wf
```

#### Skill Chain

| Skill | When to use | Behavior |
|-------|-------------| -------- |
| `assign` | When context is missing | Load context from PR |
| `commit-push-pr-flow` | After task completion | Create PR |
| `review-flow` | After PR creation | Review PR |

#### Additional Agent Skills Plugins

- ...
- ...
