# Surveillance
Exercice de géocoding

Cet exercice donné par un ami Data Scientist consistait à traiter des données géographiques et temporelles.

Dans ce cadre j'ai créé des colonnes pour affiner l'analyse et rendre les informations plus lisibles.
De plus, vous trouverez des éléments d'analyse et de pistes de réflexions issues de mon travail sur les données.

Il est possible d'aller bien plus loin dans l'analyse des déplacements en croisant les utilisateurs par exemple...
Mais pour cela j'attends les directives du "bureau des légendes"

le data set events est un fichier JSON duquel nous avons tiré les colonnes suivantes : 

18162 lignes pour 4 colonnes

users/timestamp/latitude/longitude

Outils utilisés : 

Google colab : https://colab.research.google.com/drive/1l9QQnpKytJIHaSBifvOyRdKJ8PvZv9bn?usp=sharing#scrollTo=hImBSBdNQZwZ
Python
Requests
json
Pandas
Numpy
Datetime
Folium
geojson

Les objectifs fixés :

Afficher sur une carte les 3 premiers events du user "summers"
Combien d'events a produit le téléphone de "meltzer"
Sur quelle période s'étalent les events de "lowe" (date, heure du premier et dernier event)
Quel est le dernier event du dataset? Qui l'a produit? Où? Quand?
Ecris une fonction qui prend en entrée le nom d'un user et me renvoie le nombre d'événements que son téléphone a produit
