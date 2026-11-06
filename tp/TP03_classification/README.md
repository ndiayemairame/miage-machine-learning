# TP3 — De la probabilité à la décision

## Objectif

À partir des données Olist, construire un modèle de classification et comprendre comment transformer une probabilité prédite en décision.

Ce TP introduit notamment :

- la régression logistique ;
- les probabilités prédites ;
- le seuil de décision ;
- la matrice de confusion ;
- la précision, le rappel et le F1-score ;
- les courbes ROC et Precision-Recall ;
- le déséquilibre des classes ;
- les techniques de rééquilibrage (undersampling, oversampling et SMOTE).

## Notebook

Le notebook du TP est disponible dans ce dossier :

`TP03_classification_complet.ipynb`

Pour l'exécuter :

1. Téléchargez le fichier `.ipynb`.
2. Ouvrez-le dans Google Colab.
3. Exécutez les cellules dans l'ordre.

## Données

Le TP utilise le jeu de données **Olist Brazilian E-Commerce**.

Les données préparées sont disponibles dans le dossier `data/` du dépôt GitHub.

## Consigne

L'objectif n'est pas uniquement d'obtenir un bon score de classification.

Pour chaque expérience, vous devez être capable d'expliquer :

- ce que représente la probabilité prédite ;
- comment le seuil de décision influence les résultats ;
- pourquoi l'accuracy peut être trompeuse ;
- comment interpréter la précision et le rappel ;
- quel est l'effet du déséquilibre des classes ;
- comment choisir un modèle adapté au problème métier.