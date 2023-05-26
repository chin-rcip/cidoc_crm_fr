---
layout: page
title: CIDOC CRM Version 7.1
titleEn: CIDOC CRM Version 7.1
permalink: /v7.1/information/introduction
sidebar: v71
group: information
date: 2023-05-26
---

**Date de création** : 2020-10-20

**Dernière mise à jour** : 2023-05-26

<div class="lang-buttons">
 <button id="fr" class="activate">FR</button>
 <button id="en-fr">EN-FR</button>
</div>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>This document is the formal definition of the<strong> CIDOC Conceptual Reference Model (“CIDOC CRM”), </strong>a formal ontology intended to facilitate the integration, mediation and interchange of heterogeneous cultural heritage information. The CIDOC CRM is the culmination of more than a decade of standards development work by the International Committee for Documentation (CIDOC) of the International Council of Museums (ICOM). Work on the CIDOC CRM itself began in 1996 under the auspices of the ICOM-CIDOC Documentation Standards Working Group. Since 2000, development of the CIDOC CRM has been officially delegated by ICOM-CIDOC to the CIDOC CRM Special Interest Group, which collaborates with the ISO working group ISO/TC46/SC4/WG9 to bring the CIDOC CRM to the form and status of an International Standard.</p>
</td>
<td>
<p>Ce document constitue la définition du <strong>Modèle conceptuel de référence du Comité international pour la documentation du Conseil international des musées (« CIDOC CRM »)</strong>, une ontologie formelle qui a pour objectif de faciliter l’intégration, la médiation et l’échange d’informations patrimoniales hétérogènes. Le CIDOC CRM est le résultat du développement de standards par le Comité pour la documentation (CIDOC) du Conseil international des musées (ICOM), un travail qui a commencé en 1996 sous les auspices du Groupe de travail pour les standards en documentation. En 2000, ICOM-CIDOC a officiellement délégué les tâches de développement du CIDOC CRM au Groupe de travail spécial pour CIDOC CRM (CRM SIG), lequel travaille en collaboration avec le Groupe de travail ISO/TC46/SC4/WG9 afin de veiller à ce que le CIDOC CRM respecte les normes internationales en matière de standards. </p>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<th style="width:15%"><p><em>Note traducteur</em></p>
</th>
<td colspan="1">
<p>L’abréviation la plus utilisée dans le monde francophone pour le modèle demeure son acronyme anglophone (CIDOC CRM) et c’est celle qui est utilisée dans ce document. Les titres francophones des groupes de travail sont tirés des appellations trouvées sur le site francophone de CIDOC. </p>
</td>
</tr>
<tr>
<th style="width:15%"><p><em>Références</em></p>
</th>
<td colspan="1">
<p><em>Comité International pour la Documentation de l’ICOM. 2021. « CIDOC ». ICOM CIDOC. 24 février 2021.</em><a href="http://cidoc.mini.icom.museum/fr/"><span class="underline"><em> </em></span></a><a href="http://cidoc.mini.icom.museum/fr/"><span class="underline"><em>http://cidoc.mini.icom.museum/fr/</em></span></a><em>.</em></p>
</td>
</tr>
</tbody>
</table>

