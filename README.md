# TransitJobs — Veille emploi mobilité 🚌

Application PWA de veille emploi dans les secteurs **transport en commun, mobilité, SIG et cartographie**.

## Fonctionnalités
- Recherche via Claude API (web_search) sur France Travail, APEC, WTTJ, Indeed, LinkedIn
- Filtres : localisation, rayon, salaire minimum, type de contrat, mots-clés
- Sauvegarde des favoris (localStorage)
- Export Excel (3 feuilles : offres, favoris, résumé)
- Installable comme PWA (iOS/Android/Desktop)

## Déploiement
Voir les instructions de déploiement dans votre documentation personnelle.

## Fichiers
- `index.html` — Application complète (HTML/CSS/JS tout-en-un)
- `sw.js` — Service Worker pour le cache offline
- `manifest.json` — Manifeste PWA
- `.nojekyll` — Désactive le traitement Jekyll sur GitHub Pages
