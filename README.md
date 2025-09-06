# ML_PROJECT

Ce projet met en œuvre plusieurs algorithmes de machine learning pour l’analyse de données, la classification et la prédiction à partir de jeux de données structurés (ex. Titanic). Il se concentre sur l’utilisation de modèles supervisés comme les K-Nearest Neighbors (KNN) et les forêts aléatoires (Random Forest).

## Objectifs

- Prétraitement et analyse de données tabulaires.
- Comparaison de différents algorithmes de classification.
- Génération et évaluation de soumissions pour des compétitions de data science.
- Automatisation du workflow avec des notebooks interactifs.

## Structure du projet

```
├── train.csv                # Données d'entraînement
├── test.csv                 # Données de test
├── X_train.csv              # Variables explicatives (train)
├── X_test.csv               # Variables explicatives (test)
├── y_train.csv              # Variable cible (train)
├── gender_submission.csv    # Fichier de soumission exemple
├── submission.csv           # Soumission générée
├── submission2.csv
├── submission3.csv
├── Preprocessing.ipynb      # Prétraitement des données
├── KNN.ipynb                # Implémentation du modèle KNN
├── KNN_2.ipynb
├── KNN_3.ipynb
├── RandomForest.ipynb       # Implémentation du modèle forêt aléatoire
├── random_forest.ipynb
├── requirements.txt         # Dépendances Python
├── .gitignore               # Fichiers à ignorer par Git
```

## Prérequis & Installation

- **Python 3.x**
- Jupyter Notebook
- Installez les dépendances nécessaires :
  ```bash
  pip install -r requirements.txt
  ```

## Utilisation

1. Lancez Jupyter Notebook dans le dossier du projet :
   ```bash
   jupyter notebook
   ```
2. Ouvrez et exécutez les notebooks pour explorer le prétraitement et les différents modèles.
3. Modifiez les notebooks pour réaliser vos propres analyses et générer des fichiers de soumission.

---

**Ce projet est une base solide pour tout travail de machine learning en data science. Il valorise la compréhension du workflow ML : préparation des données, modélisation, évaluation et soumission.**
