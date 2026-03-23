# From scraping to visualization

## À propos
Ce projet explore la fiscalité mondiale à travers un cheminement complet : de la collecte des données par web scraping sur Wikipedia jusqu'à la création de cartes et de graphiques comparatifs. Il a été réalisé dans le cadre du cours "Data visualization for economics" en Master 2 à AMSE.

## Contenu du dépôt
- `yating-s-assign3.pdf` : Rapport final du projet
- `income_tax_rates_cleaned.csv` : Base de données utilisée et nettoyée

## Compétences mises en œuvre
- **Web scraping** : Récupération des données fiscales depuis Wikipedia avec le package `rvest`
- **Nettoyage et manipulation** : Transformation des données avec `dplyr`
- **Enrichissement géographique** : Ajout des continents avec `countrycode`
- **Analyse comparative** : Comparaison des taux d'imposition sur le revenu et de la TVA par continent
- **Visualisation** : Graphiques en barres avec `ggplot2` et cartes du monde
- **R Markdown** : Production d'un rapport final au format PDF

## Travail réalisé
1. Scraping du tableau des taux d'imposition sur Wikipedia
2. Nettoyage et conversion des données en valeurs numériques
3. Ajout des continents pour l'analyse géographique
4. Calcul des moyennes par continent
5. Création de graphiques comparatifs (impôt sur le revenu vs TVA)
6. Cartographie des taux d'imposition dans le monde
7. Gestion des données manquantes
8. Visualisation libre avec données INSEE

## Contexte académique
Projet réalisé dans le cadre du cours "Data visualization for economics" - Master 2 Économie, parcours Données, Analyse, Décision et Évaluation Économique, AMSE.
