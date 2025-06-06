# Projet d'EI BigData & Santé - APHP

## Structure du code

- `./data_raw/` contient les bases de données originales. 
- `./data_clean/` contient les bases de données qui ont été traitées. Les modifications appliquées sont détaillées dans le fichier `./src/clean_data.ipynb`.
- `./visuals/` contient les graphiques visuels représentant les données de manière visuel, avec des histogrammes et des graphiques.
- `./src/` contient tout les fichiers permettant de process les données 

## Le dossier source

Dans `src/`, il y a tout les fichiers. Pour construire l'ensemble du code, il faut exécuter dans l'ordre (en `run all`) les fichiers:

- `src/clean_data.ipynb`, pour générer les fichiers propres et traités 
- `src/improve_data.ipynb` (optionel), pour ajouter le facteur de risque liée au tabac avec le NLP

Ensuite, les fichiers `src/visualise.ipynb`, `src/statistics.ipynb` et `src/check_improvement.ipynb` peuvent être exécutés ou pas, dans un ordre quelconque.
Le premier fournis les graphiques utiles, le deuxième les données chiffrés de résultat et de précision, et le dernier permet de re-faire l'évaluation du NLP