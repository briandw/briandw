# AI & Code — Quarto blog

Static blog for AI/ML engineering, code snippets, and notebook posts.

## Local preview

```bash
brew install quarto
pip install jupyter
quarto preview
```

Open http://localhost:4200 — live reload is built‑in.

## Deployment

Push to `main`; GitHub Actions renders HTML and publishes via GitHub Pages.