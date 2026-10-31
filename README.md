# Connex — développement

**[Jouer et tester en ligne](https://reathoff.github.io/Connex-dev/)**

Version jouable de développement de Connex. Ce dépôt contient seulement les fichiers statiques nécessaires au jeu.

La version en ligne est servie par GitHub Pages depuis la racine de la branche `main`. Son adresse reste la même lors des mises à jour.

Le local comprend le magasin au rez-de-chaussée, une vraie réserve pour les trois cartons, un dégagement et un escalier vers les bureaux du personnel. Chaque espace a une utilité : documents d’ouverture, suivi de la vitrine et des prix, café à préparer puis boire, chat à caresser, cour avec pause cigarette et cendrier. Les pauses sont facultatives et la cigarette ne donne aucun bonus. L’escalier change de salle par une transition, selon le moteur du jeu.

Pour ouvrir : ranger C1, C2 et C3, un à la fois, terminer caisse, enseigne, vitrine et prix, puis utiliser la porte d’entrée du magasin au RDC. L’ouverture conserve la fin narrative existante ; il n’y a pas de nouvelle simulation de clientèle. Les accès du directeur, du couloir et de la petite porte sont conservés.

L’introduction vidéo à chaque tentative, le shader fixe sans réglage de menu, les tenues professionnelles et le contour cyan extérieur sont conservés. Three.js r128 est servi sur le même site, sans CDN au chargement.

Pour une mise à jour, remplacer `index.html` par le jeu reconstruit et conserver la référence locale `./vendor/three.min.js`. Ne pas publier de secrets ni de fichiers de développement privés.

## Bibliothèque tierce

Three.js r128, licence MIT : voir `vendor/LICENSE-three.txt`.
