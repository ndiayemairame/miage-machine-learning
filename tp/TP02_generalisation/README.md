# TP2 — Complexité et généralisation

## Objectif

À partir du problème de prédiction du délai de livraison étudié au TP1, nous cherchons maintenant à améliorer le modèle sans simplement apprendre davantage les données d'entraînement.

Ce TP introduit notamment :

- la complexité d'un modèle ;
- la régression polynomiale ;
- le compromis biais-variance ;
- la régularisation ;
- le choix des hyperparamètres ;
- la sélection d'un modèle avant l'évaluation finale.

## Notebook

Le notebook du TP est disponible dans ce dossier.

Pour l'exécuter :

1. téléchargez le fichier `.ipynb` ;
2. ouvrez-le dans Google Colab ;
3. exécutez les cellules dans l'ordre.

Les données nécessaires sont chargées directement depuis le dépôt GitHub.

## Données

Le TP utilise le jeu de données **Olist Brazilian E-Commerce**.

Le fichier préparé pour les TP se trouve dans :

`data/orders_ml.csv`

## Consigne

L'objectif n'est pas uniquement d'obtenir le modèle ayant la plus faible erreur sur les données d'apprentissage.

Pour chaque expérience, vous devez être capable d'expliquer :

- comment la complexité du modèle évolue ;
- ce qui se passe sur les données d'apprentissage et de validation ;
- comment identifier un problème de surapprentissage ;
- quel est l'effet de la régularisation.