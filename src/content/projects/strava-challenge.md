---
title: Challenge Strava
publishDate: 2023-06-01 00:00:00
img: /assets/challenge-strava.png
img_alt: Tableau de bord du challenge
description: |
  J'ai créé une application de Challenge Strava qui consiste en une application de visualisation de données utilisant Grafana et Postgresql pour organiser un challenge de course à pied. L'application récupère les données de l'API Strava pour chaque participant au challenge et les stocke dans une base de données PostgreSQL. Les performances de chaque athlète sont ensuite affichées sur un tableau de bord Grafana.
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
