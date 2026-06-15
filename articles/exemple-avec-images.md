---
title: Exemple d'article avec images
date: 2026-06-15
category: Stratégie
slug: exemple-avec-images
---

![Hero: Façade du bureau Fragata Gosselin](building-exterior.webp)

Ceci est un article de démonstration pour montrer comment insérer des images facilement.

On écrit le texte normalement. Le **gras** et l'*italique* fonctionnent.

## Insérer une image centrée

Il suffit d'écrire le markdown d'image sur sa propre ligne :

![Chargement de camion chez un client](building-exterior.webp)

La légende reprend le texte entre crochets automatiquement.

## Image flottante

Pour qu'une image flotte à droite du texte, on ajoute `{.right}` après le lien :

![Logo Fragata Gosselin](logo-new.webp){.right}

Le texte continue à côté de l'image. C'est pratique pour les photos d'illustration qui accompagnent un paragraphe sans prendre toute la largeur. Même principe avec `{.left}` pour flotter à gauche.

## Deux images côte à côte

On met les deux images sur des lignes consécutives :

![Yuani Fragata](yuani-fragata.webp)
![Francis Gosselin](francis-gosselin.webp)

## Résumé

Plus besoin d'ouvrir le HTML :

- `{.hero}` sur l'image → image pleine largeur en haut
- Seule sur sa ligne → centrée avec légende
- `{.left}` ou `{.right}` → image flottante
- Deux images sur des lignes consécutives → côte à côte
