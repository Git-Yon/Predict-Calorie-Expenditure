python -m venv kaggle-calories

.\kaggle-calories\Scripts\activate

pip install -r requirements.txt



Plan de projet Kaggle — Prédiction Calories Brûlées 🔥
1. Compréhension & Exploration des données
Charger les datasets (train.csv, test.csv)

Analyse des colonnes (types, valeurs manquantes)

Statistiques descriptives (moyenne, médiane, écart-type…)

Visualisations univariées (histogrammes, boxplots verticaux pour détecter outliers)

Visualisations bivariées (corrélations, scatter plots, heatmap)

Analyse des distributions par catégories (ex: boxplots par genre)

2. Préparation des données
Nettoyage des données (gestion des valeurs manquantes et outliers)

Encodage des variables catégorielles (Gender, etc.)

Création de nouvelles features (feature engineering)

Ex : imbrication durée × fréquence cardiaque

Ex : indice de masse corporelle (IMC) à partir de poids et taille

Normalisation ou standardisation des variables si nécessaire

Séparation features / target (Calories)

3. Modélisation de base
Mise en place d’une baseline simple (régression linéaire, random forest)

Entraînement sur le train set

Validation par cross-validation (ex: KFold)

Évaluation avec métriques adaptées (MAE, RMSE)

4. Amélioration des modèles
Essais de modèles plus puissants (XGBoost, LightGBM)

Optimisation des hyperparamètres (GridSearchCV, RandomizedSearchCV)

Feature selection / importance

Analyse des erreurs (résidus, points mal prédits)

5. Préparation à la soumission Kaggle
Prédiction sur le test set

Formatage du fichier de soumission (id, Calories prédites)

Vérification du format et upload