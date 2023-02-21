---
layout: page
title: Introduction aux concepts fondamentaux
titleEn: Introduction to the basic concepts - Introduction aux concepts fondamentaux
permalink: /v7.1/information/introduction-aux-concepts-fondamentaux
sidebar: v71
group: info
date: 2022-11-07
---

**Date de création** : 2020-20-10

**Dernière mise à jour** : 2022-11-07

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
<p>The following paragraphs explain the most general logic of the CIDOC CRM. The CIDOC CRM is a formalized representation of historical discourse, a formal ontology. In this capacity, it is meant to support the (re)presentation of fact based, analytic discourse about what has happened in the past in a human understandable and machine-processable manner.  It achieves this function by proposing a series of formalized properties (relations) and classes. The formalized properties support the making of semantically explicit statements relating classes of things. Their formal definition logically explicates the classes of things to which they may pertain. The CIDOC CRM properties thus enable a formal, logically explicit description of relations between individual, real world items, classified under distinct ontological classes. Encoding analytic data pertaining to the past under such a system of statements provides a standard representation for data and allows the uniform application of reasoning to large sets of data. </p>
<p>Grounding this high-level logic is a hierarchical system of classes and relations, that provide basic ontological distinctions by which to represent historical discourse. Familiarity with the basic ontological distinctions made in the top level of the class hierarchy provides the basic entry point to understanding how to apply the CIDOC CRM for knowledge representation.</p>
<p>The highest-level distinction in the CIDOC CRM is represented by the top-level concepts of E77 Persistent Item, equivalent to the philosophical notion of endurant; E2 Temporal Entity, equivalent to the philosophical notion of perdurant and, further, the concept of E92 Spacetime Volume.</p>
<p>As an event-centric model, supporting historical discourse, the CIDOC CRM firstly enables the description of entities that are themselves time-limited processes or evolutions within the passing of time using E2 Temporal Entity and its subclasses. Their basic function is to capture the fact of something having happened over time. In addition to allowing the description of a temporal duration, the subclasses of E2 Temporal Entity are used to document the historical relations between objects, similar to the role of action verbs in a natural language phrase. The more specific subclasses of E2 Temporal Entity enable the documentation of events pertaining to individually related/affected material, social or mental objects that have been described using subclasses of E77 Persistent Item. This precise documentation is enabled through the use of specialized properties formalizing the manner of the relation or affect. Examples of specific subclasses of E2 Temporal Entity include E12 Production, which allows the representation of events of making things by humans, and E5 Event which allows the documentation, among other things, of geological events and large-scale social events such as a war. Each of these subclasses have specific properties associated to them which allow them to function to represent the specific, real world connection between instances of E77 Persistent Item, such as the relation of an object to its time of production through <em>P108 was produced by </em>(E12) or the relation of a place to a geological phenomenon through <em>P7 was place of</em> (E5). The entities that E2 Temporal Entity documents, being time limited processes / occurrences, are such that their existence can be declared only on the basis of direct observation or recording of the event, or indirect observation of its material outcomes. Evidence of such entities may be preserved on material objects that are permanently changed because of them. Likewise, events may have been recorded in text or remembered through oral history. E2 Temporal Entity and its subclasses are central to the CRM and essential for almost all modelling tasks (e.g., in a museum catalogue one cannot consider an object outside its production event).</p>
<p></p>
<p>The real-world entities, which the event centric modelling of the CIDOC CRM aims to enable the accurate historical description of, are captured through E77 Persistent Item and its subclasses.  E77 Persistent Item is used to describe entities that are relatively stable in form through the passage of time, maintaining a recognizable identity because their significant properties do not change. Specific subclasses of E77 Persistent Item can illustrate this point.  E22 Human Made Object is used for the description of discrete, physical objects having been produced by human action, such as an artwork or monument. An artwork or monument is persistent with regards to its physical constitution. So long as it retains its general physical form, it is said to exist and to participate in the flow of historical events. E28 Conceptual Object is also used to describe persistent items, but of a mental character. It is used to describe identifiable ideas that are named and form an object of historical discourse. Its identity conditions rely in having a carrier by which it can be recalled.  The entities described by E77 Persistent Item are prone to change through human activity, biological, geological or environmental processes, but are regarded to continue to exist and be the same just as long as such changes do not alter their basic identity (essence) as defined in the scope note of the relevant class. </p>
<p></p>
<p>The notion of identity is key in the application of CIDOC CRM. The properties and relations it provides are designed to allow the accurate historical description of the evolution of real-world items through time. This being the case, classes and properties are created in order to provide a definition, which will allow the accurate application of the classes or properties to the same real-world items by diverse users. Identity, in the sense of the CIDOC CRM, therefore, means that informed people are able to agree that they refer to the same, single thing in its distinction from others, both in its extent and over its time of existence. </p>
<p></p>
<p>The criteria for such a determination should come from understanding the scope note of the respective CIDOC CRM class this thing is regarded to be an instance of, because communication via information systems may not leave space for respective clarifying dialogues between users. For example, the Great Sphinx of Giza may have lost part of its nose, but there is no question that we are still referring to the same monument as that before the damage occurred, since it continues to represent significant characteristics and distinctness from an overall shaping in the past, which is of archaeological relevance. Things lacking sufficient stability or differentiation, such as atmosphere, soil, clouds, waves, are not instances of E77 Persistent Item, and not suited for information integration. Discourse about such items may be documented with concepts of the CIDOC CRM as observations in relation to things of persistent identity, such as places.</p>
<p>Learning to distinguish and then interrelate instances of E77 Persistent Item (endurants) and instances of E2 Temporal Entity (perdurants) using the appropriate properties is key to the proper understanding and application of CIDOC CRM in order to formally represent analytic historical data. In the large majority of cases, the distinction this provides, and the subsequent elaboration of subclasses and properties is adequate to describe the content of database records in the cultural and scientific heritage domain. In exceptional cases, where we need to consider complex combinations of changes of spatial extent over time, the concept of spacetime (E92 Spacetime Volume) also needs to be considered. E92 Spacetime Volume describes the entities whose substance has or is an identifiable, confined geometrical extent in the material world that may vary over time, fuzzy boundaries notwithstanding. For example, the built settlement structure of the city of Athens is confined both from the point of view of time-span (from its founding until now) and from its changing geographical extent over the centuries, which may become more or less evident from current observation, historical documents and excavations. Even though E92 Spacetime Volume is an important theoretical part of the model, it can be ignored for most practical documentation and modelling tasks.</p>
<p>The key to the proper understanding of CIDOC CRM comes through the appropriation of its basic divisions and the logic these represent. It is important to underline that the CIDOC CRM is not intended to function as a classification system or vocabulary tool. The basic class divisions in CIDOC CRM are declared in order to be able to apply distinct properties to these classes and, in so doing, formulate precise, analytic propositions that represent historical realities. The expressive power of CIDOC CRM comes not from the application of classes to classify entities but in the documenting the interrelation of individual historical items through well-defined properties. These properties characteristically cover subjects such as relations of <em>identifying</em> items by names and identifiers; <em>participation</em> of persistent items in temporal entities; <em>location</em> of temporal entities and physical things in space and time; relations of <em>observation</em> and assessment; part-decomposition and <em>structural</em> properties of anything; <em>influence</em> of things and experiences on the activities of people and their products; <em>reference</em> of information objects to anything.</p>
<p></p>
<p>We explain these concepts with the help of graphical representations in the next sections.</p>
</td>
<td>
<p>Les paragraphes suivants expliquent la logique générale du CIDOC CRM, une ontologie formelle représentant le discours historique. À ce titre, le CIDOC CRM a pour objectif de soutenir la (re)présentation d'un discours analytique basé sur des faits reflétant ce qui s'est produit dans le passé, et ce de manière à être compréhensible par l'humain ainsi que par la machine. Le CIDOC CRM atteint cet objectif en proposant une série de propriétés (relations) et de classes formalisées. Ces propriétés formalisées soutiennent l'élaboration d'énoncés sémantiques explicites reliant des classes de choses. Leur définition formelle explique logiquement les classes de choses auxquelles elles sont pertinentes. Ces propriétés du CIDOC CRM permettent ainsi une description formelle, explicitée logiquement, des relations entre des entitées individuelles du monde réel classifiées sous des classes ontologiques distinctes. L'encodage de données analytiques au sujet du passé en utilisant un tel système permet de standardiser la représentation des données et permet l'application uniforme de processus de raisonnement logique à des ensembles de données de large taille. </p>
<p></p>
<p>Un système de classes et de relations hiérarchisé sous-tend la logique de ce système ainsi que des distinctions ontologiques de base qui permettent de représenter le discours historique. Une familiarité avec ces distinctions ontologiques de base dans les classes supérieures de la hiérarchie est nécessaire à la compréhension et à l'utilisation du CIDOC CRM à des fins de représentation des connaissances. </p>
<p></p>
<p>Dans le CIDOC CRM, le plus haut niveau de distinction est représenté par les concepts suivants:</p>
<p></p>
<ul><li><p><code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code>, qui correspond à la notion philosophique de perdurance; </p>
</li>
<li><p><code class="language-plaintext highlighter-rouge">E77_Entité_persistante</code>, qui correspond à la notion philosophique d'endurance;</p>
</li>
<li><p><code class="language-plaintext highlighter-rouge">E92_Volume_spatio-temporel</code>. </p>
</li></ul>
<p></p>
<p>Le CIDOC CRM est un modèle construit autour de la notion d'évènement qui soutient le discours historique. À ce titre, il permet la description d'entités qui sont elles-mêmes des processus limités dans le temps ou des évolutions s'inscrivant dans le passage du temps, et ce grâce à l'usage de la classe <code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code> et de ses sous-classes. La principale fonction de <code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code> et de ses sous-classes est de capturer le fait que quelque chose s'est produit à travers le temps. Ces sous-classes sont utilisées non seulement pour signaler une durée temporelle, mais aussi pour documenter des relations historiques entre des objets (à la manière des verbes actifs dans une phrase de langage naturel). Les sous-classes de <code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code>, lesquelles sont plus spécifiques, permettent la documentation d'évènements qui concernent des matériaux individuellement reliés ou affectés, ou encore des objets sociaux ou mentaux qui sont décrits grâce aux sous-classes de <code class="language-plaintext highlighter-rouge">E77_Entité_persistante</code>. Cette documentation précise est possible grâce à l'utilisation de propriétés spécialisées formalisant la manière de la relation ou de l'affect. Des exemples de sous-classes spécifiques de <code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code> sont: </p>
<p></p>
<ul><li><p><code class="language-plaintext highlighter-rouge">E12_Production</code> qui permet la représentation d'évènements où des humains fabriquent des choses; </p>
</li>
<li><p><code class="language-plaintext highlighter-rouge">E5_Évènement</code> qui permet la documentation d'évènements géologiques ou d'évènements sociaux de grande envergure (p. ex. une guerre). </p>
</li></ul>
<p></p>
<p>Des propriétés spécifiques à chacune de ces sous-classes permettent de représenter les connexions réelles entre des instances de <code class="language-plaintext highlighter-rouge">E77_Entité_persistante</code>, comme par exemple la relation d'un objet au moment de sa production grâce à la propriété <code class="language-plaintext highlighter-rouge">P108_a_produit</code> (<code class="language-plaintext highlighter-rouge">E12_Production</code>) ou la relation d'un lieu à un phénomène géologique grâce à la propriété <code class="language-plaintext highlighter-rouge">P7_a_eu_lieu_dans </code>(<code class="language-plaintext highlighter-rouge">E5_Évènement</code>). Les entités que documente <code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code>, puisqu'elles sont des processus limités dans le temps ou des occurrences, sont d'une telle nature que leur existence ne peut être déclarée que sur la base d'observations: directes ou d'enregistrements d'un évènement, ou sur la base d'observations indirectes des manifestations d'un évènement sur un objet matériel ayant subi un changement en raison de ce même évènement. Des évènements peuvent aussi avoir été documentés textuellement ou inscrits dans la l'histoire et la mémoire orale d'une collectivité. <code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code> et ses sous-classes sont des éléments centraux du CIDOC CRM et sont essentielles à presque toutes les tâches de modélisation (p. ex. il n'est pas possible, dans un catalogue muséal, de considérer un objet en dehors de son évènement de production). </p>
<p></p>
<p>La modélisation évènementielle du CIDOC CRM a pour objectif de permettre une description historique fidèle en représentant des entités du monde réel grâce à la classe <code class="language-plaintext highlighter-rouge">E77_Entité_persistante</code> et à ses sous-classes. <code class="language-plaintext highlighter-rouge">E77_Entité_persistante</code> est utilisée pour décrire des entités qui sont formellement relativement stables à travers le temps et qui maintiennent une identité reconnaissable en raison du fait que leurs attributs significatifs ne changent pas. Des sous-classes spécifiques de <code class="language-plaintext highlighter-rouge">E77_Entité_persistante</code> illustrent ceci: </p>
<p></p>
<ul><li><p><code class="language-plaintext highlighter-rouge">E22_Objet_élaboré_par_l’humain</code> est utilisée pour la description d'objets physiques distincts étant le produit de l'action humaine (p. ex. une œuvre d'art ou un monument est persistant quant à sa constitution physique et tant qu'il conserve sa forme physique générale, il est considéré exister et participer au flux des évènements historiques); </p>
</li>
<li><p><code class="language-plaintext highlighter-rouge">E28_Objet_conceptuel</code> est utilisée pour la description d'entités persistantes ayant un caractère mental, à savoir pour la description d'idées identifiables qui sont nommées et qui constituent un objet du discours historique, et dont les conditions identitaires reposent sur le fait qu'elles s'incarnent dans une chose grâce à laquelle ces idées peuvent être convoquées de nouveau ou rappelées. </p>
</li></ul>
<p></p>
<p>Les entités décrites par <code class="language-plaintext highlighter-rouge">E77_Entité_persistante</code> sont sujettes au changement du fait d'activités humaines ou biologiques, ou du fait de processus géologiques ou environnementaux. Elles sont néanmoins considérées continuer d'exister et d'être pareilles à elles-mêmes tant que ces changements n'altèrent pas leur identité fondamentale (essence) telle qu'elle est définie dans la note d'application de la classe concernée. </p>
<p></p>
<p>La notion d'identité est clé pour l'application du CIDOC CRM. Les propriétés et les relations que fournit le modèle sont conçues pour permettre la description historique fidèle de l'évolution d'entités réelles à travers le temps. Les classes et les propriétés sont donc créées afin de fournir une définition permettant leur application aux mêmes entités réelles par des utilisateurs divers. Ainsi, au sens du CIDOC CRM, l'identité implique que des personnes informées sont à même de convenir qu'elles réfèrent à une seule et même chose distincte tout au long des étendues et de la durée de son existence. Les critères permettant de déterminer ceci émanent de la note d'application de la classe du CIDOC CRM dont la chose est considérée être une instance, car la communication informatique ne soutient pas un dialogue entre utilisateurs. Par exemple, le Sphinx de Gizeh a été endommagé, notamment au niveau du nez qui est absent, mais il est considéré être le même monument qu'avant sa mutilation car il continue de représenter les caractéristiques distinctes d'une forme passée ayant une pertinence archéologique. Les choses n'étant pas dotées d'une stabilité et d'une distinction suffisantes ne sont pas des instances de <code class="language-plaintext highlighter-rouge">E77_Entité_persistante</code> et elles ne se prêtent pas à l'intégration dans le CIDOC CRM (p. ex. l'atmosphère, les nuages, les vagues ou le sol).  Un discours au sujet de telles entités peut être documenté sous forme d'observations au sujet des relations entre des choses à l'identité persistante (p. ex. des lieux) à l'aide de concepts du CIDOC CRM.</p>
<p></p>
<p>Il est crucial, afin de représenter formellement des données analytiques historiques, de savoir distinguer et inter-relier des instances de <code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code> (perdurants) et de <code class="language-plaintext highlighter-rouge">E77_Entité_persistante</code> (endurants) grâce aux propriétés appropriées. Dans la majorité des cas, cette distinction combinée à l'élaboration de sous-classes et de propriétés est suffisante à la description des entrées de bases de données patrimoniales des domaines patrimoniaux culturel et scientifique. Exceptionnellement, lorsque des combinaisons complexes de changements de l'étendue spatiale à travers le temps doivent être documentées, il est nécessaire d'utiliser <code class="language-plaintext highlighter-rouge">E92_Volume_spatio-temporel</code> qui décrit des entités dont la substance est ou contient une étendue identifiable et confinée géométriquement dans le monde réel, lequel peut varier à travers le temps indépendamment de frontières floues. Par exemple, les constructions de l'établissement de la ville d'Athènes sont contraintes par leur intervalle temporel (depuis la fondation jusqu'à aujourd'hui) par leur étendue géographique changeante à travers les siècles (ce qui peut être plus ou moins évident au regard des observations actuelles, des documents historiques, et des excavations). Bien que <code class="language-plaintext highlighter-rouge">E92_Volume_spatio-temporel</code> soit une part théorique importante du CIDOC CRM, il peut dans la plupart des cas être ignoré en faveur d'une documentation et d'une modélisation appliquées. </p>
<p></p>
<p>La clé de la compréhension adéquate du CIDOC CRM est l'appropriation de ses divisions fondamentales et de la logique qu'elles représentent. Malgré cela, le CIDOC CRM n'est pas un système de classification ou un vocabulaire contrôlé. Ses divisions de classes sont déclarées afin de pouvoir appliquer des propriétés distinctes qui permettent d'énoncer des propositions analytiques représentant précisément des réalités historiques. Ainsi, le pouvoir expressif du CIDOC CRM n'émane pas de la classification d'entités, mais de la documentation des inter-relations entre des entités individuelles historiques grâce à des propriétés adéquatement définies. Typiquement, ces propriétés recoupent différents sujets comme : </p>
<p></p>
<ul><li><p>les relations d'identification d'entités grâce à des noms et des identifiants; </p>
</li>
<li><p>les participations d'entités persistantes à des entités temporelles; </p>
</li>
<li><p>les lieux d'entités temporelles et de choses matérielles dans l'espace et dans le temps; </p>
</li>
<li><p>les relations d'observation et d'évaluation; </p>
</li>
<li><p>les propriétés structurelles et les décompositions en parties de choses; </p>
</li>
<li><p>l'influence des choses et des expériences sur les activités des personnes et des produits; </p>
</li>
<li><p>les références d'objets informationnels à quoi que ce soit. </p>
</li></ul>
<p></p>
<p>Les sections suivantes expliquent ces concepts à l'aide de diagrammes. </p>
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
<th><p><em>Références</em></p>
</th>
<td colspan="1">
</td>
</tr>
</tbody>
</table>

