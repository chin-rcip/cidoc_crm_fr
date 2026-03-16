---
layout: page
title: 4. Description du modèle
titleEn: 4. Description of the model - 4. Description du modèle
permalink: /lrmoo/v1.0/description-du-modele
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
<p>The CIDOC CRM is an ontology in the sense used in computer science. More specifically, the model is expressed in terms of the primitives of semantic data modelling. As such, it consists of:</p>
<ul><li><p>classes, which represent general notions in the domain of discourse, such as the CIDOC CRM class E21 Person which represents the notion of person;</p>
</li>
<li><p> properties, which represent the binary relations that link the individuals in the domain of discourse, such as the CIDOC CRM property <em>P152 has parent</em> linking a person to one of the person’s parents.</p>
</li>
<li><p>properties of properties (“.1 properties”), such as the property <em>P14.1 in the role of</em>, of the CIDOC CRM property <em>P14</em> <em>carried out by (performed)</em>.</p>
</li></ul>
<p>These .1 properties do not appear in the property hierarchy list, but are included as part of their base property declaration and are referred to in the class declarations. They all have the implicit quantification “many to many”.</p>
<p>In understanding the models, it is important to keep in mind that the classes and properties declared in the models are entity types, that is, types or categories of classes or properties. Individual entities are recorded as individual instances of the appropriate classes or properties.</p>
</td>
<td>
<p>Le <em>Modèle conceptuel de référence du Comité international pour la documentation du Conseil international des musées</em> (CIDOC CRM) est une ontologie (dans le sens informatique du terme). Plus spécifiquement, le CIDOC CRM est exprimé en utilisant les primitives de la modélisation sémantique de données. À ce titre, le modèle est constitué de : </p>
<ul><li><p><em>classes</em>, qui représentent des notions générales du domaine du discours comme la classe du CIDOC CRM <code class="language-plaintext highlighter-rouge">E21_Personne</code> qui représente la notion de personne ; </p>
</li>
<li><p><em>propriétés</em>, qui représentent les relations binaires liant les instances du domaine du discours, comme la propriété du CIDOC CRM <code class="language-plaintext highlighter-rouge">P152_a_pour_parent (est_le_parent_de)</code> qui relie une personne à l’un de ses parents ; </p>
</li>
<li><p><em>propriétés de propriétés</em>, les propriétés « .1 » comme la propriété <code class="language-plaintext highlighter-rouge">P14.1_dans_le_rôle_de</code> dérivée de la propriété du CIDOC CRM <code class="language-plaintext highlighter-rouge">P14_a_été_effectué_par (a_effectué)</code>.</p>
</li></ul>
<p>Celles-ci n’apparaissent pas dans la hiérarchie des propriétés ; elles sont plutôt incluses dans la déclaration de leur propriété source et mentionnées dans les déclarations de classe. Elles ont toutes la quantification implicite « plusieurs à plusieurs » (voir la section 4.4 « <a href="https://cidoc-crm-fr.info/lrmoo/v1.0/description-du-modele#quantificateurs-de-proprietes"><span class="underline">Quantificateurs de propriétés</span></a> »). </p>
<p>Il est important de prendre en considération que les classes et propriétés déclarées dans les modèles sont des types d’entités, c.-à-d. des catégories ou types de classes ou de propriétés qui s’appliquent à ces entités. Les entités elles-mêmes sont enregistrées comme des instances individuelles de leurs classes et propriétés respectives. </p>
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
<p>Cette traduction est tirée de la section « <a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction#application-formelle"><span class="underline">Application formelle</span></a> » de l’introduction du CIDOC CRM.</p>
</td>
</tr>
<tr>
<th style="width:15%"><p><em>Références</em></p>
</th>
<td colspan="1">
<p>CIDOC CRM Special Interest Group. « CIDOC CRM Version 7.1.3 ». Traduit par Frédéric Bricaud, Camille Crevier-Lalonde, Stephen Hart, Karine Léonard Brouillet, Marie-Elaine Mathieu, Philippe Michon, Marielle St-Germain, et Marie-Pier Blain. Traduction en français du CIDOC CRM, 23 août 2024.<a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline"> </span></a><a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline">https://cidoc-crm-fr.info/v7.1.3/information/introduction</span></a>.</p>
</td>
</tr>
</tbody>
</table>

<h2 id="caracteristiques-des-proprietes"><span class="en heading">4.1. Characteristics of Properties - </span>4.1. Caractéristiques des propriétés</h2>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>In mathematics and logic three features are used to characterize properties that have the same class as both domain and range. These are transitivity, symmetry, and reflexivity. Where applicable, the scope notes of properties explicitly state whether the property is transitive or not, symmetric or asymmetric, reflexive or irreflexive. The formal definitions of these terms is found in the following table.</p>
</td>
<td>
<p>Dans les domaines des mathématiques et de la logique, trois caractéristiques sont utilisées pour qualifier des propriétés qui ont une même classe pour leur domaine ainsi que pour leur portée. Ces caractéristiques sont la transitivité, la symétrie, et la réflexivité. Lorsque c’est pertinent, les notes d’application des propriétés statuent explicitement si la propriété est transitive ou non, symétrique ou asymétrique, ou réflexive ou non réflexive. Ces termes sont formellement définis dans le tableau ci-dessous. </p>
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

<p><em><span class="en">Table 1. Definitions of characteristics of properties - </span>Tableau 1 : Définitions des caractéristiques des propriétés</em></p>

<table class="original-table">
<colgroup>
<col style="width:15%">
</colgroup>
<tbody>
<tr>
<td>
<p class="en block">transitive</p>
<p class="en block">~~~~~</p>
<p>transitive</p>
</td>
<td>
<p class="en block">A property P is transitive if the domain and range is the same class and for all instances x, y, z of this class the following is the case: If x is related by P to y and y is related by P to z, then x is related by P to z. The intention of a property as described in the scope note will decide whether a property is transitive or not. For example, the property <em>P121 overlaps with</em> between instances of E53 Place is not transitive, while the property <em>P89 falls within (contains)</em> between instances of E53 Place and the property <em>P46 is composed of (forms part of)</em> between instances of E18 Physical Thing are both transitive.</p>
<p class="en block">~~~~~</p>
<p>Une propriété <code class="language-plaintext highlighter-rouge">P</code> est transitive si son domaine et sa portée sont la même classe, et que pour toutes les instances <code class="language-plaintext highlighter-rouge">x</code>, <code class="language-plaintext highlighter-rouge">y</code>, <code class="language-plaintext highlighter-rouge">z</code> de cette classe si <code class="language-plaintext highlighter-rouge">x</code> est relié par <code class="language-plaintext highlighter-rouge">P</code> à <code class="language-plaintext highlighter-rouge">y</code> et que <code class="language-plaintext highlighter-rouge">y</code> est relié par <code class="language-plaintext highlighter-rouge">P</code> à <code class="language-plaintext highlighter-rouge">z</code>, alors <code class="language-plaintext highlighter-rouge">x</code> est relié par <code class="language-plaintext highlighter-rouge">P</code> à <code class="language-plaintext highlighter-rouge">z</code>. L’intention de la propriété telle qu’elle est établie dans sa note d’application détermine si elle est transitive ou non. Par exemple, la propriété <code class="language-plaintext highlighter-rouge">P121_se_superpose_partiellement_à</code> entre des instances de <code class="language-plaintext highlighter-rouge">E53_Lieu</code> n’est pas transitive alors que la propriété <code class="language-plaintext highlighter-rouge">P89_s’insère_dans (contient)</code> entre des instances de <code class="language-plaintext highlighter-rouge">E53_Lieu</code> et la propriété <code class="language-plaintext highlighter-rouge">P46_est_composé_de (fait_partie_de)</code> entre des instances de <code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code> sont toutes deux transitives.</p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="0">
<p>Cette traduction est tirée de la définition miroir du terme « <a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction#terminologie-transitivite"><span class="underline">transitivité</span></a> » dans la section « <a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction#terminologie"><span class="underline">Terminologie</span></a> » de l’introduction du CIDOC CRM.</p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="0">
<p>CIDOC CRM Special Interest Group. « CIDOC CRM Version 7.1.3 ». Traduit par Frédéric Bricaud, Camille Crevier-Lalonde, Stephen Hart, Karine Léonard Brouillet, Marie-Elaine Mathieu, Philippe Michon, Marielle St-Germain, et Marie-Pier Blain. Traduction en français du CIDOC CRM, 23 août 2024.<a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline"> </span></a><a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline">https://cidoc-crm-fr.info/v7.1.3/information/introduction</span></a>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">symmetric</p>
<p class="en block">~~~~~</p>
<p>symétrique<em></em></p>
</td>
<td>
<p class="en block">A property P is symmetric if the domain and range are the same class and for all instances x, y of this class the following is the case: If x is related by P to y, then y is related by P to x. The intention of a property as described in the scope note will decide whether a property is symmetric or not. An example of a symmetric property is E53 Place. <em>P122 borders with</em>: E53 Place. The names of symmetric properties have no parenthetical form, because reading in the range-to-domain direction is the same as the domain-to-range reading.</p>
<p class="en block">~~~~~</p>
<p>Une propriété <code class="language-plaintext highlighter-rouge">P</code> est symétrique si son domaine et sa portée sont la même classe, et que pour toutes les instances <code class="language-plaintext highlighter-rouge">x, y</code> de cette classe si <code class="language-plaintext highlighter-rouge">x</code> est relié par <code class="language-plaintext highlighter-rouge">P</code> à <code class="language-plaintext highlighter-rouge">y</code>, alors <code class="language-plaintext highlighter-rouge">y</code> est relié par <code class="language-plaintext highlighter-rouge">P</code> à <code class="language-plaintext highlighter-rouge">x</code>. L’intention de la propriété (telle qu’elle est établie dans sa note d’application) détermine si elle est symétrique ou non. Un exemple de propriété symétrique est <code class="language-plaintext highlighter-rouge">E53_Lieu</code>. <code class="language-plaintext highlighter-rouge">P122_est_limitrophe_de</code> : <code class="language-plaintext highlighter-rouge">E53_Lieu</code>. Les noms de propriétés symétriques n’ont pas de forme parenthétique, car les lire depuis la portée vers le domaine revient au même que les lire depuis le domaine vers la portée. </p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="0">
<p>Cette traduction est tirée de la définition miroir du terme « <a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction#terminologie-symetrie"><span class="underline">symétrie</span></a> » dans la section « <a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction#terminologie"><span class="underline">Terminologie</span></a> » de l’introduction du CIDOC CRM.</p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="0">
<p>CIDOC CRM Special Interest Group. « CIDOC CRM Version 7.1.3 ». Traduit par Frédéric Bricaud, Camille Crevier-Lalonde, Stephen Hart, Karine Léonard Brouillet, Marie-Elaine Mathieu, Philippe Michon, Marielle St-Germain, et Marie-Pier Blain. Traduction en français du CIDOC CRM, 23 août 2024.<a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline"> </span></a><a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline">https://cidoc-crm-fr.info/v7.1.3/information/introduction</span></a>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">asymmetric</p>
<p class="en block">~~~~~</p>
<p>asymétrique</p>
</td>
<td>
<p class="en block">A property P is asymmetric if the domain and range are the same class and for all pairs of instances x, y of this class the following is the case: If x is related by P to y, then y is not related by P to x. In CIDOC CRM asymmetry is mostly used in properties denoting part-whole relationships, when the whole cannot be a part of itself. An example of such an asymmetric property is E18 Physical Thing. <em>P46 is composed of (forms part of)</em>: E18 Physical Thing. An asymmetric property is always also irreflexive.</p>
<p class="en block">~~~~~</p>
<p>Une propriété <code class="language-plaintext highlighter-rouge">P</code> est asymétrique si son domaine et sa portée sont la même classe, et que pour toutes les instances <code class="language-plaintext highlighter-rouge">x, y</code> de cette classe si <code class="language-plaintext highlighter-rouge">x</code> est relié par <code class="language-plaintext highlighter-rouge">P</code> à <code class="language-plaintext highlighter-rouge">y</code>, alors <code class="language-plaintext highlighter-rouge">y</code> n’est pas relié par <code class="language-plaintext highlighter-rouge">P</code> à <code class="language-plaintext highlighter-rouge">x</code>. </p>
<p>Dans le CIDOC CRM l’asymétrie est principalement utilisée dans des propriétés qui dénotent des relations entre des éléments et leurs ensembles lorsque l’ensemble ne peut pas constituer une part de lui-même. Un exemple de propriété asymétrique est <code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code>. <code class="language-plaintext highlighter-rouge">P46_est_composé_de (fait_partie_de)</code> : <code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code>. Une propriété asymétrique est toujours non réflexive.</p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="0">
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="0">
<p><em></em></p>
</td>
</tr>
<tr>
<td>
<p class="en block">reflexive</p>
<p class="en block">~~~~~</p>
<p>réflexive</p>
</td>
<td>
<p class="en block">A property P is reflexive if the domain and range are the same class and for all instances x of this class the following is the case: x is related by P to itself. The intention of a property as described in the scope note will decide whether a property is reflexive or not. An example of a reflexive property is E53 Place. <em>P89 falls within (contains)</em>: E53 Place.</p>
<p class="en block">~~~~~</p>
<p>Une propriété <code class="language-plaintext highlighter-rouge">P</code> est réflexive si son domaine et sa portée sont la même classe, et que pour toutes les instances <code class="language-plaintext highlighter-rouge">x</code> de cette classe <code class="language-plaintext highlighter-rouge">x</code> est relié à lui-même par <code class="language-plaintext highlighter-rouge">P</code>. L’intention de la propriété (telle qu’elle est établie dans sa note d’application) détermine si elle réflexive ou non. Un exemple de propriété réflexive est <code class="language-plaintext highlighter-rouge">E53_Lieu</code>. <code class="language-plaintext highlighter-rouge">P89_s’insère_dans (contient)</code> : <code class="language-plaintext highlighter-rouge">E53_Lieu</code>. </p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="0">
<p>Cette traduction est tirée de la définition miroir du terme « <a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction#terminologie-reflexivite"><span class="underline">réflexivité</span></a> » dans la section « <a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction#terminologie"><span class="underline">Terminologie</span></a> » de l’introduction du CIDOC CRM.</p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="0">
<p>CIDOC CRM Special Interest Group. « CIDOC CRM Version 7.1.3 ». Traduit par Frédéric Bricaud, Camille Crevier-Lalonde, Stephen Hart, Karine Léonard Brouillet, Marie-Elaine Mathieu, Philippe Michon, Marielle St-Germain, et Marie-Pier Blain. Traduction en français du CIDOC CRM, 23 août 2024.<a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline"> </span></a><a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline">https://cidoc-crm-fr.info/v7.1.3/information/introduction</span></a>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">irreflexive</p>
<p class="en block">~~~~~</p>
<p>non réflexive</p>
</td>
<td>
<p class="en block">A property P is irreflexive if the domain and range are the same class and for all instances x of this class the following is the case: x is not related by P to itself. An example of an irreflexive property is E33 Linguistic Object. <em>P73 has translation (is translation of)</em>: E33 Linguistic Object. A property that is asymmetric is always also irreflexive.</p>
<p class="en block">~~~~~</p>
<p>Une propriété <code class="language-plaintext highlighter-rouge">P</code> est non réflexive si son domaine et sa portée sont la même classe, et que pour toutes les instances <code class="language-plaintext highlighter-rouge">x</code> de cette classe <code class="language-plaintext highlighter-rouge">x</code> n’est pas relié à lui-même par <code class="language-plaintext highlighter-rouge">P</code>. Un exemple de propriété non réflexive est <code class="language-plaintext highlighter-rouge">E33_Objet_linguistique</code>. <code class="language-plaintext highlighter-rouge">P73_a_pour_traduction (est_traduction_de)</code> : <code class="language-plaintext highlighter-rouge">E33_Objet_linguistique</code>. Une propriété asymétrique est toujours non réflexive. </p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="0">
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="0">
<p><em></em></p>
</td>
</tr>
</tbody>
</table>

