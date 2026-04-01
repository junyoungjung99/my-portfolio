# Next Steps

## Immediate — content to fill in

All structure is in place. The following slots in the HTML are empty and need real content:

**`index.html`**
- `<title>` — page title (e.g. "Junyoung Jung")
- `<h1>` — full name
- `.discipline` — e.g. "HCI Researcher · Yonsei University"
- `.tagline` — one sentence positioning statement
- 3× project card: `<span class="project-status">` (Ongoing / Completed), `<h3>` (project title)
- 2× selected works teaser: `.pub-title`, `.pub-meta` (venue + year)
- `.bio` — short bio paragraph
- `<a class="email-link" href="mailto:">` — email address in both `href` and link text
- `<footer><small>` — e.g. "© 2025 Junyoung Jung"

**`publications.html`**
- Each `<li class="pub-entry">`: title, authors, venue, year, PDF link href, DOI link href
- Add or remove `<li>` entries and `<div class="pub-group">` sections as needed

## Infrastructure — Cloudflare Pages setup

Not yet connected. Steps:
1. `dash.cloudflare.com` → Workers & Pages → Create → Pages → Connect to Git
2. Select `junyoungjung99/my-portfolio`
3. Build command: *(empty)*, Output directory: `/`
4. Custom domain: `junyoungjung.com` (auto-configured since domain is on Cloudflare)
5. Also add `www.junyoungjung.com` with a redirect to apex

## Possible future additions (only build when asked)
- Project detail pages
- A CV / résumé PDF link in the nav or about section
- Favicon
- Open Graph meta tags for link previews
- Light/dark mode toggle (discuss first — currently dark-only by design)
