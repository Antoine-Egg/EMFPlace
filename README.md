# EMF-JPO-2023

EMF/Place est une application web inspirée de r/place, qui permet aux utilisateurs de collaborer pour créer une toile pixelisée en temps réel.

![Capture d'écran de EMF/Place](https://eggera.emf-informatique.ch/emfplace1.png)

## Fonctionnalités

- **Toile Pixelisée Collaborative** : Les utilisateurs peuvent placer des pixels sur une toile pixelisée partagée en temps réel.
- **Choix de Couleurs** : Choisissez parmi une palette de couleurs pour dessiner.

## Comment Utiliser

1. **Sélection de Couleur** : Choisissez la couleur que vous souhaitez utiliser pour dessiner.

3. **Placement de Pixels** : Cliquez sur la toile pour placer des pixels de la couleur sélectionnée.

## Technologies Utilisées

- **Frontend** : HTML, CSS, JavaScript (Framework : [jQuery](https://jquery.com/))
- **Backend** : PHP
- **Base de Données** : MySQL


## Reprise du projet

- Importer le fichier sql pour avoir la base de données utilisation (Attention création du schéma inclus)
- Modifier les configuration de la base de donnée dans le fichier ``server/wrk/config.php``

## Axes d'amélioration

- Optimisation des requêtes
- Système d'historique avec des comptes
- Cooldown pour les pixels
- Accès a la page admin plus simple

## Page admin

Pour accèder a la page admin il faut executer ``wrk.login('Password')`` sur la page de la toile. Le mot de passe de trouve dans le fichier ``server/requestHandler.php``
