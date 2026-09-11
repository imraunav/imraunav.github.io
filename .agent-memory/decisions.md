# Decisions & Rationale

## Architectural Decisions

### 1. Minimal Jekyll & Minima Theme
- **Decision:** Use standard Jekyll with the `minima` theme instead of heavy static site generators (Next.js, Astro, Hugo) or complex theme setups.
- **Rationale:** Low maintenance overhead, native GitHub Pages build support without GitHub Actions or extra CI configurations.

### 2. Instruction Delegation (`AGENTS.md` -> `CLAUDE.md`)
- **Decision:** Keep `CLAUDE.md` as the main project instructions and point `AGENTS.md` directly to it.
- **Rationale:** Avoids duplicated guidelines across multiple instruction files and ensures consistency across different agent tools.

### 3. Agent Memory Store (`.agent-memory/`)
- **Decision:** Maintain a dedicated hidden `.agent-memory/` directory with a topic-based index.
- **Rationale:** Enables AI agents to quickly identify and reference specific repo facts, conventions, and past decisions without re-reading the entire codebase each time.
