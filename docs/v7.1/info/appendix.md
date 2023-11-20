---
layout: page
title: Annexe
titleEn: Appendix - Annexe
permalink: /v7.1/annexe
sidebar: v71
date: 2023-05-26
---

**Date de création** : 2020-10-20

**Dernière mise à jour** : 2023-05-26

<div class="lang-buttons">
 <button id="fr" class="activate">FR</button>
 <button id="en-fr">EN-FR</button>
</div>

<h2 id="classes-et-proprietes-depreciees"><span class="en heading">Deprecated classes and properties - </span>Classes et propriétés dépréciées</h2>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>The following is a list of classes and/or properties that have been deprecated between the version 5.0.4 of the CIDOC CRM, which served as community draft for ISO21127:2014, and this release (7.1). While the CIDOC CRM is developed with the principle of monotonic change, attempting to minimize backwards incompatibility through conservative initial modelling as well as modelling evolution, certain revisions inevitably entail changes to the model which will require an update to knowledge bases based on old versions of the ontology, in order to reconcile instances with the current version. The following tables provide information on which classes or properties have been deprecated and will thus require an update to previous official CRM compliant KBs in order to be in accord with the latest version of the standard. The reader will find in the first table, "Deprecated Class Migration Instructions", classes that have been deprecated and the suggested class or primitive replacement for that class. The reader should further refer to the 'deprecated property migration instructions table' in order to see not only the replacements for deprecated properties but also to understand how to build correct new semantic paths between the instances of deprecated classes and the newly suggested replacement classes or primitives.</p>
</td>
<td>
<p>La liste qui suit énumère les classes et/ou propriétés qui ont été dépréciées depuis la version 5.0.4 du CIDOC CRM (laquelle a servi d’ébauche communautaire pour ISO21127:2014 ainsi que pour cette version 7.1). Bien que le modèle CIDOC CRM soit développé selon les principes du changement monotone et que tout soit mis en oeuvre pour minimiser la rétro-incompatibilité (notamment grâce à une modélisation conservatrice tant initialement qu’au cours de l’évolution du modèle), certaines révisions exigent inévitablement des mises à jour des bases de connaissances qui s’appuient sur d’anciennes versions de l’ontologie afin de réconcilier les instances avec la version actuelle. Les tableaux ci-bas indiquent quelles classes et quelles propriétés ont été dépréciées de telle sorte qu’elles exigent une mise à jour des bases de connaissances auparavant conformes au CIDOC CRM afin d’être conformes avec la version la plus récente du standard. </p>
<p>Le tableau « <a href="https://cidoc-crm-fr.info/v7.1/annexe#instructions-de-migration-des-classes-depreciees"><span class="underline">Instructions de migration des classes dépréciées</span></a> » énumère les classes dépréciées ainsi que les classes ou entités primitives qu’il est recommandé d’utiliser à la place de celles-ci. </p>
<p>[n.d.t. Le tableau « <a href="https://cidoc-crm-fr.info/v7.1/annexe#instructions-de-migration-pour-e81_transformation-domaine-dapplication-restreint"><span class="underline">Instructions de migration pour </span></a><a href="https://cidoc-crm-fr.info/v7.1/annexe#instructions-de-migration-pour-e81_transformation-domaine-dapplication-restreint"><span class="underline"><code class="language-plaintext highlighter-rouge">E81_Transformation</code></span></a><a href="https://cidoc-crm-fr.info/v7.1/annexe#instructions-de-migration-pour-e81_transformation-domaine-dapplication-restreint"><span class="underline"> (domaine d’application restreint)</span></a> » fait des recommandations quand à la meilleure manière de mettre à jour une base de connaissances suite à la restriction du domaine d’application de <code class="language-plaintext highlighter-rouge">E81_Transformation</code>.] </p>
<p>Le tableau « <a href="https://cidoc-crm-fr.info/v7.1/annexe#instructions-de-migration-des-proprietes-depreciees"><span class="underline">Instructions de migration des propriétés dépréciées</span></a> » énumère les propriétés dépréciées ainsi que celles qu’il est recommandé d’utiliser à la place de celles-ci. C’est un bon outil pour comprendre comment bien construire de nouveaux chemins sémantiques entre des instances de classes dépréciées et les remplacements de classes ou d’entités primitives qui sont recommandés. </p>
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
</td>
</tr>
</tbody>
</table>

