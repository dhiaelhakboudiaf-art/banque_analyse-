

Ce notebook Python a pour objectif l’analyse et l’exploration de données bancaires issues d’un fichier CSV (privé.csv) dans le cadre d’un projet BEA.
Il permet de :

Charger et nettoyer des données de crédits bancaires

Identifier les dossiers bénéficiant de dispositifs de soutien de l’État (ANSEJ / CNAC)

Séparer les crédits soutenus des crédits classiques

Analyser les créances contentieuses et les montants compromis

Réaliser des statistiques agrégées par agence

Visualiser les résultats à l’aide de graphiques

Le projet utilise principalement Pandas, NumPy, Matplotlib et Seaborn pour la manipulation, l’analyse et la visualisation des données.

PROJET BEA – Analyse des Crédits Bancaires

 Description
Ce projet vise à analyser des données de crédits bancaires afin d’évaluer
l’exposition au risque, la répartition des dossiers et l’impact des dispositifs
de soutien de l’État (ANSEJ / CNAC).

L’analyse est réalisée à l’aide de Python et de bibliothèques de data science.

---

Structure du projet

- projet bea.ipynb   → Notebook principal d’analyse
- privé.csv          → Données sources (confidentielles)
- README.md          → Documentation du projet

---

 Technologies utilisées

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

 Fonctionnalités

- Nettoyage et préparation des données
- Détection automatique des crédits ANSEJ / CNAC
- Séparation des crédits soutenus et classiques
- Calcul des créances contentieuses
- Analyse des montants compromis (50% / 100%)
- Agrégation par agence
- Visualisation des résultats

---
 Exécution

1. Installer les dépendances :
```bash
pip install pandas numpy matplotlib seaborn
