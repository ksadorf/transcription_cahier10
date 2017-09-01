# Installation et documentation


## Installation


Pour télécharge le cahier::

  git clone git@github.com:ksadorf/transcription_cahier10.git
  pip install ./liblinkstream



## Requirements

Optionnellement:
``
   virtualenv venv --python=python3
   source venv/bin/activate
``


Voir requirements.txt ::
  pip install -r requirements.txt

## Construire le cahier 10

``
   make html
``
ou
``
 make latexpdf
``

Le site est dans le dossier ``./_build/html``.
Ce dossier est ignoré par .gitignore.

## Construire le site pour la version web

``
   make publish
``

Le site est dans le dossier ``./html``.
Il est encore nécessaire de commit et push le résultat.