<h3 id="heritage"><span class="en heading">4.1.1. Inheritance - </span>4.1.1. Héritage</h3>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>Inheritance is a construct frequently used in modelling and the isA (inheritance) relationship is used to define one class as a more specialized version of another. A specialized class (subclass) implies a subset, since any instance of the subclass also counts as an instance of the class it inherits from (superclass). A property that is defined for a class will also apply on any of its subclasses. It is worth underlining that inheritance is a modelling construct, it is a relationship between types of things. CIDOC CRM, and its extensions, is formulated as a class system with inheritance. Property P with domain A and range B will also be a property between any possible subclasses of A and of B.</p>
</td>
<td>
<p>L’héritage est un construit couramment utilisé dans la modélisation où la relation <code class="language-plaintext highlighter-rouge">estUn</code> (héritage) est utilisée pour indiquer qu’une classe est une version spécialisée d’une autre. Une classe spécialisée (sous-classe) implique un sous-ensemble puisque toute instance de cette sous-classe est aussi une instance de la classe dont elle hérite (super-classe). Une propriété définie pour une classe s’applique aussi à ses sous-classes. </p>
<p>Il est important de souligner que l’héritage est un construit de modélisation, une relation entre des types de choses. Le CIDOC CRM ainsi que ses extensions est un système de classes qui inclut l’héritage. Ainsi, une propriété <code class="language-plaintext highlighter-rouge">P</code> ayant un domaine <code class="language-plaintext highlighter-rouge">A</code> et une portée <code class="language-plaintext highlighter-rouge">B</code> sera aussi une propriété valide entre des sous-classes de <code class="language-plaintext highlighter-rouge">A</code> et de <code class="language-plaintext highlighter-rouge">B</code>. </p>
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

<h3 id="raccourcis"><span class="en heading">4.1.2. Shortcuts - </span>4.1.2. Raccourcis</h3>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>Some properties are declared as shortcuts of longer, more comprehensively articulated paths that connect the same domain and range classes as the shortcut property via one or more intermediate classes. For example, the property E18 Physical Thing. <em>P52 has current owner (is current owner of):</em> E39 Actor, is a shortcut for a fully articulated path from E18 Physical Thing through E8 Acquisition to E39 Actor. We distinguish the following terms:</p>
<p><strong>Shortcut:</strong> An instance of the fully-articulated path always implies an instance of the shortcut property. However, the converse may not be true; an instance of the fully-articulated path cannot always be inferred from an instance of the shortcut property.</p>
<p><strong>Inverse shortcut:</strong> An instance of the shortcut property always implies an instance of the fully-articulated path. However, the converse may not be true; an instance of the shortcut property cannot always be inferred from an instance of the fully-articulated path.</p>
<p><strong>Strong shortcut:</strong> An instance of the fully-articulated path always implies an instance of the strong shortcut property and an instance of the fully-articulated path can always be inferred from an instance of the strong shortcut property.</p>
</td>
<td>
<p>Certaines propriétés sont déclarées à titre de raccourci de chemins sémantiques plus exhaustifs qui connectent les mêmes domaine et portée que la propriété « raccourci » par le biais d’une ou de plusieurs classes intermédiaires. Par exemple, <code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code>. <code class="language-plaintext highlighter-rouge">P52_a_pour_propriétaire_actuel (est_l’actant_propriétaire_actuel_de)</code> : <code class="language-plaintext highlighter-rouge">E39_Actant</code> est un raccourci du chemin sémantique depuis <code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code> via <code class="language-plaintext highlighter-rouge">E8_Acquisition</code> jusqu’à <code class="language-plaintext highlighter-rouge">E39_Actant</code>. Les termes suivants doivent donc être distingués :</p>
<p><strong>Raccourci :</strong> Une instance d’un chemin sémantique exhaustif implique toujours une instance de la propriété-raccourci. Par contre, le contraire n’est pas toujours vrai et une instance du chemin sémantique exhaustif ne peut pas toujours être inférée de l’instance de propriété-raccourci. </p>
<p><strong>Raccourci inverse :</strong> Une instance d’une propriété-raccourci implique toujours une instance du chemin sémantique exhaustif. Par contre, le contraire n’est pas toujours vrai et une instance de propriété-raccourci ne peut pas toujours être inférée de l’instance de son chemin sémantique exhaustif.</p>
<p><strong>Raccourci robuste :</strong> Une instance d’un chemin sémantique exhaustif implique toujours une instance de sa propriété-raccourci robuste, et une instance de son chemin sémantique exhaustif peut toujours être inférée d’une instance de propriété-raccourci robuste. </p>
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

<h2 id="apercu-du-modele"><span class="en heading">4.2. Overview of the Model - </span>4.2. Aperçu du modèle</h2>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>LRM<sub>OO</sub> declares 16 classes and 37 properties, in addition to those used from CIDOC CRM. In comparison, IFLA LRM has 11 entities, 37 attributes and 36 relationships.</p>
<p>The core of the model is the WEMI (Work, Expression, Manifestation, Item) classes which were first defined in FRBR, and the relationships linking them together. As an object-oriented model, LRM<sub>OO</sub> brings out the events that result in the creation of instances of the WEMI classes, using specific creation classes that are linked to the WEMI classes by specific properties. These creation classes are subclasses of the CIDOC CRM classes E65 Creation or E12 Production, and in turn both of these classes are subclasses of the basic E7 Activity class. Since instances of E39 Actor (to which the IFLA LRM entity LRM-E6 Agent is mapped) can <em>P14i perform</em> instances of E7 Activity, an agent can be linked to the creation or modification of any WEMI instance. This is shown in Illustration 1 below.</p>

<div class="mxgraph" style="max-width:100%;border:1px solid #cccccc;" data-mxgraph="{&quot;highlight&quot;:&quot;#0000ff&quot;,&quot;target&quot;:&quot;blank&quot;,&quot;nav&quot;:true,&quot;resize&quot;:true,&quot;toolbar&quot;:&quot;zoom layers lightbox&quot;,&quot;edit&quot;:&quot;_blank&quot;,&quot;xml&quot;:&quot;&lt;mxfile host=\&quot;app.diagrams.net\&quot; agent=\&quot;5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) draw.io/20.3.0 Chrome/104.0.5112.114 Electron/20.1.3 Safari/537.36\&quot; modified=\&quot;2026-02-09T20:45:59.187Z\&quot; version=\&quot;20.3.0\&quot; etag=\&quot;fSob3lqv2eBsrdea8mzJ\&quot; type=\&quot;device\&quot; pages=\&quot;6\&quot;&gt;&lt;diagram name=\&quot;1-ConnectionsClassesProprietesLRMooCIDOCCRM\&quot; id=\&quot;SHI43zq17c6qGugvLIqx\&quot;&gt;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&lt;/diagram&gt;&lt;/mxfile&gt;&quot;}"> </div>

<p><em>Illustration 1. LRM<sub>OO</sub> classes and properties and their connections to CIDOC CRM classes</em></p>
<p>Not illustrated in the diagram is that any E7 Activity can also be linked to a specific instance of E52 Place using the <em>P7 took place at (witnessed)</em> property or with an instance of E53 Time-span using the <em>P4 has time-span (is time-span of)</em> property.</p>
<p>The F27 Work Creation class in LRM<sub>OO</sub> comprises activities by which instances of F1 Work come into existence and can serve to document the period a work was coming into existence and the circumstances of it, when these are known. In many cases Work Creation coincides with the existence of the first known complete expression of that work. Similarly, the F28 Expression Creation class comprises activities that result in instances of F2 Expression coming into existence. An instance of expression is considered to be created when it is captured on a carrier other than the creator’s brain. Expression Creation necessarily requires creating a realisation (R19) of an instance of F1 Work in the instance of F2 Expression being created. The creation of an instance of expression coincides with the creation of the first instance of F3 Manifestation that <em>R4 embodies (is embodied in)</em> this instance of expression.</p>
<p>The F32 Item Production Event class comprises the activities that produce one or more instances of F5 Item, and requires the materialization (R27) of an instance of F3 Manifestation that each instance of F5 Item <em>R7 exemplifies (is exemplified by)</em>.</p>
<p>The F33 Reproduction Event class, a specialisation of the F30 Manifestation Creation class, can use as its source material either a specific instance of F5 Item using the <em>R29 reproduced object (was object reproduced by)</em> property or a specific instance of F3 Manifestation using <em>R30 reproduced publication (was publication reproduced by)</em> instead. In either case, a new instance of F3 Manifestation is created by the event.</p>
</td>
<td>
<p>LRM<sub>OO</sub> déclare 16 classes et 37 propriétés en plus de celles du CIDOC CRM, alors que le <em>Modèle conceptuel pour l’information bibliographique</em> de la Fédération internationale des associations et institutions de bibliothèques (IFLA LRM) a 11 entités, 37 attributs, et 36 relations. </p>
<p>Le modèle est essentiellement composé de classes dites « WEMI » de l’acronyme « <em>work, expression, manifestation, item</em> » (œuvre, expression, manifestation, item), classes qui ont d’abord été définies ainsi que les relations les liant dans les <em>Fonctionnalités requises des notices bibliographiques </em>(FRBR). À titre de modèle orienté-objet, LRM<sub>OO</sub> s’attarde aux évènements qui résultent de la création d’instances des classes WEMI en utilisant des créations spécifiques de classes liées à ces classes WEMI par des propriétés particulières. Ces créations de classe sont des sous-classes des classes du CIDOC CRM <code class="language-plaintext highlighter-rouge">E12_Production</code> ou <code class="language-plaintext highlighter-rouge">E65_Création</code>, qui sont elles-mêmes des sous-classes de <code class="language-plaintext highlighter-rouge">E7_Activité</code>. Puisque les instances de <code class="language-plaintext highlighter-rouge">E39_Actant</code> – qui correspondent à l’entité IFLA LRM <code class="language-plaintext highlighter-rouge">LRM-E6_Agent</code> – peuvent performer (<code class="language-plaintext highlighter-rouge">P14i_a_effectué</code>) des instances de <code class="language-plaintext highlighter-rouge">E7_Activité</code>, un agent peut être lié à la création ou à la modification d’instances WEMI. Cela est illustré dans la figure 1 ci-dessous. </p>

<div class="mxgraph" style="max-width:100%;border:1px solid #cccccc;" data-mxgraph="{&quot;highlight&quot;:&quot;#0000ff&quot;,&quot;target&quot;:&quot;blank&quot;,&quot;nav&quot;:true,&quot;resize&quot;:true,&quot;toolbar&quot;:&quot;zoom layers lightbox&quot;,&quot;edit&quot;:&quot;_blank&quot;,&quot;xml&quot;:&quot;&lt;mxfile host=\&quot;app.diagrams.net\&quot; agent=\&quot;5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) draw.io/20.3.0 Chrome/104.0.5112.114 Electron/20.1.3 Safari/537.36\&quot; modified=\&quot;2026-02-09T20:45:59.187Z\&quot; version=\&quot;20.3.0\&quot; etag=\&quot;fSob3lqv2eBsrdea8mzJ\&quot; type=\&quot;device\&quot; pages=\&quot;6\&quot;&gt;&lt;diagram name=\&quot;1-LRMooConnectionToCIDOCCRM\&quot; id=\&quot;W1kl0TPtMKKERFrJc7qM\&quot;&gt;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&lt;/diagram&gt;&lt;/mxfile&gt;&quot;}"> </div>

