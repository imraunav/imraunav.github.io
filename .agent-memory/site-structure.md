# Site Structure

## Key Files & Directories

- `_config.yaml`: Jekyll site configuration. Defines site title, description, `minima` theme, active plugins (`jekyll-feed`, `jekyll-seo-tag`), and exclusions for agent-only documents.
- `assets/main.scss`: Imports `minima` and adds custom styling. Compiles to `/assets/main.css`, the stylesheet linked by Minima's default head include.
- `index.md`: The primary landing page (`layout: home`). Contains the bio hero banner, experience timeline cards, education grid, and technical toolkit.
- `AGENTS.md`: Entrypoint instruction file for AI agents, redirecting to `CLAUDE.md`.
- `CLAUDE.md`: Working instructions, conventions, and reminders for agent workflows.
- `.agent-memory/`: Persistent memory notes and context for AI agents working in this repository.

## Content Sections in `index.md`
1. Header / Bio: Brief intro and profile links (GitHub, LinkedIn, Email).
2. Experience: Reverse chronological career history with technical achievements.
3. Education: Degree programs and institutions.
4. Commented Templates: Commented HTML block for future "Key Projects" and "Technical Writeup" additions.
5. Technical Toolkit: Core programming languages and frameworks.
