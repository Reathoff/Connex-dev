# Connex — développement

**[Jouer et tester en ligne](https://reathoff.github.io/Connex-dev/)**

Version jouable de développement de Connex. Ce dépôt contient seulement les fichiers statiques nécessaires au jeu.

La version en ligne est servie par GitHub Pages depuis la racine de la branche `main`. Son adresse reste la même lors des mises à jour.

Le jeu comprend son introduction vidéo et son shader fixe, des tenues professionnelles pour Léa et Karim et un contour cyan extérieur pour les objets visés, sans remplissage ni changement de leur couleur. Les superpositions des vêtements et les facettes du costume ont été corrigées ; le décor opaque masque le contour. La carte et les missions sont conservées dans cette version. Three.js r128 est servi sur le même site pour ne pas dépendre d’un CDN au chargement.

Pour une mise à jour, remplacer `index.html` par le jeu reconstruit et conserver la référence locale `./vendor/three.min.js`. Ne pas publier de secrets ni de fichiers de développement privés.

## Bibliothèque tierce

Three.js r128, licence MIT : voir `vendor/LICENSE-three.txt`.
