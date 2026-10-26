# Site Nij e Barzh — Hugo + Blowfish

Site statique du club de modélisme indoor de Plouvien (Finistère).

## Structure
- `content/` — pages et articles
- `content/modeles/` — fiches des avions du club
- `content/docs/` — pages de téléchargement des PDF
- `static/pdf/` — les PDF (copiés tels quels)
- `static/images/` — photos des galeries
- `static/CNAME` — domaine personnalisé nij-e-barzh.fr

## Démarrage local
```
hugo mod get github.com/nunocoracao/blowfish/v2
hugo server
```

## Déploiement
Push sur `main` : le workflow construit et publie automatiquement.
Réglages GitHub : Settings → Pages → Source: GitHub Actions.
