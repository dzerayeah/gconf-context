# AGENTS.md starter

Скопируйте этот шаблон в `AGENTS.md` в корне проекта.

```markdown
# Instructions for agents

## Scope

Work only inside this repository unless explicitly asked otherwise.

Before reading or editing files outside this folder, ask for confirmation.

## Safety

- Never commit `.env`, API keys, tokens, private links, cookies, credentials, or personal data.
- Before any `git push`, check for secrets and private data.
- Do not delete files without explicit confirmation.
- Do not run destructive commands unless explicitly requested.

## Database

Before any work with a database:

1. Check which database is connected.
2. Confirm it belongs to this repository/project.
3. Identify whether it is local, staging, or production.
4. Do not run migrations, deletes, backfills, or destructive updates without a plan and confirmation.

## Git

- Show `git status` before staging.
- Keep commits focused.
- Do not rewrite history unless explicitly requested.
- Do not overwrite changes made by other people.

## Work style

- Start with a short plan for non-trivial tasks.
- Prefer small working steps.
- After changes, explain how to verify the result.
- If blocked, summarize the blocker and the next concrete option.
```
