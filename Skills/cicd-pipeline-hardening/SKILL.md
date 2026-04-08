---
name: cicd-pipeline-hardening
description: Hardens CI/CD pipelines with quality gates, security checks, deployment safety, and rollback readiness. Use when creating or improving build and release pipelines.
---

# CI/CD Pipeline Hardening

## Workflow

1. Review current pipeline stages and branch/release strategy.
2. Enforce compile, test, lint, and static security checks.
3. Add artifact traceability, SBOM/signing, and deployment approvals.
4. Validate environment promotion and rollback controls.
5. Produce prioritized hardening backlog.

## Output template

```md
## Pipeline gaps
- High risk:
- Medium risk:

## Hardening backlog
1.
2.
```
