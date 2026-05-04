# nijkah.github.io

Personal academic homepage for Hakjin Lee — Research Engineer at PIT IN Corp. Hand-coded static site (HTML + CSS), no build step.

## Run locally

```sh
python3 -m http.server 8000
```

Open `http://localhost:8000`.

## Edit the content

- **Add a publication** — open `index.html`, copy a `<div class="research-proj">…</div>` block inside `#publications`, and update the title, authors, venue, links, and `images/<thumb>.png`.
- **Add a news item** — add an `<li>` to `#news`.
- **Add a project card** — copy a `.project-card` block inside `.projects-grid`.
- **Replace photos** — drop a real headshot at `images/profile.jpeg` and project thumbnails under `images/`.

## Deploy

This repo is published by GitHub Pages from `master`. Pushing the root files is enough; the `.nojekyll` file disables Jekyll processing.
