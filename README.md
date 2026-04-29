# 📊 Projet d'apprentissage supervisé – Prédiction de la puissance éolienne

## 🎯 Objectif du projet

Ce projet a pour but de prédire la **puissance produite par une éolienne** à partir de la **vitesse du vent**, en utilisant différentes méthodes de régression en machine learning.

---

## 📁 Structure du projet

```
Projet-apprentissage-supervise/
│
├── data/
│   └── Wind_turbine_data.csv
│
├── notebooks/
│   └── projet_apprentissage_supervise.ipynb
```

---

## ⚙️ Technologies utilisées

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🔎 Étapes du projet

### 1️⃣ Visualisation des données

* Analyse des relations entre :

  * vitesse du vent 🌬️
  * direction du vent
  * puissance produite ⚡
* Identification des tendances principales

---

### 2️⃣ Préparation des données

* Nettoyage du dataset
* Suppression des valeurs non pertinentes
* Conversion des dates
* Création des variables explicatives (X) et cible (y)

---

### 3️⃣ Modélisation

* Création de plusieurs modèles :

  * Régression Lasso
  * Régression ElasticNet
* Transformation polynomiale des données

---

### 4️⃣ Optimisation (Cross-validation)

* Utilisation de `GridSearchCV`
* Sélection des meilleurs hyperparamètres
* Validation croisée (k-fold)

---

### 5️⃣ Utilisation des pipelines

* Chaînage des étapes :

  * transformation
  * scaling
  * modèle
* Code plus propre et plus fiable

---

### 6️⃣ Comparaison des modèles

* Comparaison entre :

  * Lasso
  * ElasticNet
  * SVR (Support Vector Regression)
* Analyse visuelle des prédictions

---

### 7️⃣ Prédiction finale

* Utilisation du meilleur modèle (SVR)
* Estimation de la production énergétique d’un champ de **50 éoliennes**
* Conversion de la puissance (kW) en énergie (kWh)

---

## 📈 Résultats

* La vitesse du vent est la variable la plus importante
* Le modèle SVR donne les meilleures performances
* Le modèle permet d’estimer la production énergétique mensuelle

---

## 🚀 Lancer le projet

### 1. Installer les dépendances

```bash
pip install -r requirements.txt
```

### 2. Ouvrir le notebook

```bash
cd notebooks
jupyter notebook
```

---

## 📌 Conclusion

Ce projet démontre l’importance :

* de la préparation des données
* du choix des modèles
* de la validation croisée
* de l’interprétation des résultats

Le machine learning permet ici de répondre à un problème concret :
👉 **estimer la production d’énergie renouvelable**

---

## 👤 Auteur

Jeremy-James Noivo
