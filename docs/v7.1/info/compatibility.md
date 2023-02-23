---
layout: page
title:  Compatibilité avec le CIDOC CRM
titleEn: Compatibility with the CIDOC CRM - Compatibilité avec le CIDOC CRM
permalink: /v7.1/information/compatibilite-avec-le-cidoc-crm
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
<p>Users intending to take advantage of the semantic interoperability offered by the CIDOC CRM should ensure conformance with the relevant data structures. Conformance pertains either to data to be made accessible in an integrated environment or intended for transport to other environments. Any encoding of data in a formal language that preserves the relations of the classes, properties, and inheritance rules defined by this International Standard, is regarded as conformant.</p>
<p></p>
<p>Conformance with the CIDOC CRM does not require complete matching of all local documentation structures, nor that all concepts and structures present in this International Standard be implemented. This International Standard is intended to allow room both for extensions, needed to capture the full richness of cultural documentation, and for simplification, in the interests of economy. A system will be deemed partially conformant if it supports a subset of subclasses and sub properties defined by this International Standard. Designers of the system should publish details of the constructs that are supported.</p>
<p></p>
<p>The focus of the CIDOC CRM is the exchange and mediation of structured information. It does not require the interpretation of unstructured (free text) information into a structured, logical form. Unstructured information is supported, but falls outside the scope of conformance considerations.</p>
<p></p>
<p>Any documentation system will be deemed conformant with this International Standard, regardless of the internal data structures it uses; if a deterministic logical algorithm can be constructed, that transforms data contained in the system into a directly compatible form without loss of meaning.</p>
<p></p>
<p>No assumptions are made as to the nature of this algorithm. "Without loss of meaning" signifies that designers and users of the system are satisfied that the data representation corresponds to the semantic definitions provided by this International Standard.   </p>
</td>
<td>
<p>Les utilisateurs voulant tirer avantage de l’interopérabilité sémantique du CIDOC CRM devraient s’assurer de la conformité de leurs structures de données avec celui-ci. La conformité des données réfère à leur accessibilité dans le contexte d’un environnement [n.d.t. d’utilisateur] intégré ou de leur transfert vers d’autres environnements. </p>
<p></p>
<p>Tout encodage de données dans un langage formel qui maintient les relations des classes, des propriétés, ainsi que des règles d’<a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#heritage"><span class="underline">héritage</span></a> définies par le CIDOC CRM est considéré y être conforme. Ceci dit, cette conformité ne requiert pas une équivalence complète de toutes les structures de documentation locales, ni que tous les concepts et structures du CIDOC CRM ne soient implémentés. </p>
<p></p>
<p>Ce standard international a pour objectif de permettre la mise en place d’extensions nécessaires pour saisir la richesse des phénomènes culturels et de leur documentation, et ce, tout en prônant la parcimonie. Un système est considéré partiellement conforme s’il soutient un sous-ensemble des <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#sous-classe"><span class="underline">sous-classes</span></a> et <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#sous-propriete"><span class="underline">sous-propriétés </span></a>définies par ce standard. Les concepteurs de systèmes devraient publier le détail des construits qui sont supportés par leur système. </p>
<p></p>
<p>Le CIDOC CRM porte principalement sur l’échange et la médiation d’information structurée et n’exige pas l’interprétation d’information non structurée dans une forme logique. L’information non structurée peut être traitée par le CIDOC CRM, mais les résultats qui en découlent ne sont pas pris en compte dans l’évaluation de la conformité d’un système. </p>
<p></p>
<p>Tout système documentaire sera considéré conforme [n.d.t. avec les règles du CIDOC CRM], peu importe les structures de données internes qu’il utilise, si des algorithmes peuvent transformer les données non structurées du système en une forme compatible avec le CIDOC CRM sans que la signification n’en soit affectée.</p>
<p></p>
<p>« Sans que la signification n’en soit affectée » signifie que les concepteurs et les utilisateurs du système considèrent que la représentation résultant de l’utilisation de cet algorithme correspond aux définitions sémantiques fournies dans ce standard. </p>
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
<p>Le terme « construct » n’a pas d’équivalent français parfait, mais une recherche sommaire révèle que le terme « construit » (n.m.) semble répandu dans les domaines de la philosophie et de la sociologie et est celui dont le sens se rapproche le plus de la forme originale. </p>
<p></p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="1">
<p>Termium. 2009. « construct ». Termium Plus. 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=construct&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=construct&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=construct&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
<p></p>
</td>
</tr>
</tbody>
</table>

