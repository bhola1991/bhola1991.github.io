# Portfolio

Five pages, one stylesheet, no build step.

```
index.html          hero + tile grid
janata-bazar.html   the flagship
job-triage.html     the software
panee.html          agri-tech
writing.html        blockchain writing + film & theatre
assets/style.css    all styling
```

## Put it online

1. New GitHub repo named `yourusername.github.io` — the name is what gives you the clean URL.
2. Upload everything, keeping `assets/` as a folder.
3. Settings → Pages → Deploy from a branch → `main` → `/ (root)`. Save.
4. Live at `https://yourusername.github.io` in a minute or two.

## Fill these in first — 7 placeholders

Search for `data-todo`. They render with dashed borders so you can't miss them.

**index.html** — email, LinkedIn, GitHub. The site is useless without these.

**janata-bazar.html** — Facebook URL, and the systems write-up.

That write-up is the highest-value thing on this list. A thousand words: what the operation looked like before, what broke, what you built, what you got wrong the first time, what staff actually did with it versus what you expected. Add it as `janata-systems.html` and link it. For the roles you're chasing this beats a code repo — nobody reads strangers' code, everyone reads a real problem and how software survived it.

**job-triage.html** — repo link. Push it with a README explaining why fit and reachability are separate axes, and why it reads ATS feeds instead of scraping. That reasoning is your interview answer.

**writing.html** — three best pieces. Three, not everything.

## Editing

Colours are four variables at the top of `assets/style.css`:

```css
--run:#2C6E49;    /* green: operations, what you run */
--build:#C87F1E;  /* ochre: systems, what you built */
```

These do structural work — the headline underlines, column headers, list markers, tile backgrounds. Change both together and keep them clearly distinct.

**Adding a project:** copy a tile in `index.html`, copy `panee.html` as the page. Keep the two-column run/build split — it's the argument the site exists to make.

**Adding a nav item:** it's in the `<header>` of all five pages. Update each one.
