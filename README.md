# REXIA - Responsible and Explainable AI

## TP 1 – Données Tabulaires

### Introduction

Ce travail pratique explore l'application de techniques d'IA responsable et explicable à des données tabulaires de ressources humaines. L'objectif est de prédire les démissions d'employés tout en garantissant la transparence et l'interprétabilité des modèles choisies.

TP réalisé dans le cadre du cours Responsible and Explainable AI à CentraleSupélec.

## Structure du projet

1. **Analyse des données**
   - Exploration des caractéristiques du dataset
   - Analyse des profils d'employés
   - Études de corrélation

2. **Apprentissage automatique**
   - Entraînement de trois modèles transparents : **Régression logistique**, **Arbre de décision** et  **Random Forest**
   - Évaluation des performances

3. **Explication post-hoc**
   - Application de techniques d'explication : **Tests de signification statistique (tests t)** pour identifier les caractéristiques les plus pertinentes & **LIME**
   - Réduction des caractéristiques basée sur leur significativité

4. **Réentraînement sur données réduites**
   - Nouvelle formation des modèles avec caractéristiques réduites
   - Comparaison des performances

## Utilisation

Pour exécuter ce projet, assurez-vous d'avoir Python 3.8+ installé sur votre machine.

### Installation des dépendances

1. Clonez ce dépôt
2. Installez les dépendances requises :
   ```
   pip install -r requirements.txt
   ```
3. Exécutez les cellules dans l'ordre pour reproduire l'analyse

## Auteurs
- Rayane bouaita
- Gabriel Trier
