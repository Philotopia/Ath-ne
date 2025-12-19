# Ath-ne (GitHub Pages)

Site statique (un seul `index.html`) prêt à commit sur GitHub Pages.

## Points clés
- **Photos réelles** : chargées depuis **Wikipedia** (API REST) à partir d'un `wikiTitle` par lieu.
- **Planning utilisable** : vue **Agenda par jour** (pas de timeline), édition via formulaire, import/export JSON.

## Déploiement
Repo → Settings → Pages → Deploy from a branch → `main` + `/(root)`

URL : `https://<user>.github.io/<repo>/`

## Modifier le planning
- Onglet **Planning** → boutons **Importer / Exporter**.
- Pour partager à tout le monde : export → remplacer `data/tripPlan.json` → commit/push.

## Remarque photos (licences)
Les miniatures viennent de Wikipedia/Commons. Dans chaque carte, le lien "Photo : Wikipedia" pointe vers la page source.
