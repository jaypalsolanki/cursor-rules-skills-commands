# Cloud Architecture Decision

## Use case
Produce a clear architecture recommendation for Azure/AWS workloads.

## Inputs
- Workload description: `<workload>`
- NFR targets: `<latency_availability_security_cost>`
- Constraints: `<compliance_team_budget>`

## Prompt body
Recommend a cloud architecture for `<workload>` considering `<nfr_targets>` and `<constraints>`. Compare at least two viable options with trade-offs in reliability, cost, security, and operability.

## Expected output format
- Options compared
- Trade-off matrix
- Recommended option
- Implementation next steps
