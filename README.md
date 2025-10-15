# 🏥 Prédiction des Charges Médicales avec l’Apprentissage Automatique

## 📘 Contexte du Projet  
Ce projet vise à développer un **modèle d’intelligence artificielle** capable de **prédire les charges médicales** que chaque assuré devra payer à partir de critères cliniques et personnels (âge, sexe, IMC, tabagisme, etc.).  
L’objectif est de fournir un outil d’aide à la décision pour les compagnies d’assurance afin d’anticiper les coûts, d’améliorer la transparence et d’optimiser les politiques tarifaires.

---

## 🧩 Objectif Global  
- Construire un pipeline complet allant du **prétraitement des données** à la **prédiction des charges médicales**.  
- Comparer plusieurs modèles de **régression supervisée** et sélectionner le plus performant.  
- Fournir une **interface simple** permettant de tester le modèle final.  

---

## 🧠 Approche Méthodologique  
1. **Préparation des données** : nettoyage, encodage, normalisation.  
2. **Analyse exploratoire (EDA)** : étude des distributions, corrélations et détection d’anomalies.  
3. **Entraînement des modèles** : Linear Regression, Random Forest, XGBoost, SVR.  
4. **Évaluation** : calcul des métriques RMSE, MAE et R².  
5. **Optimisation** : tuning des hyperparamètres avec GridSearchCV / RandomizedSearchCV.  
6. **Déploiement** : sauvegarde du modèle et création d’une interface d’utilisation.

---

## 📊 Métriques d’Évaluation  
| Métrique | Description |
|-----------|--------------|
| **RMSE** | Racine de l’erreur quadratique moyenne |
| **MAE** | Erreur absolue moyenne |
| **R²** | Coefficient de détermination |

---

## 🧰 Outils et Librairies Utilisés  
- **Python 3.x**  
- **Pandas**, **NumPy**  
- **Matplotlib**, **Seaborn**  
- **Scikit-learn**  
- **XGBoost**  
- **Joblib**  
- **Jupyter Notebook**

---

## ⚙️ Installation et Exécution  

### 🔹 1. Cloner le dépôt  
```bash
git clone https://github.com/bouchramilo/medical-charges-prediction
cd medical-charges-prediction
```

***
Thank you 😊
