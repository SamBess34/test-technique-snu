# Test technique SNU - Mars 2024

## Corrections apportées
- Correction du problème d'enregistrement du nom lors de la creation manuelle d'un utilisateur
- Modification du comportement du bouton "update" lors de la mise à jour d'un compte utilisateur : onChange => onClick
- Correction de l'erreur empéchant d'accéder au contenu d'un projet : la variable project est un tableau contenant un objet. il n'était donc pas possible d'afficher les valeurs des propriétés directement. Solution choisi :  project[0].propriety
- Amélioratation de l'expérience utilisateur en ajoutant un X pour fermer la modale "Create new project" 



## Setup api
- cd api
- Run `npm i`
- Run `npm run dev`

## Setup app

- cd app
- Run `npm i`
- Run `npm run dev`


