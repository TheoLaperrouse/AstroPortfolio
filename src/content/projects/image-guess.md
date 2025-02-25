---
title: Jeu de reconnaissance d'image
publishDate: 2023-10-10 00:00:00
img: /assets/image-guess.png
img_alt: Quizz de reconnaissance d'images
description: |
  Jeu de reconnaissance d'image où le but est de retrouver le plus d'images possible en 60 secondes. Les joueurs peuvent passer une image s'ils ne la reconnaissent pas.
tags:
  - Vue3
  - Vite
  - AWS
---

## Explication

Le jeu de reconnaissance d'image a pour objectif de retrouver le plus d'images possible en 60 secondes. Si un joueur ne reconnaît pas une image, il peut choisir de passer à la suivante.

Pour améliorer l'expérience utilisateur, un système d'approximation a été mis en place. Cet algorithme utilise la distance de Levenshtein avec une tolérance maximale de 2. Par exemple, "Laperrouze" sera accepté si l'on cherche "Laperrouse".

Les joueurs ont la possibilité de passer jusqu'à trois fois s'ils ne connaissent pas la réponse.

Ce projet utilise Vue3 et Vite pour le développement frontend, et est déployé sur AWS pour assurer une disponibilité et une performance optimales.

Pour plus de détails, visitez le [dépôt GitHub](https://github.com/TheoLaperrouse/image-guess).