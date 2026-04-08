---
name: database-choice-advisor
description: Compares SQL Server, Cosmos DB, DynamoDB, and MongoDB against workload requirements. Use when selecting a primary datastore or redesigning persistence architecture.
---

# Database Choice Advisor

## Workflow

1. Gather workload profile (read/write ratio, latency, consistency, scale).
2. Identify access patterns, partitioning needs, and query complexity.
3. Evaluate operational model, cloud alignment, and cost envelope.
4. Score candidate databases against requirements.
5. Return recommendation with trade-offs and migration risks.

## Output template

```md
## Workload summary

## Option scoring
- SQL Server:
- Cosmos DB:
- DynamoDB:
- MongoDB:

## Recommendation
```
