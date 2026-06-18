# 🍷 Optimisation des données commerciales d'une boutique e-commerce

## 🎯 Objectif

Optimiser la qualité et l'exploitation des données d'une boutique spécialisée dans la vente de vins et spiritueux afin de fiabiliser les indicateurs commerciaux et faciliter la prise de décision.

## 📌 Contexte

Projet réalisé dans le cadre de la formation **Data Analyst OpenClassrooms**.

L'entreprise Bottleneck utilise deux systèmes distincts :

* Un ERP pour la gestion des stocks et des prix d'achat
* Une boutique WooCommerce pour les ventes en ligne

L'absence de communication entre ces outils génère des erreurs et nécessite des traitements manuels chronophages.

## ❓ Problématique

Comment nettoyer, fusionner et analyser plusieurs sources de données afin de produire des indicateurs fiables et améliorer le pilotage de l'activité commerciale ?

## 📂 Sources de données

* ERP : stocks et prix d'achat
* WooCommerce : ventes et catalogue web
* Fichier de correspondance produits

## 🛠️ Méthodologie

### Audit qualité des données

Identification des anomalies :

* Doublons
* Produits sans identifiant
* Prix négatifs
* Stocks négatifs
* Incohérences de typage

### Nettoyage des données

* Suppression des doublons
* Correction des erreurs de prix
* Correction des erreurs de stock
* Gestion des valeurs manquantes
* Contrôle des formats de données

### Fusion des sources

Création d'un dataset unique regroupant :

* Produits
* Ventes
* Stocks
* Prix d'achat
* Prix de vente

### Analyse commerciale

* Chiffre d'affaires
* Volumes vendus
* Valorisation du stock
* Analyse des marges
* Analyse des corrélations
* Détection d'anomalies

## 📊 Principaux résultats

### Qualité des données

* 190 anomalies détectées puis corrigées
* Base de données fiabilisée à plus de 99 %

### Chiffre d'affaires

* Plus de 143 000 € de chiffre d'affaires analysés
* Forte concentration du CA sur une partie limitée du catalogue

### Analyse des ventes

* 5 750 unités vendues
* Environ 52 % des références génèrent 80 % du chiffre d'affaires

### Gestion des stocks

* Stock valorisé à près de 300 000 €
* Identification de stocks dormants à faible rotation

### Analyse des marges

* Marge brute moyenne proche de 37 %
* Détection de produits vendus à perte nécessitant une action corrective

## 📈 Analyses réalisées

* Analyse de Pareto (80/20)
* Analyse des ventes
* Analyse des stocks
* Analyse des marges
* Détection d'anomalies
* Corrélations entre prix, coûts et volumes vendus
* Recommandations business

## 🧰 Technologies utilisées

* Python
* Pandas
* NumPy
* Jupyter Notebook
* Excel

## 📁 Structure du projet

```text
data/
│
├── erp.xlsx
├── web.xlsx
├── liaison.xlsx

notebooks/
│
├── bottleneck_analysis.ipynb

presentation/
│
├── presentation.pdf

README.md
```

## 💡 Recommandations formulées

* Automatisation du processus de reporting
* Mise en place de contrôles qualité automatiques
* Optimisation de la politique tarifaire
* Réduction du stock dormant
* Concentration des efforts marketing sur les produits les plus rentables

## ✅ Compétences développées

* Data Cleaning
* Contrôle qualité des données
* Fusion de sources multiples
* Analyse exploratoire
* KPI commerciaux
* Analyse de rentabilité
* Détection d'anomalies
* Recommandations orientées business

## 👨‍💻 Auteur

**Mohamed Zaidi**