<h2 id="quantificateurs-de-proprietes"><span class="en heading">Property Quantifiers - </span>Quantificateurs de propriétés</h2>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>Quantifiers for properties are provided for the purpose of semantic clarification only, and should <strong>not</strong> be treated as implementation recommendations. The CIDOC CRM has been designed to accommodate alternative opinions and incomplete information, and therefore <strong>all</strong> properties should be implemented as optional and repeatable for their domain and range (“many to many (0,n:0,n)”). Therefore, the term “cardinality constraints” is avoided here, as it typically pertains to implementations. <strong></strong></p>
<p></p>
<p>The following table lists all possible property quantifiers occurring in this document by their notation, together with an explanation in plain words. In order to provide optimal clarity, two widely accepted notations are used redundantly in this document, a verbal and a numeric one. The verbal notation uses phrases such as “one to many”, and the numeric one, expressions such as “(0,n:0,1)”. While the terms “one”, “many” and “necessary” are quite intuitive, the term “dependent” denotes a situation where a range instance cannot exist without an instance of the respective property. In other words, the property is “necessary” for its range. (Meghini, C. & Doerr, M., 2018).</p>
</td>
<td>
<p>Les <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#quantificateurs-de-propriete"><span class="underline">quantificateurs des propriétés</span></a> sont présentés ici à des fins de clarification sémantique seulement et ne devraient <strong>pas</strong> être considérés comme des recommandations d’implémentation. Le CIDOC CRM a été conçu afin d'accommoder des options alternatives ou des informations incomplètes [n.d.t. afin d’accommoder plusieurs interprétations ou compréhensions d’un même phénomène], de sorte que <strong>toutes</strong> les <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#propriete"><span class="underline">propriétés</span></a> devraient être implémentées avec un <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#domaine"><span class="underline">domaine</span></a> et une <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#portee"><span class="underline">portée</span></a> optionnels et répétables [n.d.t. c.-à-d. qu’une même propriété peut être utilisée à plusieurs reprises avec une même instance de son domaine] (« relation plusieurs-à-plusieurs (0,n:0,n) »). [n.d.t. Cette question des contraintes de cardinalité, qui précise les principes de généralisation d’une <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#classe"><span class="underline">classe</span></a>], porte généralement sur les implémentations d’un système [n.d.t. plutôt que sur sa conception], de sorte qu’il n’en est pas exhaustivement question ici et que l’expression « contraintes de cardinalité » n'est pas préconisée. </p>
<p></p>
<p>Le tableau suivant énumère les quantificateurs de propriété utilisés dans ce document (dans l’ordre de leur notation) ainsi qu’une explication en langage naturel [n.d.t. de chacun d’entre eux]. Les notations verbale et numérique sont juxtaposées dans ce document à des fins de clarté : la notation verbale utilise des syntagmes tels que « un à plusieurs » alors que la notation numérique utilise des expressions telles que « (0,n:0,1) ». Les termes « un », « plusieurs » et « nécessaire » [n.d.t. revêtent leur sens habituel et] intuitif; le terme « dépendant » indique une situation où une <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#instance"><span class="underline">instance</span></a> de la portée d’une propriété ne peut pas exister sans une instance de cette propriété elle-même. En d’autres termes, la propriété est « nécessaire » à sa portée (Meghini, C. & Doerr, M., 2018).</p>
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
<p>Un contrainte de cardinalité précise si une entité parent peut appartenir à plusieurs entités enfants (principe du recouvrement ou <em>overlapping</em>) ou à un seul (principe de la disjonction). </p>
<p></p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="1">
<p>Termium. 2009. « cardinalité ». Termium PLus. 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=cardinalit%C3%A9&index=frt&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=cardinalit%C3%A9&index=frt&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=cardinalit%C3%A9&index=frt&codom2nd_wet=1#resultrecs</span></a>.</p>
<p></p>
</td>
</tr>
</tbody>
</table>

