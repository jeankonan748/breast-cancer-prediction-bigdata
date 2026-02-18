# breast-cancer-prediction-bigdata
Ce projet vise à prédire le cancer du sein à partir de données biomédicales en utilisant des techniques de Machine Learning et de Deep Learning. Il repose sur l’analyse de caractéristiques morphologiques cellulaires afin de classifier les tumeurs en bénignes ou malignes et de comparer les performances des différents modèles développés.

🎯 Objectifs du projet
Objectif général

Développer un modèle prédictif performant capable de classifier les tumeurs mammaires en deux catégories :

Bénigne (Benign)

Maligne (Malignant)

Objectifs spécifiques

Réaliser une analyse exploratoire approfondie des données

Appliquer des techniques de prétraitement adaptées

Implémenter plusieurs algorithmes de Machine Learning

Concevoir un modèle basé sur les réseaux de neurones artificiels

Comparer les performances des approches ML et DL

Proposer une analyse d’interprétabilité des modèles

📊 Description du Dataset

Le projet repose sur un dataset de diagnostic du cancer du sein contenant des caractéristiques morphologiques extraites d’images de noyaux cellulaires.

Caractéristiques principales :

Radius

Texture

Perimeter

Area

Smoothness

Compactness

Concavity

Symmetry

Fractal Dimension

Ces variables sont mesurées sous différentes formes statistiques (moyenne, erreur standard, worst value).

Variable cible :

Diagnosis

M : Malignant

B : Benign

Le dataset présente :

Des variables numériques continues

Une classification binaire

Un léger déséquilibre de classes

⚙️ Méthodologie adoptée

Le projet suit une approche structurée en plusieurs étapes :

1️⃣ Analyse exploratoire

Distribution des classes

Analyse statistique descriptive

Matrice de corrélation

Détection d’anomalies

2️⃣ Prétraitement

Encodage de la variable cible

Normalisation des données

Séparation Train / Test

Validation croisée

3️⃣ Modélisation Machine Learning

Régression Logistique

Support Vector Machine

Random Forest

XGBoost

4️⃣ Modélisation Deep Learning

Réseau de neurones artificiels (ANN)

Activation ReLU

Dropout pour éviter le surapprentissage

Optimiseur Adam

5️⃣ Évaluation des performances

Les modèles sont évalués à l’aide des métriques suivantes :

Accuracy

Precision

Recall

F1-score

ROC-AUC

Matrice de confusion

🏆 Apport scientifique du projet

Ce travail ne se limite pas à une simple implémentation algorithmique. Il propose :

Une comparaison rigoureuse ML vs DL

Une analyse de l’importance des variables

Une étude de robustesse par validation croisée

Une réflexion sur l’interprétabilité des modèles

Un pipeline reproductible adapté aux problématiques biomédicales

💡 Intérêt du projet

Ce projet démontre comment les techniques de Big Data et d’Intelligence Artificielle peuvent :

Améliorer la précision du diagnostic médical

Réduire les erreurs humaines

Accélérer la prise de décision clinique

Contribuer à la médecine prédictive

Il s’inscrit pleinement dans les enjeux actuels de la santé numérique et de la médecine assistée par l’intelligence artificielle.
