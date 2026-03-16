---
layout: page
title: 10. Migration du FRBRoo vers le LRMoo
titleEn: 10. Migration from FRBRoo to LRMoo - 10. Migration du FRBRoo vers le LRMoo
permalink: /lrmoo/v1.0/migration-du-frbroo-vers-le-lrmoo
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
<p>This section consists of a comprehensive list of the classes and properties that were declared in the last approved version of FRBR<sub>OO</sub> (version 2.4, 2015) and provides the corresponding LRM<sub>OO</sub> or CIDOC CRM class or property. The last column indicates briefly whether the class or property was retained or deprecated in LRM<sub>OO</sub>. For those classes and properties that were retained in a transformed version, the change (which might involve renaming) is briefly indicated. For the deprecated classes and properties, the corresponding class or property (or appropriate path) to substitute when implementing LRM<sub>OO</sub> is noted in the second column, with a brief explanation in the last column. This substitute class, property or path is in a number of cases drawn from CIDOC CRM. These recommended correspondences may need to be adjusted to maintain internal consistency when migrating specific implementations of FRBR<sub>OO</sub>, considering usage in the implementation. Some data validation may also be required. The classes and properties listed in section 9 above as to be transferred to CRMsoc are simply indicated as ‘See CRMsoc’ in the LRM<sub>OO</sub> column.</p>
</td>
<td>
<p>Cette section recense une liste exhaustive des classes et propriétés déclarées dans la dernière version approuvée des <em>Fonctionnalités requises des notices bibliographiques, orientation objet </em>(FRBR<sub>OO</sub>) (version 2.4, en 2015) ainsi que de leurs classes et propriétés du <em>Modèle conceptuel pour l’information bibliographique, orientation objet</em> (LRM<sub>OO</sub>) et du <em>Modèle conceptuel de référence du Comité international pour la documentation du Conseil international des musées</em> (CIDOC CRM). </p>
<p>La dernière colonne indique si la classe ou la propriété a été retenue ou dépréciée par LRM<sub>OO</sub> ainsi que, lorsque cela s’applique, les modifications apportées – incluant le renommage de l’entité. Dans le cas des classes et propriétés dépréciées, les classes, propriétés, ou chemins sémantiques de substitution – souvent tirés du CIDOC CRM – sont indiquées dans la seconde colonne en plus d’une explication dans la dernière colonne. Ces correspondances pourraient toutefois nécessiter des ajustements afin d’assurer la cohérence interne lors de la migration d’implémentations spécifiques du FRBR<sub>OO</sub>, et ce en fonction des usages qui en sont faits. La validation des données pourrait elle aussi s’avérer nécessaire. </p>
<p>Les classes et propriétés énumérées dans la section 9 « <a href="https://cidoc-crm-fr.info/lrmoo/v1.0/classes-et-proprietes-frbroo-transferees-au-crmsoc"><span class="underline">Les classes et propriétés du FRBR</span></a><sub><a href="https://cidoc-crm-fr.info/lrmoo/v1.0/classes-et-proprietes-frbroo-transferees-au-crmsoc"><span class="underline">OO</span></a></sub><a href="https://cidoc-crm-fr.info/lrmoo/v1.0/classes-et-proprietes-frbroo-transferees-au-crmsoc"><span class="underline"> transférées à CRM</span></a><sub><a href="https://cidoc-crm-fr.info/lrmoo/v1.0/classes-et-proprietes-frbroo-transferees-au-crmsoc"><span class="underline">SOC</span></a></sub> », lesquelles sont destinées à un transfert vers le <em>Modèle conceptuel de référence pour les phénomènes sociaux</em> (CRM<sub>SOC</sub>) sont identifiées par la mention « Voir CRM<sub>SOC</sub> » dans la colonne dédiée au LRM<sub>OO</sub>. </p>
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

<h2 id="migration-des-classes-frbroo"><span class="en heading">10.1. Migration of FRBR<sub>OO</sub> Classes - </span>10.1. Migration des classes FRBR<sub>OO</sub></h2>

