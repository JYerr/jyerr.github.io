# Maya Whitfield — Portfolio Site (Template)

A 5-page static site: a resume homepage + 3 mocked consulting case studies with charts.
No build tools, no npm — just HTML/CSS files you can edit directly and host for free.

## Files
- `index.html` — homepage: resume summary, experience, skills, case study index
- `case-retail.html`, `case-health.html`, `case-fintech.html` — case study detail pages
- `styles.css` — shared design system (colors, fonts, layout) used by every page

## 1. Customize the content (no coding needed)
Open any `.html` file in a plain text editor (Notepad, TextEdit, or VS Code) and change the
text between the tags. You don't need to touch anything inside `<svg>` unless you want to
change the chart shapes — just edit the surrounding text, numbers, and links.

Things to swap out first:
- Your name (search/replace "Maya Whitfield" everywhere)
- The role, summary, and hero-meta block in `index.html`
- Experience entries and skill pills in `index.html`
- Case study titles, client names, metrics, and body text in the three `case-*.html` files
- Email address and links in the footer of each page
- To add a 4th case study: duplicate one of the `case-*.html` files, edit its content, then
  add a matching row in the "Case Work" section of `index.html`

## 2. Host it for free on GitHub Pages
1. Create a free GitHub account at github.com if you don't have one
2. Create a new repository (e.g. `your-name-portfolio`) — make it Public
3. Upload all 5 files in this folder to that repository (drag-and-drop works in the GitHub
   web UI — click "Add file" → "Upload files")
4. Go to the repo's **Settings** tab → **Pages** (left sidebar)
5. Under "Build and deployment", set Source to **Deploy from a branch**, branch `main`, folder `/root`
6. Save — GitHub gives you a live URL in a minute or two, usually
   `https://your-username.github.io/your-name-portfolio/`

No servers, no cost, no maintenance. Every time you edit a file and re-upload it, the live
site updates automatically within a minute.

## 3. Optional: custom domain
In the same Pages settings screen you can add a custom domain (e.g. `mayawhitfield.com`) if
you buy one — GitHub's docs walk through the DNS setup: docs.github.com → Pages → custom domain.

## Notes
- All client names, metrics, and quotes are placeholder/mocked — replace with your real
  project details before sharing.
- Fonts (Fraunces, Inter, IBM Plex Mono) load free from Google Fonts via the `<link>` tags
  at the top of each page — no account needed.
- Charts are hand-drawn SVG, so there's no chart library to install or keep updated.
