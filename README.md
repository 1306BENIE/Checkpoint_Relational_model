# Gestion des Hôtels - Modèle Relationnel
## Introduction
Ce projet vise à modéliser une base de données relationnelle pour la gestion des hôtels dans une zone touristique. En s'appuyant sur le modèle entité-relation fourni, nous avons conçu un diagramme relationnel qui optimise l'organisation des données et facilite leur exploitation.

## Objectif
Structurer et normaliser les informations des hôtels.

Définir les relations entre les différentes entités **(Hôtel, Employé, Chambre, Type, Catégorie)**.

Assurer la cohérence et l'intégrité des données.

## Outils utilisés
**Looping** : Conception du modèle relationnel.

**SQL** : Génération des tables pour implémentation future.

## Structure du Modèle Relationnel
Le modèle relationnel repose sur les entités suivantes :

**Type** : Définit les types d'hôtels.

**Category** : Spécifie les catégories des chambres (prix, nombre de lits).

**Hotel** : Contient les informations des hôtels avec leur type.

**Room** : Liste les chambres en lien avec un hôtel et une catégorie.

**Employee** : Gère les employés et leurs affectations aux hôtels.

## Contenu du projet
### Capture du modèle relationnel (relational_model.png)

### Script SQL à générer (non inclus dans ce dépôt)

# Installation et Utilisation
Ouvrir le fichier relational_model.png pour visualiser la structure relationnelle.

Utiliser un SGBD (MySQL, PostgreSQL, etc.) pour créer les tables en suivant la structure définie.

## Remarque
Ce projet peut être étendu pour intégrer des fonctionnalités supplémentaires telles que la gestion des réservations et des clients.

## 👨‍💻 Auteur
 **BENIE SYLVESTRE**