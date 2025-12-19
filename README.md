# Ath-ne (GitHub Pages)

Site statique (un seul `index.html`) prêt à commit sur GitHub Pages.

## Onglets
- 🏛️ **Lieux** (cartes, mythe/philo, activité, liens Maps + site)
- 🗓️ **Planning** (agenda par jour, édition, import/export JSON)
- 🗺️ **Carte** (Leaflet)
- 🍷 **Vie pratique**
- 📸 **Défi photo** (stockage local)

## Photos
Les photos des lieux sont chargées automatiquement depuis Wikipedia (API REST).
Chaque carte inclut un lien “Photo : Wikipedia” vers la page source (où se trouvent auteur/licence).

## Déploiement GitHub Pages
Repo → Settings → Pages → Deploy from a branch → `main` + `/(root)`

## Modifier le planning
- Onglet **Planning** → **Exporter** → remplace `data/tripPlan.json` par le fichier exporté → commit/push
- **Importer** applique une surcharge **locale** (localStorage) sans toucher au repo.

