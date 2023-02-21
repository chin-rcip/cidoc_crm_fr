---
layout: page
title:  Terminologie
titleEn: Terminology - Terminologie
permalink: /v7.1/information/terminologie
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
<p>The following definitions of key terminology used in this document are provided both as an aid to readers unfamiliar with object-oriented modelling terminology, and to specify the precise usage of terms that are sometimes applied inconsistently across the object-oriented modelling community for the purpose of this document. Where applicable, the editors have tried to consistently use terminology that is compatible with that of the Resource Description Framework (RDF),<sup>3</sup> a recommendation of the World Wide Web Consortium. The editors have tried to find a language, which is comprehensible to the non-computer expert and precise enough for the computer expert so that both understand the intended meaning.  </p>
<p></p>
<hr><p></p>
<p></p>
<p><sup>3</sup> Information about the Resource Description Framework (RDF) can be found at http://www.w3.org/RDF/</p>
</td>
<td>
<p>Les définitions suivantes ont pour objectif d’aider le lecteur qui ne serait pas familier avec la terminologie de la modélisation orientée-objet ainsi que de préciser l’usage de termes qui ne sont parfois pas utilisés de manière uniforme par cette communauté de modélisation. Les éditeurs ont tenté d’utiliser une terminologie compatible avec les recommandations du World Wide Web Consortium quant au Resource Description Framework (RDF)<sup>3</sup>. Les éditeurs ont utilisé un langage compréhensible pour le lecteur qui ne serait pas un expert informatique tout en préconisant une précision suffisante pour servir les besoins d’un tel expert de manière à ce que l’un comme l’autre comprenne le sens du CIDOC CRM. </p>
<p></p>
<hr><p></p>
<p></p>
<p><sup>3</sup> Plus d'informations au sujet du Resource Description Framework (RDF) sont disponibles au <a href="http://www.w3.org/RDF/"><span class="underline">http://www.w3.org/RDF/</span></a>. </p>
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
<p>Une recherche sommaire de la documentation technique traduite sur le site du World Wide Web Consortium ne révèle pas de traduction francophone de « Resource Description Framework (RDF) », de sorte que l’appellation anglophone est préconisée dans la présente traduction. </p>
<p></p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="1">
<p>Berners-Lee, Tim, Tim Bray, Dan Connolly, Paul Cotton, Roy Fielding, Mario Jeckle, Chris Lilley, et al. (2005) 2006. « Architecture du World Wide Web, Volume Un ». Traduit par Frédéric Laurent. opikanoba. 2006.<a href="http://www.opikanoba.org/tr/w3c/webarch/"><span class="underline"> </span></a><a href="http://www.opikanoba.org/tr/w3c/webarch/"><span class="underline">http://www.opikanoba.org/tr/w3c/webarch/</span></a>.</p>
<p>Berrueta, Diego, et Jon Phipps. 2008. « Méthodes exemplaires pour la publication des vocabulaires RDF ». Traduit par Jean-Jacques Solari. W3C. 28 août 2008.<a href="http://www.yoyodesign.org/doc/w3c/swbp-vocab-pub/"><span class="underline"> </span></a><a href="http://www.yoyodesign.org/doc/w3c/swbp-vocab-pub/"><span class="underline">http://www.yoyodesign.org/doc/w3c/swbp-vocab-pub/</span></a>.</p>
<p>World Wide Web Consortium. 2021. « Translations of W3C Technical Reports ». W3c. 8 mars 2021.<a href="https://www.w3.org/Translations/"><span class="underline"> </span></a><a href="https://www.w3.org/Translations/"><span class="underline">https://www.w3.org/Translations/</span></a>.</p>
<p></p>
</td>
</tr>
</tbody>
</table>