<h2 id="objectifs-du-cidoc-crm"><span class="en heading">Objectives of the CIDOC CRM - </span>Objectifs du CIDOC CRM</h2>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>The primary role of the CIDOC CRM is to enable information exchange and integration between heterogeneous sources of cultural heritage information. It aims at providing the semantic definitions and clarifications needed to transform disparate, localised information sources into a coherent global resource, be it within a larger institution, in intranets or on the Internet. </p>
<p>Its perspective is supra-institutional and abstracted from any specific local context. This goal determines the constructs and level of detail of the CIDOC CRM. </p>
<p>More specifically, it defines and is restricted to the <strong>underlying semantics</strong> of database schemata and document <strong>structures</strong> used in cultural heritage and museum documentation in terms of a formal ontology. It does <strong>not</strong> define any of the <strong>terminology</strong> appearing typically as data in the respective data structures; however, it foresees the characteristic relationships for its use. It does <strong>not</strong> aim at proposing what cultural institutions <strong>should</strong> document. Rather, it explains the logic of what they actually currently document, and thereby enables <strong>semantic interoperability.</strong></p>
<p>It intends to provide a model of the intellectual structure of cultural documentation in logical terms. As such, it is not optimised for implementation-specific storage and processing aspects. Implementations may lead to solutions where elements and links between relevant elements of our conceptualizations are no longer explicit in a database or other structured storage system. For instance, the birth event that connects elements such as father, mother, birth date, birth place may not appear in the database, in order to save storage space or response time of the system. The CIDOC CRM allows us to explain how such apparently disparate entities are intellectually interconnected, and how the ability of the database to answer certain intellectual questions is affected by the omission of such elements and links.</p>
<p>The CIDOC CRM aims to support the following specific functionalities:</p>
<ul><li><p>Inform developers of information systems as a guide to good practice in conceptual modelling, in order to effectively structure and relate information assets of cultural documentation. </p>
</li>
<li><p>Serve as a common language for domain experts and IT developers to formulate requirements and to agree on system functionalities with respect to the correct handling of cultural contents.</p>
</li>
<li><p>To serve as a formal language for the identification of common information contents in different data formats; in particular, to support the implementation of automatic data transformation algorithms from local to global data structures without loss of meaning. The latter being useful for data exchange, data migration from legacy systems, data information integration and mediation of heterogeneous sources.</p>
</li>
<li><p>To support associative queries against integrated resources by providing a global model of the basic classes and their associations to formulate such queries.</p>
</li>
<li><p>It is further believed that advanced natural language algorithms and case-specific heuristics can take significant advantage of the CIDOC CRM to resolve free text information into a formal logical form, if that is regarded beneficial. The CIDOC CRM is however not thought to be a means to replace scholarly text, rich in meaning, by logical forms, but only a means to identify related data. </p>
</li></ul>
<p>Users of the CIDOC CRM should be aware that the definition of data entry systems requires support of community-specific terminology, guidance to what should be documented and in which sequence, and application-specific consistency controls. The CIDOC CRM does not provide such notions.</p>
<p>By its very structure and formalism, the CIDOC CRM is extensible and users are encouraged to create extensions for the needs of more specialized communities and applications.</p>
</td>
<td>
<p>CIDOC CRM a pour principale fonction de favoriser l’échange d’informations et leur intégration parmi des sources hétérogènes d’informations patrimoniales. Il fournit les définitions sémantiques et clarifications nécessaires à la transformation d’informations localisées et disparates grâce à une ressource globale et cohérente [n.d.t. prenant la forme d’une norme de documentation], que ce soit au sein d’une institution de plus grande envergure, d’intranets ou sur Internet. </p>
<p>Son approche est supra-institutionnelle et désagrégée de tout contexte local spécifique, ce qui détermine le niveau de détail et les construits du CIDOC CRM. </p>
<p>Plus spécifiquement, ce modèle définit par une ontologie formelle la <strong>sémantique</strong> qui sous-tend les schèmes de base de données et les <strong>structures</strong> des documents utilisés dans le milieu patrimonial et muséal. CIDOC CRM ne définit pas la <strong>terminologie</strong> qui se trouve typiquement dans les structures de données sous forme de valeurs, bien qu’il entrevoit les relations caractéristiques nécessaires à son usage [n.d.t. de sorte que le CIDOC CRM précise comment utiliser une classe, mais pas les valeurs qu’elle comprend lorsqu’elle est implémentée]. Il <strong>n’a pas </strong>pour objectif d’indiquer ce que les institutions culturelles <strong>devraient</strong> documenter, mais bien d’expliquer la logique de ce qu’elles documentent afin de favoriser l’<a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#interoperabilite-semantique"><span class="underline"><strong>interopérabilité sémantique</strong></span></a>. </p>
<p>Il propose un modèle des structures intellectuelles de la documentation patrimoniale en termes logiques et n’est donc pas optimisé pour une implémentation spécifique, en particulier en ce qui a trait au stockage et au traitement des données. L’implémentation peut en outre mener à ce que certains éléments des conceptualisations du CIDOC CRM ne soient plus explicites dans le contexte d'une base de données ou d'un système de stockage structuré. Par exemple, un évènement de naissance reliant des éléments tels que le père, la mère, la date et le lieu de naissance peut ne pas être apparent dans une base de données afin de préserver l’espace de stockage et le temps de réponse d’un système. Le CIDOC CRM permet d’expliquer en quoi ces entités à première vue disparates sont intellectuellement interconnectées et comment la capacité d’une base de données à fournir des réponses à des questions de nature intellectuelle est limitée par l’omission de tels liens et éléments. </p>
<p>Le CIDOC CRM a pour objectif de soutenir les fonctionnalités spécifiques suivantes : </p>
<ul><li><p>Informer les développeurs de systèmes informatiques grâce à un guide de pratiques exemplaires de la modélisation conceptuelle, et ce, afin de structurer et de lier différents avoirs informationnels de la documentation culturelle. </p>
</li>
<li><p>Servir de langage commun entre les experts et les développeurs informatiques afin qu’ils puissent identifier leurs besoins et s’entendre sur les fonctionnalités nécessaires à la bonne gestion des contenus culturels.</p>
</li>
<li><p>Servir de langage formel pour l’identification de contenus informationnels communs même lorsqu’ils ont initialement des formats de données disparates. Cela s’applique particulièrement à la transformation automatique de données locales en données globales par l’implémentation d’algorithmes permettant ce transfert sans perte de sens ou de savoirs émanant desdites données. De tels algorithmes s’avèrent particulièrement utiles lors de l’échange ou de la migration de données depuis des systèmes (pré)existants, lors de l’intégration de données informationnelles ou lors de la médiation de données issues de sources disparates. </p>
</li>
<li><p>Faciliter les requêtes d’association dans des ressources intégrées en offrant un modèle global de classes de base et d'associations entre elles qui permettent de formuler de telles requêtes. </p>
</li>
<li><p>Les algorithmes avancés de traitement automatique du langage naturel ainsi que les méthodes heuristiques (dans des cas spécifiques) peuvent aussi grandement bénéficier de l’usage du CIDOC CRM dans le passage d’une forme textuelle libre à une logique formelle. Le CIDOC CRM n’a cependant pas pour objectif de remplacer des textes experts riches de sens par une logique formelle, mais plutôt d’identifier les données pertinentes liées à de tels textes. </p>
</li></ul>
<p>Les utilisateurs du CIDOC CRM auront besoin de l’intégration d’une terminologie particulière à leur domaine ainsi que de l’apport de leur communauté de pratique dans la sélection de ce qui doit être documenté, de la séquence dans laquelle ce doit être documenté ainsi que dans l’application de protocoles de contrôle et de validation. Le CIDOC CRM ne documente pas ces aspects. </p>
<p>Par sa structure et son formalisme, le CIDOC CRM est extensible et ses utilisateurs sont encouragés à créer des extensions dédiées à des communautés de pratique et des applications spécialisées. </p>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<th style="width:15%"><p><em>Note traducteur</em></p>
</th>
<td colspan="1">
<p>Le terme « construct » n’a pas d’équivalent français parfait, mais une recherche sommaire révèle que le terme « construit » (n.m.) semble répandu dans les domaines de la philosophie et de la sociologie et est celui dont le sens se rapproche le plus de la forme originale. </p>
<p>Le terme « use » (« foresees use of ») a été traduit par « usage » en adéquation avec la traduction de <code class="language-plaintext highlighter-rouge">P68_foresees_use_of</code>. </p>
</td>
</tr>
<tr>
<th style="width:15%"><p><em>Références</em></p>
</th>
<td colspan="1">
<p>Termium. « construct ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=construct&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=construct&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=construct&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
</td>
</tr>
</tbody>
</table>

