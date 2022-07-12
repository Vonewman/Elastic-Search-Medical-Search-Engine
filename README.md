# Elastic-Search-Medical-Search-Engine

## Problematique

L'essor du moteur de recherche Google, ainsi que d'autres moteurs de recherche disponibles gratuitement, a facilité nos recherches quotidiennes en ligne. Selon la recherche, Google reçoit plus d'un milliard de questions sur la santé chaque jour. c'est-à-dire que 7% des recherches quotidiennes de Google sont liées à la santé.

Traditionnellement, la médecine ne reposait que sur la discrétion conseillée par les médecins. Par exemple, un médecin devrait suggérer un médicament approprié en fonction des symptômes d'un patient. Cependant, ce n'est pas toujours correct. Les informations médicales en ligne peuvent accroître les connaissances, les compétences et l'engagement des patients dans les stratégies de prise de décision en matière de santé. Les enquêtes médicales en ligne indépendantes peuvent compléter et être utilisées en synergie avec les interactions médecin-patient dans la clinique.

![Build Medical Search Engine](https://miro.medium.com/max/1400/1*96OxtsVCaYO4vcBGv83CIg.jpeg)

Pour mener a bien ce projet nous allons:

1. Collecter les donner pour le projet (Web Scraping?)
2. Stockez les données récupérées dans Redis et MongoDB
3. Data Cleaning and Preprocessing
4. Charger les données dans Elastic Search
5. Créer une interface utilisateur à l'aide de Flask
6. Créez une API Rest qui appelle l'endpoint pour chaque recherche de médicament
7. Faire une requête CURL pour chaque recherche et obtenez les détails
8. Déployer le projet sur Herok