<p><em>Figure 1 : Les connections des classes et propriétés du LRM</em><sub><em>OO</em></sub><em> aux classes du CIDOC CRM</em></p>
<p>Toute instance de <code class="language-plaintext highlighter-rouge">E7_Activité</code> peut en outre être liée à une instance spécifique de <code class="language-plaintext highlighter-rouge">E52_Intervalle_temporel</code> par le biais de la propriété <code class="language-plaintext highlighter-rouge">P7_a_eu_lieu_dans (a_été_témoin_de)</code> ou encore par une instance de <code class="language-plaintext highlighter-rouge">E53_Lieu</code> de concert avec la propriété <code class="language-plaintext highlighter-rouge">P4_a_pour_intervalle_temporel (est_l’intervalle_temporel_de)</code>. </p>
<p>Dans LRM<sub>OO</sub>, la classe <code class="language-plaintext highlighter-rouge">F27_Création_d’œuvre</code> comprend les activités par lesquelles des instances de <code class="language-plaintext highlighter-rouge">F1_Œuvre</code> ont vu le jour. Elles peuvent être utilisées pour documenter la période lors de laquelle une œuvre a été créée ainsi que les circonstances de cette création lorsque celles-ci sont connues. Dans beaucoup de cas, <code class="language-plaintext highlighter-rouge">F27_Création_d’œuvre</code> coïncide avec la première expression complète connue de l’œuvre en question. </p>
<p>De manière similaire, la classe <code class="language-plaintext highlighter-rouge">F28_Création_d’expression</code> comprend les activités dont résultent la venue au jour d’instances de <code class="language-plaintext highlighter-rouge">F2_Expression</code>. Une instance de <code class="language-plaintext highlighter-rouge">F2_Expression</code> est considérée être créée lorsqu’elle est incarnée par un support autre que le cerveau du créateur. La création d’une expression (<code class="language-plaintext highlighter-rouge">F28_Création_d’expression</code>) exige la création de la réalisation (<code class="language-plaintext highlighter-rouge">R19_a_créé_une_réalisation_de (a_été_réalisé_par)</code>) d’une instance de <code class="language-plaintext highlighter-rouge">F1_Œuvre</code> dans l’instance de <code class="language-plaintext highlighter-rouge">F2_Expression</code> créée. La création d’une instance de <code class="language-plaintext highlighter-rouge">F2_Expression</code> coïncide avec la création de la première instance de <code class="language-plaintext highlighter-rouge">F3_Manifestation</code> qui incarne (<code class="language-plaintext highlighter-rouge">R4_incarne (est_incarné_dans)</code>) cette instance de <code class="language-plaintext highlighter-rouge">F2_Expression</code>. </p>
<p>La classe <code class="language-plaintext highlighter-rouge">F32_Évènement_de_production_d’item</code> comprend les activités qui produisent une ou plusieurs instances de <code class="language-plaintext highlighter-rouge">F5_Item</code>. Elle exige la matérialisation (<code class="language-plaintext highlighter-rouge">R27_a_matérialisé (a_été_matérialisé_par)</code>) d’une instance de <code class="language-plaintext highlighter-rouge">F3_Manifestation</code> pour chaque item (<code class="language-plaintext highlighter-rouge">F5_Item</code>) qui l’exemplifie (<code class="language-plaintext highlighter-rouge">R7_exemplifie (est_exemplifié_par)</code>). </p>
<p>La classe <code class="language-plaintext highlighter-rouge">F33_Évènement_de_reproduction</code>, qui précise la classe <code class="language-plaintext highlighter-rouge">F30_Création_de_manifestation</code>, peut avoir comme source une instance spécifique de :</p>
<ul><li><p><code class="language-plaintext highlighter-rouge">F5_Item</code> de concert avec la propriété <code class="language-plaintext highlighter-rouge">R29_objet_reproduit (était_l’objet_reproduit_par)</code> ;</p>
</li>
<li><p><code class="language-plaintext highlighter-rouge">F3_Manifestation</code> de concert avec la propriété <code class="language-plaintext highlighter-rouge">R30_publication_reproduite (était_la_publication_reproduite_par)</code>.</p>
</li></ul>
<p>Dans les deux cas, une nouvelle instance de <code class="language-plaintext highlighter-rouge">F3_Manifestation</code> est créée par cet évènement (<code class="language-plaintext highlighter-rouge">F33_Évènement_de_reproduction</code>).</p>
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
<p>L’acronyme « WEMI » a été conservé ici car il est couramment utilisé par le milieu francophone. </p>
</td>
</tr>
<tr>
<th style="width:15%"><p><em>Références</em></p>
</th>
<td colspan="1">
<p>L’Infrastructure Numérique pour les données Culturelles dans le web Sémantique (LINCS). s. d. « WEMI | LINCS ». L’Infrastructure Numérique pour les données Culturelles dans le web Sémantique (LINCS). Consulté le 25 septembre 2024.<a href="https://lincsproject.ca/fr/docs/terms/wemi"><span class="underline"> </span></a><a href="https://lincsproject.ca/fr/docs/terms/wemi"><span class="underline">https://lincsproject.ca/fr/docs/terms/wemi</span></a>.</p>
<p>Riva, Pat, Patrick Le Bœuf, et Maja Žumer. 2021. <em>Un modèle conceptuel pour l’information bibliographique</em>. Traduit par Aude Le Moullec-Rieu, Françoise Leresche, Frédéric Puyrenier, et Mélanie Roche. Committee Publications. La Haye, NL: Fédération internationale des associations et institutions de bibliothèques (IFLA).<a href="https://repository.ifla.org/server/api/core/bitstreams/b395a0a0-c9b8-49c6-8919-9befda0c40ed/content"><span class="underline"> </span></a><a href="https://repository.ifla.org/server/api/core/bitstreams/b395a0a0-c9b8-49c6-8919-9befda0c40ed/content"><span class="underline">https://repository.ifla.org/server/api/core/bitstreams/b395a0a0-c9b8-49c6-8919-9befda0c40ed/content</span></a>.</p>
</td>
</tr>
</tbody>
</table>

<h3 id="lintegration-dexpressions-par-de-nouvelles-uvres"><span class="en heading">4.2.1. Incorporation of expressions into new works - </span>4.2.1. L’intégration d’expressions par de nouvelles œuvres</h3>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>Incorporation of pre-existing expressions into expressions of new works, although a frequent occurrence, is an aspect not included in the 2017 version of IFLA LRM. A proposed extension is under consideration. Examples include poems set to music or reusing music in new compositions. In LRM<sub>OO</sub> this is covered by two properties, <em>R74 uses expression of (has expression used in)</em> and <em>R75 incorporates (is incorporated in)</em>. The latter is a relationship between expressions, where the first expression includes as an integral part the second expression (which is a realisation of a different work). <em>R74 uses expression of</em> deals with the work level: all expressions of the first work will include some expression of the second. A well known example is Beethoven’s 9th Symphony, which uses an expression of ‘An die Freude’ by Friedrich Schiller (but it can be any language version).</p>
</td>
<td>
<p>L’intégration d’expressions pré-existantes par de nouvelles œuvres n’est pas traitée par le IFLA LRM bien que cela se produise couramment, raison pour laquelle IFLA considère actuellement la création d’une extension qui y soit dédiée. Cela permettrait de traiter certains cas comme des poèmes introduits dans une pièce musicale ou la réutilisation de musique dans de nouvelles compositions. </p>
<p>Dans LRM<sub>OO</sub>, ceci est traité par deux propriétés : <code class="language-plaintext highlighter-rouge">R74_utilise_l’expression_de (a_l’expression_utilisée_dans)</code> et <code class="language-plaintext highlighter-rouge">R75_incorpore (est_inclus_dans)</code>. Cette dernière établit une relation entre deux expressions de telle manière que la première expression comprend de manière intégrale la seconde (qui est dans ce cas de figure la réalisation d’une œuvre différente). Par exemple, la<em> 9. Sinfonie</em> de Ludwig van Beethoven reprend une expression de « An die Freude » de Friedrich von Schiller (n.b. cela s’appliquerait à ses versions en d’autres langues aussi). </p>
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
<p>Wikipédia. 2024a. « Ode à la joie ». Dans <em>Wikipédia</em>. San Francisco, US-CA: Wikipédia.<a href="https://fr.wikipedia.org/w/index.php?title=Ode_%C3%A0_la_joie&oldid=214242151"><span class="underline"> </span></a><a href="https://fr.wikipedia.org/w/index.php?title=Ode_%C3%A0_la_joie&oldid=214242151"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Ode_%C3%A0_la_joie&oldid=214242151</span></a>.</p>
<p>———. 2024b. « Symphonie n° 9 de Beethoven ». Dans <em>Wikipédia</em>. San Francisco, US-CA: Wikipédia.<a href="https://fr.wikipedia.org/w/index.php?title=Symphonie_no_9_de_Beethoven&oldid=218754304"><span class="underline"> </span></a><a href="https://fr.wikipedia.org/w/index.php?title=Symphonie_no_9_de_Beethoven&oldid=218754304"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Symphonie_no_9_de_Beethoven&oldid=218754304</span></a>.</p>
</td>
</tr>
</tbody>
</table>

<h3 id="les-expressions-et-attributs-representatifs"><span class="en heading">4.2.2. Representative attributes and representative expressions - </span>4.2.2. Les expressions et attributs représentatifs</h3>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>The work attribute LRM-E2-A2 Representative Expression Attribute was introduced in IFLA LRM to enable specifying essential characteristics of a work (such as original language, original instrumentation, intended audience), associated with the canonical expression, most often the one considered original. </p>
<p>In LRM<sub>OO</sub>, this is achieved with the property <em>R79 has representative expression attribute (is representative expression attribute of)</em> which associates an instance of F1 Work with an instance of F55 Type. The type system is suitably selected to cover the category of attribute which is of interest. In addition, the property <em>R73 takes representative attribute from (bears representative attribute for) </em>may be applied to associate a work with the representative expression, the one that the attributes are taken from.</p>
</td>
<td>
<p>Dans le IFLA LRM, l’attribut d’œuvre <code class="language-plaintext highlighter-rouge">LRM-E2-A2_attribut_d’expression_représentative</code> </p>
<p>a été introduit afin de spécifier des caractéristiques essentielles d’une œuvre qui sont associées à son expression canonique (laquelle est souvent considérée l’« originale »). Ces caractéristiques essentielles peuvent être, par exemple, la langue originale de l’œuvre, son audience cible, ou encore le choix original des instruments pour sa composition. </p>
<p>Dans LRM<sub>OO</sub>, cela est traité par l’usage de <code class="language-plaintext highlighter-rouge">R79_a_l’attribut_d’expression_représentatif (est_l’attribut_d’expression_représentatif_de)</code> pour associer une instance de <code class="language-plaintext highlighter-rouge">F1_Œuvre</code> à une instance de <code class="language-plaintext highlighter-rouge">E55_Type</code>. Il est important de sélectionner adéquatement le système de types afin de pouvoir traiter la catégorie d’attribut concernée. De plus, la propriété <code class="language-plaintext highlighter-rouge">R73_prend_l’attribut_représentatif_de (porte_l’attribut_représentatif_pour)</code> peut être utilisée pour associer une œuvre à l’expression représentative d’où sont tirés les attributs. </p>
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
<p>Riva, Pat, Patrick Le Bœuf, et Maja Žumer. 2021. <em>Un modèle conceptuel pour l’information bibliographique</em>. Traduit par Aude Le Moullec-Rieu, Françoise Leresche, Frédéric Puyrenier, et Mélanie Roche. Committee Publications. La Haye, NL: Fédération internationale des associations et institutions de bibliothèques (IFLA).<a href="https://repository.ifla.org/server/api/core/bitstreams/b395a0a0-c9b8-49c6-8919-9befda0c40ed/content"><span class="underline"> </span></a><a href="https://repository.ifla.org/server/api/core/bitstreams/b395a0a0-c9b8-49c6-8919-9befda0c40ed/content"><span class="underline">https://repository.ifla.org/server/api/core/bitstreams/b395a0a0-c9b8-49c6-8919-9befda0c40ed/content</span></a>.<em></em></p>
</td>
</tr>
</tbody>
</table>

<h3 id="proprietes-wemi"><span class="en heading">4.2.3. WEMI Properties - </span>4.2.3. Propriétés « WEMI »</h3>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>Some properties declared in LRM<sub>OO</sub> enable full mapping to IFLA LRM relationships. <em>R77 accompanies or complements (is accompanied or complemented by)</em> provides a mapping at a suitable level of granularity for the LRM-R20 accompanies/complements relationship between two works. <em>R68 is inspired by (is inspiration for)</em> serves as a direct equivalent of the IFLA LRM inspiration relationship LRM-R21 between two works. <em>R76 is derivative of (has derivative)</em> is declared as the equivalent to the IFLA LRM relationship LRM-R24. This property is connecting two expressions and it enables recording the exact derivation chain, when known. It is an important complement to the more general work-to-work derivation relationship, <em>R2 is derivative of (has derivative)</em>, which corresponds to the IFLA LRM transformation relationship LRM-R22.</p>
<p>The work-to-work property<em> R67 has part (forms part of)</em> is declared as the equivalent to IFLA LRM relationship LRM-R18. It allows modelling structural composition of works.</p>
<p>The symmetric property <em>R78 has alternate</em> provides an equivalent to the alternate relationship between manifestations, LRM-R29. These properties are summarized in Illustration 2.</p>