<table>
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
<p>Illimité : Une <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#instance"><span class="underline">instance</span></a> du <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#domaine"><span class="underline">domaine</span></a> et une instance de la <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#portee"><span class="underline">portée</span></a> de cette <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#propriete"><span class="underline">propriété</span></a> peuvent n’avoir aucune, une ou plusieurs instances de cette propriété. En d’autres termes, cette propriété est optionnelle et répétable [n.d.t. c.-à-d. qu’une même propriété peut être utilisée à plusieurs reprises avec une même instance de son domaine] pour son domaine ainsi que pour sa portée. </p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p>Une propriété répétable est une propriété pouvant apparaître plus d'une fois dans un enregistrement. </p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Termium. 2009. « Répétable ». Termium Plus. 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE</span></a>.</p>
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
<p>Une <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#instance"><span class="underline">instance</span></a> individuelle du <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#domaine"><span class="underline">domaine</span></a> de cette <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#propriete"><span class="underline">propriété</span></a> peut n’avoir aucune, une ou plusieurs instance(s) de cette propriété, mais une instance individuelle de sa <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#portee"><span class="underline">portée</span></a> ne peut pas faire l’objet d’une référence par plus d’une instance de cette même propriété. En d’autres termes, le domaine et la portée de cette propriété sont optionnels, mais seul son domaine est répétable [n.d.t. c.-à-d. qu’une même propriété peut être utilisée à plusieurs reprises avec une même instance de son domaine]. Cette situation est parfois qualifiée de « sortance ». </p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p>Une propriété répétable est une propriété pouvant apparaître plus d'une fois dans un enregistrement. </p>
<p>Une recherche sommaire indique que le terme « fan-out » est surtout usité dans le domaine des circuits booléens et de l’intelligence artificielle, où il est parfois question d’arité sortante ou de sortance. </p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Termium. 2009a. « fan-out ». Termium Plus. 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-out&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-out&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-out&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
<p>———. 2009b. « Répétable ». Termium Plus. 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE</span></a>.</p>
<p>Wikipedia. 2020. « Fan-out ». Dans <em>Wikipédia</em>. San Francisco, CA: Wikipedia.<a href="https://fr.wikipedia.org/w/index.php?title=Fan-out&oldid=176479075"><span class="underline"> </span></a><a href="https://fr.wikipedia.org/w/index.php?title=Fan-out&oldid=176479075"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Fan-out&oldid=176479075</span></a>.</p>
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
<p>Une <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#instance"><span class="underline">instance</span></a> du <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#domaine"><span class="underline">domaine</span></a> de cette <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#propriete"><span class="underline">propriété</span></a> peut n’avoir aucune ou une seule instance de cette propriété, mais une instance de sa <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#portee"><span class="underline">portée</span></a> peut être référencée par aucune, une ou plusieurs instances de cette même propriété. En d’autres termes, le domaine et la portée de cette propriété sont optionnels, mais seule sa portée est répétable [n.d.t. c.-à-d. qu’une même propriété peut être utilisée à plusieurs reprises avec une même instance de son domaine]. Cette situation est parfois qualifiée d’« entrance ». </p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p>Une propriété répétable est une propriété pouvant apparaître plus d'une fois dans un enregistrement. </p>
<p>Une recherche sommaire indique que le terme « fan-in » est surtout usité dans le domaine des circuits booléens et de l’intelligence artificielle où il est parfois question d’arité entrante ou d’entrance. </p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Termium. 2009a. « fan-in ». Termium Plus. 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
<p>———. 2009b. « Répétable ». Termium Plus. 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE</span></a>.</p>
<p>Wikipedia. 2020. « Fan-in ». Dans <em>Wikipédia</em>. San Francisco, CA: Wikipedia.<a href="https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056"><span class="underline"> </span></a><a href="https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056</span></a>.</p>
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
<p>Une <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#instance"><span class="underline">instance</span></a> individuelle du <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#domaine"><span class="underline">domaine</span></a> de cette <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#propriete"><span class="underline">propriété</span></a> peut avoir une ou plusieurs instance(s) de cette propriété, mais une instance individuelle de sa <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#portee"><span class="underline">portée</span></a> peut n’avoir aucune, une ou plusieurs instances de cette même propriété. En d’autres termes, le domaine de cette propriété est nécessaire et répétable [n.d.t. c.-à-d. qu’une même propriété peut être utilisée à plusieurs reprises avec une même instance de son domaine] alors que sa portée est optionnelle et répétable [n.d.t. c.-à-d. qu’une même propriété peut être utilisée à plusieurs reprises avec une même instance de son domaine]. </p>
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
<p></p>
</td>
<td>
<p>Une <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#instance"><span class="underline">instance</span></a> individuelle du <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#domaine"><span class="underline">domaine</span></a> de cette <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#propriete"><span class="underline">propriété</span></a> peut n’avoir qu’une seule ou plusieurs instance(s) de cette propriété, mais une instance individuelle de sa <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#portee"><span class="underline">portée</span></a> ne peut pas être référencée par plus d’une instance de cette même propriété. En d’autres termes, le domaine de cette propriété est nécessaire et répétable [n.d.t. c.-à-d. qu’une même propriété peut être utilisée à plusieurs reprises avec une même instance de son domaine], mais sa portée est optionnelle. Dans certains contextes, cette situation est qualifiée de « sortance ».</p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p>Une propriété répétable est une propriété pouvant apparaître plus d'une fois dans un enregistrement. </p>
<p>Une recherche sommaire indique que le terme « fan-out » est surtout usité dans le domaine des circuits booléens et de l’intelligence artificielle, où il est parfois question d’arité sortante ou de sortance. </p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Termium. 2009a. « fan-out ». Termium Plus. 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-out&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-out&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-out&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
<p>———. 2009b. « Répétable ». Termium Plus. 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE</span></a>.</p>
<p>Wikipedia. 2020. « Fan-out ». Dans <em>Wikipédia</em>. San Francisco, CA: Wikipedia.<a href="https://fr.wikipedia.org/w/index.php?title=Fan-out&oldid=176479075"><span class="underline"> </span></a><a href="https://fr.wikipedia.org/w/index.php?title=Fan-out&oldid=176479075"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Fan-out&oldid=176479075</span></a>.</p>
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
<p>Une <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#instance"><span class="underline">instance</span></a> du <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#domaine"><span class="underline">domaine</span></a> de cette <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#propriete"><span class="underline">propriété</span></a> peut n’avoir qu’une seule instance de cette propriété, mais une instance de sa <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#portee"><span class="underline">portée</span></a> peut être référencée par aucune, une ou plusieurs instances de cette même propriété. En d’autres termes, le domaine de cette propriété est nécessaire et répétable [n.d.t. c.-à-d. qu’une même propriété peut être utilisée à plusieurs reprises avec une même instance de son domaine], mais sa portée est optionnelle et répétable [n.d.t. c.-à-d. qu’une même propriété peut être utilisée à plusieurs reprises avec une même instance de son domaine]. Cette situation est parfois qualifiée d’« entrance ».  </p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p>Une propriété répétable est une propriété pouvant apparaître plus d'une fois dans un enregistrement. </p>
<p>Une recherche sommaire indique que le terme « fan-in » est surtout usité dans le domaine des circuits booléens et de l’intelligence artificielle, où il est parfois question d’arité entrante ou d’entrance. </p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Termium. 2009a. « fan-in ». Termium Plus. 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
<p>———. 2009b. « Répétable ». Termium Plus. 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE</span></a>.</p>
<p>Wikipedia. 2020. « Fan-in ». Dans <em>Wikipédia</em>. San Francisco, CA: Wikipedia.<a href="https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056"><span class="underline"> </span></a><a href="https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056</span></a>.</p>
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
<p>Une <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#instance"><span class="underline">instance</span></a> individuelle du <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#domaine"><span class="underline">domaine</span></a> de cette <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#propriete"><span class="underline">propriété</span></a> peut n’avoir aucune, une ou plusieurs instance(s) de cette propriété, mais une instance individuelle de sa <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#portee"><span class="underline">portée</span></a> ne doit être référencée que par une seule instance de cette même propriété. En d’autres termes, le domaine de cette propriété est optionnel et répétable [n.d.t. c.-à-d. qu’une même propriété peut être utilisée à plusieurs reprises avec une même instance de son domaine], mais sa portée est nécessaire et non répétable [n.d.t. c.-à-d. qu’une même propriété peut être utilisée à plusieurs reprises avec une même instance de son domaine]. Cette situation est parfois qualifiée de « sortance ».</p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p>Une propriété répétable est une propriété pouvant apparaître plus d'une fois dans un enregistrement. </p>
<p>Une recherche sommaire indique que le terme « fan-out » est surtout usité dans le domaine des circuits booléens et de l’intelligence artificielle où il est parfois question d’arité sortante ou de sortance. </p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Termium. 2009a. « fan-out ». Termium Plus. 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-out&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-out&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-out&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
<p>———. 2009b. « Répétable ». Termium Plus. 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE</span></a>.</p>
<p>Wikipedia. 2020. « Fan-out ». Dans <em>Wikipédia</em>. San Francisco, CA: Wikipedia.<a href="https://fr.wikipedia.org/w/index.php?title=Fan-out&oldid=176479075"><span class="underline"> </span></a><a href="https://fr.wikipedia.org/w/index.php?title=Fan-out&oldid=176479075"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Fan-out&oldid=176479075</span></a>.</p>
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
<p>Une <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#instance"><span class="underline">instance</span></a> individuelle du <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#domaine"><span class="underline">domaine</span></a> de cette <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#propriete"><span class="underline">propriété</span></a> peut n’avoir qu’une seule ou plusieurs instance(s) de cette propriété, mais une instance individuelle de sa <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#portee"><span class="underline">portée</span></a> ne doit être référencée que par une seule instance de cette même propriété. En d’autres termes, le domaine de cette propriété est nécessaire et répétable [n.d.t. c.-à-d. qu’une même propriété peut être utilisée à plusieurs reprises avec une même instance de son domaine] et sa portée est nécessaire mais non répétable [n.d.t. c.-à-d. qu’une même propriété peut être utilisée à plusieurs reprises avec une même instance de son domaine]. Cette situation est parfois qualifiée de « sortance ».</p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p>Une propriété répétable est une propriété pouvant apparaître plus d'une fois dans un enregistrement. </p>
<p>Une recherche sommaire indique que le terme « fan-in » est surtout usité dans le domaine des circuits booléens et de l’intelligence artificielle, où il est parfois question d’arité entrante ou d’entrance.  </p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Termium. 2009a. « fan-in ». Termium Plus. 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
<p>———. 2009b. « Répétable ». Termium Plus. 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE</span></a>.</p>
<p>Wikipedia. 2020. « Fan-in ». Dans <em>Wikipédia</em>. San Francisco, CA: Wikipedia.<a href="https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056"><span class="underline"> </span></a><a href="https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056</span></a>.</p>
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
<p>Une <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#instance"><span class="underline">instance</span></a> individuelle du <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#domaine"><span class="underline">domaine</span></a> de cette <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#propriete"><span class="underline">propriété</span></a> doit n’avoir qu’une seule instance de cette propriété, mais une instance individuelle de sa <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#portee"><span class="underline">portée</span></a> peut être référencée par une ou plusieurs instances de cette même propriété. En d'autres termes, le domaine de cette propriété est nécessaire et non répétable, tandis que la portée est nécessaire et répétable. Cette situation est parfois qualifiée d’« entrance ». </p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p>Une propriété répétable est une propriété pouvant apparaître plus d'une fois dans un enregistrement. </p>
<p>Une recherche sommaire indique que le terme « fan-in » est surtout usité dans le domaine des circuits booléens et de l’intelligence artificielle, où il est parfois question d’arité entrante ou d’entrance. </p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Termium. 2009a. « fan-in ». Termium Plus. 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
<p>———. 2009b. « Répétable ». Termium Plus. 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE</span></a>.</p>
<p>Wikipedia. 2020. « Fan-in ». Dans <em>Wikipédia</em>. San Francisco, CA: Wikipedia.<a href="https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056"><span class="underline"> </span></a><a href="https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056</span></a>.</p>
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
<p>Une <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#instance"><span class="underline">instance</span></a> individuelle du <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#domaine"><span class="underline">domaine</span></a> et une instance de la <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#portee"><span class="underline">portée</span></a> de cette <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#propriete"><span class="underline">propriété</span></a> doivent avoir exactement une instance de cette propriété. En d’autres termes, le domaine et la portée de cette propriété sont nécessaires et non répétables [n.d.t. c.-à-d. qu’une même propriété ne peut être utilisée qu’une seule fois avec une instance de son domaine]. </p>
</td>
</tr>
<tr>
<th><p><em>Note traducteur</em></p>
</th>
<td colspan="3">
<p>Une propriété répétable est une propriété pouvant apparaître plus d'une fois dans un enregistrement. </p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p>Termium. 2009. « Répétable ». Termium Plus. 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE</span></a>.</p>
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
<p></p>
<ul><li><p>the property is necessary for the domain;</p>
</li>
<li><p>the property is necessary for the range, or, in other words, the range is dependent on the property.</p>
</li></ul>
<p></p>
<p>The possible kinds of dependencies are defined in the table above. Note that if a dependent property is not specified for an instance of the respective domain or range, it means that the property exists, but the value on one side of the property is unknown. In the case of optional properties, the methodology proposed by the CIDOC CRM does not distinguish between a value being unknown or the property not being applicable at all. For example, one may know that an object has an owner, but the owner is unknown. In a CIDOC CRM instance this case cannot be distinguished from the fact that the object has no owner at all. Of course, such details can always be specified by a textual note. </p>
</td>
<td>
<p>Le CIDOC CRM définit certains dépendants entre les <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#propriete"><span class="underline">propriétés</span></a> et les <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#classe"><span class="underline">classes</span></a> sous la forme de leur <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#domaine"><span class="underline">domaine</span></a> et de leur <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#portee"><span class="underline">portée</span></a>. Ceux-ci peuvent être l’une ou une combinaison des options suivantes : </p>
<p></p>
<ul><li><p>la propriété est nécessaire pour le domaine;</p>
</li>
<li><p>la propriété est nécessaire pour la portée ou, en d’autres termes, la portée dépend de la propriété.</p>
</li></ul>
<p></p>
<p>Les dépendants possibles sont définis dans le tableau ci-haut. Si une propriété n’est pas spécifiée pour une <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#instance"><span class="underline">instance</span></a> de son domaine ou de sa portée, il est entendu que la propriété existe, mais qu’une valeur associée à une part ou à l’autre de la propriété est inconnue. Dans le cas des propriétés optionnelles, la méthodologie proposée par le CIDOC CRM n’établit pas de distinction entre une valeur inconnue et une propriété qui ne serait pas du tout applicable. Par exemple, un objet peut avoir un•e propriétaire sans que l’identité de ce•tte propriétaire ne soit connue. Dans le cadre du CIDOC CRM, une telle situation ne peut être distinguée d’un cas où l’objet n’aurait aucun•e propriétaire. Bien entendu, de tels détails peuvent être indiqués à l’aide de notes textuelles. </p>
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
<p>Le terme « dépendant » a été préféré au terme « dépendance » en guise de traduction de « dependencies » puisqu’il transmet davantage le fait qu’il s’agit d’un élément qui s’inscrit dans la suite d’un autre (qui en dépend) plutôt qu’un élément qui a lui-même « besoin » d’un autre élément (qui est en situation de dépendance). </p>
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

