# CI/CD Release Readiness

## Use case
Verify release readiness for services deployed through CI/CD pipelines.

## Inputs
- Service: `<service_name>`
- Target environment: `<environment>`
- Release version: `<version>`

## Prompt body
Assess release readiness for `<service_name>` `<version>` to `<environment>`. Validate quality gates, security checks, deployment strategy, rollback readiness, and observability.

## Expected output format
- Go/no-go decision
- Blocking issues
- Pre-release checklist
- Post-release monitoring checklist
