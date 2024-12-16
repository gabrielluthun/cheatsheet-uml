## Introduction

Cette cheatsheet a pour objectif de présenter les bases du langage UML (Unified Modeling Language). 

### Table des matières

1. [Qu'est-ce que UML ?](#qu'est-ce-que-uml)
2. [L'UML répond à différents besoins](#l'uml-répond-à-différents-besoins)
3. [Comparaison UML vs MERISE](#comparaison-uml-vs-merise)
4. [Les différents types de diagrammes UML](#les-différents-types-de-diagrammes-uml)
5. [Outils utilisés pour la création de diagrammes UML](#outils-utilisés-pour-la-création-de-diagrammes-uml)
6. [Initiation sur le diagramme de cas d'utilisation](#initiation-sur-le-diagramme-de-cas-d'utilisation)
7. [Diagramme de classe](#diagramme-de-classe)

## Qu'est-ce que UML ?

UML, ou Unified Modeling Language, est un langage de modélisation graphique sous forme de pictogrammes ou de diagrammes. Il est utilisé pour décrire des systèmes logiciels orientés objet. Le langage UML est destiné à l'architecture, la conception, et la mise en œuvre de systèmes logiciels complexes.

*Pour le côté historique, UML est une synthèse de trois anciennes méthodes de modélisation : Booch, OMT et OOSE.*

### L'UML répond à différents besoins

UML a été créé pour répondre à plusieurs besoins :

- **Standardiser la notation** : c'est l'un des objectifs principaux de l'UML → fournir une notation standard pour la modélisation des systèmes orientés **objet**. Cela signifie que tous les développeurs peuvent comprendre les diagrammes UML de la même manière.
- **Amélioration de la communication** : UML facilite la communication entre les différents acteurs d'un projet (développeurs, chefs de projet, clients, etc.), ce qui est crucial pour le succès d'un projet.
- **Optimiser le processus de développement** : UML aide à mieux comprendre les besoins du client, à concevoir des solutions adaptées, et à faciliter la maintenance du code.
- **Réduction des coûts** : UML permet de réduire les coûts de développement en améliorant la qualité du code et en facilitant la communication.

Une phrase résume à elle seule l'utilité d'UML : 
> Une image vaut mieux qu'un long discours. 

## Comparaison UML vs MERISE

La différence principale entre UML et MERISE réside dans le fait que MERISE est une méthode de modélisation des **données**, tandis qu'UML est une méthode de modélisation **orientée objet**. Cela signifie que UML est plus adapté pour modéliser des systèmes complexes qui interagissent avec des objets.

Pour plus de détails, voici un tableau comparatif entre UML et MERISE :
[UML vs MERISE](docs/uml-vs-merise.md)

## Les différents types de diagrammes UML

La version actuelle d'UML propose 14 types de diagrammes, répartis en deux catégories :

- **Diagrammes structurels** (7 types) : illustrent la structure d'un système (comme les classes, objets, composants, etc.). Ces diagrammes montrent comment les différentes parties d'un système sont organisées.
- **Diagrammes comportementaux** (7 types) : illustrent le comportement d'un système (comme les cas d'utilisation, séquences, états, etc.). Ces diagrammes montrent comment le système interagit avec les utilisateurs et d'autres systèmes.

Pour une liste complète des diagrammes UML sous forme de tableau, consultez la page suivante : [Liste des diagrammes UML](docs/liste-diagrammes-uml.md)

---

### Outils utilisés pour la création de diagrammes UML

Il existe de nombreux outils pour créer des diagrammes UML. 

Ces outils sont séparés en deux **catégories** :

- **Outils clients lourds** : ce sont des logiciels qui nécessitent une installation sur l'ordinateur. Ils offrent souvent des fonctionnalités avancées.
- **Outils cloud** : ce sont des applications en ligne qui ne nécessitent pas d'installation. Ils sont souvent plus accessibles et faciles à utiliser.

Voici quelques outils clients lourds utilisés pour la création de diagrammes UML :

- **[Visual Paradigm](https://www.visual-paradigm.com/)** : un outil **complet** pour la modélisation UML, adapté aux professionnels.
- **[StarUML](http://staruml.io/)** : un outil open-source pour la **modélisation** UML, idéal pour les développeurs.
- **[Astah UML](http://astah.net/editions/uml-new)** : un outil simple et efficace pour la **modélisation** UML, parfait pour les débutants.

Et voici quelques outils cloud pour la création de diagrammes UML :

- **[Lucidchart](https://www.lucidchart.com/)** : un outil en ligne pour la **création** de diagrammes UML, facile à utiliser.
- **[Draw.io](https://www.draw.io/)** : un outil en ligne gratuit pour la **création** de diagrammes UML, très accessible.
- **[Creately](https://creately.com/)** : un outil en ligne pour la **création** de diagrammes UML, avec des fonctionnalités collaboratives.

---

### Initiation sur le diagramme de cas d'utilisation
*ou use-case*

Le diagramme de cas d'utilisation est l'un des diagrammes les plus importants en UML. Il permet de capturer les exigences fonctionnelles du système.

#### Objectifs du diagramme de cas d'utilisation
##### Du point de vue client 
- Visualiser les fonctionnalités du système
- Comprendre les interactions entre le système et les acteurs
- Identifier les cas d'utilisation principaux


##### Du point de vue développeur
- Définir la portée fonctionnelle du projet
- Identifier les exigences fonctionnelles du système
- Faciliter la communication avec les parties prenantes
- Servir de base pour une planification et estimation du projet

#### Quels sont les concepts clés du diagramme de cas d'utilisation ?

- **Acteur** : une entité externe (comme un utilisateur ou un autre système) qui interagit avec le système.
- **Cas d'utilisation** : une fonctionnalité du système qui apporte de la valeur à un acteur. Par exemple, "Se connecter" ou "Passer une commande".
- **Relation acteur-cas d'utilisation** : une association entre un acteur et un cas d'utilisation, montrant comment l'acteur utilise la fonctionnalité.
- **Système** : l'ensemble des cas d'utilisation et acteurs, représentant le périmètre du projet.

*Tip : lors de la réalisation d'un diagramme, on commence toujours par le système, puis on ajoute les acteurs qui interagiront avec lui.*

#### Quels sont les liens entre User Stories et cas d'utilisation ?

Les **User Stories** sont des descriptions courtes et simples des fonctionnalités du système, souvent utilisées dans les méthodes agiles. Un cas d'utilisation peut être décomposé en plusieurs User Stories, permettant ainsi de mieux gérer le développement et de s'assurer que toutes les fonctionnalités sont couvertes.

---

### Diagramme de classe 

Le diagramme de classe est un diagramme statique qui représente la structure d'un système. 

#### Objectifs du diagramme de classe
- Visualiser la structure d'un système, en montrant les classes et leurs relations
- Identifier les classes et les relations entre elles, ce qui est essentiel pour la conception du système
- Comprendre les attributs (propriétés) et les méthodes (comportements) de chaque classe

#### Quels sont les concepts clés du diagramme de classe ?

- **Classe** : une entité qui représente un concept du système, comme "Client" ou "Produit".
- **Attribut** : une propriété de la classe, par exemple, un "Client" peut avoir un attribut "nom".
- **Méthode** : un comportement de la classe, par exemple, un "Produit" peut avoir une méthode "calculerPrix".
- **Relation** : une association, agrégation, héritage, et composition, qui montre comment les classes interagissent entre elles.

Pour avoir un aperçu complet du diagramme de classe, consultez la page suivante : [Diagramme de classe](/docs/diagramme-class.md)