# Projets de Statistique Industrielle – ISUP

Ce dépôt contient deux projets réalisés dans le cadre du cours de **Statistique Industrielle** au sein du master ISDS (Ingénierie Statistique et Data Science) de Sorbonne Université – ISUP, année 2024–2025. Chaque projet aborde un thème différent de l’analyse de risque et de l’optimisation appliquée à des systèmes réels.

---

## 📌 Projet 1 – Dimensionnement d’une digue (Analyse de fiabilité)

📁 `projet_digue/`

Objectif : déterminer la **hauteur optimale d’une digue** pour protéger une installation industrielle contre les crues, en intégrant incertitude et coût.

Approches mises en œuvre :
- Empirique : estimation de la surverse à partir de données historiques
- Probabiliste : modélisation hydraulique avec incertitude (Monte Carlo)
- Économique : minimisation du coût total (construction, maintenance, dommages)

📊 Outils : Python (`numpy`, `scipy`, `matplotlib`)

---

## 📌 Projet 2 – Optimisation de la qualité du sommeil (Plan d’expérience)

📁 `projet_sommeil/`

Objectif : identifier les **conditions optimales pour améliorer la qualité du sommeil**, en testant différents facteurs (température, activité, lumière) via un **plan Latin Hypercube**.

Méthodologie :
- Génération d’un plan d’expérience sous contraintes réelles (15 jours)
- Collecte des données via Apple Watch
- Régression linéaire + tests statistiques (Shapiro, Breusch-Pagan, Durbin-Watson)
- Validation des hypothèses et recommandations pratiques

📊 Outils : R (`DiceDesign`, `lm`, `car`, `ggplot2`)

