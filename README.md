### Hikae Marketplace

Personal Claude Code plugin marketplace for streamlined PR workflows and code quality management.

### Installation

```bash
claude plugin marketplace add HikaruEgashira/hikae-claude-code-marketplace
claude plugin install wf
claude plugin install architect
```

### Examples

#### Review an existing PR
```bash
/review <PR_URL>
```

#### Start from PR
```bash
/assign
```

### Shell Function Shortcuts

Add these convenient shell functions to your `.zshrc` or `.bashrc` for quick access to common commands:

```bash
review() { claude "/review $1"; }
assign() { claude "/assign $1"; }
```

## Awesome Claude Code

- https://github.com/fumiya-kume/claude-code
