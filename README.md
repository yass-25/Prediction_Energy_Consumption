# ML-Project
# Prédiction des Charges Énergétiques des Bâtiments

Ce projet utilise des techniques de machine learning pour prédire les charges de chauffage et de refroidissement des bâtiments en fonction de diverses caractéristiques architecturales et physiques.

## Vue d'Ensemble du Projet

Le but de ce projet est de prédire la charge de chauffage (Heating Load) et la charge de refroidissement (Cooling Load) des bâtiments en utilisant diverses techniques de machine learning, notamment **XGBoost**, **Random Forest**, et **Régression Linéaire**.

## Structure du Dépôt

- `data/` : Contient les fichiers de données 
- `notebooks/` : Contient le notebook Jupyter pour l'exploration des données et l'entraînement des modèles.
- `scripts/` : Contient les scripts Python pour le prétraitement des données, l'entraînement des modèles, et l'évaluation des modèles.
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
