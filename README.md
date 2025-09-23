"# formation_SIG" 
Ce dépôt contient les travaux de ma formation personnelle en SIG avec QGIS et Python.

## Carte du Lundi 22 septembre : première carte des départements

- **Objectif** : prendre en main QGIS, créer une première carte simple.
- **Données** : GeoJSON/Shape des départements français.
- **Méthode** :
  1. Charger le GeoJSON des départements
  2. Explorer l’interface QGIS
  3. Appliquer un style simple (par défaut)
  4. Exporter la carte en image

- **Livrable** :
  - Carte PNG exportée
  - Projet QGIS (.qgz)

![Première carte départements](premiere_carte.png)

## Carte thématique : population par département (France)

- **Données utilisées** :
  - GeoJSON : contours des départements français
  - CSV : population par département (`DEP` = numéro département, `PTOT` = population totale)

- **Méthode** :
  1. Charger le GeoJSON et le CSV dans QGIS
  2. Faire une jointure attributaire sur le champ `DEP`
  3. Styliser la couche avec symbologie **graduée** sur `PTOT`
  4. Ajouter titre, légende, échelle, source dans le Print Layout
  5. Exporter la carte en PNG/PDF

- **Livrable** :
  - Carte PNG/PDF jointe dans le repo
  - Projet QGIS (`.qgz`) contenant toutes les couches et styles
