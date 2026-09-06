# rajesh-pushparaj.github.io

Personal academic website (robotics / perception / machine learning), built as a plain
static site for GitHub Pages &mdash; no build step, no framework.

## Pages

- `index.html` &mdash; home (banner, portrait, letter, "Currently", contact)
- `projects.html` &mdash; open-source projects and datasets
- `publications.html` &mdash; publications grouped by year
- `updates.html` &mdash; short news items, newest first
- `writing.html` &mdash; essays and posts
- `style.css` &mdash; shared stylesheet (design tokens at the top)

## Before publishing

All copy is placeholder (name, letter, publications, links, etc.) &mdash; replace it with
real content in each `.html` file.

Both images are placeholder SVGs in `assets/`; swap them for real files and update the
`src` attributes:
- `assets/banner-placeholder.svg` &rarr; a landscape photo, ~2400px wide (`index.html`)
- `assets/portrait-placeholder.svg` &rarr; a color portrait, ~720&times;900 (`index.html`,
  rendered grayscale via CSS)
