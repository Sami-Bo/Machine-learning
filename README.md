# Machine Learning – TP Iris, Clustering & Classification

Ce projet implémente plusieurs techniques de Machine Learning sur le dataset Iris et des jeux de données simulés, couvrant visualisation, réduction de dimensions, clustering et classification.

## 1. Visualisation et Analyse
- Exploration du dataset Iris (`iris.data`, `iris.target`, `iris.feature_names`)  
- Visualisation 2D de toutes les combinaisons de variables avec coloration par classes  
- Calcul des corrélations pour sélectionner les variables les plus informatives  

## 2. Réduction de Dimensions
- **PCA** : projection des données sur les composantes principales  
- **LDA** : séparation supervisée des classes  
- Comparaison visuelle PCA vs LDA et tests avec d’autres techniques de réduction de dimension  

## 3. Clustering
- Génération de données synthétiques avec `make_blobs`  
- **K-Means** et **Hierarchical Clustering** sur Iris et données artificielles  
- Évaluation avec indice de **Silhouette**  
- Visualisation des clusters sur projections PCA  

## 4. Classification
- **K-Nearest Neighbors (KNN)** avec cross-validation leave-one-out  
- Test du KNN maison vs `sklearn.neighbors.KNeighborsClassifier`  
- **SVM** (Linear et Kernel), **Naive Bayes**, **Decision Trees**  
- Analyse des performances avec erreur de prédiction et matrice de confusion  

## 5. Régression Linéaire
- Comparaison de **Linear Regression**, **Ridge** et **Lasso**  
- Étude de l’impact des paramètres de régularisation (`C`, `alpha`) sur les scores  

## Bibliothèques
- Python 3.x, `numpy`, `matplotlib`, `scikit-learn`

## Résultats
- Visualisation des distributions et clusters  
- Évaluation comparative des classificateurs et modèles de régression  
- Interprétation de l’impact des paramètres sur performances et décision
