# Rara

A self-evolving, developer-first personal proactive agent built in Rust.

## Highlights

- **Proactive** — Heartbeat-driven background actions, not just request-response
- **Tape memory** — Append-only JSONL tape with anchor-based context windowing
- **Kernel architecture** — OS-inspired event loop: LLM, Tool, Memory, Session, Guard, EventBus
- **Multi-channel** — Telegram, Web Chat, Terminal

## Tech Stack

- **Backend**: Rust, axum, tokio, sqlx, tonic (gRPC)
- **Frontend**: React 19, Tailwind v4, shadcn/ui
- **Database**: PostgreSQL
- **Integrations**: MCP protocol, Composio

## License

Apache-2.0
