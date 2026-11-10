# Site de Baskapp (GitHub Pages)

Petit site statique : présentation de l'appli, bouton de remerciement PayPal, politique de confidentialité (URL à donner au Play Store). Aucun script, aucun cookie, polices hébergées ici.

## Avant de publier

1. `index.html` : remplacer `TON-IDENTIFIANT` dans le lien PayPal (voir ci-dessous) et relire le texte « Pourquoi Baskapp ? ».
2. `confidentialite.html` : remplacer `[adresse e-mail de contact à compléter]`.

## Lien PayPal

Le plus simple : un lien **PayPal.me** (paypal.com/paypalme → créer son lien), par exemple `https://www.paypal.com/paypalme/baskapp`. Il fonctionne avec un compte personnel, sans code à intégrer.

## Publication

Le dépôt de l'appli étant privé, publier ce dossier dans un **dépôt public séparé** (par ex. `baskapp`) :

1. Créer le dépôt public `baskapp` sur GitHub.
2. Y déposer **le contenu** de ce dossier (`index.html`, `confidentialite.html`, `style.css`, `.nojekyll`, `img/`, `fonts/`) à la racine.
3. *Settings → Pages* : *Deploy from a branch*, branche `main`, dossier `/ (root)`.
4. Le site est en ligne en 1 à 2 minutes : `https://<compte>.github.io/baskapp/`.
5. Play Console : politique de confidentialité = `https://<compte>.github.io/baskapp/confidentialite.html` ; site web de la fiche = `https://<compte>.github.io/baskapp/`.

Tenir `confidentialite.html` à jour avec `docs/politique-de-confidentialite.md`.
