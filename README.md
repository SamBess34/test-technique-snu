# Test technique projet SNU - Mars 2024

## Lien vers le test technique original :
[selego/technical-test-4](https://github.com/selego/technical-test-4)

## Corrections apportées
- Correction du problème d'enregistrement du nom lors de la creation manuelle d'un utilisateur
- Modification du comportement du bouton "update" lors de la mise à jour d'un compte utilisateur : onChange => onClick
- Correction de l'erreur empéchant d'accéder au contenu d'un projet : la variable project est un tableau contenant un objet. il n'était donc pas possible d'afficher les valeurs des propriétés directement. Solution choisi :  setProject(projectData[0])
- Amélioration de l'expérience utilisateur en ajoutant un X pour fermer les modales "Create new project" & "Create new user"
- Correction du filtre par projet sur la page listant les activités
- Correction du bouton edit d'un projet. Ajout de la possibilité d'éditer les informations d'un projet
- Mise jour à de la list des projets après la création d'un nouveau.

## Nouvelle Fonctionnalité : Exportation des données au format CSV
- Ajout de la possibilité d'exporter son activité mensuelle sur un ou plusieurs projets au format csv.

## Feedback à propose du code et difficultés rencontrées
- Pour être honnête, je n'ai pas rencontré de problème majeur pour comprendre l'intégralité du projet. Les premières heures ont été consacrées à la revue du code. Même si, parfois, les commentaires faisaient défaut, le code était globalement lisible. Comme je n'ai effectué aucune modification du côté du back-end durant ce test, j'ai néanmoins été tenté de modifier les contrôleurs. J'ai pour habitude de créer mes routes dans un ou plusieurs fichiers router et de les relier à mes contrôleurs pour une meilleure lisibilité. J'ai cependant observé des similitudes dans l'architecture avec ce que je propose lors de la création de mes projets.

## Setup api
- cd api
- Run `npm i`
- Run `npm run dev`

## Setup app

- cd app
- Run `npm i`
- Run `npm run dev`


