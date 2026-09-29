# 🥗 Open Food Facts — Analyse exploratoire & idée d'application

> Exploration statistique de la base Open Food Facts pour proposer une application innovante en lien avec l'alimentation et la santé publique.

---

## 🎯 Contexte

Dans le cadre d'un appel à projets de **Santé publique France**, ce projet analyse la base de données Open Food Facts pour évaluer la faisabilité d'une application destinée au grand public. L'enjeu : extraire des insights actionnables à partir de données massives et hétérogènes, et les communiquer de façon accessible à un public non expert.

---

## ⚙️ Ce que fait le projet

- **Nettoyage des données** — détection et traitement des valeurs manquantes (3 méthodes), identification des valeurs aberrantes, pipeline automatisé et robuste aux mises à jour du dataset
- **Analyse univariée** — distribution et comportement de chaque variable clé
- **Analyse multivariée** — corrélations, ACP, tests statistiques pour valider les hypothèses
- **Idée d'application** — proposition argumentée sur la base des données, avec évaluation de faisabilité

---

## 🛠️ Stack

`Python` `Pandas` `NumPy` `Matplotlib` `Seaborn` `Scipy` `Scikit-learn`

---

## 📁 Structure du projet

```
├── notebooks/
│   ├── 01_nettoyage.ipynb          # Traitement des données
│   ├── 02_analyse_univariee.ipynb  # Visualisations par variable
│   └── 03_analyse_multivariee.ipynb # Tests statistiques & corrélations
└── README.md
```

---

## 📂 Données

Base de données collaborative **Open Food Facts** — [world.openfoodfacts.org](https://world.openfoodfacts.org/data)

Plus de 2 millions de produits alimentaires référencés, avec composition nutritionnelle, labels, catégories et Nutri-Score.
