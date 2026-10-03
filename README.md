# Cloud Native Abidjan — Community Docs

Documentation publique de Cloud Native Abidjan, publiée avec MkDocs Material et GitHub Pages.

## UX principles

- contenu court et orienté action ;
- une seule action principale par écran ;
- images dans l’ordre exact du parcours ;
- toutes les ressources externes sont cliquables ;
- affichage mobile-friendly ;
- captures zoomables ;
- pas de contenu administratif inutile.

## Local development

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
mkdocs serve
```

Puis ouvrir http://127.0.0.1:8000

## Publication

Les changements poussés sur `main` sont automatiquement construits et publiés sur GitHub Pages.
