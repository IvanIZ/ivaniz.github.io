# ivaniz.github.io

Ninghan Zhong's academic website, built with [al-folio](https://github.com/alshedivat/al-folio) v1 (Jekyll). Every push to `main` builds and deploys the site through `.github/workflows/deploy.yml`.

## Where things live

| What | Where |
| --- | --- |
| Bio | `_pages/about.md` |
| Role line, contact links, research groups, experience, awards, service | `_data/home.yml` |
| Papers (homepage rows and the Publications page) | `_bibliography/papers.bib` |
| News items, one file each | `_news/` |
| Research clips (`.mp4` plus a `.jpg` poster of the same name) | `assets/video/research/` |
| Research figures | `assets/img/research/` |
| Institution logos | `assets/img/logos/` |
| CV (the nav "CV" link opens it) | `assets/pdf/cv.pdf` |
| Style: a, b or c | `site_style` in `_config.yml` |

## Add a paper

1. Add a BibTeX entry to `_bibliography/papers.bib`. For the homepage, give it a `theme` (`vla`, `contact` or `hri`), a one-line `tldr`, comma-separated `tags`, and `media` with `media_size`. Links go in `website` (project page), `pdf` (paper), `arxiv` (ID only) and `code`.
2. Put its clip and poster in `assets/video/research/`, or an image in `assets/img/research/`. Keep clips short (about 10 s), muted and under 2 MB.

## Add a news item

Create `_news/YYYY-MM-short-name.md`:

```markdown
---
date: 2026-10-01
inline: true
---

One line of Markdown, with [links](https://example.com) if needed.
```

The homepage shows the five newest items.

## Local changes to al-folio

The site overrides one core file and adds its own layouts and styles. al-folio's `test/style_contract.js` flags these, so its unit-test workflow is removed.

- `assets/css/main.scss`: the core file plus one `@use "nz"` line
- `_sass/_nz.scss`: style tokens for options a, b and c, and the homepage styles
- `_layouts/home.liquid`: the homepage
- `_layouts/research_row.liquid`: one research row (a jekyll-scholar template)
- `_layouts/redirect_now.liquid`: the instant redirect behind the CV nav link
