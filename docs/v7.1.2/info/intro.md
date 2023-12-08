---
layout: page
title: CIDOC CRM Version 7.1.2
titleEn: CIDOC CRM Version 7.1.2
permalink: /v7.1.2/information/introduction
sidebar: v712
tab: versions
group: information
date: 2023-11-08
---

**Date de création** : 2023-11-08

**Dernière mise à jour** : 2023-11-08

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
<p>This document is the formal definition of the<strong> CIDOC Conceptual Reference Model (“CIDOC CRM”), </strong>a formal ontology intended to facilitate the integration, mediation and interchange of heterogeneous cultural heritage information and similar information from other domains, as further detailed below. The CRM is the culmination of more than two decades of standards development work by the International Committee for Documentation (CIDOC) of the International Council of Museums (ICOM). Work on the CRM itself began in 1996 under the auspices of the ICOM-CIDOC Documentation Standards Working Group. Since 2000, development of the CRM has been officially delegated by ICOM-CIDOC to the CIDOC CRM Special Interest Group (SIG). The SIG, in turn, collaborates with the ISO working group ISO/TC46/SC4/WG9 to bring the CRM to the form and status of an International Standard. This set of collaborations has resulted in the production of ISO21127:2004 and ISO21127:2014, the ISO standard editions of the CIDOC CRM. This collaboration will be continued in order to support the next update of the ISO standard edition. The present document belongs to the series of evolving versions of the formal definition of the CRM, which serve the ISO working group as community draft for the standard. Eventual minor differences, in semantics and notation, of the ISO standard text from the present, community CIDOC CRM version, which the ISO working group requires and implements, will be harmonized in the subsequent versions of the present, community CIDOC CRM formal definition document.</p>
</td>
<td>
<p>Ce document constitue la définition du <strong>Modèle conceptuel de référence du Comité international pour la documentation du Conseil international des musées (« CIDOC CRM »)</strong>, une ontologie formelle qui a pour objectif de faciliter l’intégration, la médiation et l’échange d’informations patrimoniales hétérogènes (ainsi que d'information comparable issue d'autres domaines pertinents détaillés plus bas). Le CIDOC CRM est le résultat du développement de standards par le Comité pour la documentation (CIDOC) du Conseil international des musées (ICOM), un travail qui a commencé en 1996 sous les auspices du Groupe de travail pour les standards en documentation. En 2000, ICOM-CIDOC a officiellement délégué les tâches de développement du CIDOC CRM au Groupe de travail spécial pour CIDOC CRM (CRM SIG), lequel travaille en collaboration avec le Groupe de travail ISO/TC46/SC4/WG9 afin de veiller à ce que le CIDOC CRM respecte les normes internationales en matière de standards. </p>
<p>Ces collaborations ont mené à la publication des documents ISO21127:2004 et ISO21127:2014, les normes ISO (International Standards Organization) du CIDOC CRM qui continueront d'être mises à jour. Ce document s'inscrit dans une série de versions évolutives de la définition formelle du CIDOC CRM qui servent de fondements au groupe de travail ISO. Des différences mineures de sémantique et de notation entre les formes ISO et communautaire de cette définition formelle seront harmonisées dans ses versions futures. </p>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<th style="width:15%"><p><em>Note de traduction</em></p>
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
<p>The primary role of the CIDOC CRM is to enable the exchange and integration of information from heterogeneous sources for the reconstruction and interpretation of the past at a human scale, based on all kinds of material evidence, including texts, audio-visual material and oral tradition. It starts from, but is not limited to, the needs of museum documentation and research based on museum holdings. It aims at providing the semantic definitions and clarifications needed to transform disparate, localised information sources into a coherent global resource, be it within a larger institution, in intranets or on the Internet, and to make it available for scholarly interpretation and scientific evaluation. These goals determine the constructs and level of detail of the CIDOC CRM. </p>
<p>More specifically, it defines, in terms of a formal ontology, the <strong>underlying semantics</strong> of database schemata and structured documents used in the documentation of cultural heritage and scientific activities. In particular it defines the semantics related to the study of the past and current state of our world, as it is characteristic for museums, but also or other cultural heritage institutions and disciplines. It does <strong>not</strong> define any of the <strong>terminology</strong> appearing typically as data in the respective data structures; it foresees, however, the characteristic relationships for its use. It does <strong>not</strong> aim at proposing what cultural heritage institutions <strong>should</strong> document. Rather, it explains the logic of what they actually currently document, and thereby enables <strong>semantic interoperability.</strong></p>
<p>The CIDOC CRM intends, moreover, to provide a model of the intellectual structure of the respective kinds of mentioned documentation in logical terms. As such, it has not been optimised for implementation specific storage and processing factors. Actual system implementations may lead to solutions where elements and links between relevant elements of our conceptualizations are no longer explicit in a database or other structured storage system. For instance, the birth event that connects elements such as father, mother, birth date, birth place may not appear in the database, in order to save storage space or response time of the system. The CIDOC CRM provides a conceptual and technical means to explain how such apparently disparate entities are semantically and logically interconnected, and how the ability of the database to answer certain intellectual questions is affected by the omission of such elements and links.</p>
<p>The CIDOC CRM aims to support the following specific functionalities:</p>
<ul><li><p>Inform developers of information systems as a guide to good practice in conceptual modelling, in order to effectively structure and relate information assets of cultural documentation. </p>
</li>
<li><p>Serve as a common language for domain experts and IT developers to formulate requirements and to agree on system functionalities with respect to the correct handling of cultural contents.</p>
</li>
<li><p>To serve as a formal language for the identification of common information contents in different data formats; in particular, to support the implementation of automatic data transformation algorithms from local to global data structures without loss of meaning. The latter being useful for data exchange, data migration from legacy systems, data information integration and mediation of heterogeneous sources.</p>
</li>
<li><p>To support associative queries against integrated resources by providing a global model of the basic classes and their associations to formulate such queries.</p>
</li>
<li><p>It is further believed that advanced natural language algorithms and case-specific heuristics can take significant advantage of the CIDOC CRM to resolve free text information into a formal logical form, if that is regarded beneficial. The CIDOC CRM is not thought, however, to be a means to replace scholarly text, rich in meaning, by logical forms, but only a means to identify related data. </p>
</li></ul>
<p>Users of the CIDOC CRM should be aware that the definition of data entry systems requires support of community-specific terminology, guidance to what should be documented and in which sequence, and application-specific consistency controls. The CIDOC CRM does not provide such notions.</p>
<p>By its very structure and formalism, the CIDOC CRM is extensible and users are encouraged to create extensions for the needs of more specialized communities and applications.</p>
</td>
<td>
<p>CIDOC CRM a pour principale fonction de favoriser l’échange d’informations et leur intégration parmi des sources hétérogènes d’informations dédiées à la reconstruction et l'interprétation du passé à échelle humaine sur la base de preuves matérielles incluant des textes, du matériel audio-visuel et des traditions orales. Il émane des besoins de documentation et de recherche des musées sur les objets de leurs collections sans pour autant s'y limiter. Il fournit les définitions sémantiques et clarifications nécessaires à la transformation d’informations localisées et disparates grâce à une ressource globale et cohérente [n.d.t. prenant la forme d’une norme de documentation], que ce soit au sein d’une institution de plus grande envergure, d’intranets ou sur Internet pour les rendre utilisables à des fins d'interprétation experte et d'évaluation scientifique. Ces objectifs déterminent le niveau de détail et les construits du CIDOC CRM. </p>
<p>Plus spécifiquement, ce modèle définit par une ontologie formelle la <strong>sémantique</strong> qui sous-tend les schèmes de base de données et les <strong>documents structurés</strong> utilisés dans le cadre de la documentation en milieu patrimonial ou scientifique. Il définit particulièrement la sémantique portant sur l'étude du passé et sur l'état actuel du monde, une approche caractéristique des musées et d'autres institutions et disciplines culturelles. Le CIDOC CRM ne définit pas la <strong>terminologie</strong> qui se trouve typiquement dans les structures de données sous forme de valeurs, bien qu’il entrevoit les relations caractéristiques nécessaires à son usage [n.d.t. de sorte que le CIDOC CRM précise comment utiliser une classe, mais pas les valeurs qu’elle comprend lorsqu’elle est implémentée]. Il <strong>n’a pas </strong>pour objectif d’indiquer ce que les institutions culturelles patrimoniales <strong>devraient</strong> documenter, mais bien d’expliquer la logique de ce qu’elles documentent afin de favoriser l’<a href="/v7.1.2/information/introduction#terminologie-interoperabilite-semantique"><span class="underline"><strong>interopérabilité sémantique</strong></span></a>. </p>
<p>Le CIDOC CRM propose un modèle des structures intellectuelles de la documentation sus-mentionnée en termes logiques et n’est donc pas optimisé pour une implémentation spécifique, en particulier en ce qui a trait au stockage et au traitement des données. L’implémentation peut en outre mener à ce que certains éléments des conceptualisations du CIDOC CRM ne soient plus explicites dans le contexte d'une base de données ou d'un système de stockage structuré. Par exemple, un évènement de naissance reliant des éléments tels que le père, la mère, la date et le lieu de naissance peut ne pas être apparent dans une base de données afin de préserver l’espace de stockage et le temps de réponse d’un système. Le CIDOC CRM offre les moyens conceptuels et techniques pour expliquer en quoi ces entités à première vue disparates sont sémantiquement et logiquement interconnectées et comment la capacité d’une base de données à fournir des réponses à des questions de nature intellectuelle est limitée par l’omission de tels liens et éléments. </p>
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
<th style="width:15%"><p><em>Note de traduction</em></p>
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
<p>The overall scope of the CIDOC CRM can be summarised in simple terms as the curated, factual knowledge about the past at a human scale.</p>
<p>However, a more detailed and useful definition can be articulated by defining both the Intended Scope, a broad and maximally-inclusive definition of general application principles, and the Practical Scope, which is expressed by the overall scope of a growing reference set of specific, identifiable documentation standards and practices that the CIDOC CRM aims to semantically describe, restricted, always, in its details to the limitations of the Intended Scope.</p>
<p>The reasons for these distinctions between Intended and Practical Scope are twofold. Firstly, the CIDOC CRM is developed in a “bottom-up” manner, starting from well-understood, actual, and widely used concepts of domain experts, which are disambiguated and gradually generalized as more forms of encoding are encountered. This aims to avoid the misadaptations and vagueness that can sometimes be found in introspection-driven attempts to find overarching concepts for such a wide scope, and provides stability to the generalizations found. Secondly, it is a means to identify and keep a focus on the concepts most needed by the communities working in the scope of the CIDOC CRM and to maintain a well-defined agenda for its evolution.</p>
<p>The Intended Scope of the CIDOC CRM may, therefore, be defined as all information required for the exchange and integration of heterogeneous scientific and scholarly documentation about the past at a human scale and the available documented and empirical evidence for this. This definition requires further elaboration:</p>
<ul><li><p>The term “scientific and scholarly documentation” is intended to convey the requirement that the depth and quality of descriptive information that can be handled by the CIDOC CRM should be sufficient for serious academic research. This does not mean that information intended for presentation to members of the general public is excluded, but rather that the CRM is intended to provide the level of detail and precision expected and required by museum professionals and researchers in the field.</p>
</li>
<li><p>As “available documented and material evidence” are regarded all types of material collected and displayed by museums and related institutions, as defined by ICOM<sup>1</sup>, and other collections, in-situ objects, sites, monuments and intangible heritage relating to fields such as social history, ethnography, archaeology, fine and applied arts, natural history, history of sciences and technology. </p>
</li>
<li><p>The concept “documentation” includes the detailed description of individual items, in situ or within collections, groups of items and collections as a whole, as well as practices of intangible heritage. It pertains to their current state as well as to information about their past. The CIDOC CRM is specifically intended to cover contextual information: the historical, geographical and theoretical background that gives cultural heritage collections much of their cultural significance and value.</p>
</li>
<li><p>The exchange of relevant information with libraries and archives, and the harmonisation of the CIDOC CRM with their models, falls within the Intended Scope of the CIDOC CRM. </p>
</li>
<li><p>Information required solely for the administration and management of cultural institutions, such as information relating to personnel, accounting, and visitor statistics, falls outside the Intended Scope of the CIDOC CRM.</p>
</li></ul>
<p>The Practical Scope<sup>2</sup> of the CIDOC CRM is expressed in terms of the set of reference standards and de facto standards for documenting factual knowledge that have been used to guide and validate the CIDOC CRM’s development and its further evolution. The CRM covers the same domain of discourse as the union of these reference standards; this means that for data correctly encoded according to these documentation formats there can be a CIDOC CRM-compatible expression that conveys the same meaning. </p>
<p>As part of the on-going work of keep the standard up-to-date, discussions on the types of bias present in the CIDOC CRM are in progress within the CIDOC CRM community.</p>
<hr><p><sup>1 </sup>The ICOM Statutes provide a definition of the term “museum” at <a href="http://icom.museum/statutes.html#2"><span class="underline">http://icom.museum/statutes.html#2</span></a> </p>
<p><sup>2</sup> The Practical Scope of the CIDOC CRM, including a list of the relevant museum documentation standards, is discussed in more detail on the CIDOC CRM website at <a href="http://cidoc.ics.forth.gr/scope.html"><span class="underline">http://cidoc.ics.forth.gr/scope.html</span></a></p>
</td>
<td>
<p>Le domaine d’application global du CIDOC CRM peut être résumé, en termes simples, aux connaissances factuelles au sujet du passé à échelle humaine [n.d.t. c.-à-d. les informations recensées dans les bases de données d’institutions patrimoniales].</p>
<p><code class="language-plaintext highlighter-rouge"></code></p>
<p>Cependant, une définition plus détaillée et utile peut être articulée en définissant à la fois : </p>
<ul><li><p>le Domaine d’application prévu, une définition large et maximalement inclusive des principes généraux d'application, </p>
</li>
<li><p>et le Domaine d’application pratique, qui est exprimé par le domaine d’application d'un ensemble de référence croissant comprenant des normes et des pratiques spécifiques et identifiables en matière de documentation, normes et pratiques que le CIDOC CRM vise à décrire sémantiquement, même si ses détails sont toujours restreints aux contraintes du Domaine d'application prévu.</p>
</li></ul>
<p>La distinction entre les domaines d'application prévu et pratique est attribuable à deux éléments. En premier lieu, le CIDOC CRM est développé avec une approche ascendante (« <em>bottom up</em> ») fondée sur des concepts établis, réels et bien compris des expert·e·s, lesquels sont ensuite désambiguïsés et généralisés de manière graduelle au fur et à mesure que de nouvelles formes d'encodage émergent. Cette distinction confère à ces concepts une certaine stabilité et a pour objectif d'éviter le flou et les erreurs qui peuvent s'immiscer avec des approches plus introspectives visant à trouver des concepts englobant un domaine aussi large. En second lieu, cette distinction permet d'identifier les concepts essentiels aux communautés du domaine du CIDOC CRM, d'y accorder une attention particulière et soutenue, et de planifier leur évolution de manière ordonnée. </p>
<p>Le Domaine d’application prévu du CIDOC CRM peut être défini comme l’ensemble des informations nécessaires à l'échange et à l'intégration de la documentation hétérogène scientifique et experte au sujet du passé à l'échelle humaine ainsi que des preuves empiriques et documentées disponibles la soutenant. Cette définition requiert une élaboration plus approfondie : </p>
<ul><li><p>Le terme « documentation scientifique et experte » est destiné à exprimer l'exigence selon laquelle la profondeur et la qualité des informations descriptives qui peuvent être traitées par le CIDOC CRM doivent être suffisantes pour une recherche académique sérieuse. Cela ne signifie pas que les informations destinées à être présentées aux membres du grand public sont exclues, mais plutôt que le CIDOC CRM est prévu pour fournir le niveau de détail et de précision attendu et requis par les professionnels des musées et les chercheurs du domaine [n.d.t. patrimonial].</p>
</li>
<li><p>Le terme « preuves documentées et matérielles disponibles » désigne tous les types de matériaux conservés et exposés par les musées et les institutions qui y sont associées telles que définies par l'ICOM<sup>1</sup>, ainsi que les collections, objets in situ, sites, monuments, et patrimoines intangibles liés à des domaines tels que l'histoire sociale, l'ethnographie, l'archéologie, les beaux-arts et les arts appliqués, l’histoire naturelle, ainsi que l’histoire des sciences et de la technologie.</p>
</li>
<li><p>Le concept de « documentation » inclut la description détaillée d’entités individuelles, in situ ou au sein des collections, de groupes d’entités et de collections dans leur ensemble, et de pratiques culturelles intangibles que ce soit au sujet de leur état actuel ou passé. Le CIDOC CRM est spécifiquement destiné à couvrir les informations contextuelles, à savoir le contexte historique, géographique et théorique qui confère aux collections du patrimoine culturel une grande partie de leur signification et de leur valeur culturelles.</p>
</li>
<li><p>L'échange d'informations pertinentes avec les bibliothèques et les archives, et l'harmonisation du CIDOC CRM avec leurs modèles, s'inscrit dans le Domaine d'application prévu du CIDOC CRM.</p>
</li>
<li><p>Les informations requises uniquement pour l'administration et la gestion des institutions culturelles, telles que les informations relatives au personnel, à la comptabilité et aux statistiques des visiteurs, n'entrent pas dans le Domaine d'application prévu du CRM CIDOC.</p>
</li></ul>
<p>Le Domaine d’application pratique<sup>2</sup> du CIDOC CRM est exprimé en termes d'ensembles de normes de références et d'usage pour documenter les connaissances factuelles qui ont été utilisées pour guider et valider le développement du CIDOC CRM ainsi que son évolution. Le CIDOC CRM couvre le même domaine de discours que l'union de ces référentiels; cela signifie que pour les données correctement encodées conformément à ces formats de documentation, il peut y avoir une expression CIDOC CRM compatible qui transmet la même signification. Dans le cadre du travail continu visant à maintenir la norme à jour, des discussions sur les types de biais présents dans le CIDOC CRM sont en cours au sein de la communauté CIDOC CRM.</p>
<hr><p><sup>1 </sup>Les statuts de l'ICOM fournissent une définition du terme « musée » à l'adresse <a href="http://icom.museum/statutes.html#2"><span class="underline">http://icom.museum/statutes.html#2</span></a>(page non accessible).</p>
<p><sup>2</sup> Le Domaine d'application pratique du CIDOC CRM, y compris une liste des normes de documentation muséales pertinentes, est discuté plus en détail sur le site Web du CIDOC CRM à l'adresse <a href="http://cidoc.ics.forth.gr/scope.html"><span class="underline">http://cidoc.ics.forth.gr/scope.html</span></a>(page non accessible).</p>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<th style="width:15%"><p><em>Note de traduction</em></p>
</th>
<td colspan="1">
</td>
</tr>
<tr>
<th style="width:15%"><p><em>Références</em></p>
</th>
<td colspan="1">
<p><em></em></p>
</td>
</tr>
</tbody>
</table>

<h2 id="compatibilite-avec-le-cidoc-crm"><span class="en heading">Compatibility with the CIDOC CRM - </span>Compatibilité avec le CIDOC CRM</h2>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>Users intending to take advantage of the semantic interoperability offered by the CIDOC CRM should ensure conformance with the relevant data structures. Conformance pertains either to data to be made accessible in an integrated environment or intended for transport to other environments. Any encoding of data in a formal language that preserves the relations of the classes, properties, and inheritance rules defined by this International Standard, is regarded as conformant.</p>
<p>Conformance with the CIDOC CRM does not require complete matching of all local documentation structures, nor that all concepts and structures present in this International Standard be implemented. This International Standard is intended to allow room both for extensions, needed to capture the full richness of cultural documentation, and for simplification, in the interests of economy. A system will be deemed partially conformant if it supports a subset of subclasses and sub properties defined by this International Standard. Designers of the system should publish details of the constructs that are supported.</p>
<p>The focus of the CIDOC CRM is the exchange and mediation of structured information. It does not require the interpretation of unstructured (free text) information into a structured, logical form. Unstructured information is supported, but falls outside the scope of conformance considerations.</p>
<p>Any documentation system will be deemed conformant with this International Standard, regardless of the internal data structures it uses; if a deterministic logical algorithm can be constructed, that transforms data contained in the system into a directly compatible form without loss of meaning.</p>
<p>No assumptions are made as to the nature of this algorithm. "Without loss of meaning" signifies that designers and users of the system are satisfied that the data representation corresponds to the semantic definitions provided by this International Standard.   </p>
</td>
<td>
<p>Les utilisateurs voulant tirer avantage de l’interopérabilité sémantique du CIDOC CRM devraient s’assurer de la conformité de leurs structures de données avec celui-ci. La conformité des données réfère à leur accessibilité dans le contexte d’un environnement [n.d.t. d’utilisateur] intégré ou de leur transfert vers d’autres environnements. </p>
<p>Tout encodage de données dans un langage formel qui maintient les relations des classes, des propriétés, ainsi que des règles d’<a href="/v7.1.2/information/introduction#terminologie-heritage"><span class="underline">héritage</span></a> définies par le CIDOC CRM est considéré y être conforme. Ceci dit, cette conformité ne requiert pas une équivalence complète de toutes les structures de documentation locales, ni que tous les concepts et structures du CIDOC CRM ne soient implémentés. </p>
<p>Ce standard international a pour objectif de permettre la mise en place d’extensions nécessaires pour saisir la richesse des phénomènes culturels et de leur documentation, et ce, tout en prônant la parcimonie. Un système est considéré partiellement conforme s’il soutient un sous-ensemble des <a href="/v7.1.2/information/introduction#terminologie-sous-classe"><span class="underline">sous-classes</span></a> et <a href="/v7.1.2/information/introduction#terminologie-sous-propriete"><span class="underline">sous-propriétés </span></a>définies par ce standard. Les concepteurs de systèmes devraient publier le détail des construits qui sont supportés par leur système. </p>
<p>Le CIDOC CRM porte principalement sur l’échange et la médiation d’information structurée et n’exige pas l’interprétation d’information non structurée dans une forme logique. L’information non structurée peut être traitée par le CIDOC CRM, mais les résultats qui en découlent ne sont pas pris en compte dans l’évaluation de la conformité d’un système. </p>
<p>Tout système documentaire sera considéré conforme [n.d.t. avec les règles du CIDOC CRM], peu importe les structures de données internes qu’il utilise, si des algorithmes peuvent transformer les données non structurées du système en une forme compatible avec le CIDOC CRM sans que la signification n’en soit affectée. </p>
<p>« Sans que la signification n’en soit affectée » signifie que les concepteurs et les utilisateurs du système considèrent que la représentation résultant de l’utilisation de cet algorithme correspond aux définitions sémantiques fournies dans ce standard. </p>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<th style="width:15%"><p><em>Note de traduction</em></p>
</th>
<td colspan="1">
<p>Certains paragraphes ont été édités dans la version francophone à des fins de compréhension. Les sections concernées sont indiquées de [n.d.t. texte concerné]. </p>
<p>Le terme « construct » n’a pas d’équivalent français parfait, mais une recherche sommaire révèle que le terme « construit » (n.m.) semble répandu dans les domaines de la philosophie et de la sociologie et est celui dont le sens se rapproche le plus de la forme originale. </p>
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

