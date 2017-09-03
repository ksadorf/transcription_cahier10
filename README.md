# Installation et documentation


## Installation


Pour télécharge le cahier:

```
  git clone git@github.com:ksadorf/transcription_cahier10.git  
  pip install ./liblinkstream  
 ```


## Requirements

Optionnellement:

```
   virtualenv venv --python=python3
   source venv/bin/activate
```


Voir requirements.txt :

```
  pip install -r requirements.txt
```

## Aide sur la syntaxe result

Vous pouvez aller sur la documentaion de [sphinx](http://www.sphinx-doc.org/en/stable/rest.html).

### Ordre de section utilisé

rst n'impose auncun ordre et déduit le niveau (section, paragraphe, etc..) en fonction du premier signe rencontré.
L'ordre dans ce document est le suivant:  

   1. #
   2. -
   3. ~
   4. +
   5. "

Il est possible d'en utiliser d'[autre](http://www.sphinx-doc.org/en/stable/rest.html#sections).
Pour avoir le formatage d'un titre sans rajouter d'entré dans l'index, il faut
utiliser ``.. rubric:: Titre de section``.

## Construire le cahier 10

```
   cd docs/
   make html
```
ou
```
  cd docs/
  make latexpdf
```

Le site est dans le dossier ``docs/_build/html``.  
Ce dossier est ignoré par .gitignore.

## Construire le site pour la version web

```
  cd docs/
  make publish
```

Le site est alors construit à la racine.  
Il est encore nécessaire de commit et push le résultat.
