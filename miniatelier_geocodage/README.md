# Mini-atelier sur la geolocalisation des crimes sur le territoire montréalais
Cet atelier partira d’un cas particulier, la représentation spatiale de crimes sur le territoire montréalais. On verra comment importer un jeu de données depuis le site de Données Québec, puis on utilisera les extensions tidygeocoder et leaflet for R pour projeter ces données sur une carte de la Ville de Montréal.

## Source de donnees:
VILLE DE MONTRÉAL. Actes criminels, [Jeu de données], dans Données Québec, 2016, mis à jour le 08 mai 2025. [https://www.donneesquebec.ca/recherche/dataset/vmtl-actes-criminels], (consulté le 09 mai 2025).Attribution (CC-BY 4.0)

Date d'extraction : 9 mai 2025

# Prétraitement des données

Par exemple, les valeurs manquantes, etc. ont été supprimées.

# Dossiers

## Données
contient des tableaux de données.

**actes-criminels.csv** contient une table avec les crimes et leurs les cornonnées geographiques.

## Scripts
contient le code pour le prétraitement et l'analyse des données.

**atelier_actescriminel_geo.R**
Ce script génère différentes cartes pour localiser les crimes à Montréal. Il comprend également plusieurs petits défis.

## Figures
inclut les figures générés.

## Resultats
comprend des tableaux de fréquence et des données d'entrée pour générer les chiffres.

# Licence

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