<div class="mxgraph" style="max-width:100%;border:1px solid #cccccc;" data-mxgraph="{&quot;highlight&quot;:&quot;#0000ff&quot;,&quot;target&quot;:&quot;blank&quot;,&quot;nav&quot;:true,&quot;resize&quot;:true,&quot;toolbar&quot;:&quot;zoom layers lightbox&quot;,&quot;edit&quot;:&quot;_blank&quot;,&quot;xml&quot;:&quot;&lt;mxfile host=\&quot;app.diagrams.net\&quot; agent=\&quot;5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) draw.io/20.3.0 Chrome/104.0.5112.114 Electron/20.1.3 Safari/537.36\&quot; modified=\&quot;2026-02-09T20:45:59.187Z\&quot; version=\&quot;20.3.0\&quot; etag=\&quot;fSob3lqv2eBsrdea8mzJ\&quot; type=\&quot;device\&quot; pages=\&quot;6\&quot;&gt;&lt;diagram name=\&quot;2-ProprietesClassesWEMI\&quot; id=\&quot;g6b7lt_Gj6UT_sBM0Mlg\&quot;&gt;7V1tc5s4EP41nvuUDIj3j02a9DrXdjrp3bS9Lx5isE2LkQ9wXvrrTwLJSKA4NkLEqZVpE7MgrRCPVvtIy3piXa4e3uXhevkRRnE6AcYiT6KJ9XYCgIn+I8E6XMScAF/xJflFhQaRbpIoLrgLSwjTMlnzwhnMsnhWcrIwz+E9f9kcpt1mfJmFadyRfk2icllLfcdo5H/GyWJJFZkGObMK6cVEUCzDCN4zIutqAtwJsB7CiXUxwTL+n3WZQ1g+exm9ePVwGae4Z2m/3nz64ATX5l/Ou9ug2HyybO8v/6xuzPXAtW57KY+zUqX29K3/6Sr999e39Y/7aOP9NN8/umfGntpJK4vykT7dMn5ABS6W5SpFAhN9DNNkkaHPaTzHZ+7ivEwQGt4Q8SqJIlz4Io+L5Fd4W1WEWnqxhklWVtByLibOW1zTpoRFDV9ccVHm8Gd8CVOYI0kGM1zLPEnTtghmJUG9aVa9g9t8F6Yb0mbUcyluWpTccTfj/rfBaKkqOKsVv0EXmGD90JzEg4DcSiOs7pW5xF2Qv5WepC3ACnppnoczvsDfyQoNZWB8iu/R7xu4CrNuO66TxSaP0XlQYQLX/DmH6zyZXFqTN0FZ/8HVRFVlszQsiurT16uP72mjEerqdvP3gsSd+3vpG6Zqb3NBa/e9CSSrAEKlFYgQmOMHxq7tNwybwfguhqu4zB/R8ZIxehYZgPeNgdxaParOJ8eP9bFHz4fEHC+2VR9kINC1xEbsWwLe/sDTAjDS8DZOa+XXJj536UwCsLnDWMMt++fmfX12WZbr6gFf446eI3iVYRaFeVScJ9kcImGGnul1mq/q3xCLrs3pV5j/rKtKk+zn32G+iEmHTW/TMGPODaUnrsc1aCQ77WYvDBCD3MPY5nCTRXFE7OH9MinjL+t6hNwjz4C3w6xlRK2bR9HMslvm0aXHRIc5AMyfBbvXBbtp82C3zOA8CDi8A4p/Kbz3Rz0qQYAvNU4sdPwxzJJ5jLBZJjAbZKhYU0GdKseMUCEdPIJTO0cR0KNI3SjyuFHkBK9tFO3nwFoEgdGizTr2hAfc5MTTECuwOzDCuugTh3m5hAuYhelVI71ogIb92+aaDxCuCbx+xGX5SHCE3V0efHEWvcGEq/FtkeQ6wf1dVVl7xJRVAbGvK+Wk5HGKRvEd36ki7PTD9mfs8zOA9buAZURUb1kZNVK2L2y3Nzmyo4Rv5OphjdhPMZT1B9N2hSpNf1cbtftt+c4Ra2ujP5bRt63uGDp6uy8aPBxxr3nZDSYeyNfAF2KKW2xmM4TBeJNjCVwk/22wOEK/3HCFn3N2W6yfoXly4/HGnCbFFOuehemUNAjmUzhXPjifU01HalKQ3kGXNZ0GcZ/RS3cOXkdi8Kqbo7uj/pA52uw3R7M2we7YBNEcjW42f/yGDs6Mc8PwqOQ7ntTPfcelgrcPZJqvjx7Zo89xnqDxG+dU+JCU36oKLMcnx3WFQWCT46Y+fPDIHLRrm23yu63fUndqyQB2GCq8v79BLJtxDgLT5CzbGTCGdEm6jgmtF87nRdzH2+ArRt5c+MhUS9Y8JRrbbTKdB9wOhbYIhe5/B09qA9ZLa7NltVWTVP2AhkAOfQxet6l064OioDZsff3Z5xrQ7SvbbDVAzqFmuu9gt5orexRM0p2wm19kf2KyXY1lJ6unp8bOJPShdmJE+yQzVB+2vDI7JULaN+xy9S7LjCYyP3AABzJlXFHaJI9HAPdDnKcRdzDijHMvMBwNuFYJEWm6qRz/iiFF9U5fjvhO9WFSE6MBKA/AvCNCbuRd9chG4TpP6eRITnN+sie38TW3GYrbbCU1FTFtS4bbVFWaHLlx/N+H3Bi4vzSZ2dvhJx04Dr0AZN/k6OhFd6PUosEEo9AL4HQb4LUaoOlFY0kCSWfPP0FnT9MLGcRRsq8hp/mFLOKE/ML18E1gJMFq16XmFmn9ZxUToy/LMFxvugyLKUJrqZ5adJRRToGk9ZAp92ASpkx4mKYSzJaGx3j9DbM4yO3fMhNU3DNZYlJV6PRhJsdKJRzP5l2yM7pJrKnFHvskNBxXAbWwgAJtiqgF8uxBwPzw0yHwgnPfHZFp4K5zfaP5cfn2tONDNetgjA6Q9AFN8aTxezuBmndIYc7SmDscc5p4CEuIiQdipmRnI8mKdZIPvavh+niLoa47jqa3jyMwD7FKbk+DnkUf6fndI1Em1lLzkIY4+ME2OIsSB1NqS8M4d21KZbZUhG5xvP4tDcf1fM6UWY6mIUDo3drGmDTEtu3XQkPsPV4FU8s7BBFcbTqtuQZjWBxZv0/8rs3v7fdpriGFOdmovZPEnOYawhJCruEhgBibMkmTAkcSpX/EzMtOQ/ENz55uiriYNnWPEki1Qy3lHZs6HwR303tFU5me5h7yeyBmJ/LJtJ3+WyBmNzbL8bd7Iq9/B6SiURb/Elw75l1TD9pbjopwp0O0WUCZNlsQniStTQ3RcboM0KKpsEYhOrbgjSFNdHbYMV/W6fRO0OnUREcKc7LxgyeJOU10hCXERKeK5prN4GodLrLqrYlNBbjVmgnpGojveFOiKUsQ/4D5tFITYw3FCLznefWU/zDX4R7JaY+w1+7OcWS8CA86dn6zg5H4zvbV+NfPSIxz4HuD2hwFloev+GU3PxS+PS5iIONqO9J31UWPYdR31UUMpN0AzUCYSYXP1Hy4N0gvPClvUDMQKcwBjbnDMacZiAzklGd3FLjLndSLDDD5xI7tfONNcA9dov9Oyu1Yrm+CjLZvInznnN6nXOB98kE+6wDbwuEhMRbYpHV0BheODyaTXXumHzy95PabBahvEbTG4BDOjTCtJa/XHnZV9aUXDBw8frMZzNcwH2hdwJnSCsMyHmMlQKRwG3PZObPbWh1ntKVcAtuXWRGwOFOIKLTdZ0VgZ7Dl4S+S9VlgOBgSPRwMx+E3PHVuvCcNckV0WzlSm7SpqhYBXlqho1IhU/ugChWudLRaC7pJcpUudjiCRL3u0MmumU78HdY7ZENLwSmG+en1DinMyYaWniTm9HqHsISYQKGSyhP0ee4LZOh7Uqlkij5wnEGlr4ViMUGlNH0eCQL1JIJKMb0KWMJmjplWQz3DQtMoMFs27UxHlXaavIOBeCNTHgcopTymoUShovDSnc9jJMojeESmpjw7pzrZIFNwigF/mvJIYU42yPQkMacpj7CEkPLgLSMmYyAOpYRFOFCmQKfK3VfVmW2zD6qkOUKFfMbA1snd32VoaHYjz26arH7NO3Ou1Z/eNKk52BDVXtk/jozfDMtdxs4K7jEZ4SzevXUMhd7/c8oDldQDVa9cuRoa8lzLBV9VqDZ/+d49qemJaK6SjUClyepPylXU9EQKc0Bj7nDMaXoiLCHekcFfKqs8o7lnjpjRvKOsV0Zz6zhj28DroiZs3BlhJpbExouYmfT6Gtk+zASoYybMdyPZvF+m9106Td46tAbXUw55oUoJC+FVuSSCW0XedHNoVYrojdNq56gZPJ7qJU1dRHOZbDCZdYqBPZq6SGFONpjsJDGnqYuwhIi6oJIpws9FlNyhjwv88QbnYGbYjBuukIN7kd0W66r+ugBSz5QRVLMm2dULhCf0pKoMgGGKoJWR0C1xPUPwJL+iLlRZPAJZEmrkGVPr5O5hf5zxaq+MNrUSIFrBwZSpQ2+U0xaamFbzlE4sUJs8EE9ZRWTYeDzFDoZWpSgaDIh7f6w8H+Je0jxFNHnIRoBZpxiNo3mKFOZkI8BOEnOap3SvzSHcZRBpK/JwvfwIIwyOq/8B&lt;/diagram&gt;&lt;/mxfile&gt;&quot;}"> </div>

<p><em>Illustration 2. Properties of WEM classes</em><em> </em></p>
</td>
<td>
<p>Certaines propriétés déclarées dans le LRM<sub>OO</sub> permettent une mise en correspondance complète avec les relations du IFLA LRM :</p>
<ul><li><p><code class="language-plaintext highlighter-rouge">R77_accompagne_ou_complémente (est_accompagné_ou_complémenté_de)</code> permet une équivalence à un degré de granularité adéquat pour l’utilisation de la relation <code class="language-plaintext highlighter-rouge">LRM-R20_accompagne/complète (est_accompagnée_par/est_complétée_par)</code> entre deux œuvres ;</p>
</li>
<li><p><code class="language-plaintext highlighter-rouge">R68_est_inspiré_de (est_source_d’inspiration_pour)</code> est équivalente à la relation <code class="language-plaintext highlighter-rouge">LRM-R21_est_source_d’inspiration_pour (inspirée_de)</code> entre deux œuvres ;</p>
</li>
<li><p><code class="language-plaintext highlighter-rouge">R76_est_dérivé_de (a_pour_dérivé)</code> est équivalente à la relation <code class="language-plaintext highlighter-rouge">LRM-R24_est_dérivée_de (a_pour_dérivation)</code> entre deux expressions, laquelle permet d’enregistrer un circuit de dérivation lorsqu’il est connu, un complément important à ;</p>
</li>
<li><p><code class="language-plaintext highlighter-rouge">R2_est_dérivé_de (a_pour_dérivé)</code> est équivalente à la relation de dérivation/transformation d’œuvre-à-œuvre <code class="language-plaintext highlighter-rouge">LRM-R22_est_une_transformation_de (a_été_transformée_en)</code> ; </p>
</li>
<li><p><code class="language-plaintext highlighter-rouge">R67_a_pour_élément (fait_partie_de)</code> est équivalente à la relation d’œuvre-à-œuvre <code class="language-plaintext highlighter-rouge">LRM-R18_a_pour_partie (fait_partie_de)</code> pour la modélisation des structures compositionnelles d’œuvres ;</p>
</li>
<li><p><code class="language-plaintext highlighter-rouge">R78_a_pour_présentation_alternative</code> (propriété symétrique) est équivalente à la relation alternative entre des manifestations <code class="language-plaintext highlighter-rouge">LRM-R29_a_pour_présentation_alternative</code>. </p>
</li></ul>
<p>Ces propriétés sont résumées dans la figure 2. </p>

<div class="mxgraph" style="max-width:100%;border:1px solid #cccccc;" data-mxgraph="{&quot;highlight&quot;:&quot;#0000ff&quot;,&quot;target&quot;:&quot;blank&quot;,&quot;nav&quot;:true,&quot;resize&quot;:true,&quot;toolbar&quot;:&quot;zoom layers lightbox&quot;,&quot;edit&quot;:&quot;_blank&quot;,&quot;xml&quot;:&quot;&lt;mxfile host=\&quot;app.diagrams.net\&quot; agent=\&quot;5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) draw.io/20.3.0 Chrome/104.0.5112.114 Electron/20.1.3 Safari/537.36\&quot; modified=\&quot;2026-02-09T20:45:59.187Z\&quot; version=\&quot;20.3.0\&quot; etag=\&quot;fSob3lqv2eBsrdea8mzJ\&quot; type=\&quot;device\&quot; pages=\&quot;6\&quot;&gt;&lt;diagram name=\&quot;2-PropertiesWEMIClasses\&quot; id=\&quot;u-hnEYLaX5a-InyjV6O9\&quot;&gt;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&lt;/diagram&gt;&lt;/mxfile&gt;&quot;}"> </div>

<p><em>Figure 2 : Propriétés des classes WEMI</em><em></em></p>
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
<p>Riva, Pat, Patrick Le Bœuf, et Maja Žumer. 2021. <em>Un modèle conceptuel pour l’information bibliographique</em>. Traduit par Aude Le Moullec-Rieu, Françoise Leresche, Frédéric Puyrenier, et Mélanie Roche. Committee Publications. La Haye, NL: Fédération internationale des associations et institutions de bibliothèques (IFLA).<a href="https://repository.ifla.org/server/api/core/bitstreams/b395a0a0-c9b8-49c6-8919-9befda0c40ed/content"><span class="underline"> </span></a><a href="https://repository.ifla.org/server/api/core/bitstreams/b395a0a0-c9b8-49c6-8919-9befda0c40ed/content"><span class="underline">https://repository.ifla.org/server/api/core/bitstreams/b395a0a0-c9b8-49c6-8919-9befda0c40ed/content</span></a>.<em></em></p>
</td>
</tr>
</tbody>
</table>

