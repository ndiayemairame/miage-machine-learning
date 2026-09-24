# TP1 — Du SI à une première prédiction

## Objectif

À partir des données Olist, construire une première démarche de prédiction du délai réel de livraison d'une commande.

Ce TP introduit notamment :

- le passage de données issues d'un SI à un jeu analytique ;
- la définition de l'unité d'observation et de la cible ;
- la distinction entre variables disponibles et fuite de données ;
- la séparation apprentissage / test ;
- la construction d'une baseline ;
- la régression linéaire ;
- l'évaluation et l'analyse des erreurs.

## Notebook

Le notebook du TP est disponible dans ce dossier.

Pour l'exécuter, vous pouvez :

1. télécharger le fichier `.ipynb` ;
2. l'ouvrir dans Google Colab ;
3. exécuter les cellules dans l'ordre.

Les données nécessaires sont chargées directement depuis le dépôt GitHub.

## Données

Le TP utilise le jeu de données **Olist Brazilian E-Commerce**.

Le fichier préparé pour les TP se trouve dans :

`data/orders_ml.csv`

## Consigne

L'objectif n'est pas uniquement d'obtenir un modèle qui fonctionne.

Pour chaque expérience, vous devez être capable d'expliquer :

- ce que vous cherchez à prédire ;
- quelles informations sont disponibles au moment de la prédiction ;
- comment vous évaluez le modèle ;
- ce que signifient les résultats obtenus.