<h3 id="instructions-de-migration-des-classes-depreciees"><span class="en heading">Deprecated Class Migration Instructions - </span>Instructions de migration des classes dépréciées</h3>

<table class="original-table">
<tbody>
<tr>
<td class="en">
<p>E38 Image</p>
</td>
<td class="en">
<p>use E36 Visual Item</p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">E38_Image</code></p>
</td>
<td>
<p>utiliser <code class="language-plaintext highlighter-rouge">E36_Entité_visuelle</code></p>
</td>
</tr>
<tr>
<td class="en">
<p>E40 Legal Body</p>
</td>
<td class="en">
<p>use E74 Group</p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">E40_Entité_légale</code></p>
</td>
<td>
<p>utiliser <code class="language-plaintext highlighter-rouge">E74_Groupe</code></p>
</td>
</tr>
<tr>
<td class="en">
<p>E44 Place Appellation</p>
</td>
<td class="en">
<p>use E41 Appellation</p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">E44_Appellation_du_lieu</code></p>
</td>
<td>
<p>utiliser <code class="language-plaintext highlighter-rouge">E41_Appellation</code></p>
</td>
</tr>
<tr>
<td class="en">
<p>E45 Address</p>
</td>
<td class="en">
<p>use E41 Appellation, <em>P2</em><em> has type</em>: “Address”</p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">E45_Adresse</code></p>
</td>
<td>
<p>utiliser <code class="language-plaintext highlighter-rouge">E41_Appellation</code>,  <code class="language-plaintext highlighter-rouge">P2_a_pour_type</code> : « Adresse »</p>
</td>
</tr>
<tr>
<td class="en">
<p>E46 Section Definition</p>
</td>
<td class="en">
<p>use E41 Appellation</p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">E46_Définition_de_section</code></p>
</td>
<td>
<p>utiliser <code class="language-plaintext highlighter-rouge">E41_Appellation</code></p>
</td>
</tr>
<tr>
<td class="en">
<p>E47 Spatial Coordinates</p>
</td>
<td class="en">
<p>use E94 Space Primitive</p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">E47_Coordonnées_spatiales</code></p>
</td>
<td>
<p>utiliser <code class="language-plaintext highlighter-rouge">E94_Primitive_spatiale</code></p>
</td>
</tr>
<tr>
<td class="en">
<p>E48 Place Name</p>
</td>
<td class="en">
<p>use E41 Appellation</p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">E48_Nom_de_lieu</code></p>
</td>
<td>
<p>utiliser <code class="language-plaintext highlighter-rouge">E41_Appellation</code></p>
</td>
</tr>
<tr>
<td class="en">
<p>E49 Time Appellation</p>
</td>
<td class="en">
<p>use E41 Appellation</p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">E49_Appellation_de_temps</code></p>
</td>
<td>
<p>utiliser <code class="language-plaintext highlighter-rouge">E41_Appellation</code></p>
</td>
</tr>
<tr>
<td class="en">
<p>E50 Date</p>
</td>
<td class="en">
<p>use E61 Time Primitive</p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">E50_Date</code></p>
</td>
<td>
<p>utiliser <code class="language-plaintext highlighter-rouge">E61_Primitive_temporelle</code></p>
</td>
</tr>
<tr>
<td class="en">
<p>E51 Contact Point</p>
</td>
<td class="en">
<p>use E41 Appellation, <em>P2</em><em> has type</em>: “Contact Point”</p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">E51_Point_de_contact</code></p>
</td>
<td>
<p>utiliser <code class="language-plaintext highlighter-rouge">E41_Appellation</code>,  <code class="language-plaintext highlighter-rouge">P2_a_pour_type</code> : « Point de contact »</p>
</td>
</tr>
<tr>
<td class="en">
<p>E75 Conceptual Object Appellation</p>
</td>
<td class="en">
<p>use E41 Appellation</p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">E75_Appellation_d’objet_conceptuel</code></p>
</td>
<td>
<p>utiliser <code class="language-plaintext highlighter-rouge">E41_Appellation</code></p>
</td>
</tr>
<tr>
<td class="en">
<p>E82 Actor Appellation</p>
</td>
<td class="en">
<p>use E41 Appellation</p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">E82_Appellation_d’acteur</code></p>
</td>
<td>
<p>utiliser <code class="language-plaintext highlighter-rouge">E41_Appellation</code></p>
</td>
</tr>
<tr>
<td class="en">
<p>E84 Information Carrier</p>
</td>
<td class="en">
<p>use E22 Human-Made Object, <em>P2</em><em> has type</em>: “Information Carrier”</p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">E84_Porteur_d’information</code></p>
</td>
<td>
<p>utiliser <code class="language-plaintext highlighter-rouge">E22_Objet_élaboré_par_l'humain</code>,  <code class="language-plaintext highlighter-rouge">P2_a_pour_type</code> : « Porteur d’information »</p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
<p>Les traductions des classes dépréciées sont littérales et n’ont pas fait l’objet d’un examen dédié dans le cadre de ce travail. </p>
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p></p>
</td>
</tr>
</tbody>
</table>

