# Udaya Kumar — Portfolio Website

A single-page personal portfolio site, split into separate HTML, CSS, and JS files for easier editing and hosting.

## Files

- `index.html` — page structure/content
- `style.css` — all styling (fonts, colors, layout, animations)
- `script.js` — scroll reveal animations, progress bar animations, modal close-on-Escape

## How to run

No build tools or server required.

1. Keep all three files (`index.html`, `style.css`, `script.js`) in the same folder.
2. Double-click `index.html` to open it in any browser, or use a simple local server:
   ```
   npx serve .
   ```
   then visit the URL it gives you.

## Notes

- The **Business Suite** modal (Father's Shop tools) currently links to local file paths like `file:///C:/Users/udaya/Downloads/...`. These only work on your own computer. If you host this site online (GitHub Pages, Netlify, Vercel, etc.), replace those links with the actual hosted URLs of those HTML tools, or remove the links and just describe the tools.
- Fonts (`DM Serif Display`, `DM Sans`) are loaded from Google Fonts via `@import` in `style.css`, so an internet connection is needed for the fonts to load correctly (the page still works offline, just with fallback fonts).
- To deploy for free, you can drag-and-drop this folder into [Netlify Drop](https://app.netlify.com/drop) or push it to a GitHub repo and enable GitHub Pages.

## Customizing

- Colors and theme variables are defined at the top of `style.css` under `:root` (e.g. `--accent`, `--ink`, `--surface`).
- Section content (About, Skills, Projects, etc.) is in `index.html` — search for the relevant `<section>` or `id` to edit text.
- Modal popups (the "tool detail" boxes) are also in `index.html`, identified by `id="...-modal"`.
