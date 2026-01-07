# Power BI – End-to-End Churn Analysis

## 📌 Présentation du projet

Ce projet est une **analyse end-to-end du churn client** combinant **SQL, Power BI et Machine Learning**. Il couvre l’ensemble du pipeline data : de la préparation des données jusqu’à la visualisation et la prédiction des clients à risque de résiliation.

L’objectif est de fournir un **tableau de bord décisionnel clair** permettant aux équipes métiers d’identifier les facteurs clés du churn et d’anticiper les départs clients.

---

## 🎯 Objectifs

* Analyser le comportement des clients et identifier les profils à risque
* Mesurer le churn à l’aide de KPI clairs et actionnables
* Mettre en place une segmentation pertinente (âge, ancienneté, contrat, services, paiement, etc.)
* Prédire les clients susceptibles de churner via un modèle de Machine Learning

---

## 🛠️ Technologies utilisées

* **SQL** : extraction et préparation des données
* **Power BI** :

  * Power Query (nettoyage et transformations)
  * Modélisation des données
  * DAX (mesures et KPI)
  * Visualisations interactives
* **Machine Learning (Python)** :

  * Entraînement d’un modèle de prédiction du churn
  * Génération des clients prédits comme churners

---

## 🔄 Pipeline du projet

1. Extraction des données via SQL
2. Nettoyage et transformations avec Power Query
3. Création de tables de mapping (âge, ancienneté, services)
4. Modélisation et calcul des KPI avec DAX
5. Analyse descriptive du churn
6. Prédiction du churn via Machine Learning
7. Intégration des résultats de prédiction dans Power BI

---

## 📊 Tableau de bord Power BI

### 🔹 Page Résumé

Cette page fournit une **vue globale du churn** à travers :

* Nombre total de clients
* Nombre de nouveaux clients
* Nombre de clients churnés
* Taux de churn
* Répartition des clients par profil (contrat, paiement, ancienneté, démographie, etc.)

📷 *Capture d’écran – Page Résumé Power BI*


![Page Résumé](https://github.com/raskel00/powerbi-end-to-end-churn-analysis/blob/main/rs.png))


---

### 🔹 Page Prédiction du Churn

Cette page met en avant les **résultats du modèle de Machine Learning** :

* Nombre de clients prédits comme churners
* Profils des clients à risque
* Segmentation des churners prédits selon différents critères

📷 *Capture d’écran – Page Prédiction du Churn*

![Page Prédiction](https://github.com/raskel00/powerbi-end-to-end-churn-analysis/blob/main/pdc.png)


---

## 📈 Indicateurs clés (KPI)

* Total Customers
* New Joiners
* Total Churn
* Churn Rate
* Count of Predicted Churners

---

## 💡 Valeur métier

* Aide à la **prise de décision stratégique**
* Identification proactive des clients à risque
* Optimisation des actions de rétention
* Meilleure compréhension des facteurs influençant le churn

---

## 🚀 Cas d’usage

* Télécoms
* Banques et assurances
* FinTech
* SaaS et abonnements

---



## 👤 Auteur

Projet réalisé dans un objectif **portfolio professionnel** en Data Science / Data Analytics.

N’hésitez pas à explorer le dashboard et à me contacter pour toute question ou collaboration.
