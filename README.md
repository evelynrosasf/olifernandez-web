# Olivier Fernández — website

Static website for Olivier Fernández, bean-to-bar chocolate maker (Barcelona). Plain HTML and CSS, no build step. Ready for GitHub Pages.

## Pages

| File | Page |
|---|---|
| `index.html` | Home (minimal menu, scroll animations) |
| `about.html` | About Olivier |
| `consulting.html` | Consulting |
| `projects.html` | Projects |
| `training.html` | Training & talks |
| `contact.html` | Contact form |

Assets live in `assets/`: self-hosted fonts (`assets/fonts/`, woff2), photos (`assets/img/`) and the Oli favicon.

## Publish with GitHub Pages

1. Repository **Settings → Pages**.
2. **Source:** Deploy from a branch. **Branch:** `main`, folder `/ (root)`. Save.
3. The site appears at `https://evelynrosasf.github.io/olifernandez-web/` after a minute or two.
4. Custom domain (optional): add it under **Settings → Pages → Custom domain** and point the domain's DNS to GitHub Pages.

All links and asset paths are relative, so the site works both under `/olifernandez-web/` and on a custom domain.

## Before going live

Search the code for `PLACEHOLDER` and `data-placeholder` to find everything still pending:

- **Professional email and social links** (footer, contact page, menu).
- **Contact form endpoint.** GitHub Pages can't process forms. In `contact.html`, set the `<form action="#">` to a form service (for example Formspree or Basin) and add an anti-spam measure.
- **Project roles and permissions** (projects page): role and scope for each project, name and permission for the origin project, a photo of 97-12º.
- **Talk history** (training page): events where "From Bean to Business" has been given, confirmed by the organiser.
- **Legal pages:** legal notice (LSSI-CE), privacy policy (GDPR) and cookie policy. The footer and form currently link to `#`. Texts should be reviewed by a lawyer or gestor.

## Notes

- Fonts: Archivo, Inter, IBM Plex Mono and Instrument Serif (SIL Open Font License), subset to Latin.
- Scroll animations use CSS scroll-driven animations (Chrome, Edge and other Chromium browsers; other browsers show the static layout). Animations are switched off for visitors who prefer reduced motion.
