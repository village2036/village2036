---
layout: post
enquete: crimes
title:  "Suis-je en sécurité?"
date:   2020-12-05 17:09:13 -0500
abstract: |-
  L'attaque au katana de Québec nous a vraiment traumatisé! Mais ça nous a aussi
  permis de découvrir de superbes jeux de données et d'imaginer une nouvelle application.
img_preview: "preview1.png"
img_atl: Des indicateurs de risque sur une carte
---



Comme pour plusieurs résidents de Québec, l'attaque au katana m'a bouleversé. J'avais eu l'idée d'aller marcher dans le Vieux-Québec ce soir-là. Heureusement, j'ai été trop lâche pour sortir... sauvé par ma paresse! N'empêche que mes enfants ont passé l'halloween à quelques rues de là. Depuis ce drame, ma blonde me fait une scène à chaque fois que j'oublie de barrer la porte. "Je ferme à clef quand je sors, oui d'accord. Mais en plus tu voudrais que je nous embarre à l'intérieur?!!"

Ce genre d'histoire est certainement exceptionelle et assez difficile à prévoir. N'empêche que je me suis demandé "Suis-je en sécurité?" Ça a été suffisant me lancer sur la piste des données qui pourraient répondre à cette question.

## Quelles données sont accessibles?

Premier réflexe: un courriel à la police de Québec. On s'attend bien à ce que la police soit pas très enthousiaste à nous donner accès à leurs données. Leur réponse est tout de même très décevante: "Nous ne produisons pas de données ouvertes. Les données sur la criminalité se trouvent dans notre rapport annuel. Statistique Canada a aussi des données sur la criminalité."

Voyons voir ce rapport annuel... Un pdf contenant quelques tableaux aggréggés principales catégories de crimes. Y'a des chiffres, oui, mais on arrivera pas à grand chose avec ça. Ça demanderait un effort important pour retrouver les rapports, mettre ces chiffres sous une forme appétisante pour mon ordinateur et obtenir des données qui nous permettent même pas de savoir dans quels quartiers ont eu lieu les évènements. Non merci, je passe mon tour.

Je continue mes recherches. Rien dans les Données Ouvertes de la ville de Québec non plus... Attends un peu: Montréal!  Ils ont publié la liste des [actes criminels depuis 2015](https://www.donneesquebec.ca/recherche/dataset/vmtl-actes-criminels). Ce jeux de donnée a une catégorisation assez sommaire: introduction, vol dans / sur véhicule à moteur, vol de véhicule à moteur, méfait, vol qualifié et infraction entraînant la mort. Quand même, 128 916 évènements géolocalisés sur 5 ans. On va partir de ça.

 <img src="{{site.url}}/public/img/crimes/preview1.png">
