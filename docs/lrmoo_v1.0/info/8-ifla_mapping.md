---
layout: page
title: 8. Mise en correspondance du IFLA LRM au LRMoo
titleEn: 8. IFLA LRM to LRMoo mapping - 8. Mise en correspondance du IFLA LRM au LRMoo
permalink: /lrmoo/v1.0/mise-en-correspondance-du-iflalrm-au-lrmoo
sidebar: lrmoo_v10
date: 2026-02-09
---

**Date de création** : 2026-02-09

**Dernière mise à jour** : 2026-02-09

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
<p>The mapping is divided into three sections, respectively the IFLA LRM entities, attributes, and relationships. Each IFLA LRM element is identified by its LRM ID and name, and the definitions are given. However, for the IFLA LRM scope notes, consult the IFLA LRM model definition.</p>
<p>The mappings preferentially use LRM<sub>OO</sub> constructs, else the most specific CIDOC CRM construct that corresponds. The intention is for it to be feasible to implement these mappings using only LRM<sub>OO</sub> and the subset of CIDOC CRM indicated in sections 5.3 and 5.7. Thus, the mappings do not use any classes or properties from any other CRM family model. In particular, the classes and properties to be transferred to CRMsoc and listed in section 9 are not used. In the cases where the FRAD mapping found in FRBR<sub>OO</sub> version 2.4 used these classes, this mapping uses their CIDOC CRM superclasses.</p>
<p>The mappings from LRM<sub>OO</sub> or CIDOC CRM provided for the IFLA LRM entities are strictly equivalent. Most of the mappings for IFLA LRM attributes and relationships are also equivalent. However, in some cases, the granularity of the models differ and more than one mapping in CIDOC CRM applies, depending on the situation covered by the IFLA LRM definition. For these broader IFLA LRM attributes or relationships, more than one mapping is given, and the condition governing the choice is briefly described in the column preceding the mapping.</p>
<p>IFLA LRM entities are always mapped to classes, either in LRM<sub>OO</sub> or in CIDOC CRM. IFLA LRM attributes are always mapped to a property. This property is presented with a domain corresponding to the IFLA LRM entity that the attribute is the attribute of. The IFLA LRM entity may be a subclass of the actual domain of the property. The mapping is given as a path and the property label is given only in the direction that corresponds with its use. IFLA LRM relationships are also mapped to a property or a path, presented in the direction that corresponds to the IFLA LRM domain-to-range.</p>
<p><strong>Multiple instantiation in the mapping:</strong> In some cases the domain must be multiply instantiated as a specific CRM class for the relevant property to be valid. For example, <em>P72 has language</em> requires a domain of E33 Linguistic Object. To indicate the language attribute of an F2 Expression, that instance of expression must also be an instance of E33 Linguistic Object for it to be valid as the domain of <em>P72 has language</em> and be connected to an instance of E56 Language. This multiple instantiation requirement is given in parentheses after the class.</p>
<p><strong>Mappings to range E55 Type</strong>:</p>
<ul><li><p>If the values of E55 Type concerned are to come from a particular kind of categorization, that categorization is indicated in curly brackets.</p>
<p>For example, LRM-E1-A1 Res-Category: the E55 Type is to be drawn from a categorization of types of Res. This is notated: E55 Type {Res:Category}.</p></li>
<li><p>If a specific value of E55 Type is intended, this is indicated with an equals sign and a string in quotes.</p>
<p>For example, in mappings for creation relationships where the property P14 <em>carried out by</em> is used to link the creation event to an instance of E39 Actor responsible for the creation, the statement {P14.1 in the role of: E55 Type = “creator”} is used to state that the agent’s role must have been assigned the value “creator”. This side-branch of the path is all enclosed in curly brackets.</p></li>
</ul>
<p><strong>Notes on specific mappings</strong></p>
<p><em>Extent</em>: A complete mapping for each dimension being recorded must specify three things:</p>
<ul><li><p>The specific dimension being recorded, a value of E54 Dimension, e.g. height</p>
</li>
<li><p>The numeric value found for that dimension, a value of E60 Number connected to E54 Dimension via <em>P90 has value</em>, e.g. 28</p>
</li>
<li><p>The type of units that are being applied to the measurement to determine the numeric value, a value of E58 Measurement Unit connected to E54 Dimension via <em>P91 has unit</em>, e.g. cm</p>
</li>
<li><p>That both <em>P90 has value</em> and <em>P91 has unit</em> must be present and that the same instance of E54 Dimension is the domain of both properties, is indicated by “<em>and”</em> in the mapping.</p>
</li></ul>
<p><em>Association relationships</em>: The general association relationships LRM-R1, LRM-R33, and LRM-R35, involving LRM-E1 Res, are so broad that they are broader than any CRM properties. Thus they are not mapped. The intention in LRM<sub>OO</sub> is that more specific refinements of these relationships would be implemented.</p>
</td>
<td>
<p>La mise en correspondance est divisée en trois sections en fonction des éléments du <em>Modèle conceptuel pour l’information bibliographique</em> de la Fédération internationale des associations et institutions de bibliothèques (IFLA LRM) : entités, attributs, relations. Chaque élément est identifié par son identifiant du LRM (LRM ID) et par son nom qui précèdent sa définition. Par contre, les notes d’application de ceux-ci ne sont pas reproduites ici ; elles peuvent être consultées dans la définition du modèle <a href="https://repository.ifla.org/rest/api/core/bitstreams/b395a0a0-c9b8-49c6-8919-9befda0c40ed/content"><span class="underline">IFLA LRM</span></a>. </p>
<p>La mise en correspondance privilégie les construits du <em>Modèle conceptuel pour l’information bibliographique, orientation objet</em> (LRM<sub>OO</sub>), mais utilise les construits correspondants du <em>Modèle conceptuel de référence du Comité international pour la documentation du Conseil international des musées</em> (CIDOC CRM) lorsque c’est nécessaire. L’objectif du LRM<sub>OO</sub> est de permettre l’implémentation de ces mises en correspondances en n’utilisant que les classes et propriétés du LRM<sub>OO</sub> de pair avec le sous-ensemble d’entités du CIDOC CRM détaillé dans les sections 5.3 « <a href="https://cidoc-crm-fr.info/lrmoo/v1.0/hierarchie-de-classes-et-de-proprietes#liste-de-classes-du-cidoccrm-utilisees-dans-le-lrmoo"><span class="underline">Liste des classes du CIDOC CRM utilisées dans le LRM</span></a><a href="https://cidoc-crm-fr.info/lrmoo/v1.0/hierarchie-de-classes-et-de-proprietes#liste-de-classes-du-cidoccrm-utilisees-dans-le-lrmoo"><span class="underline">OO</span></a> » et 5.7 « <a href="https://cidoc-crm-fr.info/lrmoo/v1.0/hierarchie-de-classes-et-de-proprietes#liste-de-proprietes-du-cidoccrm-utilisees-dans-le-lrmoo"><span class="underline">Liste des propriétés du CIDOC CRM utilisées dans le LRM</span></a><a href="https://cidoc-crm-fr.info/lrmoo/v1.0/hierarchie-de-classes-et-de-proprietes#liste-de-proprietes-du-cidoccrm-utilisees-dans-le-lrmoo"><span class="underline">OO</span></a> ». Ainsi, les mises en correspondance n’utilisent pas de classes ou de propriétés tirées d’autres modèles. Plus particulièrement, les classes et propriétés devant être transférées au <em>Modèle conceptuel de référence pour les phénomènes sociaux</em> (CRM<sub>SOC</sub>) et énumérées dans la section 9 « <a href="https://cidoc-crm-fr.info/lrmoo/v1.0/classes-et-proprietes-frbroo-transferees-au-crmsoc"><span class="underline">Classes et propriétés du FRBR</span></a><a href="https://cidoc-crm-fr.info/lrmoo/v1.0/classes-et-proprietes-frbroo-transferees-au-crmsoc"><span class="underline">OO</span></a><a href="https://cidoc-crm-fr.info/lrmoo/v1.0/classes-et-proprietes-frbroo-transferees-au-crmsoc"><span class="underline"> transférées à CRM</span></a><a href="https://cidoc-crm-fr.info/lrmoo/v1.0/classes-et-proprietes-frbroo-transferees-au-crmsoc"><span class="underline">SOC</span></a> » ne sont pas utilisées ici. Lorsque la mise en correspondance entre la version 2.4 des <a href="https://cidoc-crm.org/lrmoo/ModelVersion/frbroo-v.-2.4"><span class="underline"><em>Fonctionnalités requises des notices bibliographiques, orientation objet </em></span></a><a href="https://cidoc-crm.org/lrmoo/ModelVersion/frbroo-v.-2.4"><span class="underline">(FRBR</span></a><a href="https://cidoc-crm.org/lrmoo/ModelVersion/frbroo-v.-2.4"><span class="underline">OO</span></a><a href="https://cidoc-crm.org/lrmoo/ModelVersion/frbroo-v.-2.4"><span class="underline">)</span></a> et des <a href="https://www.ifla.org/wp-content/uploads/2019/05/assets/cataloguing/frad/frad_2009-fr.pdf"><span class="underline"><em>Fonctionnalités requises des données d’autorité</em></span></a><a href="https://www.ifla.org/wp-content/uploads/2019/05/assets/cataloguing/frad/frad_2009-fr.pdf"><span class="underline"> (FRAD</span></a>) repose sur ces classes, elle utilise plutôt leurs super-classes du CIDOC CRM. </p>
<p>Les mises en correspondance entre les entités du LRM<sub>OO</sub> ou du CIDOC CRM et celles du IFLA LRM constituent des équivalences directes et strictes. La plupart des mises en correspondance pour des attributs ou des relations du IFLA LRM le sont aussi. Par contre, dans certains cas, le niveau de granularité des modèles diffère de sorte que plus d’une mise en correspondance avec le CIDOC CRM est applicable en fonction de la situation à laquelle s’applique la définition du IFLA LRM. Dans le cas de ces attributs ou relations du IFLA LRM dont l’application est plus large, plusieurs mises en correspondance sont détaillées ainsi que la condition déterminante de leur applicabilité dans la colonne précédant la mise en correspondance. </p>
<p>Les entités IFLA LRM sont toujours mises en correspondance avec des classes du LRM<sub>OO</sub> ou du CIDOC CRM alors que les attributs, eux, sont toujours mis en correspondance avec des propriétés dont le domaine correspond aux entités IFLA LRM dont ils sont les attributs. Ces entités peuvent être des sous-classes du domaine réel de la propriété concernée. La mise en correspondance est présentée sous forme de chemin sémantique et l’étiquette de la propriété n’est présentée que dans la direction qui correspond à son usage. Les relations IFLA LRM sont aussi mises en correspondance avec une propriété ou un chemin sémantique présenté dans la direction domaine-portée correspondante du IFLA LRM. </p>
<p><strong>Instanciation multiple dans la mise en correspondance</strong></p>
<p>Il arrive parfois, pour que la propriété soit valide, que le domaine soit instancié avec plusieurs classes du CIDOC CRM (voir « <a href="https://cidoc-crm-fr.info/v7.1/information/terminologie#instanciation-multiple"><span class="underline">Instanciation multiple</span></a> » dans le CIDOC CRM). Par exemple, <code class="language-plaintext highlighter-rouge">P72_a_pour_langue (est_la_langue_de)</code> nécessite l’utilisation du domaine <code class="language-plaintext highlighter-rouge">E33_Objet_linguistique</code>. En effet, pour indiquer la langue d’une expression (<code class="language-plaintext highlighter-rouge">F2_Expression</code>) en tant qu’attribut de telle manière qu’elle soit valide à titre de domaine de <code class="language-plaintext highlighter-rouge">P72_a_pour_langue (est_la_langue_de)</code> – et pour la connecter à une instance de <code class="language-plaintext highlighter-rouge">E56_Langue</code> –, cette instance d’expression doit aussi être une instance de <code class="language-plaintext highlighter-rouge">E33_Objet_linguistique</code>. Dans de tels cas l’exigence d’une instanciation multiple est indiquée entre parenthèses après la classe concernée. </p>
<p><strong>Mise en correspondance dont la portée est </strong><code class="language-plaintext highlighter-rouge">E55_Type</code><strong></strong></p>
<ul><li><p>Lorsque les valeurs de <code class="language-plaintext highlighter-rouge">E55_Type</code>  émanent d’une catégorisation dont le type est spécifique, celui-ci est indiqué entre accolades. Par exemple, <code class="language-plaintext highlighter-rouge">LRM-E1-A1_Res-Catégorie</code> : <code class="language-plaintext highlighter-rouge">E55_Type</code>  doit extraire sa catégorisation du type « Res », ce qui est exprimé de la manière suivante : <code class="language-plaintext highlighter-rouge">E55_Type</code> {Res : Catégorie}. </p>
</li>
<li><p>Lorsqu’une valeur spécifique de <code class="language-plaintext highlighter-rouge">E55_Type</code>  est prévue, elle est indiquée par l’utilisation du signe « = » et par sa description entre guillemets dans une chaîne de caractères. Par exemple, dans les mises en correspondance des créations de relations où la propriété <code class="language-plaintext highlighter-rouge">P14_a_été_effectué_par (a_effectué)</code> est utilisée afin de lier la création d’un évènement à une instance de <code class="language-plaintext highlighter-rouge">E39_Actant</code> responsable de cette création, l’énoncé suivant est utilisé afin d’indiquer que le rôle de cet actant doit avoir pour valeur « créateur » : {<code class="language-plaintext highlighter-rouge">P14.1_dans_le_rôle_de</code> : <code class="language-plaintext highlighter-rouge">E55_Type</code>  = « créateur »}. Toute cette section du chemin sémantique se trouve entre accolades. </p>
</li></ul>
<p><strong>Notes sur des mises en correspondance spécifiques</strong></p>
<p><em>Mise en correspondance des aires</em></p>
<p>Une mise en correspondance complète de toutes les dimensions enregistrées doit spécifier trois choses : </p>
<ul><li><p>La dimension enregistrée, une valeur de <code class="language-plaintext highlighter-rouge">E54_Dimension</code> (p. ex. « hauteur ») ;</p>
</li>
<li><p>La valeur numérique pour cette dimension spécifique, une valeur de <code class="language-plaintext highlighter-rouge">E60_Nombre</code> liée à l’instance de dimension enregistrée (<code class="language-plaintext highlighter-rouge">E54_Dimension</code>) par la propriété <code class="language-plaintext highlighter-rouge">P90_a_pour_valeur</code> (p. ex. « 28 ») ; </p>
</li>
<li><p>Le type d’unité de mesure utilisé afin de déterminer la valeur numérique, une valeur de <code class="language-plaintext highlighter-rouge">E58_Unité_de_mesure</code> connectée à l’instance de dimension enregistrée (<code class="language-plaintext highlighter-rouge">E54_Dimension</code>) par la propriété <code class="language-plaintext highlighter-rouge">P91_a_pour_unité_de_mesure (est_l’unité_de_mesure_de)</code> (p. ex. « cm »). </p>
</li></ul>
<p>De plus, non seulement <code class="language-plaintext highlighter-rouge">P90_a_pour_valeur</code> et <code class="language-plaintext highlighter-rouge">P91_a_pour_unité_de_mesure (est_l’unité_de_mesure_de)</code> doivent être utilisées, mais elles doivent aussi mobiliser la même instance de <code class="language-plaintext highlighter-rouge">E54_Dimension</code> comme domaine, ce qui est signalé par l’utilisation du « et » dans la mise en correspondance. </p>
<p><em>Mise en correspondance des relations d’association</em> </p>
<p>Les relations d’association généralistes <code class="language-plaintext highlighter-rouge">LRM-R1_est_associée_à</code>, <code class="language-plaintext highlighter-rouge">LRM-R33_a_pour_lieu_associé (est_associé_à)</code> et <code class="language-plaintext highlighter-rouge">LRM-R35_a_pour_laps_de_temps_associé (est_associé_à)</code>, qui implique aussi <code class="language-plaintext highlighter-rouge">LRM-E1_Res</code>, ont un champ d’application qui dépasse celui de toutes les propriétés du CIDOC CRM. Elles ne sont donc pas mises en correspondance ici. Éventuellement, le LRM<sub>OO</sub> pourrait implémenter des précisions spécifiques de ces relations. </p>
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
<p>Riva, Pat, Patrick Le Bœuf, et Maja Žumer. 2021. <em>Un modèle conceptuel pour l’information bibliographique</em>. Traduit par Aude Le Moullec-Rieu, Françoise Leresche, Frédéric Puyrenier, et Mélanie Roche. Committee Publications. La Haye, NL: Fédération internationale des associations et institutions de bibliothèques (IFLA).<a href="https://repository.ifla.org/server/api/core/bitstreams/b395a0a0-c9b8-49c6-8919-9befda0c40ed/content"><span class="underline"> </span></a><a href="https://repository.ifla.org/server/api/core/bitstreams/b395a0a0-c9b8-49c6-8919-9befda0c40ed/content"><span class="underline">https://repository.ifla.org/server/api/core/bitstreams/b395a0a0-c9b8-49c6-8919-9befda0c40ed/content</span></a>.</p>
</td>
</tr>
</tbody>
</table>