<h2 id="convention-dappellation"><span class="en heading">Naming Conventions - </span>Convention d’appellation</h2>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>The following naming conventions have been applied throughout the CIDOC CRM:</p>
<p></p>
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
<ul><li><p>Temporal Entity and its subclasses</p>
</li>
<li><p>Thing and its subclasses</p>
</li>
<li><p>Actor and its subclasses</p>
</li>
<li><p>Other</p>
</li></ul>
</li></ul>
<p></p>
</td>
<td>
<p>La convention suivante a été appliquée à travers le CIDOC CRM : </p>
<p></p>
<ul><li><p>Les <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#classe"><span class="underline">classes</span></a> sont identifiées par des numéros précédés de la lettre majuscule « E » (historiquement, les classes de CIDOC CRM étaient parfois appelées des « entités ») et leurs appellations sont constituées de groupes nominaux, les initiales des noms sont en majuscules. Par exemple, <code class="language-plaintext highlighter-rouge">E63_Début_d'existence</code> [n.d.t. Dans la version francophone, les classes sont toujours conjuguées au féminin singulier, p. ex. « une <code class="language-plaintext highlighter-rouge">E63_Début_d'existence</code> »]. </p>
</li>
<li><p>Les <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#propriete"><span class="underline">propriétés</span></a> sont identifiées par des numéros précédés de la lettre majuscule « P » et leurs appellations sont bi-directionnelles et constituées de syntagmes verbaux dont tous les termes sont en minuscules. Les propriétés ayant les caractéristiques d’états utilisent le présent (p. ex. « a pout type »), alors que les propriétés liées à des évènements sont nommées au passé (p. ex. a été effectué par). Par exemple, <code class="language-plaintext highlighter-rouge">P126_a_employé (a_été_employé_dans)</code> [n.d.t. Dans la version francophone, les propriétés sont toujours conjuguées au féminin singulier, p. ex. « une <code class="language-plaintext highlighter-rouge">P126_a_employé (a_été_employé_dans)</code> »]. </p>
</li>
<li><p>Les noms des propriétés devraient être lus dans leur forme non parenthétique lors d’une lecture dirigée depuis le <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#domaine"><span class="underline">domaine</span></a> vers la <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#portee"><span class="underline">portée</span></a>, et dans leur forme parenthétique lors d’une lecture dirigée depuis la portée vers le domaine. Lire une propriété depuis la portée vers le domaine équivaut à l’inverse de cette propriété. En adéquation avec les pratiques de notation <a href="https://www.w3.org/OWL/"><span class="underline">OWL</span></a> actuelles, les <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#inverse-de"><span class="underline">propriétés inverses </span></a>sont identifiées par l’ajout d’un « i » minuscule à la suite du numéro d’identification et de la forme parenthétique complète de la propriété (p. ex. <code class="language-plaintext highlighter-rouge">P59i_se_situe_sur_ou_dans</code> est la propriété inverse de <code class="language-plaintext highlighter-rouge">P59_a_pour_section (se_situe_sur_ou_dans)</code>). </p>
</li>
<li><p>Les propriétés dont la portée est une <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#sous-classe"><span class="underline">sous-classe</span></a> de <code class="language-plaintext highlighter-rouge">E59_Valeur_primitive</code> (p. ex. <code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code>. <code class="language-plaintext highlighter-rouge">P3_a_pour_note</code> : <code class="language-plaintext highlighter-rouge">E62_Chaîne_de_caractères</code>) n’ont pas de forme appellative parenthétique, car la lecture depuis la portée vers le domaine n’est pas porteuse de sens. </p>
</li>
<li><p>Les propriétés qui ont des domaine et portée identiques sont soit <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#symetrie"><span class="underline">symétriques</span></a>, soit <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#transitivite"><span class="underline">transitives</span></a>. Instancier une propriété symétrique implique que la même relation est applicable lors de la lecture depuis le domaine vers la portée et depuis la portée vers le domaine (p. ex. <code class="language-plaintext highlighter-rouge">E53_Lieu</code>. <code class="language-plaintext highlighter-rouge">P122_est_limitrophe_de</code> : <code class="language-plaintext highlighter-rouge">E53_Lieu</code>). Les formes appellatives de propriétés symétriques n’ont pas de forme parenthétique, car la lecture depuis la portée vers le domaine équivaut à la lecture depuis le domaine vers la portée. Les propriétés transitives asymétriques (p. ex. <code class="language-plaintext highlighter-rouge">E4_Période</code>. <code class="language-plaintext highlighter-rouge">P9_comprend (fait_partie_de)</code> : <code class="language-plaintext highlighter-rouge">E4_Période</code>) ont une forme parenthétique qui porte sur la signification de leur direction inverse. </p>
</li>
<li><p>Le choix du domaine des propriétés, et donc de l’ordre de leur appellation, est établi selon les priorités suivantes : </p>

