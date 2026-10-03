# Cloud Native Abidjan — Community Docs

Documentation publique de Cloud Native Abidjan, publiée avec MkDocs Material et GitHub Pages.

## Local development

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
mkdocs serve
```

Puis ouvrir `http://127.0.0.1:8000`.

## Publication

Les changements poussés sur `main` sont automatiquement construits et publiés sur GitHub Pages via GitHub Actions.

## Structure

- `docs/index.md` — point d'entrée
- `docs/join-community.md` — guide pour rejoindre CNA
- `docs/events.md` — événements et formats
- `docs/community.md` — présentation de la communauté
- `docs/assets/images/` — captures d'écran
- `docs/assets/stylesheets/extra.css` — personnalisation visuelle