<h2 id="entites-du-iflalrm"><span class="en heading">8.1. IFLA LRM Entities - </span>8.1. Entités du IFLA LRM</h2>

<table>
    <tbody>
        <tr>
            <th>
                <p class="en block">LRM ID</p>
                <p class="en block">~~~~~</p>
                <p>Identifiant LRM</p>
            </th>
            <th>
                <p class="en block">LRM Name</p>
                <p class="en block">~~~~~</p>
                <p>Nom LRM</p>
            </th>
            <th>
                <p class="en block">LRM Definition</p>
                <p class="en block">~~~~~</p>
                <p>Définition LRM</p>
            </th>
            <th>
                <p class="en block">Mapping</p>
                <p class="en block">~~~~~</p>
                <p>Mise en correspondance</p>
            </th>
        </tr>
        <tr>
            <td>
                <p>LRM-E1</p>
            </td>
            <td>
                <p class="en block">Res</p>
                <p class="en block">~~~~~</p>
                <p>Res</p>
            </td>
            <td>
                <p class="en block">Any entity in the universe of discourse</p>
                <p class="en block">~~~~~</p>
                <p>Toute entité présente dans l’univers du discours.</p>
            </td>
            <td>
                <p class="en block">E1 CRM Entity</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E2</p>
            </td>
            <td>
                <p class="en block">Work</p>
                <p class="en block">~~~~~</p>
                <p>Œuvre</p>
            </td>
            <td>
                <p class="en block">The intellectual or artistic content of a distinct creation</p>
                <p class="en block">~~~~~</p>
                <p>Le contenu intellectuel ou artistique d’une création distincte.</p>
            </td>
            <td>
                <p class="en block">F1 Work</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F1_Œuvre</code>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E3</p>
            </td>
            <td>
                <p class="en block">Expression</p>
                <p class="en block">~~~~~</p>
                <p>Expression</p>
            </td>
            <td>
                <p class="en block">A distinct combination of signs conveying intellectual or artistic </p>
                <p class="en block">content</p>
                <p class="en block">~~~~~</p>
                <p>Une combinaison particulière de signes qui véhicule un contenu intellectuel ou artistique.</p>
            </td>
            <td>
                <p class="en block">F2 Expression</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F2_Expression</code>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E4</p>
            </td>
            <td>
                <p class="en block">Manifestation</p>
                <p class="en block">~~~~~</p>
                <p>Manifestation</p>
            </td>
            <td>
                <p class="en block">A set of all carriers that are assumed to share the same characteristics as to intellectual or artistic content and aspects of physical form. That set is defined by both the overall content and the production plan for its carrier or carriers</p>
                <p class="en block">~~~~~</p>
                <p>L’ensemble de tous les supports qui sont présumés partager les mêmes caractéristiques relatives tant au contenu intellectuel ou artistique qu’aux aspects de présentation matérielle. Cet ensemble est défini à la fois par son contenu global et par le plan de production pour son (ou ses) support(s).</p>
            </td>
            <td>
                <p class="en block">F3 Manifestation</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F3_Manifestation</code>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E5</p>
            </td>
            <td>
                <p class="en block">Item</p>
                <p class="en block">~~~~~</p>
                <p>Item</p>
            </td>
            <td>
                <p class="en block">An object or objects carrying signs intended to convey intellectual or artistic content</p>
                <p class="en block">~~~~~</p>
                <p>Un ou plusieurs objets portant des signes chargés de véhiculer un contenu intellectuel ou artistique.</p>
            </td>
            <td>
                <p class="en block">F5 Item</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F5_Item</code>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E6</p>
            </td>
            <td>
                <p class="en block">Agent</p>
                <p class="en block">~~~~~</p>
                <p>Agent</p>
            </td>
            <td>
                <p class="en block">An entity capable of deliberate actions, of being granted rights, and of being held accountable for its actions</p>
                <p class="en block">~~~~~</p>
                <p>Une entité à même d’agir de son propre chef, de se voir accorder des droits et d’être tenue pour responsable de ses actions.</p>
            </td>
            <td>
                <p class="en block">E39 Actor</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">E39_Actant</code>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E7</p>
            </td>
            <td>
                <p class="en block">Person</p>
                <p class="en block">~~~~~</p>
                <p>Personne</p>
            </td>
            <td>
                <p class="en block">An individual human being</p>
                <p class="en block">~~~~~</p>
                <p>Un être humain en particulier.</p>
            </td>
            <td>
                <p class="en block">E21 Person</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">E21_Personne</code>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E8</p>
            </td>
            <td>
                <p class="en block">Collective Agent</p>
                <p class="en block">~~~~~</p>
                <p>Agent collectif</p>
            </td>
            <td>
                <p class="en block">A gathering or organization of persons bearing a particular name and capable of acting as a unit</p>
                <p class="en block">~~~~~</p>
                <p>Groupement ou association de personnes portant un nom particulier et disposant de la faculté d’agir collectivement.</p>
            </td>
            <td>
                <p class="en block">F55 Collective Agent</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F55_Agent_collectif</code>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E9</p>
            </td>
            <td>
                <p class="en block">Nomen</p>
                <p class="en block">~~~~~</p>
                <p>Nomen</p>
            </td>
            <td>
                <p class="en block">An association between an entity and a designation that refers to it</p>
                <p class="en block">~~~~~</p>
                <p>Une association entre une entité et une désignation qui y réfère.</p>
            </td>
            <td>
                <p class="en block">F12 Nomen</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F12_Nomen</code>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E10</p>
            </td>
            <td>
                <p class="en block">Place</p>
                <p class="en block">~~~~~</p>
                <p>Lieu</p>
            </td>
            <td>
                <p class="en block">A given extent of space</p>
                <p class="en block">~~~~~</p>
                <p>Une étendue spatiale donnée.</p>
            </td>
            <td>
                <p class="en block">E53 Place</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">E53_Lieu</code>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E11</p>
            </td>
            <td>
                <p class="en block">Time-span</p>
                <p class="en block">~~~~~</p>
                <p>Laps de temps</p>
            </td>
            <td>
                <p class="en block">A temporal extent having a beginning, an end and a duration</p>
                <p class="en block">~~~~~</p>
                <p>Plage temporelle ayant un début, une fin et une durée.</p>
            </td>
            <td>
                <p class="en block">E52 Time-span</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">E52_Intervalle_temporel</code>
                </p>
            </td>
        </tr>
        <tr>
            <th>
                <p>
                    <em>Note de traduction</em>
                </p>
            </th>
            <td colspan="2">
                <p>Le texte de ce tableau est issu de la traduction en français du 
                    <em>Modèle conceptuel pour l’information bibliographique</em>
                    de la Fédération internationale des associations et institutions de bibliothèques (IFLA LRM).</p>
            </td>
        </tr>
        <tr>
            <th>
                <p>
                    <em>Références</em>
                </p>
            </th>
            <td colspan="2">
                <p>Riva, Pat, Patrick Le Bœuf, et Maja Žumer. 2021. 
                    <em>Un modèle conceptuel pour l’information bibliographique</em>
                    . Traduit par Aude Le Moullec-Rieu, Françoise Leresche, Frédéric Puyrenier, et Mélanie Roche. Committee Publications. La Haye, NL: Fédération internationale des associations et institutions de bibliothèques (IFLA).
                    <a href="https://repository.ifla.org/server/api/core/bitstreams/b395a0a0-c9b8-49c6-8919-9befda0c40ed/content">
                        <span class="underline"/></a>
                    <a href="https://repository.ifla.org/server/api/core/bitstreams/b395a0a0-c9b8-49c6-8919-9befda0c40ed/content">
                        <span class="underline">https://repository.ifla.org/server/api/core/bitstreams/b395a0a0-c9b8-49c6-8919-9befda0c40ed/content</span>
                    </a>.</p>
            </td>
        </tr>
    </tbody>
</table>

<h2 id="attributs-du-iflalrm"><span class="en heading">8.2. IFLA LRM Attributes - </span>8.2. Attributs du IFLA LRM</h2>

