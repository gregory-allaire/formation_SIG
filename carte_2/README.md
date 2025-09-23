"# formation_SIG" 
# Carte thématique population par département

## Données
- GeoJSON contours départements
- CSV population (DEP / PTOT)

## Méthode
1. Jointure attributaire dans QGIS (GeoJSON + CSV)
2. Symbologie graduée sur PTOT
3. Mise en page Print Layout
4. Export PDF/PNG

## Livrables
- `population_departements.qgz` : projet QGIS
- `population_departements.png` : carte finale
