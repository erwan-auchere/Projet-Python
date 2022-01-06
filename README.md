# Utilisation des données du fichier BAAC pour prédire la gravité d'accidents routiers

Ce projet cherche à exploiter les données mises à disposition par le Minstère de l'Intérieur sur les accidents routiers ayant eu lieu en France en 2019 afin de prédire la gravité d'un accident en fonction de ses caractéristiques.

Contenu du dépôt :

- `Compte-rendu.ipynb` : notebook final contenant toutes les étapes de notre analyse : récupération et nettoyage des données, visualisation des données et modélisation.
- `randomforest-balanced_lzma.zip`, `randomforest-optimized.zip`, `randomforest-optimized.zip` et `REG-KNN-SVC.zip` : archives contenant les modèles entraînés, elles seront automatiquement décompressées par le code de `Compte-rendu.ipynb`.
- `departements-france.csv` et `regions_2015_metropole_region.geojson` : fichiers de données géographiques nécessaires au tracé de la carte.
