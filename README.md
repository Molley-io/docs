# docs

This repository hosts the Molley documentation static site that deploys via GitHub Pages.

## Static Site Generator

- **Engine**: Jekyll (GitHub Pages default)
- **Config**: `_config.yml`
- **Dependencies**: defined in `Gemfile` (uses the `github-pages` gem bundle)

## Local Development

```bash
bundle install
bundle exec jekyll serve
```

Visit <http://localhost:4000> to preview changes.

## Custom Script Injection

Use page front matter (e.g., in `index.md`) to control assets:

- `stylesheets`: array of CSS URLs
- `head_inject`: raw HTML snippets added inside `<head>`
- `inline_scripts`: array of inline `<script>` blocks appended before other scripts
- `scripts`: array of objects that can specify:
  - `raw`: literal HTML (e.g., a full `<script>` tag)
  - `inline`: JavaScript content (with optional `id`, `type`, `async`, `defer`, etc.)
  - `src`: external script URL, plus supporting attributes (`module`, `crossorigin`, etc.)
- `body_end_inject`: raw HTML appended before the closing `</body>`

See `index.md` for an example that loads Mermaid and registers DOM-ready logic.