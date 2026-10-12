---
title: "LootRadar, comparateur de prix de jeux PC"
date: 2026-10-12
cadre: "Projet personnel"
resume: "Création et mise en ligne d'un site qui compare le prix d'un jeu PC dans plus de 30 boutiques officielles, grâce à une API publique."
competences: [c3, c4, c5]
---

## Contexte

Je voulais réaliser un vrai site internet pour la partie « site internet » de mon portfolio. J'ai choisi un comparateur de prix de jeux vidéo PC : l'utilisateur tape le nom d'un jeu et découvre immédiatement dans quelle boutique il est le moins cher.

- Site en ligne : [ilivn.github.io/Site-Internet](https://ilivn.github.io/Site-Internet/)
- Code source : [github.com/ilivn/Site-Internet](https://github.com/ilivn/Site-Internet)

## Conditions et moyens

Seul, avec l'aide de Claude (assistant IA) pour la conception et l'écriture du code. Outils gratuits uniquement : HTML, CSS et JavaScript sans framework, l'API publique CheapShark pour les prix, GitHub pour le code et GitHub Pages pour l'hébergement.

## Description de l'activité

1. Étude du besoin et des sources de données possibles (API gratuites, conditions d'utilisation, limites).
2. Choix d'une architecture simple : un site statique qui interroge directement l'API CheapShark avec `fetch`.
3. Réalisation de la recherche instantanée, de la fiche détaillée de chaque jeu (prix par boutique, plus bas prix historique, économie réalisée) et des bons plans du moment.
4. Ajout d'une section présentant les boutiques comparées (Steam, GOG, Gamesplanet, Fanatical, DLGamer, Green Man Gaming…) avec l'indication des prix suivis automatiquement ou non.
5. Sécurisation : échappement de toutes les données reçues de l'API pour se protéger des failles XSS, liens externes en `rel="noopener"`.
6. Dépôt des fichiers sur GitHub et mise en ligne avec GitHub Pages.

## Productions et preuves

- Le site en ligne : [ilivn.github.io/Site-Internet](https://ilivn.github.io/Site-Internet/)
- Le dépôt GitHub et son historique : [github.com/ilivn/Site-Internet](https://github.com/ilivn/Site-Internet)
- Le fichier `README.md` du dépôt, qui documente les fonctionnalités, la sécurité et les limites du site.

## Ce que j'en retiens

J'ai appris à utiliser une API REST, à publier un site avec GitHub Pages et à me méfier des données externes (faille XSS). J'ai aussi rencontré des difficultés à l'installation de Node.js : PowerShell bloquait l'exécution des scripts. J'ai compris ce qu'était la politique d'exécution de Windows avant de choisir une solution plus simple, un site statique qui ne nécessite aucune installation.
