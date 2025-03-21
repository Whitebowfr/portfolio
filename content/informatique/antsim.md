---
title: Simulation d'une colonie de fourmis avec parallélisation des calculs
type: post
tags: ["Python"]
---

Ce projet a commencé pour un cours d'informatique, mais nous avons vite été limité par la vitesse de calcul et d'affichage de Python.

Nous avons donc porté la codebase complète pour utiliser la parallélisation au travers de la librairie Taichi, nous permettant d'effectuer des fonctions sur des matrices en parallèle.

Cela nous a permis de passer de 3 images par seconde sur une grille de 500x500 avec 50 agents à plus de 160 images par seconde sur une grille de 5000x5000 avec 1000 agents.

https://github.com/Whitebowfr/projet-fourmis/tree/taichi