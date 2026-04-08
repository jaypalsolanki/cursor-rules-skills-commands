---
name: clean-architecture-refactor
description: Refactors codebases toward clean architecture boundaries and dependency direction. Use when services mix domain, application, and infrastructure concerns.
---

# Clean Architecture Refactor

## Workflow

1. Map current layers and identify dependency violations.
2. Define target boundaries (Web, Application, Domain, Infrastructure).
3. Extract interfaces/ports and move implementations outward.
4. Isolate domain logic from frameworks and persistence details.
5. Propose incremental migration slices with risk notes.

## Output template

```md
## Boundary violations
- Item:

## Refactor slices
1. Slice, impact, rollback
2. Slice, impact, rollback
```
