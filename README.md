# NBS — Lecture du matin

Site statique des briefings quotidiens NBS. Les pages sont conçues pour une lecture confortable sur iPhone, iPad et ordinateur.

## Publication GitHub Pages

1. Ouvrir **Settings → Pages** dans ce dépôt.
2. Dans **Build and deployment**, choisir **GitHub Actions** comme source.
3. Le workflow `.github/workflows/pages.yml` publiera automatiquement le site à chaque mise à jour de la branche `main`.

Le dépôt ne contient que les pages HTML destinées à la lecture publique. Le dépôt personnel `second-brain` reste séparé et privé.

## Ajouter une édition

Ajouter un fichier HTML dans `briefings/`, puis ajouter son lien dans `index.html`.
