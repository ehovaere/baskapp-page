# Site de Baskapp (GitHub Pages)

Petit site statique : présentation de l'appli, bouton de remerciement PayPal, politique de confidentialité (URL à donner au Play Store). Aucun script, aucun cookie, polices hébergées ici.

## Avant de publier

1. `index.html` : lien PayPal renseigné ; relire le texte « Pourquoi Baskapp ? ».
2. `confidentialite.html` : adresse e-mail de contact renseignée (la même que dans `docs/politique-de-confidentialite.md`).

## Lien PayPal

Le bouton « Me dire merci » de `index.html` utilise un lien de don PayPal (`paypal.com/donate/?business=…`). Pour le changer, remplacer l'adresse du lien `btn-paypal`. Rappel : ce lien ne doit jamais apparaître dans l'appli, ni dans `confidentialite.html`.

## Publication

Le dépôt de l'appli étant privé, publier ce dossier dans un **dépôt public séparé** (ici `baskapp-page`) :

1. Créer le dépôt public `baskapp-page` sur GitHub.
2. Y déposer **le contenu** de ce dossier (`index.html`, `confidentialite.html`, `style.css`, `.nojekyll`, `img/`, `fonts/`) à la racine.
3. *Settings → Pages* : *Deploy from a branch*, branche `main`, dossier `/ (root)`.
4. Le site est en ligne en 1 à 2 minutes : `https://ehovaere.github.io/baskapp-page/`.
5. Play Console : politique de confidentialité = `https://ehovaere.github.io/baskapp-page/confidentialite.html` ; site web de la fiche = `https://ehovaere.github.io/baskapp-page/`.

**Important** : `confidentialite.html` est la seule page ouverte depuis l'appli (Réglages → À propos). Elle ne doit contenir **aucun lien** vers l'accueil ou le don : Google Play interdit qu'une appli mène, même indirectement, vers un paiement hors de son système (les dons au développeur compris).

Tenir `confidentialite.html` à jour avec `docs/politique-de-confidentialite.md`.
