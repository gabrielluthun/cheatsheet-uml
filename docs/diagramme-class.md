### Diagramme de classe (UML)

Ce fichier présente en détail les concepts clés du diagramme de classe en UML.

Tout d'abord, il faut créer une classe et lui donner un nom.
*(par exemple, une classe animal dans le cadre d'un diagramme de classe pour un zoo)*

Cette classe comporte 2 parties :
- **Attributs** : valeurs décrivant chaque instance de cette classe -> à inscrire dans la première moitié de la classe
Un attribut doit commencer par une minuscule et être en camelCase.
Elle doit spécifier le type de données de l'attribut.


- **Méthodes** : les comportements de la classe ->  à inscrire dans la seconde moitié de la classe
Pareillement, une méthode doit commencer par une minuscule et être en camelCase.


En ce qui concerne les **attributs**, la visibilité de l'attribut peut être spécifiée :
- **+** : public -> accessible par toutes les classes
- **-** : private -> aucune autre classe ne peut accéder à cet attribut
- **#** : protected -> accessible par les classes enfants
- **~** : package -> accessible par les classes du même package (rarement utilisé)

*Tip : Dans la plupart des cas, les attributs sont privés, donc la visibilité indiquée est « **-** ».*
*Les méthodes sont publiques de manière générale.*

Cette visiblité doit être placée avant le nom de l'attribut (donc à gauche).
Il est possible de spécifier la visibilité des méthodes de la même manière, mais cela est moins courant.