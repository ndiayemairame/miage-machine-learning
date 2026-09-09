# Données pédagogiques

Ce dossier contient les jeux de données pédagogiques utilisés dans les travaux pratiques du cours **Introduction au Machine Learning — M2 MIAGE**.

Les données ont été construites à partir du dataset **Olist Brazilian E-Commerce**.

## orders_ml.csv

Granularité : **une ligne par commande livrée**.

Nombre d'observations : **96 470 commandes**.

Ce jeu de données est utilisé dans les TP consacrés à :

- la régression ;
- la généralisation et la régularisation ;
- la classification ;
- les arbres et méthodes d'ensemble.

Deux variables cibles principales sont disponibles :

- `delivery_time_days` : délai réel de livraison en jours ;
- `is_late` : indique si la commande a été livrée après la date de livraison promise.

## sellers_ml.csv

Granularité : **une ligne par vendeur actif**.

Nombre d'observations : **2 970 vendeurs**.

Ce jeu de données est utilisé pour le TP consacré au clustering et à la réduction de dimension.

## Données sources

Les fichiers Olist originaux ne sont pas inclus dans ce dépôt.

Les jeux de données présents ici sont des tables analytiques dérivées, préparées pour les besoins pédagogiques du cours.