# 🌊 Analyse des vagues à Mooloolaba (Australie) – Python Data Analysis

Ce projet explore les données océanographiques recueillies par des bouées de mesure au large de Mooloolaba, en Australie.  
L’objectif est d’analyser la variation de la hauteur des vagues et de la température de surface selon les saisons à l’aide de **Python**.

## 📊 Données

📦 **Source :** [Kaggle – Waves Measuring Buoys Data (Mooloolaba)](https://www.kaggle.com/jolasa/waves-measuring-buoys-data-mooloolaba)  
Le dataset contient les mesures de hauteur de vagues (Hs, Hmax), périodes (Tz, Tp), direction (Peak Direction) et température de surface (SST) entre 2017 et 2018.

## 🧹 Étapes principales

- Nettoyage des valeurs aberrantes
- Conversion de la colonne temporelle `Date/Time` en format datetime
- Création d’un indicateur qualitatif de hauteur des vagues
- Suppression des données incomplètes de 2019

## 📈 Analyses réalisées

- Statistiques descriptives sur les hauteurs et températures
- Comparaison saisonnière des vagues (2017 vs 2018)
- Corrélations entre variables continues (heatmap)
- Régressions et distributions (regplot, jointplot)

## 🔍 Résultats

- Les vagues les plus hautes sont observées entre mars et avril.  
- Octobre enregistre les vagues extrêmes (>6 m).  
- Corrélation forte entre la hauteur significative et maximale (r ≈ 0.97).  
- Les conditions optimales combinent température élevée et vagues régulières.

## 🧠 Compétences mobilisées

**Hard skills :**  
- Python, Pandas, NumPy, Seaborn, Matplotlib  
- Analyse statistique et visualisation de données  
- Nettoyage et transformation des données  

**Soft skills :**  
- Esprit analytique  
- Rigueur scientifique  
- Communication visuelle claire  

## 💼 Auteur

**Maxime HERVÉ**  
📎 [Mon profil LinkedIn](https://www.linkedin.com/in/maxime-herve-05925a144/)  
📧 Contact : maxime.herve97@gmail.com