<table>
<tbody>
<tr>
<th>
<p class="en block">FRBR<sub>OO</sub> version 2.4</p>
<p class="en block">~~~~~</p>
<p>FRBR<sub>OO</sub> version 2.4</p>
</th>
<th>
<p class="en block">LRM<sub>OO</sub></p>
<p class="en block">~~~~~</p>
<p>LRM<sub>OO</sub></p>
</th>
<th>
<p class="en block">Changes for LRM<sub>OO</sub></p>
<p class="en block">~~~~~</p>
<p>Changements pour le LRM<sub>OO</sub></p>
</th>
</tr>
<tr>
<td>
<p class="en block">F1 Work </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
</td>
<td>
<p class="en block">F1 Work </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
</td>
<td>
<p class="en block">Retained, editorial scope note revision</p>
<p class="en block">~~~~~</p>
<p>Retenue avec des modifications éditoriales apportées à la note d’application.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">F2 Expression </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F2_Expression</code></p>
</td>
<td>
<p class="en block">F2 Expression </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F2_Expression</code></p>
</td>
<td>
<p class="en block">Retained, editorial scope note revision</p>
<p class="en block">~~~~~</p>
<p>Retenue avec des modifications éditoriales apportées à la note d’application.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">F3 Manifestation Product Type </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F3_Modèle_de_produit_de_la_manifestation</code></p>
</td>
<td>
<p class="en block">Use F3 Manifestation</p>
<p class="en block">and multiply instantiate as E99 Product Type</p>
<p class="en block">~~~~~</p>
<p>Utiliser <code class="language-plaintext highlighter-rouge">F3_Manifestation</code> et procéder à une instanciation multiple avec <code class="language-plaintext highlighter-rouge">E99_Modèle_de_produit</code>.</p>
</td>
<td>
<p class="en block">Revised to be more general, renamed as Manifestation, now a subclass of E73 Information Object. Requires E99 Product Type to express the product type aspects.</p>
<p class="en block">Merged in F24 Publication Expression, revised scope note</p>
<p class="en block">~~~~~</p>
<p>Révisée afin d’élargir le champ d’application et renommée <code class="language-plaintext highlighter-rouge">F3_Manifestation</code>, maintenant une sous-classe de <code class="language-plaintext highlighter-rouge">E73_Objet_informationnel</code> nécessitant une instance de <code class="language-plaintext highlighter-rouge">E99_Modèle_de_produit</code> afin d’exprimer les particularités du type de produit. </p>
<p>Intégrée à <code class="language-plaintext highlighter-rouge">F24_Expression_de_publication</code> avec une note d’application révisée. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F4 Manifestation Singleton </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F4_Manifestation_unique</code></p>
</td>
<td>
<p class="en block">Use F3 Manifestation </p>
<p class="en block">with R7i is exemplified by: F5 Item</p>
<p class="en block">~~~~~</p>
<p>Utiliser <code class="language-plaintext highlighter-rouge">F3_Manifestation</code> avec <code class="language-plaintext highlighter-rouge">R7i_est_exemplifié_par</code> : <code class="language-plaintext highlighter-rouge">F5_Item</code>.</p>
</td>
<td>
<p class="en block">Deprecated. Merged with F3 Manifestation and requires a single instance of F5 Item to be instantiated</p>
<p class="en block">~~~~~</p>
<p>Dépréciée et intégrée à <code class="language-plaintext highlighter-rouge">F3_Manifestation</code> ne nécessitant qu’une seule instance de <code class="language-plaintext highlighter-rouge">F5_Item</code> pour être instanciée. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F5 Item </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F5_Item</code></p>
</td>
<td>
<p class="en block">F5 Item</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F5_Item</code></p>
</td>
<td>
<p class="en block">Retained, expanded scope note</p>
<p class="en block">~~~~~</p>
<p>Retenue avec une note d’application élargie. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F6 Concept </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F6_Concept</code></p>
</td>
<td>
<p class="en block">Use E28 Conceptual Object</p>
<p class="en block">~~~~~</p>
<p>Utiliser <code class="language-plaintext highlighter-rouge">E28_Objet_conceptuel</code>.</p>
</td>
<td>
<p class="en block">Deprecated classes exactly equivalent to CRM classes</p>
<p class="en block">~~~~~</p>
<p>Classes dépréciées correspondant de manière exacte aux classes du CIDOC CRM. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F7 Object </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F7_Objet</code></p>
</td>
<td>
<p class="en block">Use E18 Physical Thing</p>
<p class="en block">~~~~~</p>
<p>Utiliser <code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code>.</p>
</td>
<td>
<p class="en block">Deprecated classes exactly equivalent to CRM classes</p>
<p class="en block">~~~~~</p>
<p>Classes dépréciées correspondant de manière exacte aux classes du CIDOC CRM. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F8 Event </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F8_Évènement</code></p>
</td>
<td>
<p class="en block">Use E4 Period</p>
<p class="en block">~~~~~</p>
<p>Utiliser <code class="language-plaintext highlighter-rouge">E4_Période</code>.</p>
</td>
<td>
<p class="en block">Deprecated classes exactly equivalent to CRM classes</p>
<p class="en block">~~~~~</p>
<p>Classes dépréciées correspondant de manière exacte aux classes du CIDOC CRM. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F9 Place </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F9_Lieu</code></p>
</td>
<td>
<p class="en block">Use E52 Place</p>
<p class="en block">~~~~~</p>
<p>Utiliser <code class="language-plaintext highlighter-rouge">E52_Intervalle_temporel</code>.</p>
</td>
<td>
<p class="en block">Deprecated classes exactly equivalent to CRM classes</p>
<p class="en block">~~~~~</p>
<p>Classes dépréciées correspondant de manière exacte aux classes du CIDOC CRM. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F10 Person </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F10_Personne</code></p>
</td>
<td>
<p class="en block">Use E21 Person</p>
<p class="en block">~~~~~</p>
<p>Utiliser <code class="language-plaintext highlighter-rouge">E21_Personne</code>.</p>
</td>
<td>
<p class="en block">Deprecated classes exactly equivalent to CRM classes</p>
<p class="en block">~~~~~</p>
<p>Classes dépréciées correspondant de manière exacte aux classes du CIDOC CRM. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F11 Corporate Body </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F11_Peronne_morale</code></p>
</td>
<td>
<p class="en block">F11 Corporate Body</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F11_Personne_morale</code></p>
</td>
<td>
<p class="en block">Retained, modified superclass to F55 Collective Agent</p>
<p class="en block">~~~~~</p>
<p>Retenue, mais relevant dorénavant de la super-classe <code class="language-plaintext highlighter-rouge">F55_Agent_collectif</code>. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F12 Nomen </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F12_Nomen</code></p>
</td>
<td>
<p class="en block">F12 Nomen</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F12_Nomen</code></p>
</td>
<td>
<p class="en block">Considerably modified</p>
<p class="en block">Merged in F35 Nomen Use Statement</p>
<p class="en block">~~~~~</p>
<p>Modifiée considérablement et intégrée à <code class="language-plaintext highlighter-rouge">F35_Énoncé_d’utilisation_de_nomen</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">F13 Identifier </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F13_Identifiant</code></p>
</td>
<td>
<p class="en block">Use E42 Identifier</p>
<p class="en block">Else use F12 Nomen</p>
<p class="en block">~~~~~</p>
<p>Utiliser <code class="language-plaintext highlighter-rouge">E42_Identifiant</code> ou <code class="language-plaintext highlighter-rouge">F12_Nomen</code>.</p>
</td>
<td>
<p class="en block">Deprecated classes exactly equivalent to CRM classes</p>
<p class="en block">~~~~~</p>
<p>Classes dépréciées correspondant de manière exacte aux classes du CIDOC CRM. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F14 Individual Work </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F14_Œuvre_individuelle</code></p>
</td>
<td>
<p class="en block">Use superclass F1 Work</p>
<p class="en block">Else, do not migrate</p>
<p class="en block">~~~~~</p>
<p>Utiliser la super-classe <code class="language-plaintext highlighter-rouge">F1_Œuvre</code> ou ne pas procéder à la migration. </p>
</td>
<td>
<p class="en block">Deprecated unneeded subclasses of F1 Work</p>
<p class="en block">If F14 Individual Work was implemented with a one-to-one correspondence to F22 Self-Contained Expression and an instance of F15 Complex Work or F1 Work existed for all instances of F14, then the instances of F14 Individual Work are redundant and should not be migrated. In this case, also do not migrate instances of property <em>R9 is realised in (realises)</em></p>
<p class="en block">~~~~~</p>
<p>Sous-classes de <code class="language-plaintext highlighter-rouge">F1_Œuvre</code> n’étant plus nécessaire et ayant été dépréciées. </p>
<p>Lorsque les conditions suivantes sont réunies, les instances de <code class="language-plaintext highlighter-rouge">F14_Œuvre_individuelle</code> sont redondantes et ne devraient pas être migrées :</p>
<ul><li><p>une instance de <code class="language-plaintext highlighter-rouge">F14_Œuvre_individuelle</code> a été implémentée en tant qu équivalente de <code class="language-plaintext highlighter-rouge">F22_Expression_autonome</code> ;</p>
</li>
<li><p>une instance de <code class="language-plaintext highlighter-rouge">F15_Œuvre_complexe</code> ou de <code class="language-plaintext highlighter-rouge">F1_Œuvre</code> existait pour chacune de ces instances de <code class="language-plaintext highlighter-rouge">F14_Œuvre_individuelle</code>.</p>
</li></ul>
<p>Les instances de <code class="language-plaintext highlighter-rouge">R9_est_réalisé_dans (réalise)</code> ne devraient pas non plus, dans ces circonstances, faire l’objet d’une migration. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F15 Complex Work </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F15_Œuvre_complexe</code></p>
</td>
<td>
<p class="en block">Use superclass F1 Work</p>
<p class="en block">~~~~~</p>
<p>Utiliser la super-classe <code class="language-plaintext highlighter-rouge">F1_Œuvre</code>.</p>
</td>
<td>
<p class="en block">Deprecated unneeded subclasses of F1 Work</p>
<p class="en block">~~~~~</p>
<p>Sous-classes de <code class="language-plaintext highlighter-rouge">F1_Œuvre</code> n’étant plus nécessaires et ayant été dépréciées. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F16 Container Work </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F16_Œuvre-contenant</code></p>
</td>
<td>
<p class="en block">Use superclass F1 Work</p>
<p class="en block">~~~~~</p>
<p>Utiliser la super-classe <code class="language-plaintext highlighter-rouge">F1_Œuvre</code>.</p>
</td>
<td>
<p class="en block">Deprecated unneeded subclasses of F1 Work</p>
<p class="en block">~~~~~</p>
<p>Sous-classes de <code class="language-plaintext highlighter-rouge">F1_Œuvre</code> n’étant plus nécessaires et ayant été dépréciées. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F17 Aggregation Work </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F17_Œuvre_agrégeante</code></p>
</td>
<td>
<p class="en block">Use superclass F1 Work</p>
<p class="en block">~~~~~</p>
<p>Utiliser la super-classe <code class="language-plaintext highlighter-rouge">F1_Œuvre</code>.</p>
</td>
<td>
<p class="en block">Deprecated unneeded subclasses of F1 Work</p>
<p class="en block">~~~~~</p>
<p>Sous-classes de <code class="language-plaintext highlighter-rouge">F1_Œuvre</code> n’étant plus nécessaires et ayant été dépréciées. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F18 Serial Work </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F18_Œuvre_de_publication_en_série</code></p>
</td>
<td>
<p class="en block">F18 Serial Work</p>
<p class="en block">Else use superclass F1 Work</p>
<p class="en block">~~~~~</p>
<p>Utiliser <code class="language-plaintext highlighter-rouge">F18_Œuvre_de_publication_en_série</code> ou la super-classe <code class="language-plaintext highlighter-rouge">F1_Œuvre</code>.</p>
</td>
<td>
<p class="en block">Now a direct subclass of F1 Work</p>
<p class="en block">Implement only in conjunction with PRESS<sub>OO</sub></p>
<p class="en block">~~~~~</p>
<p>Dorénavant une sous-classe directe de <code class="language-plaintext highlighter-rouge">F1_Œuvre</code>.</p>
<p>Ne doit être implémentée que de concert avec PRESS<sub>OO</sub>. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F19 Publication Work </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F19_Œuvre_de_publication</code></p>
</td>
<td>
<p class="en block">Use superclass F1 Work</p>
<p class="en block">~~~~~</p>
<p>Utiliser la super-classe <code class="language-plaintext highlighter-rouge">F1_Œuvre</code>.</p>
</td>
<td>
<p class="en block">Deprecated unneeded subclasses of F1 Work</p>
<p class="en block">~~~~~</p>
<p>Sous-classes de <code class="language-plaintext highlighter-rouge">F1_Œuvre</code> n’étant plus nécessaires et ayant été dépréciées. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F20 Performance Work </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F20_Œuvre_de_performance</code> </p>
</td>
<td>
<p class="en block">Use superclass F1 Work</p>
<p class="en block">~~~~~</p>
<p>Utiliser la super-classe <code class="language-plaintext highlighter-rouge">F1_Œuvre</code>.</p>
</td>
<td>
<p class="en block">Deprecated unneeded subclasses of F1 Work</p>
<p class="en block">~~~~~</p>
<p>Sous-classes de <code class="language-plaintext highlighter-rouge">F1_Œuvre</code> n’étant plus nécessaires et ayant été dépréciées. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F21 Recording Work </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F21_Œuvre_d’enregistrement</code></p>
</td>
<td>
<p class="en block">Use superclass F1 Work</p>
<p class="en block">~~~~~</p>
<p>Utiliser la super-classe <code class="language-plaintext highlighter-rouge">F1_Œuvre</code>.</p>
</td>
<td>
<p class="en block">Deprecated unneeded subclasses of F1 Work</p>
<p class="en block">~~~~~</p>
<p>Sous-classes de <code class="language-plaintext highlighter-rouge">F1_Œuvre</code> n’étant plus nécessaires et ayant été dépréciées. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F22 Self-Contained Expression </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F22_Expression_autonome</code></p>
</td>
<td>
<p class="en block">Use superclass F2 Expression</p>
<p class="en block">~~~~~</p>
<p>Utiliser la super-classe <code class="language-plaintext highlighter-rouge">F2_Expression</code>.</p>
</td>
<td>
<p class="en block">Deprecated, merged into its superclass F2 Expression</p>
<p class="en block">~~~~~</p>
<p>Dépréciée et intégrée à la super-classe <code class="language-plaintext highlighter-rouge">F2_Expression</code>. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F23 Expression Fragment </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F23_Fragment_d’expression</code></p>
</td>
<td>
<p class="en block">Use E90 Symbolic Object</p>
<p class="en block">~~~~~</p>
<p>Utiliser <code class="language-plaintext highlighter-rouge">E90_Objet_symbolique</code>.</p>
</td>
<td>
<p class="en block">Deprecated</p>
<p class="en block">~~~~~</p>
<p>Dépréciée</p>
</td>
</tr>
<tr>
<td>
<p class="en block">F24 Publication Expression </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F24_Expression_de_publication</code></p>
</td>
<td>
<p class="en block">Use F3 Manifestation</p>
<p class="en block">~~~~~</p>
<p>Utiliser <code class="language-plaintext highlighter-rouge">F3_Manifestation</code>.</p>
</td>
<td>
<p class="en block">Merged with F3 Manifestation</p>
<p class="en block">Note that any instances of the property <em>R4 embodies (is embodied in)</em> originating with domain F24 Publication Expression, should not be migrated</p>
<p class="en block">~~~~~</p>
<p>Intégrée à <code class="language-plaintext highlighter-rouge">F3_Manifestation</code>. </p>
<p>Aucune instance de la propriété <code class="language-plaintext highlighter-rouge">R4_incarne (est_incarné_dans)</code> originant du domaine <code class="language-plaintext highlighter-rouge">F24_Expression_de_publication</code> ne devrait être migrée. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F25 Performance Plan </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F25_Plan_de_performance</code></p>
</td>
<td>
<p class="en block">Use superclass F2 Expression</p>
<p class="en block">and multiply instantiate as E29 Design or Procedure</p>
<p class="en block">~~~~~</p>
<p>Utiliser la super-classe <code class="language-plaintext highlighter-rouge">F2_Expression</code> et procéder à une instanciation multiple avec <code class="language-plaintext highlighter-rouge">E29_Conceptualisation_ou_procédure</code>.</p>
</td>
<td>
<p class="en block">Deprecated unneeded subclass of F2 Expression. Requires E29 Design or Procedure to express the plan aspects</p>
<p class="en block">~~~~~</p>
<p>Sous-classe de <code class="language-plaintext highlighter-rouge">F2_Expression</code> n’étant plus nécessaire et exigeant dorénavant l’usage de <code class="language-plaintext highlighter-rouge">E29_Conceptualisation_ou_procédure</code> pour exprimer les particularités du plan. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F26 Recording </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F26_Enregistrement</code></p>
</td>
<td>
<p class="en block">Use superclass F2 Expression</p>
<p class="en block">~~~~~</p>
<p>Utiliser la super-classe <code class="language-plaintext highlighter-rouge">F2_Expression</code>.</p>
</td>
<td>
<p class="en block">Deprecated unneeded subclass of F2 Expression</p>
<p class="en block">~~~~~</p>
<p>Sous-classe de <code class="language-plaintext highlighter-rouge">F2_Expression</code> n’étant plus nécessaire.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">F27 Work Conception </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F27_Conceptualisation_d’oeuvre</code></p>
</td>
<td>
<p class="en block">F27 Work Creation </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F27_Création_d’œuvre</code></p>
</td>
<td>
<p class="en block">Retained, renamed, revised scope note to focus on creation rather than inception of the F1 Work</p>
<p class="en block">~~~~~</p>
<p>Retenue et renommée avec une note d’application révisée afin de mettre l’accent sur la création, plutôt que l’inception, d’une instance de <code class="language-plaintext highlighter-rouge">F1_Œuvre</code>. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F28 Expression Creation </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F28_Création_d’expression</code></p>
</td>
<td>
<p class="en block">F28 Expression Creation </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F28_Création_d’expression</code></p>
</td>
<td>
<p class="en block">Retained, editorial scope note revision</p>
<p class="en block">~~~~~</p>
<p>Retenue avec des modifications éditoriales apportées à la note d’application.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">F29 Recording Event </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F29_Évènement_d’enregistrement</code></p>
</td>
<td>
<p class="en block">Use superclass F28 Expression Creation</p>
<p class="en block">~~~~~</p>
<p>Utiliser la super-classe <code class="language-plaintext highlighter-rouge">F28_Création_d’expression</code>.</p>
</td>
<td>
<p class="en block">Deprecated unneeded subclass of F28 Expression Creation</p>
<p class="en block">~~~~~</p>
<p>Sous-classe de <code class="language-plaintext highlighter-rouge">F28_Création_d’expression</code> n’étant plus nécessaire.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">F30 Publication Event </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F30_Évènemenr_de_publication</code></p>
</td>
<td>
<p class="en block">F30 Manifestation Creation</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F30_Création_de_manifestation</code></p>
</td>
<td>
<p class="en block">Retained, renamed Manifestation Creation, revised scope note</p>
<p class="en block">~~~~~</p>
<p>Retenue et renommée <code class="language-plaintext highlighter-rouge">F30_Création_de_manifestation</code> avec une note d’application révisée. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F31 Performance </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F31_Performance</code></p>
</td>
<td>
<p class="en block">F31 Performance </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F31_Performance</code></p>
</td>
<td>
<p class="en block">Retained, scope note revised</p>
<p class="en block">~~~~~</p>
<p>Retenue avec une note d’application révisée. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F32 Carrier Production Event </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F32_Évènement_de_production_de_support</code></p>
</td>
<td>
<p class="en block">F32 Item Production Event </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F32_Évènement_de_production_d’item</code></p>
</td>
<td>
<p class="en block">Retained, renamed Item Production Event, editorial scope note revision</p>
<p class="en block">~~~~~</p>
<p>Retenue et renommée <code class="language-plaintext highlighter-rouge">F32_Évènement_de_production_d’item</code> avec des modifications éditoriales apportées à la note d’application. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F33 Reproduction Event </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F33_Évènement_de_reproduction</code></p>
</td>
<td>
<p class="en block">F33 Reproduction Event </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F33_Évènement_de_reproduction</code></p>
</td>
<td>
<p class="en block">Retained, editorial scope note revision. </p>
<p class="en block">Added superclass F30 Manifestation Creation</p>
<p class="en block">~~~~~</p>
<p>Retenue avec des modifications éditoriales apportées à la note d’application. </p>
<p>Ajout de la super-classe <code class="language-plaintext highlighter-rouge">F30_Création_de_manifestation</code>. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F34 KOS </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F34_Système_d’organisation_des_connaissances</code></p>
</td>
<td>
<p class="en block">Use superclass F2 Expression</p>
<p class="en block">~~~~~</p>
<p>Utiliser la super-classe <code class="language-plaintext highlighter-rouge">F2_Expression</code>.</p>
</td>
<td>
<p class="en block">Deprecated unneeded subclass of F2 Expression</p>
<p class="en block">~~~~~</p>
<p>Sous-classe de <code class="language-plaintext highlighter-rouge">F2_Expression</code> n’étant plus nécessaire.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">F35 Nomen Use Statement </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F35_Énoncé_d’utilisation_de_nomen</code></p>
</td>
<td>
<p class="en block">Use F12 Nomen </p>
<p class="en block">~~~~~</p>
<p>Utiliser <code class="language-plaintext highlighter-rouge">F12_Nomen</code>.</p>
</td>
<td>
<p class="en block">Merged into revised F12 Nomen</p>
<p class="en block">~~~~~</p>
<p>Intégrée à une note d’application révisée de <code class="language-plaintext highlighter-rouge">F12_Nomen</code>. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F36 Script Conversion </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F36_Conversion_de_script</code></p>
</td>
<td>
<p class="en block">F36 Script Conversion </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F36_Conversion_de_script</code></p>
</td>
<td>
<p class="en block">Retained</p>
<p class="en block">~~~~~</p>
<p>Retenue</p>
</td>
</tr>
<tr>
<td>
<p class="en block">F38 Character </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F38_Personne_fictive</code></p>
</td>
<td>
<p class="en block">See CRMsoc</p>
<p class="en block">~~~~~</p>
<p>Voir CRM<sub>SOC</sub></p>
</td>
<td>
<p class="en block">Moved to other family model</p>
<p class="en block">~~~~~</p>
<p>Transférée à un autre modèle conceptuel de l’ensemble du CIDOC CRM. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F39 Family </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F39_Famille</code></p>
</td>
<td>
<p class="en block">F39 Family </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F39_Famille</code></p>
</td>
<td>
<p class="en block">Retained, modified superclass to F55 Collective Agent </p>
<p class="en block">~~~~~</p>
<p>Retenue, mais relevant dorénavant de la super-classe <code class="language-plaintext highlighter-rouge">F55_Agent_collectif</code>. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F40 Identifier Assignment </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F40_Assignation_d’identifiant</code></p>
</td>
<td>
<p class="en block">Use E15 Identifier Assignment</p>
<p class="en block">~~~~~</p>
<p>Utiliser <code class="language-plaintext highlighter-rouge">E15_Assignation_d’identifiant</code>.</p>
</td>
<td>
<p class="en block">Deprecated classes exactly equivalent to CRM classes</p>
<p class="en block">~~~~~</p>
<p>Classes dépréciées correspondant de manière exacte aux classes du CIDOC CRM. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F41 Representative Manifestation Assignment </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F41_Assignation_de_manifestation_représentative</code></p>
</td>
<td>
<p class="en block">Use E13 Attribute Assignment to label an instance of manifestation as representative of the expression</p>
<p class="en block">~~~~~</p>
<p>Utiliser <code class="language-plaintext highlighter-rouge">E13_Assignation_d’attribut</code> pour identifier une instance de <code class="language-plaintext highlighter-rouge">F3_Manifestation</code> en tant que représentative de l’expression.</p>
</td>
<td>
<p class="en block">Deprecated, use the superclass to assign the type (P2 has type: E55 Type = “representative”) to the F3 Manifestation </p>
<p class="en block">~~~~~</p>
<p>Dépréciée, utiliser la super-classe appropriée pour assigner le type (<code class="language-plaintext highlighter-rouge">P2_a_pour_type</code> : <code class="language-plaintext highlighter-rouge">E55_Type</code> = « Représentative ») à l’instance de <code class="language-plaintext highlighter-rouge">F3_Manifestation</code>. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F42 Representative Expression Assignment </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F42_Assignation_d’expression_représentative</code></p>
</td>
<td>
<p class="en block">Use E13 Attribute Assignment to label an instance of expression as representative of the work</p>
<p class="en block">~~~~~</p>
<p>Utiliser <code class="language-plaintext highlighter-rouge">E13_Assignation_d’attribut</code> pour identifier une instance de <code class="language-plaintext highlighter-rouge">F2_Expression</code>en tant que représentative de l’expression.</p>
</td>
<td>
<p class="en block">Deprecated, use the superclass to assign the type (P2 has type: E55 Type = “representative”) to the F2 Expression</p>
<p class="en block">~~~~~</p>
<p>Dépréciée, utiliser la super-classe appropriée pour assigner le type (<code class="language-plaintext highlighter-rouge">P2_a_pour_type</code> : <code class="language-plaintext highlighter-rouge">E55_Type</code> = « Représentative ») à l’instance de <code class="language-plaintext highlighter-rouge">F2_Expression</code>. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F43 Identifier Rule </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F43_Règle_d’identifiant</code></p>
</td>
<td>
<p class="en block">Use superclass E29 Design or Procedure</p>
<p class="en block">and multiply instantiate as F2 Expression</p>
<p class="en block">~~~~~</p>
<p>Utiliser la super-classe <code class="language-plaintext highlighter-rouge">E29_Conceptualisation_ou_procédure</code> et procéder à une instanciation multiple avec <code class="language-plaintext highlighter-rouge">F2_Expression</code>.</p>
</td>
<td>
<p class="en block">Deprecated unneeded subclass</p>
<p class="en block">~~~~~</p>
<p>Sous-classe dépréciée n’étant plus nécessaire. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F44 Bibliographic Agency </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F44_Agence_bibliographique</code></p>
</td>
<td>
<p class="en block">Use superclass F11 Corporate Body</p>
<p class="en block">~~~~~</p>
<p>Utiliser la super-classe <code class="language-plaintext highlighter-rouge">F11_Personne_morale</code>.</p>
</td>
<td>
<p class="en block">Deprecated unneeded subclass</p>
<p class="en block">~~~~~</p>
<p>Sous-classe dépréciée n’étant plus nécessaire. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F50 Controlled Access Point </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F50_Point_d’accès_contrôlé</code></p>
</td>
<td>
<p class="en block">Use superclass F12 Nomen</p>
<p class="en block">~~~~~</p>
<p>Utiliser la super-classe <code class="language-plaintext highlighter-rouge">F12_Nomen</code>.</p>
</td>
<td>
<p class="en block">Deprecated unneeded subclass</p>
<p class="en block">~~~~~</p>
<p>Sous-classe dépréciée n’étant plus nécessaire. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F51 Pursuit </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F51_Pratique</code></p>
</td>
<td>
<p class="en block">See CRMsoc</p>
<p class="en block">~~~~~</p>
<p>Voir CRM<sub>SOC</sub></p>
</td>
<td>
<p class="en block">Moved to other family model</p>
<p class="en block">~~~~~</p>
<p>Transférée à un autre modèle conceptuel de l’ensemble du CIDOC CRM. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F52 Name Use Activity </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F52_Activité_d’utilisation_du_nom</code></p>
</td>
<td>
<p class="en block">See CRMsoc</p>
<p class="en block">~~~~~</p>
<p>Voir CRM<sub>SOC</sub></p>
</td>
<td>
<p class="en block">Moved to other family model, revised scope note</p>
<p class="en block">~~~~~</p>
<p>Transférée à un autre modèle conceptuel de l’ensemble du CIDOC CRM avec une note d’application révisée. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F53 Material Copy </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F53_Copie_matérielle</code></p>
</td>
<td>
<p class="en block">Use F5 Item</p>
<p class="en block">and multiply instantiate as E25 Human-Made Feature</p>
<p class="en block">~~~~~</p>
<p>Utiliser <code class="language-plaintext highlighter-rouge">F5_Item</code> et procéder à une instanciation multiple avec <code class="language-plaintext highlighter-rouge">E25_Caractéristique_élaborée_par_l’humain</code>.</p>
</td>
<td>
<p class="en block">Deprecated overly specialized class in favour of multiple instantiation</p>
<p class="en block">~~~~~</p>
<p>Classe trop spécifique dépréciée en faveur d’instanciations multiples. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">F54 Utilised Information Carrier </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F54_Support_informationnel_utilisé</code></p>
</td>
<td>
<p class="en block">Use subclass F5 Item</p>
<p class="en block">and multiply instantiate as E22 Human-Made Object</p>
<p class="en block">~~~~~</p>
<p>Utiliser <code class="language-plaintext highlighter-rouge">F5_Item</code> et procéder à une instanciation multiple avec <code class="language-plaintext highlighter-rouge">E22_Objet_élaboré_par_l’humain</code>.</p>
</td>
<td>
<p class="en block">Deprecated unneeded superclass in favour of multiple instantiation</p>
<p class="en block">~~~~~</p>
<p>Super-classe n’étant plus nécessaire dépréciée en faveur d’instanciations multiples. </p>
</td>
</tr>
<tr>
<td>
</td>
<td>
</td>
<td>
</td>
</tr>
<tr>
<td>
<p class="en block"><strong>New</strong></p>
<p class="en block">~~~~~</p>
<p>Nouvelle</p>
</td>
<td>
<p class="en block">F55 Collective Agent</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F55_Agent_collectif</code></p>
</td>
<td>
<p class="en block">Added as an equivalent to LRM-E8 Collective Agent</p>
<p class="en block">New class, subclass of E74 Group, superclass of F11 Corporate Body and F39 Family</p>
<p class="en block">~~~~~</p>
<p>Ajout à titre d’équivalent à la classe <code class="language-plaintext highlighter-rouge">LRM-E8-Agent_collectif</code>.</p>
<p>Nouvelle classe qui est aussi une sous-classe de <code class="language-plaintext highlighter-rouge">E74_Groupe</code> et une super-classe de <code class="language-plaintext highlighter-rouge">F11_Personne_morale</code> ainsi que de <code class="language-plaintext highlighter-rouge">F39_Famille</code>.</p>
</td>
</tr>
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




