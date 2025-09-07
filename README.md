# The <span class="notranslate">Future Engine Project</span> — Public Wiki

This repo powers the public wiki at GitHub Pages using **MkDocs Material**.

## Quick Start
1. Install Python 3.x and `pip`.
2. `pip install mkdocs-material`
3. `mkdocs serve`  → open http://127.0.0.1:8000
4. Commit to `main` — GitHub Action deploys to `gh-pages` automatically.
5. In GitHub → Settings → Pages → set Source to **GitHub Actions**.

Optional: add a `CNAME` file at repo root with your domain (`futureengineproject.org`).

## Structure
- `mkdocs.yml` — site config
- `/docs` — markdown content (see `codex/`, `future-history/`, etc.)
- `.github/workflows/deploy.yml` — auto-deploy on push to `main`

---

*The Codex lives under `/docs/codex/`. Future volumes live under `/docs/future-history/YYYY/`.*
