# Progress

## Session 1

### What was built

**Core files**
- `index.html` — single-page portfolio with Hero, Projects, Selected Works, About, and Contact sections
- `style.css` — shared stylesheet for all pages
- `publications.html` — dedicated publications page with Conference Papers and Journal Articles groups

**Design decisions**
- Plain HTML + CSS only; no frameworks, no JavaScript
- Dark theme: `#0c0c0c` background, `#e2e2e2` text, `#222` borders
- Inter (Google Fonts) for typography; weights 300, 400, 500
- CSS custom properties (`--bg`, `--text`, `--space-*`, etc.) for all tokens
- Max content width: `1100px`, centered

**Layout**
- Fixed nav: name left (`Junyoung Jung` links to `index.html`), section links right
- Hero fills 80vh, content anchored to bottom
- Projects: 3-column CSS Grid → 2-col at 900px → 1-col at 600px
- About and Contact: 1fr/2fr two-column grid → stacked on mobile
- Nav wraps on mobile: name on its own line, links below

**Content slots (all empty, ready to fill)**
- `index.html`: page `<title>`, `h1` (name), `.discipline`, `.tagline`, 3× project card (`<span class="project-status">`, `<h3>`), 2× selected works teaser (`.pub-title`, `.pub-meta`), `.bio`, `.email-link`
- `publications.html`: all publication entries (title, authors, venue, year, PDF/DOI href)
- `<footer><small>` on both pages

### Infrastructure
- Git repo initialized, `main` branch
- GitHub: `junyoungjung99/my-portfolio` (public)
- Hosting: Cloudflare Pages (recommended, not yet connected — see Next Steps)
- Domain: `junyoungjung.com` via Cloudflare Registrar