<h2 id="migration-des-proprietes-frbroo"><span class="en heading">10.2. Migration of FRBR<sub>OO</sub> Properties - </span>10.2. Migration des propriétés FRBR<sub>OO</sub></h2>


<table>
<tbody>
<tr>
<th>
<p class="en block">FRBR<sub>OO</sub> version 2.4</p>
<p class="en block">~~~~~</p>
<p>FRBR<sub>OO</sub> version 2.4</p>
</th>
<th>
<p class="en block">LRM<sub>OO</sub></p>
<p class="en block">~~~~~</p>
<p>LRM<sub>OO</sub></p>
</th>
<th>
<p class="en block">Changes for LRM<sub>OO</sub></p>
<p class="en block">~~~~~</p>
<p>Changements pour le LRM<sub>OO</sub></p>
</th>
</tr>
<tr>
<td>
<p class="en block">R1 is logical successor of (has successor)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R1_a_pour_successeure_logique (a_pour_successeure)</code></p>
</td>
<td>
<p class="en block">R1 is logical successor of (has successor)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R1_est_le_successeur_logique_de (a_pour_successeur)</code></p>
</td>
<td>
<p class="en block">Retained</p>
<p class="en block">~~~~~</p>
<p>Retenue</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R2 is derivative of (has derivative)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R2_est_dérivée_de (a_pour_dérivation)</code></p>
</td>
<td>
<p class="en block">R2 is derivative of (has derivative)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R2_est_dérivé_de (a_pour_dérivé)</code></p>
</td>
<td>
<p class="en block">Retained, now subproperty of new property R68</p>
<p class="en block">~~~~~</p>
<p>Retenue, maintenant une sous-propriété de <code class="language-plaintext highlighter-rouge">R68_est_inspiré_de (est_source_d’inspiration_pour)</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R3 is realised in (realises)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R3_est_réalisé_dans (réalise)</code></p>
</td>
<td>
<p class="en block">R3 is realised in (realises)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R3_est_réalisé_dans (réalise)</code></p>
</td>
<td>
<p class="en block">Retained, revised range to F2 Expression, superclass of deprecated F22 Self-contained Expression, quantification revised, deprecated .1 property</p>
<p class="en block">~~~~~</p>
<p>Retenue avec une étendue révisée à <code class="language-plaintext highlighter-rouge">F2_Expression</code>, super-classe de l’entité dépréciée <code class="language-plaintext highlighter-rouge">F22_Expression_autonome</code>, une révision de la quantification, et la dépréciation de la propriété « .1 » associée.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R4 carriers provided by (comprises carriers of)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R4_supports_fournis_par (comprend_les_supports_de)</code></p>
</td>
<td>
<p class="en block">R4 embodies (is embodied in)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R4_incarne (est_incarné_dans)</code></p>
</td>
<td>
<p class="en block">Retained, renamed (and reversed direction), superproperty modified, quantification revised</p>
<p class="en block">~~~~~</p>
<p>Retenue, renommée en direction inverse, avec une super-propriété modifiée et une quantification révisée.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R5 has component (is component of)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R5_a_pour_partie (fait_partie_de)</code></p>
</td>
<td>
<p class="en block">R5 has component (is component of)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R5_a_pour_composant (est_le_composant_de)</code></p>
</td>
<td>
<p class="en block">Retained, revised range to F2 Expression, superclass of deprecated F22 Self-contained Expression</p>
<p class="en block">~~~~~</p>
<p>Retenue, avec une révision de l’étendue à <code class="language-plaintext highlighter-rouge">F2_Expression</code>, super-classe de l’entité dépréciée <code class="language-plaintext highlighter-rouge">F22_Expression_autonome</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R6 carries (is carried by)</p>
<p class="en block">D: F54; R: F24</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R6_porte (est_porté_par)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F54_Support_informationnel_utilisé</code> ; Portée : <code class="language-plaintext highlighter-rouge">F24_Expression_de_publication</code>.</p>
</td>
<td>
<p class="en block">Use R7 exemplifies (is exemplified by)</p>
<p class="en block">D: F5; R: F3</p>
<p class="en block">~~~~~</p>
<p>Utiliser <code class="language-plaintext highlighter-rouge">R7_exemplifie (est_exemplifié_par)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F5_Item</code> ; Portée : <code class="language-plaintext highlighter-rouge">F3_Manifestation</code> </p>
</td>
<td>
<p class="en block">Merged into R7, as its domain, F54 Utilised Information Carrier, is deprecated in favour of F5 Item, and its range, F24 Publication Expression, is merged with F3 Manifestation</p>
<p class="en block">~~~~~</p>
<p>Intégrée à <code class="language-plaintext highlighter-rouge">R7_exemplifie (est_exemplifié_par)</code> avec pour domaine <code class="language-plaintext highlighter-rouge">F5_Item</code>  au lieu de <code class="language-plaintext highlighter-rouge">F54_Support_informationnel_utilisé</code>, et avec pour portée <code class="language-plaintext highlighter-rouge">F3_Manifestation</code> car <code class="language-plaintext highlighter-rouge">F24_Expression_de_publication</code> y est intégrée. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">R7 is example of (has example)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R7_est_un_exemple_de (a_pour_exemple)</code></p>
</td>
<td>
<p class="en block">R7 exemplifies (is exemplified by)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R7_exemplifie (est_exemplifié_par)</code></p>
</td>
<td>
<p class="en block">Retained, renamed, superproperty modified, scope note revised</p>
<p class="en block">~~~~~</p>
<p>Retenue et renommée avec une note d’application révisée et une super-propriété révisée.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R8 consists of (forms part of)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R8_consiste_en (fait_partie_de)</code></p>
</td>
<td>
<p class="en block">R8 combines (is combined to form)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R8_combine (est_combiné_pour_former)</code></p>
</td>
<td>
<p class="en block">Retained, renamed, modified domain and range to F12 Nomen, replaced superproperty with a shortcut statement</p>
<p class="en block">~~~~~</p>
<p>Retenue et renommée avec un domaine (<code class="language-plaintext highlighter-rouge">F12_Nomen</code>) et une portée (<code class="language-plaintext highlighter-rouge">F12_Nomen</code>) modifiés ainsi que sa super-propriété remplacée par un raccourci.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R9 is realised in (realises)</p>
<p class="en block">D: F14; R: F22</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R9_est_réalisé_dans (réalise)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F14_Œuvre_individuelle</code> ; Portée : <code class="language-plaintext highlighter-rouge">F22_Expression_autonome</code>.</p>
</td>
<td>
<p class="en block">Use superproperty R3 is realised in (realises)</p>
<p class="en block">D: F1; R: F2</p>
<p class="en block">Else, if F14 Individual Work is not migrated, do not migrate</p>
<p class="en block">~~~~~</p>
<p>Utiliser la super-propriété <code class="language-plaintext highlighter-rouge">R3_est_réalisé_dans (réalise)</code>.</p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F1_Œuvre</code> ; Portée : <code class="language-plaintext highlighter-rouge">F2_Expression</code>.</p>
<p>Si <code class="language-plaintext highlighter-rouge">F14_Œuvre_individuelle</code> n’a pas fait l’objet d’une migration, ne pas procéder à la migration. </p>
</td>
<td>
<p class="en block">Deprecated unneeded subproperty. Its domain, F14 Individual Work, is deprecated in favour of F1 Work, its range, F22 Self-contained Expression, in favour of F2 Expression</p>
<p class="en block">If F14 Individual Work is not migrated (see note at F14 Individual Work), then the migrated instances of this property would produce instances of <em>R3 is realised in (realises)</em> redundant with those originally declared, and should not be migrated</p>
<p class="en block">~~~~~</p>
<p>Sous-propriété superflue dépréciée dont le domaine (<code class="language-plaintext highlighter-rouge">F14_Œuvre_individuelle</code>) est déprécié en faveur de <code class="language-plaintext highlighter-rouge">F1_Œuvre</code> de même que la portée (<code class="language-plaintext highlighter-rouge">F22_Expression_autonome</code>) en faveur de <code class="language-plaintext highlighter-rouge">F2_Expression</code>. </p>
<p>Si <code class="language-plaintext highlighter-rouge">F14_Œuvre_individuelle</code> n’a pas fait l’objet d’une migration (voir note), les instances de cette propriété produiront des instances de <code class="language-plaintext highlighter-rouge">R3_est_réalisé_dans (réalise)</code> qui seront redondantes des instances initialement déclarées et qui ne devraient pas faire l’objet d’une migration. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">R10 has member (is member of)</p>
<p class="en block">D: F15; R: F1</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R10_a_pour_composant (est_composant_de)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F15_Œuvre_complexe</code> ; Portée : <code class="language-plaintext highlighter-rouge">F1_Œuvre</code>.</p>
</td>
<td>
<p class="en block">R10 is member of (has member)</p>
<p class="en block">D: F1; R: E28</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R10_est_composant_de (a_pour_composant)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F1_Œuvre</code> ; Portée : <code class="language-plaintext highlighter-rouge">E28_Objet_conceptuel</code> </p>
</td>
<td>
<p class="en block">Retained, reversed direction, revised range to E28 Conceptual Object, quantification revised, scope note revised</p>
<p class="en block">~~~~~</p>
<p>Retenue en direction inversée avec une portée révisée à <code class="language-plaintext highlighter-rouge">E28_Objet_conceptuel</code> ainsi qu’une quantification et une note d’application révisée</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R11 has issuing rule (is issuing rule of)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R11_a_pour_règle_d'émission (est_règle_d'émission_de)</code></p>
</td>
<td>
<p class="en block">R11 has issuing rule (is issuing rule of)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R11_a_pour_règle_d’émission (est_la_règle_d’émission_de) [PRESS</code><sub><code class="language-plaintext highlighter-rouge">OO</code></sub><code class="language-plaintext highlighter-rouge">]</code></p>
</td>
<td>
<p class="en block">Implement only in conjunction with PRESS<sub>OO</sub>. Shortcut statement added</p>
<p class="en block">~~~~~</p>
<p>N’implémenter que de concert avec PRESS<sub>OO</sub> ainsi qu’avec un raccourci</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R12 is realised in (realises)</p>
<p class="en block">D: F20; R: F25</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R12_est_réalisé_dans (réalise)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F20_Œuvre_de_performance</code> ; Portée : <code class="language-plaintext highlighter-rouge">F25_Plan_de_performance</code>.</p>
</td>
<td>
<p class="en block">Use superproperty R3 is realised in (realises)</p>
<p class="en block">~~~~~</p>
<p>Utiliser la super-propriété <code class="language-plaintext highlighter-rouge">R3_est_réalisé_dans (réalise)</code>.</p>
</td>
<td>
<p class="en block">Deprecated unneeded subproperty. Its domain, F20 Performance Work, is deprecated in favour of F1 Work, its range, F25 Performance Plan, in favour of F2 Expression</p>
<p class="en block">~~~~~</p>
<p>Sous-propriété superflue dépréciée dont le domaine (<code class="language-plaintext highlighter-rouge">F20_Œuvre_de_performance</code>) est déprécié en faveur de <code class="language-plaintext highlighter-rouge">F1_Œuvre</code> de même que la portée (<code class="language-plaintext highlighter-rouge">F25_Plan_de_performance</code>) en faveur de <code class="language-plaintext highlighter-rouge">F2_Expression</code>. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">R13 is realised in (realises)</p>
<p class="en block">D: F21; R: F26</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R13_est_réalisé_dans (réalise)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F21_Œuvre_d’enregistrement</code> ; Portée : <code class="language-plaintext highlighter-rouge">F26_Enregistrement</code>.</p>
</td>
<td>
<p class="en block">Use superproperty R3 is realised in (realises)</p>
<p class="en block">~~~~~</p>
<p>Utiliser la super-propriété <code class="language-plaintext highlighter-rouge">R3_est_réalisé_dans (réalise)</code>.</p>
</td>
<td>
<p class="en block">Deprecated unneeded subproperty. Its domain, F21 Recording Work, is deprecated in favour of F1 Work, its range, F26 Recording, in favour of F2 Expression</p>
<p class="en block">~~~~~</p>
<p>Sous-propriété superflue dépréciée dont le domaine (<code class="language-plaintext highlighter-rouge">F21_Œuvre_d’enregistrement</code>) est déprécié en faveur de <code class="language-plaintext highlighter-rouge">F1_Œuvre</code> de même que la portée (<code class="language-plaintext highlighter-rouge">F26_Enregistrement</code>) en faveur de <code class="language-plaintext highlighter-rouge">F2_Expression</code> </p>
</td>
</tr>
<tr>
<td>
<p class="en block">R15 has fragment (is fragment of)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R15_a_pour_fragment (est_fragment_de)</code></p>
</td>
<td>
<p class="en block">R15 has fragment (is fragment of)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R15_a_pour_fragment (est_un_fragment_de)</code></p>
</td>
<td>
<p class="en block">Retained, revised range to E90 Symbolic Object, scope note revised</p>
<p class="en block">~~~~~</p>
<p>Retenue avec une portée révisée à <code class="language-plaintext highlighter-rouge">E90_Objet_symbolique</code> ainsi qu’une note d’application révisée</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R16 initiated (was initiated by)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R16_a_initié (a_été_initié_par)</code></p>
</td>
<td>
<p class="en block">R16 created (was created by)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R16_a_créé (a_été_créé_par)</code></p>
</td>
<td>
<p class="en block">Retained, renamed, scope note revised for consistency</p>
<p class="en block">~~~~~</p>
<p>Retenue et renommée avec une note d’application révisée.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R17 created (was created by)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R17_a_créé (a_été_créé_par)</code></p>
</td>
<td>
<p class="en block">R17 created (was created by)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R17_a_créé (a_été_créé_par)</code></p>
</td>
<td>
<p class="en block">Retained, quantification revised, scope note revised for consistency</p>
<p class="en block">~~~~~</p>
<p>Retenue avec une note d’application et une quantification révisées.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R18 created (was created by)</p>
<p class="en block">D: F28; R: F4</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R18_a_créé (a_été_créé_par)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F28_Création_d’expression</code> ; Portée : <code class="language-plaintext highlighter-rouge">F4_Manifestation_unique</code>.</p>
</td>
<td>
<p class="en block">Use a path: F28 Expression Creation. R17 created (was created by): F2 Expression.</p>
<p class="en block"> R4i is embodied in: F3 Manifestation. R7i is exemplified by: F5 Item</p>
<p class="en block">~~~~~</p>
<p>Utiliser le chemin sémantique suivant : <code class="language-plaintext highlighter-rouge">F28_Création_d’expression</code>. <code class="language-plaintext highlighter-rouge">R17_a_créé</code> : <code class="language-plaintext highlighter-rouge">F2_Expression</code>. <code class="language-plaintext highlighter-rouge">R4i_est_incarné_dans</code> : <code class="language-plaintext highlighter-rouge">F3_Manifestation</code>. <code class="language-plaintext highlighter-rouge">R7i_est_exemplifié_par</code> : <code class="language-plaintext highlighter-rouge">F5_Item </code></p>
</td>
<td>
<p class="en block">Deprecated, its range, F4 Manifestation Singleton, is deprecated in favour of F3 Manifestation</p>
<p class="en block">~~~~~</p>
<p>Dépréciée, la portée (<code class="language-plaintext highlighter-rouge">F4_Manifestation_unique</code>) a été elle aussi dépréciée en faveur de <code class="language-plaintext highlighter-rouge">F3_Manifestation</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R19 created a realisation of (was realised through)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R19_a_créé_une_réalisation_de (a_été_réalisé_à_travers)</code></p>
</td>
<td>
<p class="en block">R19 created a realisation of (was realised through)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R19_a_créé_une_réalisation_de (a_été_réalisé_par)</code></p>
</td>
<td>
<p class="en block">Retained, quantification revised</p>
<p class="en block">~~~~~</p>
<p>Retenue avec une quantification révisée.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R20 recorded (was recorded through) </p>
<p class="en block">D: F29; R: E2</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R20_a_enregistré (a_été_enregistré_par)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F29_Évènement_d’enregistrement</code> ; Portée : <code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code> .</p>
</td>
<td>
<p class="en block">Use superproperty R17 created (was created by)</p>
<p class="en block">D: F28; R: F2</p>
<p class="en block">with P129 is about (is subject of) D: E89; R: E1</p>
<p class="en block">to link the expression to the temporal entity recorded</p>
<p class="en block">~~~~~</p>
<p>Utiliser la super-propriété <code class="language-plaintext highlighter-rouge">R17_a_créé (a_été_créé_par)</code>.</p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F28_Création_d’expression</code> ; Portée : <code class="language-plaintext highlighter-rouge">F2_Expression</code> en liant l’expression à une entité temporelle grâce à <code class="language-plaintext highlighter-rouge">P129_a_pour_sujet (est_le_sujet_de)</code>.</p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">E89_Objet_propositionnel</code> ; Portée : <code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code>.</p>
</td>
<td>
<p class="en block">Deprecated, its domain, F29 Recording Event, is deprecated in favour of F28 Expression Creation</p>
<p class="en block">~~~~~</p>
<p>Dépréciée, la portée (<code class="language-plaintext highlighter-rouge">F29_Évènement_d’enregistrement</code>) a été elle aussi dépréciée en faveur de <code class="language-plaintext highlighter-rouge">F28_Création_d’expression</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R21 created (was created through) </p>
<p class="en block">D: F29; R: F26</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R21_a_créé (a_été_créé_à_travers)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F29_Évènement_d’enregistrement</code> ; Portée : <code class="language-plaintext highlighter-rouge">F26_Enregistrement</code>.</p>
</td>
<td>
<p class="en block">Use superproperty R17 created (was created by)</p>
<p class="en block">D: F28; R: F2</p>
<p class="en block">~~~~~</p>
<p>Utiliser la super-propriété <code class="language-plaintext highlighter-rouge">R17_a_créé (a_été_créé_par)</code>.</p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F28_Création_d’expression</code> ; Portée : <code class="language-plaintext highlighter-rouge">F2_Expression</code>.</p>
</td>
<td>
<p class="en block">Deprecated unneeded subproperty. Its domain, F29 Recording Event, is deprecated in favour of F28 Expression Creation, its range, F26 Recording, in favour of F2 Expression</p>
<p class="en block">~~~~~</p>
<p>Sous-propriété superflue dépréciée dont le domaine (<code class="language-plaintext highlighter-rouge">F29_Évènement_d’enregistrement</code>) est déprécié en faveur de <code class="language-plaintext highlighter-rouge">F28_Création_d’expression</code> de même que la portée (<code class="language-plaintext highlighter-rouge">F26_Enregistrement</code>) en faveur de <code class="language-plaintext highlighter-rouge">F2_Expression</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R22 created a realisation of (was realised through)</p>
<p class="en block">D: F29; R: F21 </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R22_a_créé_une_réalisation_de (a_été_réalisé_à_travers)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F29_Évènement_d’enregistrement</code> ; Portée : <code class="language-plaintext highlighter-rouge">F21_Œuvre_d’enregistrement</code>.</p>
</td>
<td>
<p class="en block">Use superproperty R19 created a realisation of (was realised through)</p>
<p class="en block">D: F28; R: F1</p>
<p class="en block">~~~~~</p>
<p>Utiliser la super-propriété <code class="language-plaintext highlighter-rouge">R19_a_créé_une_réalisation_de (a_été_réalisé_par)</code>.</p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F28_Création_d’expression</code> ; Portée : <code class="language-plaintext highlighter-rouge">F1_Œuvre</code>.</p>
</td>
<td>
<p class="en block">Deprecated unneeded subproperty. Its domain, F29 Recording Event, is deprecated in favour of F28 Expression Creation, its range, F21 Recording Work, is deprecated in favour of F1 Work</p>
<p class="en block">~~~~~</p>
<p>Sous-propriété superflue dépréciée dont le domaine (<code class="language-plaintext highlighter-rouge">F29_Évènement_d’enregistrement</code>) est déprécié en faveur de <code class="language-plaintext highlighter-rouge">F28_Création_d’expression</code> de même que la portée (<code class="language-plaintext highlighter-rouge">F21_Œuvre_d’enregistrement</code>) en faveur de <code class="language-plaintext highlighter-rouge">F2_Expression</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R23 created a realisation of (was realised through)</p>
<p class="en block">D: F30; R: F19</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R23_a_créé_une_réalisation_de (a_été_réalisé_à_travers)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F30_Évènement_de_publication</code> ; Portée : <code class="language-plaintext highlighter-rouge">F19_Œuvre_de_publication</code>.</p>
</td>
<td>
<p class="en block">Use superproperty R19 created a realisation of (was realised through)</p>
<p class="en block">D: F28; R: F1</p>
<p class="en block">~~~~~</p>
<p>Utiliser la super-propriété <code class="language-plaintext highlighter-rouge">R19_a_créé_une_réalisation_de (a_été_réalisé_par)</code>.</p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F28_Création_d’expression</code> ; Portée : <code class="language-plaintext highlighter-rouge">F1_Œuvre</code>.</p>
</td>
<td>
<p class="en block">Deprecated unneeded subproperty. Its domain, F30 Publication Event, was formerly a subclass of F28 Expression Creation. Its range, F19 Publication Work, is deprecated in favour of F1 Work</p>
<p class="en block">~~~~~</p>
<p>Sous-propriété superflue dépréciée dont le domaine (<code class="language-plaintext highlighter-rouge">F30_Évènement_de_publication</code>) était auparavant une sous-classe de <code class="language-plaintext highlighter-rouge">F28_Création_d’expression</code> ; la portée (<code class="language-plaintext highlighter-rouge">F19_Œuvre_de_publication</code>) a été dépréciée en faveur de <code class="language-plaintext highlighter-rouge">F1_Œuvre</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R24 created (was created through)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R24_a_créé (a_été_créé_à_travers)</code></p>
</td>
<td>
<p class="en block">R24 created (was created through)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R24_a_créé (a_été_créé_à_travers)</code></p>
</td>
<td>
<p class="en block">Retained, modified range to F3 Manifestation, modified superproperty to P94 has created, quantification revised</p>
<p class="en block">~~~~~</p>
<p>Retenue avec une portée et une super-propriété modifiées (maintenant <code class="language-plaintext highlighter-rouge">F3_Manifestation</code> et <code class="language-plaintext highlighter-rouge">P94_a_créé (a_été_créé_par)</code>) ainsi qu’une quantification révisée.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R25 performed (was performed in) </p>
<p class="en block">D: F31; R: F25</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R25_a_performé (a_été_performé_dans)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F31_Performance</code> ; Portée : <code class="language-plaintext highlighter-rouge">F25_Plan_de_performance</code>.</p>
</td>
<td>
<p class="en block">Use superproperty P33 used specific technique (was used by): E29 Design or Procedure</p>
<p class="en block">~~~~~</p>
<p>Utiliser la super-propriété <code class="language-plaintext highlighter-rouge">P33_a_mobilisé_comme_technique_spécifique (a_été_la_technique_spécifique_mise_en_œuvre_dans)</code> : <code class="language-plaintext highlighter-rouge">E29_Conceptualisation_ou_procédure</code> </p>
</td>
<td>
<p class="en block">Deprecated unneeded property. Its range, F25 Performance Plan, is deprecated in favour of E29 Design or Procedure, which may be multiply instantiated as F2 Expression</p>
<p class="en block">~~~~~</p>
<p>Sous-propriété superflue dépréciée dont la portée (<code class="language-plaintext highlighter-rouge">F25_Plan_de_performance</code>) est dépréciée en faveur de <code class="language-plaintext highlighter-rouge">E29_Conceptualisation_ou_procédure</code>, laquelle peut faire l’objet de multiples instanciations de <code class="language-plaintext highlighter-rouge">F2_Expression</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R26 produced things of type (was produced by) </p>
<p class="en block">D: F32; R: F3</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R26_a_produit_des_choses_du_type (a_été_produit_par)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F32_Évènement_de_production_de_support</code> ; Portée : <code class="language-plaintext highlighter-rouge">F3_Modèle_de_produit_de_la_manifestation</code>.</p>
</td>
<td>
<p class="en block">Use R27 materialized (was materialized by): F3 Manifestation and multiply instantiate as E99 Product Type</p>
<p class="en block">~~~~~</p>
<p>Utiliser <code class="language-plaintext highlighter-rouge">R27_a_matérialisé (a_été_matérialisé_par)</code> : <code class="language-plaintext highlighter-rouge">F3_Manifestation</code> et procéder à une instanciation multiple avec <code class="language-plaintext highlighter-rouge">E99_Modèle_de_produit</code>. </p>
</td>
<td>
<p class="en block">Merged with R27</p>
<p class="en block">~~~~~</p>
<p>Intégrée à <code class="language-plaintext highlighter-rouge">R27_a_matérialisé (a_été_matérialisé_par)</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R27 used as source material (was used by)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R27_a_utilisé_pour_matériel_source (a_été_utilisé_par)</code></p>
</td>
<td>
<p class="en block">R27 materialized (was materialized by)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R27_a_matérialisé (a_été_matérialisé_par)</code></p>
</td>
<td>
<p class="en block">Renamed, modified range to F3 Manifestation</p>
<p class="en block">~~~~~</p>
<p>Renommée avec une portée modifiée à <code class="language-plaintext highlighter-rouge">F3_Manifestation</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R28 produced (was produced by)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R28_a_produit (a_été_produit_par)</code></p>
</td>
<td>
<p class="en block">R28 produced (was produced by)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R28_a_produit (a_été_produit_par)</code></p>
</td>
<td>
<p class="en block">Retained, revised range to F5 Item, quantification revised</p>
<p class="en block">~~~~~</p>
<p>Retenue avec une quantification et une portée révisée à <code class="language-plaintext highlighter-rouge">F5_Item</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R29 reproduced (was reproduced by)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R29_a_reproduit (a_été_reproduit_par)</code></p>
</td>
<td>
<p class="en block">R29 reproduced object (was object reproduced by)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R29_objet_reproduit (était_l’objet_reproduit_par)</code></p>
</td>
<td>
<p class="en block">Retained, renamed, revised range to F5 Item</p>
<p class="en block">~~~~~</p>
<p>Retenue et renommée avec une portée révisée à <code class="language-plaintext highlighter-rouge">F5_Item</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R30 produced (was produced by)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R30_a_produit (a_été_produit_par)</code></p>
</td>
<td>
<p class="en block">R30 reproduced publication (was publication reproduced by)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R30_publication_reproduite (était_la_publication_reproduite_par)</code></p>
</td>
<td>
<p class="en block">Retained, renamed, revised range to F3 Manifestation, superproperty modified, quantification revised</p>
<p class="en block">~~~~~</p>
<p>Retenue et renommée avec une portée (maintenant <code class="language-plaintext highlighter-rouge">F3_Manifestation</code>) et une super-propriété modifiées ainsi qu’une quantification révisée.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R31 is reproduction of (has reproduction)</p>
<p class="en block">D: E84; R: E84</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R31_est_la_reproduction_de (a_pour_reproduction)</code></p>
<p>Domaine :  ; Portée : .</p>
</td>
<td>
<p class="en block">Use a path: F5 Item(1). R29i was object reproduced by: F33 Reproduction Event. R24 created (was created through): F3 Manifestation. R7i is exemplified by: F5 Item(2)</p>
<p class="en block">~~~~~</p>
<p>Utiliser le chemin sémantique suivant : <code class="language-plaintext highlighter-rouge">F5_Item</code> [1]. <code class="language-plaintext highlighter-rouge">R29i_était_l’objet_reproduit_par</code> : <code class="language-plaintext highlighter-rouge">F33_Évènement_de_reproduction</code>. <code class="language-plaintext highlighter-rouge">R24_a_créé (a_été_créé_à_travers)</code> : <code class="language-plaintext highlighter-rouge">F3_Manifestation</code>. <code class="language-plaintext highlighter-rouge">R7i_est_exemplifié_par</code> : <code class="language-plaintext highlighter-rouge">F5_Item</code> [2].</p>
</td>
<td>
<p class="en block">Deprecated in favour of the long path. An Item cannot be reproduced directly from another Item. It requires the creation of an intermediate Manifestation</p>
<p class="en block">~~~~~</p>
<p>Dépréciée en faveur du chemin sémantique complet ; une instance de <code class="language-plaintext highlighter-rouge">F5_Item</code> ne peut pas être reproduite directement d’une autre instance de <code class="language-plaintext highlighter-rouge">F5_Item</code>, il est en effet nécessaire de créer une instance de  <code class="language-plaintext highlighter-rouge">F3_Manifestation</code> intermédiaire. </p>
</td>
</tr>
<tr>
<td>
<p class="en block">R32 is warranted by (warrants)</p>
<p class="en block">D: F35; R: F52</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R32_est_cautionné_par (cautionne)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F35_Énoncé_d’utilisation_de_nomen</code> ; Portée : <code class="language-plaintext highlighter-rouge">F52_Activité_d’utilisation_du_nom</code>.</p>
</td>
<td>
<p class="en block">Use R35 is specified by (specifies)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R35_est_specifié_par (spécifie)</code></p>
</td>
<td>
<p class="en block">Deprecated, its domain F35 Nomen Use Statement, is merged into F12 Nomen. Its range, F52 Name Use Activity, moved to CRMsoc</p>
<p class="en block">~~~~~</p>
<p>Dépréciée, le domaine (<code class="language-plaintext highlighter-rouge">F35_Énoncé_d’utilisation_de_nomen</code> ) a été intégré à <code class="language-plaintext highlighter-rouge">F12_Nomen</code>  et la portée (<code class="language-plaintext highlighter-rouge">F52_Activité_d’utilisation_du_nom</code>) relève maintenant de CRM<sub>SOC</sub></p>
</td>
</tr>
<tr>
<td>
<p class="en block">R33 has content</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R33_a_pour_contenu</code></p>
</td>
<td>
<p class="en block">R33 has string</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R33_a_pour_chaîne_de_caractères</code></p>
</td>
<td>
<p class="en block">Retained, renamed, quantification revised, .1 property deprecated</p>
<p class="en block">~~~~~</p>
<p>Retenue et renommée avec une quantification révisée et une propriété « .1 » dépréciée</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R34 has validity period (is validity period of)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R34_a_pour_période_valide (est_période_de_validité_de)</code></p>
</td>
<td>
<p class="en block">To be generalized in a CRM family model</p>
<p class="en block">~~~~~</p>
<p>Doit être généralisé dans le cadre d’un modèle de l’ensemble du CIDOC CRM.</p>
</td>
<td>
<p class="en block">Deprecated, its domain, F34 KOS, is deprecated. Semantics require a more general construct which is out of LRM<sub>OO</sub> scope</p>
<p class="en block">~~~~~</p>
<p>Dépréciée ainsi que son domaine <code class="language-plaintext highlighter-rouge">F34_Système_d’organisation_des_connaissances</code> ; la sémantique requise ici nécessite un construit qui dépasse l’application du LRM<sub>OO</sub><sub></sub></p>
</td>
</tr>
<tr>
<td>
<p class="en block">R35 is specified by (specifies)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R35_est_spécifié_par (spécifie)</code></p>
</td>
<td>
<p class="en block">R35 is specified by (specifies)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R35_est_specifié_par (spécifie)</code></p>
</td>
<td>
<p class="en block">Retained, revised domain to F12 Nomen, revised range to F2 Expression, superclass of deprecated F34 KOS, modified superproperty, deprecated .1 property</p>
<p class="en block">~~~~~</p>
<p>Retenue avec un domaine et une portée révisés (maintenant <code class="language-plaintext highlighter-rouge">F12_Nomen</code> et <code class="language-plaintext highlighter-rouge">F2_Expression</code>, super-classe de <code class="language-plaintext highlighter-rouge">F34_Système_d’organisation_des_connaissances</code>, aussi dépréciée) ainsi qu’une super-propriété modifiée et une propriété « .1 » dépréciée.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R36 uses script conversion (is script conversion used in)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R36_utilise_la_conversion_de_script (est_la_conversion_de_script_utilisée_dans)</code></p>
</td>
<td>
<p class="en block">R36 uses script conversion (is script conversion used in)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R36_utilise_la_conversion_de_script (est_la_conversion_de_script_utilisée_dans)</code></p>
</td>
<td>
<p class="en block">Retained, revised domain to F12 Nomen, quantification revised, shortcut statement added, scope note revised</p>
<p class="en block">~~~~~</p>
<p>Retenue avec un domaine (maintenant <code class="language-plaintext highlighter-rouge">F12_Nomen</code>), une quantification et une note d’application révisés, ainsi qu’un raccourci ajouté.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R37 states as nomen (is stated as nomen in)</p>
<p class="en block">D: F35; R: F12</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R37_établi_comme_nomen (est_établi_comme_nomen)</code></p>
<p>Domaine :  ; Portée : .</p>
</td>
<td>
<p class="en block">No equivalent</p>
<p class="en block">~~~~~</p>
<p>Sans équivalent</p>
</td>
<td>
<p class="en block">Deprecated, domain F35 Nomen Use Statement merged with F12 Nomen</p>
<p class="en block">~~~~~</p>
<p>Dépréciée, le domaine <code class="language-plaintext highlighter-rouge">F35_Énoncé_d’utilisation_de_nomen</code> a été intégré à <code class="language-plaintext highlighter-rouge">F12_Nomen</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R38 refers to thema (is thema of)</p>
<p class="en block">D: F35; R: E1</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R38_réfère_au_thème (est_thème_de)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F35_Énoncé_d’utilisation_de_nomen</code> ; Portée : <code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code> .</p>
</td>
<td>
<p class="en block">No equivalent</p>
<p class="en block">~~~~~</p>
<p>Sans équivalent</p>
</td>
<td>
<p class="en block">Deprecated, domain F35 Nomen Use Statement merged with F12 Nomen</p>
<p class="en block">~~~~~</p>
<p>Dépréciée, le domaine <code class="language-plaintext highlighter-rouge">F35_Énoncé_d’utilisation_de_nomen</code> a été intégré à <code class="language-plaintext highlighter-rouge">F12_Nomen</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R39 is intended for (is target audience in)</p>
<p class="en block">D: F35; R: E74</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R39_est_destiné_à (est_public_destinataire_de)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F35_Énoncé_d’utilisation_de_nomen</code> ; Portée : <code class="language-plaintext highlighter-rouge">E74_Groupe</code> .</p>
</td>
<td>
<p class="en block">Use property P103 was intended for (was intention of): E55 Type. The type describes the type of users intended</p>
<p class="en block">~~~~~</p>
<p>Utiliser la propriété <code class="language-plaintext highlighter-rouge">P103_a_eu_pour_raison_d’être (a_été_la_raison_d’être_de)</code> : <code class="language-plaintext highlighter-rouge">E55_Type</code>.</p>
</td>
<td>
<p class="en block">Deprecated, domain F35 Nomen Use Statement merged with F12 Nomen.</p>
<p class="en block">The target audience of the nomen is not an instance of E74 Group, rather the intended users share a type which describes their shared characteristics</p>
<p class="en block">~~~~~</p>
<p>Dépréciée, le domaine <code class="language-plaintext highlighter-rouge">F35_Énoncé_d’utilisation_de_nomen</code> a été intégré à <code class="language-plaintext highlighter-rouge">F12_Nomen</code> ; l’audience cible de ce nomen n’est pas une instance de <code class="language-plaintext highlighter-rouge">E74_Groupe</code>  mais bien les utilisateurs qui partagent un type (<code class="language-plaintext highlighter-rouge">E55_Type</code>) décrivant leurs caractéristiques communes.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R40 has representative expression (is representative expression for)</p>
<p class="en block">D: F1; R: F22</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R40_a_pour_expression_représentative (est_expression_représentative_de)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F1_Œuvre</code> ; Portée : <code class="language-plaintext highlighter-rouge">F22_Expression_autonome</code>.</p>
</td>
<td>
<p class="en block">Use superproperty R3 is realised in (realises): F2 Expression</p>
<p class="en block">with R73 takes representative attribute from (bears representative attribute for): F2 Expression</p>
<p class="en block">where the same instance of F2 is the range of both properties and the same instance of F1 is the domain of both properties</p>
<p class="en block">~~~~~</p>
<p>Utiliser la super-propriété <code class="language-plaintext highlighter-rouge">R3_est_réalisé_dans (réalise)</code> : <code class="language-plaintext highlighter-rouge">F2_Expression</code> avec <code class="language-plaintext highlighter-rouge">R73_prend_l’attribut_représentatif_de (porte_l’attribut_représentatif_pour)</code> : <code class="language-plaintext highlighter-rouge">F2_Expression</code> où :</p>
<ul><li><p>la même instance de <code class="language-plaintext highlighter-rouge">F2_Expression</code> constitue la portée des deux propriétés ;</p>
</li>
<li><p>la même instance de <code class="language-plaintext highlighter-rouge">F1_Œuvre</code> est le domaine des deux propriétés.</p>
</li></ul>
</td>
<td>
<p class="en block">Deprecated unneeded property. Its range, F22 Self-contained Expression, is deprecated in favour of F2 Expression</p>
<p class="en block">~~~~~</p>
<p>Propriété superflue dépréciée dont la portée (<code class="language-plaintext highlighter-rouge">F22_Expression_autonome</code>) est dépréciée en faveur de <code class="language-plaintext highlighter-rouge">F2_Expression</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R41 has representative manifestation product type (is representative manifestation product type for)</p>
<p class="en block">D: F2; R: F3</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R41_a_pour_type_de_produit_de_manifestation_représentative (est_le_type_de_produit_de_manifestation_représentative_pour)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F2_Expression</code> ; Portée : <code class="language-plaintext highlighter-rouge">F3_Modèle_de_produit_de_la_manifestation</code>.</p>
</td>
<td>
<p class="en block">Use superproperty F2 Expression. R4i is embodied in: F3 Manifestation and multiply instantiate as E99 Product Type</p>
<p class="en block">with R73 takes representative attribute from (bears representative attribute for): F2 Expression</p>
<p class="en block">where the same instance of F2 is the domain of R4i and the range of R73</p>
<p class="en block">~~~~~</p>
<p>Utiliser la super-propriété <code class="language-plaintext highlighter-rouge">F2_Expression</code>. <code class="language-plaintext highlighter-rouge">R4i_est_incarné_dans</code> : <code class="language-plaintext highlighter-rouge">F3_Manifestation</code> et procéder à une instanciation multiple avec <code class="language-plaintext highlighter-rouge">E99_Modèle_de_produit</code> avec <code class="language-plaintext highlighter-rouge">R73_prend_l’attribut_représentatif_de (porte_l’attribut_représentatif_pour)</code> : <code class="language-plaintext highlighter-rouge">F2_Expression</code> où la même instance de <code class="language-plaintext highlighter-rouge">F2_Expression</code> constitue le domaine de <code class="language-plaintext highlighter-rouge">R4i_est_incarné_dans</code>  et la portée de <code class="language-plaintext highlighter-rouge">R73_prend_l’attribut_représentatif_de (porte_l’attribut_représentatif_pour)</code>.</p>
</td>
<td>
<p class="en block">Deprecated unneeded property</p>
<p class="en block">~~~~~</p>
<p>Propriété superflue dépréciée.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R42 is representative manifestation singleton for (has representative manifestation singleton)</p>
<p class="en block">D: F4; R: F2</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R42_est_manifestation_représentative_unique_pour (a_pour_manifestation_représentative_unique)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F4_Manifestation_unique</code> ; Portée : <code class="language-plaintext highlighter-rouge">F2_Expression</code>.</p>
</td>
<td>
<p class="en block">Use the path F5 Item. R7 exemplifies: F3 Manifestation (not multiply instantiated as E99 Product Type). R4 embodies (is embodied in): F2 Expression</p>
<p class="en block">with R73 takes representative attribute from (bears representative attribute for): F2 Expression</p>
<p class="en block">where the same instance of F2 is the range of both properties</p>
<p class="en block">~~~~~</p>
<p>Utiliser le chemin sémantique : <code class="language-plaintext highlighter-rouge">F5_Item</code>. <code class="language-plaintext highlighter-rouge">R7_exemplifie (est_exemplifié_par)</code> (sans procéder à une instanciation multiple avec <code class="language-plaintext highlighter-rouge">E99_Modèle_de_produit</code>). <code class="language-plaintext highlighter-rouge">R4_incarne (est_incarné_dans)</code> : <code class="language-plaintext highlighter-rouge">F2_Expression</code> avec <code class="language-plaintext highlighter-rouge">R73_prend_l’attribut_représentatif_de (porte_l’attribut_représentatif_pour)</code> : <code class="language-plaintext highlighter-rouge">F2_Expression</code> où la même instance de <code class="language-plaintext highlighter-rouge">F2_Expression</code> constitue la portée des deux propriétés. </p>
</td>
<td>
<p class="en block">Deprecated unneeded property. Its domain, F4 Manifestation Singleton, is deprecated in favour of F3 Manifestation. In this case F3 cannot also be an E99 Product Type and is exemplified by a single instance of F5 Item</p>
<p class="en block">~~~~~</p>
<p>Propriété superflue dépréciée dont le domaine (<code class="language-plaintext highlighter-rouge">F4_Manifestation_unique</code>) est déprécié en faveur de <code class="language-plaintext highlighter-rouge">F3_Manifestation</code> ; dans ce cas-ci une instance de <code class="language-plaintext highlighter-rouge">F3_Manifestation</code> ne peut pas aussi être une instance de <code class="language-plaintext highlighter-rouge">E99_Modèle_de_produit</code>, elle est plutôt exemplifiée par une instance unique de <code class="language-plaintext highlighter-rouge">F5_Item</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R43 carried out by (performed)</p>
<p class="en block">D: F41; R: F44</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R43_a_été_effectué_par (a_effectué)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F41_Assignation_de_manifestation_représentative</code> ; Portée : <code class="language-plaintext highlighter-rouge">F44_Agence_bibliographique</code>.</p>
</td>
<td>
<p class="en block">Use superproperty P14 carried out by (performed)</p>
<p class="en block">~~~~~</p>
<p>Utiliser la super-propriété <code class="language-plaintext highlighter-rouge">P14_a_été_effectué_par (a_effectué)</code> </p>
</td>
<td>
<p class="en block">Deprecated unneeded subproperty. Its domain, F41 Representative Manifestation Assignment, is deprecated in favour of E13 Attribute Assignment, its range, F44 Bibliographic Agency, in favour of F11 Corporate Body</p>
<p class="en block">~~~~~</p>
<p>Sous-propriété superflue dépréciée dont le domaine (<code class="language-plaintext highlighter-rouge">F41_Assignation_de_manifestation_représentative</code>) est déprécié en faveur de  <code class="language-plaintext highlighter-rouge">E13_Assignation_d’attribut</code> de même que la portée (<code class="language-plaintext highlighter-rouge">F44_Agence_bibliographique</code>) en faveur de <code class="language-plaintext highlighter-rouge">F11_Personne_morale</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R44 carried out by (performed)</p>
<p class="en block">D: F42; R: F44</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R44_a_été_effectué_par (a_effectué)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F42_Assignation_d’expression_représentative</code> ; Portée : <code class="language-plaintext highlighter-rouge">F44_Agence_bibliographique</code>.</p>
</td>
<td>
<p class="en block">Use superproperty P14 carried out by (performed)</p>
<p class="en block">~~~~~</p>
<p>Utiliser la super-propriété <code class="language-plaintext highlighter-rouge">P14_a_été_effectué_par (a_effectué)</code> </p>
</td>
<td>
<p class="en block">Deprecated unneeded subproperty. Its domain, F42 Representative Expression Assignment, is deprecated in favour of E13 Attribute Assignment, its range, F44 Bibliographic Agency, in favour of F11 Corporate Body</p>
<p class="en block">~~~~~</p>
<p>Sous-propriété superflue dépréciée dont le domaine (<code class="language-plaintext highlighter-rouge">F42_Assignation_d’expression_représentative</code>) est déprécié en faveur de  <code class="language-plaintext highlighter-rouge">E13_Assignation_d’attribut</code> de même que la portée (<code class="language-plaintext highlighter-rouge">F44_Agence_bibliographique</code>) en faveur de <code class="language-plaintext highlighter-rouge">F11_Personne_morale</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R45 assigned to (was assigned by)</p>
<p class="en block">D: F40; R: E1</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R45_a_été_assigné_à (a_été_assigné_par)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F40_Assignation_d’identifiant</code> ; Portée : <code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code> .</p>
</td>
<td>
<p class="en block">Use superproperty P140 assigned attribute to (was attributed by)</p>
<p class="en block">~~~~~</p>
<p>Utiliser la super-propriété <code class="language-plaintext highlighter-rouge">P140_a_assigné_l’attribut_à (a_reçu_l’attribut_par)</code></p>
</td>
<td>
<p class="en block">Deprecated unneeded subproperty. Its domain, F40 Identifier Assignment, is equal to E15 Identifier Assignment</p>
<p class="en block">~~~~~</p>
<p>Sous-propriété superflue dépréciée dont le domaine (<code class="language-plaintext highlighter-rouge">F40_Assignation_d’identifiant</code>) est équivalent <code class="language-plaintext highlighter-rouge">E15_Assignation_d’identifiant</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R46 assigned (was assigned by)</p>
<p class="en block">D: F40; R: E1</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R46_a_été_assigné (a_été_assigné_par)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F40_Assignation_d’identifiant</code>  ; Portée : <code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code> .</p>
</td>
<td>
<p class="en block">Use the equivalent property P37 assigned (was assigned by)</p>
<p class="en block">~~~~~</p>
<p>Utiliser la propriété équivalente <code class="language-plaintext highlighter-rouge">P37_a_assigné (a_été_assigné_par)</code></p>
</td>
<td>
<p class="en block">Deprecated properties exactly equivalent to CRM properties. Its domain, F40 Identifier Assignment, is equal to E15 Identifier Assignment; its range, F13 Identifier, to E42 Identifier</p>
<p class="en block">~~~~~</p>
<p>Propriété dépréciée ayant des équivalent exacts dans le CIDOC CRM : son domaine (<code class="language-plaintext highlighter-rouge">F40_Assignation_d’identifiant</code> ) est équivalent à <code class="language-plaintext highlighter-rouge">E15_Assignation_d’identifiant</code> et sa portée (<code class="language-plaintext highlighter-rouge">F13_Identifiant</code>) à <code class="language-plaintext highlighter-rouge">E42_Identifiant</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R48 assigned to (was assigned by)</p>
<p class="en block">D: F41; R: F2</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R48_a_été_assigné_à (a_été_assigné_par)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F41_Assignation_de_manifestation_représentative</code> ; Portée : <code class="language-plaintext highlighter-rouge">F2_Expression</code>.</p>
</td>
<td>
<p class="en block">Use superproperty P140 assigned attribute to (was attributed by)</p>
<p class="en block">~~~~~</p>
<p>Utiliser la super-propriété <code class="language-plaintext highlighter-rouge">P140_a_assigné_l’attribut_à (a_reçu_l’attribut_par)</code></p>
</td>
<td>
<p class="en block">Deprecated unneeded subproperty. Its domain, F41 Representative Manifestation Assignment, is deprecated in favour of E13 Attribute Assignment</p>
<p class="en block">~~~~~</p>
<p>Sous-propriété superflue dépréciée dont le domaine (<code class="language-plaintext highlighter-rouge">F41_Assignation_de_manifestation_représentative</code>) est déprécié en faveur de  <code class="language-plaintext highlighter-rouge">E13_Assignation_d’attribut</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R49 assigned (was assigned by)</p>
<p class="en block">D: F41; R: F3</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R49_a_été_assigné (a_été_assigné_par)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F41_Assignation_de_manifestation_représentative</code> ; Portée : <code class="language-plaintext highlighter-rouge">F3_Modèle_de_produit_de_la_manifestation</code>.</p>
</td>
<td>
<p class="en block">Use superproperty P141 assigned (was assigned by)</p>
<p class="en block">~~~~~</p>
<p>Utiliser la super-propriété <code class="language-plaintext highlighter-rouge">P141_a_assigné (a_été_assigné_par)</code> </p>
</td>
<td>
<p class="en block">Deprecated unneeded subproperty. Its domain, F41 Representative Manifestation Assignment, is deprecated in favour of E13 Attribute Assignment</p>
<p class="en block">~~~~~</p>
<p>Sous-propriété superflue dépréciée dont le domaine (<code class="language-plaintext highlighter-rouge">F41_Assignation_de_manifestation_représentative</code>) est déprécié en faveur de  <code class="language-plaintext highlighter-rouge">E13_Assignation_d’attribut</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R50 assigned to (was assigned by) </p>
<p class="en block">D: F42; R: F15</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R50_a_été_assigné_à (a_été_assigné_par)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F42_Assignation_d’expression_représentative</code> ; Portée : <code class="language-plaintext highlighter-rouge">F15_Œuvre_complexe</code>.</p>
</td>
<td>
<p class="en block">Use superproperty P140 assigned attribute to (was attributed by)</p>
<p class="en block">~~~~~</p>
<p>Utiliser la super-propriété <code class="language-plaintext highlighter-rouge">P140_a_assigné_l’attribut_à (a_reçu_l’attribut_par)</code></p>
</td>
<td>
<p class="en block">Deprecated unneeded subproperty. Its domain, F42 Representative Expression Assignment, is deprecated in favour of E13 Attribute Assignment</p>
<p class="en block">~~~~~</p>
<p>Sous-propriété superflue dépréciée dont le domaine (<code class="language-plaintext highlighter-rouge">F42_Assignation_d’expression_représentative</code>) est déprécié en faveur de  <code class="language-plaintext highlighter-rouge">E13_Assignation_d’attribut</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R51 assigned (was assigned by) </p>
<p class="en block">D: F42; R: F2</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R51_a_assigné (a_été_assigné_par)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F42_Assignation_d’expression_représentative</code> ; Portée : <code class="language-plaintext highlighter-rouge">F2_Expression</code>.</p>
</td>
<td>
<p class="en block">Use superproperty P141 assigned (was assigned by)</p>
<p class="en block">~~~~~</p>
<p>Utiliser la super-propriété <code class="language-plaintext highlighter-rouge">P141_a_assigné (a_été_assigné_par)</code> </p>
</td>
<td>
<p class="en block">Deprecated unneeded subproperty. Its domain, F42 Representative Expression Assignment, is deprecated in favour of E13 Attribute Assignment</p>
<p class="en block">~~~~~</p>
<p>Sous-propriété superflue dépréciée dont le domaine (<code class="language-plaintext highlighter-rouge">F42_Assignation_d’expression_représentative</code>) est déprécié en faveur de  <code class="language-plaintext highlighter-rouge">E13_Assignation_d’attribut</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R52 used rule (was the rule used in) </p>
<p class="en block">D: F40; R: F43</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R52_a_utilisé_comme_règle (a_été_règle_utilisée_dans)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F40_Assignation_d’identifiant</code> ; Portée : <code class="language-plaintext highlighter-rouge">F43_Règle_d’identifiant</code>.</p>
</td>
<td>
<p class="en block">Use superproperty P33 used specific technique: (was used by): E29 Design or Procedure</p>
<p class="en block">~~~~~</p>
<p>Utiliser la super-propriété <code class="language-plaintext highlighter-rouge">P33_a_mobilisé_comme_technique_spécifique (a_été_la_technique_spécifique_mise_en_œuvre_dans)</code> : <code class="language-plaintext highlighter-rouge">E29_Conceptualisation_ou_procédure</code></p>
</td>
<td>
<p class="en block">Deprecated unneeded subproperty. Its domain, F40 Identifier Assignment, is equal to E15 Identifier Assignment; its range, F43 Identifier Rule, is a subclass of E29 Design or Procedure</p>
<p class="en block">~~~~~</p>
<p>Sous-propriété superflue dépréciée dont le domaine (<code class="language-plaintext highlighter-rouge">F40_Assignation_d’identifiant</code> ) est équivalent <code class="language-plaintext highlighter-rouge">E15_Assignation_d’identifiant</code>, et dont la portée (<code class="language-plaintext highlighter-rouge">F43_Règle_d’identifiant</code>) est une sous-classe de <code class="language-plaintext highlighter-rouge">E29_Conceptualisation_ou_procédure</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R53 assigned (was assigned by) </p>
<p class="en block">D: F41; R: F4</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R53_a_assigné (a_été_assigné_dans)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F41_Assignation_de_manifestation_représentative</code> ; Portée : <code class="language-plaintext highlighter-rouge">F4_Manifestation_unique</code>.</p>
</td>
<td>
<p class="en block">Use superproperty P141 assigned (was assigned by)</p>
<p class="en block">~~~~~</p>
<p>Utiliser la super-propriété <code class="language-plaintext highlighter-rouge">P141_a_assigné (a_été_assigné_par)</code> </p>
</td>
<td>
<p class="en block">Deprecated unneeded subproperty. Its domain, F41 Representative Manifestation Assignment, is deprecated in favour of E13 Attribute Assignment</p>
<p class="en block">~~~~~</p>
<p>Sous-propriété superflue dépréciée dont le domaine (<code class="language-plaintext highlighter-rouge">F41_Assignation_de_manifestation_représentative</code>) est déprécié en faveur de  <code class="language-plaintext highlighter-rouge">E13_Assignation_d’attribut</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R54 has nomen language (is language of nomen in) </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R54_a_pour_langue_du_nomen (est_langue_du_nomen_dans)</code></p>
</td>
<td>
<p class="en block">R54 has language (is language of)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R54_a_pour_langue (est_la_langue_de)</code></p>
</td>
<td>
<p class="en block">Retained, renamed, domain modified to F12 Nomen, superproperty modified</p>
<p class="en block">~~~~~</p>
<p>Retenue et renommée avec un domaine modifié (maintenant  <code class="language-plaintext highlighter-rouge">F12_Nomen</code>) ainsi qu’une super-propriété modifiée.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R55 has nomen form (is nomen form in)</p>
<p class="en block">D: F35; R: E55</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R55_a_pour_forme_du_nomen (est_forme_du_nomen_dans)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F35_Énoncé_d’utilisation_de_nomen</code> ; Portée : <code class="language-plaintext highlighter-rouge">E55_Type</code>.</p>
</td>
<td>
<p class="en block">Use P2 has type (is type of)</p>
<p class="en block">~~~~~</p>
<p>Utiliser <code class="language-plaintext highlighter-rouge">P2_a_pour_type (est_le_type_de)</code> </p>
</td>
<td>
<p class="en block">Deprecated, prefer a general property to assign a type to a nomen</p>
<p class="en block">~~~~~</p>
<p>Dépréciée, favoriser l’usage d’une propriété générale pour assigner un type de  <code class="language-plaintext highlighter-rouge">F12_Nomen</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R56 has related use (is related use for)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R56_a_pour_usage_afférent (est_usage_afférent_de)</code></p>
</td>
<td>
<p>R56 has related form (is related form of)</p>
<p>~~~~~ </p>
<p><code class="language-plaintext highlighter-rouge">R56_a_pour_forme_connexe (est_la_forme_connexe_de)</code></p>
</td>
<td>
<p class="en block">Retained, renamed, domain and range modified to F12 Nomen, replaced superproperty with a shortcut statement</p>
<p class="en block">~~~~~</p>
<p>Retenue et renommée avec un domaine et une portée modifiés (tous deux  <code class="language-plaintext highlighter-rouge">F12_Nomen</code>) ainsi qu’avec une super-propriété remplacée par un raccourci.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R57 is based on (is basis for)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R57_est_fondé_sur (est_la_base_de)</code></p>
</td>
<td>
<p class="en block">See CRMsoc</p>
<p class="en block">~~~~~</p>
<p>Voir CRM<sub>SOC</sub></p>
</td>
<td>
<p class="en block">Moved to other family model</p>
<p class="en block">~~~~~</p>
<p>Relève maintenant d’un autre modèle.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R58 has fictional member (is fictional member of)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R58_a_pour_membre_fictif (est_le_membre_fictif_de)</code></p>
</td>
<td>
<p class="en block">See CRMsoc</p>
<p class="en block">~~~~~</p>
<p>Voir CRM<sub>SOC</sub></p>
</td>
<td>
<p class="en block">Moved to other family model</p>
<p class="en block">~~~~~</p>
<p>Relève maintenant d’un autre modèle.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R59 had typical subject (was typical subject of) </p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R59_avait_pour_sujet_de_la_pratique (était_le_sujet_de_la_pratique_de)</code></p>
</td>
<td>
<p class="en block">See CRMsoc</p>
<p class="en block">~~~~~</p>
<p>Voir CRM<sub>SOC</sub></p>
</td>
<td>
<p class="en block">Moved to other family model</p>
<p class="en block">~~~~~</p>
<p>Relève maintenant d’un autre modèle.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R60 used to use language (was language used by)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R60_utilisait_pour_langage (était_le_langage_utilisé_par)</code></p>
</td>
<td>
<p class="en block">See CRMsoc</p>
<p class="en block">~~~~~</p>
<p>Voir CRM<sub>SOC</sub></p>
</td>
<td>
<p class="en block">Moved to other family model</p>
<p class="en block">~~~~~</p>
<p>Relève maintenant d’un autre modèle.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R61 occurred in kind of context (was kind of context for)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R61_s’est_produit_dans_le_type_de_contexte (était_le_type_de_contexte_de)</code></p>
</td>
<td>
<p class="en block">See CRMsoc</p>
<p class="en block">~~~~~</p>
<p>Voir CRM<sub>SOC</sub></p>
</td>
<td>
<p class="en block">Moved to other family model</p>
<p class="en block">~~~~~</p>
<p>Relève maintenant d’un autre modèle.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R62 was used for membership in (was context for)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R62_a_été_utilisé_pour_l’adhésion_à (était_le_contexte_de)</code></p>
</td>
<td>
<p class="en block">See CRMsoc</p>
<p class="en block">~~~~~</p>
<p>Voir CRM<sub>SOC</sub></p>
</td>
<td>
<p class="en block">Moved to other family model</p>
<p class="en block">~~~~~</p>
<p>Relève maintenant d’un autre modèle.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R63 named (was named by)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R63_a_nommé (a_été_nommé_par)</code></p>
</td>
<td>
<p class="en block">See CRMsoc</p>
<p class="en block">~~~~~</p>
<p>Voir CRM<sub>SOC</sub></p>
</td>
<td>
<p class="en block">Moved to other family model</p>
<p class="en block">~~~~~</p>
<p>Relève maintenant d’un autre modèle.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R64 used name (was name used by)</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R64_a_utilisé_pour_nom (était_le_nom_utilisé_par)</code></p>
</td>
<td>
<p class="en block">See CRMsoc</p>
<p class="en block">~~~~~</p>
<p>Voir CRM<sub>SOC</sub></p>
</td>
<td>
<p class="en block">Moved to other family model</p>
<p class="en block">~~~~~</p>
<p>Relève maintenant d’un autre modèle.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R65 recorded aspects of (had aspects recorded through)</p>
<p class="en block">D: F29; R: E18</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R65_a_enregistré_des_aspects_de (a_eu_des_aspects_enregistré_par)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F29_Évènement_d’enregistrement</code> ; Portée : <code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code>.</p>
</td>
<td>
<p class="en block">Use property R17 created (was created by)</p>
<p class="en block">D: F28; R: F2</p>
<p class="en block">with P62 depicts (is depicted by) D: E24; R: E1</p>
<p class="en block">to link the items of the expression to the physical thing captured in the recording</p>
<p class="en block">~~~~~</p>
<p>Utiliser la propriété <code class="language-plaintext highlighter-rouge">R17_a_créé (a_été_créé_par)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F28_Création_d’expression</code> ; Portée : <code class="language-plaintext highlighter-rouge">F2_Expression</code> </p>
<p>avec <code class="language-plaintext highlighter-rouge">P62_illustre (est_illustré_par)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">E24_Chose_matérielle_élaborée_par_l’humain</code> ; Portée : <code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code> pour lier les items de l’expression à la chose matérielle enregistrée. </p>
</td>
<td>
<p class="en block">Deprecated, its domain, F29 Recording Event, is deprecated in favour of F28 Expression Creation</p>
<p class="en block">~~~~~</p>
<p>Dépréciée, le domaine (<code class="language-plaintext highlighter-rouge">F29_Évènement_d’enregistrement</code>) a été déprécié en faveur de <code class="language-plaintext highlighter-rouge">F28_Création_d’expression</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">R66 included performed version of (had a performed version through)</p>
<p class="en block">D: F31: R:E89</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R66_a_inclus_une_version_performée_de (a_eu_une_version_performée_à_travers)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F31_Performance</code> ; Portée : <code class="language-plaintext highlighter-rouge">E89_Objet_propositionnel</code>.</p>
</td>
<td>
<p class="en block">Use R80 performed (is performed in)</p>
<p class="en block">D: F31; R: F1</p>
<p class="en block">~~~~~</p>
<p>Utiliser <code class="language-plaintext highlighter-rouge">R80_a_interprété (est_interprété_dans)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F31_Performance</code> ; Portée : <code class="language-plaintext highlighter-rouge">F1_Œuvre</code> </p>
</td>
<td>
<p class="en block">Deprecated in favour of a more specific property with range F1 Work instead of E89 Propositional Object</p>
<p class="en block">~~~~~</p>
<p>Dépréciée en faveur d’une propriété plus spécifique utilisée avec la portée <code class="language-plaintext highlighter-rouge">F1_Œuvre</code> plutôt que <code class="language-plaintext highlighter-rouge">E89_Objet_propositionnel</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">CLP2 should have type (should be type of)</p>
<p class="en block">D: F3; R: E55</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">CLP2_devrait_avoir_pour_type (devrait_être_type_de)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F3_Modèle_de_produit_de_la_manifestation</code> ; Portée : <code class="language-plaintext highlighter-rouge">E55_Type</code>.</p>
</td>
<td>
<p class="en block">Use R69 has physical form (is physical form of)</p>
<p class="en block">D: F3; R: E55</p>
<p class="en block">~~~~~</p>
<p>Utiliser <code class="language-plaintext highlighter-rouge">R69_a_pour_forme_physique (est_forme_physique_de)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F3_Manifestation</code> ; Portée : <code class="language-plaintext highlighter-rouge">E55_Type</code> </p>
</td>
<td>
<p class="en block">Class property redefined as a standard property since domain, F3 Manifestation, is no longer a subclass of E55 Type, superproperty added</p>
<p class="en block">~~~~~</p>
<p>La propriété-classe a été redéfinie comme une propriété standard puisque son domaine (<code class="language-plaintext highlighter-rouge">F3_Manifestation</code>) n’est plus une sous-classe de <code class="language-plaintext highlighter-rouge">E55_Type</code> ; une super-propriété a été ajoutée.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">CLP43 should have dimension (should be dimension of)</p>
<p class="en block">D: F3; R: E54</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">CLP43_devrait_avoir_pour_dimension (devrait_être_dimension_de)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F3_Modèle_de_produit_de_la_manifestation</code> ; Portée : <code class="language-plaintext highlighter-rouge">E54_Dimension</code>.</p>
</td>
<td>
<p class="en block">Use R70 has dimension (is dimension of)</p>
<p class="en block">D: F3; R: E54</p>
<p class="en block">~~~~~</p>
<p>Utiliser <code class="language-plaintext highlighter-rouge">R70_a_pour_dimension (est_la_dimension_de)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F3_Manifestation</code> ; Portée : <code class="language-plaintext highlighter-rouge">E54_Dimension</code> </p>
</td>
<td>
<p class="en block">Class property redefined as a standard property since domain F3 Manifestation is no longer a subclass of E55 Type, superproperty added</p>
<p class="en block">~~~~~</p>
<p>La propriété-classe a été redéfinie comme une propriété standard puisque son domaine (<code class="language-plaintext highlighter-rouge">F3_Manifestation</code>) n’est plus une sous-classe de <code class="language-plaintext highlighter-rouge">E55_Type</code> ; une super-propriété a été ajoutée.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">CLP45 should consist of (should be incorporated in)</p>
<p class="en block">D: F3; R: E57</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">CLP45_devrait_consister_en (devrait_être_inclus_dans)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F3_Modèle_de_produit_de_la_manifestation</code> ; Portée : <code class="language-plaintext highlighter-rouge">E57_Matériau</code>.</p>
</td>
<td>
<p class="en block">Use R69 has physical form (is physical form of)</p>
<p class="en block">D: F3; R: E55</p>
<p class="en block">~~~~~</p>
<p>Utiliser <code class="language-plaintext highlighter-rouge">R69_a_pour_forme_physique (est_forme_physique_de)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F3_Manifestation</code> ; Portée : <code class="language-plaintext highlighter-rouge">E55_Type</code> </p>
</td>
<td>
<p class="en block">Merged into R69. Its range, E57 Material, is a subclass of E55 Type</p>
<p class="en block">~~~~~</p>
<p>Intégrée à <code class="language-plaintext highlighter-rouge">R69_a_pour_forme_physique (est_forme_physique_de)</code>, son domaine (<code class="language-plaintext highlighter-rouge">E57_Matériau</code>) est une sous-classe de <code class="language-plaintext highlighter-rouge">E55_Type</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">CLP46 should be composed of (may form part of)</p>
<p class="en block">D: F3; R: F3</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">CLP46_devrait_être_composée_de (peut_faire_partie_de)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F3_Modèle_de_produit_de_la_manifestation</code> ; Portée : <code class="language-plaintext highlighter-rouge">F3_Modèle_de_produit_de_la_manifestation</code>.</p>
</td>
<td>
<p class="en block">Use R71 has part (is part of)</p>
<p class="en block">D: F3; R: F3</p>
<p class="en block">~~~~~</p>
<p>Utiliser <code class="language-plaintext highlighter-rouge">R71_a_pour_élément (fait_partie_de)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F3_Manifestation</code> ; Portée : <code class="language-plaintext highlighter-rouge">F3_Manifestation</code>  </p>
</td>
<td>
<p class="en block">Class property redefined as a standard property since domain F3 Manifestation is no longer a subclass of E55 Type, superproperty added</p>
<p class="en block">~~~~~</p>
<p>La propriété-classe a été redéfinie comme une propriété standard puisque son domaine (<code class="language-plaintext highlighter-rouge">F3_Manifestation</code>) n’est plus une sous-classe de <code class="language-plaintext highlighter-rouge">E55_Type</code> ; une super-propriété a été ajoutée.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">CLP57 should have number of parts</p>
<p class="en block">D: F3; R: E60</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">CLP57_devrait_avoir_pour_nombre_d’éléments</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F3_Modèle_de_produit_de_la_manifestation</code> ; Portée : <code class="language-plaintext highlighter-rouge">E60_Nombre</code>.</p>
</td>
<td>
<p class="en block">Use R70 has dimension (is dimension of)</p>
<p class="en block">D: F3; R: E54</p>
<p class="en block">~~~~~</p>
<p>Utiliser <code class="language-plaintext highlighter-rouge">R70_a_pour_dimension (est_la_dimension_de)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F3_Manifestation</code> ; Portée : <code class="language-plaintext highlighter-rouge">E54_Dimension</code> </p>
</td>
<td>
<p class="en block">Merged into R70. Number of parts is a type of dimension</p>
<p class="en block">~~~~~</p>
<p>Intégrée à <code class="language-plaintext highlighter-rouge">R70_a_pour_dimension (est_la_dimension_de)</code> car le nombre d’éléments est un type de dimension.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">CLP104 subject to (applies to)</p>
<p class="en block">D: F3; R: E30</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">CLP104_sujet_à (s’applique_à)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F3_Modèle_de_produit_de_la_manifestation</code> ; Portée : <code class="language-plaintext highlighter-rouge">E30_Droit</code>.</p>
</td>
<td>
<p class="en block">Use P104 is subject to (applies to)</p>
<p class="en block">D: E72; R: E30</p>
<p class="en block">~~~~~</p>
<p>Utiliser <code class="language-plaintext highlighter-rouge">P104_est_soumis_à (s’applique_à)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">E72_Objet_juridique</code> ; Portée : <code class="language-plaintext highlighter-rouge">E30_Droit</code> </p>
</td>
<td>
<p class="en block">Deprecated unneeded class property in favour of equivalent property</p>
<p class="en block">~~~~~</p>
<p>Propriété-classe superflue dépréciée en faveur d’une propriété équivalente.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">CLP105 right held by (right on)</p>
<p class="en block">D: F3; R: E39</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">CLP105_droit_détenu_par (droit_sur)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F3_Modèle_de_produit_de_la_manifestation</code> ; Portée : <code class="language-plaintext highlighter-rouge">E39_Actant</code>.</p>
</td>
<td>
<p class="en block">Use P105 right held by (has right on)</p>
<p class="en block">D: E72; R: E39</p>
<p class="en block">~~~~~</p>
<p>Utiliser <code class="language-plaintext highlighter-rouge">P105_droit_détenu_par (détient_le_droit_sur)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">E72_Objet_juridique</code> ; Portée : <code class="language-plaintext highlighter-rouge">E39_Actant</code> </p>
</td>
<td>
<p class="en block">Deprecated unneeded class property in favour of equivalent property</p>
<p class="en block">~~~~~</p>
<p>Propriété-classe superflue dépréciée en faveur d’une propriété équivalente.</p>
</td>
</tr>
<tr>
<td>
<p class="en block">CLR6 should carry (should be carried by) </p>
<p class="en block">D: F3; R: F24</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">CLR6_devrait_porter (devrait_être_porté_par)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F3_Modèle_de_produit_de_la_manifestation</code> ; Portée : <code class="language-plaintext highlighter-rouge">F24_Expression_de_publication</code>.</p>
</td>
<td>
<p class="en block">Use R4 embodies (is embodied in)</p>
<p class="en block">D: F3; R: F2</p>
<p class="en block">~~~~~</p>
<p>Utiliser <code class="language-plaintext highlighter-rouge">R4_incarne (est_incarné_dans)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F3_Manifestation</code> ; Portée : <code class="language-plaintext highlighter-rouge">F2_Expression</code> </p>
</td>
<td>
<p class="en block">Deprecated unneeded property since domain F3 Manifestation is no longer a subclass of E55 Type, and its range, F24 Publication Expression, was a subclass of F2</p>
<p class="en block">~~~~~</p>
<p>Propriété superflue dépréciée car son domaine (<code class="language-plaintext highlighter-rouge">F3_Manifestation</code>) n’est plus une sous-classe de <code class="language-plaintext highlighter-rouge">E55_Type</code> et sa portée (<code class="language-plaintext highlighter-rouge">F24_Expression_de_publication</code>) était une sous-classe de <code class="language-plaintext highlighter-rouge">F2_Expression</code>.</p>
</td>
</tr>
<tr>
<td>
<p><strong>New</strong></p>
<p>~~~~~<strong></strong></p>
<p>Nouvelle</p>
</td>
<td>
<p class="en block">R67 has part (forms part of)</p>
<p class="en block">D: F1; R: F1</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R67_a_pour_élément (fait_partie_de)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F1_Œuvre</code> ; Portée : <code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
</td>
<td>
<p class="en block">Added as an equivalent for the work relationship LRM-R18 has part (is part of)</p>
<p class="en block">~~~~~</p>
<p>Ajoutée comme équivalent à la relation d’œuvre <code class="language-plaintext highlighter-rouge">LRM-R18_a_pour_partie (fait_partie_de)</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block"><strong>New</strong></p>
<p class="en block">~~~~~</p>
<p>Nouvelle</p>
</td>
<td>
<p class="en block">R68 is inspired by (is inspiration for)</p>
<p class="en block">D: F1; R: F1</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R68_est_inspiré_de (est_source_d’inspiration_pour)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F1_Œuvre</code> ; Portée : <code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
</td>
<td>
<p class="en block">Added as an equivalent for the work relationship LRM-R21 is inspiration for (is inspired by) </p>
<p class="en block">Superproperty of R2</p>
<p class="en block">~~~~~</p>
<p>Ajoutée comme équivalent à la relation d’œuvre <code class="language-plaintext highlighter-rouge">LRM-R21_est_source_d’inspiration_pour (inspirée_de)</code> ; super-propriété de <code class="language-plaintext highlighter-rouge">R2_est_dérivé_de (a_pour_dérivé)</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block"><strong>New</strong></p>
<p class="en block">~~~~~</p>
<p>Nouvelle</p>
</td>
<td>
<p class="en block">R73 takes representative attribute from (bears representative attribute for) </p>
<p class="en block">D: F1; R: F2</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R73_prend_l’attribut_représentatif_de (porte_l’attribut_représentatif_pour)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F1_Œuvre</code> ; Portée : <code class="language-plaintext highlighter-rouge">F2_Expression</code></p>
</td>
<td>
<p class="en block">Added as part of the simplification of the modelling of representative expressions</p>
<p class="en block">~~~~~</p>
<p>Ajoutée dans le cadre de la simplification de la modélisation des expressions représentatives.</p>
</td>
</tr>
<tr>
<td>
<p class="en block"><strong>New</strong></p>
<p class="en block">~~~~~</p>
<p>Nouvelle</p>
</td>
<td>
<p class="en block">R74 uses expression of (has expression used in)</p>
<p class="en block">D: F1; R: F1</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R74_utilise_l’expression_de (a_l’expression_utilisée_dans)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F1_Œuvre</code> ; Portée : <code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
</td>
<td>
<p class="en block">Added to model works using expressions of pre-existing works</p>
<p class="en block">~~~~~</p>
<p>Ajoutée afin de modéliser les œuvres mobilisant des expressions d’œuvres pré-existantes</p>
</td>
</tr>
<tr>
<td>
<p class="en block"><strong>New</strong></p>
<p class="en block">~~~~~</p>
<p>Nouvelle</p>
</td>
<td>
<p class="en block">R75 incorporates (is incorporated in)</p>
<p class="en block">D: F2; R: F2</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R75_incorpore (est_inclus_dans)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F2_Expression</code> ; Portée : <code class="language-plaintext highlighter-rouge">F2_Expression</code></p>
</td>
<td>
<p class="en block">Added to model expressions using expressions of pre-existing works</p>
<p class="en block">~~~~~</p>
<p>Ajoutée afin de modéliser les expressions mobilisant des expressions d’œuvres pré-existantes.</p>
</td>
</tr>
<tr>
<td>
<p class="en block"><strong>New</strong></p>
<p class="en block">~~~~~</p>
<p>Nouvelle</p>
</td>
<td>
<p class="en block">R76 is derivative of (has derivative)</p>
<p class="en block">D: F2; R: F2</p>
<p class="en block">R76.1 has type</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R76_est_dérivé_de (a_pour_dérivé)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F2_Expression</code> ; Portée : <code class="language-plaintext highlighter-rouge">F2_Expression</code></p>
<p><code class="language-plaintext highlighter-rouge">R76.1_a_pour_type</code></p>
</td>
<td>
<p class="en block">Added as an equivalent for the expression relationship LRM-R24 is derivation of (has derivation)</p>
<p class="en block">~~~~~</p>
<p>Ajoutée comme équivalent à la relation d’expression <code class="language-plaintext highlighter-rouge">LRM-R24_est_dérivée_de (a_pour_dérivation)</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block"><strong>New</strong></p>
<p class="en block">~~~~~</p>
<p>Nouvelle</p>
</td>
<td>
<p class="en block">R77 accompanies or complements (is accompanied or complemented by)</p>
<p class="en block">D: F1; R: F1</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R77_accompagne_ou_complémente (est_accompagné_ou_complémenté_de)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F1_Œuvre</code> ; Portée : <code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
</td>
<td>
<p class="en block">Added as an equivalent for the work relationship LRM-R20 accompanies / complements (is accompanied /complemented by)</p>
<p class="en block">~~~~~</p>
<p>Ajoutée comme équivalent à la relation d’œuvre <code class="language-plaintext highlighter-rouge">LRM-R20_accompagne/complète (est_accompagnée_par/est_complétée_par)</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block"><strong>New</strong></p>
<p class="en block">~~~~~</p>
<p>Nouvelle</p>
</td>
<td>
<p class="en block">R78 has alternate</p>
<p class="en block">D: F3; R: F3</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R78_a_pour_présentation_alternative</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F3_Manifestation</code> ; Portée : <code class="language-plaintext highlighter-rouge">F3_Manifestation</code> </p>
</td>
<td>
<p class="en block">Added as an equivalent for the manifestation relationship LRM-R29 has alternate</p>
<p class="en block">~~~~~</p>
<p>Ajoutée comme équivalent à la relation de manifestation <code class="language-plaintext highlighter-rouge">LRM-R29_a_pour_présentation_alternative</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block"><strong>New</strong></p>
<p class="en block">~~~~~</p>
<p>Nouvelle</p>
</td>
<td>
<p class="en block">R79 has representative expression attribute (is representative expression attribute of)</p>
<p class="en block">D: F1; R: E55</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R79_a_l’attribut_d’expression_représentatif (est_l’attribut_d’expression_représentatif_de)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F1_Œuvre</code> ; Portée : <code class="language-plaintext highlighter-rouge">E55_Type</code> </p>
</td>
<td>
<p class="en block">Added as an equivalent for the work attribute LRM-E2-A2 Representative expression attribute</p>
<p class="en block">~~~~~</p>
<p>Ajoutée comme équivalent à la relation d’œuvre <code class="language-plaintext highlighter-rouge">LRM-E2-A2_attribut_d’expression_représentative</code>.</p>
</td>
</tr>
<tr>
<td>
<p class="en block"><strong>New</strong></p>
<p class="en block">~~~~~</p>
<p>Nouvelle</p>
</td>
<td>
<p class="en block">R80 performed (is performed in)</p>
<p class="en block">D: F31; R: F1</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R80_a_interprété (est_interprété_dans)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F31_Performance</code> ; Portée : <code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
</td>
<td>
<p class="en block">Added to explicitly link a performance to the work performed</p>
<p class="en block">~~~~~</p>
<p>Ajoutée pour lier explicitement une performance à une œuvre performée.</p>
</td>
</tr>
<tr>
<td>
<p class="en block"><strong>New</strong></p>
<p class="en block">~~~~~</p>
<p>Nouvelle</p>
</td>
<td>
<p class="en block">R81 recorded (is recorded in)</p>
<p class="en block">D: F28; R:F31</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">R81_enregistré (est_enregistré_dans)</code></p>
<p>Domaine : <code class="language-plaintext highlighter-rouge">F28_Création_d’expression</code> ; Portée : <code class="language-plaintext highlighter-rouge">F31_Performance</code> </p>
</td>
<td>
<p class="en block">Added to model the use of the recording of a performance as a means of expressions creation</p>
<p class="en block">~~~~~</p>
<p>Ajoutée pour modéliser l’usage d’un enregistrement d’une performance comme mode de création d’expressions.</p>
</td>
</tr>
</tbody>
</table>

