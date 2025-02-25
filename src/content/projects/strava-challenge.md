---
title: Challenge Strava
publishDate: 2023-06-01 00:00:00
img: /assets/challenge-strava.png
img_alt: Tableau de bord du challenge
description: |
  J'ai créé une application de Challenge Strava qui consiste en une application de visualisation de données utilisant Grafana et PostgreSQL pour organiser un challenge de course à pied. L'application récupère les données de l'API Strava pour chaque participant au challenge et les stocke dans une base de données PostgreSQL. Les performances de chaque athlète sont ensuite affichées sur un tableau de bord Grafana.
tags:
  - Grafana
  - Node
  - PostgreSQL
  - AWS
---

## Architecture de l'application

L'application est composée de trois parties :

1. **API de remontée de données** : Une application qui récupère les données de l'API Strava et les stocke dans une base de données PostgreSQL.

2. **Base de données PostgreSQL** : Cette partie de l'application stocke les données des athlètes et leurs performances.

3. **Tableau de bord Grafana** : Cette interface affiche les données stockées dans la base de données PostgreSQL pour visualiser les performances de chaque athlète.

## Fonctionnalités

L'application Challenge Strava offre les fonctionnalités suivantes :
- Récupération automatique des données de l'API Strava pour chaque participant.
- Stockage sécurisé des données dans une base de données PostgreSQL.
- Visualisation des performances des athlètes sur un tableau de bord Grafana.
- Mise à jour en temps réel des données affichées sur le tableau de bord.

## Technologies utilisées

Le projet utilise les technologies suivantes :
- **Grafana** : Pour la visualisation des données et la création de tableaux de bord interactifs.
- **Node.js** : Pour le développement de l'API de remontée de données.
- **PostgreSQL** : Pour le stockage des données des athlètes.
- **AWS** : Pour l'hébergement et le déploiement de l'application.

## Conclusion

Ce projet démontre ma capacité à intégrer différentes technologies pour créer une application complète de visualisation de données. En utilisant Grafana, Node.js, PostgreSQL et AWS, j'ai pu développer une solution robuste et évolutive pour organiser et suivre un challenge de course à pied.

Pour plus de détails, visitez le [dépôt GitHub](https://github.com/TheoLaperrouse/strava-challenge).