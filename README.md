# Formation python pour les SHS

## Objectif de la formation

  * Comprendre l'intérêt de Python pour le script scientifique en SHS
  * Bases sur le langage
  * Présentation du Notebook Jupyter
  * Librairie Pandas pour manipuler des tableaux
  * Statistiques avec Python
  * Aller vers des fonctions avancées

 Attention : Python est présenté ici comme un outil pour le script scientifique, et non pas comme un langage de programmation pour développer des applications


## Elements concernant la formation du vendredi 26 avril

Les exercices d'illustration seront construits autour d'une étude de cas : analyser des éléments de presse autour du débat sur le déremboursement de l'homéopathie.

Tous les documents utilisés dans la formation (code et jeux de données) sont sur ce dépôt Github.

Chacun.e est responsable d'amener son ordinateur.

Tout le monde doit avoir installé Anaconda avant la formation, la connexion internet n'est pas garantie.

Le planning prévu est le suivant : 
  * 9h-9h30 : Accueil et vérification des configurations
  * 9h30-10h : Présentation sur l'usage de python en recherche
  * 10h-11h30 : Bases de script python sous Jupyter
  * 11h30-12h30 : Librairie Pandas
  * 12h30-14h : Repas et échanges (pour l'instant, chacun prend charge de son repas)
  * 14h-15h30 : Faire des statistiques avec Python
  * 15h30-16h30 : Hands on
  * 16h30-17h30 : Usages avancés (Webscraping,)


## Installation de Python

Python est un langage interprété qui nécessite un environnement. *Anaconda* est un environnement qui fournit l'ensemble des éléments nécessaires pour exécuter du code python. Il permet de construire des environnements (une version du langage et de librairies spécifiques) et de travailler au sein de ces environnements permettant d'en avoir plusieurs (par exemple, pour tester des versions différentes de librairies, etc.)
  * Télécharger Anaconda pour votre OS en version python 3.7 : https://www.anaconda.com/distribution/
  * Installer (suivant que vous soyez sous Windows, Linux ou Mac, la procédure va changer)
  * Lancer Anaconda pour créer un environnement de travail
  	* Sur windows : Aller dans environnements > Create > donner un nom (ex. p35) et une version de python 3.5
  	* Sur linux/mac : Ouvrir un terminal, puis créer un environnement en tappant la commande : conda create --name p35 python=3.5
  	(pour toute information sur les commandes conda : https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf)
  * Lancer python (sur windows en lançant Anaconda ; sous linux/mac en tapant la commande source activate p35 dans un terminal)
  * Installer les packages nécessaires à la formation : pandas, jupyter, scipy, xlrd
    * Sur windows, aller dans le gestionnaire de package
	* Sur linux/max : conda install *nomdupackage*

## Ressources

  * Nombreux tutoriaux : https://nealcaren.github.io/python-tutorials/
  * Tutoriaux SciPy 2018: https://www.youtube.com/playlist?list=PLYx7XA2nY5Gd-tNhm79CNMe_qvi35PgUR