<h2 id="portee-du-cidoc-crm"><span class="en heading">Scope of the CIDOC CRM - </span>Portée du CIDOC CRM</h2>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>The overall scope of the CIDOC CRM can be summarised in simple terms as the curated knowledge of museums.</p>
<p>However, a more detailed and useful definition can be articulated by defining both the Intended Scope, a broad and maximally-inclusive definition of general application principles, and the Practical Scope, which is expressed by the overall scope of a reference set of specific identifiable museum documentation standards and practices that the CIDOC CRM aims to encompass, however restricted in its details to the limitations of the Intended Scope.</p>
<p>The Intended Scope of the CIDOC CRM may be defined as all information required for the exchange and integration of heterogeneous scientific documentation of museum collections. This definition requires further elaboration:</p>
<ul><li><p>The term “scientific documentation” is intended to convey the requirement that the depth and quality of descriptive information that can be handled by the CIDOC CRM should be sufficient for serious academic research. This does not mean that information intended for presentation to members of the general public is excluded, but rather that the CIDOC CRM is intended to provide the level of detail and precision expected and required by museum professionals and researchers in the field. </p>
</li>
<li><p>The term “museum collections »is intended to cover all types of material collected and displayed by museums and related institutions, as defined by ICOM.<sup>1</sup> This includes collections, sites and monuments relating to fields such as social history, ethnography, archaeology, fine and applied arts, natural history, history of sciences and technology.</p>
</li>
<li><p>The documentation of collections includes the detailed description of individual items within collections, groups of items and collections as a whole. The CIDOC CRM is specifically intended to cover contextual information: the historical, geographical and theoretical background that gives museum collections much of their cultural significance and value. </p>
</li>
<li><p>The exchange of relevant information with libraries and archives, and the harmonisation of the CIDOC CRM with their models, falls within the Intended Scope of the CIDOC CRM. </p>
</li>
<li><p>Information required solely for the administration and management of cultural institutions, such as information relating to personnel, accounting, and visitor statistics, falls outside the Intended Scope of the CIDOC CRM.</p>
</li></ul>
<p>The Practical Scope<sup>2</sup> of the CIDOC CRM is expressed in terms of the current reference standards for museum documentation that have been used to guide and validate the CIDOC CRM’s development. The CIDOC CRM covers the same domain of discourse as the union of these reference standards; this means that data correctly encoded according to these museum documentation standards there can be a CIDOC CRM-compatible expression that conveys the same meaning. Discussions on the types of bias present in the CIDOC CRM are in progress within the CIDOC CRM community.</p>
<hr><p><sup>1 </sup>The ICOM Statutes provide a definition of the term “museum” at <a href="http://icom.museum/statutes.html#2"><span class="underline">http://icom.museum/statutes.html#2</span></a> </p>
<p><sup>2</sup> The Practical Scope of the CIDOC CRM, including a list of the relevant museum documentation standards, is discussed in more detail on the CIDOC CRM website at <a href="http://cidoc.ics.forth.gr/scope.html"><span class="underline">http://cidoc.ics.forth.gr/scope.html</span></a></p>
</td>
<td>
<p>Le domaine d’application global du CIDOC CRM peut être résumé, en termes simples, aux connaissances des musées [n.d.t. c.-à-d. les informations recensées dans les bases de données d’institutions patrimoniales].</p>
<p>Cependant, une définition plus détaillée et utile peut être articulée en définissant à la fois : </p>
<ul><li><p>le Domaine d’application prévu, une définition large et maximalement inclusive des principes généraux d'application, </p>
</li>
<li><p>et le Domaine d’application pratique, qui est exprimé par le domaine d’application d'un ensemble de référence comprenant des normes et des pratiques spécifiques et identifiables en matière de documentation muséale, normes et pratiques que le CIDOC CRM vise à inclure, même si ses détails sont restreints aux contraintes du Domaine d'application prévu.</p>
</li></ul>
<p>Le Domaine d’application prévu du CIDOC CRM peut être défini comme l’ensemble des informations nécessaires à l'échange et à l'intégration de la documentation scientifique hétérogène des collections muséales. Cette définition requiert une élaboration plus approfondie : </p>
<ul><li><p>Le terme « documentation scientifique » est destiné à exprimer l'exigence selon laquelle la profondeur et la qualité des informations descriptives qui peuvent être traitées par le CIDOC CRM doivent être suffisantes pour une recherche académique sérieuse. Cela ne signifie pas que les informations destinées à être présentées aux membres du grand public sont exclues, mais plutôt que le CIDOC CRM est prévu pour fournir le niveau de détail et de précision attendu et requis par les professionnels des musées et les chercheurs du domaine [n.d.t. patrimonial].</p>
</li>
<li><p>Le terme « collections muséales » désigne tous les types de matériaux conservés et exposés par les musées et les institutions qui y sont associées, comme l’indique l'ICOM<sup>1</sup>. Cela comprend les collections, les sites et les monuments liés à des domaines tels que l'histoire sociale, l'ethnographie, l'archéologie, les beaux-arts et les arts appliqués, l’histoire naturelle, ainsi que l’histoire des sciences et de la technologie.</p>
</li>
<li><p>La documentation des collections inclut la description détaillée d’entités individuelles au sein des collections, de groupes d’entités et de collections dans leur ensemble. Le CIDOC CRM est spécifiquement destiné à couvrir les informations contextuelles, à savoir le contexte historique, géographique et théorique qui confère aux collections muséales une grande partie de leur signification et de leur valeur culturelles.</p>
</li>
<li><p>L'échange d'informations pertinentes avec les bibliothèques et les archives, et l'harmonisation du CIDOC CRM avec leurs modèles, s'inscrit dans le Domaine d'application prévu du CIDOC CRM.</p>
</li>
<li><p>Les informations requises uniquement pour l'administration et la gestion des institutions culturelles, telles que les informations relatives au personnel, à la comptabilité et aux statistiques des visiteurs, n'entrent pas dans le Domaine d'application prévu du CRM CIDOC.</p>
</li></ul>
<p>Le Domaine d’application pratique<sup>2</sup> du CIDOC CRM est exprimé en termes de normes de référence actuelles pour la documentation muséale qui ont été utilisées pour guider et valider le développement du CIDOC CRM. Le CIDOC CRM couvre le même domaine de discours que l'union de ces référentiels; cela signifie que pour les données correctement encodées conformément à ces normes de documentation muséale, il peut y avoir une expression CIDOC CRM compatible qui transmet la même signification. Des discussions sur les types de biais présents dans le CIDOC CRM sont en cours au sein de la communauté CIDOC CRM.</p>
<hr><p><sup>1 </sup>Les statuts de l'ICOM fournissent une définition du terme « musée » à l'adresse <a href="http://icom.museum/statutes.html#2"><span class="underline">http://icom.museum/statutes.html#2</span></a>(page non accessible).</p>
<p><sup>2</sup> Le Domaine d'application pratique du CIDOC CRM, y compris une liste des normes de documentation muséales pertinentes, est discuté plus en détail sur le site Web du CIDOC CRM à l'adresse <a href="http://cidoc.ics.forth.gr/scope.html"><span class="underline">http://cidoc.ics.forth.gr/scope.html</span></a>(page non accessible).</p>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<th style="width:15%"><p><em>Note traducteur</em></p>
</th>
<td colspan="1">
</td>
</tr>
<tr>
<th style="width:15%"><p><em>Références</em></p>
</th>
<td colspan="1">
</td>
</tr>
</tbody>
</table>