<li><p>Entités temporelles (<code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code> et ses sous-classes)</p>
<ul>
<li><p>Choses (<code class="language-plaintext highlighter-rouge">E70_Chose</code> et ses sous-classes)</p>
</li>
<li><p>Acteurs (<code class="language-plaintext highlighter-rouge">E39_Actant</code> et ses sous-classes)</p>
</li>
<li><p>Autres</p>
</li></ul>
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
<p>Le terme « naming convention » est parfois traduit par « convention d’appellation » ou « convention de nommage”; le terme « convention d’appellation » a été privilégié, car il semble davantage utilisé de manière générale (après avoir fait une brève recherche en ligne) et est entériné par Termium. </p>
<p></p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="1">
<p>OWL Working Group. 2012. « OWL - Semantic Web Standards ». W3C. 11 décembre 2012.<a href="https://www.w3.org/OWL/"><span class="underline"> </span></a><a href="https://www.w3.org/OWL/"><span class="underline">https://www.w3.org/OWL/</span></a>.</p>
<p>Termium. 2009. « Convention Appellation Courriels ». Termium Plus. 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-eng.html?lang=eng&i=1&index=frt&srchtxt=CONVENTION%20APPELLATION%20COURRIELS"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-eng.html?lang=eng&i=1&index=frt&srchtxt=CONVENTION%20APPELLATION%20COURRIELS"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-eng.html?lang=eng&i=1&index=frt&srchtxt=CONVENTION%20APPELLATION%20COURRIELS</span></a>.</p>
<p></p>
</td>
</tr>
</tbody>
</table>

