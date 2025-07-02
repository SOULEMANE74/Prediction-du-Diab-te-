# Diabète Prédiction - Modèle de Machine Learning

Ce projet consiste à prédire la probabilité de présence de diabète chez des individus en utilisant des techniques de **Machine Learning** sur un dataset médical. L'objectif est de créer un modèle capable de prédire si une personne est diabétique (classe **1**) ou non diabétique (classe **0**) à partir de caractéristiques cliniques telles que le **glucose**, le **BMI**, l’**âge**, etc.

## Objectif du Projet

L'objectif est de construire un modèle de classification efficace qui aide à prédire la présence de diabète en fonction de données cliniques. Le modèle développé peut être utilisé comme un outil de support pour la détection précoce du diabète.

## Description du Dataset

Le dataset utilisé provient des **Pima Indians Diabetes Database** et contient des informations cliniques sur les patients, incluant les variables suivantes :

* **Pregnancies** : Nombre de grossesses
* **Glucose** : Taux de glucose sanguin
* **BloodPressure** : Pression sanguine
* **SkinThickness** : Épaisseur de la peau
* **Insulin** : Niveau d'insuline
* **BMI** : Indice de masse corporelle
* **DiabetesPedigreeFunction** : Fonction de prédisposition génétique au diabète
* **Age** : Âge du patient
* **Outcome** : Indicateur de diabète (0 = Non diabétique, 1 = Diabétique)

## Méthodologie

Le projet suit les étapes classiques de la **science des données** :

1. **Prétraitement des données** : Nettoyage et préparation des données pour l'entraînement.
2. **Séparation des données** : Division du dataset en un ensemble d'entraînement et un ensemble de test.
3. **Entraînement des modèles** : Différents algorithmes de classification sont utilisés pour la prédiction du diabète, dont :

   * **Random Forest Classifier**
   * **Logistic Regression**
   * **Support Vector Machine (SVM)**
   * **K-Nearest Neighbors (KNN)**
4. **Évaluation des modèles** : Comparaison des performances des modèles à l’aide de **précision**, **rappel**, et **F1-score**.

## Résultats

Parmi les modèles testés, le **Random Forest Classifier** a donné les meilleurs résultats avec une précision de **90.26%** sur le jeu de test. Ce modèle a montré de bonnes capacités à prédire aussi bien les individus diabétiques que non diabétiques, avec des scores solides pour chaque classe.

## Conclusion

Ce projet démontre la capacité des techniques de machine learning à prédire la présence de diabète en fonction de variables cliniques. Le **Random Forest Classifier** s’est avéré le plus performant, mais d’autres améliorations peuvent être explorées, telles que l’équilibrage des classes ou l’ajustement des hyperparamètres.

## Dépendances

* pandas
* numpy
* scikit-learn
* matplotlib
* seaborn
* jupyter


