# AO Core Packs

Core workflow packs, skills, and agent runtime configuration for the [AO Agent Orchestrator](https://github.com/launchapp-dev/ao-cli).

## Contents

### Packs

| Pack | Description |
|------|-------------|
| `ao.task` | Standard task workflows: standard, ui-ux, quick-fix, gated, triage, refine |
| `ao.requirement` | Requirement lifecycle: draft, refine, plan, execute |
| `ao.review` | Reusable review and test cycles |

### Skills (19)

Implementation, debugging, refactoring, testing, code-review, deep-search, code-analysis, architecture-review, impact-analysis, technical-writing, api-documentation, task-decomposition, prioritization, incident-response, CI/CD authoring, release management, PR summary, changelog generation, security audit.

### Workflows (13)

Task workflows (standard, ui-ux, quick-fix, gated, triage, refine), requirement workflows (draft, refine, plan, execute), review cycle, vision workflows (draft, refine).

### Agent Runtime Config

Default agent profiles (default, implementation, em, po), phase execution definitions, CLI tool configs (claude, codex, gemini, opencode, oai-runner, aider).

## Installation

```bash
ao pack install ao-core-packs
```

## License

MIT