<h2 id="des-relations-evenementielles"><span class="en heading">Relations with Events - </span>Des relations évènementielles</h2>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>Figure 1 illustrates the minimal properties in the CIDOC CRM for documenting “what has happened”, the central pattern of the Model. Let us first consider the class E1 CRM Entity, the formal top class of the model. It primarily serves a technical purpose to aggregate the ontologically meaningful concepts of the model. It declares however two important properties of general validity and distinct features of the Model: <em>P1 is identified by</em>, with range E41 Appellation<em>,</em> makes the fundamental ontological distinction between the identity of a particular and an identifier (see section “Reality, Knowledge Bases and CIDOC CRM” above), and in practice allows for describing a discourse about resolving historical ambiguities of names and reconciliation of multiple identifiers. The property <em>P2 has type</em>, with range E55 Type, constitutes a practical interface for refining classes by terminologies, being often volatile, as detailed in the section “About Types” below.</p>
<p></p>
<iframe frameborder="0" style="width:100%;height:500px;" src="https://viewer.diagrams.net/?tags=%7B%7D&target=blank&highlight=0000ff&edit=_blank&layers=1&nav=1#G1ms3l5f3Ql7p_pv1JdfuPRXZva4-wGmyo"></iframe>
<p><em>Figure 1: High Level Properties and Classes of CIDOC CRM</em></p>
<p></p>
<p>All classes in figure 1 are direct or indirect subclasses of E1 CRM Entity<em>, </em>but for better readability, only the “subclass of” -link from E2 Temporal Entity is shown. The latter comprises phenomena that continuously occur over some time-span (E52 Time-Span) in the natural time dimension, but some of them may not be confined to specific area, such as a marriage status. Further specializing, E4 Period comprises phenomena occurring in addition within a specific area in the physical space, which can be specified by <em>P7 took place at</em>, with range E53 Place. Instances of E4 Period can be of any size, such as the Warring States Period, the Roman Period, a siege or just the process of making a signature. Further specializing, E5 Event<em> </em>comprises phenomena involving and affecting certain instances of E77 Persistent Item in a way characteristic of the kind of process, which can be specified by the property <em>P12 occurred in the presence of</em>. This concept of presence is very powerful: It constrains the existence of the involved things to the respective places within the specified time and implies the potential of passive or active involvement and mutual impact. Via presence, events represent nodes in a network of things meeting in various combinations in the course of time at different places.</p>
<p></p>
<p>The most important specializations of E77 Persistent Item in this context are: E39 Actor, those capable of intentional actions, E18 Physical Thing, having an identity bound to a relative stability of material form, and E28 Conceptual Object, the idealized things that can be recognized but have an identity independent from the materialization on a specific carrier. The property <em>P12 occurred in the presence of </em>has 36 direct and indirect subproperties, relating these and many more subclasses of E5 Event and E77 Persistent Item<em>.</em> Regardless whether a CRM-compatible knowledge base is created with these properties only or with their much more expressive specializations, querying for the above presented five properties will provide answer to all “Who-When-Where-What-How” questions, and allow for retrieving potentially richly elaborated stories of people, places, times and things.</p>
<p></p>
<p>This pattern of “meeting” is complemented by two more subclasses of E5 Event: E63 Beginning of Existence and E64 End of Existence, which imply not only presence, but constitute the <strong>endpoints of existence</strong> of things and people in space and time, often in explicit presence and interaction with others, be they causal by producing or consuming or just witnessing. Note that the Model supports multiple instantiation. As a consequence, particular events can be instances of combinations of these and others classes, describing tightly integrated processes of multiple nature. The representation of things connected in events by presence, beginning and end of existence is sufficient to describe the logic of <em>termini postquos and antequos</em>, a major form of reasoning about chronology in historical studies.</p>
<p></p>
<iframe frameborder="0" style="width:100%;height:500px;" src="https://viewer.diagrams.net/?tags=%7B%7D&target=blank&highlight=0000ff&edit=_blank&layers=1&nav=1#G1fC7Oxh1vsL6zUJGLunVLg10xDwAImB6-"></iframe>
<p><em>Figure 2: CIDOC CRM Encoding Example (Winkelmann seeing Leocoön)</em></p>
<p></p>
<p><strong>Example: </strong></p>
<p></p>
<p>As a simple, real example of applying the above concepts we present a historical event, relevant for the history of art: Johann-Joachim Winkelmann (a German Scholar) has seen the so-called Laocoön Group in 1755 in the Vatican in Rome (at display in the Cortile del Belvedere). He described his impressions in 1764 in his “History of the Art of Antiquity”, (being the first to articulate the difference between Greek, Greco-Roman and Roman art, characterizing Greek art with the famous words “…noble simplicity, silent grandeur”). The sculpture, in Hellenistic "Pergamene baroque" style (Bieber 1961, Brilliant 2000) is widely assumed to be a copy, made between 27 BC and 68 AD (following a Roman commission) from a Greek (no more extent) original. Johann-Joachim Winkelmann was born 1717 as child of Martin Winkelmann and Anna-Maria Meyer and died in 1768 in Trieste.</p>
<p></p>
<p>Figure 2 presents a semantic graph of this event, as described above, using CIDOC CRM concepts. The facts in parentheses above are omitted for better clarity. Instances of classes are represented by informative labels instead of identifiers, in boxes showing the class label above the instance label. Properties are represented as arrows with the property label attached. After class labels and property labels, we show in parenthesis the identifiers of the respective superclasses and superproperties from figure 1, in order to demonstrate that the story can be represented and queried with these concepts only. It also shows how concept specialization increases expressiveness without losing genericity. It is noteworthy that the transfer of information from the Greek original, to the copy, to the mind of Winkelmann and into his writings can be solely understood by this chain of things <em>being present</em> in different meetings. Note also that the degree to which a fact is believed to be real does not affect the choice of CIDOC CRM concepts for description of the fact, nor the reality concept underlying the Model. </p>
<p></p>
<p>Figure 2 represents in addition one more top-level property of the CIDOC CRM: <em>P67 refers to</em>, which describe an evidence-based fact that an information object makes reference to an identifiable item.</p>
<p></p>
<iframe frameborder="0" style="width:100%;height:500px;" src="https://viewer.diagrams.net/?tags=%7B%7D&target=blank&highlight=0000ff&edit=_blank&layers=1&nav=1#G1CqBAtocuopSFK0bKy0E5FkZiKXxlt2Eh"></iframe>
<p><em>Figure 3: Symbolic Representation of "Winkelmann seeing Laocoön" as an Evolution in Space and Time</em></p>
<p>As mentioned above, the central concept of the CIDOC CRM is the representation of a part of reality that can be approximated as a network of things meeting in various combinations in spacetime. Using the same example from above, figure 3 illustrates this concept via an alternative symbolic representation. It aims at rendering the idea that people and things in the past have performed mostly unknown trajectories in spacetime and the historical facts known to us constrain their possible whereabouts for some limited time-spans to having been together at some known or unknown place. </p>
<p></p>
<p>We use a one-dimensional representation of space, as used in archaeology to describe the spatial  evolution of periods or cultures over time, and a vertical time axis. We symbolize the trajectories of things and people as fuzzy lines between events in order to render their relative indeterminacy between known events. Non-animate things use to be stationary if not transferred, whereas people may move around on their own.  We symbolize events as fuzzy ovals to render the fuzzy boundaries of events in space and time. Note that in this representation, as a general pattern, things may “survive” events, emerge from events or end in events. Beginning and ending of existence impose an additional temporal order on events of causal nature, which can be stronger than explicit dates. We symbolize the unreported ends of existence of people and things, which are also events, by a dot at the end of the trajectory.</p>
<p></p>
<p>In the following, we give an overview of the system of spatial and temporal relations in the CIDOC CRM, because it constitutes an important tool for precise documentation of the past and has a certain complexity that needs to be understood in a synopsis.</p>
</td>
<td>
<p>La figure 1 illustre les propriétés minimales pour documenter « ce qui s'est produit », à savoir le patron fondamental du CIDOC CRM. La classe <code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code> est la classe à la tête de la hiérarchie du modèle; elle a pour fonction de fédérer les concepts ontologiquement signifiants du modèle. De plus, cette classe déclare deux propriétés essentielles à la validité générale et aux caractéristiques distinctes du CIDOC CRM: </p>
<p></p>
<ul><li><p><code class="language-plaintext highlighter-rouge">P1_est_identifié_par</code> avec pour portée <code class="language-plaintext highlighter-rouge">E41_Appellation</code> établit une distinction ontologique fondamentale entre l'identité d'un particulier et son identifiant (voir la section <a href="/cidoc_crm_fr-ca/v7.1/information/principes-de-modelisation#de-la-realite-des-bases-de-connaissance-et-du-cidoc-crm"><span class="underline">De la réalité, des bases de connaissance, et du CIDOC CRM</span></a>), ce qui permet de décrire un discours solutionnant des ambiguïtés historiques de noms ainsi que de réconcilier de multiples identifiants; </p>
</li>
<li><p><code class="language-plaintext highlighter-rouge">P2_a_pour_type</code> avec pour portée <code class="language-plaintext highlighter-rouge">E55_Type</code> constitue une interface pratique pour rafiner des classes par le biais de terminologies, lesquelles sont souvent fluctuantes (voir la section <a href="/cidoc_crm_fr-ca/v7.1/information/basic-concepts#des-types"><span class="underline">Des types</span></a>).  </p>
</li></ul>
<p></p>
<iframe frameborder="0" style="width:100%;height:500px;" src="https://viewer.diagrams.net/?tags=%7B%7D&target=blank&highlight=0000ff&edit=_blank&layers=1&nav=1#G1PFRT0SGXGdLd-l-R56rFF0AMzgcSx5Fx"></iframe>
<p><em>Figure 1 : Propriétés et classes de haut-niveau du CIDOC CRM</em></p>
<p></p>
<p>Toutes les classes de la figure 1 sont des sous-classes directes ou indirectes de <code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code>, mais à des fins de lisibilité seuls les liens de sous-classe depuis <code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code> sont illustrés. </p>
<p></p>
<p>La classe <code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code> comprend des phénomènes qui se produisent de manière continue sur une étendue de temps déterminée (<code class="language-plaintext highlighter-rouge">E52_Intervalle_temporel</code>) dans la dimension naturelle du temps bien que certains de ces phénomènes puissent de pas être confinés à une aire spécifique (p. ex. le statut d'être une personne mariée). </p>
<p></p>
<p>La classe <code class="language-plaintext highlighter-rouge">E4_Période</code> est encore plus spécifique et comprend des phénomènes se produisant dans l’espace et dans le temps, information qui peut être représentée par la propriété <code class="language-plaintext highlighter-rouge">P7_a_eu_lieu_dans</code> avec pour portée <code class="language-plaintext highlighter-rouge">E53_Lieu</code>. Les instances de <code class="language-plaintext highlighter-rouge">E4_Période</code> peuvent avoir des tailles variables (p. ex. la période des Royaumes combattants, la période Romaine, un siège, ou encore la procédure d'une signature).</p>
<p></p>
<p>La classe <code class="language-plaintext highlighter-rouge">E5_Évènement</code> est encore plus spécifique et comprend des phénomènes impliquant et affectant certaines instances de <code class="language-plaintext highlighter-rouge">E77_Entité_persistante</code> d'une manière caractéristique de types de processus précisés par la propriété <code class="language-plaintext highlighter-rouge">P12_a_eu_lieu_en_présence_de</code>. Ce concept de présence est particulièrement puissant dans la mesure où il : </p>
<p></p>
<ul><li><p>contraint l'existence des choses impliquées aux lieux qui leur sont associés dans un temps spécifié; </p>
</li>
<li><p>indique le potentiel d'une implication passive ou active [n.d.t. des entités impliquées] ainsi que leur impact mutuel les unes sur les autres. </p>
</li></ul>
<p></p>
<p>Du fait de ce concept de présence, les évènements représentent des nœuds dans un réseau de choses reliées entre elles dans des combinaisons diverses à travers le temps et dans différents lieux [(en d'autres termes, un patron de « rencontre » des entités)]. </p>
<p></p>
<p>Les spécialisations les plus importantes de <code class="language-plaintext highlighter-rouge">E77_Entité_persistante</code> dans ce contexte sont: </p>
<p></p>
<ul><li><p><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code>, qui désigne des entités dont l'identité est déterminée par la stabilité relative de leur forme matérielle; </p>
</li>
<li><p><code class="language-plaintext highlighter-rouge">E28_Objet_conceptuel</code>, qui désigne des choses idéalisées qui peuvent être reconnues, mais ont une identité indépendante de leur matérialisation sur un support physique; </p>
</li>
<li><p><code class="language-plaintext highlighter-rouge">E39_Actant</code>, qui désigne des entités capables d'actions intentionnelles. </p>
</li></ul>
<p></p>
<p>La propriété <code class="language-plaintext highlighter-rouge">P12_a_eu_lieu_en_présence_de</code> a 36 sous-propriétés directes et indirectes qui permettent de relier de nombreuses sous-classes de <code class="language-plaintext highlighter-rouge">E5_Évènement</code> et de <code class="language-plaintext highlighter-rouge">E77_Entité_persistante</code> telles que celles mentionnées ci-haut. Qu'une base de connaissances compatible avec le CIDOC CRM soit créée uniquement avec ces propriétés ou qu'elle le soit avec leurs spécialisations (qui sont beaucoup plus expressives), des requêtes utilisant les quatre propriétés susmentionnées (<code class="language-plaintext highlighter-rouge">P1_est_identifié_par</code>, <code class="language-plaintext highlighter-rouge">P2_a_pour_type</code>, <code class="language-plaintext highlighter-rouge">P7_a_eu_lieu_dans</code>, <code class="language-plaintext highlighter-rouge">P12_a_eu_lieu_en_présence_de</code>) permettent de répondre à la plupart des questions de type « qui, quand, où, quoi et comment » et permettent de rapatrier des histoires richement élaborées de personnes, de lieux, de temps et de choses. </p>
<p></p>
<p>Ce patron de « rencontre » des entités est assorti de deux sous-classes supplémentaires de <code class="language-plaintext highlighter-rouge">E5_Évènement</code> : <code class="language-plaintext highlighter-rouge">E63_Début_d’existence</code> et <code class="language-plaintext highlighter-rouge">E64_Fin_d’existence</code>. Celles-ci impliquent non seulement la présence des entités, mais constituent aussi les frontières externes de l'existence de choses et de personnes dans l'espace et dans le temps, et ce le plus souvent en présence et en interaction directes avec d'autres entités, notamment de manière causale par le fait de produire, de consommer, ou d'être témoin d'une chose. </p>
<p></p>
<p>Puisque le CIDOC CRM supporte la multi-instanciation, des évènements particuliers peuvent être des instances de combinaisons de ces classes ou d'autres classes afin de décrire des processus étroitement interreliés de natures multiples. La représentation de choses connectées à des évènements par leur présence, par le début de leur existence, ou par la fin de celle-ci, est suffisante à la description d'une logique <em>termini postquos et antequos</em>, une forme de raisonnement logique crucial à la chronologie des études historiques. </p>
<p></p>
<p>Par exemple : </p>
<p></p>
<p>Un exemple représentant adéquatement l'application des concepts susmentionnés dans le contexte de l'histoire de l'art est celui de Johann Joachim Winckelmann (érudit allemand) voyant l'œuvre sculptée intitulée <em>Groupe du Laocoön</em> en 1755 au vatican à Rome (exposée dans le Cortile del Belvedere). En 1764, dans son article « Histoire de l'art dans l'Antiquité », il décrit ses impressions et articule les différences entre l'art grec, l'art gréco-romain, et l'art romain (il a d'ailleurs indiqué dans un article précédent que l'art grec se distingue par une « noble simplicité et une grandeur tranquille, tant dans l’attitude que dans l’expression »). La sculpture, de style hellenistique pergamene baroque (Bieber 1961, Brilliant 2000), est reconnue être une copie, d'un original grec, effectuée entre 27 AEC et 68 EC à la suite d'une commande par un mécène romain. Johann Joachim Winckelmann, fils de Martin Winckelmann et de Anna-Maria Meyer, est né en 1717 [à Stendal (Allemagne)] et décédé en 1768 à Trieste (Italie). </p>
<p></p>
<p>La figure 2 représente un graphe sémantique de ces évènements à l'aide des concepts du CIDOC CRM: </p>
<p></p>
<ul><li><p>Les éléments entre parenthèses ne sont pas représentés dans le diagramme ci-dessous à des fins de clarté et de simplicité;</p>
</li>
<li><p>Les instances de classes sont représentées par des libellés informatifs plutôt que par des identifiants, eux-mêmes surmontés des libellés de leurs classes précédés de leur code;</p>
</li>
<li><p>Les propriétés sont représentées à l'aide de flèches auxquelles sont associés les libellés des propriétés en question; </p>
</li>
<li><p>Les identifiants entre parenthèses représentent les super-classes et super-propriétés de haut niveau illustrées dans la figure 1, et ce afin d'indiquer comment cette information aurait pu être représentée et faire l'objet de requêtes en utilisant un nombre limité de concepts (ceci illustre aussi en quoi la spécialisation des classes et propriétés permet d'augmenter l'expressivité du modèle sans en perdre la généricité); </p>
</li>
<li><p>La propriété de haut niveau <code class="language-plaintext highlighter-rouge">P67_renvoie_à (fait_l’objet_d’un_renvoi_par)</code> est aussi illustrée dans ce diagramme, celle-ci décrit un fait appuyé par des preuves qu'un objet informationnel (<code class="language-plaintext highlighter-rouge">E33_Objet_linguistique</code>) réfère à une entité identifiable. </p>
</li></ul>
<p></p>
<p>Il est intéressant de noter que le transfert d'information depuis l'original grec, vers sa copie romaine, puis vers l'esprit de Winckelmann et finalement vers ses écrits ne peut être compris que par cette chaîne de rencontres entre des entités présentes à différentes occasions. Il faut aussi noter que le degré de véracité perçue d'un fait n'affecte pas le choix des concepts du CIDOC CRM utilisés pour représenter ce fait; il n'affecte pas non plus le concept de réalité qui sous-tend le modèle lui-même. </p>
<p></p>
<iframe frameborder="0" style="width:100%;height:500px;" src="https://viewer.diagrams.net/?tags=%7B%7D&target=blank&highlight=0000ff&edit=_blank&layers=1&nav=1#G1PlVtHOLLkgH7K0IgM9RdnHBG1iAcKcwf"></iframe>
<p><em>Figure 2 : Exemple d'encodage avec le CIDOC CRM (Winckelmann voyant le Laocoön)</em></p>
<p></p>
<p>Tel que mentionné plus haut, le concept central du CIDOC CRM est la représentation d'une part de la réalité qui peut être représentée approximativement par un réseau de choses se rencontrant selon des combinaisons variées à travers le temps et l'espace. La figure 3 reprend l'exemple ci-haut afin de représenter symboliquement ce concept de « rencontre ». Ce diagramme a pour objectif d'illustrer comment par le passé les personnes et les choses ont performé des trajectoires dans l'espace et dans le temps qui sont en grande partie inconnues. Néanmoins, les faits historiques connus indiquent des intervalles temporels limités lors desquels les trajectoires de ces personnes et de ces choses se sont croisées à des lieux connus ou inconnus, ce qui permet de contraindre les hypothèses quant à leur présence.  </p>
<p></p>
<p>Le CIDOC CRM fait usage d'un axe temporel vertical et d'une représentation unidimensionnelle de l'espace telle qu'elle est utilisée en archéologie afin de décrire l'évolution à travers le temps de périodes ou de cultures. </p>
<p></p>
<p>La figure 3 offre un aperçu du système relationnel spatial et temporel du CIDOC CRM. </p>
<p></p>
<iframe frameborder="0" style="width:100%;height:500px;" src="https://viewer.diagrams.net/?tags=%7B%7D&target=blank&highlight=0000ff&edit=_blank&layers=1&nav=1#G1qtb46yLp91qgk-nnNmjWmxvZ0Z83C9Yc"></iframe>
<p><em>Figure 3: Représentation symbolique de « Winckelmann voyant le Laocoön » en tant qu'évolution dans le temps et l'espace</em></p>
<p></p>
<ul><li><p>La trajectoire des personnes et des choses est symbolisée par des lignes reliant les évènements et dotées d'une ombre afin d'illustrer leur indétermination et leur nature floue; </p>
</li>
<li><p>Les trajectoires des personnes, capables de se mouvoir de leur propre volition, sont illustrées par des flèches pleines; </p>
</li>
<li><p>Les trajectoires des choses inanimées, incapables de se mouvoir de leur propre volition, sont illustrées par des flèches pointillées;</p>
</li>
<li><p>Les évènements, dont la nature spatiale et temporelle est floue, sont représentés dans des bulles à l'effet glacé; </p>
</li>
<li><p>Dans le contexte de cette illustration qui représente un patron général, les choses peuvent « survivre » aux évènements, en émerger, ou s'y éteindre; </p>
</li>
<li><p>Le début et la fin de l'existence imposent des contraintes temporelles additionnelles aux évènements de nature causale interreliés dans cet exemple, ce qui peut parfois être plus signifiant que l'usage de dates explicites; </p>
</li>
<li><p>Les fins d'existence non-recensées de personnes et de choses, ces fins étant elles aussi des évènements, sont illustrées par la présence d'un point à la fin de leur trajectoire, elle-même représentée par une flèche. </p>
</li></ul>
<p></p>
<p>Ce système constitue un outil important pour la documentation du passé et possède une certaine complexité qui doit sommairement être comprise. </p>
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
<p>Les auteurs mentionnent les « <em>termini postquos and antequos</em> » qui réfèrent aux concepts de <em>terminus ante quem</em> (c.-à-d. « date avant laquelle », qui signale la date avant laquelle un événement s'est nécessairement produit) et de <em>terminus post quem</em> (c.-à-d. « date à partir de laquelle », qui signale la date à partir de laquelle un événement s'est nécessairement produit). </p>
<p></p>
<p>La traduction de la citation de Wincklemann « noble simplicity, silent grandeur » (« noble simplicité et une grandeur tranquille, tant dans l’attitude que dans l’expression ») est issue de la traduction par Laure Cahen-Maurel de <em>Pensées sur l’imitation des oeuvres grecques en peinture et en sculpture</em>, où Winckelmann utilise cette expression dès 1755. </p>
<p></p>
<p>Après consultation de la figure 3 à laquelle le texte fait référence, la phrase « Non-animate things use to be stationary if not transferred, whereas people may move around on their own » a été interprétée de la manière suivante : « Non-animate things use dotted lines to illustrate they are stationary if not transferred, whereas people may move around on their own and are using full lines ». </p>
<p></p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="1">
<p>Winckelmann, Johann Joachim. <em>Pensées sur l’imitation des oeuvres grecques en peinture et en sculpture</em>. Traduit par Laure Cahen-Maurel. Le dix-huitième siècle – entre les lumières et l’incendie. 1755. Reprint, Paris, FR-IDF: Allia, 2005.<a href="https://www.editions-allia.com/fr/livre/91/pensees-sur-limitation-des-uvres-grecques-en-peinture-et-en-sculpture"><span class="underline"> </span></a><a href="https://www.editions-allia.com/fr/livre/91/pensees-sur-limitation-des-uvres-grecques-en-peinture-et-en-sculpture"><span class="underline">https://www.editions-allia.com/fr/livre/91/pensees-sur-limitation-des-uvres-grecques-en-peinture-et-en-sculpture</span></a>.</p>
<p></p>
</td>
</tr>
</tbody>
</table>

<h3 id="des-relations-spatiales"><span class="en heading">Spatial Relations - </span>Des relations spatiales</h3>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>A major area of documentation and historical research centres around positioning in space of what has happened and the things involved, as well as reasoning about respective spatial relations. The key class CIDOC CRM provides for modelling this information is E53 Place. E53 Place is used to document geometric extents in the physical space containing actual or possible positions of things or happenings.  The higher-level properties and classes of CIDOC CRM that centre around E53 Place allow for the documentation of: relations between places; recording the geometric expressions defining or approximating a place and their semantic function; tracing the history of locations of a physical object; identifying the places where an individual or group have been located; identifying places on a physical object and the spatial extent of certain temporal entities.</p>
<p></p>
<iframe frameborder="0" style="width:100%;height:500px;" src="https://viewer.diagrams.net/?tags=%7B%7D&target=blank&highlight=0000ff&edit=_blank&layers=1&nav=1#G18miFAOo4oiF8l82Qu2WxmVnagF7XrHNI"></iframe>
<p><em>Figure 4: Basic CIDOC CRM Properties and Classes for Reasoning about Spatial Information</em></p>
<p><em></em></p>
<p><em>Relations between Places:</em> The cluster of relations <em>P89 falls within (contains)</em>, <em>P122 borders with</em>, <em>P121 overlaps with</em> and <em>P189 approximates</em> can express relative relationships held between places. These properties hold between instances of E53 Place and allow interordering places using common mereotopological concepts.</p>
<p></p>
<p><em>Geometric Expressions of Place</em>: Contemporary documentation of spatial information has access to advanced equipment for accurately recording location and libraries of georeferenced place information. For this reason, documentation of place now often includes the recording of precise coordinates for a referenced place. Of great importance semantically, is to understand the manner in which such a geometric place expression actually relates to a referenced place. The cluster or relations <em>P168 place is defined by</em>, <em>P171 at some place within</em>, and <em>P172 contains</em> allows the user to link to geometric place expressions while also accurately indicating how this expression relates to the documented place. Geometric place expressions are instances of E94 Space Primitive, a primitive class for expressing values in data systems not further analyzed in the CIDOC CRM. These properties provide a valid interface to the OGC standards, as elaborated in CRMgeo (Doerr & Hiebel 2013).</p>
<p></p>
<p><em>History of Object Locations</em>: Instances of place are often referenced in order to record the location of some object. When the movement of the object to different locations through time is of interest, it is also important to be able to analytically record the different locations at which an object was and at what point. The CIDOC CRM offers two top level mechanisms for tracing the relation of objects to places. If the aspect of time is unknown or not of interest, then an object can be related to a place through the properties <em>P53 has former or current location</em> and <em>P55 has current location</em>. The former property is the conservatively appropriate choice for documenting the object-to-place relation when time elements are not known. If one is actively tracking current location, the latter property is also of use. When an accurate history of the temporal aspect of location should be provided, the user should take advantage of the class E9 Move, a temporal entity class. Instantiating E9 Move allows the user to document the origin, destination and concerned object of a move event using the collection of properties <em>P27 moved from</em>, <em>P26 moved to</em>, <em>P25 moved</em>. Being a temporal class E9 Move further allows the tracing of time, agency etc. Note that things may be moved indirectly as parts of or within other things.</p>
<p></p>
<p><em>Actor Locations</em>: Tracking the history of the location of actors is related to the history of object location with a significant difference: in the CIDOC CRM an actor is defined as an entity featuring agency which is not the case in objects and physical entities in general. Not being physical, an actor cannot be the subject of an instance of E9 Move which documents physical relocations. The CIDOC CRM thus offers the notion of <em>P74 has current or former residence</em> in order to document the relation of a person or group to a location as residing there at some time.</p>
<p><em></em></p>
<p><em>Places on a Physical Object</em>: In the recording of cultural heritage and other scientific data, particularly about mobile objects, including ships, it is often necessary to identify where on an object or a certain feature is located and where a certain phenomenon is observed. For this the CIDOC CRM offers the relation <em>P59 has section</em> relating the object to the places which are defined upon it. Note that Earth is the physical object we relate places to per default. In geological times, a narrower relation to a tectonic plate may be necessary.</p>
<p></p>
<p><em>Spatial Extent of Temporal Entities</em>: In order to spatially define the extent of temporal phenomena, the CIDOC CRM offers two properties that apply to all instances of temporal entity under the class E4 Period: <em>P7 took place at</em> and <em>P8 took place on or within</em>. The former is used to relate a temporal phenomenon directly to an instance of E53 Place which provides the geometric context in which that phenomenon took place. The latter property allows the documentation of a temporal phenomenon taking place in relation to a physical object. This is useful for recording information such as the occurrence of an event on a moving ship or within a particular storage container, where the geometric location is not known or indirectly relevant.</p>
<p></p>
</td>
<td>
<p>L'un des axes centraux de la recherche historique et documentaire est le positionnement dans l'espace de ce qui s'est produit ainsi que des entités impliquées, de même que le raisonnement logique associé à ces relations spatiales. La classe essentielle à la modélisation de cette information dans le CIDOC CRM est <code class="language-plaintext highlighter-rouge">E53_Lieu</code>. Cette dernière est utilisée pour documenter des étendues géométriques dans un espace physique contenant des positions réelles ou possibles de choses ou d'évènements. Les classes et propriétés de haut niveau associées à <code class="language-plaintext highlighter-rouge">E53_Lieu</code> permettent de documenter : </p>
<p></p>
<ul><li><p>Les relations entre des lieux;</p>
</li>
<li><p>Les expressions géométriques définissant ou approximant un lieu ainsi que de la fonction sémantique de ces expressions; </p>
</li>
<li><p>L'historiques des localisations d'un objet physique (traçage); </p>
</li>
<li><p>L'historiques des localisations d'un individu ou d'un groupe; </p>
</li>
<li><p>Les lieux situés sur un objet physique; </p>
</li>
<li><p>Les étendues spatiales de certaines entités temporelles. </p>
</li></ul>
<p></p>
<iframe frameborder="0" style="width:100%;height:500px;" src="https://viewer.diagrams.net/?tags=%7B%7D&target=blank&highlight=0000ff&edit=_blank&layers=1&nav=1#G1BFbCQXBD7aI3DSWLVjw6N08ekUjtjWH_"></iframe>
<p><em>Figure 4: Propriétés et classes fondamentales pour le raisonnement logique au sujet d'information spatiale</em></p>
<p></p>
<p>Les relations entre les lieux: </p>
<p></p>
<p>Le regroupement des relations <code class="language-plaintext highlighter-rouge">P89_s’insère_dans (inclut)</code>, <code class="language-plaintext highlighter-rouge">P121_se_superpose_partiellement_à</code>, <code class="language-plaintext highlighter-rouge">P122_est_limitrophe_de</code> et <code class="language-plaintext highlighter-rouge">P189_approxime (est_approximé_par)</code> permet d'exprimer des relations relatives entre des lieux. Ces propriétés se situent entre des instances de <code class="language-plaintext highlighter-rouge">E53_Lieu</code> et permettent d'ordonner de manière interne des lieux en utilisant des concepts méréotopologiques communs. </p>
<p></p>
<p>L'expression géométrique des lieux : </p>
<p></p>
<p>La documentation contemporaine d'information spatiale bénéficie, d'une part, d'équipements spécialisés pour le recensement précis de lieux et, d'autre part, de bibliothèques d'informations géoréférencées au sujet des lieux. Pour cette raison, la documentation des lieux inclut souvent le recensement de coordonnées précises pour un lieu référencé.  </p>
<p></p>
<p>Il est crucial, d'un point de vue sémantique, de comprendre la manière dont l'expression géométrique d'un lieu <code class="language-plaintext highlighter-rouge">A</code> est liée à un lieu référencé <code class="language-plaintext highlighter-rouge">B</code>. Le regroupement des relations <code class="language-plaintext highlighter-rouge">P168_lieu_défini_par (définit_le_lieu)</code>, <code class="language-plaintext highlighter-rouge">P171_a_eu_lieu_quelque_part_dans</code> et <code class="language-plaintext highlighter-rouge">P172_contient</code> permet ceci en liant des expressions géométriques de lieux <code class="language-plaintext highlighter-rouge">A</code> tout en indiquant précisément comment ces expressions sont liées au lieu documenté <code class="language-plaintext highlighter-rouge">B</code>. </p>
<p></p>
<p>Les expressions géométriques de lieux sont des instances de <code class="language-plaintext highlighter-rouge">E94_Primitive_spatiale</code>, une classe primitive ayant pour fonction d'exprimer des valeurs dans des systèmes de données qui ne sont pas couverts par le CIDOC CRM. Les propriétés susmentionnées procurent une interface valide pour CRMgeo (Doerr & Hiebel 2013) qui mobilise les standards OGC [n.d.t. standards de l'Open Geospatial Consortium qui assurent l'interopérabilité dans les domaines de la géomatique et de l'information]. </p>
<p></p>
<p>L'historique des localisations d'objets physiques : </p>
<p></p>
<p>Les instances de <code class="language-plaintext highlighter-rouge">E53_Lieu</code> sont souvent référencées afin d'enregistrer la localisation d'un objet et, lorsque les déplacements d'un objet à travers le temps sont eux-mêmes pertinents, il est aussi important de pouvoir recenser ces différentes localisations tant de manière spatiale que temporelle. Pour ce faire, le CIDOC CRM propose deux mécanismes de haut niveau permettant de tracer la relation des objets aux lieux. </p>
<p></p>
<p>Dans l'éventualité où l'aspect temporel n'est pas d'intérêt ou est inconnu, un objet peut être lié à un lieu grâce aux propriétés <code class="language-plaintext highlighter-rouge">P53_a_pour_localisation_actuelle_ou_antérieure (est_localisation_actuelle_ou_antérieure_de)</code> et <code class="language-plaintext highlighter-rouge">P55_a_actuellement_pour_localisation (est_actuellement_localisation_de)</code>. La première est appropriée pour documenter la relation d'un objet à un lieu lorsque les éléments temporels sont inconnus. La seconde est appropriée lorsque la localisation actuelle est activement tracée. </p>
<p></p>
<p>Lorsqu'un historique précis des aspects temporels de la localisation est disponible, il est préférable d'utiliser la classe temporelle <code class="language-plaintext highlighter-rouge">E9_Déplacement</code> dont l'instanciation permet de documenter l'origine, la destination, et l'objet d'un évènement de déplacement de concert avec les propriétés <code class="language-plaintext highlighter-rouge">P25_a_déplacé (a_été_déplacé_par)</code>, <code class="language-plaintext highlighter-rouge">P26_a_déplacé_vers (a_été_la_destination_de)</code> et <code class="language-plaintext highlighter-rouge">P27_a_déplacé_depuis (a_été_le_point_de_départ_de)</code>. Puisque c'est une classe temporelle, <code class="language-plaintext highlighter-rouge">E9_Déplacement</code> permet aussi de tracer la temporalité, l'agentivité, etc. </p>
<p></p>
<p>Il est important de prendre en considération que des choses peuvent être déplacées indirectement du fait de leur appartenance à d'autres choses (c.-à-d. parce qu'elles sont des parties d'ensembles ou parce qu'elles sont contenues par une autre chose). </p>
<p></p>
<p>L'historique des localisations d'actants : </p>
<p></p>
<p>L'historique des localisations d'actants est comparable à l'historique des localisations d'objets physiques à la différence que dans le CIDOC CRM l'actant est défini comme étant une entité dotée d'agentivité (contrairement à d'autres entités physiques ou objets). L'essence de l'actant n'étant pas physique, celui-ci ne peut pas être le sujet d'instances de <code class="language-plaintext highlighter-rouge">E9_Déplacement</code> afin de documenter ses relocalisations. Le CIDOC CRM offre donc la notion de résidence (<code class="language-plaintext highlighter-rouge">P74_a_pour_résidence_actuelle_ou_antérieure (est_résidence_actuelle_ou_antérieure_de)</code>) afin de documenter la relation d'une personne ou d'un groupe à une localisation le temps d'une résidence dans un lieu. </p>
<p></p>
<p>Les lieux situés sur des objets physiques : </p>
<p></p>
<p>L'enregistrement de données patrimoniales et scientifiques exige souvent le recensement de l'emplacement précis d'un objet, d'une caractéristique, d'un phénomène ou de son observation (p. ex. dans le cas d'objets mobiles comme des bâteaux). La propriété <code class="language-plaintext highlighter-rouge">P59_a_pour_section (se_situe_sur_ou_dans)</code> peut être utilisée dans ce contexte afin de lier l'objet aux lieux qui sont définis sur ou dans celui-ci. </p>
<p></p>
<p>Par défaut, c'est la planète Terre qui est désignée comme objet physique sur lequel les lieux sont interreliés. Des relations plus précises grâce à des références aux plaques tectoniques peuvent cependant être nécessaires dans le cadre d'analyses géologiques. </p>
<p></p>
<p>Les étendues spatiales d'entités temporelles : </p>
<p></p>
<p>Le CIDOC CRM offre deux propriétés permettant de définir spatialement l'étendue temporelle de phénomènes (celles-ci s'appliquent à toutes les instances d'entités temporelles relevant de la classe <code class="language-plaintext highlighter-rouge">E4_Période</code>) : </p>
<p></p>
<ul><li><p><code class="language-plaintext highlighter-rouge">P7_a_eu_lieu_dans (a_été_témoin_de)</code>  permet de relier directement un phénomène temporel à des instances de <code class="language-plaintext highlighter-rouge">E53_Lieu</code>, fournissant de ce fait le contexte géométrique dans lequel le phénomène a pris place; </p>
</li>
<li><p><code class="language-plaintext highlighter-rouge">P8_a_eu_lieu_à (a_été_témoin_de)</code> permet la documentation d'un phénomène temporel par rapport à un objet physique, ce qui est utile pour l'enregistrement d'information où la localisation géométrique n'est pas directement pertinente ou est inconnue (p. ex. l'occurrence d'un évènement sur un bateau en déplacement ou dans l'enceinte d'un conteneur d'entreposage particulier). </p>
</li></ul>
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
<p></p>
<p></p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="1">
<p><em></em></p>
<p></p>
</td>
</tr>
</tbody>
</table>

<h3 id="des-relations-temporelles"><span class="en heading">Temporal Relations - </span>Des relations temporelles</h3>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>Historical and scientific discourse about the past deals with different levels of knowledge regarding events and their temporal ordering that feed into chronology. Chronology is fundamental to understanding social and natural history, and reasoning about temporal relations and causality is directly related. An immense wealth of physical observations allows for inferring temporal relations and vice-versa. It is important to be able to document temporality both with regards to known dates but also according to relative positioning within a historical time line. The top-level properties of the CIDOC CRM relating to temporal entities support the documentation of: dates as time spans or dimensions, mereological relations between temporal entities as well as a complete suite of topological relations.</p>
<p></p>
<p><em>Dates and Durations</em>: When some absolute dates limiting a temporal entity are known, this can be documented by instantiating the <em>P4 has time-span</em> property and creating an instance of E52 Time-span. Dates should then be recorded as instances of E61 Time Primitive<em> </em>and related to the time-span through properties <em>P81 ongoing throughout</em> or <em>P82 at some time within</em>. Time is recorded as a span and not an instant in the CIDOC CRM. The choice of property <em>P81 ongoing throughout</em> allows the documentation of knowledge that a temporal phenomenon was occurring at least at all points of a known time span. The property <em>P82 at some time within</em> allows the weaker claim that the phenomenon must have occurred within the limits of a particular time span without further specifying as to when precisely. It is the default for historical dates, given, for instance, in years for events of much smaller duration. The actual mode of encoding the documented date is outside the scope of the CIDOC CRM, which defines this with a primitive class, E61 Time Primitive. Finally, the property <em>P191 had duration</em> can be deployed in order to document a temporal phenomenon with known duration but with less precisely temporal positioning. For instance, a birth may be known with the precision of a year, but with a duration of 3 hours. For documenting exact time-spans that are result of a declaration rather than observation, for instance in order to describe a time-span multiple events may fall into, the property <em>P170 defines time</em> allows for specifying the time-span uniquely by a temporal primitive, rather than by <em>P81 ongoing throughout</em> or <em>P82 at some time within </em>using an identical time primitive. </p>
<p></p>
<iframe frameborder="0" style="width:100%;height:500px;" src="https://viewer.diagrams.net/?tags=%7B%7D&target=blank&highlight=0000ff&edit=_blank&layers=1&nav=1#G1XwhlLu4ruFFpGXfsqmE3AWs6SD7juz5r"></iframe>
<p><em>Figure 5: Basic CIDOC CRM Properties and Classes for Reasoning about Temporal Information</em></p>
<p></p>
<p><em>Mereological relations</em>: The documentation of the part-whole relationship of temporal phenomena is crucial for historical reasoning. The CIDOC CRM distinguishes under temporal entities two immediate specializations: E4 Period is a high-level concept for the documentation of temporal phenomena of change and interactions in space and time, comprising but not limited to historical periods such as Ming or Roman, and is further specialized in rich hierarchy of more specific processes and activities. The second specialization is E3 Condition State<em>,</em> a rather specific class for the documentation of static phases of physical things. The CIDOC CRM so far does not describe a higher-level class of static phases, because they are normally deductions from multiple observations, problematic in information integration and vulnerable to non-monotonic revision. For both classes, two different mereological relations are articulated: The property <em>P9 consists of</em> is used to document proper parthood between instances of E4 Period, i.e., to describe how the phenomena that make up an instance of E4 Period can causally be subdivided into more delimited phenomena. In contrast, the property <em>P10 falls within</em>, explained further in the section about spatiotemporal relations, describes only a non-causal co-occurrence in the same spatiotemporal extent. The property <em>P5 consists of</em> indicates, in analogy, proper parthood between instances of E3 Condition State.</p>
<p></p>
<p><em>Topological Relations</em>: A lot of semantic relations have implications on the temporal ordering of temporal entities. For instance, meeting someone must occur after birth and before death of the involved parties. Information can only be transferred after it has been learned. On the other side, direct information about temporal order has implications on possible or impossible semantic relations. This form of reasoning is of paramount importance for research about the past. It turned out that the popular temporal relations defined by (J. Allen 1983), which the CIDOC CRM had adopted in previous versions, are not well suited to describe inferences from semantic relations, as detailed in the section “Temporal Relation Primitives based on fuzzy boundaries” below. Instead, the CIDOC CRM introduces a theory of fuzzy boundaries in time that enables the accurate interpositioning of temporal entities between themselves taking into account the inherent fuzziness of temporal boundaries. This model subsumes the earlier introduced Allen temporal relations which may continued to be used in extensions of the CIDOC CRM.</p>
</td>
<td>
<p>Le discours historique et scientifique au sujet du passé concerne plusieurs niveaux de savoirs concernant des évènements et leur ordonnancement temporel tel qu'il s'inscrit dans une chronologie. Cette chronologie est fondamentale à la compréhension de l'histoire sociale et naturelle ainsi qu'à l'établissement de raisonnement logique au sujet des relations temporelles et de la causalité qui y sont directement rattachées. Une grande quantité d'observations physiques permet des inférences temporelles et vice versa. Il est important de pouvoir documenter la temporalité en ce qui a trait aux dates connues ainsi qu'en termes de positionnement relatif dans une ligne du temps historique. Les propriétés de haut niveau du CIDOC CRM qui sont liées à des entités temporelles supportent la documentation de : </p>
<p></p>
<ul><li><p>Dates en tant qu'intervalle ou que dimensions temporel·les;  </p>
</li>
<li><p>Relations méréologiques entre des entités temporelles; </p>
</li>
<li><p>Relations topologiques formant une suite complète. </p>
</li></ul>
<p></p>
<p>Les dates et les durées : </p>
<p></p>
<p>Lorsque des dates absolues limitant une entité temporelle sont connues, une instanciation de la propriété <code class="language-plaintext highlighter-rouge">P4_a_pour_intervalle_temporel (est_l’intervalle_temporel_de)</code> et la création d'une instance de <code class="language-plaintext highlighter-rouge">E52_Intervalle_temporel</code> sont recommandées. Ces dates devraient aussi être enregistrées comme instances de <code class="language-plaintext highlighter-rouge">E61_Primitive_temporelle</code> et reliées à l'intervalle temporel par les propriétés <code class="language-plaintext highlighter-rouge">P81_a_couvert</code> et <code class="language-plaintext highlighter-rouge">P82_a_eu_lieu_durant</code>. Puisque dans le CIDOC CRM le temps est enregistré à travers des intervalles (plutôt qu'à travers des instants), le choix de la propriété <code class="language-plaintext highlighter-rouge">P81_a_couvert</code> permet de documenter le fait qu'un phénomène temporel avait lieu à tout le moins durant tous les instants d'un intervalle temporel connu. La propriété <code class="language-plaintext highlighter-rouge">P82_a_eu_lieu_durant</code> permet d'affirmer moins précisément qu'un phénomène s'est produit à l'intérieur d'un intervalle temporel particulier sans pour autant indiquer précisément à quel moment. Cette dernière approche est la plus utilisée dans le cas de dates historiques où une année peut être indiquée bien que la durée de l'évènement ait certainement été moindre. Le mode d'encodage des dates lors du processus de documentation ne relève pas du CIDOC CRM qui le définit par le biais d'une classe primitive (<code class="language-plaintext highlighter-rouge">E61_Primitive_temporelle</code>). Finalement, la propriété <code class="language-plaintext highlighter-rouge">P191_a_eu_pour_durée (était_la_durée_de)</code> peut être déployée afin de documenter un phénomène temporel dont la durée est déterminée sans que son positionnement temporel ne soit pour autant connu. Par exemple, la documentation d'une naissance pourrait indiquer que l'accouchement a duré 3 heures et a eu lieu une année précise. </p>
<p></p>
<p>Pour documenter des intervalles temporels précis qui résultent de déclarations plutôt que d'observations, l'usage de la propriété <code class="language-plaintext highlighter-rouge">P170_temps_défini_par (définit_le_temps)</code> est recommandé. Cela serait par exemple pertinent pour représenter un intervalle temporel dans lequel de multiples évènements s'inscrivent car cette propriété permet de spécifier un intervalle temporel uniquement à l'aide d'une primitive temporelle plutôt que par l'usage plus alambiqué de <code class="language-plaintext highlighter-rouge">P81_a_couvert</code> et <code class="language-plaintext highlighter-rouge">P82_a_eu_lieu_durant</code> faisant usage d'une primitive temporelle identique. </p>
<p></p>
<iframe frameborder="0" style="width:100%;height:500px;" src="https://viewer.diagrams.net/?tags=%7B%7D&target=blank&highlight=0000ff&edit=_blank&layers=1&nav=1#G13QMARy-dludqR3Uz4CO0A1ckVJ0Y4r1L"></iframe>
<p><em>Figure 5: Propriétés et classes fondamentales pour le raisonnement logique au sujet d'information temporelle</em></p>
<p></p>
<p>Les relations méréologiques : </p>
<p></p>
<p>La documentation d'une relation partie-tout associée à un phénomène temporel est essentielle au raisonnement historique. Le CIDOC CRM distingue deux spécialisations immédiates des entités temporelles : </p>
<p></p>
<ul><li><p><code class="language-plaintext highlighter-rouge">E4_Période</code> est un concept de haut niveau pour la documentation de phénomènes temporels portant sur des changements ou des interactions dans l'espace et dans le temps. Ceci inclut des périodes historiques (p. ex. Ming, Romaine) sans pour autant s'y limiter. <code class="language-plaintext highlighter-rouge">E4_Période</code> est l'objet de davantage de spécialisation grâce à une riche hiérarchie de processus et d'activités plus spécifiques. </p>
</li>
<li><p><code class="language-plaintext highlighter-rouge">E3_État_matériel</code> est une classe spécifique pour la documentation de phases statiques de choses physiques. Le CIDOC CRM ne décrit pas à l'heure actuelle de classe de haut niveau pour les phases statiques car ces dernières constituent la plupart du temps des déductions issues de multiples observations, sont souvent problématiques en termes d'intégration de l'information, et sont vulnérables à la révision non-monotone. </p>
</li></ul>
<p></p>
<p>Pour ces deux classes deux relations méréologiques sont articulées par le CIDOC CRM : </p>
<p></p>
<ul><li><p><em>Des relations de partie-tout</em> documentées entre des instances de <code class="language-plaintext highlighter-rouge">E3_État_matériel</code> grâce à la propriété <code class="language-plaintext highlighter-rouge">P5_consiste_en (fait_partie_de)</code>, et documentées entre des instances de <code class="language-plaintext highlighter-rouge">E4_Période</code> grâce à la propriété <code class="language-plaintext highlighter-rouge">P9_comprend (fait_partie_de)</code> (c.-à-d. pour décrire comment les phénomènes constituant l'instance de <code class="language-plaintext highlighter-rouge">E4_Période</code> peuvent être causalement sous-divisés en des phénomènes plus délimités);</p>
</li>
<li><p><em>Des relations de co-occurrence non-causale dans une même étendue spatio-temporelle</em> documentées grâce à la propriété <code class="language-plaintext highlighter-rouge">P10_s’insère_dans_le_cours_de</code><code class="language-plaintext highlighter-rouge"> </code><code class="language-plaintext highlighter-rouge">(contient)</code> [n.d.t. qui ne peut être utilisée dans ce contexte qu'avec des instances de <code class="language-plaintext highlighter-rouge">E4_Période</code>] (cette propriété est examinée davantage dans la section <a href="#des-relations-spatio-temporelles"><span class="underline">Des relations spatio-temporelles</span></a>). </p>
</li></ul>
<p></p>
<p>Les relations topologiques :</p>
<p></p>
<p>Plusieurs relations sémantiques on une incidence sur l'ordonnancement temporel d'entités temporelles (p. ex. le fait de rencontrer quelqu'un ne peut survenir qu'après la naissance et avant la mort des personnes impliquées, de l'information ne peut être transmise qu'après avoir été apprise). De plus, de l'information directe sur l'ordonnancement temporel d'entités peut avoir une incidence sur leurs relations sémantiques possibles ou impossibles. Ce type de raisonnement est d'une grande importance pour la recherche au sujet du passé. </p>
<p></p>
<p>Les relations temporelles définies dans « Maintaining knowledge about temporal intervals » (Allen 1983) et mobilisées dans les versions précédentes du CIDOC CRM ne permettent cependant pas de décrire adéquatement des inférences issues de relations sémantiques (voir la section <a href="#des-relations-temporelles-primitives-fondees-sur-des-frontieres-floues"><span class="underline">Des relations temporelles primitives fondées sur des frontières floues</span></a>). Le CIDOC CRM introduit donc ici une théorie des frontières floues dans un contexte temporel, ce qui permet l'inter-positionnement d'entités temporelles tout en prenant en compte l'aspect flou inhérent à ces entités. Ce modèle subsume les relations précédentes de Allen qui peuvent néanmoins toujours être utilisées dans les extensions du CIDOC CRM. </p>
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
<p></p>
<p></p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="1">
<p><em></em></p>
<p></p>
</td>
</tr>
</tbody>
</table>

<h3 id="des-relations-spatio-temporelles"><span class="en heading">Spatiotemporal Relations - </span>Des relations spatio-temporelles</h3>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>Treating space and time as separate entities is normally adequate for describing events and where things are. When more precise documentation and reasoning is required about phenomena spreading out over time, such as Bronze Age, a settlement, a nation, moving reference frames such as ships, things being stored in containers and moved around, built structures being partially destroyed, rebuilt and altered etc., space and time must be understood as a coherent continuum, the so-called spacetime. This is not a familiar concept for many users, and those not interested in such details may therefore skip this section.</p>
<p></p>
<iframe frameborder="0" style="width:100%;height:500px;" src="https://viewer.diagrams.net/?tags=%7B%7D&target=blank&highlight=0000ff&edit=_blank&layers=1&nav=1#G1odWIjnwTNN8rnQBe8y7z2D4FyVHsv-DB"></iframe>
<p><em>Figure 6: Basic CIDOC CRM Properties and Classes for Reasoning with Spacetime Volumes</em></p>
<p></p>
<p>However, the respective model the CIDOC CRM adopts constitutes a valid interface to the OGC standards, as elaborated in CRMgeo (Doerr & Hiebel 2013) and important for connecting to GIS applications. The key class CIDOC CRM provides for modelling this information is E92 Spacetime Volume. E92 Spacetime Volume is used to document geometric extents in the physical spacetime containing actual or possible positions of things or happenings, in particular in those cases when the changes of place to be documented cannot be reduced to distinct events, because the spatial extent changes continuously. The higher-level properties and classes of CIDOC CRM that centre around E92 Spacetime Volume allow for the documentation of: relations between spacetime volumes, relations to space and time as separate entities, and treating the exact extent of physical things and periods in space at any time of their existence as spacetime volumes. Its use is particularly elegant for the description of temporal gazetteers.</p>
<p><em></em></p>
<p><em>Defining a Spacetime Volume: </em>There are three ways to define a spacetime volume: </p>
<ul><li><p>the property <em>P169 defines spacetime volume </em>should be used to declare a spatiotemporal container for some things or happenings in terms of spatial coordinates that may vary over time, be it in discrete steps or continuously with the help of spacetime expressions. The latter are instances of E95 Spacetime Primitive, a primitive class for expressing values in data systems not further analyzed in the CIDOC CRM. </p>
</li>
<li><p>Instances of E4 Period are regarded to be specialized instances of E92 Spacetime Volume that are formed by the spreading out of the phenomena that make up an instance of E4 Period. As such they are fuzzy but in general observable. </p>
</li>
<li><p>The continuous sequence of spatial extent that the matter of an instance of E18 Physical Thing occupies in the course of time, defines a spacetime volume unique to it from the beginning of its existence to its end, which can also be understood as its trajectory through the universe The property <em>P169 defines </em>allows for referring to this spacetime volume, in order to document its additional properties. As such this spacetime volume is fuzzy but in general observable. It is not easy to make a mental picture of the spacetime volume of a physical thing, but the construct simplifies all reasoning about where things have been. </p>
</li></ul>
<p></p>
<p><em>Relations with Places and Physical Things: </em>The property <em>P161 has spatial projection</em> associates a spacetime volume with the complete spatial extent it has occupied during its time-span of definition. Due to relativity of space, the definition of an instance of E53 Place must be relative to some physical thing as geometric reference. This can explicitly be documented with the property <em>P157 is at rest relative to</em>. If the place where something is at a certain point in time is given in multiple reference spaces in relative movement, such as with respect to a ship versus to the seafloor, these differently defined places may later move apart. Therefore, a spacetime volume, even though uniquely defined, can have any number of spatial projections, depending on the reference space. Currently, the GPS system defines a default reference space on the surface of Earth. In art conservation and other descriptions of mobile object of fixed shape, it is useful to refer to the precise place a physical thing occupies with respect to itself as reference space via <em>P156 occupies</em>, for further analysis. <em>P156 occupies</em> constitutes a particular projection of the spacetime volume of this thing. In contrast, the property <em>P53 has former or current location</em> only describes that a thing was within a specific place given in some reference space for an undefined time. </p>
<p></p>
<p><em>Relations with Time-Spans and Periods:</em> The property <em>P160 has temporal projection</em> associates a spacetime volume with the complete temporal extent it has covered comprising all places of its definition. In contrast to places, the reference system of time is unique<sup>1</sup> except for the choice of origin. For instances of E4 Period and its subclasses, which inherit <em>P160 has temporal projection,</em> the property is actually identical with the property <em>P4 has time span</em> inherited from E2 Temporal Entity<em>, </em>because is describes the temporal extent of the phenomena that make up an instance of E4 Period. Therefore, it is recommended to use <em>P4 has time span</em> for instances of E4 Period and its subclasses, rather than <em>P160 has temporal projection</em>. </p>
<p></p>
<p><em>Relations of Presence:</em> Instances of E93 Presence are specialized instances of E92 Spacetime Volume that are identical with the spatial evolution of a larger spacetime volume specified by <em>P166 was presence of</em>, but delimited to a, normally short, time-span declared by <em>P164 is temporally specified by</em>. In other words, they constitute “snapshots” or “time-slices” of another spacetime volume, such as the extent of the Roman Empire during 30AD. They are the basic construct to describe exactly where something was or happened at a particular time (-span), in connection with the property <em>P161 has spatial projection.</em> In particular, it allows for describing the whereabouts of mobile objects, be it in the storage of a museum, a palace, deposited in the ground, or transported in a container, such as the bone of a saint. For ease of use, a shortcut <em>P195 was presence of</em> is defined directly to E18 Physical Thing, bypassing the definition of its spacetime volume.</p>
<p></p>
<p><em>Topological Relations: </em>Finally,<em> </em>the Model defines truly spatiotemporal topological relations. <em>P10 falls within (contains)</em> is the complete inclusion of one spacetime volume in another. It should not be confused with inclusion in the spatial and temporal projection, which may be larger. E.g., in 14 AD, Mesopotamia was not within the Roman Empire. Further, the properties <em>P132 spatiotemporally overlaps with </em>and its negation<em> P133 is spatiotemporally separated from </em>are fundamental to argue about temporary parthood, possible continuity etc.</p>
<p></p>
<hr><p></p>
<p></p>
<p><sup>1</sup>    This holds for applications in the scope of the CIDOC CRM, which are in the non-relativistic area, but not strictly, for instance, for satellites.</p>
</td>
<td>
<p>La plupart du temps, il est adéquat de traiter le temps et l'espace comme des entités distinctes lors de la description d'évènements et des lieux où ils se produisent. Une documentation et un raisonnement plus précis sont parfois requis afin de décrire des phénomènes se produisant dans la durée (p. ex. l'âge du bronze, un établissement, une nation, des cadres de référence pour les mouvements de bateaux, des choses étant entreposées dans des conteneurs puis déplacées, des constructions étant partiellement détruites, reconstruites ou altérées, etc.). L'espace et le temps doivent alors être conceptualisés sur un continuum cohérent : l'espace-temps (un concept avec lequel plusieurs ne sont pas familiers de sorte que l'utilisateur peut, s'il n'a pas d'intérêt pour ces questions, ne pas consulter cette section). </p>
<p></p>
<iframe frameborder="0" style="width:100%;height:500px;" src="https://viewer.diagrams.net/?tags=%7B%7D&target=blank&highlight=0000ff&edit=_blank&layers=1&nav=1#G1dRffzl0uDisnq-Pii3Xq14cMdaNL33xw"></iframe>
<p><em>Figure 6: Propriétés et classes fondamentales pour le raisonnement logique avec les volumes spatio-temporels</em></p>
<p></p>
<p>Le modèle du CIDOC CRM est une interface valide pour CRMgeo (Doerr & Hiebel 2013) qui mobilise les standards OGC [n.d.t. standards de l'Open Geospatial Consortium qui assurent l'interopérabilité dans les domaines de la géomatique et de l'information] qui sont essentiels à l'utilisation de systèmes d'information géographiques (applications SIG). </p>
<p></p>
<p>La classe clé qu'offre le CIDOC CRM pour la modélisation de telles informations est <code class="language-plaintext highlighter-rouge">E92_Volume_spatio-temporel</code> qui documente des étendues géométriques, situées dans l'espace-temps physique, qui contiennent des positions d'évènements ou de choses réelles ou possibles. <code class="language-plaintext highlighter-rouge">E92_Volume_spatio-temporel</code> est particulièrement utilisé dans des changements de lieux documentés ne peuvent pas être réduits à des évènements distincts en raison d'une étendue spatiale en changement (p. ex. dans la description d'index géographiques). Les classes et propriétés de haut niveau qui s'articulent autour de <code class="language-plaintext highlighter-rouge">E92_Volume_spatio-temporel</code> permettent de documenter : </p>
<p></p>
<ul><li><p>Les relations entre des espaces-temps; </p>
</li>
<li><p>Les relations à l'espace et au temps en tant qu'entités distinctes; </p>
</li>
<li><p>Le traitement de l'étendue exacte de choses physique et de périodes dans l'espace à tout moment de leur existence en tant que volume spatio-temporel.</p>
</li></ul>
<p></p>
<p><em>Définition d'un volume spatio-temporel</em></p>
<p></p>
<p>Il y a trois manières de définir un volume spatio-temporel : </p>
<p></p>
<ul><li><p>La propriété <code class="language-plaintext highlighter-rouge">P169_définit_le_volume_spatio-temporel (volume_spatio-temporel_défini_par)</code> déclare un contenant spatio-temporel pour un évènement ou une chose. Ce contenant est défini en termes de coordonnées spatiales qui peuvent varier à travers le temps, variation qui peut être représentée par des étapes distinctes ou de manière continue à l'aide d'expression de l'espace-temps qui prennent alors la forme d'instances de <code class="language-plaintext highlighter-rouge">E95_Primitive_spatio-temporelle</code> (une classe primitive pour l'expression de valeurs dans un système de données ne faisant pas l'objet d'analyses supplémentaires par le CIDOC CRM). </p>
</li>
<li><p>Plusieurs instances de <code class="language-plaintext highlighter-rouge">E4_Période</code>, instances spécialisées de <code class="language-plaintext highlighter-rouge">E92_Volume_spatio-temporel</code> qui sont floues tout en étant observables, forment un phénomène englobant qui prend lui aussi la forme d'une instance de <code class="language-plaintext highlighter-rouge">E4_Période</code>.</p>
</li>
<li><p>Une instance de <code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code> (en tant que séquence continue d'étendue spatiale occupée à travers le temps par la matière) définit un volume spatio-temporel unique du début à la fin de son existence, ce qui peut aussi être considéré comme sa trajectoire dans l'univers. La propriété <code class="language-plaintext highlighter-rouge">P169_définit_le_volume_spatio-temporel (volume_spatio-temporel_défini_par)</code> permet de référer à ce volume spatio-temporel afin d'en documenter des attributs supplémentaires. Ce volume spatio-temporel est donc flou tout en étant observable et, bien qu'il ne soit pas aisé de visualiser mentalement le volume spatio-temporel d'une chose physique, ceci simplifie grandement le raisonnement logique au sujet des lieux où se sont trouvé des choses. </p>
</li></ul>
<p></p>
<p><em>Relations d'un volume spatio-temporel à des lieux ou à des choses physiques</em></p>
<p></p>
<p>La propriété <code class="language-plaintext highlighter-rouge">P161_a_pour_projection_spatiale (est_la_projection_spatiale_de)</code> associe un volume spatio-temporel à l'étendue spatiale qu'elle a occupé durant l'intervalle temporel de la définition. En raison de la relativité de l'espace, la définition d'instances de <code class="language-plaintext highlighter-rouge">E53_Lieu</code> doit être relative à une chose physique utilisée comme référence géométrique, une relation documentée par la propriété <code class="language-plaintext highlighter-rouge">P157_est_à_l’arrêt_par_rapport_à (procure_un_espace_de_référence_pour)</code>. Si l'emplacement d'une chose à un certain moment est disponible pour de multiples espaces relatifs de référence en mouvement (p. ex. dans le cas d'un bateau par rapport au sol marin), ces espaces définis différemment peuvent éventuellement s'éloigner ou se disjoindre les uns des autres. Ainsi, un volume spatio-temporel, même s'il est défini de manière unique, peut avoir de nombreuses projections spatiales qui dépendent de l'espace de référence. </p>
<p></p>
<p>Les systèmes de géo-positionnement satellite (GPS) actuels définissent par défaut la surface de la Terre comme espace de référence. Dans le cas de descriptions d'objets mobiles dont la forme est fixe, comme dans le contexte de conservation d'art, il est parfois utile de désigner l'endroit précis d'une chose physique par rapport à elle-même en l'utilisant comme espace de référence de concert avec la propriété <code class="language-plaintext highlighter-rouge">P156_occupe (est_occupé_par)</code>. Cette dernière constitue une projection particulière du volume spatio-temporel de la chose en question. Elle se distingue de <code class="language-plaintext highlighter-rouge">P53_a_pour_localisation_actuelle_ou_antérieure (est_localisation_actuelle_ou_antérieure_de)</code> qui ne décrit que le fait qu'une chose se trouvait dans un lieu spécifique par rapport à une référence spatiale sans précision temporelle. </p>
<p></p>
<p><em>Relations d'un volume spatio-temporel à des intervalles temporels et à des périodes</em></p>
<p></p>
<p>La propriété <code class="language-plaintext highlighter-rouge">P160_a_pour_projection_temporelle (est_la_projection_temporelle_de)</code> associe un volume spatio-temporel à l'étendue temporelle complète que ce volume a recoupé, y compris tous les lieux de sa définition. Contrairement aux lieux [n.d.t. dont les coordonnées de référence peuvent changer à travers le temps], le système de référence temporel est unique<sup>1</sup> à l'exception du choix d'origine.</p>
<p></p>
<p>Comme les sous-classes de <code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code> héritent de la propriété <code class="language-plaintext highlighter-rouge">P4_a_pour_intervalle_temporel (est_l’intervalle_temporel_de)</code>, les instances de <code class="language-plaintext highlighter-rouge">E4_Période</code> et de ses sous-classes héritent de la propriété <code class="language-plaintext highlighter-rouge">P160_a_pour_projection_temporelle (est_la_projection_temporelle_de)</code> qui lui est équivalente car elles décrivent toutes deux l'étendue temporelle du phénomène qui constitue une instance de <code class="language-plaintext highlighter-rouge">E4_Période</code>. Il est donc recommandé, [n.d.t. à des fins de simplicité], d'utiliser <code class="language-plaintext highlighter-rouge">P4_a_pour_intervalle_temporel (est_l’intervalle_temporel_de)</code> de concert avec des instances de <code class="language-plaintext highlighter-rouge">E4_Période</code> et de ses sous-classes plutôt que d'utiliser <code class="language-plaintext highlighter-rouge">P160_a_pour_projection_temporelle (est_la_projection_temporelle_de)</code>.</p>
<p></p>
<p><em>Relations de présence</em></p>
<p>Les instances de <code class="language-plaintext highlighter-rouge">E93_Présence</code> sont des instances spécialisées de <code class="language-plaintext highlighter-rouge">E92_Volume_spatio-temporel</code> qui sont identiques à l'évolution spatiale d'un volume spatio-temporel plus large spécifié par la propriété <code class="language-plaintext highlighter-rouge">P166_a_été_une_présence_de (a_eu_pour_présence)</code>, mais délimité par un intervalle temporel généralement court par la propriété <code class="language-plaintext highlighter-rouge">P164_est_temporellement_spécifié_par (était_l’intervalle_temporel_de)</code>. Il s'agit donc d'instantanés ou de « tranches » temporelles d'un autre volume spatio-temporel (p. ex. l'étendue de l'empire romain durant l'année 30 EC). Les instances de <code class="language-plaintext highlighter-rouge">E93_Présence</code> sont donc des construits spécifiques de modélisation qui décrivent précisément où une chose s'est produite ou s'est trouvée à un moment ou interval temporel particulier, et ce grâce à la propriété <code class="language-plaintext highlighter-rouge">P161_a_pour_projection_spatiale (est_la_projection_spatiale_de)</code>. Ce construit particulier permet de décrire les emplacements d'objets mobiles à différentes étapes (p. ex. l'os d'un saint qui s'est trouvé dans un réserve muséale, dans un palace, dans le sol, ou transporté dans un conteneur). À des fins de simplicité, un raccourci pour <code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code> est défini directement à travers l'usage de la propriété <code class="language-plaintext highlighter-rouge">P195_a_été_une_présence_de (a_eu_pour_présence)</code>, ce qui permet d'outrepasser la définition de son volume spatio-temporel. </p>
<p></p>
<p><em>Relations topologiques</em></p>
<p></p>
<p>Finalement, le modèle définit des relations topologiques spatio-temporelles grâce à l'usage de la propriété <code class="language-plaintext highlighter-rouge">P10_s’insère_dans_le_cours_de</code><code class="language-plaintext highlighter-rouge"> </code><code class="language-plaintext highlighter-rouge">(contient)</code> qui inclut entièrement un volume spatio-temporel dans un autre. Ceci n'équivaut cependant pas à l'inclusion de projections temporelles et spatiales qui peuvent être de plus grande ampleur (p. ex. en 14 EC, la mésopotamie n'était pas dans l'empire romain). En outre, la propriété <code class="language-plaintext highlighter-rouge">P132_recoupe_spatio-temporellement</code>  et sa négation <code class="language-plaintext highlighter-rouge">P133_est_distinct_spatio-temporellement_de</code> sont fondamentales lorsqu'il est question de continuité possible, de relation partie-tout, etc. </p>
<p></p>
<hr><p></p>
<p></p>
<p><sup>1</sup>    Ceci s'applique aux applications du domaine du CIDOC CRM qui sont de nature non-relativiste, mais ne s'applique pas strictement, par exemple, aux satellites. </p>
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
<p></p>
<p></p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="1">
<p><em></em></p>
<p></p>
</td>
</tr>
</tbody>
</table>

<h2 id="construits-specifiques-de-modelisation"><span class="en heading">Specific Modelling Constructs - </span>Construits spécifiques de modélisation</h2>

<h3 id="des-types"><span class="en heading">About Types - </span>Des Types</h3>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>Virtually all structured descriptions of museum objects begin with a unique object identifier and information about the "type" of the object, often in a set of fields with names like "Classification", "Category", "Object Type", "Object Name", etc. All these fields are used for terms that declare that the object belongs to a particular category of items. In the CIDOC CRM the class E55 Type comprises such terms from thesauri and controlled vocabularies used to characterize and classify instances of CIDOC CRM classes.  Instances of E55 Type represent concepts (universals) in contrast to instances of E41 Appellation, which are used to name instances of CIDOC CRM classes.</p>
<p></p>
<p>For this purpose, the CIDOC CRM provides two basic properties that describe classification with terminology, corresponding to what is the current practice in the majority of information systems. The class E1 CRM Entity is the domain of the property <em>P2 has type (is type of)</em>, which has the range E55 Type. Consequently, every class in the CIDOC CRM, with the exception of E59 Primitive Value, inherits the property <em>P2 has type (is type of).</em> This provides a general alternative mechanism to specialize the classification of CIDOC CRM instances to any level of detail, by linking to external vocabulary sources, thesauri, classification schemas or ontologies. </p>
<p></p>
<p>Analogous to the function of the <em>P2 has type (is type of)</em> property, some properties in the CIDOC CRM are associated with an additional property. These are numbered in the CIDOC CRM documentation with a ‘.1’ extension. The range of these properties of properties always falls under E55 Type. The purpose of a property of a property is to provide an alternative mechanism to specialize its domain property through the use of property subtypes declared as instances of E55 Type. They do not appear in the property hierarchy list but are included as part of the property declarations and referred to in the class declarations. For example, <em>P62.1 mode of depiction</em>: E55 Type is associated with E24 Physical Man-made Thing. <em>P62 depicts (is depicted by): </em>E1 CRM Entity.</p>
<p></p>
<p>The class E55 Type also serves as the range of properties that relate to categorical knowledge commonly found in cultural documentation. For example, the property <em>P125 used object of type (was type of object used in)</em> enables the CIDOC CRM to express statements such as “this casting was produced using a mould”, meaning that there has been an unknown or unmentioned object, a mould, that was actually used. This enables the specific instance of the casting to be associated with the entire type of manufacturing devices known as moulds. Further, the objects of type “mould” would be related via <em>P2 has type (is type of)</em> to this term. This indirect relationship may actually help in detecting the unknown object in an integrated environment. On the other side, some casting may refer directly to a known mould via <em>P16 used specific object (was used for).</em>  So, a statistical question to how many objects in a certain collection are made with moulds could be answered correctly (following both paths through <em>P16 used specific object (was used for)</em> - <em>P2 has type (is type of)</em> and <em>P125 used object of type (was type of object used in)</em>. This consistent treatment of categorical knowledge enhances the CIDOC CRM’s ability to integrate cultural knowledge.</p>
<p></p>
<p>Types, that is, instances of E55 Type and its subclasses, can be used to characterize the instances of a CIDOC CRM class and hence refine the meaning of the class.  A type ‘artist’ can be used to characterize persons through <em>P2 has type (is type of)</em>.  On the other hand, in an art history application of the CIDOC CRM it can be adequate to extend the CIDOC CRM class E21 Person with a subclass E21.xx Artist. What is the difference of the type ‘artist’ and the class Artist? From an everyday conceptual point of view there is no difference. Both denote the concept ‘artist’ and identify the same set of persons. Thus, in this setting a type could be seen as a class and the class of types may be seen as a metaclass.  Since current systems do not provide an adequate control of user defined metaclasses, the CIDOC CRM prefers to model instances of E55 Type as if they were particulars, with the relationships described in the previous paragraphs.</p>
<p></p>
<p>Users may decide to implement a concept either as a subclass extending the CIDOC CRM class system or as an instance of E55 Type. A new subclass should only be created in case the concept is sufficiently stable and associated with additional explicitly modelled properties specific to it. Otherwise, an instance of E55 Type provides more flexibility of use. Users that may want to describe a discourse not only using a concept extending the CIDOC CRM but also describing the history of this concept itself, may choose to model the same concept both as subclass and as an instance of E55 Type with the same name. Similarly, it should be regarded as good practice to foresee for each term hierarchy refining a CIDOC CRM class a term equivalent of this class as top term. For instance, a term hierarchy for instances of E21 Person may begin with “Person”.</p>
<p></p>
<p>One role of E55 Type is to be the CIDOC CRM’s interface to domain specific ontologies and thesauri or less formal terminological systems. Such sets of concepts can be represented in the CIDOC CRM as subclasses of E55 Type, forming hierarchies of terms, i.e., instances of E55 Type linked via <em>P127 has broader term (has narrower term).</em> Such hierarchies may be extended with additional properties. Other standard models, in particular richer ones, used to describe terminological systems can also be interfaced with the CIDOC CRM by declaring their respective concept class as being equivalent to E55 Type, and their respective broader/narrower relation as being identical with <em>P127 has broader term (has narrower term)</em>, as long as they are semantically compatible.</p>
<p></p>
<p>In addition to being an interface to external thesauri and classification systems, E55 Type is an ordinary class in the CIDOC CRM and a subclass of E28 Conceptual Object. E55 Type and its subclasses inherit all properties from this superclass.  Thus, together with the CIDOC CRM class E83 Type Creation the rigorous scholarly or scientific process that ensures a type is exhaustively described and appropriately named can be modelled inside the CIDOC CRM. In some cases, particularly in archaeology and the life sciences, E83 Type Creation requires the identification of an exemplary specimen and the publication of the type definition in an appropriate scholarly forum. This is very central to research in the life sciences, where a type would be referred to as a “taxon,” the type description as a “protologue,” and the exemplary specimens as “original element” or “holotype”.</p>
<p></p>
<p>Finally, instances of E55 Type or suitable subclasses can describe universals from type systems not organized in thesauri or ontologies, such as industrial product names and types, defined and published by the producers themselves for each new product or product variant.</p>
</td>
<td>
<p>La plupart des descriptions structurées d'objets muséaux sont initiées par la création d'un identifiant et d'information au sujet du type de cet objet, information qui est recensée dans des champs tels que « classification », « catégorie », « type d'objet », « nom d'objet », etc. Ces champs sont utilisés afin de recenser des termes qui déclarent que l'objet appartient à une catégorie particulière. Dans le CIDOC CRM, la classe <code class="language-plaintext highlighter-rouge">E55_Type</code> accommode de tels termes issus de vocabulaires contrôlés et de thésauri utilisés afin de classifier et de caractériser des instances de classes du CIDOC CRM.  Ces instances de <code class="language-plaintext highlighter-rouge">E55_Type</code> représentent des concepts (universaux) qui se distinguent d'instances de <code class="language-plaintext highlighter-rouge">E41_Appellation</code> qui sont utilisées pour nommer les instances de classes du CIDOC CRM. </p>
<p></p>
<p>Le CIDOC CRM offre à cette fin deux propriétés de base qui décrivent une classification terminologique et qui correspondent aux pratiques courantes de la majorité des systèmes d'information : </p>
<p></p>
<ul><li><p>La propriété <code class="language-plaintext highlighter-rouge">P2_a_pour_type (est_type_de)</code> qui a pour domaine la classe <code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code> et pour portée la classe <code class="language-plaintext highlighter-rouge">E55_Type</code>. Ainsi, chaque classe du CIDOC CRM à l'exception de <code class="language-plaintext highlighter-rouge">E59_Valeur_primitive</code> hérite la propriété <code class="language-plaintext highlighter-rouge">P2_a_pour_type (est_type_de)</code>. Ceci offre un mécanisme alternatif à la spécialisation de la classification des instances du CIDOC CRM à des niveaux de détails divers en pointant plutôt vers des sources externes sous la forme de vocabulaires, de thésauri, de schèmes de classification ou d'ontologies. </p>
</li>
<li><p>Certaines propriétés du CIDOC CRM sont supplémentées d'une fonction analogue à <code class="language-plaintext highlighter-rouge">P2_a_pour_type (est_type_de)</code> et identifiées par le suffixe « <code class="language-plaintext highlighter-rouge">.1</code> ». La fonction d'une propriété de propriété est d'offrir un mécanisme alternatif à la spécialisation du domaine d'une propriété par l'usage de sous-types déclarés sous forme d'instances de <code class="language-plaintext highlighter-rouge">E55_Type</code>. ces propriétés « <code class="language-plaintext highlighter-rouge">.1</code> » n'apparaissent pas dans la <a href="/cidoc_crm_fr-ca/v7.1/information/application-formelle#liste-hierarchisee-des-proprietes-du-cidoc-crm"><span class="underline">Liste hiérarchisée des propriétés du CIDOC CRM</span></a>, mais elles sont incluses dans les déclarations de <a href="/cidoc_crm_fr-ca/v7.1/classes/declaration-des-classes-du-cidoc-crm"><span class="underline">classes</span></a> et de <a href="/cidoc_crm_fr-ca/v7.1/proprietes/declaration-des-proprietes-du-cidoc-crm"><span class="underline">propriétés</span></a>.  Par exemple, <code class="language-plaintext highlighter-rouge">P62.1_mode_d'illustration</code> : <code class="language-plaintext highlighter-rouge">E55_Type</code> est associé avec <code class="language-plaintext highlighter-rouge">E24_Chose_matérielle_élaborée_par_l’humain</code> . <code class="language-plaintext highlighter-rouge">P62_illustre (est_illustré_par)</code> : <code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code>. </p>
</li></ul>
<p></p>
<p>La classe est la portée des propriétés qui portent sur des savoirs catégorisés fréquemment présents dans la documentation patrimoniale. Par exemple, la propriété permet au CIDOC CRM d'exprimer des énoncés tels que « ce moulage a été produit grâce à un moule », ce qui veut dire qu'un objet inconnu ou non-mentionné (le moule) a été utilisé. Ceci permet à l'instance spécifique du moulage d'être associée à des types d'appareils manufacturiers, les moules. De plus, les objets de type « moule » peuvent être reliés à ce terme par la propriété <code class="language-plaintext highlighter-rouge">P2_a_pour_type (est_type_de)</code>. Cette relation indirecte soutient la détection d'objets inconnus dans un environnement intégré. D'autre part, certains moulages peuvent référer directement à un moule particulier par l'entremise de la propriété <code class="language-plaintext highlighter-rouge">P16_a_mobilisé_l’objet_spécifique (a_été_mobilisé_pour)</code> de telle sorte qu'une interrogation statistique quant au nombre d'objets d'une collection issus de moules pourrait être résolue correctement (grâce à deux chemins : <code class="language-plaintext highlighter-rouge">P16_a_mobilisé_l’objet_spécifique (a_été_mobilisé_pour)</code> - <code class="language-plaintext highlighter-rouge">P2_a_pour_type (est_type_de)</code> et <code class="language-plaintext highlighter-rouge">P125_a_mobilisé_un_objet_du_type (a_été_le_type_d’objet_employé_pour)</code>). Ce traitement cohérent de l'information catégorisée accroît la capacité du CIDOC CRM d'intégrer de l'information culturelle. </p>
<p></p>
<p>Les instances de <code class="language-plaintext highlighter-rouge">E55_Type</code> et de ses sous-classes peuvent être utilisés pour caractériser les instances de classe du CIDOC CRM de manière à en affiner la définition. Un type « artiste » peut être utilisé pour caractériser une personne grâce à la propriété <code class="language-plaintext highlighter-rouge">P2_a_pour_type (est_type_de)</code>, par exemple. Mais il serait aussi possible, dans le contexte de l'histoire de l'art, d'étendre la classe <code class="language-plaintext highlighter-rouge">E21_Personne</code> avec une sous-classe <code class="language-plaintext highlighter-rouge">E21.xx_Artiste</code>. D'un point de vue conceptuel, il n'y a pas de différence notable entre le type « artiste » et la classe Artiste car tous deux dénotent le concept « artiste » et identifient le même ensemble de personnes. Dans ce contexte, un type pourrait être envisagé comme une classe et une classe de types pourrait être considérée comme une métaclasse. Cependant, puisque les systèmes actuels ne permettent pas un contrôle adéquat de métaclasses définies par des utilisateurs, le CIDOC CRM préfère modéliser des instances de <code class="language-plaintext highlighter-rouge">E55_Type</code> comme si elles étaient des particuliers, et ce grâce aux relations décrites dans les paragraphes précédents. </p>
<p></p>
<p>Les utilisateurs peuvent choisir d'implémenter un concept en tant qu'instance de <code class="language-plaintext highlighter-rouge">E55_Type</code> ou en tant que sous-classe étendant le système de classes du CIDOC CRM. Cette dernière option ne devrait être privilégiée que si le concept qu'elle représente est suffisamment stable et associé à des propriétés additionnelles qui lui sont spécifiques et qui sont explicitement modelées (sans quoi l'usage de <code class="language-plaintext highlighter-rouge">E55_Type</code> est préférable). Il est aussi possible que des utilisateurs souhaitent décrire un discours en étendant un concept du CIDOC CRM et en décrivant l'histoire de ce concept : ils peuvent alors modéliser ce même concept à la fois en tant que sous-classe et en tant qu'instance de <code class="language-plaintext highlighter-rouge">E55_Type</code> du même nom. Il est de même recommandé d'entrevoir pour chaque hiérarchie de termes affinant une classe de CIDOC CRM un terme englobant équivalent à cette classe (p. ex. une hiérarchie de termes pour des instances de <code class="language-plaintext highlighter-rouge">E21_Personne</code> pourrait débuter avec « personne »). </p>
<p></p>
<p><code class="language-plaintext highlighter-rouge">E55_Type</code> agit comme une interface entre le CIDOC CRM et les domaines spécifiques d'ontologies, de thésauri, et de systèmes terminologiques moins formels. De tels ensembles de concepts peuvent être représentés dans le CIDOC CRM comme des sous-classes de afin de former des hiérarchies de termes (c.-à-d. des instances de <code class="language-plaintext highlighter-rouge">E55_Type</code> liées par l'entremise de <code class="language-plaintext highlighter-rouge">P127_a_pour_terme_général (a_pour_terme_spécifique)</code>). De telles hiérarchies peuvent en outre être supplémentées de propriétés. D'autres standards peuvent aussi être utilisés afin de décrire des systèmes terminologiques du moment que ces modèles sont sémantiquement compatibles avec le CIDOC CRM : il faut alors déclarer leurs classes conceptuelles comme équivalentes à <code class="language-plaintext highlighter-rouge">E55_Type</code> et leurs relations de généralité-spécificité comme équivalentes à <code class="language-plaintext highlighter-rouge">P127_a_pour_terme_général (a_pour_terme_spécifique)</code>. </p>
<p></p>
<p>Dans certains cas, en particulier en archéologie ou en sciences de la vie, <code class="language-plaintext highlighter-rouge">E83_Création_de_type</code> nécessite l’identification d’un spécimen de référence et la publication de la définition de son type dans un forum de discussion scientifique approprié. L’activité modélisée comme une instance de <code class="language-plaintext highlighter-rouge">E83_Création_de_type</code> est essentielle à la recherche en sciences de la vie. Dans ce domaine, le  « taxon » fait référence au type, le « protologue » à la description du type et le « type original » ou « holotype » aux spécimens de référence</p>
<p></p>
<p>Finalement, des instances de <code class="language-plaintext highlighter-rouge">E55_Type</code> ou de ses sous-classes peuvent décrire des éléments universaux depuis des systèmes de catégorisation qui ne prennent pas la forme d'ontologies ou de thésauri, comme c'est le cas de types et de noms de produits industriels qui sont définis et publiés par leurs producteurs pour chaque nouveau produit ou dérivé. </p>
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
<th><p><em>Références</em></p>
</th>
<td colspan="1">
</td>
</tr>
</tbody>
</table>

<h3 id="des-relations-temporelles-primitives-fondees-sur-des-frontieres-floues"><span class="en heading">Temporal Relation Primitives based on fuzzy boundaries - </span>Des relations temporelles primitives fondées sur des frontières floues</h3>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>It is characteristic for sciences dealing with the past, such as history, archaeology or geology, to derive temporal topological relations from stratigraphic and other observations and from considerations of causality between events. For this reason, the CIDOC CRM introduced in version 3.3 the whole set of temporal relationships of Allen’s temporal logic (the now deprecated properties P114 to P120). It was regarded at that time as a well-justified, exhaustive and sufficient theory to deal with temporal topological relationships of spatiotemporal phenomena relevant to cultural historical discourse. Allen’s temporal logic is based on the assumption of known, exact endpoints of time intervals (time-spans), described by an exhaustive set of mutually exclusive relationships. </p>
<p></p>
<p>Since many temporal relations can be inferred from facts causal to them, e.g., a birth necessarily occurring before any intentional interaction of a person with other individuals, or from observations of material evidence without knowing the absolute time, the temporal relationships pertain in the CIDOC CRM to E2 Temporal Entities, and not their Time-Spans, which require knowledge of absolute time. If absolute times are known, deduction of Allen’s relation is a simple question of automated calculus and not the kind of primary scientific insight the CIDOC CRM, as a core model, is interested in. However, their application turned out to be problematic in practice for two reasons:</p>
<p></p>
<p><strong>Firstly,</strong> facts causal to temporal relationships result in expressions that often require a disjunction (logical OR condition) of Allen’s relationships. For instance, a child may be stillborn. Ignoring states at pregnancy as it is usual in older historical sources, birth may be <em>equal to</em> death, <em>meet</em> with death or be <em>before</em> death. The knowledge representation formalism chosen for the CIDOC CRM however does <strong>not allow</strong> for specifying <strong>disjunctions</strong>, except within queries. Consequently, simple properties of the CIDOC CRM that imply a temporal order, such as <em>P134 continued</em>, cannot be declared as subproperties of the temporal relationship they do imply, which would be, in this case: “before, meets, overlaps, starts, started-by, contains, finishes, finished-by, equals, during or overlapped by” (see <em>P174 starts before the end of</em>).  </p>
<p></p>
<p><strong>Secondly, </strong>nature does not allow us to observe equality of points in time. There are three possible interpretations to this fact. Common to all three interpretations is that they can be described in terms of fuzzy boundaries. The model proposed here is consistent with <strong>all</strong> three of these interpretations.</p>
<ul><li><p>Any observable phenomenon that can be dated has a <strong>natural temporal extent</strong> with <strong>fuzzy boundaries</strong> of <strong>gradual transition</strong> from not existing to definitely existing and then to no longer existing. </p>
</li>
<li><p>These fuzzy boundaries can also be interpreted as the time intervals about which experts, even with a complete knowledge of the described phenomenon, may not agree as to whether this phenomenon is already ongoing or not, or still ongoing or not. </p>
</li>
<li><p>Under a third interpretation, the fact that an instance of E2 Temporal Entity is ongoing is <strong>not observable</strong> within the fuzzy boundaries. </p>
</li></ul>
<p></p>
<p>Consider, for instance, a birth. Extending over a limited and non-negligible duration in the scale of hours it begins and ends gradually (1), but can be given alternative scientific definitions of start and end points (2), and neither of these can be determined with a precision much smaller than on a scale of minutes (3). The fuzzy boundaries <strong>do not</strong> describe the relation of incomplete or imprecise knowledge to reality. Assuming a lowest granularity in time is an approach which does not help, because the relevant extent of fuzziness varies at a huge scale even in cultural reasoning, depending on the type of phenomena considered. The only exact match is between arbitrarily declared time intervals, such as the end of a year being equal to the beginning of the next year, or that “Early Minoan” ends exactly when “Middle Minoan” starts, whenever that might have been. Consequently, we introduce here a new set of “temporal relation primitives” with the following characteristics:</p>
<ul><li><p>It is a minimal set of properties that allows for specifying all possible relations between two time intervals given by their start and end points, either directly, or by conjunction (logical AND condition) of the latter. </p>
</li>
<li><p>Start and end points are interpreted as “thick” fuzzy boundaries as described above. </p>
</li>
<li><p>Conditions of equality of end points are relaxed to the condition that the fuzzy boundaries <strong>overlap</strong>. Therefore, knowledge of the shape of the fuzzy function is <strong>not</strong> needed.</p>
</li>
<li><p>All of Allen’s relationships can be expressed either directly or by conjunctions of these properties.</p>
</li>
<li><p>In case of time intervals without or with negligibly short fuzzy boundaries, all of Allen’s relationships can exactly be described by adequate conjunctions of these properties.</p>
</li>
<li><p>No relationship is equal to the inverse of another. Inverses are specified by exchanging the roles of domain and range.</p>
</li></ul>
</td>
<td>
<p>Il est fréquent que des sciences traitant du passé, comme l'histoire, l'archéologie ou la géologie, dérivent des relations topologiques depuis des stratigraphies, d'autres observations ou des causalités entre des évènements. La version 3.3 du CIDOC CRM a donc intégré des ensembles de relations temporelles basés sur la logique de Allen (les propriétés maintenant dépréciées <code class="language-plaintext highlighter-rouge">P114_est_temporellement_équivalent_à</code>, <code class="language-plaintext highlighter-rouge">P115_termine (est_terminé_par)</code>, <code class="language-plaintext highlighter-rouge">P116_commence (est_commencé_par)</code>, <code class="language-plaintext highlighter-rouge">P117_se_produit_durant (comprend)</code>, <code class="language-plaintext highlighter-rouge">P118_recoupe_temporellement (est_recoupé_temporellement_par)</code>, <code class="language-plaintext highlighter-rouge">P119_rencontre_temporellement (est_rencontré_temporellement_par)</code> et <code class="language-plaintext highlighter-rouge">P120_se_produit_avant (se_produit_après)</code>) qui était à l'époque la théorie la plus exhaustive et adéquate pour traiter de relations topologiques ayant égard à des phénomènes spatio-temporels de nature historique et culturelle. La logique temporelle de Allen émane de l'idée que les frontières d'intervalles temporels sont connues et décrites par un ensemble exhaustif de relations mutuellement exclusives. </p>
<p></p>
<p>Néanmoins, plusieurs relations temporelles peuvent être induites de faits (p. ex. la  naissance d'une personne précède nécessairement son interaction intentionnelle avec une autre) ou d'observations effectuées sur des éléments matériels dont la temporalité absolue est inconnue. C'est la raison pour laquelle les relations temporelles du CIDOC CRM s'articulent autour des entités <code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code> et non des entités <code class="language-plaintext highlighter-rouge">E52_Intervalle_temporel</code>, lesquelles nécessitent la connaissance d'une temporalité absolue. Dans l'éventualité où une temporalité absolue est connue, la déduction des relations de Allen relève de calculs automatisés plutôt que de considérations scientifiques (ces dernières constituant le cœur du CIDOC CRM). Cependant, l'application de ces calculs est problématique pour deux raisons : </p>
<p></p>
<p>En premier lieu, les faits de causalité pertinents à des relations temporelles résultent fréquemment en des expressions qui nécessitent une disjonction (condition logique « ou ») des relations d'Allen. Par exemple, un enfant peut être mort-né. En faisant fi des étapes de la grossesse comme c'est souvent le cas dans les sources historiques, la naissance peut être considérée soit comme un évènement égal à la mort, soit comme une rencontre avec la mort, soit comme un évènement qui précède la mort. La représentation formelle choisie ne doit cependant pas permettre de spécifier des disjonctions sauf dans le cadre de requêtes. Par conséquent, de simples propriétés du CIDOC CRM qui impliquent un ordre temporel, comme <code class="language-plaintext highlighter-rouge">P134_a_continué (a_été_continué_par)</code>, ne peuvent pas être déclarées sous-propriétés de relations temporelles qu'elles impliquent, ce qui équivaudrait à « avant, rencontre, chevauche, commence, commencé par, contient, termine, terminé par, équivaut, durant ou chevauché par » (voir <code class="language-plaintext highlighter-rouge">P174_commence_avant_la_fin_de (se_termine_après_le_début_de)</code>). </p>
<p></p>
<p>En second lieu, il n'est pas naturellement possible d'observer l'égalité de points temporels, un fait qui peut être interprété de trois manières qui impliquent toutes des frontières floues et qui sont toutes cohérentes avec la version actuelle du CIDOC CRM : </p>
<p></p>
<ul><li><p>Tout phénomène observable qui peut être daté a une étendue temporelle naturelle marquée par des frontières floues qui établissent une transition graduelle depuis un état de non-existence vers un état d'existence établie suivie d'un état d'existence révolue. </p>
</li>
<li><p>Ces frontières floues peuvent aussi être interprétées comme des intervalles temporels au sujet desquels des experts peuvent être en désaccord quant à l'état (déjà en cours ou non, toujours en cours ou non), et ce même s'ils ont une connaissance complète d'un phénomène en question. </p>
</li>
<li><p>Le fait qu'une instance de <code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code> soit en cours n'est pas observable durant ces frontières temporelles floues. </p>
</li></ul>
<p></p>
<p>Par exemple : </p>
<p></p>
<ul><li><p>Un accouchement a une durée limitée et non-négligeable de plusieurs heures durant laquelle l'évènement commence et se termine graduellement; </p>
</li>
<li><p>Son début et sa fin peuvent être qualifiés de définitions scientifiques déterminant leurs points temporels; </p>
</li>
<li><p>Ni l'un ni l'autre de ces points temporels ne peut être déterminé plus précisément qu'à l'échelle des minutes. </p>
</li></ul>
<p></p>
<p>Les frontières floues ne décrivent pas la relation entre la réalité et des connaissances incomplètes ou imprécises et adopter une granularité temporelle inférieure ne résout pas ce problème puisque l'étendue floue pertinente varie grandement en fonction du phénomène considéré, y compris dans le contexte culturel. La seule équivalence exacte est entre des intervalles temporels déclarés arbitrairement (p. ex. la fin d'une année étant le début de la suivante, la fin du minoen ancien étant le début du minoen moyen peu importe le moment où celui-ci a commencé). Conséquemment, un nouvel ensemble de relations temporelles primitives est doté des caractéristiques suivantes : </p>
<p></p>
<ul><li><p>Cet ensemble minimal de propriétés permet de spécifier toutes les relations possibles entre deux intervalles temporels tels qu'ils sont définis par leur point de début et de fin, que ce soit directement ou par conjonction (condition logique « et »); </p>
</li>
<li><p>Les points de début et de fin sont interprétés comme des frontières floues « épaisses »; </p>
</li>
<li><p>Les conditions d'égalité des points temporels externes sont étendues au point où les frontières floues se recouvrent de sorte que la connaissance de la forme de la fonction floue n'est pas nécessaire; </p>
</li>
<li><p>Toutes les relations d'Allen peuvent être exprimées directement ou par conjonction des propriétés concernées; </p>
</li>
<li><p>Dans le cas des intervalles temporels n'ayant pas de frontières floues courtes ou n'en ayant que des négligeables, toutes les relations de Allen peuvent être décrites par des conjonctions adéquates des propriétés concernées; </p>
</li>
<li><p>Aucune relation n'est l'équivalent de l'inverse d'une autre de sorte que les inverses sont plutôt spécifiées par l'inversion du domaine et de la portée. </p>
</li></ul>
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
<p>La traduction des propriétés dépréciées (<code class="language-plaintext highlighter-rouge">P114_est_temporellement_équivalent_à</code>, <code class="language-plaintext highlighter-rouge">P115_termine (est_terminé_par)</code>, <code class="language-plaintext highlighter-rouge">P116_commence (est_commencé_par)</code>, <code class="language-plaintext highlighter-rouge">P117_se_produit_durant (comprend)</code>, <code class="language-plaintext highlighter-rouge">P118_recoupe_temporellement (est_recoupé_temporellement_par)</code>, <code class="language-plaintext highlighter-rouge">P119_rencontre_temporellement (est_rencontré_temporellement_par)</code> et <code class="language-plaintext highlighter-rouge">P120_se_produit_avant (se_produit_après)</code>) est basée sur les libellés originaux de la version 6.2. </p>
<p></p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="1">
<p>Le Bœuf, Patrick, Martin Doerr, Christian-Emil Ore, et Stephen Stead, éd. <em>Definition of the CIDOC Conceptual Reference Model</em>. CIDOC CRM Documentations, 6.2. Paris, FR-IDF: CIDOC CRM  Special Interest Group, 2015.<a href="https://cidoc-crm.org/sites/default/files/cidoc_crm_version_6.2.pdf"><span class="underline"> </span></a><a href="https://cidoc-crm.org/sites/default/files/cidoc_crm_version_6.2.pdf"><span class="underline">https://cidoc-crm.org/sites/default/files/cidoc_crm_version_6.2.pdf</span></a>.</p>
<p></p>
</td>
</tr>
</tbody>
</table>

<p style="font-size:20px;margin-bottom:15px;"><span class="en heading">Notation - </span>Notation</p>
<!-- <h4 id="notation"><span class="en heading">Notation - </span>Notation</h4> -->
<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>We use the following notation:</p>
<p></p>
<p>Comparing two instances of E2 Temporal Entity, we denote one with capital letter A, its (fuzzy) starting time with A<sup>start</sup> and its (fuzzy) ending time with A<sup>end</sup>, such that A = [A<sup>start</sup>,A<sup>end</sup>]; we denote the other with capital letter B, its (fuzzy) starting time with B<sup>start</sup> and its (fuzzy) ending time with B<sup>end</sup>, such that B = [B<sup>start</sup>,B<sup>end</sup>].</p>
<p></p>
<p>We identify a temporal relation with a predicate name (label) and define it by one or more (in)equality expressions between its end points, such as:</p>
<p></p>
<p>A <em>starts before the end of</em> B if and only if (⇔) <strong>A</strong><sup><strong>start</strong></sup><strong> < B</strong><sup><strong>end</strong></sup></p>
<p><strong> </strong> </p>
<p>We visualize a temporal relation symbolizing the temporal extents of two instances A and B of E2 Temporal Entity as horizontal bars, considered to be on a horizontal time-line proceeding from left to right. The fuzzy boundary areas are symbolized by an increasing/decreasing color gradient. The different choices of relative arrangement the relationship allows for are symbolized by two extreme allowed positions of instance A with respect to instance B connected by arrows. The reader may imagine it as the relative positions of a train A approaching a station B. If the relative length of A compared to B matters, two diagrams are provided.</p>
<p></p>
<iframe frameborder="0" style="width:100%;height:500px;" src="https://viewer.diagrams.net/?tags=%7B%7D&target=blank&highlight=0000ff&edit=_blank&layers=1&nav=1#G1FBKzKPqqjl6PMW3a9xrOoa7IHQ6M-6Yu"></iframe>
<p><em>Figure 7: Explanation of Interior and Boundary and an Example of Use from P174 starts before the end of (ends after the start of).</em><sup>1</sup></p>
<p></p>
<hr><p></p>
<p></p>
<p><sup>1</sup>    The original version of this diagram is devoid of text and reproduced below in the « Note traducteur » section. The amended version available in version 7.1.1 has been reproduced here. </p>
</td>
<td>
<p>Lors de la comparaison de deux instances de <code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code> l'une est identifiée par une lettre majuscule suivie de ses début et fin (flous) indiqués en exposants (A<sup>Début</sup>, A<sup>Fin</sup>) de telle sorte que A = [A<sup>Début</sup>, A<sup>Fin</sup>] et B = [B<sup>Début</sup>, B<sup>Fin</sup>].</p>
<p></p>
<p>La relation temporelle est identifée à l'aide d'un prédicat nommé (libellé) défini par une ou plusieurs expressions d'(in)égalité entre les points terminaux de telle sorte que : </p>
<p></p>
<p>A <em>commence avant la fin de </em>B si et seulement si (⇔) A<sup>Début</sup> < B<sup>Fin</sup></p>
<p></p>
<p>Les relations temporelles symbolisant les étendues temporelles de deux instances de <code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code> A et B sont illustrées à l'aide de barres horizontales conçues comme une ligne du temps horizontale se lisant depuis la gauche vers la droite. Les frontières floues sont illustrées par une saturation de couleur croissante ou décroissante. </p>
<p></p>
<p>Les différentes options d'ordonnancement relatif que permet la relation sont illustrés par deux positions extrêmes de l'instance A par rapport à l'instance B connectées par des flèches. Ceci pourrait par exemple représenter les positions relatives d'un train A approchant une station B. </p>
<p></p>
<p>Dans l'éventualité où la longueur de A eut égard à B est d'intérêt, deux diagrammes sont disponibles : </p>
<p></p>
<iframe frameborder="0" style="width:100%;height:500px;" src="https://viewer.diagrams.net/?tags=%7B%7D&target=blank&highlight=0000ff&edit=_blank&layers=1&nav=1#G1SK82juKreQyOfYp7mG2huU4VOY1BiY7R"></iframe>
<p><em>Figure 7: Explication des concepts d'intérieur et de frontière ainsi qu'example de l'utilisation de</em> <code class="language-plaintext highlighter-rouge">P174_commence_avant_la_fin_de (se_termine_après_le_début_de)</code></p>
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
<p>Le diagramme de la figure 7 dans la version 7.1 n'ayant pas de texte, c'est celui de la version 7.1.1 qui a été utilisée en lieu et place du diagramme initial reproduit ci-dessous: </p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="1">
</td>
</tr>
</tbody>
</table>

<p style="font-size:20px;margin-bottom:15px;"><span class="en heading">Overview of Temporal Relation Primitives - </span>Aperçu des relations temporelles primitives</p>
<!-- <h4 id="notation"><span class="en heading">Overview of Temporal Relation Primitives - </span>Aperçu des relations temporelles primitives</h4> -->
<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>The final set of temporal relation primitives can be separated into two groups: </p>
<p></p>
<ul><li><p>Those based on improper inequalities, such as A<sup>start</sup> ≤ B<sup>end</sup> (odd number items in the list below- table 1)  </p>
</li>
<li><p>Those based on proper inequalities, such as A<sup>start</sup> < B<sup>end</sup> (even number items in the list below- table 1).</p>
</li></ul>
<p></p>
<p>Improper inequalities with fuzzy boundaries are understood as extending into situations in which the fuzzy boundaries of the respective endpoints may overlap. In other words, they include situations in which it cannot be decided when one interval has ended and when the other started, but there is no knowledge of a definite gap between these endpoints. In a proper inequality with fuzzy boundaries, the fuzzy boundaries of the respective endpoints must not overlap, i.e., there is knowledge of a definite gap between these endpoints, for instance, a discontinuity between settlement phases based on the observation of archaeological layers. </p>
</td>
<td>
<p>L'ensemble final de relations primitives temporelles peut être divisé en deux groupes :</p>
<p></p>
<ul><li><p>Les relations qui se fondent sur des inégalités impropres comme A<sup>Début</sup> ≤ B<sup>Fin</sup> (les entités dont les nombres sont impairs dans le tableau ci-dessous); </p>
</li>
<li><p>Les relations qui se fondent sur des inégalités propres comme A<sup>Début</sup> < B<sup>Fin</sup> (les entités dont les nombres sont pairs dans le tableau ci-dessous). </p>
</li></ul>
<p></p>
<p>Les inégalités impropres ayant des frontières floues sont acceptées s'étendre à des situations dans lesquelles les frontières floues des points d'arrivée respectifs peuvent se chevaucher. Ils incluent donc des situations lors desquelles il est impossible de déterminer quand un intervalle a terminé et quand un autre a commencé, et où il n'y a pas de décalage déterminé entre ces points. </p>
<p></p>
<p>Les inégalités propres ayant des frontières floues ne peuvent avoir de points d'arrivée qui se chevauchent de sorte qu'il y a un décalage connu entre les points d'arrivée (p. ex. une discontinuité entre l'établissement de phases fondée sur l'observation de couches archéologiques). </p>
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
<th><p><em>Références</em></p>
</th>
<td colspan="1">
</td>
</tr>
</tbody>
</table>

<table>
<tbody>
<tr>
<td class="en">
<p></p>
</td>
<td class="en">
<p>Property</p>
</td>
<td class="en">
<p></p>
</td>
<td>
<p></p>
</td>
<td>
<p>Propriété</p>
</td>
<td>
<p>Interprétation</p>
</td>
</tr>
<tr>
<td class="en">
<p>1<em></em></p>
</td>
<td class="en">
<p><strong>P173 starts before or with the end of</strong></p>
</td>
<td class="en">
<p></p>
</td>
<td>
<p>1</p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">P173_commence_avant_ou_au_moment_de_la_fin_de (se_termine_après_ou_au_moment_du_début_de)</code></p>
</td>
<td>
<p>A<sup>Début</sup> ≤ B<sup>Fin</sup></p>
</td>
</tr>
<tr>
<td class="en">
<p>2</p>
</td>
<td class="en">
<p><strong>P174 starts before the end of</strong></p>
</td>
<td class="en">
<p></p>
</td>
<td>
<p>2</p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">P174_commence_avant_la_fin_de (se_termine_après_le_début_de)</code></p>
</td>
<td>
<p>A<sup>Début</sup> < B<sup>Fin</sup></p>
</td>
</tr>
<tr>
<td class="en">
<p>3</p>
</td>
<td class="en">
<p><strong>P175 starts before or with the start of</strong></p>
</td>
<td class="en">
<p></p>
</td>
<td>
<p>3</p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">P175_commence_avant_ou_au_moment_du_début_de (commence_après_ou_au_moment_du_début_de)</code> </p>
</td>
<td>
<p>A<sup>Début</sup> ≤ B<sup>Début</sup></p>
</td>
</tr>
<tr>
<td class="en">
<p>4</p>
</td>
<td class="en">
<p><strong>P176 starts before the start of</strong></p>
</td>
<td class="en">
<p></p>
</td>
<td>
<p>4</p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">P176_commence_avant_le_début_de (commence_après_le_début_de)</code> </p>
</td>
<td>
<p>A<sup>Début</sup> < B<sup>Début</sup></p>
</td>
</tr>
<tr>
<td class="en">
<p>5</p>
</td>
<td class="en">
<p><strong>P182 ends before or with the start of</strong></p>
</td>
<td class="en">
<p></p>
</td>
<td>
<p>5</p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">P182_se_termine_avant_ou_au_moment_du_début_de (commence_après_ou_au_moment_de_la_fin_de)</code> </p>
</td>
<td>
<p>A<sup>Fin</sup> ≤ B<sup>Début</sup></p>
</td>
</tr>
<tr>
<td class="en">
<p>6</p>
</td>
<td class="en">
<p><strong>P183 ends before the start of</strong></p>
</td>
<td class="en">
<p></p>
</td>
<td>
<p>6</p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">P183_se_termine_avant_le_début_de (commence_après_la_fin_de)</code> </p>
</td>
<td>
<p>A<sup>Fin</sup> < B<sup>Début</sup></p>
</td>
</tr>
<tr>
<td class="en">
<p>7</p>
</td>
<td class="en">
<p><strong>P184 ends before or with the end of</strong></p>
</td>
<td class="en">
<p></p>
</td>
<td>
<p>7</p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">P184_se_termine_avant_ou_au_moment_de_la_fin_de (se_termine_au_moment_ou_après_la_fin_de)</code> </p>
</td>
<td>
<p>A<sup>Fin</sup> ≤ B<sup>Fin</sup></p>
</td>
</tr>
<tr>
<td class="en">
<p>8</p>
</td>
<td class="en">
<p><strong>P185 ends before the end of</strong></p>
</td>
<td class="en">
<p></p>
</td>
<td>
<p>8</p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">P185_se_termine_avant_la_fin_de (se_termine_après_la_fin_de)</code> </p>
</td>
<td>
<p>A<sup>Fin</sup> < B<sup>Fin</sup></p>
</td>
</tr>
</tbody>
</table>

