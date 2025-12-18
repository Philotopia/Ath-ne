# Ath-ne (site statique)

Ce dossier est prêt à être **commit** sur GitHub pour GitHub Pages.

## Structure
- `index.html` : site (React UMD + Babel + Tailwind CDN)
- `data/tripPlan.json` : planning (modif “partagée” via commit)
- `assets/photos/` : images locales (placeholders SVG à remplacer par tes vraies photos)

## Déploiement GitHub Pages
1. Commit/push sur `main`
2. Repo → **Settings** → **Pages**
3. Source: **Deploy from a branch**
4. Branch: `main` • Folder: `/ (root)`

Le site sera servi sous: `https://<user>.github.io/<repo>/`

## Modifier le planning
- Dans l’onglet **Planning**, clique **Exporter JSON**, puis remplace `data/tripPlan.json` dans le repo, commit, push.
- Tu peux aussi activer une **surcharge locale** (localStorage) pour tester sans impacter le fichier repo.
