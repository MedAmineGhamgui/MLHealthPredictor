# Prédiction des Maladies Cardiovasculaires et du Diabète

## Description

Ce projet vise à créer une application web pour prédire si une personne est atteinte de maladies cardiovasculaires ou de diabète en fonction de divers facteurs tels que le poids, la pression artérielle, le tabagisme, et l'âge. Le système est construit en utilisant Angular pour le front-end, FastAPI pour le back-end, et intègre des pratiques DevOps (Jenkins, Docker), ainsi que des outils MLOps (Dagshub) et de visualisation de données (Power BI).

## Technologies Utilisées

- **Front-end**: Angular
- **Back-end**: FastAPI
- **Conteneurisation**: Docker
- **Intégration Continue / Déploiement Continu (CI/CD)**: Jenkins
- **MLOps**: Dagshub
- **Visualisation des Données**: Power BI

## Fonctionnalités

- **Saisie des Données**: Les utilisateurs peuvent entrer des données telles que le poids, la pression artérielle, le tabagisme, et l'âge pour obtenir une prédiction.
- **Prédiction**: Utilisation d'un modèle de machine learning pour prédire la probabilité de maladies cardiovasculaires ou de diabète.
- **Visualisation**: Les résultats et les statistiques sont visualisés à l'aide de Power BI.
- **Gestion des Modèles**: Suivi et gestion des modèles ML avec Dagshub.
- **Déploiement**: Déploiement automatisé via Jenkins et Docker.

## Architecture du Système

1. **Front-end (Angular)**: Interface utilisateur pour la saisie des données et l'affichage des résultats.
2. **Back-end (FastAPI)**: API pour gérer les requêtes de prédiction et communiquer avec le modèle de machine learning.
3. **Conteneurisation (Docker)**: Conteneurisation des applications pour assurer la portabilité et la cohérence des environnements.
4. **CI/CD (Jenkins)**: Pipeline CI/CD pour automatiser les tests, la construction, et le déploiement des applications.
5. **MLOps (Dagshub)**: Gestion des expérimentations et des modèles de machine learning.
6. **Visualisation (Power BI)**: Création de tableaux de bord interactifs pour l'analyse des données et des résultats.

## Installation

### Prérequis

- Node.js et npm
- Python 3.8+
- Docker
- Jenkins
---
Cette version est développée par Mohamed Amine Ghamgui.
