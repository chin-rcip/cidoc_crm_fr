---
layout: page
title: Tutoriel CIDOC CRM
permalink: /ressources/tutoriel-cidoc-crm
sidebar: tutcidocfr
tab: ressources
date: 2022-03-08
description: Ce document explique comment utiliser la documentation de CIDOC CRM afin de déterminer les entités susceptibles de répondre à un besoin particulier. Afin d’y parvenir, certains concepts associés aux données ouvertes et liées sont sommairement définis.
---

[*English follows*](#en)

**Version:** 2.0

**Auteurs:** Marie-Pier Blain, Karine Léonard Brouillet, Philippe Michon

**Date de création:** 2021-02-01

**Date de mise à jour:** 2022-03-08

**Résumé:** Ce document explique comment utiliser la spécification du CIDOC CRM afin de déterminer les entités susceptibles de répondre à un besoin ciblé. Afin d’y parvenir, certains concepts associés aux ontologies mobilisant les données ouvertes et liées sont sommairement définis.

**Pour information:** Pour toute question ou commentaire concernant le Tutoriel CIDOC CRM, veuillez consulter la section [Enjeux](https://github.com/chin-rcip/collections-model/issues) (et ouvrir un Enjeux si c’est pertinent) ou nous contacter par courriel à l'adresse [rcip-chin@pch.gc.ca](mailto:rcip-chin@pch.gc.ca) avec « Tutoriel CIDOC CRM » comme objet.

## Utilisations principales

* Se familiariser avec les principaux termes employés dans le CIDOC CRM;
* Comprendre et utiliser la spécification du CIDOC CRM;
* Identifier les entités pouvant répondre à un besoin précis.

## Contexte

Le *Conceptual Reference Model* du *Comité international pour la documentation* (CIDOC CRM) est une ontologie formelle ayant pour objectif de faciliter l’intégration, la médiation et l’échange d’informations patrimoniales hétérogènes. Plus spécifiquement, ce modèle définit la sémantique qui sous-tend les schèmes de base de données et les structures des documents utilisés par les institutions muséales et patrimoniales. En outre, il permet d’expliquer la logique de ce que ces institutions documentent afin de favoriser l’interopérabilité sémantique.

## Vocabulaire de base et connaissances préalables {#vocabulaire-de-base-et-connaissances-prealables}

Avant de poursuivre, toute personne utilisant le CIDOC CRM, que ce soit à des fins de modélisation ou non, doit bien comprendre les termes suivants :

* [Classe](https://chin-rcip.github.io/collections-model/fr/ressources/actuel/glossaire#classe-nom-feminin)
* [Entité](https://chin-rcip.github.io/collections-model/fr/ressources/actuel/glossaire#entite-nom-feminin)
* [Instance](https://chin-rcip.github.io/collections-model/fr/ressources/actuel/glossaire#instance-nom-feminin)
* [Propriété](https://chin-rcip.github.io/collections-model/fr/ressources/actuel/glossaire#propriete-nom-feminin)

## Auditoire visé et description des sections {#auditoire-vise-et-description-des-sections}

### Auditoire

Ce tutoriel s’adresse aux personnes ayant des connaissances techniques et informatiques préalables qui désirent se familiariser avec le CIDOC CRM.  

### Sections

* Mode d’emploi : les versions et les extensions du CIDOC CRM, la structuration des entités et la nomenclature utilisée, le cadre conceptuel du modèle ainsi que la méthode d’identification des entités appropriées y sont définis;
* Aide-mémoire : les éléments clés et les pistes d’action à retenir y sont détaillés;
* Pour plus d’informations : des suggestions de lectures complémentaires y sont proposées;
* Bibliographie : les sources bibliographiques ayant contribué à la rédaction de ce tutoriel y sont documentées. 

## Mode d’emploi 

### Versions et extensions

Le CIDOC CRM, dont la version originale est en anglais, est mis à jour sur une base régulière. Lorsque le CIDOC CRM est utilisé à des fins de recherche, il s’avère judicieux de se référer à la dernière version publiée. Toutefois, lorsque le CIDOC CRM est utilisé à des fins d'implémentation d’un modèle, il est préférable de se référer à la dernière version encodée en RDF. En date du 31 octobre 2021, il s’agit de la version 7.1.1.

La liste de toutes les versions est accessible [ici](http://www.cidoc-crm.org/versions-of-the-cidoc-crm).

Le CIDOC CRM sert aussi de fondement à d’autres modèles auxiliaires, dont certains ont été approuvés par le CRM SIG, appelés extensions. Ces extensions, compatibles avec le CIDOC CRM, se trouvent [ici](http://www.cidoc-crm.org/collaborations). Une fois qu’un modèle est sélectionné, il est possible de consulter l’ensemble de ses versions en cliquant sur « Resources » dans le coin supérieur droit. Par exemple, le modèle [CRMgeo](http://www.cidoc-crm.org/crmgeo/) permet de gérer des données géospatiales.

### Structuration des entités du CIDOC CRM {#structuration-des-entites-du-cidoc-crm}

Le CIDOC CRM n’est pas conçu pour être lu du début à la fin. Pour naviguer efficacement dans ce document de référence, une compréhension des concepts suivants est nécessaire.

#### Nomenclature du CIDOC CRM

La partie principale du document est divisée en deux grandes sections : « CIDOC CRM Class Declarations » et « CIDOC CRM Property Declarations ». Dans le CIDOC CRM, les classes sont toujours précédées d’un identifiant débutant par la lettre « E » suivie d’un nombre. Par exemple, la classe « Lieu » est précédée de son identifiant « E53 » : `E53_Lieu`. Il en va de même pour les propriétés, dont l’identifiant commence toujours par la lettre « P » suivie d’un nombre (il y a plus de propriétés que de classes dans le CIDOC CRM). Par exemple, la propriété « a eu lieu dans » est précédée de son identifiant « P7 » : `P7_a_eu_lieu_dans`.

À noter qu’il existe aussi une autre distinction de style entre ces deux catégories d’entités; en français, le premier mot contenu dans le nom d’une classe débute toujours par une majuscule (p. ex. `E10_Transfert_de_la_garde`), alors que les propriétés sont toujours écrites en minuscules dans leur intégralité (p. ex. `P28_a_mis_fin_à_la_garde_par`). Cependant, en anglais (la version originale), la première lettre des mots contenus dans le nom d’une classe (à l’exception de « of » et « or ») est en majuscule (p. ex. `E10_Transfer_of_Custody`). Les propriétés sont pour leur part rédigées intégralement en minuscules (p. ex. `P28_custody_surrendered_by`).

#### Classes

Les classes sont des entités qui permettent de catégoriser un ensemble d’instances en fonction d’une définition commune. Par exemple, la valeur « Montréal » pourrait être considérée comme une instance de la classe `E53_Lieu`. En plus de partager une définition commune, les instances d’une même classe peuvent être liées à d’autres instances via le même ensemble de propriétés.

#### Propriétés {#proprietes}

Les propriétés servent à lier deux instances entre elles. Ces liaisons mettent notamment en lumière la sémantique associée aux données. Par exemple, il est possible d’utiliser la propriété `P122_est_limitrophe_de` entre les valeurs « Montréal » et « Fleuve Saint-Laurent » pour indiquer que ces instances de la classe `E53_Lieu` partagent une frontière géographique commune.

#### Domaine et Portée {#domaine-et-portee}

Les propriétés ne s’appliquent pas automatiquement à toutes les instances. Deux concepts fondamentaux permettent de déterminer quelles propriétés peuvent s’appliquer à quelles instances : le domaine (en anglais *domain*) et la portée (en anglais *range*).

Le domaine indique la classe de l’instance avec laquelle il est possible d’utiliser une propriété. Similairement, la portée indique la classe de l’instance qui sert de point d’arrivée à cette même propriété. Par exemple, la propriété `P122_est_limitrophe_de` a à la fois pour domaine et pour portée la classe `E53_Lieu`, ce qui valide l’exemple précédent puisque les valeurs « Montréal » et le « Fleuve Saint-Laurent » sont toutes les deux des instances associées à `P122_est_limitrophe_de`.

À noter qu’il est possible, et même fréquent, que le domaine et la portée diffèrent. C’est notamment le cas de `P7_a_eu_lieu_dans`, qui a pour domaine `E4_Période` et pour portée `E53_Lieu`.

#### Super-classe/Sous-classe et Super-propriété/Sous-propriété {#super-classesous-classe-et-super-proprietesous-propriete}

Un autre concept important du CIDOC CRM est la hiérarchisation des entités (classes et propriétés). En effet, il est possible d’indiquer qu’une classe est la sous-classe d’une autre classe (cette dernière est alors nommée super-classe). Cette hiérarchisation est très importante, car une sous-classe hérite des propriétés de toutes ses super-classes. Par exemple, il est possible d’appliquer la propriété `P7_a_eu_lieu_dans` à la classe `E12_Production` même si son domaine est la classe `E4_Période`, car la chaîne de sous-classes suivante existe : `E4_Période`, `E5_Évènement`, `E7_Activité`, `E11_Modification` et `E12_Production` (chaque classe listée dans cette énumération est la super-classe de la suivante).

Cette hiérarchisation permet aussi à une personne utilisant le modèle d’identifier le niveau de précision qu’elle devrait préconiser. En choisissant la classe la plus précise possible, une grande variété de propriétés peut être utilisée, ce qui facilite les recherches plus spécifiques au sein d’un corpus.

Les propriétés peuvent aussi être hiérarchisées, ce qui permet d’effectuer des requêtes plus générales en utilisant des super-propriétés plutôt que leurs sous-propriétés, qui ont des notes d’application plus contraignantes. Ceci s’avère utile pour obtenir, grâce à l’usage de la propriété adéquate, le niveau de précision approprié au besoin.

### Cadre conceptuel du CIDOC CRM

Il est possible d’explorer la hiérarchie des classes et des sous-classes en s’appuyant sur les domaines et les portées ainsi que sur les propriétés qui leur sont associées sans pour autant devoir lire l’intégralité du document. Il est néanmoins utile de connaître les principes conceptuels du CIDOC CRM afin d’identifier plus rapidement les entités pertinentes à un travail sans toujours se référer à la classe `E1_Entité_CRM`, qui est très générique.

#### Entités temporelles {#entites-temporelles}

Le CIDOC CRM est structuré autour de la notion d’entité temporelle (`E2_Entité_temporelle`). Ainsi, la modélisation d’une information issue d’un jeu de données nécessite fréquemment l’utilisation d’une sous-classe de `E2_Entité_temporelle`. Par exemple, pour indiquer la date de production d’un objet, il est nécessaire d’associer une date à l'évènement de sa production, et non pas à l’objet produit. C’est pourquoi il est utile de connaître les principales sous-classes de `E2_Entité_temporelle`.

Ces entités temporelles sont dites « perdurantes », car elles évoluent dans le temps, de sorte qu’il est impossible de réduire l’entièreté d’une entité temporelle à un instant *t* (contrairement à une entité « endurante », qui contient toutes ses caractéristiques à un instant *t*). Le CIDOC CRM utilise la classe `E77_Entité_persistante` pour définir les entités endurantes, qui sont principalement des personnes ou des groupes (sous-classes de `E39_Actant`) et des choses (notamment des objets physiques et des concepts).

Certaines entités ne font partie d’aucune de ces deux catégories; c’est notamment le cas des intervalles de temps (p. ex. `E52_Intervalle_temporel`) et des lieux (p. ex. `E53_Lieu`).

#### Classes principales du CIDOC CRM

Afin de faciliter la recherche dans la spécification du CIDOC CRM, certaines classes peuvent être utilisées comme point de départ pour identifier l’entité la plus appropriée à un besoin. Le diagramme suivant met en lumière les classes principales du CIDOC CRM :
  
Diagramme des classes principales du CIDOC CRM

<iframe frameborder="0" style="width:100%;height:363px;" src="https://viewer.diagrams.net/?tags=%7B%7D&target=blank&highlight=0000ff&edit=_blank&layers=1&nav=1&title=CRM_ClassesPrincipales_2021-11-04.drawio#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1u6bnEUFB4WMzagTiurfA-PZgnjmPmrlT%26export%3Ddownload"></iframe>

La classe `E2_Entité_temporelle` et ses sous-classes permettent de lier les personnes ou groupes qui ont participé à un évènement aux objets physiques ou conceptuels utilisés ou créés lors de celui-ci. La durée de cet évènement peut être indiquée en utilisant la classe `E52_Intervalle_temporel` et les lieux où se déroule l’action peuvent être identifiés grâce à la classe `E53_Lieu`.

De manière générale, deux classes essentielles traversent l’entièreté du modèle et sont utiles pour nommer une instance (`E41_Appellation`) ou en préciser la nature (`E55_Type` associée à des vocabulaires externes). 

#### Gestion de la temporalité dans le CIDOC CRM {#gestion-de-la-temporalite-dans-le-cidoc-crm}

La gestion de la temporalité au sein du CIDOC CRM est souvent difficile à comprendre lors d’une première utilisation du modèle. Tout d’abord, il faut savoir que le CIDOC CRM utilise uniquement des *intervalles* pour documenter le passage du temps. Ce principe clé permet de rendre adéquatement compte du flou qui entoure la temporalité d’un évènement. En effet, les données patrimoniales ne représentent qu’une approximation (aussi précise soit-elle) du moment exact où un évènement s’est produit dans le monde qu’elles décrivent. Même en connaissant le moment exact (à la seconde près) où un évènement a débuté, il est presque impossible de déterminer le dixième de seconde où il a eu lieu, et ainsi de suite pour des intervalles toujours plus courts. La période durant laquelle un évènement s’est produit peut également être connue, mais sans plus de précision.

Trois propriétés (illustrées ci-dessous) permettent de documenter l’intervalle de temps durant lequel un évènement s’est produit.

Diagramme de l’intervalle de temps

<iframe frameborder="0" style="width:100%;height:302px;" src="https://viewer.diagrams.net/?tags=%7B%7D&target=blank&highlight=0000ff&edit=_blank&layers=1&nav=1&title=CRM_Temporalite_2021-11-04.drawio#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1pALuxT_l-7QJpzfr7XSeJlKGAG22Zoux%26export%3Ddownload"></iframe>

Premièrement, la propriété `P191_a_eu_pour_durée` permet d’indiquer pendant combien de temps l’évènement s’est déroulé : par exemple, l'évènement a duré trois jours.

Deuxièmement, la propriété `P81_a_couvert` — ou ses équivalents fonctionnels et plus précis `P81a_fin_du_début` et `P81b_début_de_la_fin` — permet d’indiquer le moment lors duquel l’évènement a eu lieu : par exemple, l’évènement a eu lieu le 2 février 2020 (il est possible qu’il ait commencé avant ou qu’il se soit terminé après, mais il est établi que le 2 février 2020, cet évènement était en cours).

Troisièmement, les propriétés `P82a_début_du_début` et `P82b_fin_de_la_fin` permettent d’indiquer les limites temporelles de la période durant laquelle l’entièreté de l’évènement s’est déroulée. L’utilisation de ces propriétés plus précises substitue celle de `P82_a_eu_lieu_durant` et permet d’indiquer les périodes où il est établi que l’évènement n’avait *pas* lieu. Cette troisième option est la plus courante dans le secteur patrimonial.

À noter que les spécialisations des propriétés `P81_a_couvert` et `P82_a_eu_lieu_durant` (`P81a_fin_du_début` et `P81b_début_de_la_fin` ainsi que `P82a_début_du_début` et `P82b_fin_de_la_fin`) ne sont pas recensées dans la spécification actuelle du CIDOC CRM, bien qu’elles soient fréquemment utilisées et recensées dans sa dernière version en RDF.

### Identifier la bonne entité {#identifier-la-bonne-entite}

Il existe plusieurs interfaces de consultation de la spécification du CIDOC CRM. Certaines versions (comme la [version 7.1.1](http://www.cidoc-crm.org/Version/version-7.1.1)) ont été générées en HTML afin que chaque entité puisse être consultée sur une page Web dédiée. On y trouve notamment l’ensemble des propriétés qu’une classe peut mobiliser, y compris celles qui sont associées à ses super-classes. Ceci permet d’identifier aisément les propriétés qui peuvent être utilisées avec une classe donnée.

Cependant, les versions les plus récentes sont disponibles uniquement en format .docx ou .pdf sous la forme de documents de travail (c’est le cas pour la [version 7.2](http://www.cidoc-crm.org/Version/version-7.2)).

Chaque entité est décrite à l’aide d’une série de champs, dont en voici les principaux :

**Pour les classes**

* « Sous-classe de » et « Super-classe de » identifient les classes hiérarchiquement au-dessus ou au-dessous de la classe consultée. Il est possible d’avoir accès à une vue de l’ensemble de la hiérarchie en consultant les pages 48 à 54 du document ([version 7.1.1](http://www.cidoc-crm.org/Version/version-7.1.1)).
* « Note d’application » définit la classe et les instances qui en font partie.
* « Exemples » illustre des instances possibles de la classe.
* « Propriétés » identifie les propriétés immédiatement associées à la classe consultée (c.-à-d. que cette classe en est le domaine). Les propriétés associées aux super-classes d’une classe peuvent aussi être mobilisées par cette dernière même si elles ne sont pas listées dans ce champ. Il en va de même pour les propriétés inverses. Pour avoir un aperçu de l’ensemble des propriétés, de leurs domaines et de leurs portées, il est pertinent de se référer à la [hiérarchie générale](http://www.cidoc-crm.org/Version/version-7.1.1). 


**Pour les propriétés**

* « Domaine » et « Portée » identifient rapidement le domaine et la portée de la propriété consultée.
* « Sous-propriété de » et « Super-propriété de » permettent de naviguer dans la hiérarchie des propriétés.
* « Note d’application » définit la nature du lien entre deux instances.
* « Exemples » illustre des liens possibles entre deux instances.

## Aide-mémoire {#aide-memoire}

* Il n’est pas nécessaire de lire le document dans son intégralité. Jongler avec les sous-classes, les super-classes, les sous-propriétés, les super-propriétés, les domaines et les portées s’avère le moyen le plus efficace de trouver les entités du CIDOC CRM susceptibles de répondre à des besoins d’implémentation précis. 
* La hiérarchie complète des classes et des propriétés peut être consultée dans l’introduction de la spécification du CIDOC CRM. Elle donne un bon aperçu des entités utilisables pour mobiliser ce standard.
* Les propriétés associées à une classe spécifique ne constituent pas nécessairement l’entièreté des propriétés utilisables avec cette classe, de sorte qu’il est nécessaire d’analyser les propriétés de ses super-classes ainsi que les propriétés inverses qui peuvent y être associées.
* Les entités temporelles sont au cœur du CIDOC CRM; il est pertinent de s’y référer fréquemment pour identifier les entités répondant à des besoins d’implémentation précis.
* Finalement, il est possible que le CIDOC CRM ne réponde pas à tous les besoins; l’analyse des extensions existantes ou la création d’une extension locale sont de bonnes manières de répondre à des besoins particuliers.

## Pour plus d’informations

- [Jeu d’apprentissage du CIDOC CRM](http://www.cidoc-crm-game.org/) (en anglais seulement)
- [Tutoriels sur des aspects précis du CIDOC CRM](http://www.cidoc-crm.org/tutorialPageRes) (la plupart en anglais)
- [Site du Groupe de travail canadien pour la traduction du CIDOC CRM](https://chin-rcip.github.io/cidoc_crm_fr-ca/)
- [Vidéo de présentation du CIDOC CRM](http://www.cidoc-crm.org/cidoc-crm-tutorial) (en anglais seulement)

## Bibliographie

Bekiari, Chryssoula, George Bruseker, Martin Doerr, Christian-Emil Ore, Stephen Stead, et Athanasios Velios, éd. 2021. *Definition of the CIDOC Conceptual Reference Model*. CIDOC CRM Documentations, 7.1. Paris, FR-IDF: CIDOC CRM  Special Interest Group. [http://cidoc-crm.org/sites/default/files/CIDOC%20CRM_v.7.1%20%5B8%20March%202021%5D.pdf](http://cidoc-crm.org/sites/default/files/CIDOC%20CRM_v.7.1%20%5B8%20March%202021%5D.pdf).

CIDOC CRM. 2021. « CRMgeo ». 2021. [http://www.cidoc-crm.org/crmgeo/home-5](http://www.cidoc-crm.org/crmgeo/home-5).

CIDOC CRM Special Interest Group. 2021. « Tutorials ». CIDOC CRM. octobre 2021. [http://www.cidoc-crm.org/tutorialPageRes](http://www.cidoc-crm.org/tutorialPageRes).

FORTH. 2015. *CRMgeo: A Spatiotemporal Model: An Extension of CIDOC CRM to Link the CIDOC CRM to GeoSPARQL through a Spatiotemporal Refinement*. GR. [http://www.cidoc-crm.org/crmgeo/sites/default/files/CRMgeo1_2.pdf](http://www.cidoc-crm.org/crmgeo/sites/default/files/CRMgeo1_2.pdf).

Groupe de travail canadien pour la traduction du CIDOC CRM. 2021. « Traduction en français du CIDOC CRM ». Traduction en français du CIDOC CRM. 3 juin 2021. [https://chin-rcip.github.io/cidoc_crm_fr-ca/](https://chin-rcip.github.io/cidoc_crm_fr-ca/).

Guillem, Anaïs, et George Bruseker. (2017) 2021. « CIDOC CRM Game ». CIDOC CRM Game. 2021. [http://www.cidoc-crm-game.org/](http://www.cidoc-crm-game.org/).

Stead, Stephen. 2008. « CIDOC CRM Tutorial ». CIDOC CRM. novembre 2008. [http://www.cidoc-crm.org/cidoc-crm-tutorial](http://www.cidoc-crm.org/cidoc-crm-tutorial).

---

<h1 class="post-title" id="en">CIDOC CRM Tutorial</h1>

**Version:** 2.0

**Authors:** Marie-Pier Blain, Karine Léonard Brouillet, Philippe Michon

**Creation date:** 2021-02-01

**Update date:** 2022-03-08

**Abstract:** This document explains how to use the CIDOC CRM specification to identify entities that may address an identified need. To this end, brief definitions are provided for certain concepts associated with ontologies that leverage open and linked data.

**For information:** If you have any questions or comments about the CIDOC CRM Tutorial, please visit the [Issues](https://github.com/chin-rcip/collections-model/issues) section (and open an Issue if relevant) or send us an email at [rcip-chin@pch.gc.ca](mailto:rcip-chin@pch.gc.ca) with "CIDOC CRM Tutorial" in the subject line.


## Main Uses

* Become familiar with the main terms used in the CIDOC CRM;
* Understand and use the CIDOC CRM specification;
* Identify entities that may address a specific need.

## Context

The International Committee for Documentation's *Conceptual Reference Model* (CIDOC CRM) is a formal ontology that facilitates the integration, mediation, and exchange of heterogeneous heritage information. More specifically, it defines the underlying semantics of database schemes and structured documents used by museum and heritage institutions. In addition, it explains the logic of what those institutions document, thereby supporting semantic interoperability.

## Essential Vocabularies and Prior Knowledge

Before proceeding, anyone using CIDOC CRM, whether for modelling purposes or not, needs to understand the following terms:

* [Class](https://chin-rcip.github.io/collections-model/en/resources/current/glossary#class-noun)
* [Entity](https://chin-rcip.github.io/collections-model/en/resources/current/glossary#entity-noun)
* [Instance](https://chin-rcip.github.io/collections-model/en/resources/current/glossary#instance-noun)
* [Property](https://chin-rcip.github.io/collections-model/en/resources/current/glossary#property-noun)

## Intended Audience and Section Description

### Audience

This tutorial is intended for people who have a background knowledge of information technology and techniques, and are interested in learning about CIDOC CRM.

### Sections {#sections-en}

* Directions for use: the versions and extensions of CIDOC CRM, the structure of the entities and the naming conventions used, the model’s conceptual framework, as well as the method of identifying appropriate entities are defined;
* Aide-mémoire: key elements and important actions are detailed;
* For more information: suggestions for further reading are provided;
* Bibliography: bibliographic sources used in the preparation of this tutorial are documented. 

## How-To

### Versions and Extensions

CIDOC CRM is updated on a regular basis. When using CIDOC CRM for research, please refer to the latest published version. When using CIDOC CRM for model implementation, you should refer to the latest version encoded in RDF. As of October 31, 2021, that is version 7.1.1.

A list of all versions is available [here](http://www.cidoc-crm.org/versions-of-the-cidoc-crm).

The CIDOC CRM also serves as the foundation for other auxiliary models, some of which have been approved by the CRM SIG, called extensions. Those extensions, compatible with the CIDOC CRM, can be found [here](http://www.cidoc-crm.org/collaborations). After selecting a model, click "Resources" in the upper right corner to view all of its versions. For example, [CRMgeo](http://www.cidoc-crm.org/crmgeo/) is the model used to manage geospatial data.

### Structure of CIDOC CRM Entities

CIDOC CRM is not designed to be read from start to finish. To effectively navigate this reference document, an understanding of the following concepts is necessary.

#### CIDOC CRM Naming Conventions

The main part of the document is divided into two large sections: "CIDOC CRM Class Declarations" and "CIDOC CRM Property Declarations." In CIDOC CRM, classes are always preceded by an identifier starting with the letter "E" followed by a number. For example, the class "Place" is preceded by its identifier, "E53": `E53_Place`. The same applies to properties, whose identifier always begins with the letter "P" followed by a number (there are more properties than classes in CIDOC CRM). For example, the property "took place at" is preceded by its identifier, "P7": `P7_took_place_at`.

There is also another style distinction between these two categories of entities; in French, the first word in a class name is capitalized (e.g. `E10_Transfert_de_la_garde`), while lower case is used in property names (e.g. `P28_a_mis_fin_à_la_garde_par`). In English (the original version), title case (except for "of" and "or") is used in class names (e.g. `E10_Transfer_of_Custody`) and lower case is used in property names (e.g. `P28_custody_surrendered_by`).

#### Classes {#classes-en}

Classes are entities used to categorize a set of instances based on a common definition. For example, the value "Montreal" may be considered an instance of the class `E53_Place`. In addition to sharing a common definition, instances of the same class can be linked to other instances via the same set of properties.

#### Properties

Properties are used to link two instances together. Those linkages show the semantics associated with the data. For example, the property `P122_borders_with` can be used between the values "Montreal" and "St. Lawrence River" to indicate that these instances of the class `E53_Place` share a common geographic boundary.

#### Domain and Range

Properties do not automatically apply to all instances. There are two fundamental concepts that determine which properties are applicable to which instances: *domain* and *range*.

The domain indicates the class of the instance with which a property can be used. Similarly, the range indicates the class of the instance that serves as the endpoint of that same property. For example, the property `P122_borders_with` has the class `E53_Place` as both its domain and its range, which validates the previous example since the values "Montreal" and "St. Lawrence River" are both instances associated with `P122_borders_with`.

Note that it is possible, and even common, for the domain and range to differ. A case in point is `P7_took_place_at`, which has for domain `E4_Period` and for range `E53_Place`.

#### Super-class/Sub-class and Super-property/Sub-property

Another important concept of CIDOC CRM is the hierarchy of entities (classes and properties). A class can be designated as a sub-class of another class (which then becomes its super-class). This hierarchy is very important because a sub-class inherits the properties of all of its super-classes. For example, the property `P7_took_place_at` can be applied to the class `E12_Production` even though its domain is the class `E4_Period` because the following sub-class chain exists: `E4_Period`, `E5_Event`, `E7_Activity`, `E11_Modification`, and `E12_Production` (each class in this list is the super-class of the following class).

This hierarchy also allows a person using the model to identify the level of precision they should seek. By choosing the most precise class possible, a wide variety of properties can be used, which facilitates more specific searches within a corpus.

Properties can be hierarchical as well, allowing more general queries to be made with super-properties rather than their sub-properties, which have more restrictive scope notes. This is useful to achieve, through the use of the appropriate property, the right level of precision to meet the need.

### CIDOC CRM Conceptual Framework

You can explore the hierarchy of classes and sub-classes using domains and ranges, and their associated properties without having to read the entire document. However, it is useful to know CIDOC CRM’s conceptual principles to more quickly identify the relevant entities for a job without always referring to the class `E1_CRM_Entity`, which is very generic.

#### Temporal Entities

CIDOC CRM is structured around the concept of temporal entity (`E2_Temporal_Entity`). As a result, modelling information from a dataset frequently requires the use of a sub-class of `E2_Temporal_Entity`. For example, to indicate an object’s production date, a date must be associated with the event of its production, and not with the object produced. Consequently, it is helpful to know the main sub-classes of `E2_Temporal_Entity`.

These temporal entities are called "perduring", because they evolve over time, so that the entirety of a temporal entity cannot be reduced to time *t* (unlike an "enduring" entity which contains all of its characteristics at time *t*). CIDOC CRM uses the class `E77_Persistent_Item` to define enduring entities, which are mainly individuals or groups (sub-classes of `E39_Actor`) and things (including physical objects and concepts).

Some entities do not belong to either of these two categories; that is the case for time intervals (e.g. `E52_Time-Span`) and places (e.g. `E53_Place`).

#### CIDOC CRM Main Classes

To facilitate searches in the CIDOC CRM specification, certain classes can be used as a starting point to identify the entity best-suited to a need. The following diagram shows CIDOC CRM main classes:

Diagram of the CIDOC CRM’s main classes

<iframe frameborder="0" style="width:100%;height:363px;" src="https://viewer.diagrams.net/?tags=%7B%7D&target=blank&highlight=0000ff&edit=_blank&layers=1&nav=1&title=CRM_MainClasses_2019-12-08#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1FCeNoxLPlfJ5Kc0IcMmN3pcJPJPNzgwg%26export%3Ddownload"></iframe>

The class `E2_Temporal_Entity` and its sub-classes make it possible to link the individuals or groups that participated in an event to the physical or conceptual objects used or created during the event. The event’s duration can be indicated using the class `E52_Time-Span` and identify the places where the action occurs using the class `E53_Place`.

In general, two essential classes run through the entire model and are useful for naming an instance (`E41_Appellation`) or specifying its nature (`E55_Type` associated with external vocabularies). 

#### Management of Temporality in CIDOC CRM

The management of temporality in CIDOC CRM is often difficult to understand for first-time users. First of all, it is important to know that CIDOC CRM uses only *intervals* to document the passage of time. This key principle allows to properly account for the vagueness that surrounds the temporality of an event. Heritage data provides only an approximation (no matter how precise) of the exact time an event occurred in the world the data describes. Even knowing the exact time (to the second) when an event started, it is almost impossible to determine to the tenth of a second when it took place, and so on for ever shorter intervals. The time period during which an event occurred may also be known, but just as imprecisely.

Three properties (shown below) are used to document the time interval during which an event occurred.

Time interval diagram

<iframe frameborder="0" style="width:100%;height:302px;" src="https://viewer.diagrams.net/?tags=%7B%7D&target=blank&highlight=0000ff&edit=_blank&layers=1&nav=1&title=005_CRM_Temporalite_2021-11-04-EN.drawio#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1wk1lohCuGxyHgo1pPKMZ6ZZn0720M94d%26export%3Ddownload"></iframe>

First, the property `P191_had_duration` allows to indicate for how long the event took place: for example, the event lasted three days.

Second, the property `P81_ongoing_throughout`—or its more precise functional equivalents `P81a_end_of_the_begin` and `P81b_begin_of_the_end`—allows to indicate the time at which the event occurred: for example, the event took place on February 2, 2020 (it may have started before or ended after, but it is known to have been in progress on February 2, 2020).

Third, the properties `P82a_begin_of_the_begin` and `P82b_end_of_the_end` allow to indicate the temporal limits of the period during which the whole event occurred. The use of these more precise properties replaces that of `P82_at_some_time_within` and makes it possible to indicate the periods when the event is known *not* to have taken place. This third option is the most commonly used in the heritage sector.

Note that the specializations of `P81_ongoing_throughout` and `P82_at_some_time_within` (`P81a_end_of_the_begin`, `P81b_begin_of_the_end`, `P82a_begin_of_the_begin`, and `P82b_end_of_the_end`) are not listed in the current CIDOC CRM specification, although they are frequently used and listed in its latest RDF version.

### Identify the Right Entity

There are several interfaces for viewing the CIDOC CRM specification. Some versions (such as [version 7.1.1](http://www.cidoc-crm.org/Version/version-7.1.1)) were generated in HTML so that each entity can be viewed on a dedicated web page. They show all the properties that a class can use, including those associated with its super-classes. This makes it easy to identify the properties that can be used with a given class.

However, the most recent versions are available only in .docx or .pdf format as working documents (this is the case for [version 7.2](http://www.cidoc-crm.org/Version/version-7.2)).

Each entity is described using a series of fields. The main ones are listed below.

**For classes**

* "Sub-class of" and "Super-class of" identify classes hierarchically above or below the class being viewed. An overview of the entire hierarchy can be found on pages 48 to 54 of the document ([version 7.1.1](http://www.cidoc-crm.org/Version/version-7.1.1)).
* "Scope note" defines the class and the instances that are part of it.
* "Examples" contains possible instances of the class.
* "Properties" identifies the properties immediately associated with the class being viewed (in other words, this class is the domain). The properties associated with the super-classes of a class can also be used by the class even if they are not listed in this field. The same is true for the inverse properties. For an overview of all properties and their domains and ranges, see the [property hierarchy](http://www.cidoc-crm.org/Version/version-7.1.1). 

**For properties**

* "Domain" and "Range" quickly identify the domain and range of the property being viewed.
* "Sub-property of" and "Super-property of" help you navigate through the property hierarchy.
* "Scope note" defines the nature of the link between two instances.
* "Examples" contains possible links between two instances.

## Aide-mémoire {#aide-memoire-en}

* It is not necessary to read the entire document. Experimenting with sub-classes, super-classes, sub-properties, super-properties, domains, and ranges is the most efficient way to find CRM CIDOC entities capable of meeting specific implementation needs. 
* For the complete hierarchy of classes and properties, see the introduction to the CIDOC CRM specification. It provides a good overview of the entities that can be used to leverage this standard.
* The properties associated with a specific class do not necessarily constitute all the properties that can be used with the class, so it is necessary to study the properties of its super-classes and the inverse properties that may be associated with it.
* Temporal entities are central to CIDOC CRM; it is relevant to refer to them frequently to identify entities that meet specific implementation needs.
* CIDOC CRM may not address all needs; examining existing extensions or creating a local extension are good ways to meet specific needs.

## For More Information

* [CIDOC CRM Game](http://www.cidoc-crm-game.org/)
* [Tutorials on specific aspects of the CIDOC CRM](http://www.cidoc-crm.org/tutorialPageRes)
* [Canadian CIDOC CRM Translation Working Group website](https://chin-rcip.github.io/cidoc_crm_fr-ca/)
* [CIDOC CRM introduction video](http://www.cidoc-crm.org/cidoc-crm-tutorial)

## Bibliography

Bekiari, Chryssoula, George Bruseker, Martin Doerr, Christian-Emil Ore, Stephen Stead, and Athanasios Velios, eds. *Definition of the CIDOC Conceptual Reference Model*. CIDOC CRM Documentations, 7.1. Paris, FR-IDF: CIDOC CRM Special Interest Group, 2021. [http://cidoc-crm.org/sites/default/files/CIDOC%20CRM_v.7.1%20%5B8%20March%202021%5D.pdf](http://cidoc-crm.org/sites/default/files/CIDOC%20CRM_v.7.1%20%5B8%20March%202021%5D.pdf).

CIDOC CRM. "CRMgeo." 2021. [http://www.cidoc-crm.org/crmgeo/home-5](http://www.cidoc-crm.org/crmgeo/home-5).

CIDOC CRM Special Interest Group. "Tutorials." CIDOC CRM. October 2021. [http://www.cidoc-crm.org/tutorialPageRes](http://www.cidoc-crm.org/tutorialPageRes).

FORTH. *CRMgeo: A Spatiotemporal Model: An Extension of CIDOC CRM to Link the CIDOC CRM to GeoSPARQL through a Spatiotemporal Refinement*. GR. 2015. [http://www.cidoc-crm.org/crmgeo/sites/default/files/CRMgeo1_2.pdf](http://www.cidoc-crm.org/crmgeo/sites/default/files/CRMgeo1_2.pdf).

Canadian CIDOC CRM Translation Working Group. "Traduction en français du CIDOC CRM." French translation of the CIDOC CRM. June 3, 2021. [https://chin-rcip.github.io/cidoc_crm_fr-ca/](https://chin-rcip.github.io/cidoc_crm_fr-ca/).

Guillem, Anaïs, and George Bruseker. "CIDOC CRM Game." CIDOC CRM Game. 2021. [http://www.cidoc-crm-game.org/](http://www.cidoc-crm-game.org/).

Stead, Stephen. "CIDOC CRM Tutorial." CIDOC CRM. November 2008. [http://www.cidoc-crm.org/cidoc-crm-tutorial](http://www.cidoc-crm.org/cidoc-crm-tutorial).

