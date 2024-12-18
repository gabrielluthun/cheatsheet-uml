# Diagramme de séquence (UML)

Le diagramme de séquence est un diagramme comportemental qui montre **comment** les objets interagissent dans une séquence temporelle.

 Le diagramme de séquence possède des éléments propres à lui permettant de **représenter** les **interactions** entre les **objets** de manière claire et précise. 
 
 *(Tout comme le diagramme de cas d'utilisation et le diagramme de classe, d'ailleurs)*

### Quels sont les objectifs du diagramme de séquence ?

Le diagramme de séquence a plusieurs objectifs, notamment :

- **Représentation temporelle des interactions** : Il permet de visualiser l'ordre des messages échangés entre les objets.

- **Compréhension des interactions** : Il facilite la compréhension des interactions entre les objets, en montrant comment ils se répondent les uns aux autres.

- **Visualisation du flux de contrôle** : Il montre comment le contrôle passe d'un objet à un autre, permettant de comprendre le déroulement des opérations.

- **Illustration ds scénarios d'utilisation** : Il peut être utilisé pour détailler un scénario d'utilisation, montrant comment les objets interagissent pour réaliser une tâche.

- **Validation de la logique** : Il permet aux concepteurs et aux développeurs de valider la logique de l'interaction entre les objets.

### Les éléments principaux du diagramme de séquence

Les diagrammes de séquence UML sont des outils qui aident à visualiser comment les objets d'un système interagissent au fil du temps. Voici les éléments essentiels d'un diagramme de séquence :

## Lignes de vie

Les lignes de vie montrent les participants à une interaction, que ce soit des objets ou des utilisateurs. Elles sont représentées par des lignes verticales en pointillés, avec le nom de l'objet ou de l'utilisateur en haut. La ligne de vie descend pour montrer le passage du temps.

## Messages

Les messages représentent les communications entre les lignes de vie. Il existe plusieurs types de messages :

- **Messages synchrones** : Ce sont des flèches pleines avec une tête remplie. L'expéditeur doit attendre une réponse avant de continuer.
- **Messages asynchrones** : Ce sont des flèches pleines avec une tête ouverte. L'expéditeur peut continuer sans attendre de réponse.
- **Messages de retour** : Ils sont généralement représentés par des lignes pointillées.

## Barres d'activation

Les barres d'activation sont des rectangles verticaux sur les lignes de vie. Elles montrent quand un objet est actif ou en train d'exécuter une tâche.

## Acteurs

Les acteurs représentent les utilisateurs ou les systèmes externes qui interagissent avec le système que l'on modélise.

## Fragments combinés

Les fragments combinés permettent de montrer des structures de contrôle plus complexes, comme les boucles ou les conditions. Ils sont entourés de cadres et incluent des opérateurs comme :

- **alt** : pour les choix (si-alors-sinon)
- **loop** : pour les répétitions
- **par** : pour les actions qui se déroulent en même temps (parallèles)
- **opt** : pour les parties optionnelles

## Notes et contraintes

Les notes ajoutent des commentaires ou des informations supplémentaires au diagramme. Les contraintes spécifient des conditions ou des règles particulières.

En utilisant ces éléments, les diagrammes de séquence UML offrent une représentation visuelle simple et chronologique des interactions entre les composants d'un système, ce qui aide à comprendre et à concevoir des processus complexes.

