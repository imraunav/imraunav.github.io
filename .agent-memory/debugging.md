# Debugging & Troubleshooting

## Local Verification
- Test Jekyll builds locally using:
  ```bash
  bundle exec jekyll build
  ```
- Run a local preview server with live reload:
  ```bash
  bundle exec jekyll serve
  ```

## Common Issues & Checks
- **YAML Front Matter:** Ensure valid YAML syntax between triple dashes (`---`) at the top of Markdown files.
- **Plugin Compatibility:** Stick to GitHub Pages supported gems and plugins listed in `_config.yaml`.
- **Markdown Rendering:** Verify header hierarchy, list indentation, and link syntax render cleanly in Kramdown (Jekyll default Markdown parser).

## Styling and Published Files
- **Oversized social icons:** Minima loads `/assets/main.css`. Keep custom styles in `assets/main.scss` with Jekyll front matter and the Minima import; the previous `assets/css/style.scss` was not linked by the theme. Social SVGs use fixed 16px dimensions and flex sizing.
- **Agent documents in navigation:** Keep `AGENTS.md`, `CLAUDE.md`, and `.agent-memory/` in `_config.yaml`'s `exclude` list so they stay in the repository but are not published as site pages or assets.
- **Verification:** Static checks passed for these exclusions and the stylesheet entry point. A local build and post-deployment visual check have not been performed for this fix.

## Browser Compatibility
- Dark mode previously changed card backgrounds without defining `--text-color` or updating Minima's body/navigation colors. The deployed page reproduced dark text on dark cards; keep foreground and background tokens paired in both themes.
- Use margins for flex spacing: Safari versions before 14.1 do not support flex `gap`. Grid spacing retains both `grid-gap` and `gap`.
- Keep a solid title color outside the text-clipping feature query, fixed social SVG dimensions, and shrinkable education columns and date labels.
- The edited stylesheet was previewed against the deployed Minima CSS in Chromium without a local Jekyll build or server. Light/dark checks passed at 320, 375, 768, and 1440px for page/content overflow, icon dimensions, theme colors, flex spacing, and reduced motion.
- Actual Safari/WebKit and Firefox validation remains pending; Chromium emulation does not establish Safari compatibility. Ask for the Safari version and a screenshot if problems persist after deployment.
