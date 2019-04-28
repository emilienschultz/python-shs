# Formation python pour les SHS

## Objectif de la formation

  * Comprendre l'intérêt de Python pour le script scientifique en SHS
  * Bases sur le langage
  * Présentation du Notebook Jupyter
  * Librairie Pandas pour manipuler des tableaux
  * Statistiques avec Python
  * Aller vers des fonctions avancées

La formation est prévue sur une journée. Par contre le contenu est très dense pour des débutants en script. Elle peut être décomposée sur deux jours, avec des périodes consacrées aux applications.

Attention : Python est présenté ici comme un outil pour le script scientifique, et non pas comme un langage de programmation pour développer des applications

## Elements concernant la formation du vendredi 26 avril

Les exercices d'illustration seront construits autour d'une étude de cas principale : analyser des éléments de presse autour du débat (sur le déremboursement de l'homéopathie).

Tous les documents utilisés dans la formation (code et jeux de données) sont sur ce dépôt Github.

Chacun.e est responsable d'__amener son ordinateur__.

__Tout le monde doit avoir installé Anaconda avant la formation, la connexion internet n'est pas garantie.__

Le planning pour une journée est le suivant : 
  * 9h-9h30 : Accueil et vérification des configurations
  * 9h30-10h : Présentation sur l'usage de python en recherche
  * 10h-11h30 : Bases de script python sous Jupyter
  * 11h30-12h30 : Librairie Pandas
  * 12h30-14h : Repas et échanges (le laboratoire fournit les sandwichs)
  * 14h-15h30 : Faire des statistiques avec Python
  * 15h30-16h30 : Hands on
  * 16h30-17h30 : Usages avancés (Webscraping,)


## Installation de Python

Python est un langage interprété qui nécessite un environnement. *Anaconda* est un environnement qui fournit l'ensemble des éléments nécessaires pour exécuter du code python. Il permet de construire des environnements (une version du langage et de librairies spécifiques) et de travailler au sein de ces environnements permettant d'en avoir plusieurs (par exemple, pour tester des versions différentes de librairies, etc.)
  * Télécharger __Anaconda__ pour votre OS en version python 3.7 : https://www.anaconda.com/distribution/
  * Installer (suivant que vous soyez sous Windows, Linux ou Mac, la procédure va changer)
  * Lancer Anaconda pour créer un environnement de travail
  	* Sur __windows__ : Aller dans environnements > Create > donner un nom (ex. p35) et une version de python 3.5 (__Attention bien installer la version 3.5 de python __)
  	* Sur __linux/mac__ : Ouvrir un terminal, puis créer un environnement en tappant la commande : conda create --name p35 python=3.5
  	(pour toute information sur les commandes conda : https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf)
  * Lancer python (sur windows en lançant Anaconda ; sous linux/mac en tapant la commande source activate p35 dans un terminal)
  * Installer les packages nécessaires à la formation (dans l'ordre): *matplotlib, jupyter, pandas, scipy, numpy, xlrd, bs4, urllib3, networkx, regex* (accepter si le logiciel vous propose d'installer les dépendances)
    * Sur windows, aller dans le gestionnaire de package
	* Sur linux/max : __conda install *nomdupackage*__ et si le package n'est pas trouvé, l'autre commande est __pip install *nomdupackage*__ (si vous n'avez pas *pip* pensez à l'installer https://ahmadawais.com/install-pip-macos-os-x-python/)

Pour vérifier l'installation :
* lancez un terminal (vous pouvez le faire sous le logiciel Anaconda) et vérifiez que ipython est bien installé en tapant *ipython*
* de manière similaire, lancez Jupyter notebook en tapant *jupyter notebook* 
* essayez d'importer les différentes librairies installées dans ipython en tapant : import nom_de_la_librairie (pandas par exemple)

## Autres logiciels

Installer Sublime text : https://www.sublimetext.com/ (pour visualiser des documents)

## Fichiers disponibles
  * 1 - Introduction : exemple de traitement d'une revue de presse
  * 2 - Rudiments de Python en situation : manipuler les données de la revue de presse
  * 3 - Passer sous Pandas : travailler sur une base de données
  * 4 - Traitements statistiques : analyser la base de données
  * 5 - Aller plus loin : scrapping, analyse lexicométrique et analyse de réseaux

## Ressources : ne pas hésiter à s'appuyer sur la communauté python

  * Nombreux tutoriaux : https://nealcaren.github.io/python-tutorials/
  * Tutoriaux vidéos SciPy 2018: https://www.youtube.com/playlist?list=PLYx7XA2nY5Gd-tNhm79CNMe_qvi35PgUR
  * Automatiser les tâches ennuyeuses : https://automatetheboringstuff.com/
  * Python for Social Science https://gawron.sdsu.edu/python_for_ss/course_core/book_draft/index.html
  * Et surtout : ce magnifique exemple autour du vélo http://jakevdp.github.io/blog/2014/06/10/is-seattle-really-seeing-an-uptick-in-cycling/