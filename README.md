# Coach 12 semaines

Application web de suivi du programme d'entraînement 12 semaines.
Fonctionne hors ligne, données stockées localement sur l'appareil, aucune requête réseau.

## Publication (GitHub Pages)

1. Créer un dépôt (privé ou public) et y déposer le contenu de ce dossier à la racine.
2. Settings → Pages → Source : `Deploy from a branch` → branche `main`, dossier `/ (root)`.
3. Attendre ~1 min. L'URL est `https://<utilisateur>.github.io/<depot>/`.

## Installation sur iPhone

Ouvrir l'URL dans **Safari** (pas Chrome — l'ajout à l'écran d'accueil est réservé à Safari sur iOS),
bouton Partager → « Sur l'écran d'accueil ».

L'app s'ouvre alors en plein écran, sans barre d'adresse, et fonctionne sans réseau.

## Fichiers

- `index.html` — application complète (HTML + CSS + JS, aucune dépendance)
- `manifest.webmanifest` — métadonnées PWA (nom, icônes, mode plein écran)
- `sw.js` — service worker, mise en cache pour le hors-ligne
- `icon-*.png` — icônes d'écran d'accueil

## Sauvegarde

Les données sont dans le stockage local du navigateur. Réglages → « Exporter une sauvegarde »
produit un fichier JSON réimportable. À faire de temps en temps.
