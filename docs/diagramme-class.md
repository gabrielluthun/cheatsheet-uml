# Diagramme de classe (UML)

Ce fichier présente en détail les concepts clés du diagramme de classe en UML, un outil essentiel pour modéliser la structure d'un système.

## Les classes

Tout d'abord, il faut créer une classe et lui donner un nom. 
*(par exemple, une classe `Animal` dans le cadre d'un diagramme de classe pour un zoo)*

### De quoi est composée une classe ?

Une classe est composée de deux parties principales :

- **Attributs** : Ce sont des valeurs qui décrivent chaque instance de cette classe. Ils doivent être inscrits dans la première moitié de la classe. 

  - Un attribut doit commencer par une minuscule et être en camelCase (par exemple, `nomAnimal`).

  - Il est important de spécifier le type de données de l'attribut (par exemple, `String`, `int`, etc.).

- **Méthodes** : Ce sont les comportements ou actions que la classe peut effectuer. Elles doivent être inscrites dans la seconde moitié de la classe.

  - Comme pour les attributs, une méthode doit commencer par une minuscule et être en camelCase (par exemple, `manger()`).

  - Chaque méthode peut avoir une **visibilité** qui détermine qui peut l'utiliser.

### Qu'est-ce que la visibilité ?

La visibilité établit les règles d'accès aux attributs et méthodes d'une classe. Voici comment cela fonctionne pour les **attributs** :

- **+** : **public** -> accessible par toutes les classes, ce qui signifie que n'importe quelle autre classe peut utiliser cet attribut.

- **-** : **private** -> aucune autre classe ne peut accéder à cet attribut, ce qui protège les données de la classe.

- **#** : **protected** -> accessible par les classes enfants, permettant aux sous-classes d'accéder à ces attributs.

- **~** : **package** -> accessible par les classes du même package (rarement utilisé).

*Tip : Dans la plupart des cas, les attributs sont privés pour protéger les données, donc la visibilité indiquée est « **-** ». Les méthodes sont généralement publiques pour permettre leur utilisation par d'autres classes.*

Cette **visibilité** doit être placée avant le nom de l'attribut (donc à gauche). Il est possible de spécifier la visibilité des méthodes de la même manière, mais cela est moins courant.

### Les relations

Les classes peuvent être reliées entre elles par des relations. Il existe quatre types de relations :

- **Héritage** : Une classe hérite des **attributs** et **méthodes** d'une classe parent. 
Dans un diagramme de classe, on utilise une flèche avec un triangle creux à l'extrémité de la flèche, comme suit : 
<img src="/assets/heritage-diag-classe.png" alt="Flèche de l'héritage pour le diagramme de classes" width="75" height="37" />

- **Association** : Il s'agit d'une relation entre deux classes, indiquant qu'elles interagissent d'une certaine manière. 
Représentée par une ligne simple entre les deux classes, avec une flèche indiquant la direction de la relation, comme suit :
<img src="/assets/association-diag-classe.png" alt="Flèche de l'association pour le diagramme de classes" width="75" height="37" />

- **Agrégation** : Une relation de type « tout ou en partie », indiquant qu'une classe peut contenir une autre classe sans que cette dernière soit dépendante. 
Représentée par une ligne avec un losange creux à l'extrémité de la flèche, comme suit :
<img src="/assets/agregation-diagramme-class.png" alt="Losange creux pour l'agrégation dans le diagramme de classes" width="75" height="37" />

- **Composition** : Une relation de type « tout ou rien », où une classe ne peut exister sans l'autre. 
Représentée par une ligne avec un losange plein, comme suit :
<img src="/assets/composition-diag-classe.png" alt="Losange plein pour la composition dans le diagramme de classes" width="75" height="37" />

- **Multiplicité** : Elle permet d'indiquer des contraintes numériques à notre relation. 
Voici les différentes multiplicités possibles :

    - **1** : exactement un

    - **0..1** : zéro ou un

    - **1..*** : un ou plusieurs

    - **0..*** : zéro ou plusieurs

    - **n** : un nombre précis

    - **m..n** : un intervalle de nombres

*Tip : La multiplicité peut nous faire penser à la cardinalité dans la méthode MERISE, qui est un concept similaire utilisé dans la modélisation des données.*