<h3 id="performances"><span class="en heading">4.2.4. Performances - </span>4.2.4. Performances</h3>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>LRM<sub>OO</sub> includes the class F31 Performance which comprises activities where an instance of F1 Work is presented or communicated directly or indirectly to an audience, such as a theatrical play or musical work. The main usage of this class is to enable more elaborate or explicit documentation of recorded performances. In LRM<sub>OO,</sub>, the property <em>R80 performed (is performed in)</em> is used to express the association between an instance of F31 Performance and the instance of F1 Work it conveys, and the property <em>R81 recorded (is recorded in)</em> allows for the documentation of the association that exists between the outcome of an instance of F28 Expression Creation which involved a performance recording, and the instance of F31 Performance that it is a recording of. This is shown below in Illustration 3. </p>

<div class="mxgraph" style="max-width:100%;border:1px solid #cccccc;" data-mxgraph="{&quot;highlight&quot;:&quot;#0000ff&quot;,&quot;target&quot;:&quot;blank&quot;,&quot;nav&quot;:true,&quot;resize&quot;:true,&quot;toolbar&quot;:&quot;zoom layers lightbox&quot;,&quot;edit&quot;:&quot;_blank&quot;,&quot;xml&quot;:&quot;&lt;mxfile host=\&quot;app.diagrams.net\&quot; agent=\&quot;5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) draw.io/20.3.0 Chrome/104.0.5112.114 Electron/20.1.3 Safari/537.36\&quot; modified=\&quot;2026-02-09T20:45:59.187Z\&quot; version=\&quot;20.3.0\&quot; etag=\&quot;fSob3lqv2eBsrdea8mzJ\&quot; type=\&quot;device\&quot; pages=\&quot;6\&quot;&gt;&lt;diagram name=\&quot;3-ReprésentationSymbolique\&quot; id=\&quot;3d-FAHp9C1czTHlYi9OH\&quot;&gt;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&lt;/diagram&gt;&lt;/mxfile&gt;&quot;}"> </div>

<p><em>Illustration 3. Model of F31 Performance and its use in expression creation for recordings </em></p>
<p>Additionally, more elaborated documentation of performances and the recording of performances can be achieved by using existing classes and properties in CIDOC CRM.<em></em></p>
</td>
<td>
<p>LRM<sub>OO</sub> inclut la classe <code class="language-plaintext highlighter-rouge">F31_Performance</code> qui comprend des activités lors desquelles une instance de <code class="language-plaintext highlighter-rouge">F1_Œuvre</code> est présentée ou communiquée – directement ou indirectement – à une audience (p. ex. des pièces de théâtre ou de musique). Cette classe est principalement utilisée afin de documenter de manière plus exhaustive ou explicite des performances enregistrées. Dans LRM<sub>OO</sub> :</p>
<ul><li><p><code class="language-plaintext highlighter-rouge">R80_a_interprété (est_interprété_dans)</code> permet d’exprimer l’association entre une instance de <code class="language-plaintext highlighter-rouge">F31_Performance</code> et l’instance de <code class="language-plaintext highlighter-rouge">F1_Œuvre</code> qu’elle communique ; </p>
</li>
<li><p><code class="language-plaintext highlighter-rouge">R81_enregistré (est_enregistré_dans)</code> permet de documenter l’association entre le résultat d’une instance de <code class="language-plaintext highlighter-rouge">F28_Création_d’expression</code> qui a impliqué l’enregistrement d’une performance et l’instance de <code class="language-plaintext highlighter-rouge">F31_Performance</code> enregistrée. </p>
</li></ul>
<p>Ceci est illustré dans la figure 3. </p>

<div class="mxgraph" style="max-width:100%;border:1px solid #cccccc;" data-mxgraph="{&quot;highlight&quot;:&quot;#0000ff&quot;,&quot;target&quot;:&quot;blank&quot;,&quot;nav&quot;:true,&quot;resize&quot;:true,&quot;toolbar&quot;:&quot;zoom layers lightbox&quot;,&quot;edit&quot;:&quot;_blank&quot;,&quot;xml&quot;:&quot;&lt;mxfile host=\&quot;app.diagrams.net\&quot; agent=\&quot;5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/537.36 (KHTML, like Gecko) draw.io/20.3.0 Chrome/104.0.5112.114 Electron/20.1.3 Safari/537.36\&quot; modified=\&quot;2026-02-09T20:45:59.187Z\&quot; version=\&quot;20.3.0\&quot; etag=\&quot;fSob3lqv2eBsrdea8mzJ\&quot; type=\&quot;device\&quot; pages=\&quot;6\&quot;&gt;&lt;diagram name=\&quot;3-ModelF31ExpressionCreationForRecordings\&quot; id=\&quot;5s3yMmu1LkPjZhGDHAWj\&quot;&gt;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&lt;/diagram&gt;&lt;/mxfile&gt;&quot;}"> </div>

<p><em>Figure 3 : Modélisation de l’utilisation de </em><code class="language-plaintext highlighter-rouge">F31_Performance</code><em> dans la création d’expressions lors d’enregistrements</em><em> </em></p>
<p>Il est possible de documenter plus exhaustivement les performances et leurs enregistrements grâce aux classes et propriétés existantes du CIDOC CRM. </p>
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

<h2 id="convention-dappellation"><span class="en heading">4.3. Naming Conventions - </span>4.3. Convention d’appellation</h2>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>LRM<sub>OO </sub>follows the naming conventions that have been applied throughout the CIDOC CRM family of models:</p>
<ul><li><p>Classes are identified by numbers preceded by the letter “F” and are named using noun phrases (nominal groups) using title case (initial capitals) as mnemonics for the content of the scope note. For example, F28 Expression Creation.</p>
</li>
<li><p>Properties are identified by numbers preceded by the letter “R,” and are named in both directions using verbal phrases in lower case as mnemonics for the content of the scope note. Properties with the character of states are named in the present tense, such as <em>R4 embodies</em>, whereas properties related to events are named in past tense, such as <em>R19 created a realisation of (was realised through)</em>.</p>
</li>
<li><p>Properties with similar semantic content operating between different domains and/or ranges are given the same verbal phrase as property label, however their names are unique due to their different property identifiers. For example, property <em>R16 created (was created by)</em> with domain F27 Work Creation and range F1 Work is has an identifier distinct from property <em>R17 created (was created by)</em> which has domain F28 Expression Creation and range F2 Expression.</p>
</li>
<li><p>The letters “F” and “R” were chosen during the development of FRBR<sub>OO</sub> and are to be understood as the first two letters of “FRBR”. This choice does not have any other meaning. They correspond respectively to the letters “E” and “P” in the CIDOC CRM naming conventions, where “E” historically meant “entity” (although the CIDOC CRM “entities” are now consistently called “classes”), and “P” means “property”.</p>
</li>
<li><p>Since LRM<sub>OO </sub>developed from FRBR<sub>OO, </sub>the same identifiers already assigned to classes and properties in FRBR<sub>OO </sub>are retained when those classes and properties continue to be defined in LRM<sub>OO</sub>. The identifiers for those classes and properties defined in FRBR<sub>OO</sub> that are deprecated in LRM<sub>OO</sub> are not reused, even though this results in gaps in the numbering. See section 10 for details of the evolution of all FRBR<sub>OO</sub> classes and properties in their transition to LRM<sub>OO</sub>. All classes and properties newly declared in LRM<sub>OO</sub> are assigned the next available identifier at the end of the sequence.</p>
</li>
<li><p>Property names should be read in their non-parenthetical form for the domain-to-range direction, and in parenthetical form for the range-to-domain direction. Reading a property in range-to-domain direction is equivalent to the inverse of that property. Following a current notational practice in OWL knowledge representation language, inverse properties are represented in this text by adding a letter “i” following the identification number and the parenthetical form of the full property name, such as <em>R1i has successor</em>, which is the inverse of <em>R1 is logical successor of</em>.</p>
</li>
<li><p>Properties with a range that is a subclass of CIDOC CRM class E59 Primitive Value (such as E1 CRM Entity. <em>P3 has note</em>: E62 String, for example) have no parenthetical name form, because reading the property name in the range-to-domain direction is generally not regarded as meaningful.</p>
</li>
<li><p>Properties that have identical domain and range may be symmetric or transitive. Instantiating a symmetric property implies that the same relation holds for both the domain-to-range and the range-to-domain directions. An example of this is E53 Place. <em>P122 borders with</em>: E53 Place. The names of symmetric properties have no parenthetical form, because reading in the range-to-domain direction is the same as the domain-to-range reading. Transitive asymmetric properties, such as E4 Period. <em>P9 consist of (forms part of)</em>: E4 Period, have a parenthetical form that relates to the meaning of the inverse direction.</p>
</li>
<li><p>Properties of properties are identified by “R”, followed by the number of the base property extended with “.1” and are named in one direction using a verbal phrase in lower case in the present tense. For example: the property <em>R2.1 has type</em> of the property <em>R2 is derivative of (has derivative).</em></p>
</li></ul>
</td>
<td>
<p>LRM<sub>OO</sub> suit la convention appliquée à l’ensemble des modèles du CIDOC CRM : </p>
<ul><li><p>Les classes sont identifiées par des numéros précédés de la lettre majuscule « F » (historiquement, les classes de CIDOC CRM étaient parfois appelées des « entités ») et leurs appellations sont constituées de groupes nominaux, les initiales des noms sont en majuscules. Par exemple, <code class="language-plaintext highlighter-rouge">F28_Création_d’expression</code> [n.d.t. dans la version en français, les classes sont toujours conjuguées au féminin singulier, p. ex. « une <code class="language-plaintext highlighter-rouge">E63_Début_d’existence</code> »]. </p>
</li>
<li><p>Les propriétés sont identifiées par des numéros précédés de la lettre majuscule « R » et leurs appellations sont bidirectionnelles et constituées de syntagmes verbaux dont tous les termes sont en minuscules. Les propriétés ayant les caractéristiques d’états utilisent le présent (p. ex. <code class="language-plaintext highlighter-rouge">R4_incarne (est_incarné_dans)</code>), alors que les propriétés liées à des évènements sont nommées au passé (p. ex. <code class="language-plaintext highlighter-rouge">R19_a_créé_une_réalisation_de (a_été_réalisé_par)</code>). [n.d.t. Dans la version en français, les propriétés sont toujours conjuguées au féminin singulier, p. ex. « une <code class="language-plaintext highlighter-rouge">P126_a_employé (a_été_employé_dans)</code> »]. </p>
</li>
<li><p>Les propriétés dont le contenu sémantique est similaire, mais dont les domaines et/ou les portées diffèrent ont les mêmes étiquettes tout en ayant des noms uniques du fait de leur identifiants de propriété. Par exemple, <code class="language-plaintext highlighter-rouge">R16_a_créé (a_été_créé_par)</code> en conjonction avec le domaine <code class="language-plaintext highlighter-rouge">F27_Création_d’œuvre</code> et la portée <code class="language-plaintext highlighter-rouge">F1_Œuvre</code> comporte un identifiant qui le distingue de la propriété <code class="language-plaintext highlighter-rouge">R17_a_créé (a_été_créé_par)</code> dont le domaine et la portée sont <code class="language-plaintext highlighter-rouge">F28_Création_d’expression</code> et <code class="language-plaintext highlighter-rouge">F2_Expression</code>. </p>
</li>
<li><p>Les lettres « F » et « R » ont été choisies lors du développement du <em>Fonctionnalités requises des notices bibliographiques, orientation objet </em>(FRBR<sub>OO</sub>) dont elles reprennent les deux premières lettres. Elles correspondent aux lettres « E » et « P » du CIDOC CRM où « E » représente les classes (autrefois appelées « entités ») et « P » représente les propriétés. </p>
</li>
<li><p>Puisque le LRM<sub>OO</sub> découle du FRBR<sub>OO</sub>, les identifiants assignés aux classes et propriétés du FRBR<sub>OO</sub> perdurent dans le LRM<sub>OO</sub> lorsque celles-ci y sont définies. Les identifiants de classes et de propriétés dépréciées ne sont pas réutilisés, et ce bien qu’il en résulte une discontinuité dans la suite des identifiants. Pour plus de détails sur l’évolution des classes et propriétés du FRBR<sub>OO</sub> dans le contexte de leur transition vers le LRM<sub>OO</sub>, voir la section 10 « <a href="https://cidoc-crm-fr.info/lrmoo/v1.0/migration-du-frbroo-vers-le-lrmoo"><span class="underline">Migration du FRBR</span></a><sub><a href="https://cidoc-crm-fr.info/lrmoo/v1.0/migration-du-frbroo-vers-le-lrmoo"><span class="underline">OO</span></a></sub><a href="https://cidoc-crm-fr.info/lrmoo/v1.0/migration-du-frbroo-vers-le-lrmoo"><span class="underline"> vers le LRM</span></a><sub><a href="https://cidoc-crm-fr.info/lrmoo/v1.0/migration-du-frbroo-vers-le-lrmoo"><span class="underline">OO</span></a></sub> ». Toutes les classes et propriétés nouvellement déclarées dans le LRM<sub>OO</sub> ont des identifiants suivant la séquence initiale de FRBR<sub>OO</sub>. </p>
</li>
<li><p>Les noms des propriétés devraient être lus dans leur forme non parenthétique lors d’une lecture dirigée depuis le domaine vers la portée, et dans leur forme parenthétique lors d’une lecture dirigée depuis la portée vers le domaine. Lire une propriété depuis la portée vers le domaine équivaut à l’inverse de cette propriété. En adéquation avec les pratiques de notation <a href="https://www.w3.org/OWL/"><span class="underline">OWL</span></a> actuelles, les propriétés inverses sont identifiées par l’ajout d’un « i » minuscule à la suite du numéro d’identification et de la forme parenthétique complète de la propriété (p. ex. <code class="language-plaintext highlighter-rouge">R1i_a_pour_successeur</code> est la propriété inverse de <code class="language-plaintext highlighter-rouge">R1_est_le_successeur_logique_de (a_pour_successeur)</code>). </p>
</li>
<li><p>Les propriétés dont la portée est une sous-classe de la classe du CIDOC CRM <code class="language-plaintext highlighter-rouge">E59_Valeur_primitive</code> (p. ex. <code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code>. <code class="language-plaintext highlighter-rouge">P3_a_pour_note</code> : <code class="language-plaintext highlighter-rouge">E62_Chaîne_de_caractères</code>) n’ont pas de forme appellative parenthétique, car la lecture depuis la portée vers le domaine n’est pas porteuse de sens. </p>
</li>
<li><p>Les propriétés qui ont des domaine et portée identiques peuvent être soit <a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction#terminologie-symetrie"><span class="underline">symétriques</span></a>, soit <a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction#terminologie-transitivite"><span class="underline">transitives</span></a>. Instancier une propriété symétrique implique que la relation est applicable lors de la lecture depuis le domaine vers la portée et depuis la portée vers le domaine (p. ex. <code class="language-plaintext highlighter-rouge">E53_Lieu</code>. <code class="language-plaintext highlighter-rouge">P122_est_limitrophe_de</code> : <code class="language-plaintext highlighter-rouge">E53_Lieu</code>). Les formes appellatives de propriétés symétriques n’ont pas de forme parenthétique, car la lecture depuis la portée vers le domaine équivaut à la lecture depuis le domaine vers la portée. Les propriétés transitives asymétriques (p. ex. <code class="language-plaintext highlighter-rouge">E4_Période</code>. <code class="language-plaintext highlighter-rouge">P9_comprend (fait_partie_de)</code> : <code class="language-plaintext highlighter-rouge">E4_Période</code>) ont une forme parenthétique qui porte sur la signification de leur direction inverse. </p>
</li>
<li><p>Les propriétés de propriétés sont identifiées par la lettre majuscule « R » suivi du numéro de la propriété source complété par « .1 » et sont nommées de manière unidirectionnelle à l’aide de syntagmes verbaux dont tous les termes sont en minuscules et au présent. Par exemple, la propriété <code class="language-plaintext highlighter-rouge">R2.1_a_pour_type</code> de la propriété <code class="language-plaintext highlighter-rouge">R2_est_dérivé_de (a_pour_dérivé)</code>.</p>
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
<p>Le terme « naming convention » est parfois traduit par « convention d’appellation » ou « convention de nommage » ; le terme « convention d’appellation » a été privilégié, car il semble davantage utilisé de manière générale (après avoir fait une brève recherche en ligne), qu’il est entériné par Termium et qu’il a été utilisé dans les traduction du CIDOC CRM effectuées par la Traduction en français du CIDOC CRM. </p>
<p>Cette traduction est adaptée de la définition miroir de la section « <a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction#convention-dappellation"><span class="underline">Convention d’appellation</span></a> » du CIDOC CRM.</p>
</td>
</tr>
<tr>
<th style="width:15%"><p><em>Références</em></p>
</th>
<td colspan="1">
<p>CIDOC CRM Special Interest Group. « CIDOC CRM Version 7.1.3 ». Traduit par Frédéric Bricaud, Camille Crevier-Lalonde, Stephen Hart, Karine Léonard Brouillet, Marie-Elaine Mathieu, Philippe Michon, Marielle St-Germain, et Marie-Pier Blain. Traduction en français du CIDOC CRM, 23 août 2024.<a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline"> </span></a><a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline">https://cidoc-crm-fr.info/v7.1.3/information/introduction</span></a>.</p>
<p>OWL Working Group. « OWL - Semantic Web Standards ». Ontologie. Cambridge, USA-MA: World Wide Web Consortium (W3C), 11 décembre 2012.<a href="https://www.w3.org/OWL/"><span class="underline"> </span></a><a href="https://www.w3.org/OWL/"><span class="underline">https://www.w3.org/OWL/</span></a>.</p>
<p>Termium. « Convention Appellation Courriels ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-eng.html?lang=eng&i=1&index=frt&srchtxt=CONVENTION%20APPELLATION%20COURRIELS"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-eng.html?lang=eng&i=1&index=frt&srchtxt=CONVENTION%20APPELLATION%20COURRIELS"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-eng.html?lang=eng&i=1&index=frt&srchtxt=CONVENTION%20APPELLATION%20COURRIELS</span></a>.</p>
</td>
</tr>
</tbody>
</table>

