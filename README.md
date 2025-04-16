
---

## Scoring de Crédit – Prédiction du Risque de Défaut

Ce projet consiste à prédire le **risque de défaut de crédit** à partir d'un
ensemble de données bancaires disponibles sur **Kaggle**. 
Le but est de développer un modèle capable de déterminer la probabilité qu'un 
client de Home Credit fasse défaut sur son crédit en utilisant des variables économiques et financières.

### Objectifs du projet :
1. **Analyse exploratoire des données (EDA)** :
   - Compréhension des variables, exploration des données manquantes et des déséquilibres dans les classes.
   
2. **Préparation des données** :
   - Nettoyage des données (traitement des valeurs manquantes, encodage des variables catégorielles).
   - Gestion des données déséquilibrées avec des techniques comme le sur-échantillonnage (SMOTE) ou l'ajustement des poids de classe.

3. **Modélisation** :
   - Construction de modèles de prédiction pour le scoring de crédit (Logistic Regression, XGBoost, LightGBM).
   - Optimisation des hyperparamètres.

4. **Interprétation des résultats** :
   - Analyse de l'importance des variables (SHAP).
   - Évaluation de la performance du modèle avec des métriques adaptées comme la **ROC-AUC** et le **F1-score**.

5. **Visualisation des résultats** :
   - Graphiques pour observer la distribution des variables par rapport à la cible `TARGET`.
   - Boxplots et histogrammes pour analyser les différences entre les clients ayant fait défaut et ceux n'ayant pas fait défaut.

### Outils et technologies utilisés :
- **Python** (pandas, numpy, scikit-learn, matplotlib, seaborn, SHAP)
- **Modèles** : XGBoost, LightGBM, Logistic Regression
- **Frameworks** : Jupyter Notebook (pour le prototypage), PyCharm (environnement de développement)
- **Kaggle Dataset** : Home Credit Default Risk

### Structure du projet :
1. **Préparation des données** : `data_preprocessing.ipynb`
2. **Analyse exploratoire des données** : `eda_analysis.ipynb`
3. **Modélisation et évaluation** : `modeling.ipynb`
4. **Interprétation des résultats** : `shap_analysis.ipynb`
5. **Rapport et présentation finale** : `final_report.ipynb`




