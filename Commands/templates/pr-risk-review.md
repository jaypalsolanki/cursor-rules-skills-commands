# PR Risk Review

## Use case
Review code changes for correctness, architecture impact, and release risk.

## Inputs
- PR objective: `<objective>`
- Affected components: `<components>`
- Risk tolerance: `<low_medium_high>`

## Prompt body
Perform a principal-engineer review of the PR for `<objective>`. Prioritize bugs, regressions, operational risk, and missing tests. Classify findings by severity and propose concrete fixes.

## Expected output format
- Critical findings
- Major findings
- Minor suggestions
- Test coverage gaps
