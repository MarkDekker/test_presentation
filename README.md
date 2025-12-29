# Codex Presentation Hub

Single-file HTML presentations ready for GitHub Pages. Everything lives in `docs/`, so enabling Pages with the `docs` folder will publish the hub and every deck automatically.

## Usage
1. Copy `docs/presentations/template.html` and rename it for your presentation.
2. Update the `data-title` attribute on `.deck`, the pill label in the header, and the slide content.
3. Keep each deck self-contained: inline styles and scripts are already included; add images locally or as base64.
4. Add a link to your new file in `docs/index.html` so it appears on the hub.
5. Commit and push. GitHub Pages will serve `docs/index.html` and every presentation at `/docs/presentations/<your-file>.html`.

## Included
- **`docs/index.html`** – landing page that links to the template and sample deck.
- **`docs/presentations/template.html`** – reusable starting point with navigation controls.
- **`docs/presentations/sample-roadmap.html`** – example deck inspired by existing slides.
