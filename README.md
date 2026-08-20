# 🎨 Atelier Seaborn – Capteurs IoT

## 📌 Contexte

Après NumPy, Pandas et Matplotlib, cet atelier utilise **Seaborn** pour réaliser une analyse exploratoire plus riche des données de capteurs IoT (température, humidité, pression, consommation énergétique).

Atelier réalisé dans le cadre du cours **Python pour ML et IA** – P1 IA, Orange Digital Center (ODC) 

## 🎯 Objectifs

- Visualiser des distributions avec des outils Seaborn-natifs
- Comparer des distributions par catégorie (bâtiment, état)
- Étudier des relations et tendances entre variables
- Analyser des corrélations et une analyse multivariée
- Exporter les graphiques produits

## 🗂️ Structure du projet

```
atelier_seaborn_iot/
├── data/
│   └── mesures_capteurs.csv
├── notebooks/
│   └── atelier_seaborn_iot.ipynb
└── exports/
    ├── temperature.png
    ├── temperature.pdf
    └── ...
```

## 🧩 Contenu de l'atelier

| Partie | Fonction Seaborn | Objectif |
|---|---|---|
| 1 | `histplot()` | Distribution des températures (globale et par bâtiment) |
| 2 | `kdeplot()` | Distribution lissée des températures (globale et par bâtiment) |
| 3 | `boxplot()` | Médiane, dispersion et valeurs extrêmes par bâtiment |
| 4 | `violinplot()` | Distribution enrichie par rapport au box plot |
| 5 | `countplot()` | Comptage des états des capteurs par bâtiment |
| 6 | `scatterplot()` | Relation température / consommation (globale et par bâtiment) |
| 7 | `regplot()` | Tendance entre température et consommation |
| 8 | `lmplot()` | Tendance par bâtiment |
| 9 | Corrélations + `heatmap()` | Matrice de corrélation entre température, humidité, pression, consommation |
| 10 | `pairplot()` | Analyse multivariée (distributions + scatter plots croisés) |
| 11 | Export | Sauvegarde des graphiques dans `exports/` |
| 12 | Bonus | Fonctionnalité additionnelle pertinente |

## 🔍 Points clés d'analyse

- Identification du bâtiment ayant le plus de mesures en état ALERTE/ERREUR
- Corrélations positives, négatives et proches de zéro entre variables
- Comparaison box plot vs violin plot pour la richesse d'information sur la distribution

## ▶️ Utilisation

```bash
pip install seaborn matplotlib pandas numpy jupyter
jupyter notebook notebooks/atelier_seaborn_iot.ipynb
```

## 📦 Livrable attendu

Dossier `atelier_seaborn_iot/` complet, poussé sur un dépôt public GitHub avec commits explicites au fur et à mesure.

## 👤 Auteure

**Rokhaya Coumba Diouf** –  parcours IA (P1 IA) Orange Digital Center (ODC)
