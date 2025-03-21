---
title: Robot autonome avec télécommande
type: post
tags: ["électronique", "circuit imprimé", "fabrication"]
---

Ce projet a été réalisé en freelance pour l'entreprise Lulocode, qui vends des jouets pour enfant avec pour objectif de développer des compétences de logique, sans écrans.

J'ai donc été contacté afin de réaliser un premier prototype, puis pour lancer la réalisation d'une pré-série (environ 50 exemplaires).

Pour des raisons de confidentialités, je ne peux pas partager les schematic.

## Carte de commande du robot
Le premier circuit imprimé est celui du robot en lui même. Voici les composants importants qui le composent :
- ESP32-S3 pour communication en WiFi
- Driver de moteurs DC
- Capteur de couleur avec LED d'éclairage
- Capteurs de luminosité pour suivi de ligne
- Chargeur et protection de batterie

![](/img/electronique/lulocode/pcb.png)
![](/img/electronique/lulocode/IMG_8391.jpg)

État du projet : Réalisé, soudé et testé. 

## Télécommande
Le deuxième circuit imprimé est celui d'une télécommande communiquant avec ESPNow.

![](/img/electronique/lulocode/pcb-remote.png)

État du projet : Réalisé, pas encore soudé.