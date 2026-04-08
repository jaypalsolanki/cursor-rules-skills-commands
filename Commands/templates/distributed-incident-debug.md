# Distributed Incident Debug

## Use case
Troubleshoot production incidents involving API, messaging, and data stores.

## Inputs
- Incident summary: `<incident>`
- Time window: `<start_end_utc>`
- Systems involved: `<services_topics_queues_datastores>`

## Prompt body
Investigate `<incident>` across `<systems>`. Build a timeline, identify likely failure points in API, Kafka/RabbitMQ processing, and persistence paths, then propose immediate containment and permanent fixes.

## Expected output format
- Timeline
- Probable causes with evidence
- Immediate actions
- Long-term remediation