<h2 id="terminologie"><span class="en heading">Terminology - </span>Terminologie</h2>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>The following definitions of key terminology used in this document are provided both as an aid to readers unfamiliar with object-oriented modelling terminology, and to specify the precise usage of terms that are sometimes applied inconsistently across the object-oriented modelling community for the purpose of this document. Where applicable, the editors have tried to consistently use terminology that is compatible with that of the Resource Description Framework (RDF),<sup>3</sup> a recommendation of the World Wide Web Consortium. The editors have tried to find a language, which is comprehensible to the non-computer expert and precise enough for the computer expert so that both understand the intended meaning.  </p>
<hr><p><sup>3</sup> Information about the Resource Description Framework (RDF) can be found at http://www.w3.org/RDF/</p>
</td>
<td>
<p>Les définitions suivantes ont pour objectif d’aider le lecteur qui ne serait pas familier avec la terminologie de la modélisation orientée-objet ainsi que de préciser l’usage de termes qui ne sont parfois pas utilisés de manière uniforme par cette communauté de modélisation. Les éditeurs ont tenté d’utiliser une terminologie compatible avec les recommandations du World Wide Web Consortium quant au Resource Description Framework (RDF)<sup>3</sup>. Les éditeurs ont utilisé un langage compréhensible pour le lecteur qui ne serait pas un expert informatique tout en préconisant une précision suffisante pour servir les besoins d’un tel expert de manière à ce que l’un comme l’autre comprenne le sens du CIDOC CRM. </p>
<hr><p><sup>3</sup> Plus d'informations au sujet du Resource Description Framework (RDF) sont disponibles au <a href="http://www.w3.org/RDF/"><span class="underline">http://www.w3.org/RDF/</span></a>. </p>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<th style="width:15%"><p><em>Note de traduction</em></p>
</th>
<td colspan="1">
<p>Une recherche sommaire de la documentation technique traduite sur le site du World Wide Web Consortium ne révèle pas de traduction francophone de « Resource Description Framework (RDF) », de sorte que l’appellation anglophone est préconisée dans la présente traduction. </p>
</td>
</tr>
<tr>
<th style="width:15%"><p><em>Références</em></p>
</th>
<td colspan="1">
<p>Berners-Lee, Tim, Tim Bray, Dan Connolly, Paul Cotton, Roy Fielding, Mario Jeckle, Chris Lilley, et al. « Architecture du World Wide Web: Volume Un ». Recommandation. 2005. Reprint, Cambridge, USA-MA: World Wide Web Consortium (W3C), 2006.<a href="http://www.opikanoba.org/tr/w3c/webarch/"><span class="underline"> </span></a><a href="http://www.opikanoba.org/tr/w3c/webarch/"><span class="underline">http://www.opikanoba.org/tr/w3c/webarch/</span></a>.</p>
<p>Berrueta, Diego, et Jon Phipps. « Méthodes exemplaires pour la publication des vocabulaires RDF ». Meilleures pratiques. Cambridge, USA-MA: World Wide Web Consortium (W3C), 28 août 2008.<a href="http://www.yoyodesign.org/doc/w3c/swbp-vocab-pub/"><span class="underline"> </span></a><a href="http://www.yoyodesign.org/doc/w3c/swbp-vocab-pub/"><span class="underline">http://www.yoyodesign.org/doc/w3c/swbp-vocab-pub/</span></a>.</p>
<p>World Wide Web Consortium (W3C). « Translations of W3C Technical Reports ». World Wide Web Consortium (W3C), 8 mars 2021.<a href="https://www.w3.org/Translations/"><span class="underline"> </span></a><a href="https://www.w3.org/Translations/"><span class="underline">https://www.w3.org/Translations/</span></a>.</p>
</td>
</tr>
</tbody>
</table>

