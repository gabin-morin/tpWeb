TP Web : Javascript et HTML5

Description
-----------
Ce dépôt contient un petit projet qui démontre l'utilisation de HTML5 (canvas), CSS et JavaScript pour créer une interaction graphique simple dans le navigateur. Le projet utilise aussi jQuery et Bootstrap pour les styles et quelques utilitaires.

Prérequis
---------
- Un navigateur moderne (Chrome, Firefox, Edge, ...)

Lancer le projet
----------------
- Option simple : ouvrir `canvas.html` directement dans le navigateur (double-clic).

Structure du projet
-------------------
- `canvas.html` : page HTML principale contenant le canevas et les références aux scripts/styles.
- `canvas.css` : styles spécifiques au canevas et à la page.
- `main.js` : point d'entrée JavaScript (initialisation générale).
- `controller.js` : logique de contrôle / gestion des événements.
- `model.js` : modèle de données de l'application.
- `view.js` : affichage et rendu dans le canvas.
- `interaction.js` : gestion des interactions utilisateur dans le canvas.
- `jquery-2.1.3.min.js` : bibliothèque jQuery fournie localement.
- `bootstrap/` : dossier Bootstrap contenant `css/`, `fonts/` et `js/` (pour le style et les composants UI).

Notes d'utilisation
-------------------
- Le code est conçu en MVC : il est structuré en fichiers séparés (`model`, `view`, `controller`) pour faciliter la compréhension.
- Pour modifier le comportement ou ajouter des fonctionnalités, commencez par `model.js` pour la logique, `controller.js` pour les interactions, et `view.js` pour l'affichage.

Ajout du fork
-------------
Ce projet est un fork, il ajoute les fonctionnalités de base du TP, telles que la possibilité de choisir entre 2 formes (ligne, rectangle), de choisir leur couleur, puis de les dessiner sur un canvas.
Ce fork ajoute finalement un historique des formes dessinées à droite, avec la possibilité de les supprimer.