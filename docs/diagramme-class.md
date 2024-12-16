# Diagramme de classe (UML)

Ce fichier présente en détail les concepts clés du diagramme de classe en UML.

## Les classes

Tout d'abord, il faut créer une classe et lui donner un nom.
*(par exemple, une classe animal dans le cadre d'un diagramme de classe pour un zoo)*

### De quoi est composée une classe ?
Cette classe comporte 2 parties :
- **Attributs** : valeurs décrivant chaque instance de cette classe -> à inscrire dans la première moitié de la classe
Un attribut doit commencer par une minuscule et être en camelCase.
Elle doit spécifier le type de données de l'attribut.


- **Méthodes** : les comportements de la classe ->  à inscrire dans la seconde moitié de la classe
Pareillement, une méthode doit commencer par une minuscule et être en camelCase.

Elle est composée d'une **visibilité** qui est décrite ci-dessous.

### Qu'est-ce que la visibilité ?

La visibilité établit les règles d'accès aux attributs et méthodes d'une classe.
En ce qui concerne les **attributs**, la visibilité de l'attribut peut être spécifiée :
- **+** : **public** -> accessible par toutes les classes
- **-** : **private** -> aucune autre classe ne peut accéder à cet attribut
- **#** : **protected** -> accessible par les classes enfants
- **~** : **package** -> accessible par les classes du même package (rarement utilisé)

*Tip : Dans la plupart des cas, les attributs sont privés, donc la visibilité indiquée est « **-** ».*
*Les méthodes sont publiques de manière générale.*

Cette **visiblité** doit être placée avant le nom de l'attribut (donc à gauche).
Il est possible de spécifier la visibilité des méthodes de la même manière, mais cela est moins courant.

### Les relations

Les classes peuvent être reliées entre elles par des relations.
Il existe 4 types de relations :
- **Héritage** : une classe hérite des **attributs** et **méthodes** d'une classe parent.
Dans le cadre d'un diagramme de classe, on utilise une flèche avec un triangle creux à l'extrémité de la flèche, comme suit : 
<img src="/assets/heritage-diag-classe.png" alt="Flèche de l'héritage pour le diagramme de classes" width="75" height="37" />

- **Association** : il s'agit d'une relation entre deux classes.
Représentée par une ligne simple entre les deux classes, avec une flèche indiquant la direction de la relation, comme suit :

<img src="/assets/association-diag-classe.png" alt="Flèche de l'association pour le diagramme de classes" width="75" height="37" />

- **Agrégation** : une relation de type « tout ou en partie ».
Représentée par une ligne avec un losange creux à l'extrémité de la flèche, comme suit :

<img src="/assets/association-diag-classe.png" alt="Losange creux pour l'agrégation dans le diagramme de classes" width="75" height="37" />

- **Composition** : une relation de type « tout ou rien ».
Représentée par une ligne avec un losange plein, comme suit :
<img src="/assets/composition-diag-classe.png" alt="Losange plein pour la composition dans le diagramme de classes" width="75" height="37" />

- La **multiplicité** : elle permet d'indiquer des contraintes numériques à notre relation.
Voilà les différentes multiplicités possibles :
    - **1** : exactement un
    - **0..1** : zéro ou un
    - **1..*** : un ou plusieurs
    - **0..*** : zéro ou plusieurs
    - **n** : un nombre précis
    - **m..n** : un intervalle de nombres

*Tip : La multiplicité peut nous faire penser à la cardinalité dans la méthode MERISE.*