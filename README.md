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
Pour avoir le formatage d'un titre sans rajouter d'entré dans l'index,

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


###############################################################
Méthodologie des techniques de la Canne de Combat et du Bâton
###############################################################


.. rubric:: Définition de la canne de combat

La Canne de Combat et le Bâton sont des sports de combat
utilisant une arme en bois conique et contondante. La
canne d’une longueur de 95 cm et d’un poids d’environ
120g se tient à une main. Le bâton, long de 140cm, pesant
environ 400g, se tient à deux mains.

Ces deux disciplines utilisent des mouvements de frappe
réalisés avec le côté de l’arme et non avec la pointe. Ce
sont des coups qui tranchent, apparentés aux coups de
taille du sabre sans les coups de pointe, dits d’estoc. Les
règles techniques des coups et les surfaces autorisées respectent
la méthodologie des techniques et le règlement
d’arbitrage de la Canne de Combat et du Bâton. L’esprit qui
anime ces disciplines dépend de la bonne application de
ces principes.

La pratique encore marginale de la double canne (activité
utilisant une canne dans chaque main avec les techniques
de la Canne de Combat) et du Panache (activité utilisant
à la fois les techniques de la Savate et de la Canne de
Combat), n’étant pas codifiée, respecte les règlements
techniques des différentes disciplines.

.. rubric:: Méthodologie de la canne de combat et du bâton


Ces disciplines s’inspirant des méthodes du 19 :sup:`ème`  siècle et
notamment de celle de Maître CHARLEMONT, ont été de
nouveau codifiées par Maurice SARRY dans les années
1970 dans le but de faire revivre ces disciplines et, pour ce
qui concerne la Canne de Combat, de l’adapter à la compétition.

En 2004, Bertrand DUBREUIL, Président du Comité National
de Canne de Combat et Bâton, réactualise les techniques
de la Canne de Combat et du Bâton en rédigeant
cette méthodologie.

Les éléments techniques fondamentaux et particuliers de
la Canne de Combat et du Bâton, hormis les coups eux-mêmes,
sont : la garde, la fente et l’armé. Leurs paramètres
techniques, empreints de l’histoire de ces disciplines et
de leurs valeurs d’efficacité, esthétiques et éducatives, sont
déterminants. Ils sont traités avec exhaustivité dans cette
méthodologie.


.. rubric:: Principe de base de l'activité canne de combat et bâton


Les caractéristiques techniques et réglementaires de la
pratique de la Canne de Combat et du Bâton sont fondées
sur une mise en situation d’opposition réelle. Elles sont
issues du principe d’efficacité lié aux paramètres matériels
(l’arme), historiques, physiologiques et esthétiques. Cette
situation d’opposition réelle s’exprime dans deux contextes
différents :

 * **Le cadre d’une situation duelliste**. Ce type de confrontation implique :

   * de l’incertitude, donc l’évaluation du risque et des opportunités
     d’actions dont l’objectif est de toucher sans être touché.

   * une aire de combat délimitée (circulaire de 9 m de diamètre),
     donc la gestion de l’espace dans la maîtrise des placements
     et des déplacements.

   * des formes de frappes codifiées, donc la caractérisation
     de l’arme (canne ou bâton), des cibles (tête, flanc, jambe),
     des trajectoires (4 coups verticaux, 2 coups horizontaux).

   * un temps limité (assauts de 3 à 4 reprises, chacune de 2
     minutes maximum), donc la gestion des ressources mentales
     et physiques.

 * **Le cadre d’une situation duettiste**. Ce type de confrontation implique :

   * de la coopération entre les tireurs, donc la simulation
     du risque et des opportunités d’actions dont l’objectif est
     démonstratif.

   * une aire de combat aux dimensions variables, donc
     l’adaptation des déplacements à l’espace.

   * des formes de frappes codifiées, donc la caractérisation
     de l’arme (canne ou bâton), des cibles (tête, flanc, jambe),
     des trajectoires (4 coups verticaux, 2 coups horizontaux).

   * des formes de frappes non codifiées, donc l’acceptation,
     uniquement pour le Bâton démonstratif, d’1 coup horizontal
     (coup coulissé ou glissé) et d’1 coup d’estoc (coup piqué)
     supplémentaires (voir :ref:`Methodologie_baton`).

   * un temps variable sans limite maximum, donc la gestion
     des ressources mentales et physiques.


Méthodologie des techniques de la Canne de combat
--------------------------------------------------



La garde
~~~~~~~~~

**Définition :** la garde est une position de départ ou d’attente
qui précède une action tactique, offensive ou défensive.
Cette posture doit placer le tireur dans un équilibre et une
prédisposition à l’impulsion musculaire qui lui permettent
d’accéder, le plus rapidement possible et avec aisance, à
toutes les attaques et défenses.


Paramètres techniques de la garde conventionnelle
++++++++++++++++++++++++++++++++++++++++++++++++++

**Définition :** la garde conventionnelle est la garde de
référence car c’est celle qui s’applique le mieux à la définition
ci-dessus. Pour les cannistes droitiers, la garde de
référence est la garde conventionnelle à droite, dite garde
à droite : la main droite munie de l’arme et le pied droit
sont à l’avant de la garde. Pour les cannistes gauchers, les
paramètres sont inversés.

La garde conventionnelle en Canne de combat est la garde
inverse du Bâton ou de la Boxe (ex : garde à droite en
Canne : main droite et pied droit devant ; garde à droite au
Bâton ou en Boxe : main gauche et pied gauche devant).



.. _Methodologie_baton:

Méthodologie des techniques du Batôn
-------------------------------------