<h2 id="quantificateurs-de-proprietes"><span class="en heading">4.4. Property Quantifiers - </span>4.4. Quantificateurs de propriétés</h2>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>Quantifiers for properties are provided for the purpose of semantic clarification only, and should <strong>not</strong> be treated as implementation recommendations. Therefore, the term “cardinality constraints” is avoided here, as it typically pertains to implementations.</p>
<p>The following table lists all possible property quantifiers occurring in the CIDOC CRM family of models by their notation, together with an explanation in plain words. For optimal clarity, two widely accepted notations are used redundantly in this document, a verbal and a numeric one. The verbal notation uses phrases such as “one to many”, and the numeric one, expressions such as “(0,n:0,1)”. While the terms “one”, “many” and “necessary” are quite intuitive, the term “dependent” denotes a situation where a range instance cannot exist without an instance of the respective property. In other words, the property is “necessary” for its range (Meghini & Doerr 2018).</p>
</td>
<td>
<p>Les quantificateurs des propriétés sont présentés ici aux fins de clarification sémantique seulement et ne devraient <strong>pas</strong> être considérés comme des recommandations d’implémentation. La question des contraintes de cardinalité, qui précise les principes de généralisation d’une classe, porte généralement sur les implémentations d’un système [n.d.t. plutôt que sur sa conception], de sorte qu’il n’en est pas exhaustivement question ici et que l’expression « contraintes de cardinalité » n’est pas préconisée. </p>
<p>Le tableau suivant énumère les quantificateurs de propriété utilisés dans ce document (dans l’ordre de leur notation) ainsi qu’une explication en langage naturel de chacun d’entre eux. Les notations verbale et numérique sont juxtaposées dans ce document aux fins de clarté : la notation verbale utilise des syntagmes tels que « un à plusieurs » alors que la notation numérique utilise des expressions telles que « (0,n:0,1) ». Les termes « un », « plusieurs » et « nécessaire » [n.d.t. revêtent leur sens habituel et] intuitif ; le terme « dépendant » indique une situation où une instance de la portée d’une propriété ne peut pas exister sans une instance de cette propriété elle-même. En d’autres termes, la propriété est « nécessaire » à sa portée (Meghini & Doerr, 2018).</p>
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
<p>Certains paragraphes ont été édités dans la version en français aux fins de compréhension. Les sections concernées sont indiquées par la mention [n.d.t. texte concerné]. </p>
<p>Une contrainte de cardinalité précise si une entité « parent » peut appartenir à plusieurs entités « enfants » (principe du recouvrement ou <em>overlapping</em>) ou à un seul (principe de la disjonction). </p>
<p>Cette traduction est tirée de la définition miroir de la section « <a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction#quantificateurs-de-proprietes"><span class="underline">Quantificateurs de propriétés</span></a> » du CIDOC CRM.</p>
</td>
</tr>
<tr>
<th style="width:15%"><p><em>Références</em></p>
</th>
<td colspan="1">
<p>CIDOC CRM Special Interest Group. « CIDOC CRM Version 7.1.3 ». Traduit par Frédéric Bricaud, Camille Crevier-Lalonde, Stephen Hart, Karine Léonard Brouillet, Marie-Elaine Mathieu, Philippe Michon, Marielle St-Germain, et Marie-Pier Blain. Traduction en français du CIDOC CRM, 23 août 2024.<a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline"> </span></a><a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline">https://cidoc-crm-fr.info/v7.1.3/information/introduction</span></a>.</p>
<p>Termium. « cardinalité ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=cardinalit%C3%A9&index=frt&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=cardinalit%C3%A9&index=frt&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=cardinalit%C3%A9&index=frt&codom2nd_wet=1#resultrecs</span></a>.</p>
</td>
</tr>
</tbody>
</table>

<p><em><span class="en">Table 2. Property quantifiers and their definitions - </span>Tableau 2 : Les quantificateurs de propriétés et leurs définitions</em></p>

