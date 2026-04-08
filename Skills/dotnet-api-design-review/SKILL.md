---
name: dotnet-api-design-review
description: Reviews .NET Web API design for contract quality, versioning, validation, error handling, and observability. Use when building or reviewing API endpoints in .NET 8 or newer.
---

# Dotnet API Design Review

## Workflow

1. Inspect endpoint contracts, routing, and versioning strategy.
2. Validate request/response DTO design and backward compatibility.
3. Check error model (`ProblemDetails`) and status code semantics.
4. Verify tracing, correlation IDs, and structured logging.
5. Provide prioritized findings and remediation actions.

## Output template

```md
## API Review Findings
- Critical:
- Major:
- Minor:

## Recommended changes
1.
2.
```
