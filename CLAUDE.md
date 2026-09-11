# Claude Instructions

## Project overview
- This repository is a small Jekyll-based personal site.
- Configuration lives in [_config.yaml](_config.yaml).
- Primary page content lives in [index.md](index.md).

## Working conventions
- Keep changes small and focused.
- Preserve the existing site structure unless a change clearly requires something else.
- Favor simple, maintainable Markdown and Jekyll configuration updates.
- When possible, validate changes with a local build such as `bundle exec jekyll build`.

## Agent memory
- Keep notes for long-lived repo context in the hidden [.agent-memory](.agent-memory) directory.
- Record key facts, decisions, and reminders that would be useful to future agents.