<table class="original-table">
<colgroup>
<col style="width:15%">
</colgroup>
<tbody>
<tr>
<td>
<p class="en block"><strong>many to many (0,n:0,n)</strong></p>
<p class="en block">~~~~~</p>
<p><strong>plusieurs à plusieurs</strong></p>
<p><strong>(0,n:0,n)</strong></p>
</td>
<td>
<p class="en block">Unconstrained: an individual domain instance and range instance of this property can have zero, one, or more instances of the property. In other words, the property is optional and repeatable for its domain and range. </p>
<p class="en block">~~~~~</p>
<p>Illimité : une instance du domaine et une instance de la portée de cette propriété peuvent n’avoir aucune, une ou plusieurs instances de la propriété. En d’autres termes, la propriété est optionnelle et répétable [n.d.t. c.-à-d. qu’une même propriété peut être utilisée à plusieurs reprises avec de mêmes instances de] son domaine et de sa portée. </p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="0">
<p>Une propriété répétable est une propriété pouvant apparaître plus d’une fois dans un enregistrement avec le(s) même(s) domaine et/ou portée. </p>
<p>Cette traduction est tirée de la définition miroir de la section « <a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction#quantificateurs-de-proprietes"><span class="underline">Quantificateurs de propriétés</span></a> » du CIDOC CRM.</p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="0">
<p>CIDOC CRM Special Interest Group. « CIDOC CRM Version 7.1.3 ». Traduit par Frédéric Bricaud, Camille Crevier-Lalonde, Stephen Hart, Karine Léonard Brouillet, Marie-Elaine Mathieu, Philippe Michon, Marielle St-Germain, et Marie-Pier Blain. Traduction en français du CIDOC CRM, 23 août 2024.<a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline"> </span></a><a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline">https://cidoc-crm-fr.info/v7.1.3/information/introduction</span></a>.</p>
<p>Termium. « répétable ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE</span></a>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block"><strong>one to many</strong></p>
<p class="en block"><strong>(0,n:0,1)</strong></p>
<p class="en block">~~~~~</p>
<p><strong>un à plusieurs</strong></p>
<p><strong>(0,n:0,1)</strong></p>
</td>
<td>
<p class="en block">An individual domain instance of this property can have zero, one, or more instances of the property, but an individual range instance cannot be referenced by more than one instance of this property. In other words, the property is optional for its domain and range, but repeatable for its domain only. This situation is sometimes called a “fan-out”.</p>
<p class="en block">~~~~~</p>
<p>Une instance individuelle du domaine de cette propriété peut n’avoir aucune, une ou plusieurs instance(s) de la propriété, mais une instance individuelle de sa portée ne peut pas faire l’objet d’une référence par plus d’une instance de cette même propriété. En d’autres termes, le domaine et la portée de la propriété sont optionnels, mais seul son domaine est répétable [n.d.t. c.-à-d. qu’une même propriété peut être utilisée à plusieurs reprises avec une même instance de son domaine]. Cette situation est parfois qualifiée de « sortance ». </p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="0">
<p>Une propriété répétable est une propriété pouvant apparaître plus d’une fois dans un enregistrement avec le(s) même(s) domaine et/ou portée. </p>
<p>Une recherche sommaire indique que le terme « fan-out » est surtout usité dans le domaine des circuits booléens et de l’intelligence artificielle, où il est parfois question d’arité sortante ou de sortance. </p>
<p>Cette traduction est tirée de la définition miroir de la section « <a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction#quantificateurs-de-proprietes"><span class="underline">Quantificateurs de propriétés</span></a> » du CIDOC CRM.</p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="0">
<p>CIDOC CRM Special Interest Group. « CIDOC CRM Version 7.1.3 ». Traduit par Frédéric Bricaud, Camille Crevier-Lalonde, Stephen Hart, Karine Léonard Brouillet, Marie-Elaine Mathieu, Philippe Michon, Marielle St-Germain, et Marie-Pier Blain. Traduction en français du CIDOC CRM, 23 août 2024.<a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline"> </span></a><a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline">https://cidoc-crm-fr.info/v7.1.3/information/introduction</span></a>.</p>
<p>Termium. « fan-out ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-out&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-out&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-out&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
<p>———. « répétable ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE</span></a>.</p>
<p>Wikipédia. « Fan-out ». Dans <em>Wikipédia</em>. San Francisco, US-CA: Wikipédia, 11 novembre 2020.<a href="https://fr.wikipedia.org/w/index.php?title=Fan-out&oldid=176479075"><span class="underline"> </span></a><a href="https://fr.wikipedia.org/w/index.php?title=Fan-out&oldid=176479075"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Fan-out&oldid=176479075</span></a>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block"><strong>many to one</strong></p>
<p class="en block"><strong>(0,1:0,n)</strong></p>
<p class="en block">~~~~~</p>
<p><strong>plusieurs à un</strong></p>
<p><strong>(0,1:0,n)</strong></p>
</td>
<td>
<p class="en block">An individual domain instance of this property can have zero or one instance of the property, but an individual range instance can be referenced by zero, one, or more instances of the property. In other words, the property is optional for its domain and range, but repeatable for its range only. This situation is sometimes called a “fan-in”.</p>
<p class="en block">~~~~~</p>
<p>Une instance du domaine de cette propriété peut n’avoir aucune ou une seule instance de la propriété, mais une instance de sa portée peut être référencée par aucune, une ou plusieurs instances de la même propriété. En d’autres termes, le domaine et la portée de la propriété sont optionnels, mais seule sa portée est répétable [n.d.t. c.-à-d. qu’une même propriété peut être utilisée à plusieurs reprises avec une même instance de sa portée]. Cette situation est parfois qualifiée d’« entrance ». </p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="0">
<p>Une propriété répétable est une propriété pouvant apparaître plus d’une fois dans un enregistrement avec le(s) même(s) domaine et/ou portée. </p>
<p>Une recherche sommaire indique que le terme « fan-in » est surtout usité dans le domaine des circuits booléens et de l’intelligence artificielle où il est parfois question d’arité entrante ou d’entrance. </p>
<p>Cette traduction est tirée de la définition miroir de la section « <a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction#quantificateurs-de-proprietes"><span class="underline">Quantificateurs de propriétés</span></a> » du CIDOC CRM.</p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="0">
<p>CIDOC CRM Special Interest Group. « CIDOC CRM Version 7.1.3 ». Traduit par Frédéric Bricaud, Camille Crevier-Lalonde, Stephen Hart, Karine Léonard Brouillet, Marie-Elaine Mathieu, Philippe Michon, Marielle St-Germain, et Marie-Pier Blain. Traduction en français du CIDOC CRM, 23 août 2024.<a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline"> </span></a><a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline">https://cidoc-crm-fr.info/v7.1.3/information/introduction</span></a>.</p>
<p>Termium. « fan-in ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
<p>———. « répétable ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE</span></a>.</p>
<p>Wikipédia. « Fan-in ». Dans <em>Wikipédia</em>. San Francisco, US-CA: Wikipédia, 11 novembre 2020.<a href="https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056"><span class="underline"> </span></a><a href="https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056</span></a>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block"><strong>many to many, necessary (1,n:0,n)</strong></p>
<p class="en block">~~~~~</p>
<p><strong>plusieurs à plusieurs, nécessaire</strong></p>
<p><strong>(1,n:0,n)</strong></p>
</td>
<td>
<p class="en block">An individual domain instance of this property can have one or more instances of this property, but an individual range instance can have zero, one, or more instances of the property. In other words, the property is necessary and repeatable for its domain, and optional and repeatable for its range. </p>
<p class="en block">~~~~~</p>
<p>Une instance individuelle du domaine de cette propriété peut avoir une ou plusieurs instance(s) de cette propriété, mais une instance individuelle de sa portée peut n’avoir aucune, une ou plusieurs instances de la même propriété. En d’autres termes, le domaine de la propriété est nécessaire et répétable [n.d.t. c.-à-d. qu’une même propriété peut être utilisée à plusieurs reprises avec une même instance de son domaine] alors que sa portée est optionnelle et répétable [n.d.t. c.-à-d. qu’une même propriété peut être utilisée à plusieurs reprises avec une même instance de sa portée]. </p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="0">
<p>Cette traduction est tirée de la définition miroir de la section « <a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction#quantificateurs-de-proprietes"><span class="underline">Quantificateurs de propriétés</span></a> » du CIDOC CRM.</p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="0">
<p>CIDOC CRM Special Interest Group. « CIDOC CRM Version 7.1.3 ». Traduit par Frédéric Bricaud, Camille Crevier-Lalonde, Stephen Hart, Karine Léonard Brouillet, Marie-Elaine Mathieu, Philippe Michon, Marielle St-Germain, et Marie-Pier Blain. Traduction en français du CIDOC CRM, 23 août 2024.<a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline"> </span></a><a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline">https://cidoc-crm-fr.info/v7.1.3/information/introduction</span></a>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block"><strong>one to many, necessary </strong></p>
<p class="en block"><strong>(1,n:0,1)</strong></p>
<p class="en block">~~~~~</p>
<p><strong>un à plusieurs, nécessaire</strong></p>
<p><strong>(1,n:0,1)</strong></p>
</td>
<td>
<p class="en block">An individual domain instance of this property can have one or more instances of the property, but an individual range instance cannot be referenced by more than one instance of the property. In other words, the property is necessary and repeatable for its domain, and optional but not repeatable for its range. This situation is sometimes called a “fan-out”.</p>
<p class="en block">~~~~~</p>
<p>Une instance individuelle du domaine de cette propriété peut n’avoir qu’une seule ou plusieurs instance(s) de la propriété, mais une instance individuelle de sa portée ne peut pas être référencée par plus d’une instance de la même propriété. En d’autres termes, le domaine de la propriété est nécessaire et répétable [n.d.t. c.-à-d. qu’une même propriété peut être utilisée à plusieurs reprises avec une même instance de son domaine], mais sa portée est optionnelle. Dans certains contextes, cette situation est qualifiée de « sortance ».</p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="0">
<p>Une propriété répétable est une propriété pouvant apparaître plus d’une fois dans un enregistrement avec le(s) même(s) domaine et/ou portée. </p>
<p>Une recherche sommaire indique que le terme « fan-out » est surtout usité dans le domaine des circuits booléens et de l’intelligence artificielle, où il est parfois question d’arité sortante ou de sortance. </p>
<p>Cette traduction est tirée de la définition miroir de la section « <a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction#quantificateurs-de-proprietes"><span class="underline">Quantificateurs de propriétés</span></a> » du CIDOC CRM.</p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="0">
<p>CIDOC CRM Special Interest Group. « CIDOC CRM Version 7.1.3 ». Traduit par Frédéric Bricaud, Camille Crevier-Lalonde, Stephen Hart, Karine Léonard Brouillet, Marie-Elaine Mathieu, Philippe Michon, Marielle St-Germain, et Marie-Pier Blain. Traduction en français du CIDOC CRM, 23 août 2024.<a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline"> </span></a><a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline">https://cidoc-crm-fr.info/v7.1.3/information/introduction</span></a>.</p>
<p>Termium. « fan-out ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-out&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-out&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-out&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
<p>———. « répétable ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE</span></a>.</p>
<p>Wikipédia. « Fan-out ». Dans <em>Wikipédia</em>. San Francisco, US-CA: Wikipédia, 11 novembre 2020.<a href="https://fr.wikipedia.org/w/index.php?title=Fan-out&oldid=176479075"><span class="underline"> </span></a><a href="https://fr.wikipedia.org/w/index.php?title=Fan-out&oldid=176479075"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Fan-out&oldid=176479075</span></a>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block"><strong>many to one, necessary (1,1:0,n)</strong></p>
<p class="en block">~~~~~</p>
<p><strong>plusieurs à un, nécessaire</strong></p>
<p><strong>(1,1:0,n)</strong></p>
</td>
<td>
<p class="en block">An individual domain instance of this property must have exactly one instance of the property, but an individual range instance can be referenced by zero, one, or more instances of the property. In other words, the property is necessary and not repeatable for its domain, and optional and repeatable for its range. This situation is sometimes called a “fan-in”.</p>
<p class="en block">~~~~~</p>
<p>Une instance du domaine de cette propriété peut n’avoir qu’une seule instance de la propriété, mais une instance de sa portée peut être référencée par aucune, une ou plusieurs instances de la même propriété. En d’autres termes, le domaine de la propriété est nécessaire et non répétable [n.d.t. c.-à-d. qu’une même propriété ne peut être utilisée qu’une seule fois avec une instance spécifique de son domaine], mais sa portée est optionnelle et répétable [n.d.t. c.-à-d. qu’une même propriété peut être utilisée à plusieurs reprises avec une même instance de sa portée]. Cette situation est parfois qualifiée d’« entrance ». </p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="0">
<p>Une propriété répétable est une propriété pouvant apparaître plus d’une fois dans un enregistrement avec le(s) même(s) domaine et/ou portée. </p>
<p>Une recherche sommaire indique que le terme « fan-in » est surtout usité dans le domaine des circuits booléens et de l’intelligence artificielle, où il est parfois question d’arité entrante ou d’entrance. </p>
<p>Cette traduction est tirée de la définition miroir de la section « <a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction#quantificateurs-de-proprietes"><span class="underline">Quantificateurs de propriétés</span></a> » du CIDOC CRM.</p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="0">
<p>CIDOC CRM Special Interest Group. « CIDOC CRM Version 7.1.3 ». Traduit par Frédéric Bricaud, Camille Crevier-Lalonde, Stephen Hart, Karine Léonard Brouillet, Marie-Elaine Mathieu, Philippe Michon, Marielle St-Germain, et Marie-Pier Blain. Traduction en français du CIDOC CRM, 23 août 2024.<a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline"> </span></a><a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline">https://cidoc-crm-fr.info/v7.1.3/information/introduction</span></a>.</p>
<p>Termium. « fan-in ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
<p>———. « répétable ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE</span></a>.</p>
<p>Wikipédia. « Fan-in ». Dans <em>Wikipédia</em>. San Francisco, US-CA: Wikipédia, 11 novembre 2020.<a href="https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056"><span class="underline"> </span></a><a href="https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056</span></a>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block"><strong>one to many, dependent</strong></p>
<p class="en block"><strong>(0,n:1,1)</strong></p>
<p class="en block">~~~~~</p>
<p><strong>un à plusieurs, dépendant</strong></p>
<p><strong>(0,n:1,1)</strong></p>
</td>
<td>
<p class="en block">An individual domain instance of this property can have zero, one, or more instances of the property, but an individual range instance must be referenced by exactly one instance of the property. In other words, this property is optional and repeatable for its domain, but necessary and not repeatable for its range. This situation is sometimes called a “fan-out”.</p>
<p class="en block">~~~~~</p>
<p>Une instance individuelle du domaine de cette propriété peut n’avoir aucune, une ou plusieurs instance(s) de la propriété, mais une instance individuelle de sa portée ne doit être référencée que par une seule instance de la même propriété. En d’autres termes, le domaine de cette propriété est optionnel et répétable [n.d.t. c.-à-d. qu’une même propriété peut être utilisée à plusieurs reprises avec une même instance de son domaine], mais sa portée est nécessaire et non répétable [n.d.t. c.-à-d. qu’une même propriété ne peut être utilisée qu’une seule fois avec une instance spécifique de sa portée]. Cette situation est parfois qualifiée de « sortance ». </p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="0">
<p>Une propriété répétable est une propriété pouvant apparaître plus d’une fois dans un enregistrement avec le(s) même(s) domaine et/ou portée. </p>
<p>Une recherche sommaire indique que le terme « fan-out » est surtout usité dans le domaine des circuits booléens et de l’intelligence artificielle où il est parfois question d’arité sortante ou de sortance. </p>
<p>Cette traduction est tirée de la définition miroir de la section « <a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction#quantificateurs-de-proprietes"><span class="underline">Quantificateurs de propriétés</span></a> » du CIDOC CRM.</p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="0">
<p>CIDOC CRM Special Interest Group. « CIDOC CRM Version 7.1.3 ». Traduit par Frédéric Bricaud, Camille Crevier-Lalonde, Stephen Hart, Karine Léonard Brouillet, Marie-Elaine Mathieu, Philippe Michon, Marielle St-Germain, et Marie-Pier Blain. Traduction en français du CIDOC CRM, 23 août 2024.<a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline"> </span></a><a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline">https://cidoc-crm-fr.info/v7.1.3/information/introduction</span></a>.</p>
<p>Termium. « fan-out ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-out&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-out&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-out&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
<p>———. « répétable ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE</span></a>.</p>
<p>Wikipédia. « Fan-out ». Dans <em>Wikipédia</em>. San Francisco, US-CA: Wikipédia, 11 novembre 2020.<a href="https://fr.wikipedia.org/w/index.php?title=Fan-out&oldid=176479075"><span class="underline"> </span></a><a href="https://fr.wikipedia.org/w/index.php?title=Fan-out&oldid=176479075"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Fan-out&oldid=176479075</span></a>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block"><strong>many to many, necessary,</strong></p>
<p class="en block"><strong>dependent</strong></p>
<p><strong>(1,n:1,n)</strong></p>
<p class="en block">~~~~~</p>
<p><strong>plusieurs à plusieurs, nécessaire, dépendant</strong></p>
<p><strong>(1,n:1,n)</strong></p>
</td>
<td>
<p class="en block">An individual domain instance and range instance of this property must have at least one instance of this property. In other words, this property is necessary and repeatable for its domain and range.</p>
<p class="en block">~~~~~</p>
<p>Une instance individuelle du domaine et de la portée de cette propriété doit avoir au moins une instance de cette propriété. En d’autres termes, le domaine et la portée de cette propriété sont nécessaires et répétables [n.d.t. c.-à-d. qu’une même propriété peut être utilisée à plusieurs reprises avec une même instance de son domaine et de sa portée].</p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em><strong></strong></p>
</th>
<td colspan="0">
<p>Cette traduction est tirée de la définition miroir de la section « <a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction#quantificateurs-de-proprietes"><span class="underline">Quantificateurs de propriétés</span></a> » du CIDOC CRM.</p>
</td>
</tr>
<tr>
<th><p><em>Références</em><strong></strong></p>
</th>
<td colspan="0">
<p>CIDOC CRM Special Interest Group. « CIDOC CRM Version 7.1.3 ». Traduit par Frédéric Bricaud, Camille Crevier-Lalonde, Stephen Hart, Karine Léonard Brouillet, Marie-Elaine Mathieu, Philippe Michon, Marielle St-Germain, et Marie-Pier Blain. Traduction en français du CIDOC CRM, 23 août 2024.<a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline"> </span></a><a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline">https://cidoc-crm-fr.info/v7.1.3/information/introduction</span></a>.</p>
<p>Termium. « répétable ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE</span></a>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block"><strong>one to many, necessary, dependent </strong></p>
<p class="en block"><strong>(1,n:1,1)</strong></p>
<p class="en block">~~~~~</p>
<p><strong>un à plusieurs, </strong></p>
<p><strong>nécessaire, dépendant</strong></p>
<p><strong>(1,n:1,1)</strong></p>
</td>
<td>
<p class="en block">An individual domain instance of this property can have one or more instances of the property, but an individual range instance must be referenced by exactly one instance of the property. In other words, the property is necessary and repeatable for its domain, and necessary but not repeatable for its range. This situation is sometimes called a “fan-out”.</p>
<p class="en block">~~~~~</p>
<p>Une instance individuelle du domaine de cette propriété peut n’avoir qu’une seule ou plusieurs instance(s) de la propriété, mais une instance individuelle de sa portée ne doit être référencée que par une seule instance de la même propriété. En d’autres termes, le domaine de la propriété est nécessaire et répétable [n.d.t. c.-à-d. qu’une même propriété peut être utilisée à plusieurs reprises avec une même instance de son domaine] et sa portée est nécessaire mais non répétable [n.d.t. c.-à-d. qu’une même propriété ne peut être utilisée qu’une seule fois avec une instance spécifique de sa portée]. Cette situation est parfois qualifiée de « sortance ».</p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="0">
<p>Une propriété répétable est une propriété pouvant apparaître plus d’une fois dans un enregistrement avec le(s) même(s) domaine et/ou portée. </p>
<p>Une recherche sommaire indique que le terme « fan-in » est surtout usité dans le domaine des circuits booléens et de l’intelligence artificielle, où il est parfois question d’arité entrante ou d’entrance. </p>
<p>Cette traduction est tirée de la définition miroir de la section « <a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction#quantificateurs-de-proprietes"><span class="underline">Quantificateurs de propriétés</span></a> » du CIDOC CRM.</p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="0">
<p>CIDOC CRM Special Interest Group. « CIDOC CRM Version 7.1.3 ». Traduit par Frédéric Bricaud, Camille Crevier-Lalonde, Stephen Hart, Karine Léonard Brouillet, Marie-Elaine Mathieu, Philippe Michon, Marielle St-Germain, et Marie-Pier Blain. Traduction en français du CIDOC CRM, 23 août 2024.<a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline"> </span></a><a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline">https://cidoc-crm-fr.info/v7.1.3/information/introduction</span></a>.</p>
<p>Termium. « fan-in ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
<p>———. « répétable ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE</span></a>.</p>
<p>Wikipédia. « Fan-in ». Dans <em>Wikipédia</em>. San Francisco, US-CA: Wikipédia, 11 novembre 2020.<a href="https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056"><span class="underline"> </span></a><a href="https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056</span></a>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block"><strong>many to one, necessary, dependent </strong></p>
<p class="en block"><strong>(1,1:1,n)</strong></p>
<p class="en block">~~~~~</p>
<p><strong>plusieurs à un, nécessaire, </strong></p>
<p><strong>dépendant</strong></p>
<p><strong>(1,1:1,n)</strong></p>
</td>
<td>
<p class="en block">An individual domain instance of this property must have exactly one instance of the property, but an individual range instance can be referenced by one or more instances of the property. In other words, the property is necessary and not repeatable for its domain, and necessary and repeatable for its range. This situation is sometimes called a “fan-in”.</p>
<p class="en block">~~~~~</p>
<p>Une instance individuelle du domaine de cette propriété doit n’avoir qu’une seule instance de la propriété, mais une instance individuelle de sa portée peut être référencée par une ou plusieurs instances de la même propriété. En d’autres termes, le domaine de la propriété est nécessaire et non répétable [n.d.t. c.-à-d. qu’une même propriété ne peut être utilisée qu’une seule fois avec une instance spécifique de son domaine], tandis que la portée est nécessaire et répétable [n.d.t. c.-à-d. qu’une même propriété peut être utilisée à plusieurs reprises avec une même instance de sa portée]. Cette situation est parfois qualifiée d’« entrance ». </p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="0">
<p>Une propriété répétable est une propriété pouvant apparaître plus d’une fois dans un enregistrement avec le(s) même(s) domaine et/ou portée. </p>
<p>Une recherche sommaire indique que le terme « fan-in » est surtout usité dans le domaine des circuits booléens et de l’intelligence artificielle, où il est parfois question d’arité entrante ou d’entrance. </p>
<p>Cette traduction est tirée de la définition miroir de la section « <a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction#quantificateurs-de-proprietes"><span class="underline">Quantificateurs de propriétés</span></a> » du CIDOC CRM.</p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="0">
<p>CIDOC CRM Special Interest Group. « CIDOC CRM Version 7.1.3 ». Traduit par Frédéric Bricaud, Camille Crevier-Lalonde, Stephen Hart, Karine Léonard Brouillet, Marie-Elaine Mathieu, Philippe Michon, Marielle St-Germain, et Marie-Pier Blain. Traduction en français du CIDOC CRM, 23 août 2024.<a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline"> </span></a><a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline">https://cidoc-crm-fr.info/v7.1.3/information/introduction</span></a>.</p>
<p>Termium. « fan-in ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=1&srchtxt=fan-in&index=ent&codom2nd_wet=1#resultrecs</span></a>.</p>
<p>———. « répétable ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE</span></a>.</p>
<p>Wikipédia. « Fan-in ». Dans <em>Wikipédia</em>. San Francisco, US-CA: Wikipédia, 11 novembre 2020.<a href="https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056"><span class="underline"> </span></a><a href="https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056"><span class="underline">https://fr.wikipedia.org/w/index.php?title=Fan-in&oldid=176479056</span></a>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block"><strong>one to one</strong></p>
<p class="en block"><strong>(1,1:1,1)</strong></p>
<p class="en block">~~~~~</p>
<p><strong>un à un</strong></p>
<p><strong>(1,1:1,1)</strong></p>
</td>
<td>
<p class="en block">An individual domain instance and range instance of this property must have exactly one instance of the property. In other words, the property is necessary and not repeatable for its domain and for its range.</p>
<p class="en block">~~~~~</p>
<p>Une instance individuelle du domaine et une instance de la portée de cette propriété doivent avoir exactement une instance de la propriété. En d’autres termes, le domaine et la portée de la propriété sont nécessaires et non répétables [n.d.t. c.-à-d. qu’une même propriété ne peut être utilisée qu’une seule fois avec une instance spécifique de son domaine et une instance spécifique de sa portée]. </p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="0">
<p>Une propriété répétable est une propriété pouvant apparaître plus d’une fois dans un enregistrement avec le(s) même(s) domaine et/ou portée. </p>
<p>Cette traduction est tirée de la définition miroir de la section « <a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction#quantificateurs-de-proprietes"><span class="underline">Quantificateurs de propriétés</span></a> » du CIDOC CRM.</p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="0">
<p>CIDOC CRM Special Interest Group. « CIDOC CRM Version 7.1.3 ». Traduit par Frédéric Bricaud, Camille Crevier-Lalonde, Stephen Hart, Karine Léonard Brouillet, Marie-Elaine Mathieu, Philippe Michon, Marielle St-Germain, et Marie-Pier Blain. Traduction en français du CIDOC CRM, 23 août 2024.<a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline"> </span></a><a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline">https://cidoc-crm-fr.info/v7.1.3/information/introduction</span></a>.</p>
<p>Termium. « répétable ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE</span></a>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block"><strong>one to one,</strong></p>
<p class="en block"><strong>necessary</strong></p>
<p class="en block"><strong>(1,1:0,1)</strong></p>
<p class="en block">~~~~~</p>
<p><strong>un à un, nécessaire</strong></p>
<p><strong>(1,1:0,1)</strong></p>
</td>
<td>
<p class="en block">An individual domain instance of this property must have exactly one instance of this property, but an individual range instance cannot be referenced by more than one instance of this property. In other words, this property is necessary and not repeatable for its domain, and optional but not repeatable for its range. </p>
<p class="en block">~~~~~</p>
<p>Une instance individuelle du domaine de cette propriété doit avoir exactement une instance de cette propriété, mais une instance individuelle de sa portée ne peut pas faire l’objet d’une référence par plus d’une instance de cette même propriété. En d’autres termes, le domaine de cette propriété est nécessaire et non-répétable [n.d.t. c.-à-d. qu’une même propriété ne peut être utilisée qu’une seule fois avec une instance spécifique de son domaine], tandis que sa portée est optionnelle et non-répétable [n.d.t. c.-à-d. qu’une même propriété ne peut être utilisée à plusieurs reprises avec une même instance de sa portée]. </p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="0">
<p>Cette traduction est tirée de la définition miroir de la section « <a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction#quantificateurs-de-proprietes"><span class="underline">Quantificateurs de propriétés</span></a> » du CIDOC CRM.</p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="0">
<p>CIDOC CRM Special Interest Group. « CIDOC CRM Version 7.1.3 ». Traduit par Frédéric Bricaud, Camille Crevier-Lalonde, Stephen Hart, Karine Léonard Brouillet, Marie-Elaine Mathieu, Philippe Michon, Marielle St-Germain, et Marie-Pier Blain. Traduction en français du CIDOC CRM, 23 août 2024.<a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline"> </span></a><a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline">https://cidoc-crm-fr.info/v7.1.3/information/introduction</span></a>.</p>
<p>Termium. « répétable ». Dans <em>Termium Plus</em>. Ottawa, CA-ON: Gouvernement du Canada, 8 octobre 2009.<a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline"> </span></a><a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE"><span class="underline">https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&i=&index=alt&srchtxt=CATEGORIE%20REPETABLE</span></a>.</p>
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
<p>The CIDOC CRM family of models defines some dependencies between properties and the classes that are their domains or ranges. These can be one or both of the following:</p>
<ul><li><p>the property is necessary for the domain</p>
</li>
<li><p>the property is necessary for the range, or, in other words, the range is dependent on the property.</p>
</li></ul>
<p>The possible kinds of dependencies are defined in the table above. Note that if a dependent property is not specified for an instance of the respective domain or range, it means that the property exists, but the value on one side of the property is unknown. In the case of optional properties, the methodology proposed does not distinguish between a value being unknown or the property not being applicable at all. For example, one may know that an object has an owner, but the owner is unknown. In the CIDOC CRM family of models this case cannot be distinguished from the fact that the object has no owner at all. Of course, such details can always be specified by a textual note.</p>
<p>Note that the quantification of all properties of properties, “.1” properties, is “many-to-many” and, therefore, does not appear explicitly in their definitions.</p>
</td>
<td>
<p>Les modèles dérivés du CIDOC CRM définissent certains dépendants entre les propriétés et les classes sous la forme de leur domaine et de leur portée. Ceux-ci peuvent être l’une ou une combinaison des options suivantes : </p>
<ul><li><p>la propriété est nécessaire pour le domaine ;</p>
</li>
<li><p>la propriété est nécessaire pour la portée ou, en d’autres termes, la portée dépend de la propriété.</p>
</li></ul>
<p>Les dépendants possibles sont définis dans le tableau ci-haut. Si une propriété n’est pas spécifiée pour une instance de son domaine ou de sa portée, il est entendu que la propriété existe, mais qu’une valeur associée à une part ou à l’autre de la propriété est inconnue. Dans le cas des propriétés optionnelles, la méthodologie proposée par le CIDOC CRM n’établit pas de distinction entre une valeur inconnue et une propriété qui ne serait pas du tout applicable. Par exemple, un objet peut avoir un.e propriétaire sans que l’identité de ce.tte propriétaire ne soit connue. Dans le cadre des modèles du CIDOC CRM, une telle situation ne peut être distinguée d’un cas où l’objet n’aurait aucun.e propriétaire. Bien entendu, de tels détails peuvent être indiqués à l’aide de notes textuelles. </p>
<p>Parce que la quantification de toutes les propriétés de propriétés – les propriétés « .1 » – est « plusieurs à plusieurs » elle n’apparaît pas explicitement dans leurs définitions. </p>
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
<p>Cette traduction est tirée de la définition miroir de la section « <a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction#quantificateurs-de-proprietes"><span class="underline">Quantificateurs de propriétés</span></a> » du CIDOC CRM.</p>
</td>
</tr>
<tr>
<th style="width:15%"><p><em>Références</em></p>
</th>
<td colspan="1">
<p>CIDOC CRM Special Interest Group. « CIDOC CRM Version 7.1.3 ». Traduit par Frédéric Bricaud, Camille Crevier-Lalonde, Stephen Hart, Karine Léonard Brouillet, Marie-Elaine Mathieu, Philippe Michon, Marielle St-Germain, et Marie-Pier Blain. Traduction en français du CIDOC CRM, 23 août 2024.<a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline"> </span></a><a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline">https://cidoc-crm-fr.info/v7.1.3/information/introduction</span></a>.<em></em></p>
</td>
</tr>
</tbody>
</table>

