# PythonForDataAnalysis
DatasetForSensorlessDriveDiagnosis

Rachedi Yassine 

## DataSet

Lien : https://archive.ics.uci.edu/ml/datasets/Dataset+for+Sensorless+Drive+Diagnosis#

Un jeu de donnée composé de 49 colonnes : 48 de données et une derniére correspondant au label à catégoriser.

Ces données sont récupérées via WebScrapping

## Data visualisation

Trés peu d'information sont disponibles sur ce jeu de donnée pour pouvoir faire une étude poussée des données.
On peut afficher quelques statistiques (moyenne, max, min etc.) ainsi qu'un heatmap

## Modélisation

Le modéle choisi est un Random Forest Classifier, avec un score final à 0.99.
Une optimisation est réalisé, en supprimant 29 colonnes ( sans changer le score final du modéle ).
Une recherche des meilleurs hyper-paramétres (grid search) est aussi lancé.
