# SimpleApp - Gestion des Utilisateurs

Ce projet est une application de gestion des utilisateurs développée en Java avec Spring Boot et MySQL. L'application permet d'ajouter, afficher, et supprimer des utilisateurs en utilisant une base de données MySQL.

## Technologies Utilisées

- **Java** - Langage de programmation
- **Spring Boot** - Framework pour développer des applications Java
- **MySQL** - Système de gestion de base de données relationnelle
- **Thymeleaf (optionnel)** - Moteur de templates pour les vues HTML (si des pages de vues sont incluses)

## Prérequis

Avant de démarrer, assurez-vous d'avoir les outils suivants installés :

- **JDK 17** ou une version compatible de Java
- **Maven** - Pour gérer les dépendances et la compilation
- **MySQL** - Pour la gestion de la base de données
- **Git** - Pour le contrôle de version (si vous clonez depuis GitHub)

## Configuration de la Base de Données MySQL

1. **Créer une base de données MySQL** :

   Connectez-vous à votre instance MySQL et créez une base de données nommée `simpleapp` :

   ```sql
   CREATE DATABASE simpleapp;
