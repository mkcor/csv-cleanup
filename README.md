# csv-cleanup
Script pour charger, nettoyer et produire un beau CSV.

## Environnement

Je propose de rouler le projet localement, si les données sont confidentielles.
[Jupyter](http://jupyter.org/) va nous permettre d'utiliser les meilleurs
outils d'analyse de données, en R et en Python.
Donc nous voulons tout d'abord installer [Python 3](https://www.python.org/).
Ensuite nous voulons créer un environnement virtuel pour ce projet :

    $ mkdir -p ~/.virtualenv
    $ python3 -m venv ~/.virtualenv/csv-cleanup

Sous Ubuntu 14.04, il y a une erreur qui nous force à utiliser

    $ virtualenv --python=python3.4 ~/.virtualenv/csv-cleanup

(ce qui suppose d'avoir installé `virtualenv`).

Activatons notre environnement virtuel :

    $ source ~/.virtualenv/csv-cleanup/bin/activate

Et installons-y toutes les dépendances du projet :

    $ pip install -r requirements.txt

## Jupyter

Lançons le Jupyter Notebook
([anciennement](http://blog.jupyter.org/2015/04/15/the-big-split/) connu sous
le nom de IPython Notebook) pour explorer nos données et les transformer:

    $ jupyter notebook
