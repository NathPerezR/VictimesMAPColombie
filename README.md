# VICTIMES DE MINES ANTIPERSONNELS EN COLOMBIE
<!-- TABLE DES MATIERES -->
## Table de matières
1. [Présentation du projet](##pr%C3%A9sentation-du-projet)
    - [Source des données](#sources-des-donn%C3%A9es)
2. [User's Guide](#users-guide)
3. [Developer's Guide](#developers-guide)
4. [Analyse des résultats](#analyse-des-r%C3%A9sultats)
5. [Authors](#authors)

<!-- INTRODUCTION-->
## Présentation du projet

L’objectif principal de ce projet était de faire une analyse autour d’un sujet d’intérêt publique à l’aide des données publiques « Open Data » et d’un dashboard développé en **python**.

Les librairies ou modules utilisés sont : **pandas, dash, folium, plotly,** entre autres (voir détails dans _requirements.txt_). 

Le sujet d’analyse choisi concerne **La situation des victimes de mines antipersonnel (MAP) en Colombie**. Les données sont accessibles sur le site des données ouvertes du gouvernement Colombien: [datos.gov.co/Victimas-Minas-Antipersonal-en-Colombia](https://www.datos.gov.co/Inclusi-n-Social-y-Reconciliaci-n/Situaci-n-V-ctimas-Minas-Antipersonal-en-Colombia/yhxn-eqqw) ; fournies par le Département administratif de la Présidence de la République avec une fréquence de mise à jour tous les trois mois.

Ce registre inclut les accidents survenus entre 1990 et le mois précèdent à la dernière actualisation (le 15 décembre 2022), force publique et civil confondus.

<!-- SOURCES DES DONNÉES -->
### Sources des données
>DataSet

Situation Victimes : https://www.datos.gov.co/resource/yhxn-eqqw.json
>GeoGjon

Division par département :
<!-- USER'S GUIDE -->
## User's Guide

Pour lancer le projet, il faut :

1. Installer Python 3

2. Cloner le repo 
	```git clone https://github.com/github_username/repo_name.git```

	>Alternative à git : Télécharger le projet comprimé en cliquant en haut à droite.

3. Se placer dans le répertoire **MiniProjet**
	```cd /MiniProjet```
4. Installer les dépendances avec 
	 ```pip install -r requirements.txt _```

Liste des librairies/packages utilisés :

5. Lancer le dashboard avec
	```python /MiniProjet/main.py```(Windows) ou 
	```python3 main.py" ```(Linux)

6. Finalement ouvrir un Navigateur Web et aller à l'adresse indiqué sur la console : [http://127.0.0.1:8050](http://127.0.0.1:8050)

## Developer's Guide

<!-- RESULTS -->
## Analyse des résultats

À partir de cette étude on peut constater que le total de victimes de mines antipersonnel en Colombien enregistrés jusqu’à présent est de 12 273. L’histogramme met en évidence le  2006 comme l'année la plus critique puisqu'il y a eu 1 224 victimes, le nombre le plus élevé de toute l'histoire de la Colombie. Au cours de la dernière décennie, la tendance est à la baisse, à l'exception de 2012, atteignant en 2016 des niveaux jamais vus depuis 1999. En 2022, 107 victimes ont été signalées.

Parmi les victimes le 81 % (9 927) ont été blessées et le 19 % (2 346) sont décédées. D'autre part, la Colombie a été l'un des pays au monde avec le plus grand nombre de victimes de la force publique et cela signifie que sur le nombre total de victimes, 60% ont été des membres de la force publique et les 40 autres % correspondent à des civils.

## Authors
Nathalia PEREZ RAMIREZ