<table>
    <tbody>
        <tr>
            <th>
                <p class="en block">LRM ID</p>
                <p class="en block">~~~~~</p>
                <p>Identifiant LRM</p>
            </th>
            <th>
                <p class="en block">LRM Entity</p>
                <p class="en block">~~~~~</p>
                <p>Entité LRM</p>
            </th>
            <th>
                <p class="en block">LRM Name</p>
                <p class="en block">~~~~~</p>
                <p>Nom LRM</p>
            </th>
            <th>
                <p class="en block">LRM Definition</p>
                <p class="en block">~~~~~</p>
                <p>Définition LRM</p>
            </th>
            <th>
                <p class="en block">Condition</p>
                <p class="en block">~~~~~</p>
                <p>Condition</p>
            </th>
            <th>
                <p class="en block">Mapping</p>
                <p class="en block">~~~~~</p>
                <p>Mise en correspondance   
                </p>
            </th>
        </tr>
        <tr>
            <td>
                <p>LRM-E1-A1</p>
            </td>
            <td>
                <p class="en block">Res</p>
                <p class="en block">~~~~~</p>
                <p>Res</p>
            </td>
            <td>
                <p class="en block">Category</p>
                <p class="en block">~~~~~</p>
                <p>Catégorie</p>
            </td>
            <td>
                <p class="en block">A type to which the <em>res</em> belongs</p>
                <p class="en block">~~~~~</p>
                <p>Un type auquel l’instance de 
                    <code class="language-plaintext highlighter-rouge">LRM-E1_Res</code>
                    <em/> appartient.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">E1 CRM Entity. P2 has type: E55 Type {Res:Category}</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code>. 
                    <code class="language-plaintext highlighter-rouge">P2_a_pour_type</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E55_Type</code> {Res : Catégorie}</p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E1-A2</p>
            </td>
            <td>
                <p class="en block">Res</p>
                <p class="en block">~~~~~</p>
                <p>Res</p>
            </td>
            <td>
                <p class="en block">Note</p>
                <p class="en block">~~~~~</p>
                <p>Note</p>
            </td>
            <td>
                <p class="en block">Any kind of information about a <em>res</em> that is not recorded through the use of specific attributes and/or relationships</p>
                <p class="en block">~~~~~</p>
                <p>Information de toute nature sur une instance de 
                    <code class="language-plaintext highlighter-rouge">LRM-E1_Res</code> qui n’est pas enregistrée grâce à l’utilisation d’attributs et/ou de relations spécifiques.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">E1 CRM Entity. P3 has note: E62 String</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code>. 
                    <code class="language-plaintext highlighter-rouge">P3_a_pour_note</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E62_Chaîne_de_caractères</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E2-A1</p>
            </td>
            <td>
                <p class="en block">Work</p>
                <p class="en block">~~~~~</p>
                <p>Œuvre</p>
            </td>
            <td>
                <p class="en block">Category</p>
                <p class="en block">~~~~~</p>
                <p>Catégorie</p>
            </td>
            <td>
                <p class="en block">A type to which the <em>work</em> belongs</p>
                <p class="en block">~~~~~</p>
                <p>Un type auquel l’
                    <code class="language-plaintext highlighter-rouge">LRM-E2_Œuvre</code> appartient.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F1 Work. P2 has type: E55 Type {Work:Category}</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F1_Œuvre</code>. 
                    <code class="language-plaintext highlighter-rouge">P2_a_pour_type</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E55_Type</code> {Res : Catégorie}</p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E2-A2</p>
            </td>
            <td>
                <p class="en block">Work</p>
                <p class="en block">~~~~~</p>
                <p>Œuvre</p>
            </td>
            <td>
                <p class="en block">Representative expression attribute</p>
                <p class="en block">~~~~~</p>
                <p>Attributs d’expression représentative</p>
            </td>
            <td>
                <p class="en block">An attribute which is deemed essential in characterizing the <em>work</em>
                    and whose values are taken from a representative or canonical <em>expression</em>
                    of the <em>work</em></p>
                <p class="en block">~~~~~</p>
                <p>Un attribut qui est considéré comme essentiel pour caractériser l’œuvre et dont les valeurs sont reprises d’une expression représentative ou canonique de l’
                    <code class="language-plaintext highlighter-rouge">LRM-E2_Œuvre</code> .</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F1 Work. R79 has representative expression attribute: E55 Type</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F1_Œuvre</code>. 
                    <code class="language-plaintext highlighter-rouge">R79_a_l’attribut_d’expression_représentatif</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E55_Type</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E3-A1</p>
            </td>
            <td>
                <p class="en block">Expression</p>
                <p class="en block">~~~~~</p>
                <p>Expression</p>
            </td>
            <td>
                <p class="en block">Category</p>
                <p class="en block">~~~~~</p>
                <p>Catégorie</p>
            </td>
            <td>
                <p class="en block">A type to which the <em>expression</em> belongs</p>
                <p class="en block">~~~~~</p>
                <p>Un type auquel l’
                    <code class="language-plaintext highlighter-rouge">LRM-E3_Expression</code> appartient.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F2 Expression. P2 has type: E55 Type {Expression:Category}</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F2_Expression</code>. 
                    <code class="language-plaintext highlighter-rouge">P2_a_pour_type</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E55_Type</code> {Expression : Catégorie}</p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E3-A2</p>
            </td>
            <td>
                <p class="en block">Expression</p>
                <p class="en block">~~~~~</p>
                <p>Expression</p>
            </td>
            <td>
                <p class="en block">Extent</p>
                <p class="en block">~~~~~</p>
                <p>Taille</p>
            </td>
            <td>
                <p class="en block">A quantification of the extent of the <em>expression</em></p>
                <p class="en block">~~~~~</p>
                <p>Une quantification de la taille de l’
                    <code class="language-plaintext highlighter-rouge">LRM-E3_Expression</code> .</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F2 Expression. P43 has dimension: E54 Dimension. P90 has value: E60 Number, a<em>nd </em> P91 has unit: E58 Measurement Unit</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F2_Expression</code>. 
                    <code class="language-plaintext highlighter-rouge">P43_a_pour_dimension</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E54_Dimension</code>
                    . 
                    <code class="language-plaintext highlighter-rouge">P90_a_pour_valeur</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E60_Nombre</code>
                    et 
                    <code class="language-plaintext highlighter-rouge">P91_a_pour_unité_de_mesure</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E58_Unité_de_mesure</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E3-A3</p>
            </td>
            <td>
                <p class="en block">Expression</p>
                <p class="en block">~~~~~</p>
                <p>Expression</p>
            </td>
            <td>
                <p class="en block">Intended audience</p>
                <p class="en block">~~~~~</p>
                <p>Public destinataire</p>
            </td>
            <td>
                <p class="en block">A class of users for which the <em>expression</em> is intended</p>
                <p class="en block">~~~~~</p>
                <p>Une catégorie d’utilisateurs à laquelle l’
                    <code class="language-plaintext highlighter-rouge">LRM-E3_Expression</code> est destinée.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F2 Expression. P103 was intended for: E55 Type {Personal characteristic}</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F2_Expression</code>. 
                    <code class="language-plaintext highlighter-rouge">P103_a_eu_pour_raison_d’être</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E55_Type</code> {Caractéristique personnelle}</p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E3-A4</p>
            </td>
            <td>
                <p class="en block">Expression</p>
                <p class="en block">~~~~~</p>
                <p>Expression</p>
            </td>
            <td>
                <p class="en block">Use rights</p>
                <p class="en block">~~~~~</p>
                <p>Droits d’utilisation</p>
            </td>
            <td>
                <p class="en block">A class of use restrictions to which the <em>expression</em> is submitted</p>
                <p class="en block">~~~~~</p>
                <p>Une catégorie de restrictions d’utilisation auxquelles l’
                    <code class="language-plaintext highlighter-rouge">LRM-E3_Expression</code> est soumise.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F2 Expression. P104 is subject to: E30 Right</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F2_Expression</code>. 
                    <code class="language-plaintext highlighter-rouge">P104_est_soumis_à</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E30_Droit</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E3-A5</p>
            </td>
            <td>
                <p class="en block">Expression</p>
                <p class="en block">~~~~~</p>
                <p>Expression</p>
            </td>
            <td>
                <p class="en block">Cartographic scale</p>
                <p class="en block">~~~~~</p>
                <p>Échelle cartographique</p>
            </td>
            <td>
                <p class="en block">A ratio of distances in a cartographic <em>expression</em> to the actual distances they represent</p>
                <p class="en block">~~~~~</p>
                <p>Un rapport des distances mesurées sur l’
                    <code class="language-plaintext highlighter-rouge">LRM-E3_Expression</code> cartographique à leur valeur réelle sur le terrain.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F2 Expression (instantiated as E36 Visual Item. {P2 has type: E55 Type = “cartographic image”}). P2 has type: E55 Type {Cartographic scale}</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F2_Expression</code>(instanciée en tant que 
                    <code class="language-plaintext highlighter-rouge">E36_Entité_visuelle</code>
                    . {
                    <code class="language-plaintext highlighter-rouge">P2_a_pour_type</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E55_Type</code>
                     = « image cartographique »}). 
                    <code class="language-plaintext highlighter-rouge">P2_a_pour_type</code>
                      : 
                    <code class="language-plaintext highlighter-rouge">E55_Type</code>  {Échelle cartographique}</p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E3-A6</p>
            </td>
            <td>
                <p class="en block">Expression</p>
                <p class="en block">~~~~~</p>
                <p>Expression</p>
            </td>
            <td>
                <p class="en block">Language</p>
                <p class="en block">~~~~~</p>
                <p>Langue</p>
            </td>
            <td>
                <p class="en block">A language used in the <em>expression</em></p>
                <p class="en block">~~~~~</p>
                <p>Une langue utilisée dans l’
                    <code class="language-plaintext highlighter-rouge">LRM-E3_Expression</code> .</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F2 Expression (instantiated as E33 Linguistic Object). P72 has language: E56 Language</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F2_Expression</code>(instanciée en tant que 
                    <code class="language-plaintext highlighter-rouge">E33_Objet_linguistique</code>
                    ). 
                    <code class="language-plaintext highlighter-rouge">P72_a_pour_langue</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E56_Langue</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E3-A7</p>
            </td>
            <td>
                <p class="en block">Expression</p>
                <p class="en block">~~~~~</p>
                <p>Expression</p>
            </td>
            <td>
                <p class="en block">Key</p>
                <p class="en block">~~~~~</p>
                <p>Tonalité</p>
            </td>
            <td>
                <p class="en block">A pitch structure (musical scale, ecclesiastic mode, raga, maqam, etc.), that characterizes the <em>expression</em></p>
                <p class="en block">~~~~~</p>
                <p>Une échelle de hauteurs de son (gamme, mode ecclésiastique, raga, maqâm, etc.) qui caractérise une 
                    <code class="language-plaintext highlighter-rouge">LRM-E3_Expression</code> .</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F2 Expression. P2 has type: E55 Type {Key}</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F2_Expression</code>. 
                    <code class="language-plaintext highlighter-rouge">P2_a_pour_type</code>
                      : 
                    <code class="language-plaintext highlighter-rouge">E55_Type</code>  {Tonalité}</p>
            </td>
        </tr>
        <tr>
            <td rowspan="2">
                <p>LRM-E3-A8</p>
            </td>
            <td rowspan="2">
                <p class="en block">Expression</p>
                <p class="en block">~~~~~</p>
                <p>Expression</p>
            </td>
            <td rowspan="2">
                <p class="en block">Medium of performance</p>
                <p class="en block">~~~~~</p>
                <p>Distribution d’exécution</p>
            </td>
            <td rowspan="2">
                <p class="en block">A combination of performing tools (voices, instruments, ensembles, etc.) stated, intended, or actually used in the <em>expression</em></p>
                <p class="en block">~~~~~</p>
                <p>Une combinaison de moyens d’exécution (voix, instruments, ensembles, etc.) spécifiés, prévus, ou effectivement utilisés dans l’
                    <code class="language-plaintext highlighter-rouge">LRM-E3_Expression</code> .</p>
            </td>
            <td>
                <p class="en block">stated or intended medium</p>
                <p class="en block">~~~~~</p>
                <p>Moyen d’exécution spécifié ou prévu*</p>
            </td>
            <td>
                <p class="en block">F2 Expression. P103 was intended for: E55 Type {Medium of performance}</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F2_Expression</code>. 
                    <code class="language-plaintext highlighter-rouge">P103_a_eu_pour_raison_d’être</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E55_Type</code>  {Distribution d’exécution}</p>
            </td>
        </tr>
        <tr>
            <td>
                <p class="en block">actual medium</p>
                <p class="en block">~~~~~</p>
                <p>Moyen d’exécution effectivement utilisé*</p>
            </td>
            <td>
                <p class="en block">F2 Expression. R17i was created by: F28 Expression Creation. R81 recorded: F31 Performance. P125 used object of type: E55 Type {Medium of performance}</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F2_Expression</code>. 
                    <code class="language-plaintext highlighter-rouge">R17i_a_été_créé_par</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F28_Création_d’expression</code>
                    . 
                    <code class="language-plaintext highlighter-rouge">R81_enregistré</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F31_Performance</code>
                    . 
                    <code class="language-plaintext highlighter-rouge">P125_a_mobilisé_l'objet_du_type</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E55_Type</code>  {Distribution d’exécution}</p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E4-A1</p>
            </td>
            <td>
                <p class="en block">Manifestation</p>
                <p class="en block">~~~~~</p>
                <p>Manifestation</p>
            </td>
            <td>
                <p class="en block">Category of carrier</p>
                <p class="en block">~~~~~</p>
                <p>Catégorie de support*</p>
            </td>
            <td>
                <p class="en block">A type of material to which all physical carriers of the <em>manifestation</em> are assumed to belong</p>
                <p class="en block">~~~~~</p>
                <p>Une caractérisation matérielle que tous les supports physiques de la 
                    <code class="language-plaintext highlighter-rouge">LRM-E4_Manifestation</code> sont présumés présenter.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F3 Manifestation. R69 has physical form: E55 Type {Category of carrier}</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F3_Manifestation</code>. 
                    <code class="language-plaintext highlighter-rouge">R69_a_pour_forme_physique</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E55_Type</code>  {Catégorie de support}</p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E4-A2</p>
            </td>
            <td>
                <p class="en block">Manifestation</p>
                <p class="en block">~~~~~</p>
                <p>Manifestation</p>
            </td>
            <td>
                <p class="en block">Extent</p>
                <p class="en block">~~~~~</p>
                <p>Taille</p>
            </td>
            <td>
                <p class="en block">A quantification of the extent observed on a physical carrier of the <em>manifestation</em>
                    and assumed to be observable on all physical carriers of the <em>manifestation</em></p>
                <p class="en block">~~~~~</p>
                <p>Une quantification de l’importance matérielle observée sur un support physique de la 
                    <code class="language-plaintext highlighter-rouge">LRM-E4_Manifestation</code>
                    et réputée pouvoir être observée sur tous les supports physiques de la 
                    <code class="language-plaintext highlighter-rouge">LRM-E4_Manifestation</code> .</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F3 Manifestation. R70 has dimension: E54 Dimension. P90 has value: E60 Number, <em>and </em> P91 has unit: E58 Measurement Unit</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F3_Manifestation</code>. 
                    <code class="language-plaintext highlighter-rouge">R70_a_pour_dimension</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E54_Dimension</code>
                    . 
                    <code class="language-plaintext highlighter-rouge">P90_a_pour_valeur</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E60_Nombre</code>
                    , et 
                    <code class="language-plaintext highlighter-rouge">P91_a_pour_unité_de_mesure</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E58_Unité_de_mesure</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E4-A3</p>
            </td>
            <td>
                <p class="en block">Manifestation</p>
                <p class="en block">~~~~~</p>
                <p>Manifestation</p>
            </td>
            <td>
                <p class="en block">Intended audience</p>
                <p class="en block">~~~~~</p>
                <p>Public destinataire</p>
            </td>
            <td>
                <p class="en block">A class of users for which the physical carriers of the <em>manifestation</em> are intended</p>
                <p class="en block">~~~~~</p>
                <p>Une catégorie d’utilisateurs à laquelle les supports physiques de la 
                    <code class="language-plaintext highlighter-rouge">LRM-E4_Manifestation</code> sont destinés.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F3 Manifestation. P103 was intended for: E55 Type {Personal characteristic}</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F3_Manifestation</code>. 
                    <code class="language-plaintext highlighter-rouge">P103_a_eu_pour_raison_d’être</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E55_Type</code>  {Caractéristique personnelle}</p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E4-A4</p>
            </td>
            <td>
                <p class="en block">Manifestation</p>
                <p class="en block">~~~~~</p>
                <p>Manifestation</p>
            </td>
            <td>
                <p class="en block">Manifestation statement</p>
                <p class="en block">~~~~~</p>
                <p>Énoncé de manifestation*</p>
            </td>
            <td>
                <p class="en block">A statement appearing in exemplars of the <em>manifestation</em> and deemed to be significant for users to understand how the resource represents itself</p>
                <p class="en block">~~~~~</p>
                <p>Une mention figurant sur les exemplaires de la 
                    <code class="language-plaintext highlighter-rouge">LRM-E4_Manifestation</code> et jugée importante pour que les utilisateurs comprennent la façon dont la ressource se présente.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F3 Manifestation. P3 has note {P3.1 has type: E55 Type = “manifestation statement”}: E62 String</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F3_Manifestation</code>. 
                    <code class="language-plaintext highlighter-rouge">P3_a_pour_note</code>
                    {
                    <code class="language-plaintext highlighter-rouge">P3.1_a_pour_type</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E55_Type</code>
                     = « Énoncé de manifestation »} : 
                    <code class="language-plaintext highlighter-rouge">E62_Chaîne_de_caractères</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E4-A5</p>
            </td>
            <td>
                <p class="en block">Manifestation</p>
                <p class="en block">~~~~~</p>
                <p>Manifestation</p>
            </td>
            <td>
                <p class="en block">Access conditions</p>
                <p class="en block">~~~~~</p>
                <p>Conditions d’accès*</p>
            </td>
            <td>
                <p class="en block">Information as to how any of the carriers of the <em>manifestation</em> are likely to be obtained </p>
                <p class="en block">~~~~~</p>
                <p>Des informations concernant les modalités d’obtention possibles de tout support physique de la 
                    <code class="language-plaintext highlighter-rouge">LRM-E4_Manifestation</code> .</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F3 Manifestation. P3 has note {P3.1 has type: E55 Type = “access conditions”}: E62 String</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F3_Manifestation</code>. 
                    <code class="language-plaintext highlighter-rouge">P3_a_pour_note</code>
                    {
                    <code class="language-plaintext highlighter-rouge">P3.1_a_pour_type</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E55_Type</code>
                     = « Conditions d’accès »} : 
                    <code class="language-plaintext highlighter-rouge">E62_Chaîne_de_caractères</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E4-A6</p>
            </td>
            <td>
                <p class="en block">Manifestation</p>
                <p class="en block">~~~~~</p>
                <p>Manifestation</p>
            </td>
            <td>
                <p class="en block">Use rights</p>
                <p class="en block">~~~~~</p>
                <p>Droits d’utilisation</p>
            </td>
            <td>
                <p class="en block">A class of use and/or access restrictions to which all carriers of the <em>manifestation</em> are assumed to be submitted</p>
                <p class="en block">~~~~~</p>
                <p>Une catégorie de restrictions d’utilisation ou d’accès auxquelles tous les supports de la 
                    <code class="language-plaintext highlighter-rouge">LRM-E4_Manifestation</code> sont présumés être soumis.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F3 Manifestation. P104 is subject to: E30 Right</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F3_Manifestation</code>. 
                    <code class="language-plaintext highlighter-rouge">P104_est_soumis_à</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E30_Droit</code></p>
            </td>
        </tr>
        <tr>
            <td rowspan="4">
                <p>LRM-E5-A1</p>
            </td>
            <td rowspan="4">
                <p class="en block">Item</p>
                <p class="en block">~~~~~</p>
                <p>Item</p>
            </td>
            <td rowspan="4">
                <p class="en block">Location</p>
                <p class="en block">~~~~~</p>
                <p>Localisation</p>
            </td>
            <td rowspan="4">
                <p class="en block">The collection and/or institution in which the <em>item</em> is held, stored, or made available for access</p>
                <p class="en block">~~~~~</p>
                <p>Le fonds et/ou l’institution dans laquelle l’
                    <code class="language-plaintext highlighter-rouge">LRM-E5_Item</code> est conservé, stocké ou mis à disposition du public.</p>
            </td>
            <td>
                <p class="en block">normal shelf location</p>
                <p class="en block">~~~~~</p>
                <p>Localisation habituelle*</p>
            </td>
            <td>
                <p class="en block">F5 Item. P54 has current permanent location: E53 Place</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F5_Item</code>. 
                    <code class="language-plaintext highlighter-rouge">P54_a_actuellement_pour_localisation_fixe</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E53_Lieu</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p class="en block">current shelf location</p>
                <p class="en block">~~~~~</p>
                <p>Localisation actuelle*</p>
            </td>
            <td>
                <p class="en block">F5 Item. P55 has current location: E53 Place</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F5_Item</code>. 
                    <code class="language-plaintext highlighter-rouge">P55_a_actuellement_pour_localisation</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E53_Lieu</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p class="en block">collection</p>
                <p class="en block">~~~~~</p>
                <p>Collection*</p>
            </td>
            <td>
                <p class="en block">F5 Item. P46i forms part of: E78 Curated Holding. {P109 has current or former curator: E39 Actor}</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F5_Item</code>. 
                    <code class="language-plaintext highlighter-rouge">P46i_fait_partie_de</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E78_Collection</code>
                    {
                    <code class="language-plaintext highlighter-rouge">P109_a_pour_responsable_actuel_ou_antérieur_de_la_collection</code>
                     :
                    <code class="language-plaintext highlighter-rouge">E39_Actant</code> }</p>
            </td>
        </tr>
        <tr>
            <td>
                <p class="en block">institution</p>
                <p class="en block">~~~~~</p>
                <p>Institution*</p>
            </td>
            <td>
                <p class="en block">F5 Item. P50 has current keeper: E39 Actor</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F5_Item</code>. 
                    <code class="language-plaintext highlighter-rouge">P50_a_pour_actant_détenteur_actuel</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E39_Actant</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E5-A2</p>
            </td>
            <td>
                <p class="en block">Item</p>
                <p class="en block">~~~~~</p>
                <p>Item</p>
            </td>
            <td>
                <p class="en block">Use rights</p>
                <p class="en block">~~~~~</p>
                <p>~~~~</p>
                <p>Droits d’utilisation</p>
            </td>
            <td>
                <p class="en block">A class of use and/or access restrictions to which the <em>item</em> is submitted</p>
                <p class="en block">~~~~~</p>
                <p>Une catégorie de restrictions d’utilisation ou d’accès auxquelles l’
                    <code class="language-plaintext highlighter-rouge">LRM-E5_Item</code> est soumis.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F5 Item. P104 is subject to: E30 Right</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F5_Item</code>. 
                    <code class="language-plaintext highlighter-rouge">P104_est_soumis_à</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E30_Droit</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E6-A1</p>
            </td>
            <td>
                <p class="en block">Agent</p>
                <p class="en block">~~~~~</p>
                <p>Agent</p>
            </td>
            <td>
                <p class="en block">Contact information</p>
                <p class="en block">~~~~~</p>
                <p>Coordonnées</p>
            </td>
            <td>
                <p class="en block">Information useful for communicating with or getting in contact with the <em>agent</em></p>
                <p class="en block">~~~~~</p>
                <p>Des informations utiles pour contacter ou communiquer avec l’
                    <code class="language-plaintext highlighter-rouge">LRM-E6_Agent</code> .</p>
            </td>
            <td></td>
            <td>
                <p class="en block">E39 Actor. P76 has contact point: E41 Appellation. {P2 has type: E55 Type = “contact point”}</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">E39_Actant</code>. 
                    <code class="language-plaintext highlighter-rouge">P76_a_pour_coordonnées</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E41_Appellation</code>
                    {
                    <code class="language-plaintext highlighter-rouge">P2_a_pour_type</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E55_Type</code>  = « Coordonnées »}</p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E6-A2</p>
            </td>
            <td>
                <p class="en block">Agent</p>
                <p class="en block">~~~~~</p>
                <p>Agent</p>
            </td>
            <td>
                <p class="en block">Field of activity</p>
                <p class="en block">~~~~~</p>
                <p>Domaine d’activité</p>
            </td>
            <td>
                <p class="en block">A field of endeavour, area of expertise, etc., in which the <em>agent</em> is engaged or was engaged</p>
                <p class="en block">~~~~~</p>
                <p>Un champ d’action, domaine du savoir, etc., dans lequel l’
                    <code class="language-plaintext highlighter-rouge">LRM-E6_Agent</code> s’investit ou s’est investi.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">E39 Actor. P14i performed: E7 Activity.  P2 has type: E55 Type {Sphere of activity}</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">E39_Actant</code>. 
                    <code class="language-plaintext highlighter-rouge">P14i_a_effectué</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E7_Activité</code>
                    . 
                    <code class="language-plaintext highlighter-rouge">P2_a_pour_type</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E55_Type</code>  {« Domaine d’activité »}</p>
            </td>
        </tr>
        <tr>
            <td rowspan="2">
                <p>LRM-E6-A3</p>
            </td>
            <td rowspan="2">
                <p class="en block">Agent</p>
                <p class="en block">~~~~~</p>
                <p>Agent</p>
            </td>
            <td rowspan="2">
                <p class="en block">Language</p>
                <p class="en block">~~~~~</p>
                <p>Langue</p>
            </td>
            <td rowspan="2">
                <p class="en block">A language used by the <em>agent</em> when creating an expression</p>
                <p class="en block">~~~~~</p>
                <p>Une langue utilisée par l’
                    <code class="language-plaintext highlighter-rouge">LRM-E6_Agent</code> quand il crée une expression.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">E39 Actor. P14i performed {P14.1 in the role of: E55 Type = “creator”}: F28 Expression Creation. R17 created: F2 Expression (instantiated as E33 Linguistic Object). P72 has language: E56 Language</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">E39_Actant</code>. 
                    <code class="language-plaintext highlighter-rouge">P14i_a_effectué</code>
                     : {
                    <code class="language-plaintext highlighter-rouge">P14.1_dans_le_rôle_de</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E55_Type</code>
                     = « créateur »} : 
                    <code class="language-plaintext highlighter-rouge">F28_Création_d’expression</code>
                    . 
                    <code class="language-plaintext highlighter-rouge">R17_a_créé</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F2_Expression</code>
                    (instanciée en tant que 
                    <code class="language-plaintext highlighter-rouge">E33_Objet_linguistique</code>
                    ). 
                    <code class="language-plaintext highlighter-rouge">P72_a_pour_langue</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E56_Langue</code></p>
            </td>
        </tr>
        <tr>
            <td></td>
            <td>
                <p class="en block">E39 Actor. P14i performed: E7 Activity. P2 has type: E55 Type {Creating expressions in Language [fill in the specific language]}</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">E39_Actant</code>. 
                    <code class="language-plaintext highlighter-rouge">P14i_a_effectué</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E7_Activité</code>
                    . 
                    <code class="language-plaintext highlighter-rouge">P2_a_pour_type</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E55_Type</code>  {Création d’expression dans la langue [indiquer la langue spécifique]}</p>
            </td>
        </tr>
        <tr>
            <td rowspan="2">
                <p>LRM-E7-A1</p>
            </td>
            <td rowspan="2">
                <p class="en block">Person</p>
                <p class="en block">~~~~~</p>
                <p>Personne</p>
            </td>
            <td rowspan="2">
                <p class="en block">Profession / Occupation</p>
                <p class="en block">~~~~~</p>
                <p>Profession / Occupation</p>
            </td>
            <td rowspan="2">
                <p class="en block">A profession or occupation in which the <em>person</em> works or worked</p>
                <p class="en block">~~~~~</p>
                <p>Une profession ou occupation que la 
                    <code class="language-plaintext highlighter-rouge">LRM-E7_Personne</code> exerce ou a exercée.</p>
            </td>
            <td>
                <p class="en block">long-term identification</p>
                <p class="en block">~~~~~</p>
                <p>Identification prolongée*</p>
            </td>
            <td>
                <p class="en block">E21 Person. P2 has type: E55 Type {Professional category}</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">E21_Personne</code>. 
                    <code class="language-plaintext highlighter-rouge">P2_a_pour_type</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E55_Type</code>  {Catégorie professionelle}</p>
            </td>
        </tr>
        <tr>
            <td>
                <p class="en block">specific activity</p>
                <p class="en block">~~~~~</p>
                <p>Activité spécifique*</p>
            </td>
            <td>
                <p class="en block">E21 Person. P14i performed: E7 Activity. P2 has type: E55 Type {Occupational activity}</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">E21_Personne</code>. 
                    <code class="language-plaintext highlighter-rouge">P14i_a_effectué</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E7_Activité</code>
                    . 
                    <code class="language-plaintext highlighter-rouge">P2_a_pour_type</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E55_Type</code>  {« Occupation »}</p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E9-A1</p>
            </td>
            <td>
                <p class="en block">Nomen</p>
                <p class="en block">~~~~~</p>
                <p>Nomen</p>
            </td>
            <td>
                <p class="en block">Category</p>
                <p class="en block">~~~~~</p>
                <p>Catégorie</p>
            </td>
            <td>
                <p class="en block">A type to which the <em>nomen</em> belongs</p>
                <p class="en block">a) the type of thing named</p>
                <p class="en block">b) the source in which the <em>nomen</em> is attested</p>
                <p class="en block">c) the function of the<em>nomen</em></p>
                <p class="en block">~~~~~</p>
                <p>Un type auquel le 
                    <code class="language-plaintext highlighter-rouge">LRM-E9_Nomen</code> appartient :</p>
                <ul>
                    <li>
                        <p>le type de chose qui est nommée ; </p>
                    </li>
                    <li>
                        <p>la source où le 
                            <code class="language-plaintext highlighter-rouge">LRM-E9_Nomen</code>      est attesté ; </p>
                    </li>
                    <li>
                        <p>la fonction du 
                            <code class="language-plaintext highlighter-rouge">LRM-E9_Nomen</code>      .</p>
                    </li>
                </ul>
            </td>
            <td></td>
            <td>
                <p class="en block">F12 Nomen. P2 has type: E55 Type {Nomen:Category}</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F12_Nomen</code>. 
                    <code class="language-plaintext highlighter-rouge">P2_a_pour_type</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E55_Type</code>  {Nomen : Catégorie}</p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E9-A2</p>
            </td>
            <td>
                <p class="en block">Nomen</p>
                <p class="en block">~~~~~</p>
                <p>Nomen</p>
            </td>
            <td>
                <p class="en block">Nomen string</p>
                <p class="en block">~~~~~</p>
                <p>Chaîne du nomen</p>
            </td>
            <td>
                <p class="en block">The combination of signs that forms an appellation associated with an entity through the <em>nomen</em></p>
                <p class="en block">~~~~~</p>
                <p>La combinaison de signes qui forme une appellation associée à une entité à travers le 
                    <code class="language-plaintext highlighter-rouge">LRM-E9_Nomen</code> .</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F12 Nomen. R33 has string: E62 String</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F12_Nomen</code>. 
                    <code class="language-plaintext highlighter-rouge">R33_a_pour_chaîne_de_caractères</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E62_Chaîne_de_caractères</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E9-A3</p>
            </td>
            <td>
                <p class="en block">Nomen</p>
                <p class="en block">~~~~~</p>
                <p>Nomen</p>
            </td>
            <td>
                <p class="en block">Scheme</p>
                <p class="en block">~~~~~</p>
                <p>Schéma d’encodage</p>
            </td>
            <td>
                <p class="en block">The scheme in which the <em>nomen</em> is established</p>
                <p class="en block">~~~~~</p>
                <p>Le schéma d’encodage utilisé pour établir le 
                    <code class="language-plaintext highlighter-rouge">LRM-E9_Nomen</code> .</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F12 Nomen. R35 is specified by: F2 Expression. {P2 has type: E55 Type = “controlled vocabulary or knowledge organization system”} </p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F12_Nomen</code>. 
                    <code class="language-plaintext highlighter-rouge">R35_est_specifié_par</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F2_Expression</code>
                    . {
                    <code class="language-plaintext highlighter-rouge">P2_a_pour_type</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E55_Type</code>  = « Vocabulaire contrôlé ou système d’organisation des connaissances »}</p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E9-A4</p>
            </td>
            <td>
                <p class="en block">Nomen</p>
                <p class="en block">~~~~~</p>
                <p>Nomen</p>
            </td>
            <td>
                <p class="en block">Intended audience</p>
                <p class="en block">~~~~~</p>
                <p>Public destinataire</p>
            </td>
            <td>
                <p class="en block">A class of users for which the <em>nomen</em> is considered appropriate or preferred</p>
                <p class="en block">~~~~~</p>
                <p>Une catégorie d’utilisateurs pour lesquels le 
                    <code class="language-plaintext highlighter-rouge">LRM-E9_Nomen</code> est jugé approprié ou est privilégié.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F12 Nomen. P103 was intended for: E55 Type {Personal characteristic}</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F12_Nomen</code>. 
                    <code class="language-plaintext highlighter-rouge">P103_a_eu_pour_raison_d’être</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E55_Type</code>  {Caractéristique personnelle}</p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E9-A5</p>
            </td>
            <td>
                <p class="en block">Nomen</p>
                <p class="en block">~~~~~</p>
                <p>Nomen</p>
            </td>
            <td>
                <p class="en block">Context of use</p>
                <p class="en block">~~~~~</p>
                <p>Contexte d’utilisation</p>
            </td>
            <td>
                <p class="en block">Information as to the context(s) in which a <em>nomen</em>
                    is used by the <em>agent</em> who is referred to through it</p>
                <p class="en block">~~~~~</p>
                <p>Des informations sur le (ou les) contexte(s) où un 
                    <code class="language-plaintext highlighter-rouge">LRM-E9_Nomen</code>
                    est utilisé par l’agent auquel ce 
                    <code class="language-plaintext highlighter-rouge">LRM-E9_Nomen</code> réfère.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F12 Nomen. P16i was used for: E7 Activity {P14 carried out by: E39 Actor. P67i is referred to by: F12 Nomen}. P2 has type: E55 Type {Type of context}</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F12_Nomen</code>. 
                    <code class="language-plaintext highlighter-rouge">P16_a_mobilisé_l’objet_spécifique</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E7_Activité </code>
                    {
                    <code class="language-plaintext highlighter-rouge">P14_a_été_effectué_par</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E39_Actant</code>
                    . 
                    <code class="language-plaintext highlighter-rouge">P67i_fait_l’objet_d’un_renvoi_par</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F12_Nomen</code>
                    }. 
                    <code class="language-plaintext highlighter-rouge">P2_a_pour_type</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E55_Type</code>  = « Type de contexte »}</p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E9-A6</p>
            </td>
            <td>
                <p class="en block">Nomen</p>
                <p class="en block">~~~~~</p>
                <p>Nomen</p>
            </td>
            <td>
                <p class="en block">Reference source</p>
                <p class="en block">~~~~~</p>
                <p>Source de référence</p>
            </td>
            <td>
                <p class="en block">A source in which there is evidence for the use of the <em>nomen</em></p>
                <p class="en block">~~~~~</p>
                <p>Une source qui atteste de l’utilisation du 
                    <code class="language-plaintext highlighter-rouge">LRM-E9_Nomen</code> .</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F12 Nomen. R35 is specified by: F2 Expression. R4i is embodied in: F3 Manifestation</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F12_Nomen</code>. 
                    <code class="language-plaintext highlighter-rouge">R35_est_specifié_par</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F2_Expression</code>
                    . 
                    <code class="language-plaintext highlighter-rouge">R4i_est_incarné_</code>
                    <code class="language-plaintext highlighter-rouge">dans</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F3_Manifestation</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E9-A7</p>
            </td>
            <td>
                <p class="en block">Nomen</p>
                <p class="en block">~~~~~</p>
                <p>Nomen</p>
            </td>
            <td>
                <p class="en block">Language</p>
                <p class="en block">~~~~~</p>
                <p>Langue</p>
            </td>
            <td>
                <p class="en block">The language in which the <em>nomen</em> is attested</p>
                <p class="en block">~~~~~</p>
                <p>La langue dans laquelle le 
                    <code class="language-plaintext highlighter-rouge">LRM-E9_Nomen</code> est attesté. </p>
            </td>
            <td></td>
            <td>
                <p class="en block">F12 Nomen. R54 has language: E56 Language</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F12_Nomen</code>. 
                    <code class="language-plaintext highlighter-rouge">R54_a_pour_langue</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E56_Langue</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E9-A8</p>
            </td>
            <td>
                <p class="en block">Nomen</p>
                <p class="en block">~~~~~</p>
                <p>Nomen</p>
            </td>
            <td>
                <p class="en block">Script</p>
                <p class="en block">~~~~~</p>
                <p>Écriture</p>
            </td>
            <td>
                <p class="en block">The script in which the <em>nomen string</em> is notated</p>
                <p class="en block">~~~~~</p>
                <p>L’écriture dans laquelle la chaîne du 
                    <code class="language-plaintext highlighter-rouge">LRM-E9_Nomen</code> est notée.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F12 Nomen. P2 has type: E55 Type {Script}</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F12_Nomen</code>.  
                    <code class="language-plaintext highlighter-rouge">P2_a_pour_type</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E55_Type</code>  {« Écriture »}</p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E9-A9</p>
            </td>
            <td>
                <p class="en block">Nomen</p>
                <p class="en block">~~~~~</p>
                <p>Nomen</p>
            </td>
            <td>
                <p class="en block">Script conversion</p>
                <p class="en block">~~~~~</p>
                <p>Conversion d’écriture</p>
            </td>
            <td>
                <p class="en block">The rule, system, or standard that was used to create a <em>nomen string</em>
                    of a <em>nomen</em>
                    that is derived on the basis of a <em>nomen string</em>
                    of another, distinct <em>nomen</em>
                    whose <em>nomen string</em> is notated in another, distinct script</p>
                <p class="en block">~~~~~</p>
                <p>La règle, le système ou la norme utilisée pour créer la chaîne du 
                    <code class="language-plaintext highlighter-rouge">LRM-E9_Nomen</code>
                    d’un 
                    <code class="language-plaintext highlighter-rouge">LRM-E9_Nomen</code>
                    dérivé à partir de la chaîne du 
                    <code class="language-plaintext highlighter-rouge">LRM-E9_Nomen</code>
                    d’un autre 
                    <code class="language-plaintext highlighter-rouge">LRM-E9_Nomen</code> distinct quand celle-ci est notée dans une écriture différente.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F12 Nomen {P2 has type: E55 Type = “transliterated”}. R36 uses script conversion: F36 Script Conversion</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F12_Nomen</code>. {
                    <code class="language-plaintext highlighter-rouge">P2_a_pour_type</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E55_Type</code>
                     = « Translittération »}. 
                    <code class="language-plaintext highlighter-rouge">R36_utilise_la_conversion_de_script</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F36_Conversion_de_script</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E10-A1</p>
            </td>
            <td>
                <p class="en block">Place</p>
                <p class="en block">~~~~~</p>
                <p>Place</p>
            </td>
            <td>
                <p class="en block">Category</p>
                <p class="en block">~~~~~</p>
                <p>Catégorie</p>
            </td>
            <td>
                <p class="en block">A type to which the <em>place</em> belongs</p>
                <p class="en block">~~~~~</p>
                <p>Un type auquel le 
                    <code class="language-plaintext highlighter-rouge">LRM-E10_Lieu</code> appartient.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">E53 Place. P2 has type: E55 Type {Place:Category}</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">E53_Lieu</code>. 
                    <code class="language-plaintext highlighter-rouge">P2_a_pour_type</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E55_Type</code>  {« Lieu : Catégorie »}</p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E10-A2</p>
            </td>
            <td>
                <p class="en block">Place</p>
                <p class="en block">~~~~~</p>
                <p>Place</p>
            </td>
            <td>
                <p class="en block">Location</p>
                <p class="en block">~~~~~</p>
                <p>Localisation</p>
            </td>
            <td>
                <p class="en block">A delimitation of the physical territory of the <em>place</em></p>
                <p class="en block">~~~~~</p>
                <p>Une délimitation du territoire physique du 
                    <code class="language-plaintext highlighter-rouge">LRM-E10_Lieu</code> .</p>
            </td>
            <td></td>
            <td>
                <p class="en block">E53 Place. P168 is defined by: E94 Space Primitive</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">E53_Lieu</code>. 
                    <code class="language-plaintext highlighter-rouge">P168_lieu_défini_par</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E94_Primitive_spatiale</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E11-A1</p>
            </td>
            <td>
                <p class="en block">Time-span</p>
                <p class="en block">~~~~~</p>
                <p>Laps de temps</p>
            </td>
            <td>
                <p class="en block">Beginning</p>
                <p class="en block">~~~~~</p>
                <p>Début</p>
            </td>
            <td>
                <p class="en block">A value for the time at which the <em>time- span</em> started, expressed in a precise way in an authoritative external system to allow temporal positioning of events</p>
                <p class="en block">~~~~~</p>
                <p>Une valeur du moment où le 
                    <code class="language-plaintext highlighter-rouge">LRM-E11_Laps_de_temps</code> a débuté, exprimée de manière précise dans un système externe faisant autorité pour situer les événements dans le temps.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">E52 Time-Span. P82 at some time within: E61 Time Primitive/xsd:DateTime</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">E52_Intervalle_temporel</code>. 
                    <code class="language-plaintext highlighter-rouge">P82_a_eu_lieu_durant</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E61_Primitive_temporelle</code>
                     / 
                    <code class="language-plaintext highlighter-rouge">xsd_DateHeure</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-E11-A2</p>
            </td>
            <td>
                <p class="en block">Time-span</p>
                <p class="en block">~~~~~</p>
                <p>Laps de temps</p>
            </td>
            <td>
                <p class="en block">Ending</p>
                <p class="en block">~~~~~</p>
                <p>Fin</p>
            </td>
            <td>
                <p class="en block">A value for the time at which the <em>time- span</em> ended, expressed in a precise way in an authoritative external system to allow temporal positioning of events</p>
                <p class="en block">~~~~~</p>
                <p>Une valeur du moment où le 
                    <code class="language-plaintext highlighter-rouge">LRM-E11_Laps_de_temps</code> a pris fin, exprimée de manière précise dans un système externe faisant autorité pour situer les événements dans le temps.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">E52 Time-Span. P82 at some time within: E61 Time Primitive/xsd:DateTime</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">E52_Intervalle_temporel</code>. 
                    <code class="language-plaintext highlighter-rouge">P82_a_eu_lieu_durant</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E61_Primitive_temporelle</code>
                     / 
                    <code class="language-plaintext highlighter-rouge">xsd:DateHeure</code></p>
            </td>
        </tr>
        <tr>
            <th>
                <p><em>Note de traduction</em>
                </p>
            </th>
            <td colspan="4">
                <p>Le texte de ce tableau est adapté de la traduction en français du <em>Modèle conceptuel pour l’information bibliographique</em> de la Fédération internationale des associations et institutions de bibliothèques (IFLA LRM). </p>
            </td>
        </tr>
        <tr>
            <th>
                <p><em>Références</em>
                </p>
            </th>
            <td colspan="4">
                <p>Riva, Pat, Patrick Le Bœuf, et Maja Žumer. 2021. <em>Un modèle conceptuel pour l’information bibliographique</em>
                    . Traduit par Aude Le Moullec-Rieu, Françoise Leresche, Frédéric Puyrenier, et Mélanie Roche. Committee Publications. La Haye, NL: Fédération internationale des associations et institutions de bibliothèques (IFLA).
                    <a href="https://repository.ifla.org/server/api/core/bitstreams/b395a0a0-c9b8-49c6-8919-9befda0c40ed/content">
                        <span class="underline"/></a>
                    <a href="https://repository.ifla.org/server/api/core/bitstreams/b395a0a0-c9b8-49c6-8919-9befda0c40ed/content">
                        <span class="underline">https://repository.ifla.org/server/api/core/bitstreams/b395a0a0-c9b8-49c6-8919-9befda0c40ed/content</span>
                    </a>.</p>
            </td>
        </tr>
    </tbody>
