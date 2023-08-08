---
title: FastAPI FFTT - Backend avec FastAPI
publishDate: 2017-03-01 00:00:00
img: /assets/fastapi-fftt.png
img_alt: FastAPI FFTT - Backend avec FastAPI
description: |
  FastAPI FFTT est un projet de backend construit avec FastAPI et Uvicorn, déployé à l'aide d'AWS EC2 et Route53. Ce projet utilise l'API de la Fédération Française de Tennis de Table pour obtenir des informations sur les joueurs de Tennis de Table et leurs résultats. L'analyse statique du code est réalisée à l'aide de pylint. Le backend est déployé à l'adresse http://fastapifftt.thorigne-tt.net/docs et une Intégration Continue (CI) est configurée pour effectuer une vérification de style et un redéploiement automatique en cas de modification du code sur GitHub.
tags:
  - Python
  - FastAPI
  - AWS (EC2 / Route53)
  - CI
---

## Explication

FastAPI FFTT utilise l'API FFTT pour récupérer des données sur les joueurs de Tennis de Table et leurs résultats de match. Le backend est construit avec FastAPI et Uvicorn et est déployé à l'aide d'AWS EC2 et Route53. L'analyse statique du code est réalisée à l'aide de pylint pour assurer la qualité du code. La documentation du backend déployé est accessible à l'adresse http://fastapifftt.thorigne-tt.net/docs

Ce projet exploite FastAPI et Uvicorn pour fournir une solution de backend robuste pour accéder aux données de l'API FFTT. Avec le déploiement AWS EC2, l'analyse de code statique et l'intégration CI, il vise à fournir des informations fiables et à jour sur les joueurs de Tennis de Table

Pour plus de détails, visitez le [dépôt GitHub](https://github.com/TheoLaperrouse/fastapi_fftt)