## Soheb

I build backend systems and agent infrastructure. My work sits at the intersection
of service architecture, async processing, and applied AI systems.

---

## Work

### [smart-revision-engine](https://github.com/SSOHEB/smart-revision-engine)

Multi-agent pipeline for adaptive learning. A planner agent decomposes a topic into
retrievable units, a quiz agent generates and grades responses, and a progress agent
adjusts difficulty based on retention signals. Agents communicate through a shared
state graph via LangGraph. Persistence handled through PostgreSQL with Redis for
short-lived session context.

Stack: FastAPI · LangGraph · PostgreSQL · Redis · Docker

---

### [uniseba](https://github.com/SSOHEB/uniseba)

Unified search interface for Windows. Exposes a plugin interface so data sources —
local filesystem, browser history, custom indexes — register themselves and respond
to a single query. The core is an indexing service that maintains an inverted index
updated on file system events.

Stack: Python · Windows API · plugin architecture

---

### [queue-lab](https://github.com/SSOHEB/queue-lab)

Isolated experiments with RabbitMQ and Kafka. Covers producer/consumer topology,
dead letter exchange behavior, consumer group rebalancing, and idempotent message
processing. Each experiment is self-contained with a write-up on observed behavior
and failure modes.

Stack: RabbitMQ · Kafka · Python · Docker Compose

---

## Open Source

Active in: FastAPI · LangGraph · OpenTelemetry

I read source before I file issues. Contributions I care about: correctness,
observability, and the unsexy infrastructure work that makes systems reliable.

---

## Writing

[medium.com/@shaykhsuhaib7](https://medium.com/@shaykhsuhaib7)

---

shaykhsuhaib7@gmail.com · [LinkedIn](https://www.linkedin.com/in/s-soheb-292a3533b/)
