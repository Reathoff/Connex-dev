# Connex — version de développement

[Jouer](https://reathoff.github.io/Connex-dev/)

Base restaurée juste après les shaders fixes, avec Léa en sweat violet, jean et baskets, et le bouton Plein écran à l’accueil et dans le menu pause.

Le magasin est à l’avant d’un quartier jouable : la porte « Réservé au personnel » mène à l’arrière-boutique (réserve, livraisons, pause, sécurité, vestiaire), puis à la cour et à la ville : rues, place, jardin, commerces, quatre repères et une maquette 3D du quartier qui ouvre la fin bonus B2 « La ville dans la ville ». Rendu sobre et réaliste, sans pancarte bleue.

Nouveau : le quartier est vivant. Façades, toits, rues et pavés ont de vraies matières ; le soleil, les nuages et (sur ordinateur) les ombres portées donnent du relief ; des passants marchent ou sont assis, des pigeons s’envolent quand on approche ; vent, oiseaux, voitures lointaines et pas selon le sol rythment la balade. Maj pour courir dehors, M (ou le bouton 🗺) pour le plan de la ville ; l’arrière-boutique gagne ses détails d’usage.

Aucune fin n’est retirée : les fins 1 à 10 et B1 gardent leurs conditions, et la mission reste les cinq tâches d’origine. Karim, visages, coiffures, règles, shaders et vidéos inchangés.

Three.js r128 est fourni dans `vendor/`. Le dépôt principal reste privé.

## Collisions corrigées

Chaises et lampadaires solides, fauteuils et bancs aux bonnes dimensions, glissement aux coins et déplacements sécurisés même en course. Les 20 salles, quêtes, accès infrarouges, dix fins principales et deux bonus ont été revérifiés sur ordinateur et téléphone émulé (376 contrôles navigateur et 26 tests Python). Les sauvegardes, dialogues, vidéos et shaders sont conservés. Pas de test sur un vrai téléphone ni de benchmark matériel.
