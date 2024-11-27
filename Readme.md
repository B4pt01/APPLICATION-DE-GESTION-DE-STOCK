# Projet de Gestion de Stock - NEGOSUD

## Description

Ce projet est une application de gestion de stock pour **NEGOSUD**, un négociant en vin en Gascogne. L'objectif est de développer un système permettant de gérer les stocks de produits (vins, digestifs, etc.), les commandes fournisseurs et clients, ainsi que les inventaires. L'application inclura une interface back-office pour gérer les stocks et une interface front-end pour permettre aux clients de commander en ligne.

## Statut du Projet

### 🟡 **En Cours**

Le développement est en cours. Voici l'état actuel des fonctionnalités et tâches :

### Fonctionnalités Principales

- **Gestion des Stocks** :  
  ✔️ **Terminé pour les produits** : Ajout, modification et suppression de produits.  
  🔄 **En cours** : Gestion des stocks (ajouter/supprimer des quantités, réapprovisionnement automatique).
- **Gestion des Fournisseurs** :  
  ✔️ **Terminé** : Création et gestion des fournisseurs, lien avec les produits.

- **Gestion des Commandes** :  
  🔄 **En cours** : Création de commandes clients, gestion automatique des commandes fournisseurs en cas de stock insuffisant.  
  🚧 **En attente** : Génération automatique de bons de commande fournisseurs lors du passage de commandes clients.
- **Gestion de l'Inventaire** :  
  🔄 **En cours** : Interface permettant d'ajuster les quantités d'inventaire manuellement.  
  🚧 **En attente** : Fonctionnalité d'inventaire en masse.

- **API Back-End** :  
  ✔️ **Terminé** : Mise en place de l'API avec les routes pour la gestion des produits, commandes et fournisseurs.  
  🔄 **En cours** : Sécurisation avec JWT et gestion des autorisations.  
  🚧 **En attente** : Tests d'intégration et amélioration des performances.

- **Interface Front-End (Site Web)** :  
  ✔️ **Terminé** : Structure de base du site e-commerce (catalogue de produits).  
  🔄 **En cours** : Affichage des détails de chaque produit et panier d'achats.  
  🚧 **En attente** : Intégration du processus de commande (paiement, validation de commande).

### Documentation

- **API** : Documentation de l'API en cours avec Swagger. Des informations sur chaque route (création de produits, gestion des commandes, etc.) seront disponibles à la fin de cette phase.
- **Code** : Le code est actuellement versionné sur GitHub. Les commentaires sont ajoutés au fur et à mesure du développement pour assurer une bonne lisibilité.

### Déploiement

- **Back-End** : Le back-end est en phase de test sur un serveur local. Une fois les tests terminés, il sera déployé sur un serveur distant.
- **Front-End** : Le site web est en cours de développement en local. La mise en ligne est prévue après l'intégration des fonctionnalités de commande.

### Prochaines Étapes

1. Terminer la gestion des stocks et du réapprovisionnement automatique.
2. Finaliser l'intégration du panier et de la commande client.
3. Tester l'intégration entre le front-end et l'API.
4. Effectuer une révision de la sécurité, en particulier pour l'authentification via JWT.
5. Préparer la mise en production du système et déployer sur les serveurs.

---

## Installation

Pour installer et tester l'application localement, suivez ces étapes :

1.  Clonez le repository :
    ```bash
    git clone https://github.com/B4pt01/Projet-cube-APPLICATION-DE-GESTION-DE-STOCK.git
    ```
2.  Installez les dépendances pour le back-end :

    ```bash
    cd back-end
    dotnet restore
    dotnet build
    ```

3.  Installez les dépendances pour le front-end (si vous utilisez un framework comme React ou Vue) :

    ```bash
    cd front-end
    npm install

    ```

4.  Démarrez l'API et le front-end en local :

    API : dotnet run (pour back-end en ASP.Net)
    Front-End : npm start (pour front-end React ou Vue)

---

## Contribuer

    Si vous souhaitez contribuer au projet, veuillez créer une branche, faire vos modifications et soumettre une pull request. Toute suggestion ou amélioration est la bienvenue !

---

## Auteurs :

    Nom de l'auteur principal - Développeur FullStack - B4pt_02
