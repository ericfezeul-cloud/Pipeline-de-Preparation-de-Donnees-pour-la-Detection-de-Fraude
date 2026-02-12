# Pipeline de Préparation de Données pour la Détection de Fraude

## 📋 Description du Projet
Ce projet implémente un pipeline complet de prétraitement et de préparation de données pour un système de détection de fraude. L'objectif principal est de transformer des données brutes souvent déséquilibrées (cas de fraude rares par rapport aux transactions normales) en un jeu de données optimisé pour l'entraînement de modèles d'apprentissage automatique (Machine Learning).

## 🛠️ Fonctionnalités du Pipeline
Le notebook couvre les étapes critiques de la data science :
- **Exploration et Nettoyage** : Analyse des types de données et traitement des valeurs manquantes.
- **Ingénierie des Caractéristiques (Feature Engineering)** : Mise à l'échelle des données via `StandardScaler` et `RobustScaler` pour gérer les valeurs aberrantes.
- **Gestion du Déséquilibre (Imbalanced Data)** : Application de techniques avancées pour équilibrer les classes :
    - **SMOTE** (Synthetic Minority Over-sampling Technique).
    - **Random Under Sampler**.
- **Validation** : Vérification de l'équilibre final des classes et préparation des sets d'entraînement et de test.

## 🧰 Technologies Utilisées
- **Langage** : Python
- **Librairies de Manipulation de Données** : `Pandas`, `NumPy`
- **Visualisation** : `Matplotlib`, `Seaborn`
- **Machine Learning & Prétraitement** : 
    - `Scikit-learn` (Scaling, Model Selection)
    - `Imbalanced-learn` (SMOTE, UnderSampling)
