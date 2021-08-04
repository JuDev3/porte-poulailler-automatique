# porte-poulailler-automatique
Déclenchement automatique de l'ouverture et fermeture d'une porte d'un poulailler

L'objectif du projet consiste à créer une solution autonome en énergie à base d'un RaspberryPi WH

# Heures d'ouverture et fermeture
Les heures d'ouverture et fermeture de la porte dépendent de l'époque de l'année.
En hivers les poules sortent et rentrent à des heures différentes qu'en été, elles sont ryhtmées par les heures de l'aube et du crépuscule.

Une première solution aurait consisté à utiliser un capteur de luminosité.
Une 2e solution consiste à utiliser une librairie Python.

Par souci de simplification électtronique et pour éviter toute panne, j'ai opté pour la seconde solution en utilisant la librairie PyEphem : https://github.com/brandon-rhodes/pyephem

# Gestion énergétique