<h2 id="des-expressions-logiques-utilisees-dans-le-cidoc-crm"><span class="en heading">About the logical expressions used in the CIDOC CRM - </span>Des expressions logiques utilisées dans le CIDOC CRM</h2>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>The present CIDOC CRM specifications are annotated with logical axioms, providing an additional formal expression of the CIDOC CRM ontology. This section briefly introduces the assumptions that are at the basis of the logical expression of the CIDOC CRM (for a fully detailed account of the logical expression of semantic data modelling, see (Reiter,1984)).</p>
<p></p>
<p>The CIDOC CRM is expressed in terms of the primitives of semantic data modelling. As such, it consists of:</p>
<p></p>
<ul><li><p><em>classes,</em> which represent general notions in the domain of discourse, such as the CIDOC CRM class E21 Person which represents the notion of person;</p>
</li>
<li><p><em>properties,</em> which represent the binary relations that link the individuals in the domain of discourse, such as the CIDOC CRM property <em>P152 has parent </em>linking a person to one of the person’s parent.</p>
</li></ul>
<p></p>
<p>Classes and properties are used to express ontological knowledge by means of various kinds of constraints, such as sub-class/sub-property links, e.g., E21 Person<em> </em>is a sub-class of<em> </em>E20 Biological Object, or domain/range constraints, e.g., the domain of <em>P152 has parent</em> is class E21 Person<em>.</em></p>
<p></p>
<p>In contrast, first-order logic-based knowledge representation relies on a language for formally encoding an ontology. This language can be directly put in correspondence with semantic data modelling in a straightforward way:</p>
<p></p>
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
<p></p>
<p>Le CIDOC CRM est exprimé par les <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#primitive"><span class="underline">concepts primitifs</span></a> [n.d.t. concept ou sens qui ne peut être défini sans créer de cercle vicieux en raison de son extrême simplicité] de la modélisation sémantique de données, à savoir : </p>
<p></p>
<ul><li><p>les <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#classe"><span class="underline"><em>classes</em></span></a> qui représentent les principales notions du domaine du discours comme la classe CIDOC CRM <code class="language-plaintext highlighter-rouge">E21_Personne</code> qui représente la notion de « personne”; </p>
</li>
<li><p>les <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#propriete"><span class="underline"><em>propriétés</em></span></a> qui représentent les relations binaires liant des individus dans le domaine du discours comme la propriété <code class="language-plaintext highlighter-rouge">P152_a_pour_parent</code> qui lie une personne à l’un de ses parents. </p>
</li></ul>
<p></p>
<p><a name="2z0rjs1wt90d"></a>Les classes et propriétés sont utilisées pour exprimer des connaissances ontologiques par le biais de contraintes telles que des liens de <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#sous-classe"><span class="underline">sous-classe</span></a>/<a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#sous-propriete"><span class="underline">sous-propriété</span></a> (p. ex. <code class="language-plaintext highlighter-rouge">E21_Personne</code> est une sous-classe de <code class="language-plaintext highlighter-rouge">E20_Objet_biologique</code>) ou des contraintes de <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#domaine"><span class="underline">domaine</span></a>/<a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#portee"><span class="underline">portée</span></a> (p. ex. le domaine de  <code class="language-plaintext highlighter-rouge">P152_a_pour_parent</code> est la classe <code class="language-plaintext highlighter-rouge">E21_Personne</code>). </p>
<p></p>
<p>Au contraire, la représentation de connaissances sous forme de logique du premier ordre repose sur un langage permettant d’encoder de manière formelle une ontologie. Ce langage peut être mis en correspondance directe avec la modélisation sémantique de données : </p>
<p></p>
<ul><li><p>les classes sont nommées par des <em>symboles de prédicats unaires</em>; par convention, « E21 » est le symbole de prédicat unaire correspondant à la classe <code class="language-plaintext highlighter-rouge">E21_Personne</code>;</p>
</li>
<li><p>les propriétés sont nommées par des <em>symboles de prédicats binaires</em>; par convention, « P152 » est le symbole de prédicat binaire correspondant à la propriété <code class="language-plaintext highlighter-rouge">P152_a_pour_parent</code>;</p>
</li>
<li><p>les propriétés de propriétés « propriétés .1 » sont nommées par des symboles de prédicats ternaires; par convention « P14.1 » est le symbole de prédicat ternaire correspondant à la propriété <code class="language-plaintext highlighter-rouge">P14.1_dans_le_rôle_de</code>.</p>
</li></ul>
<p></p>
<p>L’ontologie est exprimée logiquement par le biais d’axiomes qui correspondent aux contraintes de la modélisation sémantique. Dans la définition des classes et propriétés de CIDOC CRM, les axiomes sont énoncés dans la section « Logique ». Plusieurs options sont possibles lorsque vient le temps de rédiger des énoncés sous une forme de logique du premier ordre; ce document privilégie une notation compacte standard utilisée dans plusieurs ouvrages et articles scientifiques. Les définitions [n.d.t. pertinentes] sont présentées dans le tableau ci-dessous. </p>
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
<p>Le terme « assomption » est peu courant, mais est préféré dans un contexte logique ou mathématique, raison pour laquelle il a été utilisé plutôt que « supposition » ou « hypothèse”. </p>
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

