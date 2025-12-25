---
author:
- Votre Nom
bibliography:
- references.bib
date: 2025-12-25
title: Exercice Biblatex - Test Complet
---

# Introduction

Test complet de biblatex avec différentes fonctionnalités.

# Citations de base

## Citations simples

- Article: @Thomas2008

- Livre: [@Graham1995]

- Avec pages: [@Thomas2008 7010-7015]

- Multiple: [@Thomas2008; @Smith2020; @Doe2019]

## Commandes de citation avancées

- Auteur seulement: @Smith2020

- Année seulement: [-@Graham1995]

- Auteur et année: @Thomas2008 ([-@Thomas2008])

# Test de citations manquantes

Citation qui n'existe pas dans la base: @ReferenceManquante2025

# Ajout de nouvelles références

- Référence existante: [@Doe2019]

- Nouvelle référence (à ajouter au .bib): @NouveauLivre2024

# Comparaison des styles

Testez en changeant le style dans le préambule:

- `style=authoryear`: (Auteur, Année)

- `style=numeric`: \[1\], \[2\], \[3\]

- `style=alphabetic`: \[Tho08\], \[Gra95\]
