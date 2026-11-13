# TP4 — Des arbres de décision aux méthodes d'ensemble

## Objectif

À partir des données Olist, comparer différentes méthodes de classification pour prédire si une commande risque d'être livrée en retard.

Ce TP introduit notamment :

- les arbres de décision et l'effet de leur profondeur ;
- le Bagging ;
- les Random Forests ;
- le Gradient Boosting ;
- les implémentations XGBoost, LightGBM et CatBoost ;
- la comparaison des performances et des temps d'entraînement ;
- la sélection d'un modèle et d'un seuil de décision.

## Notebook

Le notebook du TP est disponible dans ce dossier :

`TP04_arbres_ensembles_complet.ipynb`

Pour l'exécuter :

1. Téléchargez le fichier `.ipynb`.
2. Ouvrez-le dans Google Colab.
3. Exécutez les cellules dans l'ordre.
4. Complétez les cellules de code et les espaces de réponse prévus.

## Données

Le TP utilise le jeu de données **Olist Brazilian E-Commerce**.

Le fichier préparé pour les TP se trouve dans :

`data/orders_ml.csv`

Les données sont chargées directement depuis le dépôt GitHub.

## Consigne

L'objectif n'est pas uniquement d'obtenir le modèle ayant les meilleures performances.

Une attention particulière sera portée à l'interprétation des résultats et à la justification des choix.