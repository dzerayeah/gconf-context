# Do not include in public repo

Не переносить в публичный репозиторий:

- `archive/`, raw `.json`, `.txt`, `.srt`, runtime artifacts, sqlite, логи, кэши.
- `task-agent-app/`, `quill-followup-pipeline/`, `taskboard-runtime/`.
- реальные `.env`, API keys, bot tokens, Telegram IDs, memory repo URLs.
- Zoom, LMS invite, приватные Luma/FigJam/admin-ссылки.
- имена участников, usernames, `from_id`, timestamps и цитаты из чатов без очистки.
- внутренние product/current-state документы про LMS, flow bot, аналитику чатов.
- текущие `CLAUDE.md` / `AGENTS.md` как есть: можно взять паттерны, но не workspace-контракт с локальными путями.

