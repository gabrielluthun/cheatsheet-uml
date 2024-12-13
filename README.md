## Introduction

Cette cheatsheet a pour objectif de présenter les bases du langage UML (Unified Modeling Language). 

### Table des matières

1. [Qu'est-ce que UML ?](#qu'est-ce-que-uml)
2. [L'UML répond à différents besoins](#l'uml-répond-à-différents-besoins)
3. [Comparaison UML vs MERISE](#comparaison-uml-vs-merise)
4. [Les différents types de diagrammes UML](#les-différents-types-de-diagrammes-uml)
5. [Outils utilisés pour la création de diagrammes UML](#outils-utilisés-pour-la-création-de-diagrammes-uml)
6. [Initiation sur le diagramme de cas d'utilisation](#initiation-sur-le-diagramme-de-cas-d'utilisation)

## Qu'est-ce que UML ?

UML, ou Unified Modeling Language, est un langage de modélisation graphique sous forme de pictogrammes ou de diagrammes. Il est utilisé pour décrire des systèmes logiciels orientés objet. Le langage UML est destiné à l'architecture, la conception, et la mise en œuvre de systèmes logiciels complexes.

*Pour le côté historique, UML est une synthèse de trois anciennes méthodes de modélisation : Booch, OMT et OOSE.*

### L'UML répond à différents besoins

UML a été créé pour répondre à plusieurs besoins :

- **Standardiser la notation** : c'est l'un des objectifs principaux de l'UML → fournir une notation standard pour la modélisation des systèmes orientés **objet**.
- **Amélioration de la communication** : UML permet de faciliter la communication entre les différents acteurs d'un projet (développeurs, chefs de projet, clients, etc.)
- **Optimiser le processus de développement** : UML permet de mieux comprendre les besoins du client, de concevoir des solutions adaptées, et de faciliter la maintenance du code.
- **Réduction des coûts** : UML permet de réduire les coûts de développement en facilitant la communication et en améliorant la qualité du code.

Une phrase résume à elle seule l'utilité d'UML : 
> Une image vaut mieux qu'un long discours. 

## Comparaison UML vs MERISE

La différence principale entre UML et MERISE réside dans le fait que MERISE est une méthode de modélisation des **données**, tandis qu'UML est une méthode de modélisation **orientée objet**.

Pour plus de détails, voici un tableau comparatif entre UML et MERISE :
[UML vs MERISE](docs/uml-vs-merise.md)

## Les différents types de diagrammes UML

La version actuelle d'UML propose 14 types de diagrammes, répartis en deux catégories :

- **Diagrammes structurels** (7 types) : illustrent la structure d'un système (comme les classes, objets, composants, etc.)
- **Diagrammes comportementaux** (7 types) : illustrent le comportement d'un système (comme les cas d'utilisation, séquences, états, etc.)

Pour une liste complète des diagrammes UML sous forme de tableau, consultez la page suivante : [Liste des diagrammes UML](docs/liste-diagrammes-uml.md)

---

### Outils utilisés pour la création de diagrammes UML

Il existe de nombreux outils pour créer des diagrammes UML. 

Ces outils sont séparés en deux **catégories** :

- **Outils clients lourds** : c'est-à-dire des outils dont une installation est nécessaire sur l'ordinateur.
- **Outils cloud** : des outils en ligne qui ne nécessitent pas d'installation.

Voici quelques outils clients lourds utilisés pour la création de diagrammes UML :

- **[Visual Paradigm](https://www.visual-paradigm.com/)** : un outil **complet** pour la modélisation UML.
- **[StarUML](http://staruml.io/)** : un outil open-source pour la **modélisation** UML.
- **[Astah UML](http://astah.net/editions/uml-new)** : un outil simple et efficace pour la **modélisation** UML.

Et voici quelques outils cloud pour la création de diagrammes UML :

- **[Lucidchart](https://www.lucidchart.com/)** : un outil en ligne pour la **création** de diagrammes UML.
- **[Draw.io](https://www.draw.io/)** : un outil en ligne gratuit pour la **création** de diagrammes UML.
- **[Creately](https://creately.com/)** : un outil en ligne pour la **création** de diagrammes UML.

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

- **Acteur** : une entité externe qui interagit avec le système.
- **Cas d'utilisation** : une fonctionnalité du système qui apporte de la valeur à un acteur.
- **Relation acteur-cas d'utilisation** : une association entre un acteur et un cas d'utilisation.
- **Système** : l'ensemble des cas d'utilisation et acteurs.

#### Quels sont les liens entre User Stories et cas d'utilisation ?

Les **User Stories** sont des descriptions courtes, simples, mais plus techniquement détaillée des fonctionnalités du système.
De plus, un cas d'utilisation peut être décomposé en plusieurs User Stories.