# Projet Analyste Business Intelligence — EFM Dashboard

## Description du Projet
Ce projet a été réalisé dans le cadre de l'Examen de Fin de Module (EFM) pour concevoir un système d'aide à la décision complet (Business Intelligence) axé sur la performance des ventes mondiales, la normalisation financière et l'analyse de rentabilité multi-marchés.

## Indicateurs Clés & Impact Décisionnel
* **Pilotage Stratégique :** Visualisation interactive et monitoring d'un volume global de **984M de revenus** et **2,43M d'unités vendues**.
* **Analyse de Rentabilité :** Analyse comparative fine par marché géographique (ex: identification d'une hausse de **+4,86% à Surat** vs une baisse critique de **-20,78% à Bengaluru**), garantissant une précision des données à 99%.
* **Engineering des Données (ETL Pipeline) :** Automatisation du processus de nettoyage, de traitement et de normalisation automatique des devises multi-marchés pour fiabiliser les rapports consolidés.

## Tech Stack & Outils
* **Visualisation BI :** Tableau Software (`.twbx` joint).
* **Traitement & Bases de Données :** MySQL / Advanced Power Query.
* **Documentation :** Rapport technique complet (`.docx`) et Support de présentation exécutif (`.pptx`).

## Contenu du Repository
* `EFM_EFM.twbx` : Le classeur Tableau interactif contenant l'ensemble des dashboards dynamiques.
* `RAPPORT_EFM_DASHBORD.docx` : Le rapport d'analyse détaillé spécifiant la logique ETL et les insights métiers.
* `dashbord (1).pptx` : La présentation destinée aux équipes de direction pour l'aide à la décision.

  ##  Analyse Détaillée des Dashboards (Tableau Revenue & Profit Analytics)

Voici l'explication business et technique des deux dashboards interactifs conçus sous Tableau Software pour le pilotage de la performance globale de l'entreprise.

###  1. Dashboard : Analyse des Profits & Tendances de Marge
Ce tableau de bord est axé sur la rentabilité financière brute (Profitability Analysis) et le comportement des canaux de vente.

* **Les Top KPIs Financiers :**
  * **Total Revenue (984.87M) :** Le Chiffre d'Affaires global généré sur la période historique (2017-2020).
  * **Total Profit (24.66M) :** Le bénéfice net global après déduction des coûts associés.
* **Segmentation par Type de Client (Pie Chart) :**
  * Le canal physique **Brick & Mortar (Magasins)** domine largement le modèle économique avec **75,60%** des parts de marché, tandis que le canal **E-Commerce** représente **24,40%**.
* **Analyse Temporelle (Profit Trend) :**
  * Une courbe temporelle qui retrace l'évolution des marges par année. On observe des pics de performance critiques à **115.92M** et **105.53M**, permettant d'identifier la saisonnalité des ventes.
* **Matrice de Performance par Marché (Revenue vs Profit Margin) :**
  * **Mumbai** s'impose comme le marché le plus volumique en termes de revenus (Top des ventes), mais l'analyse de la marge révèle des disparités importantes (ex: **Surat affiche une profitabilité de +4,86%** tandis que **Bengaluru accuse une sous-performance critique à -20,78%**).

---

###  2. Dashboard : Analyse du Chiffre d'Affaires & Distribution Commerciale
Ce visuel permet de piloter la distribution logistique et d'identifier la concentration des ventes (Loi de Pareto).

* **Indicateurs d'Activité Générale :**
  * **Sales Quantity (2.429.282) :** Plus de 2,42 millions d'unités vendues et expédiées à travers les différents marchés régionaux.
* **Classement Géographique (Sales Quantity by Market) :**
  * **Delhi NCR** et **Mumbai** occupent la tête du classement en termes de volume d'unités écoulées, s'affirmant comme les hubs logistiques majeurs de l'activité commerciale.
* **Top 5 Clients & Top 5 Produits (Analyse de Concentration) :**
  * Visualisation immédiate des comptes clés (ex: **Electricalslytic** et **Premium Stores** génèrent à eux seuls les plus gros volumes de facturation).
  * Identification du catalogue produit leader (le produit **Prod040** mène le classement avec un montant normalisé de **22.58M**, suivi de près par **Prod159** à **17.66M**).
* **Évolution Annuelle (Revenue by Years) :**
  * Un graphique linéaire qui suit la trajectoire des revenus à travers les années. Il permet aux équipes de direction de valider les taux de croissance annuels et de prévoir la demande future (Demand Forecasting).

---

##  Accès aux Livrables et Visuels
Pour consulter l'intégralité du design et des rapports, vous pouvez ouvrir directement les fichiers d'export officiels joints dans ce dépôt :

* [👉 Cliquer ici pour ouvrir le Dashboard PDF (dashboard.pdf)](dashboard.pdf)
* [👉 Cliquer ici pour télécharger le classeur Tableau interactif (EFM_EFM.twbx)](EFM_EFM.twbx)
* [👉 Ouvrir le Rapport Technique d'Analyse complet (RAPPORT_EFM_DASHBORD.docx)](RAPPORT_EFM_DASHBORD.docx)
