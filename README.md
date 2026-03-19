# Market Segmentation in Python — Quarto Website

This repository is a small Quarto website prepared for GitHub Pages.

## Files

- `index.qmd` — landing page
- `tutorial.qmd` — full synthetic-data tutorial
- `deployment.qmd` — GitHub Pages and Shinylive notes
- `shinylive_demo.qmd` — starter interactive page pattern
- `_quarto.yml` — site configuration
- `.github/workflows/publish.yml` — GitHub Pages workflow

## Local use

```bash
quarto preview
```

## Render the site

```bash
quarto render
```

The rendered site will be written to `docs/`.

## Optional browser-side interactivity

```bash
quarto add quarto-ext/shinylive
```

Commit the resulting `_extensions/` directory if you use the extension.
