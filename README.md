# ML-Project
# Prédiction des Charges Énergétiques des Bâtiments

Ce projet utilise des techniques de machine learning pour prédire les charges de chauffage et de refroidissement des bâtiments en fonction de diverses caractéristiques architecturales et physiques. Le dataset utilisé pour les entrainements des modèles est disponible ici : https://archive.ics.uci.edu/dataset/242/energy+efficiency ou dans le repertoire GitHub.

## Vue d'Ensemble du Projet

Le but de ce projet est de prédire la charge de chauffage (Heating Load) et la charge de refroidissement (Cooling Load) des bâtiments en utilisant diverses techniques de machine learning, notamment **XGBoost**, **Random Forest**, et **Régression Linéaire**.

## Structure du Dépôt

- `energy+efficiency.zip/` : Contient les fichiers de données 
- `Prediction_Energy_Consumption.ipynb/` : Contient le notebook Jupyter pour l'exploration des données et l'entraînement des modèles.
- `Prediction_Energy_Consumption.py/` : Contient les scripts Python pour le prétraitement des données, l'entraînement des modèles, et l'évaluation des modèles.
- `README.md` : Ce fichier, décrivant le projet et comment l'utiliser.
- `requirements.txt` : Liste des dépendances Python nécessaires pour exécuter le projet.

## Installation

### Prérequis

- Python 3.6+
- Libraries Python : `pandas`, `numpy`, `xgboost`, `scikit-learn`, `matplotlib`, `seaborn`, `shap`

### Installation des Dépendances

1. Clonez le dépôt GitHub sur votre machine locale:

   ```sh
   git clone https://github.com/yass-25/energy-prediction.git
   cd energy-prediction


###Utilisation
Exécution des Expériences via Notebook Jupyter
Ouvrez le notebook Jupyter notebooks/prediction_energy.ipynb:

jupyter notebook notebooks/prediction_energy.ipynb

Exécutez les cellules séquentiellement pour charger les données, entraîner les modèles, et visualiser les résultats.

Exécution Automatique avec Script
Un script Python scripts/run_experiments.py est fourni pour lancer les expériences automatiquement. Exécutez-le avec:


python scripts/run_experiments.py
