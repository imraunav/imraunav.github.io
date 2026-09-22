# Site Structure

## Key Files & Directories

- `_config.yaml`: Jekyll site configuration. Defines site title, description, URL, `minima` remote theme, active plugins (`jekyll-remote-theme`, `jekyll-seo-tag`), Sass deprecation options, and exclusions for agent-only documents.
- `_sass/minima/custom-styles.scss`: Custom styling hooked directly into Minima 3's SCSS pipeline. Styles section heading icons, social pills, date badges, honors tags, and skill chips using Minima's theme CSS custom properties.
- `index.md`: The primary landing page (`layout: home`). Contains the bio hero with status indicator and social pills, experience timeline, education with honors badges, and technical toolkit skill tags.
- `AGENTS.md`: Entrypoint instruction file for AI agents, redirecting to `CLAUDE.md`.
- `CLAUDE.md`: Working instructions, conventions, and reminders for agent workflows.
- `.agent-memory/`: Persistent memory notes and context for AI agents working in this repository.

## Content Sections in `index.md`
1. Header / Bio: Brief intro and profile links (GitHub, LinkedIn, Email).
2. Experience: Reverse chronological career history with technical achievements.
3. Education: Degree programs and institutions.
4. Commented Templates: Commented HTML block for future "Key Projects" and "Technical Writeup" additions.
5. Technical Toolkit: Core programming languages and frameworks.