<h3 id="instructions-de-migration-pour-e81_transformation-domaine-dapplication-restreint"><span class="en heading">Migration Instructions for the reduced scope of E81 Transformation - </span>Instructions de migration pour <code class="language-plaintext highlighter-rouge">E81_Transformation</code> (domaine d’application restreint)</h3>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>From version 7.1 on, the class E81 Transformation pertains only to instances of E18 Physical Thing, rather than to instances of E77 Persistent Item. The reason is the insight that only for physical things the form previous to a transformation must cease to exist. For instances of Conceptual Objects, any number of copies can be around that are not affected by the transformation. Similarly, transformations of instances of E74 Group do not necessarily cause the dissolution of the previous grouping.</p>
<p>Therefore, the properties <em>P123</em><em> resulted in (resulted from)</em> and <em>P124</em><em> transformed (was transformed by) </em>have now the range: E18 Physical Thing.</p>
<p>If these properties were applied in the source to instances of E28 Conceptual Object or  its subclasses, use in the migration target E65 Creation instead of E81 Transformation, <em>P94</em><em> has created (was created by)</em> instead of <em>P123</em><em> resulted in (resulted from),</em> and <em>P16</em><em> used specific object (was used for)</em> instead of <em>P124</em><em> transformed (was transformed by).</em></p>
<p>If these properties were applied in the source to instances of 74 Group, use in the migration target E66 Formation instead of E81 Transformation, <em>P95</em><em> has formed (was formed by) </em>instead of <em>P123</em><em> resulted in (resulted from),</em> and <em>P151</em><em> was formed from (participated in)</em> instead of <em>P124</em><em> transformed (was transformed by).</em></p>
</td>
<td>
<p>À compter de la version 7.1, la classe <code class="language-plaintext highlighter-rouge">E81_Transformation</code> ne s’applique qu’aux instances de <code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code> alors qu’elle s’appliquait aussi, auparavant, aux instances de <code class="language-plaintext highlighter-rouge">E77_Entité_persistante</code>. Ce changement a été effectué car si la forme préexistante d’une chose matérielle doit cesser d’exister pour être remplacée, ce n’est pas le cas de ce qui n’est pas matériel. Dans le cas des instances de <code class="language-plaintext highlighter-rouge">E28_Objet_conceptuel</code>, de nombreuses copies d’un même objet peuvent exister sans être affectées par la transformation. De la même manière, la transformation des instances de <code class="language-plaintext highlighter-rouge">E74_Groupe</code> n’implique pas nécessairement la dissolution du groupement préexistant. </p>
<p>Les propriétés <code class="language-plaintext highlighter-rouge">P123_a_eu_pour_résultat (a_résulté_de)</code> et <code class="language-plaintext highlighter-rouge">P124_a transformé (a_été_transformé_par)</code> ont donc maintenant pour portée <code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code>.</p>
<p>Si dans la [n.d.t. base de connaissances] source ces propriétés étaient appliquées à des instances de <code class="language-plaintext highlighter-rouge">E28_Objet_conceptuel</code> ou de ses sous-classes, il est recommandé d’utiliser : </p>
<ul><li><p><code class="language-plaintext highlighter-rouge">E65_Création</code> au lieu de <code class="language-plaintext highlighter-rouge">E81_Transformation</code>;</p>
</li>
<li><p><code class="language-plaintext highlighter-rouge">P94_a_créé (a_été_créé_par)</code> au lieu de <code class="language-plaintext highlighter-rouge">P123_a_eu_pour_résultat (a_résulté_de)</code>;</p>
</li>
<li><p><code class="language-plaintext highlighter-rouge">P16_</code><code class="language-plaintext highlighter-rouge">a_utilisé_l'objet_spécifique (a_été_utilisé_pour)</code> au lieu de <code class="language-plaintext highlighter-rouge">P124_a transformé (a_été_transformé_par)</code>.</p>
</li></ul>
<p>Si dans la [n.d.t. base de connaissances] source ces propriétés étaient appliquées à des instances de <code class="language-plaintext highlighter-rouge">E74_Groupe</code>, il est recommandé d’utiliser : </p>
<ul><li><p><code class="language-plaintext highlighter-rouge">E66_Formation</code> au lieu de <code class="language-plaintext highlighter-rouge">E81_Transformation</code>;</p>
</li>
<li><p><code class="language-plaintext highlighter-rouge">P95_a_fondé (a_été_fondé_par)</code> au lieu de <code class="language-plaintext highlighter-rouge">P123_a_eu_pour_résultat (a_résulté_de)</code>;</p>
</li>
<li><p><code class="language-plaintext highlighter-rouge">P151_a_été_formé_de (a_participé_à)</code> au lieu de <code class="language-plaintext highlighter-rouge">P124_a transformé (a_été_transformé_par)</code>.</p>
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