<table>
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
<td colspan="4" class="en">
<p><em>Operators</em></p>
</td>
<td colspan="4">
<p><em>Opérateurs</em></p>
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
<p>→</p>
</td>
<td class="en">
<p>implication</p>
</td>
<td class="en">
<p>implies,</p>
<p>if … then ..</p>
</td>
<td class="en">
<p>(φ ⇒ ψ) is true </p>
<p>if and only if it is not the case that <em>φ</em> is true and <em>ψ</em> is false</p>
</td>
<td>
<p>→</p>
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
<p>↔</p>
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
<p>↔</p>
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
<p></p>
</td>
<td class="en">
<p></p>
</td>
<td class="en">
<p></p>
</td>
<td>
<p><a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#quantificateurs-de-propriete"><span class="underline"><em>Quantificateurs</em></span></a><em></em></p>
</td>
<td>
<p></p>
</td>
<td>
<p></p>
</td>
<td>
<p></p>
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
<p></p>
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
<p></p>
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
<p></p>
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
<p></p>
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
<p></p>
<p>(∀x) [E21(x) ⇒E20(x)]</p>
<p></p>
<p>(reading: for all individuals x, if x is a E21 then x is an E20). </p>
<p></p>
<p>In the definitions of classes and properties in this document the universal quantifier(s) are omitted for simplicity, so the above axiom is simply written:</p>
<p></p>
<p>E21(x) ⇒E20(x)</p>
<p></p>
<p>Likewise, the above domain constraint on property <em>P152 has parent </em>can be formulated in first order logic as the axiom:</p>
<p></p>
<p>P152(x,y) ⇒E21(x)</p>
<p></p>
<p>(reading: for all individuals x and y, if x is a P152 of y, then x is an E21).</p>
<p></p>
<p>These basic considerations should be used by the reader to understand the logical axioms that are used into the definition of the classes and properties. Further information about the first order formulation of CIDOC CRM can be found in (Meghini & Doerr, 2018).</p>
</td>
<td>
<p>Le lien de sous-classe <a href="#2z0rjs1wt90d"><span class="underline">susmentionné</span></a> entre <code class="language-plaintext highlighter-rouge">E21_Personne</code> et <code class="language-plaintext highlighter-rouge">E20_Objet_biologique</code> peut être formulé, en logique du premier ordre, par l’axiome suivant : </p>
<p></p>
<p>(∀x) [E21(x) ⇒E20(x)]</p>
<p></p>
<p>(à savoir : pour tout individu x, si x est un E21 alors x est un E20). </p>
<p></p>
<p>Dans la définition des <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#classe"><span class="underline">classes</span></a> et <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#propriete"><span class="underline">propriétés</span></a> de ce document le(s) <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#quantificateurs-de-propriete"><span class="underline">quantificateur</span></a>(s) universel(s) sont omis par soucis de simplicité, de sorte que cet axiome prend la forme suivante :</p>
<p></p>
<p>E21(x) ⇒E20(x)</p>
<p></p>
<p>De la même manière, la contrainte du <a href="/cidoc_crm_fr-ca/v7.1/information/terminologie#domaine"><span class="underline">domaine</span></a> de la propriété <code class="language-plaintext highlighter-rouge">P152_a_pour_parent</code> peut être formulée, en logique du premier ordre, par l’axiome suivant : </p>
<p></p>
<p>P152(x,y) ⇒E21(x)</p>
<p></p>
<p>(à savoir : pour tous les individus x et y, si x est un P152 de y, alors x est un E21).</p>
<p></p>
<p>Ceci devrait être utilisé par le lecteur afin de comprendre les axiomes utilisés dans la définition des classes et des propriétés. (Meghini & Doerr, 2018) offrent plus d’informations sur la formulation de logique du premier ordre dans le CIDOC CRM. </p>
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
<p>Les termes « quantifiant » ou « quantificateur » peuvent tous deux être utilisés pour désigner des « quantifiers”, la seconde option a été privilégiée pour éviter toute confusion avec le gérondif. </p>
<p></p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="1">
<p>Gouvernement du Canada, Travaux publics et Services gouvernementaux Canada. 2009. « quantifier ». Termium Plus. 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=quantifier&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=quantifier&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=quantifier&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
<p></p>
</td>
</tr>
</tbody>
</table>

