---
layout: page
title: Principes de modélisation
titleEn: Modelling principles - Principes de modélisation
permalink: /v7.1/information/principes-de-modelisation
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
<p>The following modelling principles have guided and informed the development of the CIDOC CRM. </p>
</td>
<td>
<p>Les principes de modélisation suivants ont guidé le développement du CIDOC CRM. </p>
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

<h2 id="de-la-realite-des-bases-de-connaissance-et-du-cidoc-crm"><span class="en heading">Reality, Knowledge Bases and CIDOC CRM - </span>De la réalité, des bases de connaissance et du CIDOC CRM</h2>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>The CIDOC CRM is a formal ontology in the sense introduced by (Guarino, 1998).<sup>4</sup> The present document is intended to embrace an audience not specialized in computer science and logic; therefore, it focuses on the informal semantics and on the pragmatics of the CIDOC CRM concepts, offering a detailed discussion of the main traits of the conceptualization underlying the CIDOC CRM through basic usage patterns.<sup>5</sup> The CIDOC CRM aims to assist sharing, connecting and integrating information from research about the past. In order to understand the function of a formal ontology of this kind, one needs to make the following distinctions:</p>
<ul><li><p>The <em>material reality</em>. For the purpose of the CIDOC CRM, material reality is regarded as whatever has substance that can be perceived with senses or instruments. Examples are people, a forest or a settlement environment, sea, atmosphere, distant celestial or cellular micro structures, including what we assume could be potentially or theoretically perceived if we could be there, such as the center of Earth or the sun, and all that is past. It is constrained to space and time. What goes on in <em>our minds</em> or is produced by our minds is also regarded as part of the material reality, as it becomes materially evident to other people at least by our utterances, behavior and products. </p>
</li>
<li><p>The units of description or <em>particulars</em>, i.e., the things and relations which we refer to in order to distinguish parts of reality. Examples are Mount Ida, the Taj Mahal, the formation of China by emperor Qin Shi Huang (秦始皇) in 221BC, Tut-Ankh Amun and his embalming, Prince Shotoku of Japan sending a mission to China in 607AD, the participation of Socrates in the Battle of Potidaea or the radiocarbon dating of the Iceman Ötzi (Kutschera, 2002).</p>
</li></ul>
<p>A formal ontology, such as the CIDOC CRM, constitutes a controlled language for talking about particulars. I.e., it provides classes and properties for categorizing particulars as so-called “instances” in a way that their individuation, unity and relevant properties are as unambiguous as possible.  For instance, Tut-Ankh Amun as instance of E21 Person <em>is</em> the real pharaoh from his birth to death, and not extending to his mummy, as follows from the specification of the class E21 Person and its properties in the CIDOC CRM. </p>
<p>For clarification, the CIDOC CRM does not take a position against or in favour of the existence of spiritual substance nor of substance not accessible by either senses or instruments, nor does it suggest a materialistic philosophy. However, for practical reasons, it relies on the priority of integrating information based on material evidence available for whatever human experience. The CIDOC CRM only commits to a unique material reality independent from the observer. </p>
<p>When we <em>provide descriptions</em> of particulars, we need to refer to them by unique names, titles or constructed identifiers, all of which are instances of E41 Appellation in the CIDOC CRM, in order for the reference to be independent of the context. (In contrast, reference to particulars by pronouns or enumerations of characteristic properties, such as name and birth date, are context dependent). The appellation, and the relation between the appellation and the referred item or relationship, must not be confused with the referred item and its identity. For example, Tut-Ankh Amun the name (instance of E41 Appellation) is different from Tut-Ankh Amun the person (instance of E21 Person) and also different from the relationship between name and person (<em>P1 is identified by</em>). Instances of CIDOC CRM classes are the <em>real </em>particulars, not their names, but in descriptions, names must be used as surrogates for the real things meant. Particulars are approximate individuations, like sections, of parts of reality. In other words, the uniqueness of reality does not depend on where one draws the line between the mountain and the valley.</p>
<p>A CIDOC CRM-compatible <em>knowledge base</em> (KB) (Meghini & Doerr 2018) is an instance of E73 Information Object in the CIDOC CRM. It contains (data structures that encode) formal statements representing propositions believed to be true in a reality by an observer. These statements use appellations (e.g., http://id.loc.gov/authorities/names/n79066005<sup>6</sup>) of ontological particulars and of CRM concepts (e.g., <em>P100i died in</em>). Thereby users, in their capacity of having real-world knowledge and cognition, may be able to relate these statements to the propositions they are meant to characterize, and be able to reason and research about their validity. In other words, the formal instances in a knowledge base are the <em>identifiers</em>, not the real things or phenomena. </p>
<p>A special case is digital content: a KB in a computer system may contain statements about instances of E90 Symbolic Object and the real thing may be text residing within the same KB. The instance of E90 Symbolic Object and its textual representation are separate entities and they can be connected with the property <em>P190 has symbolic content.</em></p>
<p>Therefore, a knowledge base does not contain knowledge, but <em>statements that represent</em> knowledge, as long as there exist people that can resolve the identifiers used to their referents. (Appellations described in a knowledge base, and not used as primary substitutes of other items, are of course explicitly declared as instances of E41 Appellation in the knowledge base.) </p>
<hr><p><sup>4</sup> Nicola Guarino defines a formal ontology as a specification of a set of named concepts used to describe and approximate a part of reality, plus a first-order logical theory narrowing down the intended meaning of the named concepts.</p>
<p><sup>5</sup> For the readers interested in computer science and logic, the syntax and formal semantics employed by the CIDOC CRM are given in (Meghini & Doerr 2018), where the computational aspects are also discussed.</p>
<p><sup>6</sup> The URI (instance of E41 Appellation) of the Library of Congress for Tut-Ankh-Amun, the pharaoh.</p>
</td>
<td>
<p>Le CIDOC CRM est une ontologie formelle dans le sens que l’a introduit (Guarino, 1998)<sup>4</sup>. Ce document est destiné à une audience qui n’est spécialiste ni de la logique ni des sciences informatiques, de sorte qu’il se concentre sur la sémantique informelle et sur les aspects pragmatiques des concepts du CIDOC CRM. Il s’agit d’une discussion détaillée, à travers des patrons conceptuels fondamentaux<sup>5</sup>, des principes qui sous-tendent le CIDOC CRM, une ontologie qui a pour objectif de partager, de connecter et d’intégrer de l’information issue de recherches sur le passé. Afin de comprendre la fonction d’une telle ontologie formelle, les distinctions suivantes sont nécessaires : </p>
<ul><li><p>La <em>réalité matérielle</em> est entendue comme étant tout ce qui a une substance qui peut être perçue par le biais des sens ou d’instruments; ceci est limité par l’espace et le temps. Ceci inclut, par exemple, des peuples, une forêt, un environnement où s’établissent des personnes, la mer, l'atmosphère, des micro-structures célestes ou cellulaires, notamment ce qui pourrait être potentiellement ou théoriquement perçu en présence, par exemple le centre de la terre ou du soleil et tout ce qui est passé. Ce qui se produit <em>dans</em> l’esprit ou est le produit <em>de</em> l’esprit est aussi reconnu comme faisant partie de la réalité matérielle dans la mesure où ce produit devient matériellement évident pour les autres par le biais d’énonciations, de comportements et de produits. </p>
</li>
<li><p>Les unités de description, ou <em>éléments particuliers</em> sont les choses et relations auxquelles il est fait référence afin de distinguer des éléments de la réalité. Ceci inclut le Mont Ida, le Taj Mahal, la formation de la Chine par l’empereur Qin Shi Huang (秦始皇) en 221 AEC, Toutânkhamon et son embaumement, le prince Shōtoku du Japon envoyant une délégation en Chine en 607 EC, la participation de Socrate à la bataille de Potidaea ou encore la datation radiocarbone d’Ötzi (Kutschera, 2002).</p>
</li></ul>
<p>Une ontologie formelle telle que le CIDOC CRM constitue en fait un langage contrôlé pour parler d’éléments particuliers, c.-à-d. qu’elle offre des <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#classe"><span class="underline">classes</span></a> et <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#propriete"><span class="underline">propriétés</span></a> permettant de catégoriser ces éléments particuliers comme des « <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#instance"><span class="underline">instances</span></a> », de sorte que leur individuation, leur unité et les propriétés pouvant leur être associées de manière pertinente soient aussi claires que possible. Par exemple, Toutânkhamon comme instance de <code class="language-plaintext highlighter-rouge">E21_Personne</code> <em>est</em> ce pharaon depuis sa naissance jusqu’à sa mort, mais n’est pas sa momie conformément à la définition de la classe <code class="language-plaintext highlighter-rouge">E21_Personne</code> et de ses propriétés. </p>
<p>Le CIDOC CRM ne statue pas sur l’existence ou l’inexistence d’une substance spirituelle, ni sur l’existence ou l’inexistence d’une substance qui ne soit pas accessible par les sens ou par des instruments, et ne statue pas non plus en faveur d’une philosophie matérialiste. Cependant, pour des raisons pratiques, le CIDOC CRM repose sur la nécessité d’intégrer de l’information issue d’éléments matériels qui peuvent être appréhendés du fait de l’expérience humaine. Le CIDOC CRM renvoie en ce sens à une réalité matérielle indépendante de l’observateur. </p>
<p>Lorsque des <em>descriptions </em>d’éléments particuliers<em> </em>sont disponibles, leurs identifiants, noms ou titres uniques (toutes des instances de <code class="language-plaintext highlighter-rouge">E41_Appellation</code> dans CIDOC CRM) sont utilisés [n.d.t afin qu’ils soient conceptualisés de manière générique (le concept) plutôt que spécifique (le concept tel qu’il se déploie dans un contexte particulier)]. Au contraire, les éléments particuliers évoqués à l’aide de pronoms ou d’énumération de leurs propriétés caractéristiques (comme le nom et la date de naissance) sont spécifiques (ils s’appuient sur le contexte particulier de leur mention). L’appellation ainsi que la relation [n.d.t (ou le lien)] entre l’appellation et l’entité à laquelle elle réfère diffèrent en effet de l’entité elle-même et de son identité. Par exemple, le nom Toutânkhamon (instance de <code class="language-plaintext highlighter-rouge">E41_Appellation</code>) diffère de la personne Toutânkhamon (instance de <code class="language-plaintext highlighter-rouge">E21_Personne</code>) qui diffère aussi du lien qui unit la personne à son nom (<code class="language-plaintext highlighter-rouge">P1_est_identifié_par</code>). Les instances de CIDOC CRM sont donc les <em>réels</em> éléments particuliers (plutôt que leurs noms), bien que dans les descriptions les noms doivent être utilisés à titre d’auxiliaires. Les éléments particuliers sont ainsi des différenciations approximatives de parts de la réalité (comme des sections de celle-ci). En d’autres termes, la réalité a un caractère unique qui est indépendant de toute conceptualisation (p. ex. le fait qu’il y ait une montagne adjacente à une vallée ne dépend pas de la frontière arbitraire qui les distingue).</p>
<p>Une base de connaissances (BC) compatible avec CIDOC CRM (Meghini & Doerr 2018) est une instance de <code class="language-plaintext highlighter-rouge">E73_Objet_informationnel</code> qui contient des énoncés formels (structures d’encodage de données) représentant des affirmations considérées vraies dans le contexte d’une réalité par un observateur. Ces énoncés utilisent les appellations (p. ex. http://id.loc.gov/authorities/names/n79066005<sup>6</sup>) de concepts ontologiques spécifiques ou de concepts de CIDOC CRM (p. ex. <code class="language-plaintext highlighter-rouge">P100i_est_mort_par</code>). Les utilisateurs, de par leur connaissance du monde réel et leur cognition, peuvent établir des liens entre ces énoncés formels et les affirmations auxquelles ils réfèrent pour les examiner de plus près et évaluer leur validité. </p>
<p>Le contenu numérique fait cependant classe à part, car une BC peut contenir des énoncés au sujet d’instances de <code class="language-plaintext highlighter-rouge">E90_Objet_symbolique</code> dont la réelle incarnation existe dans la BC elle-même. L’instance de <code class="language-plaintext highlighter-rouge">E90_Objet_symbolique</code> et sa représentation textuelle sont cependant des entités distinctes qui peuvent néanmoins être liées par la propriété <code class="language-plaintext highlighter-rouge">P190_a_pour_contenu_symbolique</code>. </p>
<p>Une base de connaissances ne contient donc pas les connaissances elles-mêmes, mais bien les énoncés qui représentent ces connaissances tant et aussi longtemps que des personnes en mesure de résoudre les identifiants à leur référents sont présentes. Les appellations décrites dans une base de connaissances et qui ne sont pas utilisées comme auxiliaires principaux d’autres entités sont néanmoins toujours déclarées comme des instances de <code class="language-plaintext highlighter-rouge">E41_Appellation</code> dans la base de connaissances. </p>
<hr><p><sup>4</sup> Nicola Guarino définit une ontologie formelle comme la spécification d’un ensemble de concepts nommés et utilisés pour déterminer par approximation et pour décrire une part de la réalité, spécification à laquelle s’ajoute une théorie logique du premier ordre précisant la signification prévue de ces mêmes concepts nommés. </p>
<p><sup>5</sup> Les lecteurs intéressés par les sciences informatiques, la logique, la syntaxe et la sémantique formelles utilisées par le CIDOC CRM peuvent consulter (Meghini & Doerr 2018) qui examine les aspects computationnels de l’ontologie.</p>
<p><sup>6</sup> L’URI (instance de <code class="language-plaintext highlighter-rouge">E41_Appellation</code>) de la Library of Congress pour le pharaon Toutânkhamon.</p>
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
<p>Office québécois de la langue française. « base de connaissances ». Dans <em>Grand dictionnaire terminologique</em>. Québec, CA-QC: Office québécois de la langue française, 2017.<a href="http://gdt.oqlf.gouv.qc.ca/ficheOqlf.aspx?Id_Fiche=8366746"><span class="underline"> </span></a><a href="http://gdt.oqlf.gouv.qc.ca/ficheOqlf.aspx?Id_Fiche=8366746"><span class="underline">http://gdt.oqlf.gouv.qc.ca/ficheOqlf.aspx?Id_Fiche=8366746</span></a>.</p>
</td>
</tr>
</tbody>
</table>

<h2 id="de-lauctorialite-des-contenus-dune-base-de-connaissances"><span class="en heading">Authorship of Knowledge Base Contents - </span>De l’auctorialité des contenus d’une base de connaissances</h2>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>This section describes a recommended good practice how to relate authority to knowledge base contents.</p>
<p>Statements in a KB must have been inserted by some human agent, either directly or indirectly. However, these statements often make no reference to that agent, lacking attribution of authority. An example of such statements in the CIDOC CRM is information expressed through shortcuts such as <em>P2 has type</em>. In the domain of cultural heritage, it is common practice that the responsibility for maintaining knowledge in the KB is elaborated in institutional policy or protocol documents. Thus, it is reasonable to hold that statements which lack explicit authority attribution can be read as the official view of the administrating institution of that system, i.e., the maintainers of the KB. This does not imply that the knowledge described in the KB is complete. So long as the information is under active management, it remains continuously open to revision and improvement as further research reveals further understandings.<sup>7</sup> A KB does not represent a slice of reality, but the justified beliefs of its maintainers about that reality. For simplicity, we speak about a KB as representing some reality.</p>
<p>Statements in a KB may also carry explicit references to agents that produced them, i.e., further statements of responsibility. In CIDOC CRM such statements of responsibility are expressed through knowledge creation events such as E13 Attribute Assignment and its relevant subclasses. Any knowledge that is about an explicit knowledge creation event, where the creator’s identity has been given, is implicitly attributed to be correctly referred to in the KB by the maintaining authority, whereas the responsibility for the content created by that event is assigned to the agent identified as causal to that event.</p>
<p>In the special case of an institution taking over stewardship of a database transferred into their custody, two relations of responsibility for the knowledge therein can be envisioned. If the institution accepts the dataset and undertakes to maintain and update it, then they take on responsibility for that information and become the default authority behind its statements as described above. If, on the other hand, the institution accepts the data set and stores it without change as a closed resource, then it can be considered that the default authority remains the original steward like for any other scholarly document kept by the institution.</p>
<hr><p><sup>7</sup> Statements in a KB may be in contradiction to the ontologically defined quantification of properties without the KB being broken or invalid in any sense, either because necessary properties are unknown or there exist good reasons to assume alternative values for properties with limited cardinality, be it by the same or by different maintainers.</p>
</td>
<td>
<p>Cette section présente les pratiques exemplaires qui s'appliquent lors de la liaison de contenu d’autorité aux contenus d’une base de connaissances (BC). </p>
<p>Les énoncés d’une BC doivent avoir été introduits par un agent humain de manière directe ou indirecte, mais ils ne font souvent pas explicitement référence à cet agent, de sorte que l’autorité sous laquelle une information a été émise n’est pas établie (c’est le cas, par exemple, lors de l’utilisation de raccourcis tels que <code class="language-plaintext highlighter-rouge">P2_a_pour_type</code>). Dans le domaine patrimonial, la responsabilité du maintien des informations dans la base de connaissances repose la plupart du temps sur des politiques institutionnelles ou des protocoles documentaires. Il est donc raisonnable de conclure que des affirmations dénuées d’une référence explicite à leur auteur constituent néanmoins le point de vue officiel de l’institution administrant le système (c.-à-d. le responsable de la BC). Ceci n’implique pas pour autant que les savoirs représentés dans la BC sont complets ou exhaustifs, de sorte que, tant que l’information fait l’objet d’un maintien actif, elle est sujette à des révisions et à des améliorations au gré de l’avancement de la recherche et de la compréhension qui en est faite<sup>7</sup>. Une BC ne représente en effet pas une part de la réalité, mais bien la conception que s’en font raisonnablement ces responsables même si, à des fins de simplicité, il est souvent indiqué qu’une BC représente une réalité. </p>
<p>Les énoncés d’une BC peuvent toutefois avoir des références explicites aux agents qui les ont produits (c.-à-d. des énoncés de responsabilité supplémentaires [n.d.t. qui s’ajoutent à l’énoncé institutionnel implicite]). Dans CIDOC CRM, de tels énoncés de responsabilité prennent la forme d’évènements de création de connaissances par le biais de <code class="language-plaintext highlighter-rouge">E13_Assignation_d'attribut</code> ou de l’une de ses sous-classes pertinentes. Lorsqu’un évènement de création de connaissances comporte un énoncé indiquant explicitement qui est son auteur, l’autorité de cet évènement est attribuée à l’institution responsable du maintien de la BC alors que le contenu résultant de cet évènement est attribué à l’agent l’ayant initié.</p>
<p>Lorsqu’une institution prend à sa charge une base de données dans le cadre d’un transfert de sa garde d’une autorité administrative à une autre, deux relations de responsabilité sur les connaissances de cette BC sont possibles. Si l’institution hôte accepte la responsabilité du maintien des informations, elle devient l’autorité associée par défaut aux énoncés qui s’y trouvent. Si, par contre, l’institution hôte traite l’ensemble des données comme une ressource « fermée » [n.d.t. donc traité à la manière d’un artéfact], l’autorité associée par défaut aux énoncés qui s’y trouvent sera celle de l’institution initiale (comme c’est le cas de tout autre document de recherche se trouvant dans la collection de l’institution hôte). </p>
<p>[n.d.t. voir « <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#processus-de-creation-de-connaissances"><span class="underline">Processus de création de connaissances</span></a> » dans la section <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie"><span class="underline">Terminologie</span></a>.]</p>
<hr><p><sup>7</sup> Les énoncés se trouvant dans une BC peuvent entrer en contradiction avec la quantification ontologique des propriétés sans que cette BC ne soit pour autant dysfonctionnelle ou invalidée. Une telle situation pourrait survenir soit parce que des propriétés sont inconnues, soit parce qu’il est raisonnable pour l’institution ou personne responsable du maintien de penser que des valeurs alternatives sont possibles pour des propriétés dotées d’une cardinalité limitée. </p>
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

<h2 id="des-extensions-de-cidoc-crm"><span class="en heading">Extensions of CIDOC CRM - </span>Des extensions de CIDOC CRM</h2>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>Since the intended scope of the CIDOC CRM is a subset of the “real” world and is therefore potentially infinite, the model has been designed to be extensible through the linkage of compatible external type hierarchies.</p>
<p>Of necessity, some concepts covered by the CIDOC CRM are defined in less details than others: E39 Actor and E30 Right, for example. This is a natural consequence of staying within the model’s clearly articulated practical scope in an intrinsically unlimited domain of discourse. These ‘underdeveloped’ concepts can be considered as candidate superclasses for compatible extensions, in particular for disciplines with a respective focus. Additions to the model are known as extensions while the main model is known as CRMbase.</p>
<p>Compatibility of extensions with the CRM means that data structured according to an extension must also remain valid as instances of CIDOC CRM base classes. In practical terms, this implies query containment: any queries based on CIDOC CRM concepts to a KB should retrieve a result set that is correct according to the model’s semantics, regardless of whether the KR is structured according to the CIDOC CRM’s semantics alone, or according to the CIDOC CRM plus compatible extensions. For example, a query such as “list all events” should recall 100% of the instances deemed to be events by the CIDOC CRM, regardless of how they are classified by the extension.</p>
<p>A sufficient condition for the compatibility of an extension with the CIDOC CRM is that its classes, other than E1 CRM Entity, subsume all classes of the extension, and all properties of the extension are either subsumed by CRM properties, or are part of a path for which a CIDOC CRM property is a shortcut, and that classes and properties of the extension can be well distinguished from those in the CIDOC CRM. For instance, a class “tangible object” may be in conflict with existing classes of the CIDOC CRM. Obviously, such a condition can only be tested intellectually.</p>
<p>The CRM provides a number of mechanisms to ensure that coverage of the intended scope can be increased on demand without losing compatibility: </p>
<ul><li><p>Existing classes can be extended, either structurally as subclasses or dynamically using the type hierarchy (see section About Types below).</p>
</li>
<li><p>Existing properties can be extended, either structurally as subproperties, or in some cases, dynamically, using properties of properties which allow subtyping (see section About Types below).</p>
</li>
<li><p>Additional information that falls outside the semantics formally defined by the CIDOC CRM can be recorded as unstructured data using E1 CRM Entity. <em>P3 has note</em>: E62 String. </p>
</li>
<li><p>Extending the CIDOC CRM by superclasses and properties that pertain to a wider scope. They are called conservative extensions, if they preserve backwards compatibility with instances described with the CIDOC CRM. </p>
</li></ul>
<p>Following strategies 1, 2 and 3 will have the result that the CIDOC CRM concepts subsume and thereby cover the extensions. This means that querying an extended knowledge base only with concepts of the CIDOC CRM will nevertheless retrieve all facts described via the extensions. </p>
<p><strong>In mechanism 3</strong>, the information in the notes is accessible in the respective knowledge base by retrieving the instances of E1 CRM Entity that are domain of <em>P3 has note</em>. Keyword search will also work for the content of the note. Rules should be applied to attach a note to the item most specific for the content. For instance, details about the role of an actor in an activity should be associated with the instance of E7 Activity, and not with the instance of E39 Actor. This approach is preferable when queries relating elements from the content of such notes across the knowledge base are not expected. </p>
<p>In general, only concepts to be used for selecting multiple instances from the knowledge base by formal querying need to be explicitly modelled. This criterion depends on the expected scope and use of the particular knowledge base. The CIDOC CRM prioritizes modelling the kinds of facts one would like to retrieve and relate from heterogeneous content sources, potentially from different institutions. It does not, by way of contrast, focus on the modelling of facts with a more local scope such as the administrative practices internal to an institution.</p>
<p><strong>Mechanism 4</strong>, conservative extension, is more complex: </p>
<p> </p>
<p>With increasing use of the CIDOC CRM, there is also a need for extensions that model phenomena from a scope wider than the original one of the CIDOC CRM, but which are also applicable to the concepts that do fall within the CIDOC CRM’s scope. When this occurs, properties of the CIDOC CRM may be found to be applicable more generally to superclasses of the extension than to those of their current domain or range in the CIDOC CRM. This is a consequence of the key principle of the CIDOC CRM to model “bottom up”, i.e., selecting the domains and ranges for properties to be as narrow as they would apply in a well understood fashion in the current scope, thus avoiding making poorly understood generalizations at risk of requiring non-monotonic correction. </p>
<p>The fourth mechanism for extending the CIDOC CRM by conservation extension can be seen to be split into two cases:</p>
<p>1) A new class or property is added to an extension of the CIDOC CRM, which is not covered by superclasses other than E1 CRM Entity or a superproperty in the CIDOC CRM respectively. In this case, all facts described only by such concepts are <em>not</em> accessible by queries with CIDOC CRM concepts. Therefore, the extension should <em>publish</em> in a compatibility statement the additional relevant high-level classes and properties needed to retrieve all facts documented with the extended model. This case is a monotonic extension.</p>
<p>2) The domain or range of an existing property in the CIDOC CRM is changed to a superclass of the one or the other or both, because the property is understood to be applicable beyond its originally anticipated scope. In this case, all facts described by the extension are still accessible by querying with the concepts of the CIDOC CRM, but the extension can describe additional facts that the CIDOC CRM could not. This case is a monotonic extension and generally recommended, because it enables bottom-up evolution of the model. If this change is part of a new release of the CIDOC CRM itself, it is simply backwards compatible, and this has been done frequently in the evolution of this model. </p>
<p>If case (2) should be documented and implemented in an extension module <strong>separate from</strong> the CIDOC CRM, it may come in conflict with the current way knowledge representation languages, such as RDF/OWL, treat it, because in formal logic changing the range or domain of a property is regarded <strong>as</strong> changing the ontological meaning <strong>completely;</strong> there is no distinction betwe<strong>en the meaning of the property independent of domain and range and the specification of the domain and range</strong>. It is, however, similar to what in logic is called a conservative extension of a theory, and necessary for an effective modular management of ontologies.</p>
<p>Therefore, for the interested reader, we describe here a definition of this case in terms of first order logic, which shows how modularity can formally be achieved:</p>
<p>Let us assume a property P defined with domain class A and range class C also holds for a domain class B, superclass of A, and a range class D, superclass of C, in the sense of its ontological meaning in the real world. We describe this situation by introducing an auxiliary formal property P’, defined with domain class B and range class D, and apply the following logic:</p>
<p>                               A(x) ⇒ B(x)</p>
<p>                               C(x) ⇒ D(x)</p>
<p>                               P(x,y) ⇒ A(x)</p>
<p>                               P(x,y) ⇒ C(y)</p>
<p>                               P’(x,y) ⇒ B(x)</p>
<p>                               P’(x,y) ⇒ D(y)</p>
<p>Then, P’ is a conservative extension of P if: A(x) ∧ C(y) ∧ P’(x,y) ⇔  P(x,y) </p>
<p>In other words, a separate extension module may re-declare the respective property with another identifier, preferably using the same label, and implement the above rule.</p>
</td>
<td>
<p>Puisque le domaine d’application du CIDOC CRM est en fait un sous-ensemble du monde « réel » qui lui est infini, le modèle a été conçu pour être extensible [n.d.t. afin de répondre aux différents besoins de documentation qui pourraient en émerger]. Cette extensibilité repose en grande partie sur la possibilité d’établir des liens avec des systèmes externes compatibles hiérarchisés par types. </p>
<p>Certains concepts du CIDOC CRM sont nécessairement définis plus précisément que d’autres du fait de son application pratique dans un domaine discursif qui est, lui, illimité (p. ex. les classes <code class="language-plaintext highlighter-rouge">E39_Actant</code> et <code class="language-plaintext highlighter-rouge">E30_Droit</code> sont brièvement définies alors que d’autres sont plus précises). Ces concepts « sous-développés » peuvent être utilisés comme <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#super-classe"><span class="underline">super-classes</span></a> possibles d’extensions compatibles (en particulier dans le cas de disciplines qui auraient une orientation spécifique et limitée); de telles additions au modèle principal (auquel on réfère parfois comme le CRMbase) sont généralement qualifiées d’« extensions ». </p>
<p>La compatibilité des extensions repose sur le fait que les données structurées selon celles-ci demeurent des instances valides des <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#classe"><span class="underline">classes</span></a> de CRMbase. Ceci exige, d’un point de vue pratique, un encadrement des requêtes, de sorte que toute requête d’une base de connaissances (BC) basée sur des concepts du CRMbase doit générer des résultats qui s’alignent avec la sémantique du modèle, et ce peu importe si la représentation de ces connaissances (RC) est structurée uniquement selon CRMbase ou si elle repose aussi en partie sur ses extensions. Par exemple, une requête telle que « énumérer tous les évènements » devrait générer 100 % des instances considérées comme des évènements par le CRMbase peu importe la manière dont elles sont classifiées par les extensions du modèle. </p>
<p>Un seuil acceptable de compatibilité d’une extension avec le CIDOC CRM est notamment établi par les conditions suivantes (qui doivent toutes être remplies) : </p>
<ul><li><p>les classes de CRMbase à l’exception de <code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code> subsument toutes les classes de cette extension; </p>
</li>
<li><p>les <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#propriete"><span class="underline">propriétés</span></a> de CRMbase subsument les propriétés de cette extension ou ces dernières font partie d’un chemin sémantique pour lequel une propriété du CRMbase fait office de <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#raccourci"><span class="underline">raccourci</span></a>;</p>
</li>
<li><p>les classes et les propriétés de l'extension peuvent être aisément distinguées de celle du CRMbase (p. ex. une classe « objet tangible » pourrait entrer en conflit avec des classes du CRMbase [n.d.t. comme <code class="language-plaintext highlighter-rouge">E19_Objet_Matériel</code>] et cette évaluation ne pourrait être faite qu’intellectuellement). </p>
</li></ul>
<p>Le CRMbase fournit un certain nombre de mécanismes d’extensibilité afin que son domaine d’application initial puisse être élargi sans pour autant compromettre sa compatibilité : </p>
<ul><li><p>Les classes existantes peuvent faire l’objet d’une extension structurellement — par des <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#sous-classe"><span class="underline">sous-classes</span></a> — ou dynamiquement — par une hiérarchie de types [n.d.t. comme un vocabulaire contrôlé] (à ce sujet, consulter la section intitulée <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/introduction-aux-concepts-fondamentaux#des-types"><span class="underline">Des types</span></a>). </p>
</li>
<li><p>Les propriétés existantes peuvent faire l’objet d’une extension structurellement — par des <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#sous-propriete"><span class="underline">sous-propriétés </span></a>— ou dynamiquement — par l’utilisation de propriétés de propriétés permettant le sous-typage (à ce sujet, consulter la section intitulée <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/introduction-aux-concepts-fondamentaux#des-types"><span class="underline">Des types</span></a>). </p>
</li>
<li><p>Les informations pertinentes pour lesquelles la sémantique formelle du CIDOC CRM serait inadéquate ou insuffisante peuvent être enregistrées à titre de données non structurées en utilisant la forme suivante : p. ex. <code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code> . <code class="language-plaintext highlighter-rouge">P3_a_pour_note</code> : <code class="language-plaintext highlighter-rouge">E62_Chaîne_de_caractères</code>.</p>
</li>
<li><p>Le CRMbase lui-même peut être élargi par le biais de super-classes et de propriétés s’appliquant à un domaine plus large (des « extensions conservatrices ») qui maintiennent néanmoins une compatibilité rétroactive avec les instances décrites dans le CRMbase. </p>
</li></ul>
<p>L’utilisation des stratégies [n.d.t. aussi nommées mécanismes] 1, 2 et 3 entraîne une subsomption des extensions par le CRMbase et, de fait, leur couverture complète par ce dernier, de sorte qu’une requête n’utilisant que des concepts du CRMbase dans une base de connaissances extensionnée [n.d.t. mobilisant des extensions] aura pour résultat une extraction de tous les éléments décrits par le biais de ces extensions. </p>
<p>Dans le cas du <strong>troisième mécanisme</strong> [n.d.t. l’utilisation de notes pour représenter des données non structurées], l’information contenues dans les notes est accessible depuis la base de connaissances en extrayant les <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#instance"><span class="underline">instances</span></a> de <code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code> qui sont le <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#domaine"><span class="underline">domaine</span></a> de <code class="language-plaintext highlighter-rouge">P3_a_pour_note</code> ou en effectuant une recherche par mot-clé. La note devrait être appliquée à l’élément qui porte le plus spécifiquement sur le contenu de la note et des règles d’application devraient à cet égard être mises en place [n.d.t. par les responsables de la base de connaissances]. Par exemple, des détails quant au rôle que joue un acteur dans le contexte spécifique d’une activité devraient être associés à l’instance de <code class="language-plaintext highlighter-rouge">E7_Activité</code> plutôt que de <code class="language-plaintext highlighter-rouge">E39_Actant</code> [n.d.t. puisque ce rôle n’est pas généralement endossé par l’acteur et qu’il ne s’applique qu’au contexte particulier de l’activité décrite). Cette approche est la plus appropriée tant et aussi longtemps qu’il n’est pas nécessaire de faire des requêtes reliant les contenus de plusieurs notes de cette nature dans une même base de connaissances. </p>
<p>De manière générale, seuls les concepts soumis à des requêtes formelles sélectionnant des instances multiples de la base de connaissances nécessitent une modélisation explicite; ceci repose cependant sur les applications anticipée et pratique de la base de connaissances. Le CIDOC CRM accorde en effet une importance particulière à la modélisation des éléments qu’un utilisateur aimerait extraire et lier depuis des sources hétérogènes (voire inter-institutionnelles) de contenus. Il ne priorise donc pas la modélisation d’éléments dont l’application est localisée et spécifique telles que les pratiques administratives internes d’une institution. </p>
<p>Le <strong>quatrième mécanisme</strong> (l’extension conservatrice) est plus complexe : </p>
<p>[n.d.t. L’utilisation des extension conservatrices découle d’un] usage accru du CIDOC CRM dont émane le besoin de modéliser des phénomènes issus d’un domaine d’application plus large que celui qu’avait initialement anticipé le modèle bien que ceux-ci s’inscrivent néanmoins dans le domaine d’application des concepts de CRMbase. Dans de tels cas, les propriétés de CRMbase s’avèrent souvent applicables aux super-classes des extensions de manière plus générale qu’elles ne s’appliquent à leur domaine et/ou à leur <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#portee"><span class="underline">portée</span></a> dans CRMbase. Ceci résulte de l’approche « ascendante » [n.d.t. élaboration d’un tout depuis ses parties nécessaires, appelée en anglais « bottom-up”] privilégiée par le CIDOC CRM et selon laquelle les domaines et portées des propriétés sont aussi étroitement définis que possible dans le cadre du domaine d’application concerné (et ce afin d’éviter des généralisations qui exigeraient des corrections non monotones ou induiraient des mécompréhensions). </p>
<p>Ce quatrième mécanisme d’extension de CIDOC CRM peut être divisé en deux scénarios : </p>
<ul><li><p>Une classe  — qui n’est pas couverte par les super-classes de CRMbase à l’exception de <code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code> — ou une propriété — qui n’est pas couverte par les super-propriétés du CRMbase — est ajoutée à une extension de CIDOC CRM, de sorte que les éléments qui ne sont décrits que par ces concepts ne sont pas extraits par une requête faite par des concepts de CRMbase uniquement. Dans un tel cas, l’extension devrait publier un énoncé de compatibilité précisant les classes et propriétés de haut niveau nécessaires à l’extraction de ce qui est documenté par le modèle extensionné (une extension monotone). </p>
</li>
<li><p>Le domaine ou la portée d’une propriété du CRMbase est modifié en faveur de la super-classe de l’un [n.d.t. (domaine)], l’autre [n.d.t. (portée)] ou encore des deux en raison du fait que cette propriété couvre un domaine d’application plus large qu’il n’était initialement prévu. Dans un tel cas, tous les éléments décrits par l’extension sont accessibles par le biais d’une requête ne mobilisant que des concepts de CRMbase, bien que l’extension soit en mesure de décrire des éléments additionnels. Il s’agit d’une extension monotone, une pratique généralement recommandée, car elle permet une évolution ascendante du modèle [n.d.t. élaboration d’un tout depuis ses parties nécessaires, appelée en anglais « bottom-up »]. Si un tel changement s’inscrit dans une publication du CIDOC CRM lui-même, il est rétro-compatible (une pratique courante dans l’évolution du modèle). </p>
</li></ul>
<p>La documentation et l’implémentation de ce second scénario dans le cadre d’un module <strong>distinct</strong> du CRMbase peut mener à des conflits lors du traitement par des langages de représentation des connaissances tels que <a href="https://www.w3.org/RDF/"><span class="underline">RDF</span></a>/OWL. Ceci est dû au fait que, du point de vue de la logique formelle, la modification du domaine ou de la portée d’une propriété <strong>constitue</strong> un changement de signification ontologique <strong>complet</strong> : il n’y a pas de distinction, dans ce contexte, entre la <strong>signification de la propriété (indépendamment de son domaine et de sa portée) et la spécialisation de son domaine et de sa portée</strong>. Ceci est comparable à l’extension conservatrice d’une théorie dans un contexte logique, une pratique nécessaire à la gestion modulaire d’ontologies de manière efficace. </p>
<p>Un tel cas décrit en logique du premier ordre illustre comment atteindre la modularité formellement dans ce contexte : </p>
<p>Assumant qu’une propriété <code class="language-plaintext highlighter-rouge">P</code> est définie avec pour domaine une classe <code class="language-plaintext highlighter-rouge">A</code> et pour portée une classe <code class="language-plaintext highlighter-rouge">C</code>, mais qu’elle porte aussi pour domaine une classe <code class="language-plaintext highlighter-rouge">B</code> (une super-classe de <code class="language-plaintext highlighter-rouge">A</code>) et pour portée une classe <code class="language-plaintext highlighter-rouge">D</code> (une super-classe de <code class="language-plaintext highlighter-rouge">C</code>). </p>
<p>Cette situation peut être décrite plus aisément par l’introduction d’une propriété <code class="language-plaintext highlighter-rouge">P’</code> dont le domaine est la classe <code class="language-plaintext highlighter-rouge">B</code> et la portée la classe <code class="language-plaintext highlighter-rouge">D</code>. </p>
<p>La logique suivante s’applique donc : </p>
<p>A(x) ⇒ B(x)</p>
<p>C(x) ⇒ D(x)</p>
<p>P(x,y) ⇒ A(x)</p>
<p>P(x,y) ⇒ C(y)</p>
<p>P’(x,y) ⇒ B(x)</p>
<p>P’(x,y) ⇒ D(y)</p>
<p>Ainsi, <code class="language-plaintext highlighter-rouge">P’</code> est une extension conservatrice de <code class="language-plaintext highlighter-rouge">P</code> si A(x) ∧ C(y) ∧ P’(x,y) ⇔  P(x,y) </p>
<p>En d’autres termes, un module d’extension distinct peut re-déclarer une propriété avec un autre identifiant (préférablement en utilisant une même étiquette) et implémenter la règle ci-haut. </p>
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
<p>Certains paragraphes ont été édités dans la version francophone à des fins de compréhension. Les sections concernées sont indiquées de [n.d.t. texte concerné].  </p>
<p>Le terme « fact » pour référer à un élément se trouvant dans une base de connaissances a été traduit par « élément » puisqu’il ne semble pas y avoir de référence à la nature attestée de l’élément en question. </p>
</td>
</tr>
<tr>
<th style="width:15%"><p><em>Références</em></p>
</th>
<td colspan="1">
<p>Wikipédia. « Extension conservatrice ». Dans <em>Wikipédia</em>. San Francisco, US-CA: Wikipédia, 17 décembre 2017.<a href="https://fr.wikipedia.org/w/index.php?title=Extension_conservatrice&oldid=143598511"><span class="underline"> </span></a><a href="https://fr.wikipedia.org/w/index.php?title=Extension_conservatrice&oldid=143598511"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Extension_conservatrice&oldid=143598511</span></a>.</p>
<p>———. « Monotonie ». Dans <em>Wikipédia</em>. San Francisco, US-CA: Wikipédia, 19 février 2017.<a href="https://fr.wikipedia.org/w/index.php?title=Monotonie&oldid=134697868"><span class="underline"> </span></a><a href="https://fr.wikipedia.org/w/index.php?title=Monotonie&oldid=134697868"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Monotonie&oldid=134697868</span></a>.</p>
</td>
</tr>
</tbody>
</table>

<h2 id="de-la-minimalite"><span class="en heading">Minimality - </span>De la minimalité</h2>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>Although the scope of the CIDOC CRM is very broad, the model itself is constructed as economically as possible.</p>
<ul><li><p>CIDOC CRM classes and properties are either primitive, or they are key concepts in the practical scope;</p>
</li>
<li><p>Complements of CIDOC CRM classes are not declared, because, considering the Open World principle, there are no properties for complements of a class (see Terminology and first consequence of Monotonicity).</p>
</li></ul>
<p>A CIDOC CRM class is declared when:</p>
<ul><li><p>It is required as the domain or range of a property not appropriate to its superclass. </p>
</li>
<li><p>It serves as a merging point of two CIDOC CRM class branches via multiple IsA (e.g., E25 Human-Made Feature). When the branch superclasses are used for multiple instantiation of an item, this item is in the intersection of the scopes. The class resulting from multiple IsA should be narrower in scope than the intersection of the scopes of the branch superclasses.</p>
</li>
<li><p>It is useful as a leaf class (i.e., at the end of a CIDOC CRM branch) to domain communities building CIDOC CRM extensions or matching key domain classes from other models to the CIDOC CRM (e.g., E34 Inscription).</p>
</li></ul>
</td>
<td>
<p>Bien que le domaine d’application du CIDOC CRM soit très large, le modèle lui-même promeut une économie de moyens, de sorte que :</p>
<ul><li><p>Les <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#classe"><span class="underline">classes</span></a> et <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#propriete"><span class="underline">propriétés</span></a> de CIDOC CRM sont soit primitives, soit d’une utilité avérée dans le cadre d’une application pratique;</p>
</li>
<li><p>En raison de l’<a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#monde-ouvert"><span class="underline">hypothèse du monde ouvert</span></a> qui statue qu’il n’y a pas de propriétés associées aux compléments d’une classe (voir <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie"><span class="underline">Terminologie</span></a> et la première conséquence de la <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/principes-de-modelisation#de-la-monotonicite"><span class="underline">Monotonicité</span></a>), de tels <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#complement"><span class="underline">compléments</span></a> ne sont pas déclarés dans le cadre du CIDOC CRM. </p>
</li></ul>
<p>Une classe CIDOC CRM est déclarée lorsque : </p>
<ul><li><p>Le <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#domaine"><span class="underline">domaine</span></a> ou la <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#portee"><span class="underline">portée</span></a> d’une propriété ne sont pas compatibles avec une <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#super-classe"><span class="underline">super-classe</span></a> [n.d.t. de sorte que son utilisation exige la création d’une nouvelle classe]. </p>
</li>
<li><p>Cette nouvelle classe fonctionne comme point de convergence de deux branches de classes CIDOC CRM par le biais de multiples liens <code class="language-plaintext highlighter-rouge">estUn</code>  (p. ex. <code class="language-plaintext highlighter-rouge">E25_Caractéristique_élaborée_par_l'humain</code>). Lorsque les super-classes de ces branches sont utilisées afin d’instancier à plusieurs reprises une entité, cette entité se trouve à l’intersection des domaines d’application de chacune, de sorte qu’une classe résultant de multiples <code class="language-plaintext highlighter-rouge">estUn</code> devrait avoir un domaine d’application plus restreint que ceux de ses super-classes. </p>
</li>
<li><p>Les praticiens du CIDOC CRM qui élaborent des extensions de celui-ci ou s'affairent à établir des équivalences avec des classes essentielles d’autres modèles en identifiant le besoin; dans de tels cas, il est important que la classe soit située à la fin de la branche et qu’elle ne contienne pas de <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#sous-classe"><span class="underline">sous-classes</span></a> (p. ex. <code class="language-plaintext highlighter-rouge">E34_Inscription</code>). </p>
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
<p>Certains paragraphes ont été édités dans la version francophone à des fins de compréhension. Les sections concernées sont indiquées de [n.d.t. texte concerné]. </p>
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

<h2 id="des-raccourcis"><span class="en heading">Shortcuts - </span>Des raccourcis</h2>

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
<p>Certaines <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#propriete"><span class="underline">propriétés</span></a> sont déclarées être des <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#raccourci"><span class="underline">raccourcis</span></a> de chemins sémantiques plus exhaustifs et détaillés qui relient les mêmes <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#classe"><span class="underline">classes</span></a> de <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#domaine"><span class="underline">domaine</span></a> et de <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#portee"><span class="underline">portée</span></a> que la propriété-raccourci, mais utilisent une ou plusieurs classes intermédiaires. Par exemple, la propriété <code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code>. <code class="language-plaintext highlighter-rouge">P52_a_pour_propriétaire_actuel (est_propriétaire_actuel_de)</code> : <code class="language-plaintext highlighter-rouge">E39_Actant</code> est un raccourci du chemin sémantique complet <code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code> suivi de <code class="language-plaintext highlighter-rouge">E8_Acquisition</code> et finalement <code class="language-plaintext highlighter-rouge">E39_Actant</code>. Une <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#instance"><span class="underline">instance</span></a> du chemin sémantique complet implique toujours une instance de la propriété-raccourci bien que l’inverse ne soit pas toujours vrai (c.-à-d. qu’une instance du chemin sémantique complet ne peut pas toujours être déduite d’une instance de la propriété-raccourci, en particulier dans le cadre d’une base de connaissances précise). </p>
<p>La classe <code class="language-plaintext highlighter-rouge">E13_Assignation_d'attribut</code> peut être utilisée pour documenter ce qui a mené à l’attribution d’une propriété (notamment en ce qui a trait à l’opinion du responsable qui a pris la décision de cette attribution), et ce même dans le cas de propriétés qui ne seraient pas des raccourcis. </p>
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

<h2 id="de-la-monotonicite"><span class="en heading">Monotonicity - </span>De la monotonicité</h2>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>The CIDOC CRM’s primary function is to support the meaningful integration of information in an Open World. The adoption of the Open World principle means that the CIDOC CRM itself must remain fundamentally open and knowledge bases implemented using it should be flexible enough to receive new insights. At the model level, new classes and properties within the CIDOC CRM’s scope may be found in the course of integrating more documentation records or when new kinds of relevant facts come to the attention of its maintainers. At the level of the KBs, the need to add or revise information may arise due to numerous external factors. Research may open new questions; documentation may be directed to new or different phenomena; natural or social evolution may reveal new objects of study. </p>
<p> </p>
<p>It is the aim of the maintainers of the CIDOC CRM to respect the Open World principle and to follow the principle of monotonicity. Monotonicity requires that adding new classes and properties to the model or adding new statements to a knowledge base does not invalidate already modelled structures and existing statements.</p>
<p>A first consequence of this commitment, at the level of the model, is that the CIDOC CRM aims to be monotonic in the sense of Domain Theory. That is to say, the existing CIDOC CRM constructs and the deductions made from them should remain valid and well-formed, even as new constructs are added by extensions to the CIDOC CRM. Any extensions should be, under this method, backwards compatible with previous models. The only exception to this rule arises when a previous construct is considered objectively incorrect by the domain experts and thus subjected to corrective revision. Adopting the principle of monotonicity has active consequences for the basic manner in which classes and properties are designed and declared in the CIDOC CRM. In particular, it forbids the declaration of complement classes, i.e., classes solely defined by excluding instances of some other classes.</p>
<p>For example:</p>
<p>FRBRoo (Bekiari et al (eds). 2015) extends the CIDOC CRM. In version 2.4 of FRBRoo, F51 Name Use Activity was declared as a subclass to the CIDOC CRM class E7 Activity. This class was added in order to describe a phenomenon specific to library practice and not considered within CRM base. F51 Name Use Activity describes the practice of an instance of E74 Group adopting and deploying a name within a context for a time-span. The creation of this extension is monotonic because no existing IsA relationship or inheritance of properties in CRM base are compromised and no future extension is ruled out. By way of contrast, if, to handle this situation, a subclass “Other Activity” had been declared, a non-monotonic change would have been introduced. This would be the case because the scope note of a complement class like “Other Activities” would forbid any future declaration of specializations of E7 Activity such as ‘Name Use Activity’. In the case the need arose to declare a particular specialized subclass, a non-monotonic revision would have to be made, since there would be no principled way to decide which instances of ‘Other Activity’ were instances of the new, specialized class and which were not. Such non-monotonic changes are extremely costly to end users, compromising backwards compatibility and long-term integration.</p>
<p>As a second consequence, maintaining monotonicity is also required during revising or augmenting data within a CIDOC CRM compatible system. That is, existing CIDOC CRM instances, their properties and the deductions made from them, should always remain valid and well-formed, even as new instances, regarded as consistent by the domain expert, are added to the system.</p>
<p>For example:</p>
<p>If someone describes correctly that an item is an instance of E19 Physical Object, and later it is correctly characterized as an instance of E20 Biological Object, the system should not stop treating it as an instance of E19 Physical Object. This is achieved by declaring E20 Biological Object as subclass of E19 Physical Object. </p>
<p>This example further demonstrates that the IsA hierarchy of classes and properties can represent characteristic stages of increasing knowledge about some item during the processes of investigation and collection of evidence. Higher level classes can be used to safely classify objects whose precise characteristics are not known in the first instance. An ambiguous biological object may, for example, be classified as only a physical object. Subsequent investigation can reveal its nature as a biological object. </p>
<p>A knowledge base constructed with CIDOC CRM classes designed to support monotonic revision allows for seeking physical objects that were not yet recognized as biological ones. This ability to integrate information with different specificity of description in a well-defined way is particularly important for large-scale information integration. Such a system supports scholars being able to integrate all information about potentially relevant phenomena into the information system without forcing an over or under commitment to knowledge about the object. Since large scale information integration always deals with different levels of knowledge of its relevant objects, this feature enables a consistent approach to data integration.</p>
<p>A third consequence, applied at the level of the knowledge base, is that in order to formally preserve monotonicity, when it is required to record and store alternative opinions regarding phenomena all formally defined properties should be implemented as unconstrained (many: many) so that conflicting instances of properties are merely accumulated. Thus, integrated knowledge can serve as a research tool for accumulating relevant alternative opinions around well-defined entities, whereas conclusions about the truth are the task of open-ended scientific or scholarly hypothesis building. </p>
<p>For example:</p>
<p>King Arthur’s basic life events are highly contested. Once entered in a knowledge base, he should be defined as an instance of E21 Person and treated as having existed as such within the sense of our historical discourse. The instance of E21 Person is used as the collection point for describing possible properties and existence of this individual. Alternative opinions about properties, such as the birthplace and his living places, should be accumulated without validity decisions being made during data compilation. King Arthur may be entered as a different instance, of E28 Conceptual Object, for describing him as mythological character and accumulating possibly mythological facts.</p>
<p>The fourth consequence of monotonicity relates to the use of time dependent properties in a knowledge base. Certain properties declared in the CIDOC CRM, such as having a part, an owner or a location, may change many times for a single item during the course of its existence. Asserting that such a property holds for some item means that that property held for some particular, undetermined time-span within the course of its existence. Consequently, one item may be the subject of multiple statements asserting the instantiation of that property without conflict or need for revision. The collection of such statements would reflect an aggregation of these instances of this property holding over the time-span of the item’s existence. If a more specific temporal knowledge is required/available, it is recommended to explicitly describe the events leading to the assertion of that property for that item. For example, in the case of acquiring or losing an item, it would be appropriate to declare the related event class such as E9 Move. By virtue of this principle, the CRM achieves monotonicity with respect to an increase of knowledge about the states of an item at different times, regardless of their temporal order. </p>
<p>Time-neutral properties may be specialized in a future monotonic extension by time-specific properties, but not vice-versa. Also, many properties registered do not change over time or are relative to events in the model already. Therefore, the CIDOC CRM always gives priority to modelling properties as time-neutral, and rather representing changes by events.</p>
<p>However, for some of these properties many databases may describe a “current” state relative to some property, such as “current location” or “current owner”. Using such a “current” state means that the database manager is able to verify the respective reality at the latest date of validity of the database. Obviously, this information is non-monotonic, i.e., it requires deletion when the state changes. In order to preserve a reduced monotonicity, these properties have time-neutral superproperties by which respective instances can be reclassified if the validity becomes unknown or no longer holds. Therefore, the use of such properties in the CRM is only recommended if they can be maintained consistently. Otherwise, they should be reclassified by their time-neutral superproperties. This holds in particular if data is exported to another repository, see also the paragraph “Authorship of Knowledge Base Contents”.</p>
</td>
<td>
<p>La fonction primaire du CIDOC CRM est de soutenir l’intégration d’information sur la base de l’<a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#monde-ouvert"><span class="underline">hypothèse du monde ouvert</span></a> [n.d.t. selon laquelle la véracité d'une affirmation ne repose pas sur le fait qu’un agent ou un observateur sache qu’elle est vraie]. Ceci implique que le CIDOC CRM lui-même doit être ouvert et que les bases de connaissances implémentées avec celui-ci doivent être suffisamment flexibles pour accueillir de nouvelles idées. Au niveau du modèle, ceci implique que de nouvelles <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#classe"><span class="underline">classes</span></a> et/ou <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#propriete"><span class="underline">propriétés</span></a> puissent être créées lors de l’intégration de nouveaux enregistrements documentaires ou lorsque [n.d.t. la nécessité de représenter] des éléments inédits est portée à l’attention des responsables du CIDOC CRM. Au niveau des bases de connaissances, la nécessité d’ajouter ou de réviser de l’information en raison de facteurs externes doit être prise en compte (de tels facteurs incluent, par exemple, l’avancement du milieu de la recherche qui soulève de nouvelles questions, la documentation de nouveaux phénomènes, ou encore l’évolution sociale ou naturelle qui révèle de nouveaux objets d’étude). </p>
<p>Les responsables du CIDOC CRM ont pour objectif de respecter les tenants de l’hypothèse du monde ouvert, en particulier le principe de la monotonicité qui exige que l’ajout de nouvelles classes et/ou propriétés (au modèle) ou de nouveaux énoncés (à la base de connaissances) n’invalident pas les structures et énoncés pré-existants [n.d.t. voir <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#raisonnement-monotone"><span class="underline">Raisonnement monotone</span></a> dans la section <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie"><span class="underline">Terminologie</span></a>]. </p>
<p>La <strong>première conséquence</strong> de ce choix est que le CIDOC CRM tente d’être monotone au sens de la théorie des domaines : les construits du CIDOC CRM et les déductions qui peuvent en découler doivent donc demeurer formellement et conceptuellement valides malgré l’ajout de construits issus d’extensions du CIDOC CRM, de sorte que toute extension doit être rétro-compatible avec les modèles qui la précèdent. La seule exception à cette règle serait une situation où un construit est considéré objectivement incorrect par les experts du domaine dont ce construit émane et qu’il soit en conséquence soumis à une révision corrective. L’adoption du principe de monotonicité a des conséquence notables sur la manière dont les classes et propriétés sont conceptualisées et déclarées dans le CIDOC CRM, car cela interdit la déclaration de classes complémentaires (c.-à-d. des classes définies uniquement par l’exclusion d’<a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#instance"><span class="underline">instances</span></a> d’autres classes). </p>
<p>Par exemple : </p>
<p>FRBRoo (Bekiari et al (eds). 2015), qui extensionne le CIDOC CRM, a dans sa version 2.4 une classe <code class="language-plaintext highlighter-rouge">F51_Activité_d’utilisation_de_nom</code> déclarée sous-classe de <code class="language-plaintext highlighter-rouge">E7_Activité</code>. <code class="language-plaintext highlighter-rouge">F51_Activité_d’utilisation_de_nom</code> a pour fonction de décrire un phénomène bibliothéconomique spécifique qui n’est pas couvert par le CIDOC CRM, mais qui recense le fait qu’un <code class="language-plaintext highlighter-rouge">E74_Groupe</code> adopte et fasse l’usage d’un nom particulier dans le contexte d’un intervalle temporel. La création de cette extension est monotone dans la mesure où (1) aucune relation <code class="language-plaintext highlighter-rouge">estUn</code> ou règle d’<a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#heritage"><span class="underline">héritage</span></a> s’appliquant aux propriétés du CRMbase n’est compromise et où (2) la création de futures extensions n’est pas inhibée par cette création. Au contraire, si pour gérer cette situation une <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#sous-classe"><span class="underline">sous-classe</span></a> « Autre Activité » avait été déclarée, un changement non monotone aurait été introduit dans le CRMbase, car la <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#note-dapplication"><span class="underline">note d’application</span></a> d’une telle classe complémentaire aurait proscrit la déclaration d’autres spécialisations de <code class="language-plaintext highlighter-rouge">E7_Activité</code> comme « Activité d’utilisation de nom ». Dans l’éventualité où il serait nécessaire de déclarer des sous-classes spécialisées, une révision non monotone devrait être effectuée, car il ne serait pas possible de déterminer quelles instances relèvent de la nouvelle classe spécialisée et lesquelles n’en relèvent pas (un changement et une révision qui sont extrêmement exigeants du point de vue des utilisateurs et qui compromettent sérieusement la rétro-compatibilité et l’intégration du système à long-terme). </p>
<p>La <strong>seconde conséquence</strong> de ce choix [n.d.t.méthodologique d’adopter l’hypothèse du monde ouvert] est qu’il est nécessaire de maintenir la monotonicité même lors de la révision ou de l’ajout de données dans des systèmes compatibles avec le CIDOC CRM. En d’autres termes, les instances des classes du CIDOC CRM, leurs propriétés et les déductions qui en découlent doivent demeurer formellement et conceptuellement valides, et ce même lorsque de nouvelles instances considérées par les experts d’un domaine précis considèrent qu’elles s’insèrent de manière cohérente dans l’ensemble du système. </p>
<p>Par exemple :  </p>
<p>Si quelqu’un indique correctement qu’un élément est une instance de <code class="language-plaintext highlighter-rouge">E19_Objet_matériel</code> et que ce même élément est subséquemment qualifié de <code class="language-plaintext highlighter-rouge">E20_Objet_biologique</code>, le système ne devrait pas cesser de traiter cet élément comme une instance de <code class="language-plaintext highlighter-rouge">E19_Objet_matériel</code>, car <code class="language-plaintext highlighter-rouge">E20_Objet_biologique</code> est une sous-classe de <code class="language-plaintext highlighter-rouge">E19_Objet_matériel</code>. </p>
<p>Cet exemple démontre en outre que la hiérarchie <code class="language-plaintext highlighter-rouge">estUn</code> de classes et de propriétés peut rendre compte des étapes caractéristiques de précision des connaissances au sujet d’un élément tel qu’il se décline au fur et à mesure des processus d’investigation et de cueillette d’information et de contenus. Les classes de plus haut niveau peuvent ainsi être utilisées afin de classifier des objets dont les caractéristiques particulières ne sont pas initialement toutes connues ou recensées. Par exemple, un objet biologique dont la nature est incertaine peut d’abord être classifié comme <code class="language-plaintext highlighter-rouge">E19_Objet_matériel</code>, mais des investigations subséquentes peuvent établir qu’il s’agit en fait d’un <code class="language-plaintext highlighter-rouge">E20_Objet_biologique</code>. Une base de connaissances construite avec des classes CIDOC CRM conçues de manière à permettre une révision monotone rendra possible, dans un tel cas, une recherche des objets physiques qui [n.d.t. à un certain point de leur historique de documentation] n’étaient pas encore reconnus comme des objets biologiques. Cette capacité d’intégrer de l’information dont les niveaux de spécificité descriptive diffèrent est particulièrement importante dans le contexte d’une agrégation à large échelle. C’est aussi une pratique qui permet aux chercheurs d'intégrer dans un même système de l’information au sujet de divers phénomènes sans nécessiter une connaissance exhaustive ou minimale de l’objet [n.d.t. pour se concentrer sur celui-ci plutôt que sur l’acquisition de connaissances qui l’entourent]. Puisque l’intégration d’information à large échelle implique de facto des connaissances dont le niveau de précision varie, cette caractéristique est essentielle pour une intégration cohérente des données. </p>
<p>La <strong>troisième conséquence</strong> de ce choix [n.d.t. d’une méthodologie monotone] est la nécessité d’une implémentation formelle illimitée (plusieurs à plusieurs) des propriétés recensant des enregistrements ou opinions alternatifs au sujet de phénomènes dans une base de connaissances, de telle sorte que des instances qui pourraient s’avérer conflictuelles s’accumulent [n.d.t. plutôt que d’établir des contradictions]. Ainsi, les bases de connaissances [n.d.t. où se retrouvent les informations et savoirs intégrés] peuvent être utilisées afin d’accumuler ou de recenser des opinions alternatives pertinentes au sujet d’un phénomène par l’utilisation d’entités sémantiques clairement définies alors que les constats experts ou conclusions sur ce même sujet [n.d.t. qui peuvent s’appuyer sur l’information trouvée dans ces bases de connaissances] relèvent de l’analyse scientifique ou experte. </p>
<p>Par exemple : </p>
<p>Les évènements rythmant la vie du Roi Arthur font l’objet de beaucoup de spéculations et de désaccords [n.d.t. qui doivent néanmoins être recensés dans les bases de connaissances traitant de lui]. Le CIDOC CRM préconise un recensement selon la formule suivante : </p>
<p>Une fois recensé dans une base de connaissances, le Roi Arthur [n.d.t. en tant qu’individu] devrait être défini comme une instance de <code class="language-plaintext highlighter-rouge">E21_Personne</code> et traité comme une figure historique ayant « réellement » existé (au regard de la discipline qu’est l’histoire et des discours qui la construisent). Cette instance de <code class="language-plaintext highlighter-rouge">E21_Personne</code> devrait ainsi être utilisée afin de fédérer les possibles propriétés de l’existence de l’individu sachant que les opinions alternatives au sujet de ces propriétés (par exemple le lieu de naissance ou les endroits où il a résidé) devraient être recensés sans qu’un constat sur leur validité ne soit fait à l’étape de la compilation des données. </p>
<p>Le recensement du Roi Arthur à titre de figure mythologique [n.d.t. plutôt que comme individu historique] requiert pour sa part une instance de <code class="language-plaintext highlighter-rouge">E28_Objet_conceptuel</code> qui permettra de recueillir les informations qui s’y rapportent. </p>
<p>La <strong>quatrième conséquence </strong>de ce choix d’une méthodologie monotone [n.d.t. reposant sur l’hypothèse du monde ouvert] est la possibilité pour certaines propriétés de nature temporelle (telles que celles qui se rapportent au fait d’avoir des composantes, des propriétaires ou des localisations) de changer plusieurs fois en référence à un même élément au cours de son existence. Dans ce contexte, affirmer qu’une propriété est valide pour un élément implique qu’elle soit aussi valide pour un intervalle temporel particulier, mais indéterminé et situé dans le cours de l'existence de ce même élément. Il en résulte qu’un même élément puisse faire l’objet de nombreux énoncés affirmant l’instanciation d’une propriété sans que ceci ne soit conflictuel ou ne nécessite de révision. La collecte de tels énoncés résulterait ainsi en une agrégation des instances de cette propriété en tant qu’elle s’applique à l’entièreté de l’existence de l’élément. Si des informations temporelles plus spécifiques sont nécessaires ou disponibles, il est recommandé de décrire explicitement les évènements qui sous-tendent l’application d’une propriété à un élément. </p>
<p>Par exemple : </p>
<p>Si un élément fait l’objet d’une acquisition ou d’une perte, une instance de <code class="language-plaintext highlighter-rouge">E9_Déplacement</code> devrait être liée et déclarée. Une telle approche permet de maintenir la monotonicité du CIDOC CRM malgré un accroissement des connaissances au sujet de l’état d’un élément à différents moments, et ce indépendamment de leur chronologie. </p>
<p>Des propriétés temporellement neutres peuvent faire l’objet d’une spécialisation par des propriétés temporellement spécifiques dans le cadre d’extensions monotones futures, mais le contraire n’est pas possible. En outre, plusieurs propriétés du CIDOC CRM n’ont pas de composante temporelle ou sont déjà définies par rapport à des évènements précis [n.d.t. et celles-ci devraient être envisagées avant la création de nouvelles propriétés]. Le CIDOC CRM privilégie la modélisation de propriétés qui sont temporellement neutres et l’utilisation d’évènements pour représenter le changement. </p>
<p>Toutefois, dans le cas de certaines de ces propriétés, de nombreuses bases de données indiqueront parfois un statut « actuel » relatif à une autre propriété (p. ex. « localisation actuelle » ou « propriétaire actuel »). L’utilisation d’un tel état « actuel » implique que le responsable de la base de données en question soit garant de l’information en date de la dernière date statuant la validité des contenus. Cette information, évidemment, est de nature non monotone (c.-à-d. qu’elle doit être supprimée lorsque l’état de l’élément change). Afin de préserver malgré cela une forme (réduite) de monotonicité, de telles propriétés s’inscrivent dans les super-propriétés temporellement neutres qui permettent de reclassifier leurs instances dans l’éventualité où la validité de cette information échoit ou devient inconnue. Ainsi, l’usage de telles propriétés dans le cadre du CIDOC CRM n’est recommandé que lorsque leur maintien régulier et rigoureux peut être assuré, sans quoi ces propriétés devraient être reclassifiées en faveur de leur <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#super-propriete"><span class="underline">super-propriétés</span></a> temporellement neutres; cette pratique s’applique notamment lors de l’exportation de données vers des répertoires autres (voir <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/principes-de-modelisation#de-lauctorialite-des-contenus-dune-base-de-connaissances"><span class="underline">De l’auctorialité des contenus d’une base de connaissances</span></a>). </p>
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
<p>Certains paragraphes ont été édités dans la version francophone à des fins de compréhension. Les sections concernées sont indiquées de [n.d.t. texte concerné]. </p>
</td>
</tr>
<tr>
<th style="width:15%"><p><em>Références</em></p>
</th>
<td colspan="1">
<p>Wikipédia. « Monotonie ». Dans <em>Wikipédia</em>. San Francisco, US-CA: Wikipédia, 19 février 2017.<a href="https://fr.wikipedia.org/w/index.php?title=Monotonie&oldid=134697868"><span class="underline"> </span></a><a href="https://fr.wikipedia.org/w/index.php?title=Monotonie&oldid=134697868"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Monotonie&oldid=134697868</span></a>.</p>
</td>
</tr>
</tbody>
</table>

<h2 id="de-la-disjonction"><span class="en heading">Disjointness - </span>De la disjonction</h2>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>Classes are disjoint if they cannot share any common instances at any time, past, present or future. That implies that it is not possible to instantiate an item using a combination of classes that are mutually disjoint or with subclasses of them (see “multiple instantiation” in section “Terminology”). There are many examples of disjoint classes in the CIDOC CRM.</p>
<p>A comprehensive declaration of all possible disjoint class combinations afforded by the CIDOC CRM has not been provided here; it would be of questionable practical utility, and may easily become inconsistent with the goal of providing a concise definition. However, there are two key examples of disjoint class pairs that are fundamental to effective comprehension of the CIDOC CRM:</p>
<ul><li><p>E2 Temporal Entity is disjoint from E77 Persistent Item. Instances of the class E2 Temporal Entity are perdurants, whereas instances of the class E77 Persistent Item are endurants. Even though instances of E77 Persistent Item have a limited existence in time, they are fundamentally different in nature from instances of E2 Temporal Entity, because they preserve their identity between events. Declaring endurants and perdurants as disjoint classes is consistent with the distinctions made in data structures that fall within the CIDOC CRM’s practical scope.</p>
</li>
<li><p>E18 Physical Thing is disjoint from E28 Conceptual Object. The distinction is between material and immaterial items, the latter being exclusively human-made. Instances of E18 Physical Thing and E28 Conceptual Object differ in many fundamental ways; for example, the production of instances of E18 Physical Thing implies the incorporation of physical material, whereas the production of instances of E28 Conceptual Object does not. Similarly, instances of E18 Physical Thing cease to exist when destroyed, whereas an instance of E28 Conceptual Object perishes when it is forgotten or its last physical carrier is destroyed.</p>
</li></ul>
</td>
<td>
<p>Des <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#classe"><span class="underline">classes</span></a> qui ne peuvent pas partager <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#instance"><span class="underline">d’instances</span></a> à quelque moment que ce soit (par le passé, dans le présent ou dans le futur) sont qualifiées de <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#disjointe"><span class="underline"><strong>disjointes</strong></span></a>. Un élément ne peut pas être instancié avec une combinaison de classes qui sont mutuellement disjointes ou qui sont des <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#sous-classe"><span class="underline">sous-classes</span></a> de <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#super-classe"><span class="underline">super-classes</span></a> mutuellement disjointes (voir « <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#instanciation-multiple"><span class="underline">Instanciation multiple</span></a> » dans la section <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie"><span class="underline">Terminologie</span></a>). </p>
<p>Il y a de nombreuses paires de classes disjointes dans le CIDOC CRM et une déclaration exhaustive de toutes les combinaisons possibles de celles-ci n’aurait qu’une utilité pratique limitée, en plus d’entrer en conflit avec l’objectif du CIDOC CRM d’offrir des définitions concises, de sorte qu’une telle liste n’est pas recensée ici. Deux exemples emblématiques de disjonction de classes sont néanmoins essentiels à une bonne compréhension du CIDOC CRM : </p>
<ul><li><p><code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code> est disjoint de <code class="language-plaintext highlighter-rouge">E77_Entité_persistante</code> : les instances de la classe <code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code> sont perdurantes alors que les instances de <code class="language-plaintext highlighter-rouge">E77_Entité_persistante</code> sont endurantes. Même si les instances de <code class="language-plaintext highlighter-rouge">E77_Entité_persistante</code>  ont une existence temporellement limitée, elles sont d’une nature fondamentalement différente des instances de <code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code>, car elles préservent leur identité d’un évènement à un autre. La disjonction de classes endurantes et perdurantes s’aligne à cet égard avec les distinctions structurelles des ensembles de données du domaine d’application du CIDOC CRM. </p>
</li>
<li><p><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code> est disjoint de <code class="language-plaintext highlighter-rouge">E28_Objet_conceptuel</code> : les instances de la classe <code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code> sont de nature physique alors que les instances de la classe <code class="language-plaintext highlighter-rouge">E28_Objet_conceptuel</code> sont de nature immatérielle et sont exclusivement élaborées par l’humain. Elles diffèrent fondamentalement, notamment en raison du fait que la production d’instances de <code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code> implique des matériaux physiques alors que ce n’est pas le cas de la production d’instances de <code class="language-plaintext highlighter-rouge">E28_Objet_conceptuel</code>. De la même manière, les instances de <code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code> cessent d’exister lorsqu’elles sont détruites alors que les instances de <code class="language-plaintext highlighter-rouge">E28_Objet_conceptuel</code> s’éteignent lorsqu’elles sont oubliées ou que leur support physique est détruit. </p>
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

<h2 id="de-lheritage-et-de-la-transitivite"><span class="en heading">Inheritance and Transitivity - </span>De l’héritage et de la transitivité</h2>

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
<p>Le CIDOC CRM est un système de <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#classe"><span class="underline">classe</span></a> dotées <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#heritage"><span class="underline">d’héritage</span></a>, de telle manière qu’une <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#propriete"><span class="underline">propriété</span></a> <code class="language-plaintext highlighter-rouge">P</code> ayant pour <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#domaine"><span class="underline">domaine</span></a> <code class="language-plaintext highlighter-rouge">A</code> et pour <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#portee"><span class="underline">portée</span></a> <code class="language-plaintext highlighter-rouge">B</code> sera aussi une propriété potentielle de toutes les <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#sous-classe"><span class="underline">sous-classe</span></a>s de <code class="language-plaintext highlighter-rouge">A</code> et de <code class="language-plaintext highlighter-rouge">B</code>. Dans la plupart des cas, il y aura une sous-classe commune (<code class="language-plaintext highlighter-rouge">C</code>) de <code class="language-plaintext highlighter-rouge">A</code> et de <code class="language-plaintext highlighter-rouge">B</code>. Si c’est le cas, une propriété restreinte à <code class="language-plaintext highlighter-rouge">C</code> (c.-à-d. une propriété ayant <code class="language-plaintext highlighter-rouge">C</code> pour domaine et pour portée) pourrait être <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#transitive"><span class="underline">transitive</span></a>. Par exemple, un <code class="language-plaintext highlighter-rouge">E73_Objet_informationnel</code> peut faire partie d’un <code class="language-plaintext highlighter-rouge">E90_Objet_symbolique</code>, de telle sorte qu’un objet informationnel peut s’intégrer à un autre objet informationnel [n.d.t. puisqu’un <code class="language-plaintext highlighter-rouge">E90_Objet_symbolique</code> est un <code class="language-plaintext highlighter-rouge">E73_Objet_informationnel</code>]. </p>
<p>Les propriétés transitives sont explicitement indiquées comme telles dans les <a href="https://chin-rcip.github.io/cidoc_crm_fr-ca/v7.1/information/terminologie#note-dapplication"><span class="underline">notes d’application</span></a> du CIDOC CRM, si bien que les propriétés dénuées de cette mention doivent être considérées comme non transitives. </p>
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
<p>Certains paragraphes ont été édités dans la version francophone à des fins de compréhension. Les sections concernées sont indiquées de [n.d.t. texte concerné]. </p>
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

