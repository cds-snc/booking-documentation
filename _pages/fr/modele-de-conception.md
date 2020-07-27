---
layout: page
title:  "Modèles de conception"
lang: fr
permalink: "/modeles-de-conception/"
trans_url: "/design-patterns/"
---

## Analyse comparative
Il y a certainement quelques modèles de conception utiles à prendre en compte, basés sur l’heuristique et les pratiques exemplaires. Nous avons mené une analyse comparative pour explorer les modèles de conception, et cela a soulevé quelques questions intéressantes. Les principes suivants peuvent raisonnablement être dérivés de l’analyse comparative.

## Réduire la charge cognitive
- **Supposons que les participants sont stressés** avec peu de charge cognitive lors de la conception d’une application de prise de rendez-vous. Nous supposons que le fait de vérifier le prochain rendez-vous disponible aidera un participant à prendre d’autres décisions liées au rendez-vous, comme choisir un lieu ou choisir une plage horaire. 
- **Réduire le nombre d’étapes nécessaires** pour voir la disponibilité. Nous supposons que les participants ont probablement certains critères et qu’ils doivent respecter un horaire ou un emplacement pour pouvoir prendre rendez-vous. Si la conception alourdit leur charge cognitive alors qu’ils cherchent simplement une disponibilité, ils peuvent oublier leurs critères préexistants ou quitter. 
- **Utiliser la recherche menée auprès des utilisateurs réels** pour cerner les instructions sur les étapes requises avant ou après la prise de rendez-vous. Dans certains cas, les participants savent peut-être déjà ce qu’ils doivent faire et les instructions ne font que les ralentir. Dans d’autres cas, particulièrement si les participants sont en train de prendre le rendez-vous, des instructions inadéquates pourront les amener à se présenter à des rendez-vous avec des documents ou des renseignements manquants, ce qui fera perdre à chacun un temps précieux.
- **Ne pas forcer les participants à choisir le type de rendez-vous**, à moins qu’ils aient vraiment le choix. Ce serait une perte de temps pour ces participants.

### Concevoir attentivement les parcours utilisateurs 

- **Cherchons à reporter la collecte de renseignements personnels** du participant jusqu’à ce qu’il ait choisi une date. Obliger les participants à s’inscrire ou à se connecter avant qu’ils puissent vérifier la disponibilité est contraignant. 
- **Cherchons à inclure des renseignements sur l’accessibilité** lorsqu’un participant doit choisir un lieu. ServiceOntario (l’image de droite) est un exemple du genre de renseignements demandés.
- **Cherchons à choisir un fenêtre de temps appropriée à afficher.** Nous supposons que, dans des contextes gouvernementaux où personne ne travaille la fin de semaine, vérifier la disponibilité des rendez-vous sur une période de cinq jours peut être le plus utile. De nombreuses applications de prise de rendez-vous permettent de vérifier la disponibilité sur une période d’un ou de deux mois et exigent que les utilisateurs sélectionnent d’abord une date avant de pouvoir voir les heures disponibles.
- **Cherchons à montrer la première heure disponible** par défaut lors de l’affichage des heures disponibles. Ne forcez pas les personnes à perdre leur temps à faire des sélections inutiles.
- **Cherchons à afficher les plages horaires disponibles dès le début.** De nombreux calendriers obligent les utilisateurs à choisir une date avant d’afficher les heures disponibles pour cette date. Si aucune de ces heures ne convient au participant, il doit retourner en arrière et choisir une autre date pour voir si des plages horaires peuvent fonctionner. Cela devient rapidement contraignant.

## Principes fondamentaux d’accessibilité
- **Commencer à concevoir pour les mobiles dès le début.** Surtout si vous utilisez une sorte de calendrier visuel, l’ajuster à un écran d’appareil mobile sera beaucoup plus difficile que pour un ordinateur de bureau.
- **S’assurer que tout peut être parcouru au moyen du clavier** uniquement. D’après notre analyse, cela est rare.
- **S’assurer que tous les textes sont structurés et ordonnés** de manière à ce qu’ils soient logiques pour les personnes qui utilisent des lecteurs d’écran. Il s’agissait aussi d’une embûche courante pour les applications de prise de rendez-vous que nous avons examinées.
