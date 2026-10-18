# AI Game Arcade

A small static gallery for four independent, self-contained browser games, labeled by the model/assistant you said created them:

1. Grok — NEON PULSE
2. ChatGPT — PULSE//RIFT
3. Claude — NEON PULSE
4. Gemini — CYBER PULSE

## Run locally

Open `index.html` in a current browser. The game cards navigate to the files under `games/`. All four game files are standalone HTML with inline CSS/JavaScript and no external script or stylesheet imports.

If your browser restricts local file behavior, run a simple static server from this folder:

```bash
python -m http.server 8000
```

Then open http://localhost:8000.

## Publish

Upload the entire folder contents to any static host (GitHub Pages, Netlify, Cloudflare Pages, or a normal web server). Keep the `games/` directory next to `index.html`; do not upload only the gallery file.

## Notes

- The original standalone game code is preserved except for removing the outer Markdown code fence from the Grok paste and adding a small `← Arcade` return link to each game's page.
- The gallery artwork is hand-authored inline SVG and the interface is plain HTML/CSS/JS.
- The games have different internal controls and mechanics. The gallery lists the primary controls; use each title's in-game instructions as the source of truth.