</table>


<h2 id="relations-du-iflalrm"><span class="en heading">8.3. IFLA LRM Relationships - </span>8.3. Relations du IFLA LRM</h2>

<table>
    <tbody>
        <tr>
            <th>
                <p class="en block">LRM ID</p>
                <p class="en block">~~~~~</p>
                <p>Identifiant LRM</p>
            </th>
            <th>
                <p class="en block">LRM Domain</p>
                <p class="en block">~~~~~</p>
                <p>Domaine LRM</p>
            </th>
            <th>
                <p class="en block">Name (inverse)</p>
                <p class="en block">~~~~~</p>
                <p>Nom (inverse)</p>
            </th>
            <th>
                <p class="en block">LRM Range</p>
                <p class="en block">~~~~~</p>
                <p>Portée LRM</p>
            </th>
            <th>
                <p class="en block">LRM Definition</p>
                <p class="en block">~~~~~</p>
                <p>Définition LRM</p>
            </th>
            <th>
                <p class="en block">Condition</p>
                <p class="en block">~~~~~</p>
                <p>Condition</p>
            </th>
            <th>
                <p class="en block">Mapping</p>
                <p class="en block">~~~~~</p>
                <p>Mise en correspondance</p>
            </th>
        </tr>
        <tr>
            <td>
                <p>LRM-R1</p>
            </td>
            <td>
                <p class="en block">Res</p>
                <p class="en block">~~~~~</p>
                <p>Res</p>
            </td>
            <td>
                <p class="en block">is associated with (is associated with)</p>
                <p class="en block">~~~~~</p>
                <p>est associée à (est associée à)</p>
            </td>
            <td>
                <p class="en block">Res</p>
                <p class="en block">~~~~~</p>
                <p>Res</p>
            </td>
            <td>
                <p class="en block">This relationship links two <em>res</em> that have an association of any kind</p>
                <p class="en block">~~~~~</p>
                <p>Cette relation lie deux 
                    <code class="language-plaintext highlighter-rouge">LRM-E1_Res</code>
                    associées d’une manière ou d’une autre.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">no mapping (too broad), use specific properties</p>
                <p class="en block">~~~~~</p>
                <p>Il n’y a pas de mise en correspondance spécifique en raison de l’application élargie de la relation, il faut donc utiliser des propriétés spécifiques. </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-R2</p>
            </td>
            <td>
                <p class="en block">Work</p>
                <p class="en block">~~~~~</p>
                <p>Œuvre</p>
            </td>
            <td>
                <p class="en block">is realized through (realizes)</p>
                <p class="en block">~~~~~</p>
                <p>est réalisée à travers (réalise)</p>
            </td>
            <td>
                <p class="en block">Expression</p>
                <p class="en block">~~~~~</p>
                <p>Expression</p>
            </td>
            <td>
                <p class="en block">This relationship links a <em>work</em> with any of the <em>expressions</em> which convey the same intellectual or artistic content</p>
                <p class="en block">~~~~~</p>
                <p>Cette relation lie une 
                    <code class="language-plaintext highlighter-rouge">LRM-E2_Œuvre</code>
                    à chacune des 
                    <code class="language-plaintext highlighter-rouge">LRM-E3_Expression</code>
                    véhiculant le même contenu intellectuel ou artistique.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F1 Work. R3 is realised in: F2 Expression</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F1_Œuvre</code>. 
                    <code class="language-plaintext highlighter-rouge">R3_est_réalisé_dans</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F2_Expression</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-R3</p>
            </td>
            <td>
                <p class="en block">Expression</p>
                <p class="en block">~~~~~</p>
                <p>Expression</p>
            </td>
            <td>
                <p class="en block">is embodied in (embodies)</p>
                <p class="en block">~~~~~</p>
                <p>est matérialisée dans (matérialise)</p>
            </td>
            <td>
                <p class="en block">Manifestation</p>
                <p class="en block">~~~~~</p>
                <p>Manifestation</p>
            </td>
            <td>
                <p class="en block">This relationship links an <em>expression</em> with a <em>manifestation</em> in which the <em>expression</em> appears</p>
                <p class="en block">~~~~~</p>
                <p>Cette relation lie une 
                    <code class="language-plaintext highlighter-rouge">LRM-E3_Expression</code>
                    à une 
                    <code class="language-plaintext highlighter-rouge">LRM-E4_Manifestation</code>
                    dans laquelle cette 
                    <code class="language-plaintext highlighter-rouge">LRM-E3_Expression</code>
                    figure.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F2 Expression. R4i is embodied in: F3 Manifestation</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F2_Expression</code>. 
                    <code class="language-plaintext highlighter-rouge">R4i_est_incarné_dans</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F3_Manifestation</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-R4</p>
            </td>
            <td>
                <p class="en block">Manifestation</p>
                <p class="en block">~~~~~</p>
                <p>Manifestation</p>
            </td>
            <td>
                <p class="en block">is exemplified by (exemplifies)</p>
                <p class="en block">~~~~~</p>
                <p>est exemplifiée par (exemplifie)</p>
            </td>
            <td>
                <p class="en block">Item</p>
                <p class="en block">~~~~~</p>
                <p>Item</p>
            </td>
            <td>
                <p class="en block">This relationship connects a <em>manifestation</em> with any <em>item</em> that reflects the characteristics of that <em>manifestation</em></p>
                <p class="en block">~~~~~</p>
                <p>Cette relation connecte une 
                    <code class="language-plaintext highlighter-rouge">LRM-E4_Manifestation</code>
                    avec tout 
                    <code class="language-plaintext highlighter-rouge">LRM-E5_Item</code>
                    reflétant les caractéristiques de cette 
                    <code class="language-plaintext highlighter-rouge">LRM-E4_Manifestation</code>
                    .</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F3 Manifestation. R7i is exemplified by: F5 Item</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F3_Manifestation</code>. 
                    <code class="language-plaintext highlighter-rouge">R7i_est_exemplifié_par</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F5_Item</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-R5</p>
            </td>
            <td>
                <p class="en block">Work</p>
                <p class="en block">~~~~~</p>
                <p>Œuvre</p>
            </td>
            <td>
                <p class="en block">was created by (created)</p>
                <p class="en block">~~~~~</p>
                <p>a été créée par (a créé)</p>
            </td>
            <td>
                <p class="en block">Agent</p>
                <p class="en block">~~~~~</p>
                <p>Agent</p>
            </td>
            <td>
                <p class="en block">This relationship links a <em>work</em> to an <em>agent</em> responsible for the creation of the intellectual or artistic content</p>
                <p class="en block">~~~~~</p>
                <p>La connexion logique entre une 
                    <code class="language-plaintext highlighter-rouge">LRM-E2_Œuvre</code>
                    et un agent qui lui est lié sert de base à la fois pour identifier l’
                    <code class="language-plaintext highlighter-rouge">LRM-E6_Agent</code>
                    responsable d’une œuvre particulière et pour garantir que toutes les œuvres d’un agent donné sont liées à cet agent.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F1 Work. R16i was created by: F27 Work Creation. P14 carried out by {P14.1 in the role of: E55 Type = “creator”}: E39 Actor</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F1_Œuvre</code>. 
                    <code class="language-plaintext highlighter-rouge">R16i_a_été_créé_par</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F27_Création_d’œuvre</code>
                    . 
                    <code class="language-plaintext highlighter-rouge">P14_a_été_effectué_par</code>
                    {
                    <code class="language-plaintext highlighter-rouge">P14.1_dans_le_rôle_de</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E55_Type</code>
                     = « Créateur »} : 
                    <code class="language-plaintext highlighter-rouge">E39_Actant</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-R6</p>
            </td>
            <td>
                <p class="en block">Expression</p>
                <p class="en block">~~~~~</p>
                <p>Expression</p>
            </td>
            <td>
                <p class="en block">was created by (created)</p>
                <p class="en block">~~~~~</p>
                <p>a été créée par (a créé)</p>
            </td>
            <td>
                <p class="en block">Agent</p>
                <p class="en block">~~~~~</p>
                <p>Agent</p>
            </td>
            <td>
                <p class="en block">This relationship links an <em>expression</em> to an <em>agent</em> responsible for the realization of a <em>work</em></p>
                <p class="en block">~~~~~</p>
                <p>Cette relation lie une 
                    <code class="language-plaintext highlighter-rouge">LRM-E3_Expression</code>
                    à un 
                    <code class="language-plaintext highlighter-rouge">LRM-E6_Agent</code>
                    responsable de la réalisation d’une 
                    <code class="language-plaintext highlighter-rouge">LRM-E2_Œuvre</code>
                    .</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F2 Expression. R17i was created by: F28 Expression Creation. P14 carried out by {P14.1 in the role of: E55 Type = “creator”}: E39 Actor</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F2_Expression</code>. 
                    <code class="language-plaintext highlighter-rouge">R17i_a_été_créé_par</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F28_Création_d’expression</code>
                    . 
                    <code class="language-plaintext highlighter-rouge">P14_a_été_effectué_par</code>
                    {
                    <code class="language-plaintext highlighter-rouge">P14.1_dans_le_rôle_de</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E55_Type</code>
                     = « Créateur »} : 
                    <code class="language-plaintext highlighter-rouge">E39_Actant</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-R7</p>
            </td>
            <td>
                <p class="en block">Manifestation</p>
                <p class="en block">~~~~~</p>
                <p>Manifestation</p>
            </td>
            <td>
                <p class="en block">was created by (created) </p>
                <p class="en block">~~~~~</p>
                <p>a été créée par (a créé)</p>
            </td>
            <td>
                <p class="en block">Agent</p>
                <p class="en block">~~~~~</p>
                <p>Agent</p>
            </td>
            <td>
                <p class="en block">This relationship links a <em>manifestation</em> to an <em>agent</em> responsible for creating the <em>manifestation</em></p>
                <p class="en block">~~~~~</p>
                <p>Cette relation lie une 
                    <code class="language-plaintext highlighter-rouge">LRM-E4_Manifestation</code>
                    à un 
                    <code class="language-plaintext highlighter-rouge">LRM-E6_Agent</code>
                    responsable de sa création.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F3 Manifestation. R24i was created through: F30 Manifestation Creation. P14 carried out by: E39 Actor</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F3_Manifestation</code>. 
                    <code class="language-plaintext highlighter-rouge">R24i_a_été_créé_à_travers</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F30_Création_de_manifestation</code>
                    . 
                    <code class="language-plaintext highlighter-rouge">P14_a_été_effectué_par</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E39_Actant</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-R8</p>
            </td>
            <td>
                <p class="en block">Manifestation</p>
                <p class="en block">~~~~~</p>
                <p>Manifestation</p>
            </td>
            <td>
                <p class="en block">was manufactured by (manufactured)</p>
                <p class="en block">~~~~~</p>
                <p>a été fabriquée par (a fabriqué)</p>
            </td>
            <td>
                <p class="en block">Agent</p>
                <p class="en block">~~~~~</p>
                <p>Agent</p>
            </td>
            <td>
                <p class="en block">This relationship links a <em>manifestation</em> to an <em>agent</em> responsible for the fabrication, production or manufacture of the <em>items </em> of that <em>manifestation</em></p>
                <p class="en block">~~~~~</p>
                <p>Cette relation lie une 
                    <code class="language-plaintext highlighter-rouge">LRM-E4_Manifestation</code>
                    à un 
                    <code class="language-plaintext highlighter-rouge">LRM-E6_Agent</code>
                    responsable de la fabrication (manuelle, industrielle, etc.) des 
                    <code class="language-plaintext highlighter-rouge">LRM-E5_Item</code>
                    de cette 
                    <code class="language-plaintext highlighter-rouge">LRM-E4_Manifestation</code>
                    .</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F3 Manifestation. R27i was materialized by: F32 Item Production Event. P14 carried out by: E39 Actor</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F3_Manifestation</code>. 
                    <code class="language-plaintext highlighter-rouge">R27i_a_été_matérialisé_par</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F32_Évènement_de_production_d’item</code>
                    . 
                    <code class="language-plaintext highlighter-rouge">P14_a_été_effectué_par</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E39_Actant</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-R9</p>
            </td>
            <td>
                <p class="en block">Manifestation</p>
                <p class="en block">~~~~~</p>
                <p>Manifestation</p>
            </td>
            <td>
                <p class="en block">is distributed by (distributes)</p>
                <p class="en block">~~~~~</p>
                <p>est distribuée par (distribue)</p>
            </td>
            <td>
                <p class="en block">Agent</p>
                <p class="en block">~~~~~</p>
                <p>Agent</p>
            </td>
            <td>
                <p class="en block">This relationship links a <em>manifestation</em> to an <em>agent</em> responsible for making i
                    <em>tems</em> of that <em>manifestation</em> available</p>
                <p class="en block">~~~~~</p>
                <p>Cette relation lie une 
                    <code class="language-plaintext highlighter-rouge">LRM-E4_Manifestation</code>
                    à un 
                    <code class="language-plaintext highlighter-rouge">LRM-E6_Agent</code>
                    responsable de la mise à disposition des 
                    <code class="language-plaintext highlighter-rouge">LRM-E5_Item</code>
                    de cette 
                    <code class="language-plaintext highlighter-rouge">LRM-E4_Manifestation</code>
                    .</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F3 Manifestation. P104 is subject to: E30 Right {P2 has type: E55 Type = “distribution”}. P75i is possessed by: E39 Actor</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F3_Manifestation</code>. 
                    <code class="language-plaintext highlighter-rouge">P104_est_soumis_à</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E30_Droit</code>
                    . {
                    <code class="language-plaintext highlighter-rouge">P2_a_pour_type</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E55_Type</code>
                     = « Distribution »}. 
                    <code class="language-plaintext highlighter-rouge">P75i_est_possédé_par</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E39_Actant</code></p>
            </td>
        </tr>
        <tr>
            <td rowspan="2">
                <p>LRM-R10</p>
            </td>
            <td rowspan="2">
                <p class="en block">Item</p>
                <p class="en block">~~~~~</p>
                <p>Item</p>
            </td>
            <td rowspan="2">
                <p class="en block">is owned by (owns)</p>
                <p class="en block">~~~~~</p>
                <p>est possédé par (possède)</p>
            </td>
            <td rowspan="2">
                <p class="en block">Agent</p>
                <p class="en block">~~~~~</p>
                <p>Agent</p>
            </td>
            <td rowspan="2">
                <p class="en block">This relationship links an i
                    <em>tem</em> to an <em>agent</em> that is or was the owner or custodian of that <em>item</em></p>
                <p class="en block">~~~~~</p>
                <p>Cette relation lie un 
                    <code class="language-plaintext highlighter-rouge">LRM-E5_Item</code>
                    à un 
                    <code class="language-plaintext highlighter-rouge">LRM-E6_Agent</code>
                    qui est ou a été le possesseur ou le dépositaire de cet 
                    <code class="language-plaintext highlighter-rouge">LRM-E5_Item</code>
                    .</p>
            </td>
            <td>
                <p class="en block">ownership</p>
                <p class="en block">~~~~~</p>
                <p>propriété</p>
            </td>
            <td>
                <p class="en block">F5 Item. P51 has former or current owner: E39 Actor</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F5_Item</code>. 
                    <code class="language-plaintext highlighter-rouge">P51_a_pour_propriétaire_actuel_ou_antérieur</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E39_Actant</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p class="en block">custodianship</p>
                <p class="en block">~~~~~</p>
                <p>tutelle</p>
            </td>
            <td>
                <p class="en block">F5 Item. P49 has former or current keeper: E39 Actor</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F5_Item</code>. 
                    <code class="language-plaintext highlighter-rouge">P49_a_pour_actant_détenteur_actuel_ou_antérieur</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E39_Actant</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-R11</p>
            </td>
            <td>
                <p class="en block">Item</p>
                <p class="en block">~~~~~</p>
                <p>Item</p>
            </td>
            <td>
                <p class="en block">was modified by (modified)</p>
                <p class="en block">~~~~~</p>
                <p>a été modifié par (a modifié)</p>
            </td>
            <td>
                <p class="en block">Agent</p>
                <p class="en block">~~~~~</p>
                <p>Agent</p>
            </td>
            <td>
                <p class="en block">This relationship links an <em>item</em> to an <em>agent</em> that made changes to this particular <em>item</em> without creating a new <em>manifestation</em></p>
                <p class="en block">~~~~~</p>
                <p>Cette relation lie un 
                    <code class="language-plaintext highlighter-rouge">LRM-E5_Item</code>
                    à un 
                    <code class="language-plaintext highlighter-rouge">LRM-E6_Agent</code>
                    ayant effectué des changements sur cet 
                    <code class="language-plaintext highlighter-rouge">LRM-E5_Item</code>
                    particulier sans pour autant créer une nouvelle 
                    <code class="language-plaintext highlighter-rouge">LRM-E4_Manifestation</code>
                    .</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F5 Item. P31i was modified by: E11 Modification. P14 carried out by: E39 Actor</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F5_Item</code>. 
                    <code class="language-plaintext highlighter-rouge">P31i_a_été_modifié_par</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E11_Modification</code>
                    . 
                    <code class="language-plaintext highlighter-rouge">P14_a_été_effectué_par</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E39_Actant</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-R12</p>
            </td>
            <td>
                <p class="en block">Work</p>
                <p class="en block">~~~~~</p>
                <p>Œuvre</p>
            </td>
            <td>
                <p class="en block">has as subject (is subject of)</p>
                <p class="en block">~~~~~</p>
                <p>a pour sujet (est le sujet de)</p>
            </td>
            <td>
                <p class="en block">Res</p>
                <p class="en block">~~~~~</p>
                <p>Res</p>
            </td>
            <td>
                <p class="en block">This relationship links a <em>work</em> to its topic(s)</p>
                <p class="en block">~~~~~</p>
                <p>La connexion logique entre une 
                    <code class="language-plaintext highlighter-rouge">LRM-E2_Œuvre</code>
                    et une entité qui lui est liée par une relation de sujet sert de base à la fois pour identifier le sujet d’une 
                    <code class="language-plaintext highlighter-rouge">LRM-E2_Œuvre</code>
                    particulière et pour garantir que toutes les 
                    <code class="language-plaintext highlighter-rouge">LRM-E2_Œuvre</code>
                    traitant d’un sujet donné sont liées à ce sujet.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F1 Work. P129 is about: E1 CRM Entity</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F1_Œuvre</code>. 
                    <code class="language-plaintext highlighter-rouge">P129_a_pour_sujet</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-R13</p>
            </td>
            <td>
                <p class="en block">Res</p>
                <p class="en block">~~~~~</p>
                <p>Res</p>
            </td>
            <td>
                <p class="en block">has appellation (is appellation of)</p>
                <p class="en block">~~~~~</p>
                <p>a pour appellation (est une appellation de)</p>
            </td>
            <td>
                <p class="en block">Nomen</p>
                <p class="en block">~~~~~</p>
                <p>Nomen</p>
            </td>
            <td>
                <p class="en block">This relationship links an entity with a sign or combination of signs or symbols through which that entity is referred to within a given scheme or context</p>
                <p class="en block">~~~~~</p>
                <p>Cette relation lie une entité à un signe ou une combinaison de signes ou de symboles à l’aide desquels on réfère à cette entité dans un schéma d’encodage ou un contexte donnés.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">E1 CRM Entity. P67i is referred to by: F12 Nomen</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code>. 
                    <code class="language-plaintext highlighter-rouge">P67i_fait_l’objet_d’un_renvoi_par</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F12_Nomen</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-R14</p>
            </td>
            <td>
                <p class="en block">Agent</p>
                <p class="en block">~~~~~</p>
                <p>Agent</p>
            </td>
            <td>
                <p class="en block">assigned (was assigned by)</p>
                <p class="en block">~~~~~</p>
                <p>a attribué (a été attribué par)</p>
            </td>
            <td>
                <p class="en block">Nomen</p>
                <p class="en block">~~~~~</p>
                <p>Nomen</p>
            </td>
            <td>
                <p class="en block">This relationship links an <em>agen</em> t with a particular <em>nomen </em> that was assigned by this <em>agent</em></p>
                <p class="en block">~~~~~</p>
                <p>Cette relation lie un 
                    <code class="language-plaintext highlighter-rouge">LRM-E6_Agent</code>
                    à un 
                    <code class="language-plaintext highlighter-rouge">LRM-E9_Nomen</code>
                    particulier qui a été attribué par cet 
                    <code class="language-plaintext highlighter-rouge">LRM-E6_Agent</code>
                    .</p>
            </td>
            <td></td>
            <td>
                <p class="en block">E39 Actor. P14i performed: E13 Attribute Assignment. P141 assigned: F12 Nomen</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">E39_Actant</code>. 
                    <code class="language-plaintext highlighter-rouge">P14i_a_effectué</code>
                      : 
                    <code class="language-plaintext highlighter-rouge">E13_Assignation_d’attribut</code>
                    . 
                    <code class="language-plaintext highlighter-rouge">P141_a_assigné</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F12_Nomen</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-R15</p>
            </td>
            <td>
                <p class="en block">Nomen</p>
                <p class="en block">~~~~~</p>
                <p>Nomen</p>
            </td>
            <td>
                <p class="en block">is equivalent to (is equivalent to)</p>
                <p class="en block">~~~~~</p>
                <p>est l’équivalent de (est l’équivalent de)</p>
            </td>
            <td>
                <p class="en block">Nomen</p>
                <p class="en block">~~~~~</p>
                <p>Nomen</p>
            </td>
            <td>
                <p class="en block">This is the relationship between two <em>nomens</em> which are appellations of the same <em>res</em></p>
                <p class="en block">~~~~~</p>
                <p>Cette relation est définie entre deux 
                    <code class="language-plaintext highlighter-rouge">LRM-E9_Nomen</code>
                    qui sont des appellations de la même 
                    <code class="language-plaintext highlighter-rouge">LRM-E1_Res</code>
                    .</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F12 Nomen. R56 has related form: F12 Nomen</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F12_Nomen</code>. 
                    <code class="language-plaintext highlighter-rouge">R56_a_pour_forme_connexe</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F12_Nomen</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-R16</p>
            </td>
            <td>
                <p class="en block">Nomen</p>
                <p class="en block">~~~~~</p>
                <p>Nomen</p>
            </td>
            <td>
                <p class="en block">has part (is part of)</p>
                <p class="en block">~~~~~</p>
                <p>a pour partie (fait partie de)</p>
            </td>
            <td>
                <p class="en block">Nomen</p>
                <p class="en block">~~~~~</p>
                <p>Nomen</p>
            </td>
            <td>
                <p class="en block">This relationship indicates that the <em>nomen string</em> of the domain <em>nomen</em> is constructed using the <em>nomen string</em> of another <em>nomen</em> as a component</p>
                <p class="en block">~~~~~</p>
                <p>Cette relation indique qu’une chaîne du 
                    <code class="language-plaintext highlighter-rouge">LRM-E9_Nomen</code>
                    est construite en utilisant la chaîne du 
                    <code class="language-plaintext highlighter-rouge">LRM-E9_Nomen</code>
                    d’un autre 
                    <code class="language-plaintext highlighter-rouge">LRM-E9_Nomen</code>
                    comme élément constitutif.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F12 Nomen. R8 combines: F12 Nomen</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F12_Nomen</code>. 
                    <code class="language-plaintext highlighter-rouge">R8_combine</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F12_Nomen</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-R17</p>
            </td>
            <td>
                <p class="en block">Nomen</p>
                <p class="en block">~~~~~</p>
                <p>Nomen</p>
            </td>
            <td>
                <p class="en block">is derivation of (has derivation)</p>
                <p class="en block">~~~~~</p>
                <p>est dérivé de (a pour dérivation)</p>
            </td>
            <td>
                <p class="en block">Nomen</p>
                <p class="en block">~~~~~</p>
                <p>Nomen</p>
            </td>
            <td>
                <p class="en block">This relationship indicates that one <em>nomen</em> was used as the basis for another <em>nomen</em> , both of which are appellations of the same <em>res</em></p>
                <p class="en block">~~~~~</p>
                <p>Cette relation indique qu’un 
                    <code class="language-plaintext highlighter-rouge">LRM-E9_Nomen</code>
                    a été utilisé comme base pour un autre 
                    <code class="language-plaintext highlighter-rouge">LRM-E9_Nomen</code>
                    , tous deux étant des appellations de la même 
                    <code class="language-plaintext highlighter-rouge">LRM-E1_Res</code>
                    .</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F12 Nomen. R56i is related form of {R56.1 has type E55 Type = “derivation”}: F12 Nomen</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F12_Nomen</code>. 
                    <code class="language-plaintext highlighter-rouge">R56i_est_la_forme_connexe_de</code>
                     {
                    <code class="language-plaintext highlighter-rouge">R56.1_a_pour_type</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E55_Type</code>
                     = « Dérivation »} : 
                    <code class="language-plaintext highlighter-rouge">F12_Nomen</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-R18</p>
            </td>
            <td>
                <p class="en block">Work</p>
                <p class="en block">~~~~~</p>
                <p>Œuvre</p>
            </td>
            <td>
                <p class="en block">has part (is part of)</p>
                <p class="en block">~~~~~</p>
                <p>a pour partie (fait partie de)</p>
            </td>
            <td>
                <p class="en block">Work</p>
                <p class="en block">~~~~~</p>
                <p>Œuvre</p>
            </td>
            <td>
                <p class="en block">This is the relationship between two <em>works, </em> where the content of one is a component of the other</p>
                <p class="en block">~~~~~</p>
                <p>Cette relation est définie entre deux 
                    <code class="language-plaintext highlighter-rouge">LRM-E2_Œuvre</code>
                    dont l’une est une partie constitutive de l’autre.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F1 Work. R67 has part: F1 Work</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F1_Œuvre</code>. 
                    <code class="language-plaintext highlighter-rouge">R67_a_pour_élément</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-R19</p>
            </td>
            <td>
                <p class="en block">Work</p>
                <p class="en block">~~~~~</p>
                <p>Œuvre</p>
            </td>
            <td>
                <p class="en block">precedes (succeeds)</p>
                <p class="en block">~~~~~</p>
                <p>précède (succède)</p>
            </td>
            <td>
                <p class="en block">Work</p>
                <p class="en block">~~~~~</p>
                <p>Œuvre</p>
            </td>
            <td>
                <p class="en block">This is the relationship of two <em>works</em> where the content of the second is a logical continuation of the first</p>
                <p class="en block">~~~~~</p>
                <p>Cette relation est définie entre deux 
                    <code class="language-plaintext highlighter-rouge">LRM-E2_Œuvre</code>
                    dont le contenu de la seconde est une continuation logique du contenu de la première.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F1 Work. R1i has successor: F1 Work</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F1_Œuvre</code>. 
                    <code class="language-plaintext highlighter-rouge">R1i_a_pour_successeur</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-R20</p>
            </td>
            <td>
                <p class="en block">Work</p>
                <p class="en block">~~~~~</p>
                <p>Œuvre</p>
            </td>
            <td>
                <p class="en block">accompanies / complements (is accompanied / complemented by)</p>
                <p class="en block">~~~~~</p>
                <p>accompagne / complète (est accompagnée par / est complétée par)</p>
            </td>
            <td>
                <p class="en block">Work</p>
                <p class="en block">~~~~~</p>
                <p>Œuvre</p>
            </td>
            <td>
                <p class="en block">This is the relationship between two <em>works </em> which are independent, but can also be used in conjunction with each other as complements or companions</p>
                <p class="en block">~~~~~</p>
                <p>Cette relation est définie entre deux 
                    <code class="language-plaintext highlighter-rouge">LRM-E2_Œuvre</code>
                    indépendantes mais pouvant aussi être utilisées conjointement, en complément ou accompagnement l’une de l’autre.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F1 Work. R77 accompanies or complements: F1 Work</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F1_Œuvre</code>. 
                    <code class="language-plaintext highlighter-rouge">R77_accompagne_ou_complémente</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-R21</p>
            </td>
            <td>
                <p class="en block">Work</p>
                <p class="en block">~~~~~</p>
                <p>Œuvre</p>
            </td>
            <td>
                <p class="en block">is inspiration for (is inspired by)</p>
                <p class="en block">~~~~~</p>
                <p>est source d’inspiration pour (inspirée de)</p>
            </td>
            <td>
                <p class="en block">Work</p>
                <p class="en block">~~~~~</p>
                <p>Œuvre</p>
            </td>
            <td>
                <p class="en block">This is the relationship between two <em>works </em> where the content of the first served as the source of ideas for the second</p>
                <p class="en block">~~~~~</p>
                <p>Cette relation est définie entre deux 
                    <code class="language-plaintext highlighter-rouge">LRM-E2_Œuvre</code>
                    dont le contenu de la première sert de source d’inspiration à la seconde.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F1 Work. R68i is inspiration for: F1 Work</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F1_Œuvre</code>. 
                    <code class="language-plaintext highlighter-rouge">R68i_est_source_d’inspiration_pour</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-R22</p>
            </td>
            <td>
                <p class="en block">Work</p>
                <p class="en block">~~~~~</p>
                <p>Œuvre</p>
            </td>
            <td>
                <p class="en block">is a transformation of (was transformed into)</p>
                <p class="en block">~~~~~</p>
                <p>est une transformation de (a été transformée en)</p>
            </td>
            <td>
                <p class="en block">Work</p>
                <p class="en block">~~~~~</p>
                <p>Œuvre</p>
            </td>
            <td>
                <p class="en block">This relationship indicates that a new <em>work</em> was created by changing the scope or editorial policy (as in a serial or aggregating <em>work</em> ), the genre or literary form (dramatization, novelization), target audience (adaptation for children), or style (paraphrase, imitation, parody) of a previous <em>work</em></p>
                <p class="en block">~~~~~</p>
                <p>Cette relation indique qu’une nouvelle 
                    <code class="language-plaintext highlighter-rouge">LRM-E2_Œuvre</code>
                    a été créée du fait d’un changement apporté à une 
                    <code class="language-plaintext highlighter-rouge">LRM-E2_Œuvre</code>
                    préexistante : changement de périmètre ou de politique éditoriale (comme dans le cas d’une ressource continue ou d’une œuvre agrégative), de genre ou de forme littéraire (adaptation au théâtre, adaptation en roman), de public destinataire (adaptation pour la jeunesse), ou de style (paraphrase, imitation, parodie).</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F1 Work. R2 is derivative of: F1 Work</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F1_Œuvre</code>. 
                    <code class="language-plaintext highlighter-rouge">R2_est_dérivé_de</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-R23</p>
            </td>
            <td>
                <p class="en block">Expression</p>
                <p class="en block">~~~~~</p>
                <p>Expression</p>
            </td>
            <td>
                <p class="en block">has part (is part of)</p>
                <p class="en block">~~~~~</p>
                <p>a pour partie (fait partie de)</p>
            </td>
            <td>
                <p class="en block">Expression</p>
                <p class="en block">~~~~~</p>
                <p>Expression</p>
            </td>
            <td>
                <p class="en block">This is a relationship between two <em>expressions </em> where one is a component of the other</p>
                <p class="en block">~~~~~</p>
                <p>Cette relation est définie entre deux 
                    <code class="language-plaintext highlighter-rouge">LRM-E3_Expression</code>
                    dont l’une est une partie constitutive de l’autre.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F2 Expression. R5 has component: F2 Expression</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F2_Expression</code>. 
                    <code class="language-plaintext highlighter-rouge">R5_a_pour_composant</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F2_Expression</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-R24</p>
            </td>
            <td>
                <p class="en block">Expression</p>
                <p class="en block">~~~~~</p>
                <p>Expression</p>
            </td>
            <td>
                <p class="en block">is derivation of (has derivation)</p>
                <p class="en block">~~~~~</p>
                <p>est dérivée de (a pour dérivation)</p>
            </td>
            <td>
                <p class="en block">Expression</p>
                <p class="en block">~~~~~</p>
                <p>Expression</p>
            </td>
            <td>
                <p class="en block">This relationship indicates that of two <em>expressions</em> of the same <em>work</em> , the second was used as the source for the other</p>
                <p class="en block">~~~~~</p>
                <p>Cette relation indique qu’entre deux 
                    <code class="language-plaintext highlighter-rouge">LRM-E3_Expression</code>
                    de la même 
                    <code class="language-plaintext highlighter-rouge">LRM-E2_Œuvre</code>
                    , la seconde a été utilisée comme source pour la première.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F2 Expression. R76 is derivative of: F2 Expression</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F2_Expression</code>. 
                    <code class="language-plaintext highlighter-rouge">R76_est_dérivé_de</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F2_Expression</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-R25</p>
            </td>
            <td>
                <p class="en block">Expression</p>
                <p class="en block">~~~~~</p>
                <p>Expression</p>
            </td>
            <td>
                <p class="en block">was aggregated by (aggregated)</p>
                <p class="en block">~~~~~</p>
                <p>a été agrégée par (agrège)</p>
            </td>
            <td>
                <p class="en block">Expression</p>
                <p class="en block">~~~~~</p>
                <p>Expression</p>
            </td>
            <td>
                <p class="en block">This relationship indicates that a specific <em>expression</em> of a <em>wor</em> k was chosen as part of the plan of an aggregating <em>expression</em></p>
                <p class="en block">~~~~~</p>
                <p>Cette relation indique qu’une 
                    <code class="language-plaintext highlighter-rouge">LRM-E3_Expression</code>
                    particulière d’une 
                    <code class="language-plaintext highlighter-rouge">LRM-E2_Œuvre</code>
                    a été sélectionnée pour intégrer le plan d’une 
                    <code class="language-plaintext highlighter-rouge">LRM-E3_Expression</code>
                    agrégative.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F2 Expression. P165i is incorporated in: F2 Expression</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F2_Expression</code>. 
                    <code class="language-plaintext highlighter-rouge">R165i_est_inclus_dans</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F2_Expression</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-R26</p>
            </td>
            <td>
                <p class="en block">Manifestation</p>
                <p class="en block">~~~~~</p>
                <p>Manifestation</p>
            </td>
            <td>
                <p class="en block">has part (is part of)</p>
                <p class="en block">~~~~~</p>
                <p>a pour partie (fait partie de)</p>
            </td>
            <td>
                <p class="en block">Manifestation</p>
                <p class="en block">~~~~~</p>
                <p>Manifestation</p>
            </td>
            <td>
                <p class="en block">This is a relationship between two <em>manifestations</em> where one is a component of the other</p>
                <p class="en block">~~~~~</p>
                <p>Cette relation est définie entre deux 
                    <code class="language-plaintext highlighter-rouge">LRM-E4_Manifestation</code>
                    dont l’une est une partie constitutive de l’autre.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F3 Manifestation. R71 has part: F3 Manifestation</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F3_Manifestation</code>. 
                    <code class="language-plaintext highlighter-rouge">R71_a_pour_élément</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F3_Manifestation</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-R27</p>
            </td>
            <td>
                <p class="en block">Manifestation</p>
                <p class="en block">~~~~~</p>
                <p>Manifestation</p>
            </td>
            <td>
                <p class="en block">has reproduction (is reproduction of)</p>
                <p class="en block">~~~~~</p>
                <p>a pour reproduction (reproduit)</p>
            </td>
            <td>
                <p class="en block">Manifestation</p>
                <p class="en block">~~~~~</p>
                <p>Manifestation</p>
            </td>
            <td>
                <p class="en block">This is the relationship between two <em>manifestations</em> providing the end-user with exactly the same content and where an earlier <em>manifestation</em> has provided a source for the creation of a subsequent <em>manifestation</em> , such as facsimiles, reproductions, reprints, and reissues</p>
                <p class="en block">~~~~~</p>
                <p>Cette relation est définie entre deux 
                    <code class="language-plaintext highlighter-rouge">LRM-E4_Manifestation</code>
                    offrant exactement le même contenu à l’utilisateur.rice final.e, lorsqu’une 
                    <code class="language-plaintext highlighter-rouge">LRM-E4_Manifestation</code>
                    antérieure a été utilisée pour créer une nouvelle 
                    <code class="language-plaintext highlighter-rouge">LRM-E4_Manifestation</code>
                    , comme dans le cas des fac-similés, reproductions, réimpressions, ou rééditions.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F3 Manifestation. R30i was publication reproduced in: F33 Reproduction Event. R24 created: F3 Manifestation</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F3_Manifestation</code>. 
                    <code class="language-plaintext highlighter-rouge">R30i_était_la_publication_reproduite_par</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F33_Évènement_de_reproduction</code>
                    . 
                    <code class="language-plaintext highlighter-rouge">R24_a_créé</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F3_Manifestation</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-R28</p>
            </td>
            <td>
                <p class="en block">Item</p>
                <p class="en block">~~~~~</p>
                <p>Item</p>
            </td>
            <td>
                <p class="en block">has reproduction (is reproduction of)</p>
                <p class="en block">~~~~~</p>
                <p>a pour reproduction (reproduit)</p>
            </td>
            <td>
                <p class="en block">Manifestation</p>
                <p class="en block">~~~~~</p>
                <p>Manifestation</p>
            </td>
            <td>
                <p class="en block">This is the relationship between an <em>item </em> of one <em>manifestation</em> and another <em>manifestation</em> providing the end-user with exactly the same content and where a specific <em>item</em> has provided a source for the creation of a subsequent <em>manifestation</em></p>
                <p class="en block">~~~~~</p>
                <p>Cette relation est définie entre un 
                    <code class="language-plaintext highlighter-rouge">LRM-E5_Item</code>
                    d’une 
                    <code class="language-plaintext highlighter-rouge">LRM-E4_Manifestation</code>
                    et une autre 
                    <code class="language-plaintext highlighter-rouge">LRM-E4_Manifestation</code>
                    offrant exactement le même contenu à l’utilisateur.rice final.e, lorsqu’un 
                    <code class="language-plaintext highlighter-rouge">LRM-E5_Item</code>
                    particulier a été utilisé pour créer une nouvelle 
                    <code class="language-plaintext highlighter-rouge">LRM-E4_Manifestation</code>
                    .</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F5 Item. R29i was object reproduced by: F33 Reproduction Event. R24 created: F3 Manifestation</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F5_Item</code>. 
                    <code class="language-plaintext highlighter-rouge">R29i_était_l’objet_reproduit_par</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F33_Évènement_de_reproduction</code>
                    . 
                    <code class="language-plaintext highlighter-rouge">R24_a_créé</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F3_Manifestation</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-R29</p>
            </td>
            <td>
                <p class="en block">Manifestation</p>
                <p class="en block">~~~~~</p>
                <p>Manifestation</p>
            </td>
            <td>
                <p class="en block">has alternate (has alternate)</p>
                <p class="en block">~~~~~</p>
                <p>a pour présentation alternative (a pour présentation alternative)</p>
            </td>
            <td>
                <p class="en block">Manifestation</p>
                <p class="en block">~~~~~</p>
                <p>Manifestation</p>
            </td>
            <td>
                <p class="en block">This relationship involves <em>manifestations</em> that effectively serve as alternatives for each other</p>
                <p class="en block">~~~~~</p>
                <p>Cette relation implique deux 
                    <code class="language-plaintext highlighter-rouge">LRM-E4_Manifestation</code>
                    pouvant être utilisées l’une à la place de l’autre.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F3 Manifestation. R78 has alternate: F3 Manifestation</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F3_Manifestation</code>. 
                    <code class="language-plaintext highlighter-rouge">R78_a_pour_présentation_alternative</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F3_Manifestation</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-R30</p>
            </td>
            <td>
                <p class="en block">Agent</p>
                <p class="en block">~~~~~</p>
                <p>Agent</p>
            </td>
            <td>
                <p class="en block">is member of (has member)</p>
                <p class="en block">~~~~~</p>
                <p>est membre de (a pour membre)</p>
            </td>
            <td>
                <p class="en block">Collective Agent</p>
                <p class="en block">~~~~~</p>
                <p>Agent collectif</p>
            </td>
            <td>
                <p class="en block">This is a relationship between an <em>agent</em> and a <em>collective agent</em> that the <em>agent</em> joined as a member</p>
                <p class="en block">~~~~~</p>
                <p>Cette relation est définie entre un 
                    <code class="language-plaintext highlighter-rouge">LRM-E6_Agent</code>
                    et un 
                    <code class="language-plaintext highlighter-rouge">LRM-E8-Agent_collectif</code>
                    que l’
                    <code class="language-plaintext highlighter-rouge">LRM-E6_Agent</code>
                    a rejoint en tant que membre.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">E39 Actor. P107i is current or former member of: F55 Collective Agent</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">E39_Actant</code>. 
                    <code class="language-plaintext highlighter-rouge">P107i_est_le_membre_actuel_ou_antérieur_de</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F55_Agent_collectif</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-R31</p>
            </td>
            <td>
                <p class="en block">Collective Agent</p>
                <p class="en block">~~~~~</p>
                <p>Agent collectif</p>
            </td>
            <td>
                <p class="en block">has part (is part of)</p>
                <p class="en block">~~~~~</p>
                <p>a pour partie (fait partie de)</p>
            </td>
            <td>
                <p class="en block">Collective Agent</p>
                <p class="en block">~~~~~</p>
                <p>Agent collectif</p>
            </td>
            <td>
                <p class="en block">This is a relationship between two <em>collective agents</em> where one is a component of the other </p>
                <p class="en block">~~~~~</p>
                <p>Cette relation est définie entre deux 
                    <code class="language-plaintext highlighter-rouge">LRM-E8-Agent_collectif</code>
                    dont l’un est une composante de l’autre.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F55 Collective Agent. P107 has current or former member: F55 Collective Agent</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F55_Agent_collectif</code>. 
                    <code class="language-plaintext highlighter-rouge">P107_a_pour_membre_actuel_ou_antérieur</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F55_Agent_collectif</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-R32</p>
            </td>
            <td>
                <p class="en block">Collective Agent</p>
                <p class="en block">~~~~~</p>
                <p>Agent collectif</p>
            </td>
            <td>
                <p class="en block">precedes (succeeds)</p>
                <p class="en block">~~~~~</p>
                <p>précède (succède à)</p>
            </td>
            <td>
                <p class="en block">Collective Agent</p>
                <p class="en block">~~~~~</p>
                <p>Agent collectif</p>
            </td>
            <td>
                <p class="en block">This is a relationship between two <em>collective agent</em> s where the first was transformed into the second</p>
                <p class="en block">~~~~~</p>
                <p>Cette relation est définie entre deux 
                    <code class="language-plaintext highlighter-rouge">LRM-E8-Agent_collectif</code>
                    dont le premier a été remplacé par le second.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">F55 Collective Agent. P151i participated in: E66 Formation. P151 was formed from: F55 Collective Agent</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">F55_Agent_collectif</code>. 
                    <code class="language-plaintext highlighter-rouge">P151i_a_participé_à</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E66_Formation</code>
                    . 
                    <code class="language-plaintext highlighter-rouge">P151_a_été_formé_à_partir_de</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">F55_Agent_collectif</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-R33</p>
            </td>
            <td>
                <p class="en block">Res</p>
                <p class="en block">~~~~~</p>
                <p>Res</p>
            </td>
            <td>
                <p class="en block">has association with (is associated with)</p>
                <p class="en block">~~~~~</p>
                <p>a pour lieu associé (est associé à)</p>
            </td>
            <td>
                <p class="en block">Place</p>
                <p class="en block">~~~~~</p>
                <p>Lieu</p>
            </td>
            <td>
                <p class="en block">This relationship links any entity with a given extent of space</p>
                <p class="en block">~~~~~</p>
                <p>Cette relation relie n’importe quelle entité à une étendue spatiale donnée.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">no mapping (too broad), use specific properties</p>
                <p class="en block">~~~~~</p>
                <p>Il n’y a pas de mise en correspondance spécifique en raison de l’application élargie de la relation, il faut donc utiliser des propriétés spécifiques. </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-R34</p>
            </td>
            <td>
                <p class="en block">Place</p>
                <p class="en block">~~~~~</p>
                <p>Lieu</p>
            </td>
            <td>
                <p class="en block">has part (is part of)</p>
                <p class="en block">~~~~~</p>
                <p>a pour partie (fait partie de)</p>
            </td>
            <td>
                <p class="en block">Place</p>
                <p class="en block">~~~~~</p>
                <p>Lieu</p>
            </td>
            <td>
                <p class="en block">This is a relationship between two <em>places</em> where one is a component of the other</p>
                <p class="en block">~~~~~</p>
                <p>Cette relation est définie entre deux 
                    <code class="language-plaintext highlighter-rouge">LRM-E10_Lieu</code>
                    dont l’un est une partie constitutive de l’autre.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">E53 Place. P89i contains: E53 Place</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">E53_Lieu</code>. 
                    <code class="language-plaintext highlighter-rouge">P89i_contient</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E53_Lieu</code></p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-R35</p>
            </td>
            <td>
                <p class="en block">Res</p>
                <p class="en block">~~~~~</p>
                <p>Res</p>
            </td>
            <td>
                <p class="en block">has association with (is associated with)</p>
                <p class="en block">~~~~~</p>
                <p>a pour laps de temps associé (est associé à)</p>
            </td>
            <td>
                <p class="en block">Time-span</p>
                <p class="en block">~~~~~</p>
                <p>Laps de temps</p>
            </td>
            <td>
                <p class="en block">This relationship links any entity with a temporal extent</p>
                <p class="en block">~~~~~</p>
                <p>Cette relation relie n’importe quelle entité à une plage temporelle.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">no mapping (too broad), use specific properties</p>
                <p class="en block">~~~~~</p>
                <p>Il n’y a pas de mise en correspondance spécifique en raison de l’application élargie de la relation, il faut donc utiliser des propriétés spécifiques. </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>LRM-R36</p>
            </td>
            <td>
                <p class="en block">Time-span</p>
                <p class="en block">~~~~~</p>
                <p>Laps de temps</p>
            </td>
            <td>
                <p class="en block">has part (is part of)</p>
                <p class="en block">~~~~~</p>
                <p>a pour partie (fait partie de)</p>
            </td>
            <td>
                <p class="en block">Time-span</p>
                <p class="en block">~~~~~</p>
                <p>Laps de temps</p>
            </td>
            <td>
                <p class="en block">This is a relationship between two <em>time-spans</em> where one is a component of the other</p>
                <p class="en block">~~~~~</p>
                <p>Cette relation est définie entre deux 
                    <code class="language-plaintext highlighter-rouge">LRM-E11_Laps_de_temps</code>
                    dont l’un est une partie constitutive de l’autre.</p>
            </td>
            <td></td>
            <td>
                <p class="en block">E52 Time-Span. P86i contains: E52 Time-Span</p>
                <p class="en block">~~~~~</p>
                <p>
                    <code class="language-plaintext highlighter-rouge">E52_Intervalle_temporel</code>. 
                    <code class="language-plaintext highlighter-rouge">P86i_contient</code>
                     : 
                    <code class="language-plaintext highlighter-rouge">E52_Intervalle_temporel</code></p>
            </td>
        </tr>
        <tr>
            <th>
                <p>
                    <em>Note de traduction</em>
                </p>
            </th>
            <td colspan="5">
                <p>Le texte de ce tableau est adapté de la traduction en français du <em>Modèle conceptuel pour l’information bibliographique</em> de la Fédération internationale des associations et institutions de bibliothèques (IFLA LRM).</p>
            </td>
        </tr>
        <tr>
            <th>
                <p>
                    <em>Références</em>
                </p>
            </th>
            <td colspan="5">
                <p>Riva, Pat, Patrick Le Bœuf, et Maja Žumer. 2021. <em>Un modèle conceptuel pour l’information bibliographique</em> . Traduit par Aude Le Moullec-Rieu, Françoise Leresche, Frédéric Puyrenier, et Mélanie Roche. Committee Publications. La Haye, NL: Fédération internationale des associations et institutions de bibliothèques (IFLA).
                    <a href="https://repository.ifla.org/server/api/core/bitstreams/b395a0a0-c9b8-49c6-8919-9befda0c40ed/content">
                        <span class="underline"/></a>
                    <a href="https://repository.ifla.org/server/api/core/bitstreams/b395a0a0-c9b8-49c6-8919-9befda0c40ed/content">
                        <span class="underline">https://repository.ifla.org/server/api/core/bitstreams/b395a0a0-c9b8-49c6-8919-9befda0c40ed/content</span>
                    </a>.</p>
            </td>
        </tr>
    </tbody>
</table>

