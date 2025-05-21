# 🔥 Prédiction des Calories Brûlées - Projet Kaggle

Ce projet a pour objectif de prédire le nombre de **calories brûlées** lors d'une activité physique à partir de données biométriques et personnelles. Il est réalisé dans le cadre d’un entraînement à la data science avec Python et Kaggle.
https://www.kaggle.com/competitions/playground-series-s5e5/overview

## 🗂️ Datasets utilisés

- `train.csv` : données d'entraînement contenant les caractéristiques personnelles et la variable cible `Calories`
- `test.csv` : données de test fournies sans les `Calories` (à prédire)
- `sample_submission.csv` : exemple de format pour la soumission finale

## Modèle et Score

Le modèle utilisé est un **XGBRegressor** dont les hyperparamètres ont été optimisés via un **GridSearchCV**.

Le score obtenu sur le jeu de test est :  

**Score RMSLE : 0.06052**

## ⚙️ Installation

Crée un environnement virtuel et installe les dépendances :

```bash
python -m venv kaggle-calories

.\kaggle-calories\Scripts\activate  # Sur Windows
# source kaggle-calories/bin/activate  # Sur Linux/macOS

pip install -r requirements.txt
