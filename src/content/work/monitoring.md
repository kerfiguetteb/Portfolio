---
title: monitoring
publishDate: 2019-10-02 00:00:00
img: /assets/monitoring.jpg
img_alt: Soft pink and baby blue water ripples together in a subtle texture.
description: |
  Application web de monitoring de modules IOT.
tags:
  - Php-Symfony
  - Bootstrap
  - Twig
  - JavaScript
  - Html
  - Css

---



Depuis plusieurs années, les objects connéctés à internet se multiplient, cependant les outils pour verifier leur fonctionnement et leur disponibilité restent rares. Cette apliccation a pour but de tester leur fonctionnement et leur disponibilité.

 Le but n'est pas de réellement connecter des module, mais simplement de créer un script qui les simulent.

##### Fonctionnalités:

  - Création d'une BDD répertoriant les modules, leurs details et l'historique de fonctionnement.
  - Création d'un formulaire, pour inscrire de nouveaux modules
  - Création d'une page de visualisation de l'état de fonctionnement des modules comme la valeur mesurée actuelle, durée de fonctionnement, nombre de données envoyées, état de marche ainsi qu'un graphique permettant de suivre l'évolution de la valeur mesurée.  
  - Sur l'interface, des notifications visuelles en cas de dysfonctionnement d'un module.
  - Création d'un script de génération automatique d'état des modules.
  - Les modules générent des données numériques sur la mesure qu'ils éffectuent (temperzature, vitesse, pression) et en stocker l'historique dans une base de données. Les modules peuvent tomber en panne puis refonctionner de façon aléatoire. La génération de l'historique continue lors de navigation sur l'interface web de test. 

  Lien GitHub [monitoring](https://github.com/kerfiguetteb/monitoring).