# ktavabi.github.io

Personal landing page built with [Hugo](https://gohugo.io/) and the [Console theme](https://github.com/mrmierzejewski/hugo-theme-console).

## Local development

```
hugo serve
```

Open http://localhost:1313

## Structure

- `content/about/` -- Bio and contact links
- `content/projects/` -- Project catalog (DOC, I-LABS, CHOP, earlier research)
- `content/photos/` -- Photo gallery (page bundles with `type = "gallery"`)
- `content/cv/` -- Full CV with print-optimized PDF generation
- `layouts/` -- Custom homepage, gallery grid, and header overrides
- `static/css/` -- Custom styles (CV layout, gallery grid, print styles)

## Deployment

Pushes to `main` trigger GitHub Actions (`.github/workflows/gh-pages.yml`) which builds with Hugo and deploys to GitHub Pages.