<h3 id="instructions-de-migration-des-proprietes-depreciees"><span class="en heading">Deprecated Property Migration Instructions - </span>Instructions de migration des propriétés dépréciées</h3>

<table class="original-table">
<tbody>
<tr>
<td class="en">
<p><strong>Deprecated Property</strong></p>
</td>
<td class="en">
<p><strong>Migration Instruction</strong></p>
</td>
<td>
</td>
<td>
</td>
</tr>
<tr>
<td class="en">
<p><em>P58 has section definition (defines section)</em></p>
</td>
<td class="en">
<p>use<em> </em><em>P1</em><em> is identified by (identifies)</em></p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">P58_a_pour_définition_de_section (définit_la_section)</code></p>
</td>
<td>
<p>utiliser <code class="language-plaintext highlighter-rouge">P1_est_identifié_par (identifie)</code></p>
</td>
</tr>
<tr>
<td class="en">
<p><em>P78 is identified by (identifies): </em>E49 Time Appellation</p>
<p>[except for instances of E50 Date]</p>
</td>
<td class="en">
<p>use <em>P1</em> <em>identified by (identifies):</em> E41 Appellation [for instance, Japanese imperial rule names]</p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">P78_est_identifié_par</code><em> </em><code class="language-plaintext highlighter-rouge">(identifie)</code><em> </em>: <code class="language-plaintext highlighter-rouge">E49_Appellation_de_temps</code> </p>
<p>[à l’exception des instances de <code class="language-plaintext highlighter-rouge">E50_Date</code>]</p>
</td>
<td>
<p>utiliser <code class="language-plaintext highlighter-rouge">P1_est_identifié_par (identifie)</code> : <code class="language-plaintext highlighter-rouge">E41_Appellation </code>[par exemple, des noms de règles impériales japonaises]</p>
</td>
</tr>
<tr>
<td class="en">
<p><em>P78 is identified by (identifies): </em>E50 Date</p>
</td>
<td class="en">
<p>use <em>P170i time is defined by</em>: E61Time Primitive</p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">P78_est_identifié_par (identifie)</code><em> </em>: <code class="language-plaintext highlighter-rouge">E50_Date</code></p>
</td>
<td>
<p>utiliser <code class="language-plaintext highlighter-rouge">P170i_temps_défini_par</code> : <code class="language-plaintext highlighter-rouge">E61_Primitive_temporelle</code></p>
</td>
</tr>
<tr>
<td class="en">
<p><em>P88 consists of (forms part of)</em></p>
</td>
<td class="en">
<p>If used as a geometric decomposition, use <em>P89i contains</em>.</p>
<p>If the respective place is defined in the source by an instance of E26 Physical Feature, and the use of <em>P88 consists of</em> aims at describing its decomposition into its natural components, describe explicitly in the migration target the instance of E26 Physical Feature and its parts using <em>P46</em><em> is composed of</em></p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">P88_consiste_en (fait_partie_de)</code></p>
</td>
<td>
<p>s’il s’agit d’une décomposition géométrique, utiliser <code class="language-plaintext highlighter-rouge">P89i_contient</code></p>
<p>Si le lieu dont il est question est une instance de <code class="language-plaintext highlighter-rouge">E26_Caractéristique_physique</code> et que l’usage de <code class="language-plaintext highlighter-rouge">P88_consiste_en</code> a pour objectif de décrire la décomposition en des composantes naturelles, décrire explicitement l’instance de <code class="language-plaintext highlighter-rouge">E26_Caractéristique_physique</code> ainsi que ses composantes en utilisant <code class="language-plaintext highlighter-rouge">P46_est_composé_de</code></p>
</td>
</tr>
<tr>
<td class="en">
<p><em>P83 had at least duration (was minimum duration of) </em></p>
<p>and</p>
<p><em>P84 had at most duration (was maximum duration of)</em></p>
</td>
<td class="en">
<p>use <em>P191</em><em> had duration (was duration of)</em>:</p>
<p>The instances of E60 Number in the full source paths: E52 Time-Span<em>. P83 had at least duration.</em> E54 Dimension<em>. P90 has value. </em>E60 Number and in E52 Time-Span<em>. P84 had at most duration.</em> E54 Dimension<em>. P90 has value. </em>E60 Number </p>
<p>should both be merged in the migration target path into one numerical interval, instance of E60 Number:</p>
<p>E52 Time-Span<em>.</em> <em>P191 had duration. </em>E54 Dimension<em>. P90 has value.</em> E60 Number</p>
<p>For representing intervals in RDF/OWL encoding see the respective implementation guidelines.</p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">P83_a_eu_pour_durée_minimale (était_la_durée_minimale_de)</code></p>
<p>et</p>
<p><code class="language-plaintext highlighter-rouge">P84_a_eu_pour_durée_maximale (était_la_durée_maximale_de)</code></p>
</td>
<td>
<p>utiliser <code class="language-plaintext highlighter-rouge">P191_a_eu_pour_durée (était_la_durée_de)</code></p>
<p>Les instances de <code class="language-plaintext highlighter-rouge">E60_Nombre</code> qui se trouvent dans des chemins sémantiques complets (<code class="language-plaintext highlighter-rouge">E52_Intervalle_temporel</code> . <code class="language-plaintext highlighter-rouge">P83_a_eu_pour_durée_minimale</code> . <code class="language-plaintext highlighter-rouge">E54_Dimension</code> . <code class="language-plaintext highlighter-rouge">P90_a_pour_valeur</code> . <code class="language-plaintext highlighter-rouge">E60_Nombre</code> et <code class="language-plaintext highlighter-rouge">E52_Intervalle_temporel</code> . <code class="language-plaintext highlighter-rouge">P84_a_eu_pour_durée_maximale</code> . <code class="language-plaintext highlighter-rouge">E54_Dimension</code> . <code class="language-plaintext highlighter-rouge">P90_a_pour_valeur</code> . <code class="language-plaintext highlighter-rouge">E60_Nombre</code>)  devraient être amalgamées en un seul intervalle numérique, instance de <code class="language-plaintext highlighter-rouge">E60_Nombre</code> : <code class="language-plaintext highlighter-rouge">E52_Intervalle_temporel</code> . <code class="language-plaintext highlighter-rouge">P191_a_eu_pour_durée</code> . <code class="language-plaintext highlighter-rouge">E54_Dimension</code> . <code class="language-plaintext highlighter-rouge">P90_a_pour_valeur</code> . <code class="language-plaintext highlighter-rouge">E60_Nombre</code> </p>
<p>Pour représenter les intervalles en encodage <a href="https://www.w3.org/RDF/"><span class="underline">RDF</span></a>/<a href="https://www.w3.org/OWL/"><span class="underline">OWL</span></a>, voir les recommandations d’implémentation de chacun. </p>
</td>
</tr>
<tr>
<td class="en">
<p><em>P87 is identified by (identifies)</em>: E44 Place Appellation</p>
<p>(except for instances of E47 Spatial Coordinates)</p>
</td>
<td class="en">
<p>use <em>P1</em><em> identified by (identifies)</em>: E41 Appellation</p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">P87_est_identifié_par (identifie)</code><em> </em>: <code class="language-plaintext highlighter-rouge">E44_Appellation_du_lieu</code> (à l’exception des instances de <code class="language-plaintext highlighter-rouge">E47_Coordonnées_spatiales</code>). </p>
</td>
<td>
<p>utiliser <code class="language-plaintext highlighter-rouge">P1_est_identifié_par (identifie)</code> : <code class="language-plaintext highlighter-rouge">E41_Appellation</code></p>
</td>
</tr>
<tr>
<td class="en">
<p><em>P87 is identified by (identifies)</em>: E47 Spatial Coordinates</p>
</td>
<td class="en">
<p>use <em>P168i defines place</em>: E94 Space Primitive</p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">P87_est_identifié_par (identifie)</code><em> </em>: <code class="language-plaintext highlighter-rouge">E47_Coordonnées_spatiales</code></p>
</td>
<td>
<p>utiliser <code class="language-plaintext highlighter-rouge">P168i_définit_le_lieu</code> : <code class="language-plaintext highlighter-rouge">E94_Primitive_spatiale</code></p>
</td>
</tr>
<tr>
<td class="en">
<p><em>P114 is equal in time to</em><sup><em>*</em></sup></p>
</td>
<td class="en">
<p>use the <strong>full path</strong> from E2 Temporal Entity through <em>P4</em><em> has time-span</em>, E52 Time-Span, <em>P4</em><em>i is time-span of.</em> E2 Temporal Entity.</p>
<p>Theoretically, <em>P114 is equal in time to </em>is equal to the conjunction of: <em>(</em><em>P175</em><em> starts before or with the start of </em><strong>AND </strong><em>P175</em><em>i starts after or with the start of </em><strong>AND</strong><em> </em><em>P184</em><em> ends before or with the end of</em><strong> AND </strong><em>P184</em><em>i ends with or after the end of), </em>without fuzzy temporal boundaries. However, note that only a common cause or a socially declared time-span can lead to temporal equality of different instances of E2 Temporal Entity. Consequently, creating the full path is always the preferred migration strategy.</p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">P114_a_pour_équivalence_temporelle</code><em> </em>*</p>
</td>
<td>
<p>utiliser le chemin sémantique complet depuis <code class="language-plaintext highlighter-rouge">E2_Entité_temporelle </code>en passant par <code class="language-plaintext highlighter-rouge">P4_a_pour_intervalle_temporel</code>, <code class="language-plaintext highlighter-rouge">E52_Intervalle_temporel</code>, <code class="language-plaintext highlighter-rouge">P4i_est_l’intervalle_temporel_de</code> . <code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code></p>
<p>Théoriquement, <em>P114_a_pour_équivalence_temporelle</em> est l’équivalent de la conjonction de (<code class="language-plaintext highlighter-rouge">P175_commence_avant_ou_au_moment_du_début_de</code> <strong>ET</strong> <code class="language-plaintext highlighter-rouge">P175i_</code><code class="language-plaintext highlighter-rouge">commence_après_ou_au_moment_du_début_de</code> <strong>ET </strong><code class="language-plaintext highlighter-rouge">P184_se_termine_avant_ou_au_moment_de_la_fin_de</code> <strong>ET</strong> <code class="language-plaintext highlighter-rouge">P184i_se_termine_au_moment_ou_après_la_fin_de</code>) sans frontières temporelles floues. Cependant, seules une cause commune ou un intervalle temporel déclaré socialement peuvent mener à l’équivalence temporelle de différentes instances de <code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code>. Par conséquent, la création d’un chemin sémantique complet est la stratégie de migration qui devrait toujours être privilégiée. </p>
</td>
</tr>
<tr>
<td class="en">
<p><em>P115 finishes (is finished by)</em><sup><em> *</em></sup></p>
</td>
<td class="en">
<p><em>P176</em><em>i starts after the start of </em><strong>AND </strong><em>P184</em><em> ends before or with the end of </em><strong>AND </strong><em>P184</em><em>i ends with or after the end of </em>[<em>P176</em><em>i starts after the start of </em>is required because the Range E2 Temporal Entity must be longer than the Domain E2 Temporal Entity]</p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">P115_termine (est terminé par)</code> *</p>
</td>
<td>
<p>utiliser <code class="language-plaintext highlighter-rouge">P176i_commence_avant_le_début_de</code> <strong>ET</strong> <code class="language-plaintext highlighter-rouge">P184_se_termine_avant_ou_au_moment_de_la_fin_de</code> <strong>ET</strong> <code class="language-plaintext highlighter-rouge">P184i_se_termine_au_moment_ou_après_la_fin_de</code> [<code class="language-plaintext highlighter-rouge">P176i_commence_avant_le_début_de</code> est exigé car la portée de <code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code> doit être plus longue que le domaine de <code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code>]. </p>
</td>
</tr>
<tr>
<td class="en">
<p><em>P116 starts (is started by)</em><sup><em> *</em></sup></p>
</td>
<td class="en">
<p><em>P175</em><em> starts before or with the start of </em><strong>AND </strong><em>P175i starts after or with the start of </em><strong>AND</strong><em> </em><em>P185</em><em> ends before the end of</em> [<em>P185</em><em> ends before the end of </em>is required because the Range E2 Temporal Entity must be longer than the Domain E2 Temporal Entity]</p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">P116_commence (est_commencé_par)</code> *</p>
</td>
<td>
<p>utiliser <code class="language-plaintext highlighter-rouge">P175_commence_avant_ou_au_moment_du_début_de</code> <strong>ET</strong> <code class="language-plaintext highlighter-rouge">P175i_commence_après_ou_au_moment_du_début_de</code> <strong>ET </strong><code class="language-plaintext highlighter-rouge">P185_se_termine_avant_la_fin_de</code> [<code class="language-plaintext highlighter-rouge">P185_se_termine_avant_la_fin_de</code> est exigé car la portée de <code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code> doit être plus longue que le domaine de <code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code>]</p>
</td>
</tr>
<tr>
<td class="en">
<p><em>P117 occurs during (includes)</em><sup><em> *</em></sup></p>
</td>
<td class="en">
<p><em>P176</em><em>i starts after the start of </em><strong>AND </strong><em>P185</em><em> ends before the end of</em></p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">P117_se_produit_durant (inclut)</code><em> </em>*</p>
</td>
<td>
<p>utiliser <code class="language-plaintext highlighter-rouge">P176i_</code><code class="language-plaintext highlighter-rouge">commence_après_le_début_de</code> <strong>ET </strong><code class="language-plaintext highlighter-rouge">P185_se_termine_avant_la_fin_de</code></p>
</td>
</tr>
<tr>
<td class="en">
<p><em>P118 overlaps in time with (is overlapped in time by)</em><sup><em> *</em></sup></p>
</td>
<td class="en">
<p><em>P176</em><em> starts before the start of </em><strong>AND</strong><em> </em><em>P185</em><em> ends before the end of</em></p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">P118_se_superpose_temporellement_à (est_temporellement_superposé_à) </code>*</p>
</td>
<td>
<p>utiliser <code class="language-plaintext highlighter-rouge">P176_commence_avant_le_début_de</code> <strong>ET </strong><code class="language-plaintext highlighter-rouge">P185_se_termine_avant_la_fin_de</code> </p>
</td>
</tr>
<tr>
<td class="en">
<p><em>P119 meets in time with (is met in time by)</em><sup><em> *</em></sup></p>
</td>
<td class="en">
<p>use <em>P182</em><em> ends before or with the start of </em><strong>AND</strong> <em>P173</em><em>i ends after or with the start of</em></p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">P119_concorde_temporellement_avec (concorde_temporellement_avec)</code> *</p>
</td>
<td>
<p>utiliser <code class="language-plaintext highlighter-rouge">P182_se_termine_avant_ou_au_début_du_moment_de</code> <strong>ET</strong> <code class="language-plaintext highlighter-rouge">P173i_se_termine_après_ou_au_moment_du_début_de</code></p>
</td>
</tr>
<tr>
<td class="en">
<p><em>P120 occurs before (occurs after)</em><sup><em> *</em></sup></p>
</td>
<td class="en">
<p>use <em>P183</em><em> ends before the start of</em></p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">P120_se_produit_avant (se_produit_après)</code> *</p>
</td>
<td>
<p>utiliser <code class="language-plaintext highlighter-rouge">P183_se_termine_avant_le_début_de</code></p>
</td>
</tr>
<tr>
<td class="en">
<p><em>P131 is identified by (identifies)</em></p>
</td>
<td class="en">
<p>use <em>P1</em><em> identified by (identifies)</em></p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">P131_est_identifié_par (identifie)</code><em> </em></p>
</td>
<td>
<p>utiliser <code class="language-plaintext highlighter-rouge">P1_est_identifié_par (identifie)</code></p>
</td>
</tr>
<tr>
<td class="en">
<p><em>P149 is identified by (identifies)</em></p>
</td>
<td class="en">
<p>use <em>P1</em><em> identified by (identifies)</em></p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">P149_est_identifié_par (identifie)</code><em> </em></p>
</td>
<td>
<p>utiliser <code class="language-plaintext highlighter-rouge">P1_est_identifié_par (identifie)</code></p>
</td>
</tr>
<tr>
<td class="en">
<p><em>P178 ends after or with (ends before or at the end of) </em></p>
</td>
<td class="en">
<p>use <em>P184</em><em>i ends with or after the end of</em> instead</p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">P178_se_termine_après_ou_au_moment_de (se_termine_avant_ou_à_la_fin_de)</code></p>
</td>
<td>
<p>utiliser <code class="language-plaintext highlighter-rouge">P184i_</code><code class="language-plaintext highlighter-rouge">se_termine_au_moment_de_ou_après_la_fin_de</code></p>
</td>
</tr>
<tr>
<td class="en">
<p><em>P181 has amount</em></p>
</td>
<td class="en">
<p>E54 Dimension. <em>P90</em><em> has value</em>: E60 Number instead</p>
</td>
<td>
<p><code class="language-plaintext highlighter-rouge">P181_a_pour_quantité</code></p>
</td>
<td>
<p>utiliser <code class="language-plaintext highlighter-rouge">E54_Dimension</code> . <code class="language-plaintext highlighter-rouge">P90_a_pour_valeur</code> : <code class="language-plaintext highlighter-rouge">E60_Nombre</code></p>
</td>
</tr>
<tr>
<td class="en">
<p><sup>*</sup> The properties P114 to P120 have been introduced in the CIDOC CRM extension “Definition of the CRMarchaeo. An Extension of CIDOC CRM to support the archaeological excavation process”, Version 1.5.1, March 2021.</p>
</td>
<td class="en">
</td>
<td>
<p><sup>*</sup> Les propriétés P114 à P120 ont été introduites par l’extension « Definition of the CRMarchaeo. An Extension of CIDOC CRM to support the archaeological excavation process”, Version 1.5.1 qui date de mars 2021. </p>
</td>
<td>
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
<p>OWL Working Group. 2012. « OWL - Semantic Web Standards ». W3C. 11 décembre 2012.<a href="https://www.w3.org/OWL/"><span class="underline"> </span></a><a href="https://www.w3.org/OWL/"><span class="underline">https://www.w3.org/OWL/</span></a>.</p>
<p>RDF Working Group. 2014. « RDF - Semantic Web Standards ». W3C. 25 février 2014.<a href="https://www.w3.org/RDF/"><span class="underline"> </span></a><a href="https://www.w3.org/RDF/"><span class="underline">https://www.w3.org/RDF/</span></a>.</p>
</td>
</tr>
</tbody>
</table>

<h2 id="modifications"><span class="en heading">Amendments - </span>Modifications</h2>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>The amendments can be found in “Amendments of the CIDOC: Conceptual reference Model ver. 7.1: volume B”.</p>
</td>
<td>
<p>Les modifications sont recensées dans le document « Amendments of the CIDOC: Conceptual reference Model ver. 7.1: volume B » [n.d.t. qui n’a pas fait l’objet d’une traduction]. </p>
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
</td>
</tr>
</tbody>
</table>

