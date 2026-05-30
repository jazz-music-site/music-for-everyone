# Jazz Odyssey — AGENTS.md

Static single-page site about jazz history. No build tools, no package manager, no tests.

## Commands

```bash
# Preview locally — just open in browser
open index.html

# Or start a local server
python3 -m http.server 8000
```

## Structure

- `index.html` — single-page layout with inline JS (scroll-progress bar, section nav dots, IntersectionObserver)
- `styles.css` — all styles, ~700 lines, Inter + Unbounded (Google Fonts)
- `images/` — SVG decorations + PNG musician photos, all committed

## Conventions

- Russian-language content, English section headings
- Fonts: `Unbounded` (headings), `Inter` (body) — loaded via Google Fonts
- Color palette: warm beige `#f5d7a1`, dark brown `#2a1a0e`, gold `#cbaa4c`
- Smooth scroll via CSS `scroll-behavior: smooth` + native `scroll-snap-type`
- Layout: CSS Grid sections, no framework dependencies
