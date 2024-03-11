# Test technique SNU - Mars 2024

## Corrections apportées
- Correction du problème d'enregistrement du nom lors de la creation manuelle d'un utilisateur
- Modification du comportement du bouton "update" lors de la mise à jour d'un compte utilisateur : onChange => onClick
- Correction de l'erreur empéchant d'accéder au contenu d'un projet : la variable project est un tableau contenant un objet. il n'était donc pas possible d'afficher les valeurs des propriétés directement. Solution choisi :  setProject(projectData[0])
- Amélioration de l'expérience utilisateur en ajoutant un X pour fermer les modales "Create new project" & "Create new user"
- Correction du filtre par projet sur la page listant les activités
- Correction du bouton edit d'un projet. Ajout de la possibilité d'éditer les informations d'un projet
- Mise jour à de la list des projets après la création d'un nouveau.


## Setup api
- cd api
- Run `npm i`
- Run `npm run dev`

## Setup app

- cd app
- Run `npm i`
- Run `npm run dev`