<table>
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
<a name="classe"></a><p>Classe</p>
</td>
<td>
<p>Une classe est une catégorie d'éléments qui partagent un ou plusieurs traits communs servant de critères pour identifier les éléments appartenant à cette classe. Ces traits communs n'ont pas besoin d'être explicitement formulés en termes logiques (appelés ici <strong>propriétés</strong>), mais peuvent être décrits dans un texte faisant référence à une conceptualisation commune des experts du domaine (texte appelé ici <strong>note d'application</strong>). La somme de ces traits s'appelle <strong>l'</strong><a href="#intension"><span class="underline"><strong>intension</strong></span></a> de la classe. Une classe peut être le <a href="#domaine"><span class="underline"><strong>domaine</strong></span></a> ou la <a href="#portee"><span class="underline"><strong>portée</strong></span></a> d’aucune, d’une ou de plusieurs propriétés formellement définies dans un modèle. Les propriétés formellement définies n'ont pas besoin de faire partie de l'intension de leurs domaines ou portées : ces propriétés sont facultatives. Un élément qui appartient à une classe est appelé une <a href="#instance"><span class="underline"><strong>instance</strong></span></a> de cette classe. Une classe est associée à un ensemble ouvert d'instances réelles (l'<a href="#extension"><span class="underline"><strong>extension</strong></span></a> de la classe), ce qui veut dire qu’une capacité humaine normale ne permet pas de connaître toutes les instances d’une classe existant dans le « monde » à un moment donné, ni de prendre en compte les instances qui pourraient émerger dans le futur (voir <a href="#monde-ouvert"><span class="underline"><strong>Monde Ouvert</strong></span></a>). Par conséquent, une classe ne peut pas être définie en énumérant ses instances. </p>
<p></p>
<p>Une classe joue un rôle analogue à un nom grammatical [n.d.t. dans le contexte d’une langue SVO, c.-à-d. une langue comme le français dont les phrases suivent généralement l’ordre sujet-verbe-objet] et peut être complètement définie sans référence à aucun autre construit (contrairement aux propriétés, qui doivent avoir un domaine et une plage définis sans ambiguïté). </p>
<p></p>
<p>Dans certains contextes, les termes classe individuelle, entité ou nœud sont utilisés comme synonymes de classe.</p>
<p></p>
<p>Par exemple :</p>
<p></p>
<p><code class="language-plaintext highlighter-rouge">E21_Personne</code> est une classe [n.d.t. désignant] ce que « nous » comprenons collectivement être une « personne », laquelle peut être déterminée par des caractéristiques de l’ADN par exemple. Une [n.d.t. instance de] <code class="language-plaintext highlighter-rouge">E21_Personne</code> peut avoir la propriété d'être membre d'un groupe (<code class="language-plaintext highlighter-rouge">E74_Groupe</code>), mais il n'est pas nécessaire d'être membre d'une <code class="language-plaintext highlighter-rouge">E74_Groupe</code> pour être une <code class="language-plaintext highlighter-rouge">E21_Personne</code> et il n’est pas possible de connaître toutes les personnes du passé tout comme il y aura plus de personnes dans le futur. </p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p></p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Wikipedia. 2020. « Langue SVO ». Dans <em>Wikipédia</em>. San Francisco, CA: Wikipedia. <a href="https://fr.wikipedia.org/w/index.php?title=Langue_SVO&oldid=176099662"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Langue_SVO&oldid=176099662</span></a>.</p>
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
<p></p>
<p>A subclass can have more than one immediate superclass and consequently inherits the properties of all of its superclasses (<strong>multiple inheritance</strong>). The IsA relationship or specialization between two or more classes gives rise to a structure known as a class hierarchy. The IsA relationship is transitive and may not be cyclic. In some contexts (e.g., the programming language C++) the term derived class is used synonymously with subclass. </p>
<p></p>
<p>For example:</p>
<p>Every Person IsA Biological Object, or Person is a subclass of Biological Object. </p>
<p>Also, every Person IsA Actor. A Person may die. However, other kinds of Actors, such as companies, don’t die (c.f. 2). </p>
<p>Every Biological Object IsA Physical Object. A Physical Object can be moved. Hence, a Person can be moved also (c.f. 3).</p>
</td>
<td>
<a name="sous-classe"></a><p>Sous-classe</p>
</td>
<td>
<p>Une sous-classe est une <a href="#classe"><span class="underline">classe</span></a> qui est une spécialisation d'une autre classe (sa <a href="#super-classe"><span class="underline">super-classe</span></a>). La spécialisation ou la relation <code class="language-plaintext highlighter-rouge">estUn</code> signifie que :</p>
<ul><li><p>toutes les instances de la sous-classe sont également des instances de sa superclasse; </p>
</li>
<li><p>l<a href="#intension"><span class="underline">'intension</span></a> de la sous-classe étend l'intension de sa super-classe, c'est-à-dire que ses traits sont plus restrictifs que celui de sa super-classe;</p>
</li>
<li><p>la sous-classe <a href="#heritage"><span class="underline">hérite</span></a> de la définition de toutes les propriétés déclarées pour sa super-classe, et ce sans exception (<a href="#heritage-strict"><span class="underline">héritage strict</span></a>), en plus de n'avoir aucune, une ou plusieurs propriétés qui lui sont propres.</p>
</li></ul>
<p></p>
<p>Une sous-classe peut relever directement de plus d'une super-classe et hériter par conséquent des propriétés de toutes ses super-classes (<a href="#heritage-multiple"><span class="underline"><strong>héritage multiple</strong></span></a>). La relation <code class="language-plaintext highlighter-rouge">estUn</code> (ou la spécialisation entre deux ou plusieurs classes) résulte en une hiérarchie de classes. C’est une relation transitive qui peut ne pas être cyclique. Dans certains contextes (p. ex. le langage de programmation C ++), le terme « classe dérivée » est utilisé comme synonyme de sous-classe.</p>
<p></p>
<p>Par exemple :</p>
<p></p>
<p>Chaque <code class="language-plaintext highlighter-rouge">E21_Personne</code> <code class="language-plaintext highlighter-rouge">estUn</code> <code class="language-plaintext highlighter-rouge">E20_Objet_biologique</code>, où <code class="language-plaintext highlighter-rouge">E21_Personne</code> est une sous-classe d’<code class="language-plaintext highlighter-rouge">E20_Objet_biologique</code>.</p>
<p></p>
<p>De plus, chaque <code class="language-plaintext highlighter-rouge">E21_Personne</code> <code class="language-plaintext highlighter-rouge">estUn</code> <code class="language-plaintext highlighter-rouge">E39_Actant</code>. Une <code class="language-plaintext highlighter-rouge">E21_Personne</code> peut mourir, bien que d’autres types [n.d.t. d’instances] d’<code class="language-plaintext highlighter-rouge">E39_Actant</code>, comme les entreprises, ne meurent pas (cf. 2).</p>
<p></p>
<p>Chaque <code class="language-plaintext highlighter-rouge">E20_Objet_biologique</code> <code class="language-plaintext highlighter-rouge">estUn</code> <code class="language-plaintext highlighter-rouge">E19_Objet_matériel</code>. Un <code class="language-plaintext highlighter-rouge">E19_Objet_matériel</code> peut être déplacé, ce qui implique qu’une <code class="language-plaintext highlighter-rouge">E21_Personne</code> peut également être déplacée (c.f. 3).</p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p></p>
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
<p>In some contexts (e.g., the programming language C++) the term parent class is used synonymously with superclass.</p>
<p></p>
<p>For example:</p>
<p>“Biological Object subsumes Person” is synonymous with “Biological Object is a superclass of Person”. It needs fewer traits to identify an item as a Biological Object than to identify it as a Person</p>
</td>
<td>
<a name="super-classe"></a><p>Super-classe</p>
</td>
<td>
<p>Une super-classe est une <a href="#classe"><span class="underline"><strong>classe</strong></span></a> qui est une généralisation d'une ou de plusieurs autres classes (ses <a href="#sous-classe"><span class="underline"><strong>sous-classes</strong></span></a>), ce qui signifie qu'elle englobe toutes les <a href="#instance"><span class="underline"><strong>instances</strong></span></a> de ses sous-classes et qu'elle peut également avoir des instances supplémentaires qui n'appartiennent à aucune de ses sous-classes. L'<a href="#intension"><span class="underline"><strong>intension</strong></span></a> de la super-classe est moins restrictive que n'importe laquelle de ses sous-classes. Cette relation de subsomption ou de généralisation est l’opposé de la relation ou de la spécialisation <code class="language-plaintext highlighter-rouge">estUn</code>.</p>
<p>Dans certains contextes (p. ex. le langage de programmation C ++), le terme « classe parent » est utilisé comme synonyme de super-classe.</p>
<p></p>
<p>Par exemple :</p>
<p></p>
<p>« <code class="language-plaintext highlighter-rouge">E20_Objet_biologique</code> subsume <code class="language-plaintext highlighter-rouge">E21_Personne</code> » est synonyme de « <code class="language-plaintext highlighter-rouge">E20_Objet_biologique</code> est une super-classe de <code class="language-plaintext highlighter-rouge">E21_Personne</code> ». Il faut en effet moins de traits [n.d.t. tels qu’ils sont définis dans la <a href="#note-dapplication"><span class="underline">note d’application</span></a>] pour identifier un élément en tant qu'<code class="language-plaintext highlighter-rouge">E20_Objet_biologique</code> que pour l'identifier en tant que <code class="language-plaintext highlighter-rouge">E21_Personne</code>.</p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p></p>
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
<a name="intension"></a><p>Intension</p>
</td>
<td>
<p>L'intension d'une <a href="#classe"><span class="underline"><strong>classe</strong></span></a> ou d'une <a href="#propriete"><span class="underline"><strong>propriété</strong></span></a> est sa signification prévue. Elle est composée d'un ou de plusieurs traits communs partagés par toutes les <a href="#instance"><span class="underline"><strong>instances</strong></span></a> de la classe ou de la propriété. Ces traits n'ont pas besoin d'être explicitement formulés en termes logiques, mais peuvent simplement être décrits dans un texte (appelé ici <a href="#note-dapplication"><span class="underline"><strong>note d'application</strong></span></a>) qui réfère à une conceptualisation commune aux experts du domaine. En particulier, les concepts dits <a href="#primitive"><span class="underline"><strong>primitifs</strong></span></a>, qui constituent l'essentiel du CRM CIDOC, ne peuvent être davantage réduits à d'autres concepts par des termes logiques.</p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p></p>
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
<a name="extension"></a><p>Extension</p>
</td>
<td>
<p>L'extension d'une <a href="#classe"><span class="underline"><strong>classe</strong></span></a> est l'ensemble de toutes les <a href="#instance"><span class="underline"><strong>instances</strong></span></a> « réelles » appartenant à la classe [n.d.t. du fait qu’elles] remplissent les critères de son <a href="#intension"><span class="underline"><strong>intension</strong></span></a>. Cet ensemble est « ouvert », ce qui veut dire qu’une capacité humaine normale ne permet pas de connaître toutes les instances d’une classe existant dans le « monde » à un moment donné, ni de prendre en compte les instances qui pourraient émerger dans le futur (voir <a href="#monde-ouvert"><span class="underline"><strong>Monde Ouvert</strong></span></a>). Un système d'information peut à n’importe quel moment faire référence à certaines instances d'une classe, lesquelles forment un sous-ensemble de son extension.</p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p></p>
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
<a name="note-dapplication"></a><p>Note d’application</p>
</td>
<td>
<p>Une note d'application est une description textuelle de l'<a href="#intension"><span class="underline"><strong>intension</strong></span></a> d'une <a href="#classe"><span class="underline"><strong>classe</strong></span></a> ou d'une <a href="#propriete"><span class="underline"><strong>propriété</strong></span></a>.</p>
<p></p>
<p>Les notes d’application ne sont pas des construits de modélisation formels, elles sont plutôt fournies pour expliquer la signification et l’application prévues des classes et des propriétés de CIDOC CRM. Fondamentalement, elles renvoient à une conceptualisation commune aux experts du domaine [n.d.t. qu’elles concernent] et clarifient les différentes interprétations possibles. Des exemples d’<a href="#instance"><span class="underline"><strong>instances</strong></span></a> de classes et de propriétés sont régulièrement fournis dans les notes d'application à des fins d'explication.</p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p></p>
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
<p>The painting known as the “The Mona Lisa” is an instance of the class Man Made Object.</p>
<p></p>
<p>An instance of a <strong>property</strong> is a factual relation between an instance of the <strong>domain</strong> and an instance of the <strong>range</strong> of the property that matches the criteria of the <strong>intension</strong> of the property.</p>
<p></p>
<p>For example:</p>
<p>The Mona Lisa <em>has former or current owner.</em> The Louvre is an instance of the property <em>P51 has former or current owner (is former or current owner of).</em></p>
</td>
<td>
<a name="instance"></a><p>Instance</p>
</td>
<td>
<p>L’instance d’une <a href="#classe"><span class="underline">classe</span></a> est un élément du monde réel [n.d.t. voir <a href="/cidoc_crm_fr-ca/v7.1/information/principes-de-modelisation#de-la-realite-des-bases-de-connaissance-et-du-cidoc-crm"><span class="underline">De la réalité, des bases de connaissance et du CIDOC CRM</span></a>] qui correspond à l’<a href="#intension"><span class="underline">intension</span></a> d’une classe [n.d.t. telle qu’elle est exprimée dans sa <a href="#note-dapplication"><span class="underline">note d’application</span></a>]. Le nombre d’instances déclarées pour une classe dans un système d’information est typiquement moins que la totalité [n.d.t. qui existe] dans le monde réel. Par exemple, un individu est une instance de <code class="language-plaintext highlighter-rouge">E21_Personne</code>, mais cet individu n’est pas mentionné dans tous les systèmes d’information décrivant des <code class="language-plaintext highlighter-rouge">E21_Personne</code>. </p>
<p></p>
<p>Par exemple : </p>
<p></p>
<p>La peinture connue sous le nom de « Mona Lisa » est une instance de la classe <code class="language-plaintext highlighter-rouge">E22_Objet_façonné</code>. </p>
<p></p>
<p>L’instance d’une propriété est une relation factuelle entre une instance de son domaine et une instance de sa portée, relation qui correspond à l’intension de cette propriété [n.d.t. telle qu’elle est exprimée dans sa note d’application].</p>
<p></p>
<p>Par exemple : </p>
<p></p>
<p>[n.d.t. Dans l’affirmation] « La <em>Mona Lisa</em> a pour propriétaire actuel ou antérieur le Louvre » « a pour propriétaire actuel ou antérieur » est une instance de la propriété <code class="language-plaintext highlighter-rouge">P51_a_pour_propriétaire_actuel_ou_antérieur (est_propriétaire_actuel_ou_antérieur_de)</code>. </p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p></p>
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
<p></p>
<p>For example:</p>
<p>“Physical Human-Made Thing <em>depicts</em><strong> </strong>CRM Entity” is equivalent to “CRM Entity <em>is depicted by</em> Physical Human-Made Thing”.</p>
</td>
<td>
<a name="propriete"></a><p>Propriété</p>
</td>
<td>
<p>Une propriété définit une relation spécifique entre deux <a href="#classe"><span class="underline">classes</span></a> et est caractérisée par son <a href="#intension"><span class="underline">intension</span></a> (laquelle est exprimée par la <a href="#note-dapplication"><span class="underline">note d’application </span></a>de la propriété). Une propriété est l’équivalent grammatical d’un verbe dans la mesure où elle est définie par son renvoi à son <a href="#domaine"><span class="underline">domaine</span></a> et à sa <a href="#portee"><span class="underline">portée</span></a>, lesquels sont comparables au sujet et à l’objet d’une phrase [n.d.t. dans le contexte d’une langue SVO, c.-à-d. une langue comme le français dont les phrases suivent généralement l’ordre sujet-verbe-objet], et ce contrairement aux classes qui peuvent être définies de manière indépendante. De même que le choix qu’une forme grammaticale active ou passive est arbitraire, le choix de la classe sélectionnée pour le domaine et pour la portée l’est aussi. En d’autres termes, l’interprétation d’une propriété serait distincte selon le sens dans lequel elle est lue [n.d.t. c.-à-d. depuis le domaine vers la portée ou depuis la portée vers le domaine].</p>
<p></p>
<p>Certaines propriétés s’appliquent sur d’autres propriétés [n.d.t. et peuvent donc avoir comme objet des instances]  d’autres classes, une fonctionnalité qui est mobilisée par le CIDOC CRM afin de décrire le sous-typage dynamique de propriétés [n.d.t. voir <a href="/cidoc_crm_fr-ca/v7.1/information/basic-concepts#des-types"><span class="underline">Des types</span></a>; ces propriétés sont signalées par l’usage d’un <code class="language-plaintext highlighter-rouge">.1</code>, comme par exemple <code class="language-plaintext highlighter-rouge">P14.1_dans_le_rôle_de</code> qui est  associée  à <code class="language-plaintext highlighter-rouge">P14_a_été_effectué_par (a_effectué)</code> et qui a pour objet <code class="language-plaintext highlighter-rouge">E55_Type</code> plutôt que <code class="language-plaintext highlighter-rouge">E21_Personne</code> comme propriété d’attache]. </p>
<p></p>
<p>Les propriétés peuvent aussi être spécialisées (comme c’est le cas des classes) par des relations <code class="language-plaintext highlighter-rouge">estUn</code> entre des sous-propriétés et leurs super-propriétés. </p>
<p></p>
<p>Dans certains contextes, les termes attribut, référence, lien, rôle ou créneau peuvent être synonymes de propriété. </p>
<p></p>
<p>Par exemple : </p>
<p></p>
<p><code class="language-plaintext highlighter-rouge">E24_Chose_matérielle_façonnée</code> <code class="language-plaintext highlighter-rouge">P62_illustre</code> <code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code> est l’équivalent de <code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code> <code class="language-plaintext highlighter-rouge">P62.i_est_illustré_par</code> <code class="language-plaintext highlighter-rouge">E24_Chose_matérielle_façonnée</code>.</p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p></p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Wikipedia. 2020. « Langue SVO ». Dans <em>Wikipédia</em>. San Francisco, CA: Wikipedia. <a href="https://fr.wikipedia.org/w/index.php?title=Langue_SVO&oldid=176099662"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Langue_SVO&oldid=176099662</span></a>.</p>
</td>
</tr>
<tr>
<td class="en">
<p>inverse of</p>
<p><em></em></p>
</td>
<td class="en">
<p>The inverse of a property is the reinterpretation of a <strong>property</strong> from <strong>range</strong> to <strong>domain</strong> without more general or more specific meaning, similar to the choice between active and passive voice in some languages. In contrast to some knowledge representation languages, such as RDF and OWL, we regard that the inverse of a property is not a property in its own right that needs an explicit declaration of being inverse of another, but an interpretation implicitly existing for any property. The inverse of the inverse of a property is identical to the property itself, i.e., its primary sense of direction.</p>
<p></p>
<p>For example:</p>
<p>“CRM Entity <em>is depicted by</em> Physical Human-Made Thing” is the inverse of “Physical Human-Made Thing <em>depicts</em><strong> </strong>CRM Entity” </p>
</td>
<td>
<a name="inverse-de"></a><p>Inverse de </p>
</td>
<td>
<p>L’inverse d’une <a href="#propriete"><span class="underline">propriété</span></a> est la réinterprétation de cette propriété depuis sa <a href="#portee"><span class="underline">portée</span></a> vers son <a href="#domaine"><span class="underline">domaine</span></a> sans généralisation ou spécialisation de sa signification supplémentaire. De même que le choix d’une forme grammaticale active ou passive est arbitraire [n.d.t. le choix de la classe sélectionnée pour le domaine et pour la portée l’est aussi]. Contrairement à certains langages de représentation tels que <a href="https://www.w3.org/RDF/"><span class="underline">RDF</span></a> et OWL, le CIDOC CRM considère que l’inverse d’une propriété n’est pas une propriété en soi qui nécessiterait la déclaration explicite du fait qu’elle en inverse une autre; il s’agit plutôt d’une interprétation implicite à chaque propriété. L’inverse de l’inverse d’une propriété est identique à la propriété elle-même, à savoir identique à sa direction primaire. </p>
<p></p>
<p>Par exemple : </p>
<p></p>
<p><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code> <code class="language-plaintext highlighter-rouge">P62.i_est_illustré_par</code> <code class="language-plaintext highlighter-rouge">E24_Chose_matérielle_façonnée</code> est l’inverse de <code class="language-plaintext highlighter-rouge">E24_Chose_matérielle_façonnée</code> <code class="language-plaintext highlighter-rouge">P62_illustre</code> <code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code>.</p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p></p>
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
<p></p>
<p>A subproperty can have more than one immediate superproperty and consequently inherits the properties of all of its superproperties (<strong>multiple inheritance</strong>). The IsA relationship or specialization between two or more properties gives rise to the structure we call a property hierarchy. The IsA relationship is transitive and may not be cyclic. </p>
<p>Some object-oriented programming languages, such as C++, do not contain constructs that allow for the expression of the specialization of properties as sub-properties.</p>
<p></p>
<p>Alternatively, a property may be subproperty of the <strong>inverse of</strong> another property, i.e., reading the property from range to domain. In that case, </p>
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
<a name="sous-propriete"></a><p>Sous-propriété</p>
</td>
<td>
<p>Une sous-propriété est une <a href="#propriete"><span class="underline">propriété</span></a> spécialisant une autre propriété (sa <a href="#propriete"><span class="underline">super-propriété</span></a>); une spécialisation (ou relation <code class="language-plaintext highlighter-rouge">estUn</code>) implique que : </p>
<ul><li><p>toutes les <a href="#instance"><span class="underline"><strong>instances</strong></span></a> d’une sous-propriété sont aussi des instances de sa super-propriété; </p>
</li>
<li><p>l’<a href="#intension"><span class="underline"><strong>intension</strong></span></a> d’une sous-propriété extensionne l’intension de sa super-propriété, c.-à-d. que les traits [n.d.t. décrits dans la <a href="#note-dapplication"><span class="underline">note d’application</span></a> de la sous-propriété] sont plus restrictifs que ceux de sa super-propriété; </p>
</li>
<li><p>le <a href="#domaine"><span class="underline"><strong>domaine</strong></span></a> de la sous-propriété est le même que le domaine de sa super-propriété ou d’une <a href="#sous-classe"><span class="underline">sous-classe</span></a> de ce domaine;</p>
</li>
<li><p>la <a href="#portee"><span class="underline"><strong>portée</strong></span></a> de la sous-propriété est la même que la portée de sa super-propriété ou d’une sous-classe de cette portée; </p>
</li>
<li><p>la sous-propriété <a href="#heritage"><span class="underline">hérite</span></a> la définition de toutes les propriétés déclarées pour sa super-propriété, et ce sans exception (<a href="#heritage-strict"><span class="underline">héritage strict</span></a>) en plus de n’avoir aucune, une seule ou plusieurs propriétés qui lui est/sont propre(s).</p>
</li></ul>
<p></p>
<p>Une sous-propriété peut relever directement de plus d’une super-propriété et ainsi hériter les propriétés de toutes ces super-propriétés (<a href="#heritage-multiple"><span class="underline">héritage multiple</span></a>). La relation <code class="language-plaintext highlighter-rouge">estUn</code> (spécialisation) entre deux propriétés ou plus établit une hiérarchie des propriétés; c’est une relation <a href="#transitivite"><span class="underline">transitive</span></a> qui peut ne pas être cyclique. Certains langages de programmation comme C++ n’ont pas de construits qui expriment la spécialisation de propriétés en sous-propriétés. </p>
<p></p>
<p>Une propriété peut aussi être une sous-propriété de l’<a href="#inverse"><span class="underline">inverse</span></a> d’une autre propriété, c.-à-d. que lire la propriété depuis la portée vers le domaine implique que : </p>
<ul><li><p>toutes les instances d’une sous-propriété sont aussi des instances de l’inverse de l’autre propriété; </p>
</li>
<li><p>l’intension d’une sous-propriété extensionne l’intension de l’inverse de l’autre propriété, c.-à-d. que les traits [n.d.t. décrits dans la note d’application de la sous-propriété] sont plus restrictifs que ceux de l’inverse de l’autre propriété;</p>
</li>
<li><p>le domaine de la sous-propriété est le même que le domaine de l’autre propriété ou d’une sous-classe de cette portée;</p>
</li>
<li><p>la portée de la sous-propriété est la même que le domaine de l'autre propriété [n.d.t. (la propriété initiale non-inversée)] ou une sous-classe de ce domaine </p>
</li>
<li><p>la sous-propriété hérite la définition de toutes les propriétés déclarées pour l’autre propriété, et ce sans exception (héritage strict) en plus de n’avoir aucune, une seule ou plusieurs propriétés qui lui est/sont propre(s). Les définitions des propriétés héritées doivent être interprétées dans le sens inverse de la direction de la sous-propriété, à savoir depuis la portée vers le domaine. </p>
</li></ul>
<p></p>
<p>[n.d.t. voir <a href="/cidoc_crm_fr-ca/v7.1/proprietes/declaration-des-proprietes-du-cidoc-crm"><span class="underline">Déclaration des propriétés du CIDOC CRM</span></a>].</p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p>Le terme « construct » n’a pas d’équivalent français parfait, mais une recherche sommaire révèle que le terme « construit » (n.m.) semble répandu dans les domaines de la philosophie et de la sociologie et est celui dont le sens se rapproche le plus de la forme originale. </p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Termium. 2009. « construct ». Termium Plus. 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=construct&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=construct&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=construct&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
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
<a name="super-propriete"></a><p>Super-propriété</p>
</td>
<td>
<p>Une super-propriété est une <a href="#propriete"><span class="underline"><strong>propriété</strong></span></a> qui est une généralisation de l’une ou plusieurs autres propriétés (ses <a href="#propriete"><span class="underline"><strong>sous-propriétés</strong></span></a>) : elle subsume toutes les <a href="#instance"><span class="underline"><strong>instances</strong></span></a> de toutes ses sous-propriétés et peut de surcroît avoir des instances qui ne relèvent d'aucune de ces sous-propriétés. L’<a href="#intension"><span class="underline"><strong>intension</strong></span></a> d’une super-propriété est moins restrictive que celle de n’importe laquelle de ses sous-propriétés. La relation de subsomption (généralisation) est l’inverse d’une relation <code class="language-plaintext highlighter-rouge">estUn</code> (spécialisation). Une super-propriété peut être une généralisation de l’<a href="#inverse-de"><span class="underline"><strong>inverse</strong></span></a> d’une autre propriété. </p>
<p></p>
<p>[n.d.t. voir <a href="/cidoc_crm_fr-ca/v7.1/proprietes/declaration-des-proprietes-du-cidoc-crm"><span class="underline">Déclaration des propriétés du CIDOC CRM</span></a>].</p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p></p>
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
<a name="domaine"></a><p>Domaine</p>
</td>
<td>
<p>Le domaine est la <a href="#classe"><span class="underline"><strong>classe</strong></span></a> pour laquelle une <a href="#propriete"><span class="underline"><strong>propriété</strong></span></a> est formellement définie, de sorte que les <a href="#instance"><span class="underline"><strong>instances</strong></span></a> d’une propriété ne peuvent s’appliquer qu’aux instances de sa classe de domaine. Une propriété doit avoir exactement un domaine, bien que la classe de domaine puisse contenir des instances pour lesquelles la propriété n’est pas instanciée. La classe de domaine est l’équivalent du sujet grammatical d’une phrase dont la propriété serait le verbe [n.d.t. dans le contexte d’une langue SVO, c.-à-d. une langue comme le français dont les phrases suivent généralement l’ordre sujet-verbe-objet]. Le choix de la classe sélectionnée pour le domaine et pour la <a href="#portee"><span class="underline"><strong>portée</strong></span></a> est aussi arbitraire que celui d’une forme grammaticale active ou passive. Les propriétés du CIDOC CRM sont ainsi nommées de manière à être grammaticalement correctes [n.d.t. en anglais] lors d’une lecture depuis le domaine vers la portée [n.d.t. dans le cadre de cette traduction, les propriétés sont grammaticalement correctes, mais toujours accordées au féminin dans le cadre de la phrase où elles sont citées puisqu’il est fait référence à la propriété elle-même (terme féminin) plutôt qu’à sa dénomination]. De plus, les propriétés inverses, dont le nom se trouve normalement entre parenthèses, sont elles aussi nommées de manière à être grammaticalement correctes [n.d.t. en anglais] lors d’une lecture depuis la portée vers le domaine [n.d.t. dans le cadre de cette traduction, les propriétés sont grammaticalement correctes, mais toujours accordées au féminin dans le cadre de la phrase où elles sont citées].</p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p></p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Wikipedia. 2020. « Langue SVO ». Dans <em>Wikipédia</em>. San Francisco, CA: Wikipedia. <a href="https://fr.wikipedia.org/w/index.php?title=Langue_SVO&oldid=176099662"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Langue_SVO&oldid=176099662</span></a>.</p>
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
<a name="portee"></a><p>Portée</p>
</td>
<td>
<p>La portée est la <a href="#classe"><span class="underline"><strong>classe</strong></span></a> qui englobe toutes les valeurs potentielles d’une <a href="#propriete"><span class="underline"><strong>propriété</strong></span></a>, de sorte que les <a href="#instance"><span class="underline"><strong>instances</strong></span></a> d’une propriété peuvent lier uniquement aux instances de sa classe de portée. Une propriété doit avoir exactement une portée, bien que la classe de portée puisse contenir des instances qui ne sont pas des valeurs de la propriété. La classe de portée est l’équivalent de l’objet grammatical d’une phrase dont la propriété serait le verbe [n.d.t. dans le contexte d’une langue SVO, c.-à-d. une langue comme le français dont les phrases suivent généralement l’ordre sujet-verbe-objet]. Le choix de la classe sélectionnée pour le <a href="#domaine"><span class="underline"><strong>domaine</strong></span></a> et pour la portée est aussi arbitraire que celui d’une forme grammaticale active ou passive. Les propriétés du CIDOC CRM sont ainsi nommées de manière à être grammaticalement correctes [n.d.t. en anglais] lors d’une lecture depuis le domaine vers la portée [n.d.t. dans le cadre de cette traduction, les propriétés sont grammaticalement correctes, mais toujours accordées au féminin dans le cadre de la phrase où elles sont citées]. De plus, les propriétés inverses, dont le nom se trouve normalement entre parenthèses, sont elles aussi nommées de manière à être grammaticalement correcte [n.d.t. en anglais] lors d’une lecture depuis la portée vers le domaine [n.d.t. dans le cadre de cette traduction, les propriétés sont grammaticalement correctes, mais toujours accordées au féminin dans le cadre de la phrase où elles sont citées].</p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p></p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Wikipedia. 2020. « Langue SVO ». Dans <em>Wikipédia</em>. San Francisco, CA: Wikipedia. <a href="https://fr.wikipedia.org/w/index.php?title=Langue_SVO&oldid=176099662"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Langue_SVO&oldid=176099662</span></a>.</p>
</td>
</tr>
<tr>
<td class="en">
<p>inheritance</p>
<p><em></em></p>
</td>
<td class="en">
<p>Inheritance of <strong>properties</strong> from <strong>superclasses</strong> to <strong>subclasses</strong> means that if an item x is an <strong>instance</strong> of a <strong>class</strong> A, then </p>
<ul><li><p>all properties that must hold for the instances of any of the superclasses of A must also hold for item x, and</p>
</li>
<li><p>all optional properties that may hold for the instances of any of the superclasses of A may also hold for item x.</p>
</li></ul>
</td>
<td>
<a name="heritage"></a><p>Héritage</p>
</td>
<td>
<p>L’héritage des <a href="#propriete"><span class="underline"><strong>propriétés</strong></span></a> de <a href="#super-classe"><span class="underline"><strong>super-classes</strong></span></a> vers leurs <a href="#sous-classe"><span class="underline"><strong>sous-classes</strong></span></a> implique que pour tout élément <code class="language-plaintext highlighter-rouge">x</code> étant une <a href="#instance"><span class="underline"><strong>instance</strong></span></a> d’une <a href="#classe"><span class="underline"><strong>classe</strong></span></a> <code class="language-plaintext highlighter-rouge">A</code> :</p>
<ul><li><p>toutes les propriétés qui doivent être appliquées à des instances relevant de super-classes de <code class="language-plaintext highlighter-rouge">A</code> doivent aussi s’appliquer à l’élément <code class="language-plaintext highlighter-rouge">x</code> et que</p>
</li>
<li><p>toutes les propriétés optionnelles qui peuvent être appliquées à des instances relevant de super-classes de <code class="language-plaintext highlighter-rouge">A</code> peuvent aussi s’appliquer à l’élément <code class="language-plaintext highlighter-rouge">x</code>. </p>
</li></ul>
<p></p>
<p>[n.d.t. voir <a href="/cidoc_crm_fr-ca/v7.1/information/principes-de-modelisation#de-lheritage-et-de-la-transitivite"><span class="underline">De l’héritage et de la transitivité</span></a> dans la section <a href="/cidoc_crm_fr-ca/v7.1/information/principes-de-modelisation"><span class="underline">Principes de modélisation</span></a>]. </p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p></p>
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
<a name="heritage-strict"></a><p>Héritage strict</p>
</td>
<td>
<p>L’<a href="#heritage"><span class="underline"><strong>héritage</strong></span></a> strict désigne le fait qu’il n’y a pas d’exception à l’héritage de <a href="#propriete"><span class="underline">propriétés</span></a> depuis des <a href="#super-classe"><span class="underline">super-classes</span></a> vers leurs <a href="#sous-classe"><span class="underline">sous-classes</span></a>. Par exemple, un système [n.d.t. d’information] peut déclarer que les éléphants sont gris et considérer qu’un éléphant blanc est une exception [n.d.t. à la classe éléphant]. Des règles d’héritage strict imposeraient que si tous les éléphants sont gris, un éléphant blanc ne peut être un éléphant. Évidemment, tous les éléphants ne sont pas gris et le fait d’être gris ne fait pas partie de l’<a href="#intension"><span class="underline">intension</span></a> du concept « éléphant » (il s’agit plutôt d’une propriété optionnelle). Le CIDOC CRM applique des règles d’héritage strict à des fins de normalisation. </p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p>Le terme « normalization » aurait aussi pu être traduit par « standardisation”, mais puisqu’il s’agit du principe et non pas de l’application d’un standard établi, le terme « normalisation » a été utilisé. </p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Termium. 2009. « normalization ». Termium Plus. 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=normalization&index=alt&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=normalization&index=alt&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=normalization&index=alt&codom2nd_wet=1#resultrecs</span></a>.</p>
</td>
</tr>
<tr>
<td class="en">
<p>multiple inheritance</p>
<p><em></em></p>
</td>
<td class="en">
<p>Multiple <strong>inheritance</strong> means that a <strong>class</strong> A may have more than one immediate <strong>superclass</strong>. The <strong>extension</strong> of a class with multiple immediate superclasses is a subset of the intersection of all extensions of its superclasses. The <strong>intension</strong> of a class with multiple immediate superclasses extends the intensions of all its superclasses, i.e., its traits are more restrictive than any of its superclasses. If multiple inheritance is used, the resulting “class hierarchy” is a directed graph and not a tree structure. If it is represented as an indented list, there are necessarily repetitions of the same class at different positions in the list.</p>
<p>For example, Person is both, an Actor and a Biological Object.</p>
</td>
<td>
<a name="heritage-multiple"></a><p>Héritage multiple</p>
</td>
<td>
<p>L’<a href="#heritage"><span class="underline"><strong>héritage</strong></span></a> multiple désigne le fait qu’une <a href="#instance"><span class="underline">instance</span></a> d’une <a href="#classe"><span class="underline"><strong>classe</strong></span></a> <code class="language-plaintext highlighter-rouge">A</code> puisse relever directement de plus d’une <a href="#super-classe"><span class="underline"><strong>super-classe</strong></span></a>. L’<a href="#extension"><span class="underline"><strong>extension</strong></span></a> d’une classe relevant directement de plusieurs super-classes est un sous-ensemble de l’intersection de toutes les extensions de ses super-classes. L’<a href="#intension"><span class="underline"><strong>intension</strong></span></a> d’une classe relevant directement de plusieurs super-classes étend les intensions de toutes ces super-classes (c.-à-d. que les traits [n.d.t. de cette classe tels qu’ils sont définis par sa <a href="#note-dapplication"><span class="underline">note d’application</span></a>] sont plus restrictifs que ceux de n’importe laquelle de ses super-classes). La « hiérarchie de classe » résultant d’un héritage multiple prend la forme d’un graphe orienté et non pas d’une arborescence. Si la hiérarchie en question est représentée sous la forme d’une liste comportant des retraits, il y aura nécessairement de multiples occurrences d’une même classe à différents endroits de la liste. Par exemple, <code class="language-plaintext highlighter-rouge">E21_Personne</code> est à la fois <code class="language-plaintext highlighter-rouge">E39_Actant</code> et <code class="language-plaintext highlighter-rouge">E20_Objet_biologique</code>. </p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p></p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Termium. 2009. « directed graph ». Termium Plus. 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=directed+graph&index=alt&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=directed+graph&index=alt&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=directed+graph&index=alt&codom2nd_wet=1#resultrecs</span></a>.</p>
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
<a name="instanciation-multiple"></a><p>Instanciation multiple</p>
</td>
<td>
<p>L’<strong>instanciation </strong>multiple désigne le fait qu’une <a href="#instance"><span class="underline">instance</span></a> d’une <a href="#classe"><span class="underline">classe</span></a> <code class="language-plaintext highlighter-rouge">A</code> soit aussi et simultanément une instance de l’une ou plusieurs autres classes <code class="language-plaintext highlighter-rouge">B1...n</code>. Les <a href="#propriete"><span class="underline">propriétés</span></a> de toutes ces classes deviennent alors utilisables dans la description de cette instance. Par exemple, certaines destructions (<code class="language-plaintext highlighter-rouge">E6_Destruction</code>) sont aussi des activités (<code class="language-plaintext highlighter-rouge">E7_Activité</code>) comme c’est le cas de l’acte d’Érostrate [n.d.t. qui a incendié le temple d’Artémis à Éphèse], mais ce ne sont pas toutes les destructions (<code class="language-plaintext highlighter-rouge">E6_Destruction</code>) qui sont des activités (<code class="language-plaintext highlighter-rouge">E7_Activité</code>). L’<a href="#heritage-multiple"><span class="underline">héritage multiple</span></a>, quant à lui, désigne le fait que toutes les instances d’une classe <code class="language-plaintext highlighter-rouge">A</code> sont implicitement des instances de toutes les <a href="#super-classe"><span class="underline">super-classes</span></a> de <code class="language-plaintext highlighter-rouge">A</code> (du fait de la définition de cette classe) alors que la combinaison des classes utilisée lors d’une instanciation multiple est caractéristique des instances mobilisées seulement. L’instanciation multiple ne peut mobiliser une combinaison de classes <a href="#disjointe"><span class="underline">disjointes</span></a>. </p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p></p>
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
<a name="endurant-perdurant"></a><p>Endurant, Perdurant</p>
</td>
<td>
<p>« La différence entre des entités endurantes et perdurantes (des endurants et des perdurants) repose sur leur fonctionnement dans le temps : les endurants sont présents dans leur entièreté (c.-à-d. qu’ils comprennent toutes leurs parties constituantes) peu importe le moment auquel ils sont présents. Les perdurants, quant à eux, se construisent dans le temps par l’accumulation d’éléments, de telle sorte qu’ils ne sont toujours que partiellement présents dans la mesure où certains de leurs éléments temporellement déterminés (p. ex. leurs incarnations passées ou futures) peuvent ne pas être présents. Par exemple, une feuille de papier [n.d.t. dont le contenu fait l’objet d’une lecture] est pleinement présente, bien que certains éléments de la lecture ne le soient plus. Les philosophes considèrent les endurants comme des entités situées dans le temps, mais qui n’ont pas de parties temporelles,<em> </em>car celles-ci évoluent dans le temps avec eux. Au contraire, les perdurants sont des entités qui s’incarnent dans le temps et qui peuvent avoir des parties temporelles, car celles-ci sont toutes fixées temporellement » (Gangemi et al. 2002, pp. 166-181).</p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
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
<a name="raccourci"></a><p>Raccourci</p>
</td>
<td>
<p>Un raccourci est une <a href="#propriete"><span class="underline"><strong>propriété</strong></span></a> singulière formellement définie qui représente un chemin sémantique (obtenu par déduction ou par union) dans le CIDOC CRM. Les <a href="#notes-dapplication"><span class="underline"><strong>notes d’application</strong></span></a> de toutes les propriétés caractérisées de raccourcis décrivent verbalement les déductions ou unions concernées. Les raccourcis sont utilisés lorsque la pratique documentaire réfère uniquement au résultat déduit plutôt qu’au chemin sémantique complet. Par exemple, les institutions muséales ne recensent souvent que les dimensions d’un objet sans pour autant documenter le <code class="language-plaintext highlighter-rouge">E16_Mesurage</code> qui les sous-tend. Le CIDOC CRM déclare explicitement des propriétés singulières à titre de raccourcis afin de permettre aux utilisateurs de décrire des cas dont ce ne sont pas toutes les connaissances associées au chemin sémantique complet qui sont recensées. Chaque raccourci du CIDOC CRM contient dans ses schémas les propriétés du chemin sémantique complet qui l’explique. </p>
<p></p>
<p>[n.d.t. voir <a href="#raccourci"><span class="underline">Des raccourcis</span></a> dans les <a href="/cidoc_crm_fr-ca/v7.1/information/principes-de-modelisation"><span class="underline">Principes de modélisation</span></a>].</p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p>Le terme « join of a data » a été traduit par « union » plutôt que par « fusion », car il s’agit de les réunir sans en annihiler l’une ou l’autre. </p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Termium. 2009. « join ». Termium Plus. 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=join&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=join&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=join&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
</td>
</tr>
<tr>
<td class="en">
<p>monotonic reasoning</p>
<p><em></em></p>
</td>
<td class="en">
<p>Monotonic reasoning is a term from knowledge representation. A reasoning form is monotonic if an addition to the set of propositions making up the knowledge base never determines a decrement in the set of conclusions that may be derived from the knowledge base via inference rules. In practical terms, if experts enter subsequently correct statements to an information system, the system should not regard any results from those statements as invalid, when a new one is entered. The CIDOC CRM is designed for monotonic reasoning and so enables conflict-free merging of huge stores of knowledge.</p>
<p></p>
</td>
<td>
<a name="raisonnement-monotone"></a><p>Raisonnement monotone</p>
</td>
<td>
<p>Le raisonnement monotone (un terme issu du domaine de la représentation des connaissances) stipule qu’une forme est monotone si une addition à l’ensemble de propositions qui forme la base de connaissances ne détermine jamais de décrément de l’ensemble des conclusions qui peuvent être dérivées (par des règles d’inférence) d’une base de connaissance. [n.d.t. Un décrément est une quantité constante prédéterminée dont on soustrait la valeur d’une variable.] En pratique, si des experts intègrent à un système d’information des énoncés corrects, ce système ne devrait considérer aucun de ces énoncés invalides lorsqu’un nouvel énoncé est ajouté. C’est ainsi qu’est conçu le CIDOC CRM, de sorte qu’il assure une fusion d’importants ensembles de connaissances sans conflits. </p>
<p></p>
<p>[n.d.t. voir la section sur la <a href="/cidoc_crm_fr-ca/v7.1/information/principes-de-modelisation#de-la-monotonicite"><span class="underline">Monotonicité</span></a> dans les <a href="/cidoc_crm_fr-ca/v7.1/information/principes-de-modelisation"><span class="underline">Principes de modélisation</span></a>].</p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p>Ajout d’une définition du décrément selon sa définition logicielle (quantité constante prédéterminée dont on soustrait la valeur d’une variable) plutôt que mathématique (diminution de la valeur d’une quantité variable). </p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Wikipedia. 2017. « Monotonie ». Dans <em>Wikipédia</em>. San Francisco, CA: Wikipedia. <a href="https://fr.wikipedia.org/w/index.php?title=Monotonie&oldid=134697868"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Monotonie&oldid=134697868</span></a>.</p>
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
<a name="disjointe"></a><p>Disjoint•e</p>
</td>
<td>
<p>Des classes sont disjointes si l’intersection de leurs extensions est un ensemble vide; en d’autres termes, il n’y a pas de possibilité qu’elles aient des instances communes. </p>
<p></p>
<p>[n.d.t. voir la section <a href="/cidoc_crm_fr-ca/v7.1/information/principes-de-modelisation#de-la-disjonction"><span class="underline">De la disjonction</span></a> dans les <a href="/cidoc_crm_fr-ca/v7.1/information/principes-de-modelisation"><span class="underline">Principes de modélisation</span></a>]. </p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p></p>
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
<a name="primitive"></a><p>Primitive</p>
</td>
<td>
<p>Une primitive (utilisée dans le cadre de la représentation de connaissances) est un concept qui est déclaré et dont la signification est acceptée, mais qui ne peut être définie par une déduction logique reposant sur d’autres concepts. Par exemple, « mère » est un concept qui peut être décrit comme « femme qui a un enfant”, de sorte qu’il n’est pas primitif [n.d.t. car il peut être déduit des concepts femme et enfant], alors que <code class="language-plaintext highlighter-rouge">E5_Évènement</code> est un concept primitif (ainsi que la plupart des concepts du CIDOC CRM). </p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
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
<p>Termium. 2009. « primitive ». Termium Plus. 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=primitive&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=primitive&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=primitive&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
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
<a name="monde-ouvert"></a><p>Monde Ouvert</p>
</td>
<td>
<p>L’hypothèse du « monde ouvert » porte sur les systèmes de bases de connaissances et stipule que l’information qui y est stockée est incomplète en comparaison de l’univers discursif que cette information représente. Cette incomplétude peut être due à l’incapacité du responsable [n.d.t. de la base de connaissance] de fournir des informations complètes ou encore à des problèmes plus fondamentaux du domaine eu égard à la cognition, problèmes qui sont caractéristiques des systèmes d’information sur le patrimoine culturel. En effet, les enregistrements au sujet du passé sont nécessairement incomplets et certains éléments pourraient ne pas être facilement attribuables à une <strong>classe</strong> préétablie. </p>
<p>Qui plus est, l’absence d’une <strong>propriété</strong> pour un élément décrit dans un système [n.d.t. d’information] n’implique pas automatiquement que cet élément n’a pas la propriété en question. Par exemple, si un élément est décrit comme un <code class="language-plaintext highlighter-rouge">E20_Objet_biologique</code> et qu’un autre est décrit comme un <code class="language-plaintext highlighter-rouge">E19_Objet_matériel</code>, rien n’indique que ce dernier ne soit pas lui aussi un <code class="language-plaintext highlighter-rouge">E20_Objet_biologique</code>. Ainsi, les <strong>compléments</strong> d’une classe eu égard à une <strong>super-classe</strong> ne peuvent être logiquement inférés depuis un système d’information mobilisant l’hypothèse du monde ouvert. Par exemple, il est impossible d’énumérer « tous les <code class="language-plaintext highlighter-rouge">E19_Objet_matériel</code> d’un système qui ne sont pas des <code class="language-plaintext highlighter-rouge">E20_Objet_biologique</code> dans le monde réel”, mais il est néanmoins possible d’énumérer « tous les éléments <code class="language-plaintext highlighter-rouge">E19_Objet_matériel</code> connus de ce système qui ne sont pas des <code class="language-plaintext highlighter-rouge">E20_Objet_biologique</code> connus de ce même système”.</p>
<p></p>
<p>[n.d.t. voir la section sur la <a href="/cidoc_crm_fr-ca/v7.1/information/principes-de-modelisation#de-la-minimalite"><span class="underline">Minimalité</span></a> dans les <a href="/cidoc_crm_fr-ca/v7.1/information/principes-de-modelisation"><span class="underline">Principes de modélisation</span></a>].</p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p></p>
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
<a name="complement"></a><p>Complément</p>
</td>
<td>
<p>Le complément d’une <a href="#classe"><span class="underline">classe</span></a> <code class="language-plaintext highlighter-rouge">A</code> par rapport à une de ses  <a href="#super-classe"><span class="underline"><strong>super-classes</strong></span></a> <code class="language-plaintext highlighter-rouge">B</code> est l’ensemble de toutes les <a href="#instance"><span class="underline"><strong>instances</strong></span></a> de <code class="language-plaintext highlighter-rouge">B</code> qui ne sont pas des instances de <code class="language-plaintext highlighter-rouge">A</code>. Formellement, il s’agit (en ce qui a trait à la théorie des ensembles) de l’<a href="#extension"><span class="underline"><strong>extension</strong></span></a> de <code class="language-plaintext highlighter-rouge">B</code> moins l’extension de <code class="language-plaintext highlighter-rouge">A</code>. Les extensions compatibles de CIDOC CRM ne devraient déclarer aucune classe dont l’<a href="#extension"><span class="underline"><strong>intension</strong></span></a> est le complément de l’une ou de plusieurs classes. Ceci contreviendrait aux principes du <a href="#monde-ouvert"><span class="underline"><strong>Monde Ouvert</strong></span></a> [n.d.t. selon lesquels], par exemple, pour tous les genres humains possibles, le masculin ne devrait pas être déclaré complémentaire du féminin et vice-versa. </p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p></p>
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
<a name="inclusion-des-requetes"></a><p>Inclusion des requêtes</p>
</td>
<td>
<p>L’inclusion des requêtes [n.d.t relève de la théorie des bases de données et statue] que pour une requête <code class="language-plaintext highlighter-rouge">X</code> qui contient une requête <code class="language-plaintext highlighter-rouge">Y</code>, pour chaque population possible de la base de données l’ensemble de résultats de la requête <code class="language-plaintext highlighter-rouge">X</code> contient aussi l’ensemble de résultats de la requête <code class="language-plaintext highlighter-rouge">Y</code>. [n.d.t. Dans le cadre de CIDOC CRM, ceci implique que] si les requêtes <code class="language-plaintext highlighter-rouge">X</code> et <code class="language-plaintext highlighter-rouge">Y</code> étaient des <a href="#classe"><span class="underline">classes</span></a>, alors <code class="language-plaintext highlighter-rouge">X</code> serait <a href="#super-classe"><span class="underline"><strong>super-classe</strong></span></a> de <code class="language-plaintext highlighter-rouge">Y</code>. </p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p>Le terme « query containment » a été traduit par « inclusion des requêtes ». Le « containment » est généralement traduit dans le domaine de l’algèbre par « inclusion » et dans le domaine logiciel par « contenance ». Puisqu’il s’agit d’un problème fondamentalement théorique et algorithmique, il est apparu préférable de se rapprocher de l’usage mathématique.</p>
<p>La dernière phrase du texte original semble avoir pour objectif d’inclure toutes les personnes, mais elle est formulée de manière quelque peu cavalière et ne s’aligne pas avec l’approche des autres exemples mentionnés de sorte qu’elle pourrait être considérée marginalisante et peu inclusive. Puisqu’elle n’apporte pas d’information supplémentaire, elle a été retirée du texte traduit. </p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Groz, Benoît. 2008. « Inclusion et équivalence de requêtes conjonctives ». Rapport de stage, Paris, FR: Institut national de recherche en sciences et technologies du numérique. <a href="https://www.lri.fr/~groz/documents/rapport.pdf"><span class="underline">https://www.lri.fr/~groz/documents/rapport.pdf</span></a>.</p>
<p>Termium. 2009. « containment ». Termium Plus. 8 octobre 2009. <a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=containment&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=containment&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
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
<a name="interoperabilite-syntactique"></a><p>Interopérabilité [syntactique]</p>
</td>
<td>
<p>L’interopérabilité<strong> </strong>réfère à la capacité de différents systèmes d’information de communiquer de l’information [n.d.t. entre eux], ce qui implique : </p>
<ul><li><p>que deux systèmes peuvent échanger de l’information et/ou</p>
</li>
<li><p>qu’il est possible d’accéder à plusieurs systèmes grâce à une seule méthode. </p>
</li></ul>
<p>Généralement, l’interopérabilité syntactique se distingue de l’<a href="#interoperabilite-semantique"><span class="underline"><strong>interopérabilité sémantique</strong></span></a> par le fait que l’information encodée et les protocoles d’accès syntactiques sont compatibles de telle sorte que l’information peut être traitée sans erreur. Par contre, ceci ne garantit pas que chaque système traite les données en adéquation avec la signification initiale des données. Par exemple, un système peut avoir une table « Acteur » alors qu’un autre peut avoir une table « Agent » [n.d.t. qui traitent toutes deux le même type d’information]. L’interopérabilité syntactique ne permet d’extraire les données que de manière distincte malgré que leur sens soit le même. La prise en compte de la signification des données lors de leur traitement nécessite en effet l’usage de l’interopérabilité sémantique en plus de l’interopérabilité syntactique. Le CIDOC CRM se repose sur cette dernière et n’a pour objectif que d’ajouter l’<em>interopérabilité sémantique</em>. </p>
<p></p>
<p>[n.d.t. voir aussi <a href="#interoperabilite-semantique"><span class="underline">Interopérabilité sémantique</span></a>].</p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p></p>
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
<p></p>
<p>Therefore, semantic interoperability is regarded as achieved if elements can be found that provide a reasonably close generalization for the transfer or merge. This problem is being studied theoretically as the <strong>query containment </strong>problem. The CIDOC CRM is only concerned with semantic interoperability on the level of data structure elements. </p>
</td>
<td>
<a name="interoperabilite-semantique"></a><p>Interopérabilité sémantique</p>
</td>
<td>
<p>L’<strong>interopérabilité</strong> sémantique réfère à la capacité de différents systèmes d’information de communiquer de l’information [n.d.t. entre eux] en adéquation avec sa signification initiale, ce qui comprend : </p>
<ul><li><p>les éléments de la structure de données impliqués;</p>
</li>
<li><p>la terminologie présentée comme données; </p>
</li>
<li><p>les identifiants représentant des éléments factuels comme des lieux, des personnes et des objets dans les données. </p>
</li></ul>
<p>La communication des éléments structurels doit être résolue en premier lieu. Une communication adéquate implique à cet égard que les données transférées d’une structure à l’autre conservent leur signification, ou que les données référant aux mêmes éléments et ayant la même signification soient fusionnées. En pratique cependant, en raison des niveaux de généralisation qui varient d’un système à l’autre, ceci n’est souvent pas possible. </p>
<p></p>
<p>L’interopérabilité sémantique est donc considérée atteinte si des éléments attestant une généralisation raisonnablement comparable au transfert ou à la fusion [n.d.t. des données concernées] sont identifiés. Ceci est un problème théorique étudié sous le nom du problème de <a href="#inclusion-des-requetes"><span class="underline"><strong>l’« inclusion des requêtes</strong></span></a> »; le CIDOC CRM, pour sa part, ne se concentre que sur l'interopérabilité sémantique des éléments structurés. </p>
<p></p>
<p>[n.d.t. voir aussi <a href="#interoperabilite-syntactique"><span class="underline">Interopérabilité syntactique</span></a>].</p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
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
<p>Groz, Benoît. 2008. « Inclusion et équivalence de requêtes conjonctives ». Rapport de stage, Paris, FR: Institut national de recherche en sciences et technologies du numérique. <a href="https://www.lri.fr/~groz/documents/rapport.pdf"><span class="underline">https://www.lri.fr/~groz/documents/rapport.pdf</span></a>.</p>
<p>Termium. 2009a. « containment ». Termium Plus. 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=containment&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=containment&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=containment&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
<p>———. 2009b. « merge ». Termium Plus. 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=merge&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=merge&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=merge&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
</td>
</tr>
<tr>
<td class="en">
<p>property quantifiers</p>
<p><em></em></p>
</td>
<td class="en">
<p>We use the term "property quantifiers" for the declaration of the allowed number of <strong>instances</strong> of a certain <strong>property</strong> that can refer to a particular instance of the <strong>range </strong>class or the <strong>domain</strong> class of that property. These declarations are ontological, i.e., they refer to the nature of the real world described and not to our current knowledge. For example, each person has exactly one father, but collected knowledge may refer to none, one or many.</p>
<p></p>
</td>
<td>
<a name="quantificateurs-de-propriete"></a><p>Quantificateurs de propriété</p>
</td>
<td>
<p>Le terme « quantificateurs de propriété » désigne la déclaration du nombre autorisé d’<a href="#instance"><span class="underline"><strong>instances</strong></span></a> d’une <a href="#propriete"><span class="underline"><strong>propriété</strong></span></a> qui peut référer à une instance particulière d’une <a href="#classe"><span class="underline">classe</span></a> de <a href="#portee"><span class="underline"><strong>portée</strong></span></a> ou de <a href="#domaine"><span class="underline"><strong>domaine</strong></span></a> de cette propriété. Ces déclarations sont ontologiques, c.-à-d. qu’elles concernent la nature du monde « réel » qui est décrit plutôt que la connaissance de celui-ci. Par exemple, chaque personne a exactement un père [n.d.t. biologique] même si les connaissances recensées peuvent n’en indiquer aucun ou plusieurs. </p>
<p></p>
<p>[n.d.t. voir la section <a href="/cidoc_crm_fr-ca/v7.1/information/compatibilite-avec-le-cidoc-crm#quantificateurs-de-proprietes"><span class="underline">Quantificateurs de propriétés</span></a> dans la section <a href="/cidoc_crm_fr-ca/v7.1/information/compatibilite-avec-le-cidoc-crm"><span class="underline">Compatibilité avec le CIDOC CRM</span></a>].</p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p></p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Termium. 2009. « quantifier ». Termium Plus. 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=quantifier&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=quantifier&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=quantifier&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
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
<a name="universel"></a><p>universel</p>
</td>
<td>
<p>La distinction ontologique fondamentale entre universel et particulier peut être comprise informellement en examinant la relation de chacun avec son instanciation : alors que les particuliers n’ont aucune <a href="#instance"><span class="underline"><strong>instance</strong></span></a> possible, peu importe le monde dans lequel ils se trouvent, les universels sont des entités qui, elles, ont des instances. Les <a href="#classe"><span class="underline"><strong>classes</strong></span></a> et <a href="#propriete"><span class="underline"><strong>propriétés</strong></span></a> (qui correspondent en langage logique à des prédicats) sont généralement considérées être des universels (Gangemi & al. 2002, p. 166-181).</p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p></p>
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
<p></p>
<p>A distinct exception to this rule is represented by information in the data set that carries with it an explicit statement of responsibility.</p>
<p>In CIDOC CRM such statements of responsibility are expressed through knowledge creation events such as E13 Attribute Assignment and its relevant subclasses. Any information in a CIDOC CRM model that is based on an explicit creation event for that piece of information, where the creator’s identity has been given, is attributed to the authority and assigned to the responsibility of the actor identified as causal in that event. For any information in the system connected to knowledge creation events that do not explicitly reference their creator, as well as any information not connected to creation events, the responsibility falls back to the institution responsible for the database/knowledge graph. That means that for information only expressed through shortcuts such as <em>P2 has type</em>, where no knowledge creation event has been explicitly specified, the originating creation event cannot be deduced and the responsibility for the information can never be any other body than the institution responsible for the whole information system.</p>
<p></p>
<p>In the case of an institution taking over stewardship of a database transferred into their custody, two relations of responsibility for the knowledge therein can be envisioned. If the institution accepts the dataset and undertakes to maintain and update it, then they take on responsibility for that information and become the default authority behind its statements as described above. If, on the other hand, the institution accepts the data set and stores it without change as a closed resource, then it can be considered that the default authority remains the original steward.</p>
</td>
<td>
<a name="processus-de-creation-de-connaissances"></a><p>Processus de création de connaissances</p>
</td>
<td>
<p>Toute connaissance contenue dans un système d’information doit avoir été introduite dans ce système par un agent humain, que ce soit de manière directe ou indirecte. Malgré cela, plusieurs, si ce n’est la plupart, des énoncés de tels systèmes n’ont pas d’information associée quant à la personne ayant autorité sur eux. Néanmoins, le milieu patrimonial a des pratiques d’assignation de l’autorité établissant comment et par qui une information peut être introduite ou modifiée dans un système, en particulier dans le contexte de la documentation et de la gestion des collections. Ces pratiques sont idéalement recensées dans le cadre de politiques institutionnelles et de protocoles documentaires. Il est donc raisonnable de considérer que, dans le cadre de tels systèmes d’information, tout énoncé n’ayant pas une assignation explicite d’autorité représente la position officielle de l’institution responsable du système.</p>
<p></p>
<p>Cette posture [n.d.t. du CIDOC CRM] n’implique cependant pas qu’un système d’information représente un état abouti des connaissances promues par l’institution qui en est responsable. Cette posture a plutôt pour objectif de mettre en évidence qu’un ensemble de données patrimoniales (à un quelconque degré d’élaboration) incarne une adhésion à un ensemble de standards qui garantissent la validité des données dans le cadre de celui-ci et de ses limitations. Tant que l’information [n.d.t. contenue dans le système d’information] est activement maintenue, elle demeure sujette à des améliorations, modifications et révisions au fur et à mesure que la recherche à son sujet présente de nouveaux éléments à son égard ou à l’égard de ce qui l’entoure. </p>
<p></p>
<p>De l’information dans un ensemble de données auquel est associé un énoncé explicite de responsabilité constitue une exception notable à cette règle. Dans CIDOC CRM, de tels énoncés de responsabilité sont exprimés par des évènements de création de connaissances tels que <code class="language-plaintext highlighter-rouge">E13_Attribution</code> ou ses sous-classes pertinentes. Toute information dans un modèle CIDOC CRM basée sur un évènement de création explicite de cette information (où l’identité du créateur est spécifiée) a pour autorité et responsable le créateur en question. Pour toute information dans ce système qui n’a pas de référence explicite à un créateur spécifique ainsi que pour toute information qui n’est pas liée à un évènement de création, la responsabilité de l’information revient à l’institution qui assume la gestion de la base et du graphe de connaissances. Ceci implique que l’information qui n’est exprimée que grâce à des raccourcis (p. ex.  <code class="language-plaintext highlighter-rouge">P2_a_pour_type</code>) : </p>
<ul><li><p>n’est pas associée à un évènement explicite de création de connaissances; </p>
</li>
<li><p>ne peut pas être associée à un évènement de création originel, car celui-ci ne peut être déduit; </p>
</li>
<li><p>ne peut avoir pour responsable que l’institution responsable du système d’information (et qu’aucun autre organisme ne peut en être imputable). </p>
</li></ul>
<p></p>
<p>Lorsqu’une institution prend à sa charge une base de données dans le cadre d’un transfert de sa garde d’une autorité administrative à une autre, deux relations de responsabilité sur les connaissances qui s’y trouvent sont possibles. Si l’institution hôte accepte la responsabilité de la maintenance des informations, elle devient l’autorité associée par défaut aux énoncés qui s’y trouvent. Si, par contre, l’institution hôte traite l’ensemble des données comme une ressource « fermée » [n.d.t. donc traité à la manière d’un artefact], l’autorité associée par défaut aux énoncés qui s’y trouvent sera celle de l’institution initiale [n.d.t. comme c’est le cas de tout autre document de recherche se trouvant dans la collection de l’institution hôte].  </p>
<p></p>
<p>[n.d.t. voir <a href="/cidoc_crm_fr-ca/v7.1/information/principes-de-modelisation#de-lauctorialite-des-contenus-dune-base-de-connaissances"><span class="underline">De l’auctorialité des contenus d’une base de connaissances</span></a> dans les <a href="/cidoc_crm_fr-ca/v7.1/information/principes-de-modelisation"><span class="underline">Principes de modélisation</span></a>]. </p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p>Le terme « information system » a été traduit par « système d’information ». </p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Termium. 2009. « Information System ». Termium Plus. 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-eng.html?lang=eng&i=1&srchtxt=INFORMATION+SYSTEM&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-eng.html?lang=eng&i=1&srchtxt=INFORMATION+SYSTEM&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-eng.html?lang=eng&i=1&srchtxt=INFORMATION+SYSTEM&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
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
<a name="transitivite"></a><p>Transitivité</p>
</td>
<td>
<p>La transitivité (définie selon des principes mathématiques et logiques) signifie qu’une <a href="#propriete"><span class="underline">propriété</span></a> <code class="language-plaintext highlighter-rouge">P</code> est réflexive si son <a href="#domaine"><span class="underline">domaine</span></a> et sa <a href="#portee"><span class="underline">portée</span></a> sont la même <a href="#classe"><span class="underline">classe</span></a>, et que pour toutes les <a href="#instance"><span class="underline">instances</span></a> <code class="language-plaintext highlighter-rouge">x</code>, <code class="language-plaintext highlighter-rouge">y</code>, <code class="language-plaintext highlighter-rouge">z</code> de cette classe si <code class="language-plaintext highlighter-rouge">x</code> est relié par <code class="language-plaintext highlighter-rouge">P</code> à <code class="language-plaintext highlighter-rouge">y</code> et que <code class="language-plaintext highlighter-rouge">y</code> est relié par <code class="language-plaintext highlighter-rouge">P</code> à <code class="language-plaintext highlighter-rouge">z</code>, alors <code class="language-plaintext highlighter-rouge">x</code> est relié par <code class="language-plaintext highlighter-rouge">P</code> à <code class="language-plaintext highlighter-rouge">z</code>. L’intention de la propriété telle qu’elle est établie dans sa <a href="#note-dapplication"><span class="underline">note d’application</span></a> détermine si elle est transitive ou non. Par exemple, la propriété <code class="language-plaintext highlighter-rouge">P121_se_superpose_partiellement_à</code> entre des instances d’<code class="language-plaintext highlighter-rouge">E53_Lieu</code> n’est pas transitive alors que la propriété  <code class="language-plaintext highlighter-rouge">P89_s’insère_dans (inclut)</code> entre des instances d’<code class="language-plaintext highlighter-rouge">E53_Lieu</code> et la propriété <code class="language-plaintext highlighter-rouge">P46_est_composé_de (fait_partie_de)</code> entre des instances de <code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code> sont toutes deux transitives. La transitivité est particulièrement utile lors de l’implémentation de CIDOC CRM dans un système qui utilise la déduction logique. </p>
<p></p>
<p>[n.d.t. voir <a href="/cidoc_crm_fr-ca/v7.1/information/principes-de-modelisation#de-lheritage-et-de-la-transitivite"><span class="underline">De l’héritage et de la transitivité</span></a> dans les <a href="/cidoc_crm_fr-ca/v7.1/information/principes-de-modelisation"><span class="underline">Principes de modélisation</span></a>]. </p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p></p>
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
<a name="symetrie"></a><p>Symétrie</p>
</td>
<td>
<p>La symétrie (définie selon des principes mathématiques et logiques) signifie qu’une <a href="#propriete"><span class="underline">propriété</span></a> <code class="language-plaintext highlighter-rouge">P</code> est symétrique si son <a href="#domaine"><span class="underline">domaine</span></a> et sa <a href="#portee"><span class="underline">portée</span></a> sont la même <a href="#classe"><span class="underline">classe</span></a>, et que pour toutes les <a href="#instance"><span class="underline">instances</span></a> <code class="language-plaintext highlighter-rouge">x, y</code> de cette classe si <code class="language-plaintext highlighter-rouge">x</code> est relié par <code class="language-plaintext highlighter-rouge">P</code> à <code class="language-plaintext highlighter-rouge">y</code>, alors <code class="language-plaintext highlighter-rouge">y</code> est relié par <code class="language-plaintext highlighter-rouge">P</code> à <code class="language-plaintext highlighter-rouge">x</code>. L’intention de la propriété (telle qu’elle est établie dans sa <a href="#note-dapplication"><span class="underline">note d’application</span></a>) détermine si elle est symétrique ou non. Un exemple de propriété symétrique est <code class="language-plaintext highlighter-rouge">E53_Lieu</code>. <code class="language-plaintext highlighter-rouge">P122_est_limitrophe_de</code> : <code class="language-plaintext highlighter-rouge">E53_Lieu</code>. Les noms de propriétés symétriques n’ont pas de forme parenthétique, car les lire depuis la portée vers le domaine revient au même que les lire depuis le domaine vers la portée. </p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p></p>
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
<a name="reflexivite"></a><p>Réflexivité</p>
</td>
<td>
<p>La réflexivité (définie selon des principes mathématiques et logiques standards) signifie qu’une <a href="#propriete"><span class="underline">propriété</span></a> <code class="language-plaintext highlighter-rouge">P</code> est réflexive si son <a href="#domaine"><span class="underline">domaine</span></a> et sa <a href="#portee"><span class="underline">portée</span></a> sont la même <a href="#classe"><span class="underline">classe</span></a>, et que pour toutes les <a href="#instance"><span class="underline">instances</span></a> <code class="language-plaintext highlighter-rouge">x</code> de cette classe <code class="language-plaintext highlighter-rouge">x</code> est relié à lui-même par <code class="language-plaintext highlighter-rouge">P</code>. L’intention de la propriété (telle qu’elle est établie dans sa note d’application) détermine si elle réflexive ou non. Un exemple de propriété réflexive est <code class="language-plaintext highlighter-rouge">E53_Lieu</code>. <code class="language-plaintext highlighter-rouge">P89_s’insère_dans (inclut)</code> : <code class="language-plaintext highlighter-rouge">E53_Lieu</code>. </p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p><em></em></p>
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

