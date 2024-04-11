# Application de gestion d'agenda en Svelte de Doriane Vautor, Laura Kokonyange-Nkasei, Ketchuskana Son Essome Moukouri

Réaliser un agenda simple développé en Svelte pour gérer les événements et les tâches quotidiennes.

## Sommaire

- [Installation](#installation)
- [Utilisation](#utilisation)
- [Fonctionnalités](#fonctionnalités)
- [Repartition des taches](#repartition-des-taches)

## Installation

1. Décompresser le projet et l'ouvrir dans son environnement de code
2. Dans un terminal, la commande "npm install" pour installer les dépendances
3. La commande "npm run dev" pour démarrer l'application en mode développement

## Utilisation

Après avoir lancé l'application en mode développement, ouvrez votre navigateur et accédez à l'URL http://localhost:port pour voir l'agenda.

## Fonctionnalités

- **Gestion d'événements**

    - Les utilisateurs peuvent ajouter de nouveaux événements à leur agenda.
    - Ils peuvent aussi spécifier le titre, la date de début et de fin, la couleur et une description pour chaque événement.
    - Il y a également la possibilité de modifier les détails d'un événement existant, y compris le titre, les dates, la couleur et la description.
    - La suppression d'événements est également prise en charge pour supprimer des événements de l'agenda.

- **Navigation dans l'agenda**

    - Permet aux utilisateurs de naviguer facilement entre les différents mois et années de l'agenda.
    - Affichage des événements planifiés pour chaque jour sélectionné dans l'agenda.


- **Stockage local des événements**

    - Les événements ajoutés par les utilisateurs sont stockés localement dans le navigateur à l'aide du stockage local (localStorage).
    Cette méthode permet à l'application de conserver les événements même après la fermeture et la réouverture de l'application.

- **Gestion des UR**

    - Utilisation d'un système de routage pour gérer les URL et permettre la navigation directe vers des vues spécifiques de l'agenda.

- **Tests unitaires**

    - Mise en place de tests unitaires pour les différentes fonctionnalités de l'application afin d'assurer leur bon fonctionnement et leur stabilité.

## Repartition des taches 

Nous étions une équipe de trois personnes a travaillé sur ce projet d'agenda en Svelte. Voici la répartition des tâches et ce que chacun a réalisé :

- **Doriane** :
  - Conception et développement de l'interface utilisateur avec Svelte.
  - Intégration de la navigation entre les pages et gestion des URL. 
  - Mise en place du stockage local des événements.
  - Développement de la fonctionnalité d'ajout d'événements.
  - Tests unitaires pour les fonctionnalités implémentées.

- **Laura** :
  - Conception et développement de l'interface utilisateur avec Svelte.
  - Implémentation de la fonctionnalité de suppression d'événements.
  - Mise en place et développement du composant d'ajouts d'événements.
  - Tests unitaires pour les fonctionnalités implémentées.
  - Rédaction du README.

- **Ketchuskana** :
  - Conception et développement de l'interface utilisateur avec Svelte.
  - Développement de la fonctionnalité d'affichage de l'évenement à sa date dans l'agenda
  - Tests unitaires pour les fonctionnalités implémentées.
  - Optimisation du style de l'agenda.
  
