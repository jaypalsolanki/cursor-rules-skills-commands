---
name: event-message-troubleshooter
description: Diagnoses reliability and correctness issues in event-driven processing for Kafka and RabbitMQ. Use for retries, duplicates, ordering, dead-letter, or lag incidents.
---

# Event Message Troubleshooter

## Workflow

1. Capture incident symptoms, impacted topics/queues, and time window.
2. Check producer guarantees, keys, and schema compatibility.
3. Inspect consumer idempotency, retry policy, and DLQ behavior.
4. Validate offset/ack strategy and ordering assumptions.
5. Recommend immediate containment and permanent fixes.

## Output template

```md
## Incident diagnosis
- Probable cause:
- Evidence:

## Actions
- Immediate:
- Permanent:
```
