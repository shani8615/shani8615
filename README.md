### Hi, I'm Zeeshan

Go backend engineer and tech lead. I build **AI and LLM infrastructure in Go** — services that call models reliably, stream results to users, and keep data safe — and I open-source the building blocks.

#### Go libraries

| | |
|---|---|
| [**go-structllm**](https://github.com/shani8615/go-structllm) | Typed, validated LLM output: JSON Schema from structs, automatic repair loop, OpenAI-compatible client |
| [**go-ssekit**](https://github.com/shani8615/go-ssekit) | Server-Sent Events: stream LLM tokens to browsers, broker with `Last-Event-ID` replay, reconnecting client |
| [**go-redact**](https://github.com/shani8615/go-redact) | `log/slog` handler that keeps secrets and PII out of logs |
| [**go-outbox**](https://github.com/shani8615/go-outbox) | Transactional outbox for Postgres → NATS / Kafka / RabbitMQ |
| [**go-resilience**](https://github.com/shani8615/go-resilience) | Retry with backoff, circuit breaker, rate limiting |
| [**go-httpkit**](https://github.com/shani8615/go-httpkit) | Middleware, `Idempotency-Key` support, RFC 9457 errors for plain `net/http` |

All of them depend only on the Go standard library and are tested in CI.

#### Reference projects

- [**go-microservices-kit**](https://github.com/shani8615/go-microservices-kit): gateway, auth, orders and notifications with Postgres per service, NATS JetStream and a transactional outbox
- [**go-rag-pgvector**](https://github.com/shani8615/go-rag-pgvector): chat with your documents, a RAG service in Go with PostgreSQL + pgvector and source citations

#### What I work on

Go microservices · LLM integration (structured output, RAG, streaming) · event-driven systems on Postgres and NATS · security-minded backend design

Issues and pull requests on any of these repos are welcome.
