# Observatoire National des Risques (ONR)

<p align="center">
  <img src="logo/logo.png" alt="Logo ONR" width="180">
</p>

## Vue d'ensemble du Projet
L'**Observatoire National des Risques (ONR)** est une plateforme web interactive et pédagogique conçue pour centraliser et visualiser l'information sur les risques majeurs (naturels et technologiques) en France. Ce projet fournit aux citoyens, aux collectivités et aux chercheurs un outil d'exploration des données de planification et de prévention via une approche **Story Map**.

## Objectifs
* **Pédagogie Citoyenne :** Rendre les informations complexes (PPR, PPRT, Seveso, Radon, Inondation) accessibles.
* **Visualisation Cartographique :** Afficher des indicateurs clés sur le territoire.
* **Outil d'Aide à la Décision :** Permettre l'identification rapide des zones d'engagement en matière de prévention.

## Caractéristiques Techniques

### 1. Cartes Synthétiques de la Prévention
* **Méthodologie :** Utilisation de **centroïdes départementaux**.
* **Indicateur :** La taille du centroïde est **proportionnelle au nombre de communes du département** ayant mis en place un Plan de Prévention des Risques (PPR ou PPRT).

### 2. Pages Thématiques Détaillées
Chaque risque (Inondation, Séisme, Nucléaire, Mouvements de Terrain, Radon, Industriel) est documenté par :
* **Synthèses réglementaires :** Descriptions des aléas et outils de prévention (PPRI, PPRT, Eurocode 8).
* **Chronologies Graphiques :** Frises historiques des événements majeurs et des évolutions de la loi.
* **Analyses Statistiques :** Graphiques de répartition (ex: Échelle INES, Accidentologie par secteur).

## Métadonnées et Sûreté des Données
Les données sont issues de sources officielles (Sisfrance, ARIA, Géorisques, IRSN) et traitées pour garantir une précision géographique optimale :
* **Projection :** WGS84 (EPSG:4326).

* **Processus :** Nettoyage, harmonisation des champs et jointures aux référentiels.
