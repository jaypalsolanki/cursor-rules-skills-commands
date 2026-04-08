# Rules

This folder contains reusable Cursor rule examples for enterprise-grade engineering workflows.

## How to use

- Copy selected `.mdc` files from `examples/` into your target repository `.cursor/rules/`.
- Keep rules focused: one concern per file.
- Prefer concise, actionable guidance with concrete good/bad examples.

## Rule file format

Each rule uses YAML frontmatter:

```md
---
description: Short explanation of the rule
globs: **/*.cs
alwaysApply: false
---
```

Use `alwaysApply: true` only for universal standards.

## Naming convention

- `api-*`: API conventions and web concerns
- `arch-*`: architecture and DDD boundaries
- `evt-*`: event-driven and messaging
- `data-*`: persistence and query safety
- `ops-*`: CI/CD and cloud governance

## Included starter rules

- `api-design-versioning.mdc`
- `api-error-observability.mdc`
- `arch-clean-boundaries.mdc`
- `arch-ddd-domain-events.mdc`
- `evt-message-reliability.mdc`
- `data-access-safety.mdc`
- `ops-cloud-cicd-governance.mdc`
