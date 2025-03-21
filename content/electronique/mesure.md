---
title: Triangulation en UWB
type: post
tags: ["électronique", "circuit imprimé", "clubelek"]
---

Pour le Clubelek, nous voulions un moyen de pouvoir mesurer le courant et la tension envoyée à chacune de nos trois tesla, et de pouvoir enregistrer ces mesures.

J'ai donc réalisé trois PCB différents, qui se connectent ensemble :
Le premier est le principal, avec les différents capteurs de courant et de tension :
![](/img/electronique/mesure/pcb_main.png)

Le deuxième est un buck isolé permettant d'abaisser la tension et d'isoler la carte de la très haute tension des bobines Tesla.
![](/img/electronique/mesure/power.png)

Le troisième est une devboard ESP32-C3 avec carte micro-SD.
![](/img/electronique/mesure/daughterboard.png)

État du projet : PCB réalisé, mais non fabriqué par manque de temps.