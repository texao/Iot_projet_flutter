# TP1 : Création d'Interfaces Graphiques en Flutter

## Objectif
Le but de ce TP est de se familiariser avec la création d'interfaces graphiques en Flutter en utilisant des widgets stateless et stateful.



## Prérequis
- **Flutter** : SDK installé.
- **Android Studio** : environnement de développement configuré.
- **Dart** : langage utilisé pour développer l'application.
- **GitHub** : Télécharger le code source depuis le lien suivant qui est aussi sur le rraport :  
  [Code source sur GitHub](https://github.com/texao/Flutter_tp1)  
  

## Utilisation
1. Dézipper le projet.
2. Ouvrir les dossiers sur Android Studio :
   - Le projet nommé **"profil.zip"** correspond à l'application **profil**.
   - Le dossier nommé **"quizz.zip"** correspond à l'application **quizz**.
3. Exécuter les applications en cliquant sur **Run**.



## Contenu du Projet
Ce projet est composé de deux exercices principaux :

### 1. Profile Card
- Une application Flutter affichant le profil d'une personne.
- Le profil inclut :
  - Un avatar (photo de profil).
  - Les informations personnelles (nom, prénom, email, réseaux sociaux, etc.).
- Les widgets utilisés comprennent :
    - **Scaffold** : pour une structure de page avec une barre d'application.
    - **Card** : pour afficher les informations personnelles dans une structure.
    - **Column** et **Row** : pour organiser les widgets verticalement et horizontalement.


### 2. Quizz
- Une application Flutter permettant de répondre à des questions.
- Les fonctionnalités incluent :
- Un quizz avec des questions et des réponses (modélisées avec la classe `Question`)
- Un **stateful widget** pour gérer l'état des réponses.
  - Les widgets principaux :
    - **Scaffold** : pour la structure de la page.
    - **setState** : pour gérer dynamiquement les changements dans le quizz.
