---
title: Jeu de reconnaissance d'image
publishDate: 2023-10-10 00:00:00
img: /assets/image-guess.png
img_alt: Quizz de reconnaissance d'images
description: |
  Jeu de reconnaissance d'image, le but est de retrouver le plus d'images possible en 60 secondes. On peut passer si on trouve pas l'image.
tags:
  - Vue3
  - Vite
  - AWS
---

## Explication

Jeu de reconnaissance d'image, le but est de retrouver le plus d'images possible en 60 secondes. On peut passer si on trouve pas l'image.

Mise en place d'un système d'approximation, à savoir l'algorithme de Levenstein avec une distance max de 2 ("Laperrouze" est accepté si l'on cherche "Laperrouse").

Possibilité de passer 3 fois si l'on ne sait pas la réponse.