<h2 id="convention-de-presentation"><span class="en heading">4.5. Presentation Conventions - </span>4.5. Convention de présentation</h2>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>All instances of E41 Appellation are presented within single quotation marks, whether they are used for themselves or just to refer to the things they name. Any punctuation mark that follows an instance of E41 Appellation is placed outside the single quotation marks, as it does not belong to the appellation itself.</p>
<p>Furthermore, all references to instances of E90 Symbolic Object in the form of a content model are presented within single quotation marks, such as ‘abc’. By content model we mean the symbol sequence the symbolic object consists of.</p>
<p>British spelling is used throughout the original English version of this document, except for occasional quotations and examples.</p>
</td>
<td>
<p>Qu’elles réfèrent à elles-mêmes ou à des choses qu’elles nomment, toutes les instances de <code class="language-plaintext highlighter-rouge">E41_Appellation</code> sont identifiées par des guillemets. Tout signe de ponctuation suivant une instance de <code class="language-plaintext highlighter-rouge">E41_Appellation</code> est placé à l’extérieur de ces guillemets car il ne fait pas partie de l’appellation elle-même. </p>
<p>De plus, les références à des instances de <code class="language-plaintext highlighter-rouge">E90_Objet_symbolique</code> qui prennent la forme de modèles de contenu, – c.-à-d. des séquences de symboles constituant un objet symbolique –, sont aussi présentées dans des guillemets (p. ex. « abc »). </p>
<p>La graphie britannique est utilisée dans la version originale de ce texte [n.d.t. et la graphie traditionnelle française est utilisée dans sa traduction], et ce à l’exception de citations et d’exemples spécifiques où cela est pertinent. </p>
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