<table class="original-table">
<tbody>
<tr>
<td class="en">
<p>class</p>
<p><em></em></p>
</td>
<td class="en">
<p>A class is a category of items that share one or more common traits<strong> </strong>serving as criteria to identify the items belonging to the class. These <strong>properties</strong> need not be explicitly formulated in logical terms, but may be described in a text (here called a <strong>scope note</strong>) that refers to a common conceptualisation of domain experts. The sum of these traits is called the <strong>intension</strong> of the class. A class may be the <strong>domain</strong> or <strong>range</strong> of none, one or more properties formally defined in a model. The formally defined properties need not be part of the intension of their domains or ranges: such properties are optional. An item that belongs to a class is called an <strong>instance</strong> of this class. A class is associated with an open set of real-life instances, known as the <strong>extension</strong> of the class. Here “open” is used in the sense that it is generally beyond our capabilities to know all instances of a class in the world and indeed that the future may bring new instances about at any time (<strong>Open World</strong>). Therefore, a class cannot be defined by enumerating its instances. A class plays a role analogous to a grammatical noun, and can be completely defined without reference to any other construct (unlike properties<strong>,</strong> which must have an unambiguously defined domain and range). In some contexts, the terms individual class, entity or node are used synonymously with class. </p>
<p>For example: </p>
<p>Person is a class. To be a Person may actually be determined by DNA characteristics, but we all know what a Person is. A Person may have the property of being a member of a Group, but it is not necessary to be member of a Group in order to be a Person. We shall never know all Persons of the past. There will be more Persons in the future. </p>
</td>
<td>
<a name="terminologie-classe"></a><p>Classe</p>
</td>
<td>
<p>Une classe est une catégorie d'éléments qui partagent un ou plusieurs traits communs servant de critères pour identifier les éléments appartenant à cette classe. Ces traits communs n'ont pas besoin d'être explicitement formulés en termes logiques (appelés ici<a href="/v7.1.2/information/introduction#terminologie-propriete"><span class="underline"> </span></a><a href="/v7.1.2/information/introduction#terminologie-propriete"><span class="underline"><strong>propriétés</strong></span></a>), mais peuvent être décrits dans un texte faisant référence à une conceptualisation commune des experts du domaine (texte appelé ici<a href="/v7.1.2/information/introduction#terminologie-note-dapplication"><span class="underline"> </span></a><a href="/v7.1.2/information/introduction#terminologie-note-dapplication"><span class="underline"><strong>note d'application</strong></span></a>). La somme de ces traits s'appelle l'<a href="/v7.1.2/information/introduction#terminologie-intension"><span class="underline"><strong>intension</strong></span></a> de la classe. Une classe peut être le <a href="/v7.1.2/information/introduction#terminologie-domaine"><span class="underline"><strong>domaine</strong></span></a> ou la <a href="/v7.1.2/information/introduction#terminologie-portee"><span class="underline"><strong>portée</strong></span></a> d’aucune, d’une ou de plusieurs propriétés formellement définies dans un modèle. Les propriétés formellement définies n'ont pas besoin de faire partie de l'intension de leurs domaines ou portées : ces propriétés sont facultatives. Un élément qui appartient à une classe est appelé une <a href="/v7.1.2/information/introduction#terminologie-instance"><span class="underline"><strong>instance</strong></span></a> de cette classe. Une classe est associée à un ensemble ouvert d'instances réelles (l'<a href="/v7.1.2/information/introduction#terminologie-extension"><span class="underline"><strong>extension</strong></span></a> de la classe), ce qui veut dire qu’une capacité humaine normale ne permet pas de connaître toutes les instances d’une classe existant dans le « monde » à un moment donné, ni de prendre en compte les instances qui pourraient émerger dans le futur (voir <a href="/v7.1.2/information/introduction#terminologie-monde-ouvert"><span class="underline"><strong>Monde Ouvert</strong></span></a>). Par conséquent, une classe ne peut pas être définie en énumérant ses instances. </p>
<p>Une classe joue un rôle analogue à un nom grammatical [n.d.t. dans le contexte d’une langue SVO, c.-à-d. une langue comme le français dont les phrases suivent généralement l’ordre sujet-verbe-objet] et peut être complètement définie sans référence à aucun autre construit (contrairement aux propriétés, qui doivent avoir un domaine et une portée définis sans ambiguïté). </p>
<p>Dans certains contextes, les termes classe individuelle, entité ou nœud sont utilisés comme synonymes de classe.</p>
<p>Par exemple :</p>
<p><code class="language-plaintext highlighter-rouge">E21_Personne</code> est une classe [n.d.t. désignant] ce que « nous » comprenons collectivement être une « personne », laquelle peut être déterminée par des caractéristiques de l’ADN par exemple. Une instance de <code class="language-plaintext highlighter-rouge">E21_Personne</code> peut avoir la propriété d'être membre d'un groupe (<code class="language-plaintext highlighter-rouge">E74_Groupe</code>), mais il n'est pas nécessaire d'être membre d'une <code class="language-plaintext highlighter-rouge">E74_Groupe</code> pour être une <code class="language-plaintext highlighter-rouge">E21_Personne</code> et il n’est pas possible de connaître toutes les personnes du passé tout comme il y aura plus de personnes dans le futur. </p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Wikipédia. « Langue SVO ». Dans <em>Wikipédia</em>. San Francisco, US-CA: Wikipédia, 31 octobre 2020.<a href="https://fr.wikipedia.org/w/index.php?title=Langue_SVO&oldid=176099662"><span class="underline"> </span></a><a href="https://fr.wikipedia.org/w/index.php?title=Langue_SVO&oldid=176099662"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Langue_SVO&oldid=176099662</span></a>.</p>
</td>
</tr>
<tr>
<td class="en">
<p>subclass</p>
<p><em></em></p>
</td>
<td class="en">
<p>A subclass is a <strong>class</strong> that is a specialization of another class (its <strong>superclass</strong>). Specialization or the IsA relationship means that: </p>
<ul><li><p>all <strong>instances</strong> of the subclass are also instances of its superclass, </p>
</li>
<li><p>the <strong>intension</strong> of the subclass extends the intension of its superclass, i.e., its traits are more restrictive than that of its superclass and </p>
</li>
<li><p>the subclass inherits the definition of all of the <strong>properties</strong> declared for its superclass without exceptions (<strong>strict inheritance</strong>), in addition to having none, one or more properties of its own. </p>
</li></ul>
<p>A subclass can have more than one immediate superclass and consequently inherits the properties of all of its superclasses (<strong>multiple inheritance</strong>). The IsA relationship or specialization between two or more classes gives rise to a structure known as a class hierarchy. The IsA relationship is transitive and may not be cyclic. In some contexts (e.g., the programming language C++) the term derived class is used synonymously with subclass. </p>
<p>For example:</p>
<p>Every Person IsA Biological Object, or Person is a subclass of Biological Object. </p>
<p>Also, every Person IsA Actor. A Person may die. However, other kinds of Actors, such as companies, don’t die (c.f. 2). </p>
<p>Every Biological Object IsA Physical Object. A Physical Object can be moved. Hence, a Person can be moved also (c.f. 3).</p>
</td>
<td>
<a name="terminologie-sous-classe"></a><p>Sous-classe</p>
</td>
<td>
<p>Une sous-classe est une <a href="/v7.1.2/information/introduction#terminologie-classe"><span class="underline">classe</span></a> qui est une spécialisation d'une autre classe (sa <a href="/v7.1.2/information/introduction#terminologie-super-classe"><span class="underline">super-classe</span></a>). La spécialisation ou la relation <code class="language-plaintext highlighter-rouge">estUn</code> signifie que :</p>
<ul><li><p>toutes les instances de la sous-classe sont également des instances de sa superclasse; </p>
</li>
<li><p>l<a href="/v7.1.2/information/introduction#terminologie-intension"><span class="underline">'intension</span></a> de la sous-classe étend l'intension de sa super-classe, c'est-à-dire que ses traits sont plus restrictifs que celui de sa super-classe;</p>
</li>
<li><p>la sous-classe <a href="/v7.1.2/information/introduction#terminologie-heritage"><span class="underline">hérite</span></a> de la définition de toutes les propriétés déclarées pour sa super-classe, et ce sans exception (<a href="/v7.1.2/information/introduction#terminologie-heritage-strict"><span class="underline">héritage strict</span></a>), en plus de n'avoir aucune, une ou plusieurs propriétés qui lui sont propres.</p>
</li></ul>
<p>Une sous-classe peut relever directement de plus d'une super-classe et hériter par conséquent des propriétés de toutes ses super-classes (<a href="/v7.1.2/information/introduction#terminologie-heritage-multiple"><span class="underline"><strong>héritage multiple</strong></span></a>). La relation <code class="language-plaintext highlighter-rouge">estUn</code> (ou la spécialisation entre deux ou plusieurs classes) résulte en une hiérarchie de classes. C’est une relation transitive qui peut ne pas être cyclique. Dans certains contextes (p. ex. le langage de programmation C ++), le terme « classe dérivée » est utilisé comme synonyme de sous-classe.</p>
<p>Par exemple :</p>
<p>Chaque <code class="language-plaintext highlighter-rouge">E21_Personne</code> <code class="language-plaintext highlighter-rouge">estUn</code> <code class="language-plaintext highlighter-rouge">E20_Objet_biologique</code>, où <code class="language-plaintext highlighter-rouge">E21_Personne</code> est une sous-classe de <code class="language-plaintext highlighter-rouge">E20_Objet_biologique</code>.</p>
<p>De plus, chaque <code class="language-plaintext highlighter-rouge">E21_Personne</code> <code class="language-plaintext highlighter-rouge">estUn</code> <code class="language-plaintext highlighter-rouge">E39_Actant</code>. Une <code class="language-plaintext highlighter-rouge">E21_Personne</code> peut mourir, bien que d’autres types [n.d.t. d’instances] de <code class="language-plaintext highlighter-rouge">E39_Actant</code>, comme les entreprises, ne meurent pas (cf. 2).</p>
<p>Chaque <code class="language-plaintext highlighter-rouge">E20_Objet_biologique</code> <code class="language-plaintext highlighter-rouge">estUn</code> <code class="language-plaintext highlighter-rouge">E19_Objet_matériel</code>. Un <code class="language-plaintext highlighter-rouge">E19_Objet_matériel</code> peut être déplacé, ce qui implique qu’une <code class="language-plaintext highlighter-rouge">E21_Personne</code> peut également être déplacée (c.f. 3).</p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p><em></em></p>
</td>
</tr>
<tr>
<td class="en">
<p>superclass</p>
<p><em></em></p>
</td>
<td class="en">
<p>A superclass is a <strong>class</strong> that is a generalization of one or more other classes (its <strong>subclasses</strong>), which means that it subsumes all <strong>instances</strong> of its subclasses, and that it can also have additional instances that do not belong to any of its subclasses. The <strong>intension</strong> of the superclass is less restrictive than any of its subclasses. This subsumption relationship or generalization is the inverse of the IsA relationship or specialization.</p>
<p>For example:</p>
<p>“Biological Object subsumes Person” is synonymous with “Biological Object is a superclass of Person”. It needs fewer traits to identify an item as a Biological Object than to identify it as a Person.</p>
</td>
<td>
<a name="terminologie-super-classe"></a><p>Super-classe</p>
</td>
<td>
<p>Une super-classe est une <a href="/v7.1.2/information/introduction#terminologie-classe"><span class="underline"><strong>classe</strong></span></a> qui est une généralisation d'une ou de plusieurs autres classes (ses <a href="/v7.1.2/information/introduction#terminologie-sous-classe"><span class="underline"><strong>sous-classes</strong></span></a>), ce qui signifie qu'elle englobe toutes les <a href="/v7.1.2/information/introduction#terminologie-instance"><span class="underline"><strong>instances</strong></span></a> de ses sous-classes et qu'elle peut également avoir des instances supplémentaires qui n'appartiennent à aucune de ses sous-classes. L'<a href="/v7.1.2/information/introduction#terminologie-intension"><span class="underline"><strong>intension</strong></span></a> de la super-classe est moins restrictive que n'importe laquelle de ses sous-classes. Cette relation de subsomption ou de généralisation est l’inverse de la relation ou de la spécialisation <code class="language-plaintext highlighter-rouge">estUn</code>.</p>
<p>Par exemple :</p>
<p>« <code class="language-plaintext highlighter-rouge">E20_Objet_biologique</code> subsume <code class="language-plaintext highlighter-rouge">E21_Personne</code> » est synonyme de « <code class="language-plaintext highlighter-rouge">E20_Objet_biologique</code> est une super-classe de <code class="language-plaintext highlighter-rouge">E21_Personne</code> ». Il faut en effet moins de traits [n.d.t. tels qu’ils sont définis dans la <a href="/v7.1.2/information/introduction#terminologie-note-dapplication"><span class="underline">note d’application</span></a>] pour identifier un élément en tant que <code class="language-plaintext highlighter-rouge">E20_Objet_biologique</code> que pour l'identifier en tant que <code class="language-plaintext highlighter-rouge">E21_Personne</code>.</p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p><em></em></p>
</td>
</tr>
<tr>
<td class="en">
<p>intension</p>
<p><em></em></p>
</td>
<td class="en">
<p>The intension of a <strong>class</strong> or <strong>property</strong> is its intended meaning. It consists of one or more common traits<strong> </strong>shared by all <strong>instances</strong> of the class or property. These traits need not be explicitly formulated in logical terms, but may just be described in a text (here called a <strong>scope note</strong>) that refers to a conceptualisation common to domain experts. In particular, the so-called <strong>primitive </strong>concepts, which make up most of the CIDOC CRM, cannot be further reduced to other concepts by logical terms.  </p>
</td>
<td>
<a name="terminologie-intension"></a><p>Intension</p>
</td>
<td>
<p>L'intension d'une <a href="/v7.1.2/information/introduction#terminologie-classe"><span class="underline"><strong>classe</strong></span></a> ou d'une <a href="/v7.1.2/information/introduction#terminologie-propriete"><span class="underline"><strong>propriété</strong></span></a> est sa signification prévue. Elle est composée d'un ou de plusieurs traits communs partagés par toutes les <a href="/v7.1.2/information/introduction#terminologie-instance"><span class="underline"><strong>instances</strong></span></a> de la classe ou de la propriété. Ces traits n'ont pas besoin d'être explicitement formulés en termes logiques, mais peuvent simplement être décrits dans un texte (appelé ici <a href="/v7.1.2/information/introduction#terminologie-note-dapplication"><span class="underline"><strong>note d'application</strong></span></a>) qui réfère à une conceptualisation commune aux experts du domaine. En particulier, les concepts dits <a href="/v7.1.2/information/introduction#terminologie-primitive"><span class="underline"><strong>primitifs</strong></span></a>, qui constituent l'essentiel du CIDOC CRM, ne peuvent être davantage réduits à d'autres concepts par des termes logiques.</p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p><em></em></p>
</td>
</tr>
<tr>
<td class="en">
<p>extension</p>
<p><em></em></p>
</td>
<td class="en">
<p>The extension of a <strong>class</strong> is the set of all real-life <strong>instances </strong>belonging to the class that fulfil the criteria of its <strong>intension</strong>. This set is “open” in the sense that it is generally beyond our capabilities to know all instances of a class in the world and indeed that the future may bring new instances about at any time (<strong>Open World</strong>). An information system may at any point in time refer to some instances of a class, which form a subset of its extension.</p>
</td>
<td>
<a name="terminologie-extension"></a><p>Extension</p>
</td>
<td>
<p>L'extension d'une <a href="/v7.1.2/information/introduction#terminologie-classe"><span class="underline"><strong>classe</strong></span></a> est l'ensemble de toutes les <a href="/v7.1.2/information/introduction#terminologie-instance"><span class="underline"><strong>instances</strong></span></a> « réelles » appartenant à la classe [n.d.t. du fait qu’elles] remplissent les critères de son <a href="/v7.1.2/information/introduction#terminologie-intension"><span class="underline"><strong>intension</strong></span></a>. Cet ensemble est « ouvert », ce qui veut dire qu’une capacité humaine normale ne permet pas de connaître toutes les instances d’une classe existant dans le « monde » à un moment donné, ni de prendre en compte les instances qui pourraient émerger dans le futur (voir <a href="/v7.1.2/information/introduction#terminologie-monde-ouvert"><span class="underline"><strong>Monde Ouvert</strong></span></a>). Un système d'information peut à n’importe quel moment faire référence à certaines instances d'une classe, lesquelles forment un sous-ensemble de son extension.</p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p><em></em></p>
</td>
</tr>
<tr>
<td class="en">
<p>scope note</p>
<p><em></em></p>
</td>
<td class="en">
<p>A scope note is a textual description of the <strong>intension</strong> of a <strong>class</strong> or <strong>property.</strong></p>
<p>Scope notes are not formal modelling constructs, but are provided to help explain the intended meaning and application of the CIDOC CRM’s classes and properties. Basically, they refer to a conceptualisation common to domain experts and disambiguate between different possible interpretations. Illustrative example <strong>instances</strong> of classes and properties are also regularly provided in the scope notes for explanatory purposes.</p>
</td>
<td>
<a name="terminologie-note-dapplication"></a><p>Note d’application</p>
</td>
<td>
<p>Une note d'application est une description textuelle de l'<a href="/v7.1.2/information/introduction#terminologie-intension"><span class="underline"><strong>intension</strong></span></a> d'une <a href="/v7.1.2/information/introduction#terminologie-classe"><span class="underline"><strong>classe</strong></span></a> ou d'une <a href="/v7.1.2/information/introduction#terminologie-propriete"><span class="underline"><strong>propriété</strong></span></a>.</p>
<p>Les notes d’application ne sont pas des construits de modélisation formels, elles sont plutôt fournies pour expliquer la signification et l’application prévues des classes et des propriétés du CIDOC CRM. Fondamentalement, elles renvoient à une conceptualisation commune aux experts du domaine [n.d.t. qu’elles concernent] et clarifient les différentes interprétations possibles. Des exemples d’<a href="/v7.1.2/information/introduction#terminologie-instance"><span class="underline"><strong>instances</strong></span></a> de classes et de propriétés sont régulièrement fournis dans les notes d'application à des fins d'explication.</p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p><em></em></p>
</td>
</tr>
<tr>
<td class="en">
<p>instance</p>
<p><em></em></p>
</td>
<td class="en">
<p>An instance of a <strong>class</strong> is a real-world item that fulfils the criteria of the <strong>intension</strong> of the class. Note, that the number of <strong>instances</strong> declared for a class in an information system is typically less than the total in the real world. For example, you are an instance of Person, but you are not mentioned in all information systems describing Persons.</p>
<p>For example:</p>
<p>The painting known as the “The Mona Lisa” is an instance of the class E22 Human-Made Object.</p>
<p>An instance of a <strong>property</strong> is a factual relation between an instance of the <strong>domain</strong> and an instance of the <strong>range</strong> of the property that matches the criteria of the <strong>intension</strong> of the property.</p>
<p>For example:</p>
<p>The Mona Lisa <em>has former or current owner.</em> The Louvre is an instance of the property <em>P51 has former or current owner (is former or current owner of).</em></p>
</td>
<td>
<a name="terminologie-instance"></a><p>Instance</p>
</td>
<td>
<p>L’instance d’une <a href="/v7.1.2/information/introduction#terminologie-classe"><span class="underline">classe</span></a> est un élément du monde réel [n.d.t. voir <a href="/v7.1.2/information/principes-de-modelisation#de-la-realite-des-bases-de-connaissance-et-du-cidoc-crm"><span class="underline">De la réalité, des bases de connaissance et du CIDOC CRM</span></a>] qui correspond à l’<a href="/v7.1.2/information/introduction#terminologie-intension"><span class="underline">intension</span></a> d’une classe [n.d.t. telle qu’elle est exprimée dans sa <a href="/v7.1.2/information/introduction#terminologie-note-dapplication"><span class="underline">note d’application</span></a>]. Le nombre d’instances déclarées pour une classe dans un système d’information est typiquement moins que la totalité [n.d.t. qui existe] dans le monde réel. Par exemple, un individu est une instance de <code class="language-plaintext highlighter-rouge">E21_Personne</code>, mais cet individu n’est pas mentionné dans tous les systèmes d’information décrivant des <code class="language-plaintext highlighter-rouge">E21_Personne</code>. </p>
<p>Par exemple : </p>
<p>La peinture connue sous le nom de « Mona Lisa » est une instance de la classe <code class="language-plaintext highlighter-rouge">E22_Objet_élaboré_par_l'humain</code>. </p>
<p>L’instance d’une propriété est une relation factuelle entre une instance de son domaine et une instance de sa portée, relation qui correspond à l’intension de cette propriété [n.d.t. telle qu’elle est exprimée dans sa note d’application].</p>
<p>Par exemple : </p>
<p>[n.d.t. Dans l’affirmation] « La <em>Mona Lisa</em> a pour propriétaire actuel ou antérieur le Louvre » « a pour propriétaire actuel ou antérieur » est une instance de la propriété <code class="language-plaintext highlighter-rouge">P51_a_pour_propriétaire_actuel_ou_antérieur (est_l'actant_propriétaire_actuel_ou_antérieur_de)</code>. </p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p><em></em></p>
</td>
</tr>
<tr>
<td class="en">
<p>property</p>
<p><em></em></p>
</td>
<td class="en">
<p>A property serves to define a relationship of a specific kind between two <strong>classes.</strong> The property is characterized by an <strong>intension</strong>, which is conveyed by a <strong>scope note.</strong> A property plays a role analogous to a grammatical verb, in that it must be defined with reference to both its <strong>domain</strong> and <strong>range</strong>, which are analogous to the subject and object in grammar (unlike classes, which can be defined independently). It is arbitrary, which class is selected as the domain, just as the choice between active and passive voice in grammar is arbitrary. In other words, a property can be interpreted in both directions, with two distinct, but related interpretations. Properties may themselves have properties that relate to other classes (This feature is used in this model only in order to describe dynamic subtyping of properties). Properties can also be specialized in the same manner as classes, resulting in IsA relationships between <strong>subproperties</strong> and their <strong>superproperties</strong>.</p>
<p>In some contexts, the terms attribute, reference, link, role or slot are used synonymously with property.</p>
<p>For example:</p>
<p>“Physical Human-Made Thing <em>depicts</em><strong> </strong>CRM Entity” is equivalent to “CRM Entity <em>is depicted by</em> Physical Human-Made Thing”.</p>
</td>
<td>
<a name="terminologie-propriete"></a><p>Propriété</p>
</td>
<td>
<p>Une propriété définit une relation spécifique entre deux <a href="/v7.1.2/information/introduction#terminologie-classe"><span class="underline">classes</span></a> et est caractérisée par son <a href="/v7.1.2/information/introduction#terminologie-intension"><span class="underline">intension</span></a> (laquelle est exprimée par la <a href="/v7.1.2/information/introduction#terminologie-note-dapplication"><span class="underline">note d’application </span></a>de la propriété). Une propriété est l’équivalent grammatical d’un verbe dans la mesure où elle est définie par son renvoi à son <a href="/v7.1.2/information/introduction#terminologie-domaine"><span class="underline">domaine</span></a> et à sa <a href="/v7.1.2/information/introduction#terminologie-portee"><span class="underline">portée</span></a>, lesquels sont comparables au sujet et à l’objet d’une phrase [n.d.t. dans le contexte d’une langue SVO, c.-à-d. une langue comme le français dont les phrases suivent généralement l’ordre sujet-verbe-objet], et ce contrairement aux classes qui peuvent être définies de manière indépendante. De même que le choix qu’une forme grammaticale active ou passive est arbitraire, le choix de la classe sélectionnée pour le domaine et pour la portée l’est aussi. En d’autres termes, l’interprétation d’une propriété serait distincte selon le sens dans lequel elle est lue [n.d.t. c.-à-d. depuis le domaine vers la portée ou depuis la portée vers le domaine]. </p>
<p>Certaines propriétés s’appliquent sur d’autres propriétés [n.d.t. et peuvent donc avoir comme portée des instances] d’autres classes, une fonctionnalité qui est mobilisée par le CIDOC CRM afin de décrire le sous-typage dynamique de propriétés [n.d.t. voir <a href="/v7.1.2/information/introduction-aux-concepts-fondamentaux#des-types"><span class="underline">Des types</span></a>; ces propriétés sont signalées par l’usage d’un <code class="language-plaintext highlighter-rouge">.1</code>, par exemple <code class="language-plaintext highlighter-rouge">P14.1_dans_le_rôle_de</code> qui est  associée  à <code class="language-plaintext highlighter-rouge">P14_a_été_effectué_par (a_effectué)</code> et qui a pour objet <code class="language-plaintext highlighter-rouge">E55_Type</code> plutôt que <code class="language-plaintext highlighter-rouge">E21_Personne</code> comme portée]. </p>
<p>Les propriétés peuvent aussi être spécialisées (comme c’est le cas des classes) par des relations <code class="language-plaintext highlighter-rouge">estUn</code> entre des sous-propriétés et leurs super-propriétés. </p>
<p>Dans certains contextes, les termes attribut, référence, lien, rôle ou créneau peuvent être synonymes de propriété. </p>
<p>Par exemple : </p>
<p><code class="language-plaintext highlighter-rouge">E24_Chose_matérielle_élaborée_par_l'humain</code> <code class="language-plaintext highlighter-rouge">P62_illustre</code> <code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code> est l’équivalent de <code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code> <code class="language-plaintext highlighter-rouge">P62i_est_illustré_par</code> <code class="language-plaintext highlighter-rouge">E24_Chose_matérielle_élaborée_par_l'humain</code>.</p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Wikipédia. « Langue SVO ». Dans <em>Wikipédia</em>. San Francisco, US-CA: Wikipédia, 31 octobre 2020.<a href="https://fr.wikipedia.org/w/index.php?title=Langue_SVO&oldid=176099662"><span class="underline"> </span></a><a href="https://fr.wikipedia.org/w/index.php?title=Langue_SVO&oldid=176099662"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Langue_SVO&oldid=176099662</span></a>.</p>
</td>
</tr>
<tr>
<td class="en">
<p>inverse of</p>
<p><em></em></p>
</td>
<td class="en">
<p>The inverse of a property is the reinterpretation of a <strong>property</strong> from <strong>range</strong> to <strong>domain</strong> without more general or more specific meaning, similar to the choice between active and passive voice in some languages. In contrast to some knowledge representation languages, such as RDF and OWL, we regard that the inverse of a property is not a property in its own right that needs an explicit declaration of being inverse of another, but an interpretation implicitly existing for any property. The inverse of the inverse of a property is identical to the property itself, i.e., its primary sense of direction.</p>
<p>For example:</p>
<p>“CRM Entity <em>is depicted by</em> Physical Human-Made Thing” is the inverse of “Physical Human-Made Thing <em>depicts</em><strong> </strong>CRM Entity” </p>
</td>
<td>
<a name="terminologie-inverse-de"></a><p>Inverse de</p>
</td>
<td>
<p>L’inverse d’une <a href="/v7.1.2/information/introduction#terminologie-propriete"><span class="underline">propriété</span></a> est la réinterprétation de cette propriété depuis sa <a href="/v7.1.2/information/introduction#terminologie-portee"><span class="underline">portée</span></a> vers son <a href="/v7.1.2/information/introduction#terminologie-domaine"><span class="underline">domaine</span></a> sans généralisation ou spécialisation de sa signification supplémentaire. De même que le choix d’une forme grammaticale active ou passive est arbitraire [n.d.t. le choix de la classe sélectionnée pour le domaine et pour la portée l’est aussi]. Contrairement à certains langages de représentation tels que <a href="https://www.w3.org/RDF/"><span class="underline">RDF</span></a> et OWL, le CIDOC CRM considère que l’inverse d’une propriété n’est pas une propriété en soi qui nécessiterait la déclaration explicite du fait qu’elle en inverse une autre; il s’agit plutôt d’une interprétation implicite à chaque propriété. L’inverse de l’inverse d’une propriété est identique à la propriété elle-même, à savoir identique à sa direction primaire. </p>
<p>Par exemple : </p>
<p><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code> <code class="language-plaintext highlighter-rouge">P62.i_est_illustré_par</code> <code class="language-plaintext highlighter-rouge">E24_Chose_matérielle_élaborée_par_l'humain</code> est l’inverse de <code class="language-plaintext highlighter-rouge">E24_Chose_matérielle_élaborée_par_l'humain</code> <code class="language-plaintext highlighter-rouge">P62_illustre</code> <code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code>.</p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p><em></em></p>
</td>
</tr>
<tr>
<td class="en">
<p>subproperty</p>
<p><em></em></p>
</td>
<td class="en">
<p>A subproperty is a <strong>property</strong> that is a specialization of another property (its <strong>superproperty</strong>). Specialization or IsA relationship means that: </p>
<ul><li><p>all <strong>instances</strong> of the subproperty are also instances of its superproperty, </p>
</li>
<li><p>the <strong>intension</strong> of the subproperty extends the intension of the superproperty, i.e., its traits are more restrictive than that of its superproperty, </p>
</li>
<li><p>the <strong>domain </strong>of the subproperty is the same as the domain of its superproperty or a <strong>subclass</strong> of that domain,</p>
</li>
<li><p>the <strong>range </strong>of the subproperty is the same as the range of its superproperty or a subclass of that range,</p>
</li>
<li><p>the subproperty inherits the definition of all of the properties declared for its superproperty without exceptions (<strong>strict inheritance</strong>), in addition to having none, one or more properties of its own.</p>
</li></ul>
<p>A subproperty can have more than one immediate superproperty and consequently inherits the properties of all of its superproperties (<strong>multiple inheritance</strong>). The IsA relationship or specialization between two or more properties gives rise to the structure we call a property hierarchy. The IsA relationship is transitive and may not be cyclic. </p>
<p>Some object-oriented programming languages, such as C++, do not contain constructs that allow for the expression of the specialization of properties as sub-properties.</p>
<p>Alternatively, a property may be subproperty of the <strong>inverse of</strong> another property, i.e., reading the property from range to domain. In that case:</p>
<ul><li><p>all instances of the subproperty are also instances of the inverse of the other property, </p>
</li>
<li><p>the intension of the subproperty extends the intension of the inverse of the other property, i.e., its traits are more restrictive than that of the inverse of the other property, </p>
</li>
<li><p>the domain<strong> </strong>of the subproperty is the same as the range of the other property or a subclass of that range,</p>
</li>
<li><p>the range of the subproperty is the same as the domain of the other property or a subclass of that domain,</p>
</li>
<li><p>the subproperty inherits the definition of all of the properties declared for the other property without exceptions (strict inheritance), in addition to having none, one or more properties of its own. The definitions of inherited properties have to be interpreted in the inverse sense of direction of the subproperty, i.e., from range to domain.</p>
</li></ul>
</td>
<td>
<a name="terminologie-sous-propriete"></a><p>Sous-propriété</p>
</td>
<td>
<p>Une sous-propriété est une <a href="/v7.1.2/information/introduction#terminologie-propriete"><span class="underline">propriété</span></a> spécialisant une autre propriété (sa <a href="/v7.1.2/information/introduction#terminologie-super-propriete"><span class="underline">super-propriété</span></a>); une spécialisation (ou relation <code class="language-plaintext highlighter-rouge">estUn</code>) implique que : </p>
<ul><li><p>toutes les <a href="/v7.1.2/information/introduction#terminologie-instance"><span class="underline"><strong>instances</strong></span></a> d’une sous-propriété sont aussi des instances de sa super-propriété; </p>
</li>
<li><p>l’<a href="/v7.1.2/information/introduction#terminologie-intension"><span class="underline"><strong>intension</strong></span></a> d’une sous-propriété extensionne l’intension de sa super-propriété, c.-à-d. que les traits [n.d.t. décrits dans la <a href="/v7.1.2/information/introduction#terminologie-note-dapplication"><span class="underline">note d’application</span></a> de la sous-propriété] sont plus restrictifs que ceux de sa super-propriété; </p>
</li>
<li><p>le <a href="/v7.1.2/information/introduction#terminologie-domaine"><span class="underline"><strong>domaine</strong></span></a> de la sous-propriété est le même que le domaine de sa super-propriété ou d’une <a href="/v7.1.2/information/introduction#terminologie-sous-classe"><span class="underline">sous-classe</span></a> de ce domaine;</p>
</li>
<li><p>la <a href="/v7.1.2/information/introduction#terminologie-portee"><span class="underline"><strong>portée</strong></span></a> de la sous-propriété est la même que la portée de sa super-propriété ou d’une sous-classe de cette portée; </p>
</li>
<li><p>la sous-propriété <a href="/v7.1.2/information/introduction#terminologie-heritage"><span class="underline">hérite</span></a> la définition de toutes les propriétés déclarées pour sa super-propriété, et ce sans exception (<a href="/v7.1.2/information/introduction#terminologie-heritage-strict"><span class="underline">héritage strict</span></a>) en plus de n’avoir aucune, une seule ou plusieurs propriétés qui lui est/sont propre(s).</p>
</li></ul>
<p>Une sous-propriété peut relever directement de plus d’une super-propriété et ainsi hériter les propriétés de toutes ces super-propriétés (<a href="/v7.1.2/information/introduction#terminologie-heritage-multiple"><span class="underline">héritage multiple</span></a>). La relation <code class="language-plaintext highlighter-rouge">estUn</code> (spécialisation) entre deux propriétés ou plus établit une hiérarchie des propriétés; c’est une relation <a href="/v7.1.2/information/introduction#terminologie-transitivite"><span class="underline">transitive</span></a> qui peut ne pas être cyclique. Certains langages de programmation comme C++ n’ont pas de construits qui expriment la spécialisation de propriétés en sous-propriétés. </p>
<p>Une propriété peut aussi être une sous-propriété de l’<a href="/v7.1.2/information/introduction#terminologie-inverse-de"><span class="underline">inverse</span></a> d’une autre propriété [n.d.t. (la propriété initiale non-inversée)], c.-à-d. que lire la propriété depuis la portée vers le domaine implique que : </p>
<ul><li><p>toutes les instances d’une sous-propriété sont aussi des instances de l’inverse de l’autre propriété; </p>
</li>
<li><p>l’intension d’une sous-propriété extensionne l’intension de l’inverse de l’autre propriété, c.-à-d. que les traits [n.d.t. décrits dans la note d’application de la sous-propriété] sont plus restrictifs que ceux de l’inverse de l’autre propriété;</p>
</li>
<li><p>le domaine de la sous-propriété est le même que la portée de l’autre propriété ou d’une sous-classe de cette portée;</p>
</li>
<li><p>la portée de la sous-propriété est la même que le domaine de l'autre propriété ou une sous-classe de ce domaine </p>
</li>
<li><p>la sous-propriété hérite la définition de toutes les propriétés déclarées pour l’autre propriété, et ce sans exception (héritage strict) en plus de n’avoir aucune, une seule ou plusieurs propriétés qui lui est/sont propre(s). Les définitions des propriétés héritées doivent être interprétées dans le sens inverse de la direction de la sous-propriété, à savoir depuis la portée vers le domaine. </p>
</li></ul>
<p>[n.d.t. voir <a href="/v7.1.2/proprietes/declaration-des-proprietes-du-cidoc-crm"><span class="underline">Déclaration des propriétés du CIDOC CRM</span></a>].</p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
<p>Le terme « construct » n’a pas d’équivalent français parfait, mais une recherche sommaire révèle que le terme « construit » (n.m.) semble répandu dans les domaines de la philosophie et de la sociologie et est celui dont le sens se rapproche le plus de la forme originale. </p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Termium. « construct ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=construct&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=construct&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=construct&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
</td>
</tr>
<tr>
<td class="en">
<p>superproperty</p>
<p><em></em></p>
</td>
<td class="en">
<p>A superproperty is a <strong>property</strong> that is a generalization of one or more other properties (its <strong>subproperties</strong>), which means that it subsumes all <strong>instances</strong> of its subproperties, and that it can also have additional instances that do not belong to any of its subproperties. The <strong>intension</strong> of the superproperty is less restrictive than any of its subproperties. The subsumption relationship or generalization is the inverse of the IsA relationship or specialization. A superproperty may be a generalization of the <strong>inverse of </strong>another property.</p>
</td>
<td>
<a name="terminologie-super-propriete"></a><p>Super-propriété</p>
</td>
<td>
<p>Une super-propriété est une <a href="/v7.1.2/information/introduction#terminologie-propriete"><span class="underline"><strong>propriété</strong></span></a> qui est une généralisation de l’une ou plusieurs autres propriétés (ses <a href="/v7.1.2/information/introduction#terminologie-sous-propriete"><span class="underline"><strong>sous-propriétés</strong></span></a>) : elle subsume toutes les <a href="/v7.1.2/information/introduction#terminologie-instance"><span class="underline"><strong>instances</strong></span></a> de toutes ses sous-propriétés et peut de surcroît avoir des instances qui ne relèvent d'aucune de ces sous-propriétés. L’<a href="/v7.1.2/information/introduction#terminologie-intension"><span class="underline"><strong>intension</strong></span></a> d’une super-propriété est moins restrictive que celle de n’importe laquelle de ses sous-propriétés. La relation de subsomption (généralisation) est l’inverse d’une relation <code class="language-plaintext highlighter-rouge">estUn</code> (spécialisation). Une super-propriété peut être une généralisation de l’<a href="/v7.1.2/information/introduction#terminologie-inverse-de"><span class="underline"><strong>inverse</strong></span></a> d’une autre propriété. </p>
<p>[n.d.t. voir <a href="/v7.1.2/proprietes/declaration-des-proprietes-du-cidoc-crm"><span class="underline">Déclaration des propriétés du CIDOC CRM</span></a>].</p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p><em></em></p>
</td>
</tr>
<tr>
<td class="en">
<p>domain</p>
<p><em></em></p>
</td>
<td class="en">
<p>The domain is the <strong>class</strong> for which a <strong>property</strong> is formally defined. This means that <strong>instances</strong> of the property are applicable to instances of its domain class. A property must have exactly one domain, although the domain class may always contain instances for which the property is not instantiated. The domain class is analogous to the grammatical subject of the phrase for which the property is analogous to the verb. It is arbitrary which class is selected as the domain and which as the <strong>range</strong>, just as the choice between active and passive voice in grammar is arbitrary. Property names in the CIDOC CRM are designed to be semantically meaningful and grammatically correct when read from domain to range<strong>. </strong>In addition, the inverse property name, normally given in parentheses, is also designed to be semantically meaningful and grammatically correct when read from range to domain.</p>
</td>
<td>
<a name="terminologie-domaine"></a><p>Domaine</p>
</td>
<td>
<p>Le domaine est la <a href="/v7.1.2/information/introduction#terminologie-classe"><span class="underline"><strong>classe</strong></span></a> pour laquelle une <a href="/v7.1.2/information/introduction#terminologie-propriete"><span class="underline"><strong>propriété</strong></span></a> est formellement définie, de sorte que les <a href="/v7.1.2/information/introduction#terminologie-instance"><span class="underline"><strong>instances</strong></span></a> d’une propriété ne peuvent s’appliquer qu’aux instances de sa classe de domaine. Une propriété doit avoir exactement un domaine, bien que la classe de domaine puisse contenir des instances pour lesquelles la propriété n’est pas instanciée. La classe de domaine est l’équivalent du sujet grammatical d’une phrase dont la propriété serait le verbe [n.d.t. dans le contexte d’une langue SVO, c.-à-d. une langue comme le français dont les phrases suivent généralement l’ordre sujet-verbe-objet]. Le choix de la classe sélectionnée pour le domaine et pour la <a href="/v7.1.2/information/introduction#terminologie-portee"><span class="underline"><strong>portée</strong></span></a> est aussi arbitraire que celui d’une forme grammaticale active ou passive. Les propriétés du CIDOC CRM sont ainsi nommées de manière à être grammaticalement correctes [n.d.t. en anglais] lors d’une lecture depuis le domaine vers la portée [n.d.t. dans le cadre de cette traduction, les propriétés sont grammaticalement correctes, mais toujours accordées au féminin dans le cadre de la phrase où elles sont citées puisqu’il est fait référence à la propriété elle-même (terme féminin) plutôt qu’à sa dénomination, le sujet grammatical des propriétés est pour sa part masculin]. De plus, les propriétés inverses, dont le nom se trouve normalement entre parenthèses, sont elles aussi nommées de manière à être grammaticalement correctes [n.d.t. en anglais] lors d’une lecture depuis la portée vers le domaine.</p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Wikipédia. « Langue SVO ». Dans <em>Wikipédia</em>. San Francisco, US-CA: Wikipédia, 31 octobre 2020.<a href="https://fr.wikipedia.org/w/index.php?title=Langue_SVO&oldid=176099662"><span class="underline"> </span></a><a href="https://fr.wikipedia.org/w/index.php?title=Langue_SVO&oldid=176099662"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Langue_SVO&oldid=176099662</span></a>.</p>
</td>
</tr>
<tr>
<td class="en">
<p>range</p>
<p><em></em></p>
</td>
<td class="en">
<p>The range is the <strong>class</strong> that comprises all potential values of a <strong>property.</strong> That means that <strong>instances</strong> of the property can link only to instances of its range class. A property must have exactly one range, although the range class may always contain instances that are not the value of the property. The range class is analogous to the grammatical object of a phrase for which the property is analogous to the verb. It is arbitrary which class is selected as <strong>domain</strong> and which as range, just as the choice between active and passive voice in grammar is arbitrary. Property names in the CIDOC CRM are designed to be semantically meaningful and grammatically correct when read from domain to range<strong>. </strong>In addition, the inverse property name, normally given in parentheses, is also designed to be semantically meaningful and grammatically correct when read from range to domain.</p>
</td>
<td>
<a name="terminologie-portee"></a><p>Portée</p>
</td>
<td>
<p>La portée est la <a href="/v7.1.2/information/introduction#terminologie-classe"><span class="underline"><strong>classe</strong></span></a> qui englobe toutes les valeurs potentielles d’une <a href="/v7.1.2/information/introduction#terminologie-propriete"><span class="underline"><strong>propriété</strong></span></a>, de sorte que les <a href="/v7.1.2/information/introduction#terminologie-instance"><span class="underline"><strong>instances</strong></span></a> d’une propriété peuvent se lier uniquement aux instances de sa classe de portée. Une propriété doit avoir exactement une portée, bien que la classe de portée puisse contenir des instances qui ne sont pas des valeurs de la propriété. La classe de portée est l’équivalent de l’objet grammatical d’une phrase dont la propriété serait le verbe [n.d.t. dans le contexte d’une langue SVO, c.-à-d. une langue comme le français dont les phrases suivent généralement l’ordre sujet-verbe-objet]. Le choix de la classe sélectionnée pour le <a href="/v7.1.2/information/introduction#terminologie-domaine"><span class="underline"><strong>domaine</strong></span></a> et pour la portée est aussi arbitraire que celui d’une forme grammaticale active ou passive. Les propriétés du CIDOC CRM sont ainsi nommées de manière à être grammaticalement correctes [n.d.t. en anglais] lors d’une lecture depuis le domaine vers la portée [n.d.t. dans le cadre de cette traduction, les propriétés sont grammaticalement correctes, mais toujours accordées au féminin dans le cadre de la phrase où elles sont citées, le sujet grammatical des propriétés est pour sa part masculin]. De plus, les propriétés inverses, dont le nom se trouve normalement entre parenthèses, sont elles aussi nommées de manière à être grammaticalement correcte [n.d.t. en anglais] lors d’une lecture depuis la portée vers le domaine.</p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Wikipédia. « Langue SVO ». Dans <em>Wikipédia</em>. San Francisco, US-CA: Wikipédia, 31 octobre 2020.<a href="https://fr.wikipedia.org/w/index.php?title=Langue_SVO&oldid=176099662"><span class="underline"> </span></a><a href="https://fr.wikipedia.org/w/index.php?title=Langue_SVO&oldid=176099662"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Langue_SVO&oldid=176099662</span></a>.</p>
</td>
</tr>
<tr>
<td class="en">
<p>inheritance</p>
<p><em></em></p>
</td>
<td class="en">
<p>Inheritance of <strong>properties</strong> from <strong>superclasses</strong> to <strong>subclasses</strong> means that if an item x is an <strong>instance</strong> of a <strong>class</strong> A, then:</p>
<ul><li><p>all properties that must hold for the instances of any of the superclasses of A must also hold for item x, and</p>
</li>
<li><p>all optional properties that may hold for the instances of any of the superclasses of A may also hold for item x.</p>
</li></ul>
</td>
<td>
<a name="terminologie-heritage"></a><p>Héritage</p>
</td>
<td>
<p>L’héritage des <a href="/v7.1.2/information/introduction#terminologie-propriete"><span class="underline"><strong>propriétés</strong></span></a> de <a href="/v7.1.2/information/introduction#terminologie-super-classe"><span class="underline"><strong>super-classes</strong></span></a> vers leurs <a href="/v7.1.2/information/introduction#terminologie-sous-classe"><span class="underline"><strong>sous-classes</strong></span></a> implique que pour tout élément <code class="language-plaintext highlighter-rouge">x</code> étant une <a href="/v7.1.2/information/introduction#terminologie-instance"><span class="underline"><strong>instance</strong></span></a> d’une <a href="/v7.1.2/information/introduction#terminologie-classe"><span class="underline"><strong>classe</strong></span></a> <code class="language-plaintext highlighter-rouge">A</code> :</p>
<ul><li><p>toutes les propriétés qui doivent être appliquées à des instances relevant de super-classes de <code class="language-plaintext highlighter-rouge">A</code> doivent aussi s’appliquer à l’élément <code class="language-plaintext highlighter-rouge">x</code> et que</p>
</li>
<li><p>toutes les propriétés optionnelles qui peuvent être appliquées à des instances relevant de super-classes de <code class="language-plaintext highlighter-rouge">A</code> peuvent aussi s’appliquer à l’élément <code class="language-plaintext highlighter-rouge">x</code>. </p>
</li></ul>
<p>[n.d.t. voir <a href="/v7.1.2/information/introduction#de-lheritage-et-de-la-transitivite"><span class="underline">De l’héritage et de la transitivité</span></a> dans la section <a href="/v7.1.2/information/principes-de-modelisation"><span class="underline">Principes de modélisation</span></a>]. </p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p><em></em></p>
</td>
</tr>
<tr>
<td class="en">
<p>strict inheritance<em></em></p>
</td>
<td class="en">
<p>Strict <strong>inheritance</strong> means that there are no exceptions to the inheritance of <strong>properties</strong> from <strong>superclasses</strong> to <strong>subclasses</strong>. For instance, some systems may declare that elephants are grey, and regard a white elephant as an exception. Under strict inheritance it would hold that: if all elephants were grey, then a white elephant could not be an elephant. Obviously not all elephants are grey. To be grey is not part of the <strong>intension</strong> of the concept elephant but an optional property. The CIDOC CRM applies strict inheritance as a normalization principle.</p>
</td>
<td>
<a name="terminologie-heritage-strict"></a><p>Héritage strict</p>
</td>
<td>
<p>L’<a href="/v7.1.2/information/introduction#terminologie-heritage"><span class="underline"><strong>héritage</strong></span></a> strict désigne le fait qu’il n’y a pas d’exception à l’héritage de <a href="/v7.1.2/information/introduction#terminologie-propriete"><span class="underline">propriétés</span></a> depuis des <a href="/v7.1.2/information/introduction#terminologie-super-classe"><span class="underline">super-classes</span></a> vers leurs <a href="/v7.1.2/information/introduction#terminologie-sous-classe"><span class="underline">sous-classes</span></a>. Par exemple, un système [n.d.t. d’information] peut déclarer que les éléphants sont gris et considérer qu’un éléphant blanc est une exception [n.d.t. à la classe éléphant]. Des règles d’héritage strict imposeraient que si tous les éléphants sont gris, un éléphant blanc ne peut être un éléphant. Évidemment, tous les éléphants ne sont pas gris et le fait d’être gris ne fait pas partie de l’<a href="/v7.1.2/information/introduction#terminologie-intension"><span class="underline">intension</span></a> du concept « éléphant » (il s’agit plutôt d’une propriété optionnelle). Le CIDOC CRM applique des règles d’héritage strict à des fins de normalisation. </p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
<p>Le terme « normalization » aurait aussi pu être traduit par « standardisation”, mais puisqu’il s’agit du principe et non pas de l’application d’un standard établi, le terme « normalisation » a été utilisé. </p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Termium. « normalization ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=normalization&index=alt&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=normalization&index=alt&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=normalization&index=alt&codom2nd_wet=1#resultrecs</span></a>.</p>
</td>
</tr>
<tr>
<td class="en">
<p>multiple inheritance</p>
<p><em></em></p>
</td>
<td class="en">
<p>Multiple <strong>inheritance</strong> means that a <strong>class</strong> A may have more than one immediate <strong>superclass</strong>. The <strong>extension</strong> of a class with multiple immediate superclasses is a subset of the intersection of all extensions of its superclasses. The <strong>intension</strong> of a class with multiple immediate superclasses extends the intensions of all its superclasses, i.e., its traits are more restrictive than any of its superclasses. If multiple inheritance is used, the resulting “class hierarchy” is a directed graph and not a tree structure. If it is represented as an indented list, there are necessarily repetitions of the same class at different positions in the list.</p>
<p>For example:</p>
<p>Person is both an Actor and a Biological Object.</p>
</td>
<td>
<a name="terminologie-heritage-multiple"></a><p>Héritage multiple</p>
</td>
<td>
<p>L’<a href="/v7.1.2/information/introduction#terminologie-heritage"><span class="underline"><strong>héritage</strong></span></a> multiple désigne le fait qu’une <a href="/v7.1.2/information/introduction#terminologie-instance"><span class="underline">instance</span></a> d’une <a href="/v7.1.2/information/introduction#terminologie-classe"><span class="underline"><strong>classe</strong></span></a> <code class="language-plaintext highlighter-rouge">A</code> puisse relever directement de plus d’une <a href="/v7.1.2/information/introduction#terminologie-super-classe"><span class="underline"><strong>super-classe</strong></span></a><a href="/v7.1.2/information/introduction#terminologie-super-classe"><span class="underline">.</span></a> L’<a href="/v7.1.2/information/introduction#terminologie-extension"><span class="underline"><strong>extension</strong></span></a> d’une classe relevant directement de plusieurs super-classes est un sous-ensemble de l’intersection de toutes les extensions de ses super-classes. L’<a href="/v7.1.2/information/introduction#terminologie-intension"><span class="underline"><strong>intension</strong></span></a> d’une classe relevant directement de plusieurs super-classes étend les intensions de toutes ces super-classes (c.-à-d. que les traits [n.d.t. de cette classe tels qu’ils sont définis par sa <a href="/v7.1.2/information/introduction#terminologie-note-dapplication"><span class="underline">note d’application</span></a>] sont plus restrictifs que ceux de n’importe laquelle de ses super-classes). La « hiérarchie des classes » résultant d’un héritage multiple prend la forme d’un graphe orienté et non pas d’une arborescence. Si la hiérarchie en question est représentée sous la forme d’une liste comportant des retraits, il y aura nécessairement de multiples occurrences d’une même classe à différents endroits de la liste. Par exemple, <code class="language-plaintext highlighter-rouge">E21_Personne</code> est à la fois <code class="language-plaintext highlighter-rouge">E39_Actant</code> et <code class="language-plaintext highlighter-rouge">E20_Objet_biologique</code>. </p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Termium. « directed graph ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=directed+graph&index=alt&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=directed+graph&index=alt&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=directed+graph&index=alt&codom2nd_wet=1#resultrecs</span></a>.</p>
</td>
</tr>
<tr>
<td class="en">
<p>multiple instantiation</p>
<p><em></em></p>
</td>
<td class="en">
<p>Multiple <strong>Instantiation</strong> is the term that describes the case that an instance of class A is also regarded as an instance of one or more other classes B1...n at the same time. When multiple instantiation is used, it has the effect that the properties of all these classes become available to describe this instance. For instance, some particular cases of destruction may also be activities (e.g., Herostratos’ deed), but not all destructions are activities (e.g., destruction of Herculaneum). In comparison, multiple inheritance describes the case that all instances of a class A are implicitly instances of all superclasses of A, by virtue of the definition of the class A, whereas the combination of classes used for multiple instantiation is a characteristic of particular instances only. It is important to note that multiple instantiation is not allowed using combinations of disjoint classes.</p>
</td>
<td>
<a name="terminologie-instanciation-multiple"></a><p>Instanciation multiple</p>
</td>
<td>
<p>L’<strong>instanciation </strong>multiple désigne le fait qu’une <a href="/v7.1.2/information/introduction#terminologie-instance"><span class="underline">instance</span></a> d’une <a href="/v7.1.2/information/introduction#terminologie-classe"><span class="underline">classe</span></a> <code class="language-plaintext highlighter-rouge">A</code> soit aussi et simultanément une instance de l’une ou plusieurs autres classes <code class="language-plaintext highlighter-rouge">B1...n</code>. Les <a href="/v7.1.2/information/introduction#terminologie-propriete"><span class="underline">propriétés</span></a> de toutes ces classes deviennent alors utilisables dans la description de cette instance. Par exemple, certaines destructions (<code class="language-plaintext highlighter-rouge">E6_Destruction</code>) sont aussi des activités (<code class="language-plaintext highlighter-rouge">E7_Activité</code>) comme c’est le cas de l’acte d’Érostrate [n.d.t. qui a incendié le temple d’Artémis à Éphèse], mais ce ne sont pas toutes les destructions (<code class="language-plaintext highlighter-rouge">E6_Destruction</code>) qui sont des activités (<code class="language-plaintext highlighter-rouge">E7_Activité</code>). L’<a href="/v7.1.2/information/introduction#terminologie-heritage-multiple"><span class="underline">héritage multiple</span></a>, quant à lui, désigne le fait que toutes les instances d’une classe <code class="language-plaintext highlighter-rouge">A</code> sont implicitement des instances de toutes les <a href="/v7.1.2/information/introduction#terminologie-super-classe"><span class="underline">super-classes</span></a> de <code class="language-plaintext highlighter-rouge">A</code> (du fait de la définition de cette classe) alors que la combinaison des classes utilisée lors d’une instanciation multiple est caractéristique des instances mobilisées seulement. L’instanciation multiple ne peut mobiliser une combinaison de classes <a href="/v7.1.2/information/introduction#terminologie-disjointe"><span class="underline">disjointes</span></a>. </p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p><em></em></p>
</td>
</tr>
<tr>
<td class="en">
<p>endurant, perdurant</p>
<p><em></em></p>
</td>
<td class="en">
<p>“The difference between enduring and perduring entities (which we shall also call <em>endurants </em>and <em>perdurants</em>) is related to their behaviour in time. Endurants are wholly present (i.e., all their proper parts are present) at any time they are present. Perdurants, on the other hand, just extend in time by accumulating different temporal parts, so that, at any time they are present, they are only partially present, in the sense that some of their proper temporal parts (e.g., their previous or future phases) may be not present. E.g., the piece of paper you are reading now is wholly present, while some temporal parts of your reading are not present any more. Philosophers say that endurants are entities that are in time, while lacking however temporal parts (so to speak, all their parts flow with them in time). Perdurants, on the other hand, are entities that happen in time, and can have temporal parts (all their parts are fixed in time).” (Gangemi et al. 2002, pp. 166-181).</p>
</td>
<td>
<a name="terminologie-endurant-perdurant"></a><p>Endurant, Perdurant</p>
</td>
<td>
<p>« La différence entre des entités endurantes et perdurantes (des endurants et des perdurants) repose sur leur fonctionnement dans le temps : les endurants sont présents dans leur entièreté (c.-à-d. qu’ils comprennent toutes leurs parties constituantes) peu importe le moment auquel ils sont présents. Les perdurants, quant à eux, se construisent dans le temps par l’accumulation d’éléments, de telle sorte qu’ils ne sont toujours que partiellement présents dans la mesure où certains de leurs éléments temporellement déterminés (p. ex. leurs incarnations passées ou futures) peuvent ne pas être présents. Par exemple, une feuille de papier [n.d.t. dont le contenu fait l’objet d’une lecture] est pleinement présente, bien que certains éléments de la lecture ne le soient plus. Les philosophes considèrent les endurants comme des entités situées dans le temps, mais qui n’ont pas de parties temporelles,<em> </em>car celles-ci évoluent dans le temps avec eux. Au contraire, les perdurants sont des entités qui s’incarnent dans le temps et qui peuvent avoir des parties temporelles, car celles-ci sont toutes fixées temporellement » (Gangemi et al. 2002, pp. 166-181).</p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
<p>Le terme « behaviour » a été traduit par « fonctionnement » plutôt que par « comportement » puisqu’il s’agit d’une chose et non pas d’une personne.  </p>
<p>Le terme « phase » a été traduit par « incarnation » plutôt que par « phase » puisqu’il s’agit de l’état d’une chose à un moment précis de son évolution et non pas du changement lui-même.   </p>
<p>Le terme « flow » a été traduit par « évoluer » afin d’illustrer la nature fluctuante du concept. </p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p><em></em></p>
</td>
</tr>
<tr>
<td class="en">
<p>shortcut</p>
<p><em></em></p>
</td>
<td class="en">
<p>A shortcut is a formally defined single <strong>property</strong> that represents a deduction or join of a data path in the CIDOC CRM. The <strong>scope notes</strong> of all properties characterized as shortcuts describe in words the equivalent deduction. Shortcuts are introduced for the cases where common documentation practice refers only to the deduction rather than to the fully developed path. For example, museums often only record the dimension of an object without documenting the Measurement that observed it. The CIDOC CRM declares shortcuts explicitly as single properties in order to allow the user to describe cases in which he has less detailed knowledge than the full data path would need to be described. For each shortcut, the CIDOC CRM contains in its schema the properties of the full data path explaining the shortcut.</p>
</td>
<td>
<a name="terminologie-raccourci"></a><p>Raccourci</p>
</td>
<td>
<p>Un raccourci est une <strong>propriété</strong> singulière formellement définie qui représente un chemin sémantique (obtenu par déduction ou par union) dans le CIDOC CRM. Les <a href="/v7.1.2/information/introduction#terminologie-note-dapplication"><span class="underline"><strong>notes d’application</strong></span></a><a href="/v7.1.2/information/introduction#terminologie-note-dapplication"><span class="underline"> </span></a>de toutes les propriétés caractérisées de raccourcis décrivent verbalement les déductions ou unions concernées. Les raccourcis sont utilisés lorsque la pratique documentaire réfère uniquement au résultat déduit plutôt qu’au chemin sémantique complet. Par exemple, les institutions muséales ne recensent souvent que les dimensions d’un objet sans pour autant documenter le <code class="language-plaintext highlighter-rouge">E16_Mesurage</code> qui les sous-tend. Le CIDOC CRM déclare explicitement des propriétés singulières à titre de raccourcis afin de permettre aux utilisateurs de décrire des cas dont ce ne sont pas toutes les connaissances associées au chemin sémantique complet qui sont recensées. Chaque raccourci du CIDOC CRM contient dans ses schémas les propriétés du chemin sémantique complet qui l’explique. </p>
<p>[n.d.t. voir <a href="/v7.1.2/information/introduction#des-raccourcis"><span class="underline">Des raccourcis</span></a> dans les <a href="/v7.1.2/information/principes-de-modelisation"><span class="underline">Principes de modélisation</span></a>].</p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
<p>Le terme « join of a data » a été traduit par « union » plutôt que par « fusion », car il s’agit de les réunir sans en annihiler l’une ou l’autre. </p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Termium. « join ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=join&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=join&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=join&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
</td>
</tr>
<tr>
<td class="en">
<p>monotonic reasoning</p>
<p><em></em></p>
</td>
<td class="en">
<p>Monotonic reasoning is a term from knowledge representation. A reasoning form is monotonic if an addition to the set of propositions making up the knowledge base never determines a decrement in the set of conclusions that may be derived from the knowledge base via inference rules. In practical terms, if experts enter subsequently correct statements to an information system, the system should not regard any results from those statements as invalid, when a new one is entered. The CIDOC CRM is designed for monotonic reasoning and so enables conflict-free merging of huge stores of knowledge.</p>
</td>
<td>
<a name="terminologie-raisonnement-monotone"></a><p>Raisonnement monotone</p>
</td>
<td>
<p>Le raisonnement monotone (un terme issu du domaine de la représentation des connaissances) stipule qu’une forme est monotone si une addition à l’ensemble de propositions qui forme la base de connaissances ne détermine jamais de décrément de l’ensemble des conclusions qui peuvent être dérivées (par des règles d’inférence) d’une base de connaissance. [n.d.t. Un décrément est une quantité constante prédéterminée dont on soustrait la valeur d’une variable.] En pratique, si des experts intègrent à un système d’information des énoncés corrects, ce système ne devrait considérer aucun de ces énoncés invalides lorsqu’un nouvel énoncé est ajouté. C’est ainsi qu’est conçu le CIDOC CRM, de sorte qu’il assure une fusion d’importants ensembles de connaissances sans conflits. </p>
<p>[n.d.t. voir la section sur la <a href="/v7.1.2/information/principes-de-modelisation#de-la-monotonicite"><span class="underline">Monotonicité</span></a> dans les <a href="/v7.1.2/information/principes-de-modelisation"><span class="underline">Principes de modélisation</span></a>].</p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
<p>Ajout d’une définition du décrément selon sa définition logicielle (quantité constante prédéterminée dont on soustrait la valeur d’une variable) plutôt que mathématique (diminution de la valeur d’une quantité variable). </p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Wikipédia. « Monotonie ». Dans <em>Wikipédia</em>. San Francisco, US-CA: Wikipédia, 19 février 2017.<a href="https://fr.wikipedia.org/w/index.php?title=Monotonie&oldid=134697868"><span class="underline"> </span></a><a href="https://fr.wikipedia.org/w/index.php?title=Monotonie&oldid=134697868"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Monotonie&oldid=134697868</span></a>.</p>
</td>
</tr>
<tr>
<td class="en">
<p>disjoint</p>
<p><em></em></p>
</td>
<td class="en">
<p><strong>Classes</strong> are disjoint if the intersection of their <strong>extensions</strong> is an empty set. In other words, they have no common <strong>instances</strong> in any possible world.</p>
</td>
<td>
<a name="terminologie-disjointe"></a><p>Disjoint•e</p>
</td>
<td>
<p>Des classes sont disjointes si l’intersection de leurs extensions est un ensemble vide; en d’autres termes, il n’y a pas de possibilité qu’elles aient des instances communes. </p>
<p>[n.d.t. voir la section <a href="/v7.1.2/information/principes-de-modelisation#de-la-disjonction"><span class="underline">De la disjonction</span></a> dans les <a href="/v7.1.2/information/principes-de-modelisation"><span class="underline">Principes de modélisation</span></a>]. </p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p><em></em></p>
</td>
</tr>
<tr>
<td class="en">
<p>primitive</p>
<p><em></em></p>
</td>
<td class="en">
<p>The term primitive as used in knowledge representation characterizes a concept that is declared and its meaning is agreed upon, but that is not defined by a logical deduction from other concepts. For example, mother may be described as a female human with child. Then mother is not a primitive concept. Event however is a primitive concept. </p>
<p>Most of the CIDOC CRM is made up of primitive concepts.</p>
</td>
<td>
<a name="terminologie-primitive"></a><p>Primitive</p>
</td>
<td>
<p>Une primitive (utilisée dans le cadre de la représentation de connaissances) est un concept qui est déclaré et dont la signification est acceptée, mais qui ne peut être définie par une déduction logique reposant sur d’autres concepts. Par exemple, « mère » est un concept qui peut être décrit comme « femme qui a un enfant”, de sorte qu’il n’est pas primitif [n.d.t. car il peut être déduit des concepts femme et enfant], alors que <code class="language-plaintext highlighter-rouge">E5_Évènement</code> est un concept primitif (ainsi que la plupart des concepts du CIDOC CRM). </p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
<p>« Female » est un terme qui est couramment utilisé en anglais sans être considéré péjoratif. Cependant, en français, l’utilisation du terme « femelle » pour désigner des humains du sexe féminin est généralement considérée condescendante. Le terme « femme » a donc été utilisé. </p>
<p>Techniquement, « being with child » indique qu’une femme est enceinte et non pas qu’elle a eu un enfant. Cependant, le contexte semble indiquer que c’est cette dernière signification qu’avaient en tête les auteurs, de sorte que cette traduction a été privilégiée. </p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Termium. « primitive ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=primitive&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=primitive&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=primitive&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
</td>
</tr>
<tr>
<td class="en">
<p>Open World</p>
<p><em></em></p>
</td>
<td class="en">
<p>The “Open World Assumption” is a term from knowledge base systems. It characterizes knowledge base systems that assume the information stored is incomplete relative to the universe of discourse they intend to describe. This incompleteness may be due to the inability of the maintainer to provide sufficient information or due to more fundamental problems of cognition in the system’s domain. Such problems are characteristic of cultural information systems. Our records about the past are necessarily incomplete. In addition, there may be items that cannot be clearly assigned to a given <strong>class</strong>. </p>
<p>In particular, absence of a certain <strong>property</strong> for an item described in the system does not mean that this item does not have this property. For example, if one item is described as Biological Object and another as Physical Object, this does not imply that the latter may not be a Biological Object as well. Therefore, <strong>complements</strong> of a class with respect to a <strong>superclass</strong> cannot be concluded in general from an information system using the Open World Assumption. For example, one cannot list “all Physical Objects known to the system that are not Biological Objects in the real world”, but one may of course list “all items known to the system as Physical Objects but that are not known to the system as Biological Objects”.</p>
</td>
<td>
<a name="terminologie-monde-ouvert"></a><p>Monde Ouvert</p>
</td>
<td>
<p>L’hypothèse du « monde ouvert » porte sur les systèmes de bases de connaissances et stipule que l’information qui y est stockée est incomplète en comparaison de l’univers discursif que cette information représente. Cette incomplétude peut être due à l’incapacité du responsable [n.d.t. de la base de connaissance] de fournir des informations complètes ou encore à des problèmes plus fondamentaux du domaine eu égard à la cognition, problèmes qui sont caractéristiques des systèmes d’information sur le patrimoine culturel. En effet, les enregistrements au sujet du passé sont nécessairement incomplets et certains éléments pourraient ne pas être facilement attribuables à une <strong>classe</strong> préétablie. </p>
<p>Qui plus est, l’absence d’une <strong>propriété</strong> pour un élément décrit dans un système [n.d.t. d’information] n’implique pas automatiquement que cet élément n’a pas la propriété en question. Par exemple, si un élément est décrit comme un <code class="language-plaintext highlighter-rouge">E20_Objet_biologique</code> et qu’un autre est décrit comme un <code class="language-plaintext highlighter-rouge">E19_Objet_matériel</code>, rien n’indique que ce dernier ne soit pas lui aussi un <code class="language-plaintext highlighter-rouge">E20_Objet_biologique</code>. Ainsi, les <strong>compléments</strong> d’une classe eu égard à une <strong>super-classe</strong> ne peuvent être logiquement inférés depuis un système d’information mobilisant l’hypothèse du monde ouvert. Par exemple, il est impossible d’énumérer « tous les <code class="language-plaintext highlighter-rouge">E19_Objet_matériel</code> d’un système qui ne sont pas des <code class="language-plaintext highlighter-rouge">E20_Objet_biologique</code> dans le monde réel”, mais il est néanmoins possible d’énumérer « tous les éléments <code class="language-plaintext highlighter-rouge">E19_Objet_matériel</code> connus de ce système qui ne sont pas des <code class="language-plaintext highlighter-rouge">E20_Objet_biologique</code> connus de ce même système”.</p>
<p>[n.d.t. voir la section sur la <a href="/v7.1.2/information/principes-de-modelisation#de-la-minimalite"><span class="underline">Minimalité</span></a> dans les <a href="/v7.1.2/information/principes-de-modelisation"><span class="underline">Principes de modélisation</span></a>].</p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p><em></em></p>
</td>
</tr>
<tr>
<td class="en">
<p>complement</p>
<p><em></em></p>
</td>
<td class="en">
<p>The<strong> </strong>complement of a class A with respect to one of its <strong>superclasses</strong> B is the set of all <strong>instances</strong> of B that are not instances of A. Formally, it is the set-theoretic difference of the <strong>extension</strong> of B minus the extension of A. Compatible extensions of the CIDOC CRM should not declare any <strong>class</strong> with the <strong>intension </strong>of them being the complement of one or more other classes. To do so will normally violate the desire to describe an <strong>Open World</strong>. For example, for all possible cases of human gender, male should not be declared as the complement of female or vice versa. What if someone is both or even of another kind? </p>
</td>
<td>
<a name="terminologie-complement"></a><p>Complément</p>
</td>
<td>
<p>Le complément d’une <a href="/v7.1.2/information/introduction#terminologie-classe"><span class="underline">classe</span></a> <code class="language-plaintext highlighter-rouge">A</code> par rapport à une de ses  <a href="/v7.1.2/information/introduction#terminologie-super-classe"><span class="underline"><strong>super-classes</strong></span></a> <code class="language-plaintext highlighter-rouge">B</code> est l’ensemble de toutes les <a href="/v7.1.2/information/introduction#terminologie-instance"><span class="underline"><strong>instances</strong></span></a> de <code class="language-plaintext highlighter-rouge">B</code> qui ne sont pas des instances de <code class="language-plaintext highlighter-rouge">A</code>. Formellement, il s’agit (en ce qui a trait à la théorie des ensembles) de l’<a href="/v7.1.2/information/introduction#terminologie-extension"><span class="underline"><strong>extension</strong></span></a> de <code class="language-plaintext highlighter-rouge">B</code> moins l’extension de <code class="language-plaintext highlighter-rouge">A</code>. Les extensions compatibles de CIDOC CRM ne devraient déclarer aucune classe dont l’<a href="/v7.1.2/information/introduction#terminologie-intension"><span class="underline"><strong>intension</strong></span></a> est le complément de l’une ou de plusieurs classes. Ceci contreviendrait aux principes du <a href="/v7.1.2/information/introduction#terminologie-monde-ouvert"><span class="underline"><strong>Monde Ouvert</strong></span></a> [n.d.t. selon lesquels], par exemple, pour tous les genres humains possibles, le masculin ne devrait pas être déclaré complémentaire du féminin et vice-versa. </p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
<p>La dernière phrase du texte original semble avoir pour objectif d’inclure toutes les personnes, mais elle est formulée de manière quelque peu cavalière et ne s’aligne pas avec l’approche des autres exemples mentionnés de sorte qu’elle pourrait être considérée marginalisante et peu inclusive. Puisqu’elle n’apporte pas d’information supplémentaire, elle a été retirée du texte traduit. </p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p><em></em></p>
</td>
</tr>
<tr>
<td class="en">
<p>query containment</p>
<p><em></em></p>
</td>
<td class="en">
<p>Query containment is a problem from database theory: A query X contains another query Y, if for each possible population of a database the answer set to query X contains also the answer set to query Y. If query X and Y were classes, then X would be <strong>superclass</strong> of Y. </p>
</td>
<td>
<a name="terminologie-inclusion-des-requetes"></a><p>Inclusion des requêtes</p>
</td>
<td>
<p>L’inclusion des requêtes [n.d.t relève de la théorie des bases de données et statue] que pour une requête <code class="language-plaintext highlighter-rouge">X</code> qui contient une requête <code class="language-plaintext highlighter-rouge">Y</code>, pour chaque population possible de la base de données l’ensemble de résultats de la requête <code class="language-plaintext highlighter-rouge">X</code> contient aussi l’ensemble de résultats de la requête <code class="language-plaintext highlighter-rouge">Y</code>. [n.d.t. Dans le cadre de CIDOC CRM, ceci implique que] si les requêtes <code class="language-plaintext highlighter-rouge">X</code> et <code class="language-plaintext highlighter-rouge">Y</code> étaient des <a href="/v7.1.2/information/introduction#terminologie-classe"><span class="underline">classes</span></a>, alors <code class="language-plaintext highlighter-rouge">X</code> serait <a href="/v7.1.2/information/introduction#terminologie-super-classe"><span class="underline"><strong>super-classe</strong></span></a> de <code class="language-plaintext highlighter-rouge">Y</code>. </p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
<p>Le terme « query containment » a été traduit par « inclusion des requêtes ». Le « containment » est généralement traduit dans le domaine de l’algèbre par « inclusion » et dans le domaine logiciel par « contenance ». Puisqu’il s’agit d’un problème fondamentalement théorique et algorithmique, il est apparu préférable de se rapprocher de l’usage mathématique.</p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Groz, Benoît. « Inclusion et équivalence de requêtes conjonctives ». Rapport de stage, Institut national de recherche en sciences et technologies du numérique, 2008.<a href="https://www.lri.fr/~groz/documents/rapport.pdf"><span class="underline"> </span></a><a href="https://www.lri.fr/~groz/documents/rapport.pdf"><span class="underline">https://www.lri.fr/~groz/documents/rapport.pdf</span></a>.</p>
<p>Termium. « containment ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=containment&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=containment&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=containment&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
</td>
</tr>
<tr>
<td class="en">
<p>interoperability</p>
<p><em></em></p>
</td>
<td class="en">
<p>Interoperability means the capability of different information systems to communicate some of their contents. In particular, it may mean that</p>
<ul><li><p> two systems can exchange information, and/or </p>
</li>
<li><p> multiple systems can be accessed with a single method. </p>
</li></ul>
<p>Generally, syntactic<strong> </strong>interoperability is distinguished from <strong>semantic</strong> <strong>interoperability</strong>. Syntactic interoperability means that the information encoding of the involved systems and the access protocols are compatible, so that information can be processed as described above without error. However, this does not mean that each system processes the data in a manner consistent with the intended meaning. For example, one system may use a table called “Actor” and another one called “Agent”. With syntactic interoperability, data from both tables may only be retrieved as distinct, even though they may have exactly the same meaning. To overcome this situation, semantic interoperability has to be added. The CIDOC CRM relies on existing syntactic interoperability and is concerned only with adding <em>semantic</em> <em>interoperability</em>.</p>
</td>
<td>
<a name="terminologie-interoperabilite-syntactique"></a><p>Interopérabilité [syntactique]</p>
</td>
<td>
<p>L’interopérabilité<strong> </strong>réfère à la capacité de différents systèmes d’information de communiquer de l’information [n.d.t. entre eux], ce qui implique : </p>
<ul><li><p>que deux systèmes peuvent échanger de l’information et/ou</p>
</li>
<li><p>qu’il est possible d’accéder à plusieurs systèmes grâce à une seule méthode. </p>
</li></ul>
<p>Généralement, l’interopérabilité syntactique se distingue de l’<a href="/v7.1.2/information/introduction#terminologie-interoperabilite-semantique"><span class="underline"><strong>interopérabilité sémantique</strong></span></a> par le fait que l’information encodée et les protocoles d’accès syntactiques sont compatibles de telle sorte que l’information peut être traitée sans erreur. Par contre, ceci ne garantit pas que chaque système traite les données en adéquation avec la signification initiale des données. Par exemple, un système peut avoir une table « Acteur » alors qu’un autre peut avoir une table « Agent » [n.d.t. qui traitent toutes deux le même type d’information]. L’interopérabilité syntactique ne permet d’extraire les données que de manière distincte malgré que leur sens soit le même. La prise en compte de la signification des données lors de leur traitement nécessite en effet l’usage de l’interopérabilité sémantique en plus de l’interopérabilité syntactique. Le CIDOC CRM se repose sur cette dernière et n’a pour objectif que d’ajouter l’<em>interopérabilité sémantique</em>. </p>
<p>[n.d.t. voir aussi <a href="/v7.1.2/information/introduction#terminologie-interoperabilite-semantique"><span class="underline">Interopérabilité sémantique</span></a>].</p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p><em></em></p>
</td>
</tr>
<tr>
<td class="en">
<p>semantic interoperability</p>
<p><em></em></p>
</td>
<td class="en">
<p>Semantic <strong>interoperability</strong> means the capability of different information systems to communicate information consistent with the intended meaning. In more detail, the intended meaning encompasses </p>
<ul><li><p>the data structure elements involved, </p>
</li>
<li><p>the terminology appearing as data and </p>
</li>
<li><p>the identifiers used in the data for factual items such as places, people, objects etc. </p>
</li></ul>
<p>Obviously, communication about data structure must be resolved first. In this case consistent communication means that data can be transferred between data structure elements with the same intended meaning or that data from elements with the same intended meaning can be merged. In practice, the different levels of generalization in different systems do not allow the achievement of this ideal.</p>
<p>Therefore, semantic interoperability is regarded as achieved if elements can be found that provide a reasonably close generalization for the transfer or merge. This problem is being studied theoretically as the <strong>query containment </strong>problem. The CIDOC CRM is only concerned with semantic interoperability on the level of data structure elements. </p>
</td>
<td>
<a name="terminologie-interoperabilite-semantique"></a><p>Interopérabilité sémantique</p>
</td>
<td>
<p><a href="/v7.1.2/information/introduction#terminologie-interoperabilite-semantique"><span class="underline">L’</span></a><a href="/v7.1.2/information/introduction#terminologie-interoperabilite-semantique"><span class="underline"><strong>interopérabilité</strong></span></a> sémantique réfère à la capacité de différents systèmes d’information de communiquer de l’information [n.d.t. entre eux] en adéquation avec sa signification initiale, ce qui comprend : </p>
<ul><li><p>les éléments de la structure de données impliqués;</p>
</li>
<li><p>la terminologie présentée comme données; </p>
</li>
<li><p>les identifiants représentant des éléments factuels comme des lieux, des personnes et des objets dans les données. </p>
</li></ul>
<p>La communication des éléments structurels doit être résolue en premier lieu. Une communication adéquate implique à cet égard que les données transférées d’une structure à l’autre conservent leur signification, ou que les données référant aux mêmes éléments et ayant la même signification soient fusionnées. En pratique cependant, en raison des niveaux de généralisation qui varient d’un système à l’autre, ceci n’est souvent pas possible. </p>
<p>L’interopérabilité sémantique est donc considérée atteinte si des éléments attestant une généralisation raisonnablement comparable au transfert ou à la fusion [n.d.t. des données concernées] sont identifiés. Ceci est un problème théorique étudié sous le nom du problème de l'<a href="/v7.1.2/information/introduction#terminologie-inclusion-des-requetes"><span class="underline"><strong>inclusion des requêtes</strong></span></a> »; le CIDOC CRM, pour sa part, ne se concentre que sur l'interopérabilité sémantique des éléments structurés. </p>
<p>[n.d.t. voir aussi <a href="/v7.1.2/information/introduction#terminologie-interoperabilite-syntactique"><span class="underline">Interopérabilité syntactique</span></a>].</p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
<p>Le terme « merge » a été traduit par « fusion », lequel semble être la traduction la plus courante dans le domaine du traitement de l’information. </p>
<p>Le terme « query containment » a été traduit par « inclusion des requêtes ». Le « containment » est généralement traduit dans le domaine de l’algèbre par « inclusion » et dans le domaine logiciel par « contenance ». Puisqu’il s’agit d’un problème fondamentalement théorique et algorithmique, il est apparu préférable de se rapprocher de l’usage mathématique.</p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Groz, Benoît. « Inclusion et équivalence de requêtes conjonctives ». Rapport de stage, Institut national de recherche en sciences et technologies du numérique, 2008.<a href="https://www.lri.fr/~groz/documents/rapport.pdf"><span class="underline"> </span></a><a href="https://www.lri.fr/~groz/documents/rapport.pdf"><span class="underline">https://www.lri.fr/~groz/documents/rapport.pdf</span></a>.</p>
<p>Termium. « containment ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=containment&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=containment&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=containment&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
<p>———. « merge ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=merge&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=merge&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=merge&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
</td>
</tr>
<tr>
<td class="en">
<p>property quantifiers</p>
<p><em></em></p>
</td>
<td class="en">
<p>We use the term "property quantifiers" for the declaration of the allowed number of <strong>instances</strong> of a certain <strong>property</strong> that can refer to a particular instance of the <strong>range </strong>class or the <strong>domain</strong> class of that property. These declarations are ontological, i.e., they refer to the nature of the real world described and not to our current knowledge. For example, each person has exactly one father, but collected knowledge may refer to none, one or many.</p>
</td>
<td>
<a name="terminologie-quantificateurs-de-propriete"></a><p>Quantificateurs de propriété</p>
</td>
<td>
<p>Le terme « quantificateurs de propriété » désigne la déclaration du nombre autorisé d’<a href="/v7.1.2/information/introduction#terminologie-instance"><span class="underline"><strong>instances</strong></span></a> d’une <a href="/v7.1.2/information/introduction#terminologie-propriete"><span class="underline"><strong>propriété</strong></span></a> qui peut référer à une instance particulière d’une <a href="/v7.1.2/information/introduction#terminologie-classe"><span class="underline">classe</span></a> de <a href="/v7.1.2/information/introduction#terminologie-portee"><span class="underline"><strong>portée</strong></span></a> ou de <a href="/v7.1.2/information/introduction#terminologie-domaine"><span class="underline"><strong>domaine</strong></span></a> de cette propriété. Ces déclarations sont ontologiques, c.-à-d. qu’elles concernent la nature du monde « réel » qui est décrit plutôt que la connaissance de celui-ci. Par exemple, chaque personne a exactement un père [n.d.t. biologique] même si les connaissances recensées peuvent n’en indiquer aucun ou plusieurs. </p>
<p>[n.d.t. voir la section <a href="/v7.1.2/information/introduction#quantificateurs-de-proprietes"><span class="underline">Quantificateurs de propriétés</span></a> dans la section <a href="/v7.1.2/information/compatibilite-avec-le-cidoc-crm"><span class="underline">Compatibilité avec le CIDOC CRM</span></a>].</p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Termium. « quantifier ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=quantifier&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=quantifier&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=quantifier&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
</td>
</tr>
<tr>
<td class="en">
<p>universal</p>
<p><em></em></p>
</td>
<td class="en">
<p>The fundamental ontological distinction between universals and particulars can be informally understood by considering their relationship with instantiation: particulars are entities that have no <strong>instances</strong> in any possible world; universals are entities that do have instances. <strong>Classes </strong>and <strong>properties</strong> (corresponding to predicates in a logical language) are usually considered to be universals. (after Gangemi et al. 2002, pp. 166-181).</p>
</td>
<td>
<a name="terminologie-universel"></a><p>universel</p>
</td>
<td>
<p>La distinction ontologique fondamentale entre universel et particulier peut être comprise informellement en examinant la relation de chacun avec son instanciation : alors que les particuliers n’ont aucune <a href="/v7.1.2/information/introduction#terminologie-instance"><span class="underline"><strong>instance</strong></span></a> possible, peu importe le monde dans lequel ils se trouvent, les universels sont des entités qui, elles, ont des instances. Les <a href="/v7.1.2/information/introduction#terminologie-classe"><span class="underline"><strong>classes</strong></span></a> et <a href="/v7.1.2/information/introduction#terminologie-propriete"><span class="underline"><strong>propriétés</strong></span></a> (qui correspondent en langage logique à des prédicats) sont généralement considérées être des universels (Gangemi & al. 2002, p. 166-181).</p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p><em></em></p>
</td>
</tr>
<tr>
<td class="en">
<p>Knowledge Creation Process</p>
<p><em></em></p>
</td>
<td class="en">
<p>All knowledge contained in an information system must have been introduced into that system by some human agent, either directly or indirectly. Despite this fact, many, if not most, statements within such a system will lack specific attribution of authority. That being said, in the domain of cultural heritage, it is common practice that, for the processes of collection documentation and management, there are clearly and explicitly elaborated systems of responsibility outlining by whom and how knowledge can be added and or modified in the system. Ideally these systems are specified in institutional policy and protocol documents. Thus, it is reasonable to hold that all such statements that lack explicit authority attribution within the information system can, in fact, be read as the official view of the administrating institution of that system. </p>
<p>Such a position does not mean to imply that an information system represents at any particular moment a completed phase of knowledge that the institution promotes. Rather, it means to underline that, in a CH context, a managed set of data, at any state of elaboration, will in fact embody an adherence to some explicit code of standards which guarantees the validity of that data within the scope of said standards and all practical limitations. So long as the information is under active management it remains continuously open to revision and improvement as further research reveals further understanding surrounding the objects of concern.</p>
<p>A distinct exception to this rule is represented by information in the data set that carries with it an explicit statement of responsibility.</p>
<p>In CIDOC CRM such statements of responsibility are expressed through knowledge creation events such as E13 Attribute Assignment and its relevant subclasses. Any information in a CIDOC CRM model that is based on an explicit creation event for that piece of information, where the creator’s identity has been given, is attributed to the authority and assigned to the responsibility of the actor identified as causal in that event. For any information in the system connected to knowledge creation events that do not explicitly reference their creator, as well as any information not connected to creation events, the responsibility falls back to the institution responsible for the database/knowledge graph. That means that for information only expressed through shortcuts such as <em>P2 has type</em>, where no knowledge creation event has been explicitly specified, the originating creation event cannot be deduced and the responsibility for the information can never be any other body than the institution responsible for the whole information system.</p>
<p>In the case of an institution taking over stewardship of a database transferred into their custody, two relations of responsibility for the knowledge therein can be envisioned. If the institution accepts the dataset and undertakes to maintain and update it, then they take on responsibility for that information and become the default authority behind its statements as described above. If, on the other hand, the institution accepts the data set and stores it without change as a closed resource, then it can be considered that the default authority remains the original steward.</p>
</td>
<td>
<a name="terminologie-processus-de-creation-de-connaissances"></a><p>Processus de création de connaissances</p>
</td>
<td>
<p>Toute connaissance contenue dans un système d’information doit avoir été introduite dans ce système par un agent humain, que ce soit de manière directe ou indirecte. Malgré cela, plusieurs, si ce n’est la plupart, des énoncés de tels systèmes n’ont pas d’information associée quant à la personne ayant autorité sur eux. Néanmoins, le milieu patrimonial a des pratiques d’assignation de l’autorité établissant comment et par qui une information peut être introduite ou modifiée dans un système, en particulier dans le contexte de la documentation et de la gestion des collections. Ces pratiques sont idéalement recensées dans le cadre de politiques institutionnelles et de protocoles documentaires. Il est donc raisonnable de considérer que, dans le cadre de tels systèmes d’information, tout énoncé n’ayant pas une assignation explicite d’autorité représente la position officielle de l’institution responsable du système.</p>
<p>Cette posture [n.d.t. du CIDOC CRM] n’implique cependant pas qu’un système d’information représente un état abouti des connaissances promues par l’institution qui en est responsable. Cette posture a plutôt pour objectif de mettre en évidence qu’un ensemble de données patrimoniales (à un quelconque degré d’élaboration) incarne une adhésion à un ensemble de standards qui garantissent la validité des données dans le cadre de celui-ci et de ses limitations. Tant que l’information [n.d.t. contenue dans le système d’information] est activement maintenue, elle demeure sujette à des améliorations, modifications et révisions au fur et à mesure que la recherche à son sujet présente de nouveaux éléments à son égard ou à l’égard de ce qui l’entoure. </p>
<p>De l’information dans un ensemble de données auquel est associé un énoncé explicite de responsabilité constitue une exception notable à cette règle. Dans CIDOC CRM, de tels énoncés de responsabilité sont exprimés par des évènements de création de connaissances tels que <code class="language-plaintext highlighter-rouge">E13_Assignation_d'attribut</code> ou ses sous-classes pertinentes. Toute information dans un modèle CIDOC CRM basée sur un évènement de création explicite de cette information (où l’identité du créateur est spécifiée) a pour autorité et responsable le créateur en question. Pour toute information dans ce système qui n’a pas de référence explicite à un créateur spécifique ainsi que pour toute information qui n’est pas liée à un évènement de création, la responsabilité de l’information revient à l’institution qui assume la gestion de la base et du graphe de connaissances. Ceci implique que l’information qui n’est exprimée que grâce à des raccourcis (p. ex.  <code class="language-plaintext highlighter-rouge">P2_a_pour_type</code>) : </p>
<ul><li><p>n’est pas associée à un évènement explicite de création de connaissances; </p>
</li>
<li><p>ne peut pas être associée à un évènement de création originel, car celui-ci ne peut être déduit; </p>
</li>
<li><p>ne peut avoir pour responsable que l’institution responsable du système d’information (et qu’aucun autre organisme ne peut en être imputable). </p>
</li></ul>
<p>Lorsqu’une institution prend à sa charge une base de données dans le cadre d’un transfert de sa garde d’une autorité administrative à une autre, deux relations de responsabilité sur les connaissances qui s’y trouvent sont possibles. Si l’institution hôte accepte la responsabilité de la maintenance des informations, elle devient l’autorité associée par défaut aux énoncés qui s’y trouvent. Si, par contre, l’institution hôte traite l’ensemble des données comme une ressource « fermée » [n.d.t. donc traité à la manière d’un artefact], l’autorité associée par défaut aux énoncés qui s’y trouvent sera celle de l’institution initiale [n.d.t. comme c’est le cas de tout autre document de recherche se trouvant dans la collection de l’institution hôte].  </p>
<p>[n.d.t. voir <a href="/v7.1.2/information/principes-de-modelisation#de-lauctorialite-des-contenus-dune-base-de-connaissances"><span class="underline">De l’auctorialité des contenus d’une base de connaissances</span></a> dans les <a href="/v7.1.2/information/principes-de-modelisation"><span class="underline">Principes de modélisation</span></a>]. </p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
<p>Le terme « information system » a été traduit par « système d’information ». </p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Termium. « Information System ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-eng.html?lang=eng&i=1&srchtxt=INFORMATION+SYSTEM&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-eng.html?lang=eng&i=1&srchtxt=INFORMATION+SYSTEM&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-eng.html?lang=eng&i=1&srchtxt=INFORMATION+SYSTEM&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
</td>
</tr>
<tr>
<td class="en">
<p>transitivity</p>
<p><em></em></p>
</td>
<td class="en">
<p>Transitivity is defined in the standard way found in mathematics or logic: A property P is transitive if the domain and range is the same class and for all instances x, y, z of this class the following is the case: If x is related by P to y and y is related by P to z, then x is related by P to z. The intention of a property as described in the scope note will decide whether a property is transitive or not. For example, the property <em>P121 overlaps with</em> between instances of E53 Place is not transitive, while the property <em>P89 falls within (contains)</em> between instances of E53 Place and the property <em>P46 is composed of (forms part of)</em> between instances of E18 Physical Thing are both transitive. Transitivity is especially useful when CIDOC CRM is implemented in a system with deduction.</p>
</td>
<td>
<a name="terminologie-transitivite"></a><p>Transitivité</p>
</td>
<td>
<p>La transitivité (définie selon des principes mathématiques et logiques) signifie qu’une <a href="/v7.1.2/information/introduction#terminologie-propriete"><span class="underline">propriété</span></a> <code class="language-plaintext highlighter-rouge">P</code> est réflexive si son <a href="/v7.1.2/information/introduction#terminologie-domaine"><span class="underline">domaine</span></a> et sa <a href="/v7.1.2/information/introduction#terminologie-portee"><span class="underline">portée</span></a> sont la même <a href="/v7.1.2/information/introduction#terminologie-classe"><span class="underline">classe</span></a>, et que pour toutes les <a href="/v7.1.2/information/introduction#terminologie-instance"><span class="underline">instances</span></a> <code class="language-plaintext highlighter-rouge">x</code>, <code class="language-plaintext highlighter-rouge">y</code>, <code class="language-plaintext highlighter-rouge">z</code> de cette classe si <code class="language-plaintext highlighter-rouge">x</code> est relié par <code class="language-plaintext highlighter-rouge">P</code> à <code class="language-plaintext highlighter-rouge">y</code> et que <code class="language-plaintext highlighter-rouge">y</code> est relié par <code class="language-plaintext highlighter-rouge">P</code> à <code class="language-plaintext highlighter-rouge">z</code>, alors <code class="language-plaintext highlighter-rouge">x</code> est relié par <code class="language-plaintext highlighter-rouge">P</code> à <code class="language-plaintext highlighter-rouge">z</code>. L’intention de la propriété telle qu’elle est établie dans sa <a href="/v7.1.2/information/introduction#terminologie-note-dapplication"><span class="underline">note d’application</span></a> détermine si elle est transitive ou non. Par exemple, la propriété <code class="language-plaintext highlighter-rouge">P121_se_superpose_partiellement_à</code> entre des instances de <code class="language-plaintext highlighter-rouge">E53_Lieu</code> n’est pas transitive alors que la propriété  <code class="language-plaintext highlighter-rouge">P89_s’insère_dans (contient)</code> entre des instances de <code class="language-plaintext highlighter-rouge">E53_Lieu</code> et la propriété <code class="language-plaintext highlighter-rouge">P46_est_composé_de (fait_partie_de)</code> entre des instances de <code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code> sont toutes deux transitives. La transitivité est particulièrement utile lors de l’implémentation de CIDOC CRM dans un système qui utilise la déduction logique. </p>
<p>[n.d.t. voir <a href="/v7.1.2/information/introduction#de-lheritage-et-de-la-transitivite"><span class="underline">De l’héritage et de la transitivité</span></a> dans les <a href="/v7.1.2/information/principes-de-modelisation"><span class="underline">Principes de modélisation</span></a>]. </p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p><em></em></p>
</td>
</tr>
<tr>
<td class="en">
<p>symmetry</p>
</td>
<td class="en">
<p>Symmetry is defined in the standard way found in mathematics or logic: A property P is symmetric if the domain and range are the same class and for all instances x, y of this class the following is the case: If x is related by P to y, then y is related by P to x. The intention of a property as described in the scope note will decide whether a property is symmetric or not. An example of a symmetric property is E53 Place<em>. P122 borders with: </em>E53 Place. The names of symmetric properties have no parenthetical form, because reading in the range-to-domain direction is the same as the domain-to-range reading.</p>
</td>
<td>
<a name="terminologie-symetrie"></a><p>Symétrie</p>
</td>
<td>
<p>La symétrie (définie selon des principes mathématiques et logiques) signifie qu’une <a href="/v7.1.2/information/introduction#terminologie-propriete"><span class="underline">propriété</span></a> <code class="language-plaintext highlighter-rouge">P</code> est symétrique si son <a href="/v7.1.2/information/introduction#terminologie-domaine"><span class="underline">domaine</span></a> et sa <a href="/v7.1.2/information/introduction#terminologie-portee"><span class="underline">portée</span></a> sont la même <a href="/v7.1.2/information/introduction#terminologie-classe"><span class="underline">classe</span></a>, et que pour toutes les <a href="/v7.1.2/information/introduction#terminologie-instance"><span class="underline">instances</span></a> <code class="language-plaintext highlighter-rouge">x, y</code> de cette classe si <code class="language-plaintext highlighter-rouge">x</code> est relié par <code class="language-plaintext highlighter-rouge">P</code> à <code class="language-plaintext highlighter-rouge">y</code>, alors <code class="language-plaintext highlighter-rouge">y</code> est relié par <code class="language-plaintext highlighter-rouge">P</code> à <code class="language-plaintext highlighter-rouge">x</code>. L’intention de la propriété (telle qu’elle est établie dans sa <a href="/v7.1.2/information/introduction#terminologie-note-dapplication"><span class="underline">note d’application</span></a>) détermine si elle est symétrique ou non. Un exemple de propriété symétrique est <code class="language-plaintext highlighter-rouge">E53_Lieu</code>. <code class="language-plaintext highlighter-rouge">P122_est_limitrophe_de</code> : <code class="language-plaintext highlighter-rouge">E53_Lieu</code>. Les noms de propriétés symétriques n’ont pas de forme parenthétique, car les lire depuis la portée vers le domaine revient au même que les lire depuis le domaine vers la portée. </p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p><em></em></p>
</td>
</tr>
<tr>
<td class="en">
<p>reflexivity</p>
</td>
<td class="en">
<p>Reflexivity is defined in the standard way found in mathematics or logic: A property P is reflexive if the domain and range are the same class and for all instances x, of this class the following is the case: x is related by P to itself. The intention of a property as described in the scope note will decide whether a property is reflexive or not. An example of a reflexive property is E53 Place<em>. P89 falls within (contains): </em>E53 Place. </p>
</td>
<td>
<a name="terminologie-reflexivite"></a><p>Réflexivité</p>
</td>
<td>
<p>La réflexivité (définie selon des principes mathématiques et logiques standards) signifie qu’une <a href="/v7.1.2/information/introduction#terminologie-propriete"><span class="underline">propriété</span></a> <code class="language-plaintext highlighter-rouge">P</code> est réflexive si son <a href="/v7.1.2/information/introduction#terminologie-domaine"><span class="underline">domaine</span></a> et sa <a href="/v7.1.2/information/introduction#terminologie-portee"><span class="underline">portée</span></a> sont la même <a href="/v7.1.2/information/introduction#terminologie-classe"><span class="underline">classe</span></a>, et que pour toutes les <a href="/v7.1.2/information/introduction#terminologie-instance"><span class="underline">instances</span></a> <code class="language-plaintext highlighter-rouge">x</code> de cette classe <code class="language-plaintext highlighter-rouge">x</code> est relié à lui-même par <code class="language-plaintext highlighter-rouge">P</code>. L’intention de la propriété (telle qu’elle est établie dans sa note d’application) détermine si elle réflexive ou non. Un exemple de propriété réflexive est <code class="language-plaintext highlighter-rouge">E53_Lieu</code>. <code class="language-plaintext highlighter-rouge">P89_s’insère_dans (contient)</code> : <code class="language-plaintext highlighter-rouge">E53_Lieu</code>. </p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p><em></em></p>
</td>
</tr>
</tbody>
</table>

<h2 id="application-formelle"><span class="en heading">Applied Form - </span>Application formelle</h2>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>The CIDOC CRM is an ontology in the sense used in computer science. It has been expressed as an object-oriented semantic model, in the hope that this formulation will be comprehensible to both documentation experts and information scientists alike, while at the same time being readily converted to machine-readable formats such as RDF Schema or OWL. A CRM conformant documentation system can be implemented using RDF Schema or OWL, but also in Relational or Object-Oriented schema. CIDOC CRM instances can be encoded in RDF, JSON LD, XML, OWL and others.</p>
<p>More specifically, the CIDOC CRM is expressed in terms of the primitives of semantic data modelling. As such, it consists of:</p>
<ul><li><p>classes, which represent general notions in the domain of discourse, such as the CIDOC CRM class E21 Person which represents the notion of person;</p>
</li>
<li><p>properties, which represent the binary relations that link the individuals in the domain of discourse, such as the CIDOC CRM property P152 has parent linking a person to one of the person’s parent.</p>
</li>
<li><p>properties of properties, such as the property P14.1 in the role of, of the CIDOC CRM property P14 carried out by (see also section “About Types”). They do not appear in the property hierarchy list, but are included as part of their base property declaration and are referred to in the class declarations. They all have the implicit quantification “many to many” (see also section “Property Quantifiers”)</p>
</li></ul>
<p>Although the definition of the CIDOC CRM provided here is complete, it is an intentionally compact and concise presentation of the CIDOC CRM’s  81 classes and 160 unique properties. It does not attempt to articulate the inheritance of properties by subclasses throughout the class hierarchy (this would require the declaration of several thousand properties, as opposed to 160). However, this definition does contain all of the information necessary to infer and automatically generate a full declaration of all properties, including inherited properties. </p>
</td>
<td>
<p>Le CIDOC CRM est une ontologie (dans le sens informatique du terme) prenant la forme d’un modèle sémantique orienté-objet destiné à la conversion vers des formats lisibles par des machines (p. ex. <a href="https://www.w3.org/TR/rdf-schema/"><span class="underline">RDF Schema</span></a>, <a href="https://www.w3.org/OWL/"><span class="underline">OWL</span></a>), mais formulé afin d’être compris tant par les informaticiens que par les experts de la documentation. Une documentation conforme au CIDOC CRM peut-être implémentée en utilisant RDF Schema ou OWL, mais aussi des schémas relationnels ou orientés-objets. Les instances de CIDOC CRM peuvent  être encodées en RDF, <a href="https://json-ld.org/"><span class="underline">JSON-LD</span></a>, <a href="https://www.w3.org/XML/"><span class="underline">XML</span></a>, OWL ou d'autres formats. </p>
<p>Plus spécifiquement, le CIDOC CRM est exprimé en utilisant les primitives de la modélisation sémantique de données. À ce titre, le modèle est constitué de : </p>
<ul><li><p>classes, qui représentent des notions générales du domaine du discours comme la classe du CIDOC CRM <code class="language-plaintext highlighter-rouge">E21_Personne</code> qui représente la notion de personne; </p>
</li>
<li><p>propriétés, qui représentent les relations binaires liant les instances du domaine du discours, comme la propriété du CIDOC CRM <code class="language-plaintext highlighter-rouge">P152_a_pour_parent (est_le_parent_de)</code>  qui relie une personne à l'un de ses parents; </p>
</li>
<li><p>propriétés de propriétés, comme la propriété <code class="language-plaintext highlighter-rouge">P14.1_dans_le_rôle_de</code> dérivée de la propriété du CIDOC CRM <code class="language-plaintext highlighter-rouge">P14_a_été_effectué_par (a_effectué)</code> (voir Des Types). Celles-ci n'apparaissent pas dans la hiérarchie des propriétés; elles sont plutôt incluses dans la déclaration de leur propriété source et mentionnées dans les déclarations de classe. Elles ont toutes la quantification implicite « plusieurs à plusieurs » (voir Quantificateurs de propriétés). </p>
</li></ul>
<p>La définition ci-présentée du CIDOC CRM est complète, bien qu’elle demeure une présentation intentionnellement concise et succincte de ses 81 classes et 160 propriétés uniques. Celle-ci n’a donc pas pour objectif de décliner l’héritage des propriétés par sous-classes à travers la hiérarchie des classes (ce qui exigerait la déclaration de plusieurs milliers de propriétés plutôt que de 160). Par contre, cette définition contient toute l’information nécessaire à l’inférence et à la génération automatique d’une déclaration complète des propriétés, ce qui inclut les propriétés héritées. </p>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<th style="width:15%"><p><em>Note de traduction</em></p>
</th>
<td colspan="1">
</td>
</tr>
<tr>
<th style="width:15%"><p><em>Références</em></p>
</th>
<td colspan="1">
<p>JSON-LD Working Group. « JSON-LD - JSON for Linking Data ». JSON-LD, 16 janvier 2014.<a href="https://json-ld.org/"><span class="underline"> </span></a><a href="https://json-ld.org/"><span class="underline">https://json-ld.org/</span></a>.</p>
<p>OWL Working Group. « OWL - Semantic Web Standards ». Ontologie. Cambridge, USA-MA: World Wide Web Consortium (W3C), 11 décembre 2012.<a href="https://www.w3.org/OWL/"><span class="underline"> </span></a><a href="https://www.w3.org/OWL/"><span class="underline">https://www.w3.org/OWL/</span></a>.</p>
<p>RDF Working Group. « RDF - Semantic Web Standards ». Modèle. Cambridge, USA-MA: World Wide Web Consortium (W3C), 25 février 2014.<a href="https://www.w3.org/RDF/"><span class="underline"> </span></a><a href="https://www.w3.org/RDF/"><span class="underline">https://www.w3.org/RDF/</span></a>.</p>
<p>XML Working Group. « Extensible Markup Language (XML) ». World Wide Web Consortium (W3C), 11 octobre 2016.<a href="https://www.w3.org/XML/"><span class="underline"> </span></a><a href="https://www.w3.org/XML/"><span class="underline">https://www.w3.org/XML/</span></a>.</p>
</td>
</tr>
</tbody>
</table>

<h3 id="convention-dappellation"><span class="en heading">Naming Conventions - </span>Convention d’appellation</h3>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>The following naming conventions have been applied throughout the CIDOC CRM:</p>
<ul><li><p>Classes are identified by numbers preceded by the letter “E” (historically classes were sometimes referred to as “Entities”), and are named using noun phrases (nominal groups) using title case (initial capitals). For example, E63 Beginning of Existence. </p>
</li>
<li><p>Properties are identified by numbers preceded by the letter “P,” and are named in both directions using verbal phrases in lower case. Properties with the character of states are named in the present tense, such as “has type”, whereas properties related to events are named in past tense, such as “carried out.” For example, <em>P126 employed (was employed in)</em>.</p>
</li>
<li><p>Property names should be read in their non-parenthetical form for the domain-to-range direction, and in parenthetical form for the range-to-domain direction. Reading a property in range-to-domain direction is equivalent to the inverse of that property. Following a current notational practice in OWL knowledge representation language, we represent inverse properties in this text by adding a letter “i” following the identification number and the parenthetical form of the full property name, such as <em>P59i is located on or within</em>, which is the inverse of <em>P59 has section (is located on or within).</em></p>
</li>
<li><p>Properties with a range that is a subclass of E59 Primitive Value (such as E1 CRM Entity<em>. P3 has note: </em>E62 String, for example) have no parenthetical name form, because reading the property name in the range-to-domain direction is not regarded as meaningful.</p>
</li>
<li><p>Properties that have identical domain and range are either symmetric or transitive. Instantiating a symmetric property implies that the same relation holds for both the domain-to-range and the range-to-domain directions. An example of this is E53 Place<em>. P122 borders with: </em>E53 Place. The names of symmetric properties have no parenthetical form, because reading in the range-to-domain direction is the same as the domain-to-range reading. Transitive asymmetric properties, such as E4 Period<em>. P9 consist of (forms part of): </em>E4 Period, have a parenthetical form that relates to the meaning of the inverse direction.</p>
</li>
<li><p>The choice of the domain of properties, and hence the order of their names, are established in accordance with the following priority list:</p>
<ul>
<li><p>Temporal Entity and its subclasses</p>
</li>
<li><p>Thing and its subclasses</p>
</li>
<li><p>Actor and its subclasses</p>
</li>
<li><p>Other</p>
</li></ul>
</li>
<li><p>Properties of properties are identified by “P”, followed by the number of the base property extended with “.1” and are named in one direction using a verbal phrase in lower case in the present tense. For example: the property P62.1 mode of depiction of the property P62 depicts (is depicted by)</p>
</li>
</ul>
</td>
<td>
<p>La convention suivante a été appliquée à travers le CIDOC CRM : </p>
<ul><li><p>Les <a href="/v7.1.2/information/introduction#terminologie-classe"><span class="underline">classes</span></a> sont identifiées par des numéros précédés de la lettre majuscule « E » (historiquement, les classes de CIDOC CRM étaient parfois appelées des « entités ») et leurs appellations sont constituées de groupes nominaux, les initiales des noms sont en majuscules. Par exemple, <code class="language-plaintext highlighter-rouge">E63_Début_d'existence</code> [n.d.t. Dans la version francophone, les classes sont toujours conjuguées au féminin singulier, p. ex. « une <code class="language-plaintext highlighter-rouge">E63_Début_d'existence</code> »]. </p>
</li>
<li><p>Les <a href="/v7.1.2/information/introduction#terminologie-propriete"><span class="underline">propriétés</span></a> sont identifiées par des numéros précédés de la lettre majuscule « P » et leurs appellations sont bidirectionnelles et constituées de syntagmes verbaux dont tous les termes sont en minuscules. Les propriétés ayant les caractéristiques d’états utilisent le présent (p. ex. « a pout type »), alors que les propriétés liées à des évènements sont nommées au passé (p. ex. a été effectué par). Par exemple, <code class="language-plaintext highlighter-rouge">P126_a_employé (a_été_employé_dans)</code> [n.d.t. Dans la version francophone, les propriétés sont toujours conjuguées au féminin singulier, p. ex. « une <code class="language-plaintext highlighter-rouge">P126_a_employé (a_été_employé_dans)</code> »]. </p>
</li>
<li><p>Les noms des propriétés devraient être lus dans leur forme non parenthétique lors d’une lecture dirigée depuis le <a href="/v7.1.2/information/introduction#terminologie-domaine"><span class="underline">domaine</span></a> vers la <a href="/v7.1.2/information/introduction#terminologie-portee"><span class="underline">portée</span></a>, et dans leur forme parenthétique lors d’une lecture dirigée depuis la portée vers le domaine. Lire une propriété depuis la portée vers le domaine équivaut à l’inverse de cette propriété. En adéquation avec les pratiques de notation <a href="https://www.w3.org/OWL/"><span class="underline">OWL</span></a> actuelles, les <a href="/v7.1.2/information/introduction#terminologie-propriete-inverse"><span class="underline">propriétés inverses </span></a>sont identifiées par l’ajout d’un « i » minuscule à la suite du numéro d’identification et de la forme parenthétique complète de la propriété (p. ex. <code class="language-plaintext highlighter-rouge">P59i_se_situe_sur_ou_dans</code> est la propriété inverse de <code class="language-plaintext highlighter-rouge">P59_a_pour_section (se_situe_sur_ou_dans)</code>). </p>
</li>
<li><p>Les propriétés dont la portée est une <a href="/v7.1.2/information/introduction#terminologie-sous-classe"><span class="underline">sous-classe</span></a> de <code class="language-plaintext highlighter-rouge">E59_Valeur_primitive</code> (p. ex. <code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code>. <code class="language-plaintext highlighter-rouge">P3_a_pour_note</code> : <code class="language-plaintext highlighter-rouge">E62_Chaîne_de_caractères</code>) n’ont pas de forme appellative parenthétique, car la lecture depuis la portée vers le domaine n’est pas porteuse de sens. </p>
</li>
<li><p>Les propriétés qui ont des domaine et portée identiques sont soit <a href="/v7.1.2/information/introduction#terminologie-symetrie"><span class="underline">symétriques</span></a>, soit <a href="/v7.1.2/information/introduction#terminologie-transitivite"><span class="underline">transitives</span></a>. Instancier une propriété symétrique implique que la même relation est applicable lors de la lecture depuis le domaine vers la portée et depuis la portée vers le domaine (p. ex. <code class="language-plaintext highlighter-rouge">E53_Lieu</code>. <code class="language-plaintext highlighter-rouge">P122_est_limitrophe_de</code> : <code class="language-plaintext highlighter-rouge">E53_Lieu</code>). Les formes appellatives de propriétés symétriques n’ont pas de forme parenthétique, car la lecture depuis la portée vers le domaine équivaut à la lecture depuis le domaine vers la portée. Les propriétés transitives asymétriques (p. ex. <code class="language-plaintext highlighter-rouge">E4_Période</code>. <code class="language-plaintext highlighter-rouge">P9_comprend (fait_partie_de)</code> : <code class="language-plaintext highlighter-rouge">E4_Période</code>) ont une forme parenthétique qui porte sur la signification de leur direction inverse. </p>
</li>
<li><p>Le choix du domaine des propriétés, et donc de l’ordre de leur appellation, est établi selon les priorités suivantes : </p>
<ul>
<li><p>Entités temporelles (<code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code> et ses sous-classes)</p>
</li>
<li><p>Choses (<code class="language-plaintext highlighter-rouge">E70_Chose</code> et ses sous-classes)</p>
</li>
<li><p>Acteurs (<code class="language-plaintext highlighter-rouge">E39_Actant</code> et ses sous-classes)</p>
</li>
<li><p>Autres</p>
</li>
</ul>
</li>
<li><p>Les propriétés de propriétés sont identifiées par la lettre majuscule « P » suivi du numéro de la propriété source complété par « .1 » et sont nommées de manière unidirectionnelle à l'aide de syntagmes verbaux dont tous les termes sont en minuscules et au présent. Par exemple, la propriété <code class="language-plaintext highlighter-rouge">P62.1_mode_d’illustration</code> de la propriété <code class="language-plaintext highlighter-rouge">P62_illustre (est_illustré_par)</code>.</p>
</li></ul>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<th style="width:15%"><p><em>Note de traduction</em></p>
</th>
<td colspan="1">
<p>Le terme « naming convention » est parfois traduit par « convention d’appellation » ou « convention de nommage”; le terme « convention d’appellation » a été privilégié, car il semble davantage utilisé de manière générale (après avoir fait une brève recherche en ligne) et est entériné par Termium. </p>
</td>
</tr>
<tr>
<th style="width:15%"><p><em>Références</em></p>
</th>
<td colspan="1">
<p>OWL Working Group. « OWL - Semantic Web Standards ». Ontologie. Cambridge, USA-MA: World Wide Web Consortium (W3C), 11 décembre 2012.<a href="https://www.w3.org/OWL/"><span class="underline"> </span></a><a href="https://www.w3.org/OWL/"><span class="underline">https://www.w3.org/OWL/</span></a>.</p>
<p>Termium. « Convention Appellation Courriels ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-eng.html?lang=eng&i=1&index=frt&srchtxt=CONVENTION%20APPELLATION%20COURRIELS"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-eng.html?lang=eng&i=1&index=frt&srchtxt=CONVENTION%20APPELLATION%20COURRIELS"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-eng.html?lang=eng&i=1&index=frt&srchtxt=CONVENTION%20APPELLATION%20COURRIELS</span></a>.</p>
</td>
</tr>
</tbody>
</table>

<h3 id="de-lheritage-et-de-la-transitivite"><span class="en heading">Inheritance and Transitivity - </span>De l’héritage et de la transitivité</h3>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>CIDOC CRM is formulated as a class system with inheritance. A property P with domain A and range B will also be a property between any possible subclasses of A and of B. In many cases there will be a common subclass C of both A and B. In these cases, when the property is restricted to C, that is, with C as domain and range, the restricted property could be transitive. For instance, an E73 Information Object can be incorporated into an E90 Symbolic Object and thus an information object can be incorporated in another information object. </p>
<p>In the definition of CIDOC CRM the transitive properties are explicitly marked as such in the scope notes. All unmarked properties should be considered as not transitive.</p>
</td>
<td>
<p>Le CIDOC CRM est un système de <a href="/v7.1.2/information/introduction#terminologie-classe"><span class="underline">classe</span></a> dotées <a href="/v7.1.2/information/introduction#terminologie-heritage"><span class="underline">d’héritage</span></a>, de telle manière qu’une <a href="/v7.1.2/information/introduction#terminologie-propriete"><span class="underline">propriété</span></a> <code class="language-plaintext highlighter-rouge">P</code> ayant pour <a href="/v7.1.2/information/introduction#terminologie-domaine"><span class="underline">domaine</span></a> <code class="language-plaintext highlighter-rouge">A</code> et pour <a href="/v7.1.2/information/introduction#terminologie-portee"><span class="underline">portée</span></a> <code class="language-plaintext highlighter-rouge">B</code> sera aussi une propriété potentielle de toutes les <a href="/v7.1.2/information/introduction#terminologie-sous-classe"><span class="underline">sous-classe</span></a>s de <code class="language-plaintext highlighter-rouge">A</code> et de <code class="language-plaintext highlighter-rouge">B</code>. Dans la plupart des cas, il y aura une sous-classe commune (<code class="language-plaintext highlighter-rouge">C</code>) de <code class="language-plaintext highlighter-rouge">A</code> et de <code class="language-plaintext highlighter-rouge">B</code>. Si c’est le cas, une propriété restreinte à <code class="language-plaintext highlighter-rouge">C</code> (c.-à-d. une propriété ayant <code class="language-plaintext highlighter-rouge">C</code> pour domaine et pour portée) pourrait être <a href="/v7.1.2/information/introduction#terminologie-transitive"><span class="underline">transitive</span></a>. Par exemple, un <code class="language-plaintext highlighter-rouge">E73_Objet_informationnel</code> peut faire partie d’un <code class="language-plaintext highlighter-rouge">E90_Objet_symbolique</code>, de telle sorte qu’un objet informationnel peut s’intégrer à un autre objet informationnel [n.d.t. puisqu’un <code class="language-plaintext highlighter-rouge">E90_Objet_symbolique</code> est un <code class="language-plaintext highlighter-rouge">E73_Objet_informationnel</code>]. </p>
<p>Les propriétés transitives sont explicitement indiquées comme telles dans les <a href="/v7.1.2/information/introduction#terminologie-note-dapplication"><span class="underline">notes d’application</span></a> du CIDOC CRM, si bien que les propriétés dénuées de cette mention doivent être considérées comme non transitives. </p>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<th style="width:15%"><p><em>Note de traduction</em></p>
</th>
<td colspan="1">
<p>Certains paragraphes ont été édités dans la version francophone à des fins de compréhension. Les sections concernées sont indiquées de [n.d.t. texte concerné]. </p>
</td>
</tr>
<tr>
<th style="width:15%"><p><em>Références</em></p>
</th>
<td colspan="1">
<p><em></em></p>
</td>
</tr>
</tbody>
</table>

<h3 id="des-raccourcis"><span class="en heading">Shortcuts - </span>Des raccourcis</h3>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>Some properties are declared as shortcuts of longer, more comprehensively articulated paths that connect the same domain and range classes as the shortcut property via one or more intermediate classes. For example, the property E18 Physical Thing<em>. P52 has current owner (is current owner of)</em>:<em> </em>E39 Actor, is a shortcut for a fully articulated path from E18 Physical Thing through E8 Acquisition to E39 Actor. An instance of the fully-articulated path always implies an instance of the shortcut property. However, the inverse may not be true; an instance of the fully-articulated path cannot always be inferred from an instance of the shortcut property inside the frame of the actual KB</p>
<p>The class E13 Attribute Assignment allows for the documentation of how the assignment of any property came about, and whose opinion it was, even in cases of properties not explicitly characterized as “shortcuts”. </p>
</td>
<td>
<p>Certaines <a href="/v7.1.2/information/introduction#terminologie-propriete"><span class="underline">propriétés</span></a> sont déclarées être des <a href="/v7.1.2/information/introduction#terminologie-raccourci"><span class="underline">raccourcis</span></a> de chemins sémantiques plus exhaustifs et détaillés qui relient les mêmes <a href="/v7.1.2/information/introduction#terminologie-classe"><span class="underline">classes</span></a> de <a href="/v7.1.2/information/introduction#terminologie-domaine"><span class="underline">domaine</span></a> et de <a href="/v7.1.2/information/introduction#terminologie-portee"><span class="underline">portée</span></a> que la propriété-raccourci, mais utilisent une ou plusieurs classes intermédiaires. Par exemple, la propriété <code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code>. <code class="language-plaintext highlighter-rouge">P52_a_pour_propriétaire_actuel (est_propriétaire_actuel_de)</code> : <code class="language-plaintext highlighter-rouge">E39_Actant</code> est un raccourci du chemin sémantique complet <code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code> suivi de <code class="language-plaintext highlighter-rouge">E8_Acquisition</code> et finalement <code class="language-plaintext highlighter-rouge">E39_Actant</code>. Une <a href="/v7.1.2/information/introduction#terminologie-instance"><span class="underline">instance</span></a> du chemin sémantique complet implique toujours une instance de la propriété-raccourci bien que l’inverse ne soit pas toujours vrai (c.-à-d. qu’une instance du chemin sémantique complet ne peut pas toujours être déduite d’une instance de la propriété-raccourci, en particulier dans le cadre d’une base de connaissances précise). </p>
<p>La classe <code class="language-plaintext highlighter-rouge">E13_Assignation_d'attribut</code> peut être utilisée pour documenter ce qui a mené à l’attribution d’une propriété (notamment en ce qui a trait à l’opinion du responsable qui a pris la décision de cette attribution), et ce même dans le cas de propriétés qui ne seraient pas des raccourcis. </p>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<th style="width:15%"><p><em>Note de traduction</em></p>
</th>
<td colspan="1">
</td>
</tr>
<tr>
<th style="width:15%"><p><em>Références</em></p>
</th>
<td colspan="1">
<p><em></em></p>
</td>
</tr>
</tbody>
</table>

<h3 id="des-expressions-logiques-utilisees-dans-le-cidoccrm"><span class="en heading">About the logical expressions used in the CIDOC CRM - </span>Des expressions logiques utilisées dans le CIDOC CRM</h3>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>The present CIDOC CRM specifications are annotated with logical axioms, providing an additional formal expression of the CIDOC CRM ontology. This section briefly introduces the assumptions that are at the basis of the logical expression of the CIDOC CRM (for a fully detailed account of the logical expression of semantic data modelling, see (Reiter,1984)).</p>
<p>In terms of semantic data modelling, classes and properties are used to express ontological knowledge by means of various kinds of constraints, such as sub-class/sub-property links, e.g., E21 Person<em> </em>is a sub-class of<em> </em>E20 Biological Object, or domain/range constraints, e.g., the domain of <em>P152 has parent</em> is class E21 Person<em>.</em></p>
<p>In contrast, first-order logic-based knowledge representation relies on a language for formally encoding an ontology. This language can be directly put in correspondence with semantic data modelling in a straightforward way:</p>
<ul><li><p>classes are named by <em>unary predicate symbols</em>; conventionally, we use E21 as the unary predicate symbol corresponding to class E21 Person;</p>
</li>
<li><p>properties are named by <em>binary predicate symbols</em>; conventionally, we use P152 as the binary predicate symbol corresponding to property <em>P152 has parent.</em></p>
</li>
<li><p>properties of properties, “.1 properties” are named by <em>ternary predicate symbols</em>; conventionally, we use P14.1 as the ternary predicate symbol corresponding to property <em>P14.1 in the role of.</em></p>
</li></ul>
<p><em></em></p>
<p>Ontology is expressed in logic by means of <em>logical axioms</em>, which correspond to the constraints of semantic modelling. In the definition of classes and properties of the CIDOC CRM the axioms are placed under the heading ‘In first order logic’. There are several options for writing statements in first order logic. In this document we use a standard compact notation widely used in text books and scientific papers. The definition is given in the table below.</p>
</td>
<td>
<p>Les définitions du CIDOC CRM sont annotées d’axiomes qui fournissent de l’information sur l’expression formelle de l’ontologie. Cette section introduit les assomptions qui sous-tendent l’expression logique du CIDOC CRM (pour une revue détaillée de l’expression logique de la modélisation sémantique de données, voir (Reiter, 1984)). </p>
<p>En termes de modélisation de données sémantiques, les classes et propriétés sont utilisées pour exprimer des connaissances ontologiques par le biais de contraintes telles que des liens de <a href="/v7.1.2/information/introduction#terminologie-sous-classe"><span class="underline">sous-classe</span></a>/<a href="/v7.1.2/information/introduction#terminologie-sous-propriete"><span class="underline">sous-propriété</span></a> (p. ex. <code class="language-plaintext highlighter-rouge">E21_Personne</code> est une sous-classe de <code class="language-plaintext highlighter-rouge">E20_Objet_biologique</code>) ou des contraintes de <a href="/v7.1.2/information/introduction#terminologie-domaine"><span class="underline">domaine</span></a>/<a href="/v7.1.2/information/introduction#terminologie-portee"><span class="underline">portée</span></a> (p. ex. le domaine de <code class="language-plaintext highlighter-rouge">P152_a_pour_parent</code> est la classe <code class="language-plaintext highlighter-rouge">E21_Personne</code>). </p>
<p>Au contraire, la représentation de connaissances sous forme de logique du premier ordre repose sur un langage permettant d’encoder de manière formelle une ontologie. Ce langage peut être mis en correspondance directe avec la modélisation sémantique de données : </p>
<ul><li><p>les classes sont nommées par des <em>symboles de prédicats unaires</em>; par convention, « E21 » est le symbole de prédicat unaire correspondant à la classe <code class="language-plaintext highlighter-rouge">E21_Personne</code>;</p>
</li>
<li><p>les propriétés sont nommées par des <em>symboles de prédicats binaires</em>; par convention, « P152 » est le symbole de prédicat binaire correspondant à la propriété <code class="language-plaintext highlighter-rouge">P152_a_pour_parent</code>;</p>
</li>
<li><p>les propriétés de propriétés « propriétés .1 » sont nommées par des symboles de prédicats ternaires; par convention « P14.1 » est le symbole de prédicat ternaire correspondant à la propriété <code class="language-plaintext highlighter-rouge">P14.1_dans_le_rôle_de</code>.</p>
</li></ul>
<p>L’ontologie est exprimée logiquement par le biais d’axiomes qui correspondent aux contraintes de la modélisation sémantique. Dans la définition des classes et propriétés de CIDOC CRM, les axiomes sont énoncés dans la section « Logique ». Plusieurs options sont possibles lorsque vient le temps de rédiger des énoncés sous une forme de logique du premier ordre; ce document privilégie une notation compacte standard utilisée dans plusieurs ouvrages et articles scientifiques. Les définitions [n.d.t. pertinentes] sont présentées dans le tableau ci-dessous. </p>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<th style="width:15%"><p><em>Note de traduction</em></p>
</th>
<td colspan="1">
<p>Le terme « assomption » est peu courant, mais est préféré dans un contexte logique ou mathématique, raison pour laquelle il a été utilisé plutôt que « supposition » ou « hypothèse”. </p>
</td>
</tr>
<tr>
<th style="width:15%"><p><em>Références</em></p>
</th>
<td colspan="1">
<p><em></em></p>
</td>
</tr>
</tbody>
</table>

<table class="original-table" id="table-1">
<tbody>
<tr>
<td class="en">
<p><strong>Symbol</strong></p>
</td>
<td class="en">
<p><strong>Name</strong></p>
</td>
<td class="en">
<p><strong>reads</strong></p>
</td>
<td class="en">
<p><strong>Truth value</strong></p>
</td>
<td>
<p><strong>Symbole</strong></p>
</td>
<td>
<p><strong>Nom</strong></p>
</td>
<td>
<p><strong>Lecture</strong></p>
</td>
<td>
<p><strong>Valeur de vérité </strong></p>
</td>
</tr>
<tr>
<td class="en">
<p><em>Operators</em><em></em></p>
</td>
<td class="en">
</td>
<td class="en">
</td>
<td class="en">
</td>
<td>
<p><em>Opérateurs</em><em></em></p>
</td>
<td>
</td>
<td>
</td>
<td>
</td>
</tr>
<tr>
<td class="en">
<p>∧</p>
</td>
<td class="en">
<p>conjunction</p>
</td>
<td class="en">
<p>and</p>
</td>
<td class="en">
<p>(φ ∧ ψ) is true</p>
<p>if and only if both <em>φ</em> and <em>ψ</em> are true</p>
</td>
<td>
<p>∧</p>
</td>
<td>
<p>conjonction</p>
</td>
<td>
<p>et</p>
</td>
<td>
<p>(φ ∧ ψ) est vrai si et seulement si à la fois <em>φ</em> et <em>ψ</em> sont vrais</p>
</td>
</tr>
<tr>
<td class="en">
<p>∨</p>
</td>
<td class="en">
<p>disjunction</p>
</td>
<td class="en">
<p>or</p>
</td>
<td class="en">
<p>(φ ∨ ψ) is true</p>
<p>if and only if at least one of either φ or ψ is true</p>
</td>
<td>
<p>∨</p>
</td>
<td>
<p>disjonction</p>
</td>
<td>
<p>ou</p>
</td>
<td>
<p>(φ ∨ ψ) est vrai si et seulement si l’un de φ ou ψ est vrai</p>
</td>
</tr>
<tr>
<td class="en">
<p>¬</p>
</td>
<td class="en">
<p>negation</p>
</td>
<td class="en">
<p>not</p>
</td>
<td class="en">
<p>¬φ is true if and only if <em>φ</em> is false</p>
</td>
<td>
<p>¬</p>
</td>
<td>
<p>négation</p>
</td>
<td>
<p>non</p>
</td>
<td>
<p>¬φ est vrai si et seulement si <em>φ</em> est faux</p>
</td>
</tr>
<tr>
<td class="en">
<p>⇒</p>
</td>
<td class="en">
<p>implication</p>
</td>
<td class="en">
<p>implies,</p>
<p>if … then ...</p>
</td>
<td class="en">
<p>(φ ⇒ ψ) is true </p>
<p>if and only if it is not the case that <em>φ</em> is true and <em>ψ</em> is false</p>
</td>
<td>
<p>⇒</p>
</td>
<td>
<p>implication</p>
</td>
<td>
<p>implique que, </p>
<p>si… alors ...</p>
</td>
<td>
<p>(φ ⇒ ψ) est vrai si et seulement si ce n’est pas le cas que <em>φ</em> est vrai et <em>ψ</em> est faux</p>
</td>
</tr>
<tr>
<td class="en">
<p>⇔</p>
</td>
<td class="en">
<p>equivalence</p>
</td>
<td class="en">
<p>is equivalent to, </p>
<p>if … and only if …</p>
</td>
<td class="en">
<p>φ ⇔ ψ is true</p>
<p>if and only if both <em>φ</em> and <em>ψ</em> are true or both φ and ψ are false  </p>
</td>
<td>
<p>⇔</p>
</td>
<td>
<p>équivalence</p>
</td>
<td>
<p>est équivalent à, </p>
<p>is … et seulement si ...</p>
</td>
<td>
<p>φ ⇔ ψ est vrai si et seulement si à la fois <em>φ</em> et <em>ψ</em> sont vrais ou qu’à la fois φ et ψ sont faux  </p>
</td>
</tr>
<tr>
<td class="en">
<p><em>Quantifiers</em><em></em></p>
</td>
<td class="en">
</td>
<td class="en">
</td>
<td class="en">
</td>
<td>
<p><a href="/v7.1.2/information/introduction#terminologie-quantificateurs-de-propriete"><span class="underline"><em>Quantificateurs</em></span></a><em></em></p>
</td>
<td>
</td>
<td>
</td>
<td>
</td>
</tr>
<tr>
<td class="en">
<p>∃</p>
</td>
<td class="en">
<p>existential quantifier</p>
</td>
<td class="en">
<p>exists, </p>
<p>there exists at least one</p>
</td>
<td class="en">
</td>
<td>
<p>∃</p>
</td>
<td>
<p>quantificateur existentiel</p>
</td>
<td>
<p>existe, </p>
<p>il existe au moins un</p>
</td>
<td>
</td>
</tr>
<tr>
<td class="en">
<p>∀</p>
</td>
<td class="en">
<p>Universal quantifier</p>
</td>
<td class="en">
<p>forall, </p>
<p>for all </p>
</td>
<td class="en">
</td>
<td>
<p>∀</p>
</td>
<td>
<p>quantificateur universel</p>
</td>
<td>
<p>pour tous</p>
</td>
<td>
</td>
</tr>
</tbody>
</table>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>For instance, the above sub-class link between E21 Person<em> </em>and<em> </em>E20 Biological Object can be formulated in first order logic as the axiom:</p>
<p>(∀x) [E21(x) ⇒E20(x)]</p>
<p>(reading: for all individuals x, if x is a E21 then x is an E20). </p>
<p>In the definitions of classes and properties in this document the universal quantifier(s) are omitted for simplicity, so the above axiom is simply written:</p>
<p>E21(x) ⇒E20(x)</p>
<p>Likewise, the above domain constraint on property <em>P152 has parent </em>can be formulated in first order logic as the axiom:</p>
<p>P152(x,y) ⇒E21(x)</p>
<p>(reading: for all individuals x and y, if x is a P152 of y, then x is an E21).</p>
<p>Properties of properties, indicated by a '.1' after the property number are described as ternary predicate symbols. For example,  the property P14.1 <em>in the role of</em>  is described as the ternary predicate symbol corresponding to property P14 carried out by (performed) :</p>
<p>P14(x,y) ⇒ E7(x)</p>
<p>P14(x,y)⇒ E39(y)</p>
<p>P14(x,y,z) ⇒ [P14(x,y) ∧ E55(z)]</p>
<p>These basic considerations should be used by the reader to understand the logical axioms that are used into the definition of the classes and properties. Further information about the first order formulation of CIDOC CRM can be found in (Meghini & Doerr, 2018)</p>
</td>
<td>
<p>Le lien de sous-classe susmentionné entre <code class="language-plaintext highlighter-rouge">E21_Personne</code> et <code class="language-plaintext highlighter-rouge">E20_Objet_biologique</code> peut être formulé, en logique du premier ordre, par l’axiome suivant : </p>
<p>(∀x) [E21(x) ⇒E20(x)]</p>
<p>(à savoir : pour tout individu x, si x est un E21 alors x est un E20). </p>
<p>Dans la définition des <a href="/v7.1.2/information/introduction#terminologie-classe"><span class="underline">classes</span></a> et <a href="/v7.1.2/information/introduction#terminologie-propriete"><span class="underline">propriétés</span></a> de ce document le(s) <a href="/v7.1.2/information/introduction#terminologie-quantificateurs-de-propriete"><span class="underline">quantificateur</span></a>(s) universel(s) sont omis par soucis de simplicité, de sorte que cet axiome prend la forme suivante :</p>
<p>E21(x) ⇒E20(x)</p>
<p>De la même manière, la contrainte du <a href="/v7.1.2/information/introduction#terminologie-domaine"><span class="underline">domaine</span></a> de la propriété <code class="language-plaintext highlighter-rouge">P152_a_pour_parent</code> peut être formulée, en logique du premier ordre, par l’axiome suivant : </p>
<p>P152(x,y) ⇒E21(x)</p>
<p>(à savoir : pour tous les individus x et y, si x est un P152 de y, alors x est un E21).</p>
<p>Les propriétés de propriétés « propriété .1 » sont nommées par des symboles de prédicats ternaires; par convention la propriété  <code class="language-plaintext highlighter-rouge">P14.1_dans_le_rôle_de</code> est décrite comme le symbole de prédicat ternaire correspondant à la propriété<code class="language-plaintext highlighter-rouge"> P14_a_été_effectué_par (a_effectué)</code> : </p>
<p>P14(x,y) ⇒ E7(x)</p>
<p>P14(x,y)⇒ E39(y)</p>
<p>P14(x,y,z) ⇒ [P14(x,y) ∧ E55(z)]</p>
<p>Ceci devrait être utilisé par le lecteur afin de comprendre les axiomes utilisés dans la définition des classes et des propriétés. (Meghini & Doerr, 2018) offrent plus d’informations sur la formulation de logique du premier ordre dans le CIDOC CRM. </p>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<th style="width:15%"><p><em>Note de traduction</em></p>
</th>
<td colspan="1">
<p>Les termes « quantifiant » ou « quantificateur » peuvent tous deux être utilisés pour désigner des « quantifiers”, la seconde option a été privilégiée pour éviter toute confusion avec le gérondif. </p>
</td>
</tr>
<tr>
<th style="width:15%"><p><em>Références</em></p>
</th>
<td colspan="1">
<p>Termium. « quantifier ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=quantifier&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=quantifier&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=quantifier&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
</td>
</tr>
</tbody>
</table>

<h3 id="quantificateurs-de-proprietes"><span class="en heading">Property Quantifiers - </span>Quantificateurs de propriétés</h3>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>Quantifiers for properties are provided for the purpose of semantic clarification only, and should <strong>not</strong> be treated as implementation recommendations. The CIDOC CRM has been designed to accommodate alternative opinions and incomplete information, and therefore <strong>all</strong> properties should be implemented as optional and repeatable for their domain and range (“many to many (0,n:0,n)”). Therefore, the term “cardinality constraints” is avoided here, as it typically pertains to implementations. <strong></strong></p>
<p>The following table lists all possible property quantifiers occurring in this document by their notation, together with an explanation in plain words. In order to provide optimal clarity, two widely accepted notations are used redundantly in this document, a verbal and a numeric one. The verbal notation uses phrases such as “one to many”, and the numeric one, expressions such as “(0,n:0,1)”. While the terms “one”, “many” and “necessary” are quite intuitive, the term “dependent” denotes a situation where a range instance cannot exist without an instance of the respective property. In other words, the property is “necessary” for its range. (Meghini, C. & Doerr, M., 2018)</p>
</td>
<td>
<p>Les quantificateurs des propriétés sont présentés ici à des fins de clarification sémantique seulement et ne devraient <strong>pas</strong> être considérés comme des recommandations d’implémentation. Le CIDOC CRM a été conçu afin d'accommoder des options alternatives ou des informations incomplètes [n.d.t. afin d’accommoder plusieurs interprétations ou compréhensions d’un même phénomène], de sorte que <strong>toutes</strong> les <a href="/v7.1.2/information/introduction#terminologie-propriete"><span class="underline">propriétés</span></a> devraient être implémentées avec un <a href="/v7.1.2/information/introduction#terminologie-domaine"><span class="underline">domaine</span></a> et une <a href="/v7.1.2/information/introduction#terminologie-portee"><span class="underline">portée</span></a> optionnels et répétables [n.d.t. c.-à-d. qu’une même propriété peut être utilisée à plusieurs reprises avec de mêmes instances de son domaine et de sa portée] (« relation plusieurs-à-plusieurs (0,n:0,n) »). [n.d.t. Cette question des contraintes de cardinalité, qui précise les principes de généralisation d’une <a href="/v7.1.2/information/introduction#terminologie-classe"><span class="underline">classe</span></a>], porte généralement sur les implémentations d’un système [n.d.t. plutôt que sur sa conception], de sorte qu’il n’en est pas exhaustivement question ici et que l’expression « contraintes de cardinalité » n'est pas préconisée. </p>
<p>Le tableau suivant énumère les quantificateurs de propriété utilisés dans ce document (dans l’ordre de leur notation) ainsi qu’une explication en langage naturel [n.d.t. de chacun d’entre eux]. Les notations verbale et numérique sont juxtaposées dans ce document à des fins de clarté : la notation verbale utilise des syntagmes tels que « un à plusieurs » alors que la notation numérique utilise des expressions telles que « (0,n:0,1) ». Les termes « un », « plusieurs » et « nécessaire » [n.d.t. revêtent leur sens habituel et] intuitif; le terme « dépendant » indique une situation où une <a href="/v7.1.2/information/introduction#terminologie-instance"><span class="underline">instance</span></a> de la portée d’une propriété ne peut pas exister sans une instance de cette propriété elle-même. En d’autres termes, la propriété est « nécessaire » à sa portée (Meghini, C. & Doerr, M., 2018).</p>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<th style="width:15%"><p><em>Note de traduction</em></p>
</th>
<td colspan="1">
<p>Certains paragraphes ont été édités dans la version francophone à des fins de compréhension. Les sections concernées sont indiquées de [n.d.t. texte concerné]. </p>
<p>Un contrainte de cardinalité précise si une entité parent peut appartenir à plusieurs entités enfants (principe du recouvrement ou <em>overlapping</em>) ou à un seul (principe de la disjonction). </p>
</td>
</tr>
<tr>
<th style="width:15%"><p><em>Références</em></p>
</th>
<td colspan="1">
<p>Termium. « cardinalité ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=cardinalit%C3%A9&index=frt&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=cardinalit%C3%A9&index=frt&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=cardinalit%C3%A9&index=frt&codom2nd_wet=1#resultrecs</span></a>.</p>
</td>
</tr>
</tbody>
</table>

<table class="original-table">
<tbody>
<tr>
<td class="en">
<p><strong>many to many (0,n:0,n)</strong></p>
<p><em></em></p>
</td>
<td class="en">
<p>Unconstrained: An individual domain instance and range instance of this property can have zero, one or more instances of this property. In other words, this property is optional and repeatable for its domain and range.  </p>
</td>
<td>
<p><strong>plusieurs à plusieurs (0,n:0,n)</strong></p>
<p><strong></strong></p>
</td>
<td>
<p>Illimité : Une <a href="/v7.1.2/information/introduction#terminologie-instance"><span class="underline">instance</span></a> du <a href="/v7.1.2/information/introduction#terminologie-domaine"><span class="underline">domaine</span></a> et une instance de la <a href="/v7.1.2/information/introduction#terminologie-portee"><span class="underline">portée</span></a> de cette <a href="/v7.1.2/information/introduction#terminologie-propriete"><span class="underline">propriété</span></a> peuvent n’avoir aucune, une ou plusieurs instances de cette propriété. En d’autres termes, cette propriété est optionnelle et répétable [n.d.t. c.-à-d. qu’une même propriété peut être utilisée à plusieurs reprises avec de mêmes instances de] son domaine et de sa portée. </p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
<p>Une propriété répétable est une propriété pouvant apparaître plus d'une fois dans un enregistrement avec le(s) même(s) domaine et/ou portée. </p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Termium. « répétable ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE</span></a>.</p>
</td>
</tr>
<tr>
<td class="en">
<p><strong>one to many</strong></p>
<p><strong>(0,n:0,1)</strong></p>
<p><em></em></p>
</td>
<td class="en">
<p>An individual domain instance of this property can have zero, one or more instances of this property, but an individual range instance cannot be referenced by more than one instance of this property. In other words, this property is optional for its domain and range, but repeatable for its domain only. In some contexts, this situation is called a “fan-out”.</p>
</td>
<td>
<p><strong>un à plusieurs</strong></p>
<p><strong>(0,n:0,1)</strong></p>
</td>
<td>
<p>Une <a href="/v7.1.2/information/introduction#terminologie-instance"><span class="underline">instance</span></a> individuelle du <a href="/v7.1.2/information/introduction#terminologie-domaine"><span class="underline">domaine</span></a> de cette <a href="/v7.1.2/information/introduction#terminologie-propriete"><span class="underline">propriété</span></a> peut n’avoir aucune, une ou plusieurs instance(s) de cette propriété, mais une instance individuelle de sa <a href="/v7.1.2/information/introduction#terminologie-portee"><span class="underline">portée</span></a> ne peut pas faire l’objet d’une référence par plus d’une instance de cette même propriété. En d’autres termes, le domaine et la portée de cette propriété sont optionnels, mais seul son domaine est répétable [n.d.t. c.-à-d. qu’une même propriété peut être utilisée à plusieurs reprises avec une même instance de son domaine]. Cette situation est parfois qualifiée de « sortance ». </p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
<p>Une propriété répétable est une propriété pouvant apparaître plus d'une fois dans un enregistrement avec le(s) même(s) domaine et/ou portée. </p>
<p>Une recherche sommaire indique que le terme « fan-out » est surtout usité dans le domaine des circuits booléens et de l’intelligence artificielle, où il est parfois question d’arité sortante ou de sortance. </p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Termium. « fan-out ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-out&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-out&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-out&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
<p>———. « répétable ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE</span></a>.</p>
<p>Wikipédia. « Fan-out ». Dans <em>Wikipédia</em>. San Francisco, US-CA: Wikipédia, 11 novembre 2020.<a href="https://fr.wikipedia.org/w/index.php?title=Fan-out&oldid=176479075"><span class="underline"> </span></a><a href="https://fr.wikipedia.org/w/index.php?title=Fan-out&oldid=176479075"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Fan-out&oldid=176479075</span></a>.</p>
</td>
</tr>
<tr>
<td class="en">
<p><strong>many to one</strong></p>
<p><strong>(0,1:0,n)</strong></p>
<p><em></em></p>
</td>
<td class="en">
<p>An individual domain instance of this property can have zero or one instance of this property, but an individual range instance can be referenced by zero, one or more instances of this property. In other words, this property is optional for its domain and range, but repeatable for its range only. In some contexts, this situation is called a “fan-in”.</p>
</td>
<td>
<p><strong>plusieurs à un</strong></p>
<p><strong>(0,1:0,n)</strong></p>
</td>
<td>
<p>Une <a href="/v7.1.2/information/introduction#terminologie-instance"><span class="underline">instance</span></a> du <a href="/v7.1.2/information/introduction#terminologie-domaine"><span class="underline">domaine</span></a> de cette <a href="/v7.1.2/information/introduction#terminologie-propriete"><span class="underline">propriété</span></a> peut n’avoir aucune ou une seule instance de cette propriété, mais une instance de sa <a href="/v7.1.2/information/introduction#terminologie-portee"><span class="underline">portée</span></a> peut être référencée par aucune, une ou plusieurs instances de cette même propriété. En d’autres termes, le domaine et la portée de cette propriété sont optionnels, mais seule sa portée est répétable [n.d.t. c.-à-d. qu’une même propriété peut être utilisée à plusieurs reprises avec une même instance de sa portée]. Cette situation est parfois qualifiée d’« entrance ». </p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
<p>Une propriété répétable est une propriété pouvant apparaître plus d'une fois dans un enregistrement avec le(s) même(s) domaine et/ou portée. </p>
<p>Une recherche sommaire indique que le terme « fan-in » est surtout usité dans le domaine des circuits booléens et de l’intelligence artificielle où il est parfois question d’arité entrante ou d’entrance. </p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Termium. « fan-in ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
<p>———. « répétable ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE</span></a>.</p>
<p>Wikipédia. « Fan-in ». Dans <em>Wikipédia</em>. San Francisco, US-CA: Wikipédia, 11 novembre 2020.<a href="https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056"><span class="underline"> </span></a><a href="https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056</span></a>.</p>
</td>
</tr>
<tr>
<td class="en">
<p><strong>many to many, necessary (1,n:0,n)</strong><em></em></p>
</td>
<td class="en">
<p>An individual domain instance of this property can have one or more instances of this property, but an individual range instance can have zero, one or more instances of this property. In other words, this property is necessary and repeatable for its domain, and optional and repeatable for its range. </p>
</td>
<td>
<p><strong>plusieurs à plusieurs, nécessaire (1,n:0,n)</strong><em></em></p>
</td>
<td>
<p>Une <a href="/v7.1.2/information/introduction#terminologie-instance"><span class="underline">instance</span></a> individuelle du <a href="/v7.1.2/information/introduction#terminologie-domaine"><span class="underline">domaine</span></a> de cette <a href="/v7.1.2/information/introduction#terminologie-propriete"><span class="underline">propriété</span></a> peut avoir une ou plusieurs instance(s) de cette propriété, mais une instance individuelle de sa <a href="/v7.1.2/information/introduction#terminologie-portee"><span class="underline">portée</span></a> peut n’avoir aucune, une ou plusieurs instances de cette même propriété. En d’autres termes, le domaine de cette propriété est nécessaire et répétable [n.d.t. c.-à-d. qu’une même propriété peut être utilisée à plusieurs reprises avec une même instance de son domaine] alors que sa portée est optionnelle et répétable [n.d.t. c.-à-d. qu’une même propriété peut être utilisée à plusieurs reprises avec une même instance de sa portée]. </p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p><em></em></p>
</td>
</tr>
<tr>
<td class="en">
<p><strong>one to many, necessary </strong></p>
<p><strong>(1,n:0,1)</strong></p>
<p><em></em></p>
</td>
<td class="en">
<p>An individual domain instance of this property can have one or more instances of this property, but an individual range instance cannot be referenced by more than one instance of this property. In other words, this property is necessary and repeatable for its domain, and optional but not repeatable for its range. In some contexts, this situation is called a “fan-out”.</p>
</td>
<td>
<p><strong>un à plusieurs, nécessaire </strong></p>
<p><strong>(1,n:0,1)</strong></p>
</td>
<td>
<p>Une <a href="/v7.1.2/information/introduction#terminologie-instance"><span class="underline">instance</span></a> individuelle du <a href="/v7.1.2/information/introduction#terminologie-domaine"><span class="underline">domaine</span></a> de cette <a href="/v7.1.2/information/introduction#terminologie-propriete"><span class="underline">propriété</span></a> peut n’avoir qu’une seule ou plusieurs instance(s) de cette propriété, mais une instance individuelle de sa <a href="/v7.1.2/information/introduction#terminologie-portee"><span class="underline">portée</span></a> ne peut pas être référencée par plus d’une instance de cette même propriété. En d’autres termes, le domaine de cette propriété est nécessaire et répétable [n.d.t. c.-à-d. qu’une même propriété peut être utilisée à plusieurs reprises avec une même instance de son domaine], mais sa portée est optionnelle. Dans certains contextes, cette situation est qualifiée de « sortance ».</p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
<p>Une propriété répétable est une propriété pouvant apparaître plus d'une fois dans un enregistrement avec le(s) même(s) domaine et/ou portée. </p>
<p>Une recherche sommaire indique que le terme « fan-out » est surtout usité dans le domaine des circuits booléens et de l’intelligence artificielle, où il est parfois question d’arité sortante ou de sortance. </p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Termium. « fan-out ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-out&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-out&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-out&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
<p>———. « répétable ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE</span></a>.</p>
<p>Wikipédia. « Fan-out ». Dans <em>Wikipédia</em>. San Francisco, US-CA: Wikipédia, 11 novembre 2020.<a href="https://fr.wikipedia.org/w/index.php?title=Fan-out&oldid=176479075"><span class="underline"> </span></a><a href="https://fr.wikipedia.org/w/index.php?title=Fan-out&oldid=176479075"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Fan-out&oldid=176479075</span></a>.</p>
</td>
</tr>
<tr>
<td class="en">
<p><strong>many to one, necessary (1,1:0,n)</strong></p>
</td>
<td class="en">
<p>An individual domain instance of this property must have exactly one instance of this property, but an individual range instance can be referenced by zero, one or more instances of this property. In other words, this property is necessary and not repeatable for its domain, and optional and repeatable for its range. In some contexts, this situation is called a “fan-in”.</p>
</td>
<td>
<p><strong>plusieurs à un, nécessaire (1,1:0,n)</strong></p>
</td>
<td>
<p>Une <a href="/v7.1.2/information/introduction#terminologie-instance"><span class="underline">instance</span></a> du <a href="/v7.1.2/information/introduction#terminologie-domaine"><span class="underline">domaine</span></a> de cette <a href="/v7.1.2/information/introduction#terminologie-propriete"><span class="underline">propriété</span></a> peut n’avoir qu’une seule instance de cette propriété, mais une instance de sa <a href="/v7.1.2/information/introduction#terminologie-portee"><span class="underline">portée</span></a> peut être référencée par aucune, une ou plusieurs instances de cette même propriété. En d’autres termes, le domaine de cette propriété est nécessaire et non répétable [n.d.t. c.-à-d. qu’une même propriété ne peut être utilisée qu'une seule fois avec une instance spécifique de son domaine], mais sa portée est optionnelle et répétable [n.d.t. c.-à-d. qu’une même propriété peut être utilisée à plusieurs reprises avec une même instance de sa portée]. Cette situation est parfois qualifiée d’« entrance ».  </p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
<p>Une propriété répétable est une propriété pouvant apparaître plus d'une fois dans un enregistrement avec le(s) même(s) domaine et/ou portée.  </p>
<p>Une recherche sommaire indique que le terme « fan-in » est surtout usité dans le domaine des circuits booléens et de l’intelligence artificielle, où il est parfois question d’arité entrante ou d’entrance. </p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Termium. « fan-in ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
<p>———. « répétable ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE</span></a>.</p>
<p>Wikipédia. « Fan-in ». Dans <em>Wikipédia</em>. San Francisco, US-CA: Wikipédia, 11 novembre 2020.<a href="https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056"><span class="underline"> </span></a><a href="https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056</span></a>.</p>
</td>
</tr>
<tr>
<td class="en">
<p><strong>one to many, dependent</strong></p>
<p><strong>(0,n:1,1)</strong></p>
</td>
<td class="en">
<p>An individual domain instance of this property can have zero, one or more instances of this property, but an individual range instance must be referenced by exactly one instance of this property. In other words, this property is optional and repeatable for its domain, but necessary and not repeatable for its range. In some contexts, this situation is called a “fan-out”.</p>
</td>
<td>
<p><strong>un à plusieurs, dépendant</strong></p>
<p><strong>(0,n:1,1)</strong></p>
</td>
<td>
<p>Une <a href="/v7.1.2/information/introduction#terminologie-instance"><span class="underline">instance</span></a> individuelle du <a href="/v7.1.2/information/introduction#terminologie-domaine"><span class="underline">domaine</span></a> de cette <a href="/v7.1.2/information/introduction#terminologie-propriete"><span class="underline">propriété</span></a> peut n’avoir aucune, une ou plusieurs instance(s) de cette propriété, mais une instance individuelle de sa <a href="/v7.1.2/information/introduction#terminologie-portee"><span class="underline">portée</span></a> ne doit être référencée que par une seule instance de cette même propriété. En d’autres termes, le domaine de cette propriété est optionnel et répétable [n.d.t. c.-à-d. qu’une même propriété peut être utilisée à plusieurs reprises avec une même instance de son domaine], mais sa portée est nécessaire et non répétable [n.d.t. c.-à-d. qu’une même propriété ne peut être utilisée qu'une seule fois avec une instance spécifique de sa portée]. Cette situation est parfois qualifiée de « sortance ». <code class="language-plaintext highlighter-rouge"></code></p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
<p>Une propriété répétable est une propriété pouvant apparaître plus d'une fois dans un enregistrement avec le(s) même(s) domaine et/ou portée. </p>
<p>Une recherche sommaire indique que le terme « fan-out » est surtout usité dans le domaine des circuits booléens et de l’intelligence artificielle où il est parfois question d’arité sortante ou de sortance. </p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Termium. « fan-out ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-out&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-out&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-out&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
<p>———. « répétable ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE</span></a>.</p>
<p>Wikipédia. « Fan-out ». Dans <em>Wikipédia</em>. San Francisco, US-CA: Wikipédia, 11 novembre 2020.<a href="https://fr.wikipedia.org/w/index.php?title=Fan-out&oldid=176479075"><span class="underline"> </span></a><a href="https://fr.wikipedia.org/w/index.php?title=Fan-out&oldid=176479075"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Fan-out&oldid=176479075</span></a>.</p>
</td>
</tr>
<tr>
<td class="en">
<p><strong>one to many, necessary, dependent </strong></p>
<p><strong>(1,n:1,1)</strong></p>
<p><em></em></p>
</td>
<td class="en">
<p>An individual domain instance of this property can have one or more instances of this property, but an individual range instance must be referenced by exactly one instance of this property. In other words, this property is necessary and repeatable for its domain, and necessary but not repeatable for its range. In some contexts, this situation is called a “fan-out”.</p>
</td>
<td>
<p><strong>un à plusieurs, </strong></p>
<p><strong>nécessaire, dépendant</strong></p>
<p><strong>(1,n:1,1)</strong></p>
</td>
<td>
<p>Une <a href="/v7.1.2/information/introduction#terminologie-instance"><span class="underline">instance</span></a> individuelle du <a href="/v7.1.2/information/introduction#terminologie-domaine"><span class="underline">domaine</span></a> de cette <a href="/v7.1.2/information/introduction#terminologie-propriete"><span class="underline">propriété</span></a> peut n’avoir qu’une seule ou plusieurs instance(s) de cette propriété, mais une instance individuelle de sa <a href="/v7.1.2/information/introduction#terminologie-portee"><span class="underline">portée</span></a> ne doit être référencée que par une seule instance de cette même propriété. En d’autres termes, le domaine de cette propriété est nécessaire et répétable [n.d.t. c.-à-d. qu’une même propriété peut être utilisée à plusieurs reprises avec une même instance de son domaine] et sa portée est nécessaire mais non répétable [n.d.t. c.-à-d. qu’une même propriété ne peut être utilisée qu'une seule fois avec une instance spécifique de sa portée]. Cette situation est parfois qualifiée de « sortance ».</p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
<p>Une propriété répétable est une propriété pouvant apparaître plus d'une fois dans un enregistrement avec le(s) même(s) domaine et/ou portée. </p>
<p>Une recherche sommaire indique que le terme « fan-in » est surtout usité dans le domaine des circuits booléens et de l’intelligence artificielle, où il est parfois question d’arité entrante ou d’entrance.  </p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Termium. « fan-in ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
<p>———. « répétable ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE</span></a>.</p>
<p>Wikipédia. « Fan-in ». Dans <em>Wikipédia</em>. San Francisco, US-CA: Wikipédia, 11 novembre 2020.<a href="https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056"><span class="underline"> </span></a><a href="https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056</span></a>.</p>
</td>
</tr>
<tr>
<td class="en">
<p><strong>many to one, necessary, dependent </strong></p>
<p><strong>(1,1:1,n)</strong></p>
</td>
<td class="en">
<p>An individual domain instance of this property must have exactly one instance of this property, but an individual range instance can be referenced by one or more instances of this property. In other words, this property is necessary and not repeatable for its domain, and necessary and repeatable for its range. In some contexts, this situation is called a “fan-in”.</p>
</td>
<td>
<p><strong>plusieurs à un, nécessaire, </strong></p>
<p><strong>dépendant</strong></p>
<p><strong>(1,1:1,n)</strong></p>
</td>
<td>
<p>Une <a href="/v7.1.2/information/introduction#terminologie-instance"><span class="underline">instance</span></a> individuelle du <a href="/v7.1.2/information/introduction#terminologie-domaine"><span class="underline">domaine</span></a> de cette <a href="/v7.1.2/information/introduction#terminologie-propriete"><span class="underline">propriété</span></a> doit n’avoir qu’une seule instance de cette propriété, mais une instance individuelle de sa <a href="/v7.1.2/information/introduction#terminologie-portee"><span class="underline">portée</span></a> peut être référencée par une ou plusieurs instances de cette même propriété. En d'autres termes, le domaine de cette propriété est nécessaire et non répétable [n.d.t. c.-à-d. qu’une même propriété ne peut être utilisée qu'une seule fois avec une instance spécifique de son domaine], tandis que la portée est nécessaire et répétable [n.d.t. c.-à-d. qu’une même propriété peut être utilisée à plusieurs reprises avec une même instance de sa portée]. Cette situation est parfois qualifiée d’« entrance ». </p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
<p>Une propriété répétable est une propriété pouvant apparaître plus d'une fois dans un enregistrement avec le(s) même(s) domaine et/ou portée. </p>
<p>Une recherche sommaire indique que le terme « fan-in » est surtout usité dans le domaine des circuits booléens et de l’intelligence artificielle, où il est parfois question d’arité entrante ou d’entrance. </p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Termium. « fan-in ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
<p>———. « répétable ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE</span></a>.</p>
<p>Wikipédia. « Fan-in ». Dans <em>Wikipédia</em>. San Francisco, US-CA: Wikipédia, 11 novembre 2020.<a href="https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056"><span class="underline"> </span></a><a href="https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056</span></a>.</p>
</td>
</tr>
<tr>
<td class="en">
<p><strong>one to one</strong></p>
<p><strong>(1,1:1,1)</strong></p>
</td>
<td class="en">
<p>An individual domain instance and range instance of this property must have exactly one instance of this property. In other words, this property is necessary and not repeatable for its domain and for its range. </p>
</td>
<td>
<p><strong>un à un</strong></p>
<p><strong>(1,1:1,1)</strong></p>
</td>
<td>
<p>Une <a href="/v7.1.2/information/introduction#terminologie-instance"><span class="underline">instance</span></a> individuelle du <a href="/v7.1.2/information/introduction#terminologie-domaine"><span class="underline">domaine</span></a> et une instance de la <a href="/v7.1.2/information/introduction#terminologie-portee"><span class="underline">portée</span></a> de cette <a href="/v7.1.2/information/introduction#terminologie-propriete"><span class="underline">propriété</span></a> doivent avoir exactement une instance de cette propriété. En d’autres termes, le domaine et la portée de cette propriété sont nécessaires et non répétables [n.d.t. c.-à-d. qu’une même propriété ne peut être utilisée qu’une seule fois avec une instance spécifique de son domaine et une instance spécifique de sa portée]. </p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
<p>Une propriété répétable est une propriété pouvant apparaître plus d'une fois dans un enregistrement avec le(s) même(s) domaine et/ou portée. </p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Termium. « répétable ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE</span></a>.</p>
</td>
</tr>
</tbody>
</table>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>The CIDOC CRM defines some dependencies between properties and the classes that are their domains or ranges. These can be one or both of the following:</p>
<ul><li><p>the property is necessary for the domain</p>
</li>
<li><p>the property is necessary for the range, or, in other words, the range is dependent on the property.</p>
</li></ul>
<p>The possible kinds of dependencies are defined in the table above. Note that if a dependent property is not specified for an instance of the respective domain or range, it means that the property exists, but the value on one side of the property is unknown. In the case of optional properties, the methodology proposed by the CIDOC CRM does not distinguish between a value being unknown or the property not being applicable at all. For example, one may know that an object has an owner, but the owner is unknown. In a CIDOC CRM instance this case cannot be distinguished from the fact that the object has no owner at all. Of course, such details can always be specified by a textual note. </p>
<p>Note that the quantification of all properties of properties, “.1” properties, is “many-to-many” and, therefore, does not appear explicitly in their definitions. </p>
</td>
<td>
<p>Le CIDOC CRM définit certains dépendants entre les <a href="/v7.1.2/information/introduction#terminologie-propriete"><span class="underline">propriétés</span></a> et les <a href="/v7.1.2/information/introduction#terminologie-classe"><span class="underline">classes</span></a> sous la forme de leur <a href="/v7.1.2/information/introduction#terminologie-domaine"><span class="underline">domaine</span></a> et de leur <a href="/v7.1.2/information/introduction#terminologie-portee"><span class="underline">portée</span></a>. Ceux-ci peuvent être l’une ou une combinaison des options suivantes : </p>
<ul><li><p>la propriété est nécessaire pour le domaine;</p>
</li>
<li><p>la propriété est nécessaire pour la portée ou, en d’autres termes, la portée dépend de la propriété.</p>
</li></ul>
<p>Les dépendants possibles sont définis dans le tableau ci-haut. Si une propriété n’est pas spécifiée pour une <a href="/v7.1.2/information/introduction#terminologie-instance"><span class="underline">instance</span></a> de son domaine ou de sa portée, il est entendu que la propriété existe, mais qu’une valeur associée à une part ou à l’autre de la propriété est inconnue. Dans le cas des propriétés optionnelles, la méthodologie proposée par le CIDOC CRM n’établit pas de distinction entre une valeur inconnue et une propriété qui ne serait pas du tout applicable. Par exemple, un objet peut avoir un•e propriétaire sans que l’identité de ce•tte propriétaire ne soit connue. Dans le cadre du CIDOC CRM, une telle situation ne peut être distinguée d’un cas où l’objet n’aurait aucun•e propriétaire. Bien entendu, de tels détails peuvent être indiqués à l’aide de notes textuelles. </p>
<p>Parce que la quantification de toutes les propriétés de propriétés – les propriétés « .1 » – est « plusieurs à plusieurs  » elle n'apparaît pas explicitement dans leurs définitions. </p>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr>
<th style="width:15%"><p><em>Note de traduction</em></p>
</th>
<td colspan="1">
<p>Le terme « dépendant » a été préféré au terme « dépendance » en guise de traduction de « dependencies » puisqu’il transmet davantage le fait qu’il s’agit d’un élément qui s’inscrit dans la suite d’un autre (qui en dépend) plutôt qu’un élément qui a lui-même « besoin » d’un autre élément (qui est en situation de dépendance). </p>
</td>
</tr>
<tr>
<th style="width:15%"><p><em>Références</em></p>
</th>
<td colspan="1">
<p><em></em></p>
</td>
</tr>
</tbody>
</table>

