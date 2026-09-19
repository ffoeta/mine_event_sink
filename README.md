# mine_event_sink

Sink from Kafka to the event store used by ML.

## Responsibilities
- Consume behavioral and CDC topics.
- Write append-only tables; upsert by primary key, deduplicate by business id (CDC is at least once).

## Technologies
- Kafka
- Postgres (`events` schema)
