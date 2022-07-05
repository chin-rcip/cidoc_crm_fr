---
layout: page
title: CIDOC CRM Version 7.1
permalink: /v7.1/information/introduction2
sidebar: v71
group: info
---


<div class="lang-buttons">
  <button id="fr" class="activate">FR</button>
  <button id="en-fr">EN-FR</button>
</div>


<table class="text">
<tbody>
<tr class="odd">
<td style="display:none">Texte</td>
<td class="en"><p>This document is the formal definition of the <strong>CIDOC Conceptual Reference Model (“CIDOC CRM”)</strong>, a formal ontology intended to facilitate the integration, mediation and interchange of heterogeneous cultural heritage information. The CIDOC CRM is the culmination of more than a decade of standards development work by the International Committee for Documentation (CIDOC) of the International Council of Museums (ICOM). Work on the CIDOC CRM itself began in 1996 under the auspices of the ICOM-CIDOC Documentation Standards Working Group. Since 2000, development of the CIDOC CRM has been officially delegated by ICOM-CIDOC to the CIDOC CRM Special Interest Group, which collaborates with the ISO working group ISO/TC46/SC4/WG9 to bring the CIDOC CRM to the form and status of an International Standard.</p>
</td>
<td><p>Ce document constitue la définition du <strong>Modèle conceptuel de référence du Comité international pour la documentation du Conseil international des musées (« CIDOC CRM »)</strong>, une ontologie formelle qui a pour objectif de faciliter l’intégration, la médiation et l’échange d’informations patrimoniales hétérogènes. Le CIDOC CRM est le résultat du développement de standards par le Comité pour la documentation (CIDOC) du Conseil international des musées (ICOM), un travail qui a commencé en 1996 sous les auspices du Groupe de travail pour les standards en documentation. En 2000, ICOM-CIDOC a officiellement délégué les tâches de développement du CIDOC CRM au Groupe de travail spécial pour CIDOC CRM (CRM SIG), lequel travaille en collaboration avec le Groupe de travail ISO/TC46/SC4/WG9 afin de veiller à ce que le CIDOC CRM respecte les normes internationales en matière de standards.</p>
</td>
</tr>

</tbody>
</table>
<table>
<tbody>
<tr class="odd">
<td><strong><em>Note traducteur</em></strong></td>
<td>L’abréviation la plus utilisée dans le monde francophone pour le modèle demeure son acronyme anglophone (CIDOC CRM) et c’est celle qui est utilisée dans ce document. Les titres francophones des groupes de travail sont tirés des appellations trouvées sur le site francophone de CIDOC.
</td>
</tr>
<tr class="even">
<td><strong><em>Références</em></strong></td>
<td><em>Comité International pour la Documentation de l’ICOM. 2021. « CIDOC ». ICOM CIDOC. 24 février 2021. <a href="http://cidoc.mini.icom.museum/fr/">http://cidoc.mini.icom.museum/fr/</a>.</em></td>
</tr>
</tbody>
</table>

## Objectifs de CIDOC CRM

## Portée de CIDOC CRM {#portee-de-cidoc-crm}

## Exemples

### Display of content that was originally already in table format.

<table>
<thead>
<tr class="header">
<th class="en">Symbol</th>
<th class="en">Name</th>
<th class="en">reads</th>
<th class="en">Truth value</th>
<th>Symbol(Fr)</th>
<th>Name(Fr)</th>
<th>reads(Fr)</th>
<th>Truth value(Fr)</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td class="en">Operators</td>
<td class="en"></td>
<td class="en"></td>
<td class="en"></td>
<td>Operators(Fr)</td>
<td></td>
<td></td>
<td></td>
</tr>
<tr class="even">
<td class="en">∧</td>
<td class="en">conjunction</td>
<td class="en">and</td>
<td class="en"><p>(φ ∧ ψ) is true</p>
<p>if and only if both <em>φ</em> and <em>ψ</em> are true</p></td>
<td>∧</td>
<td>conjunction(Fr)</td>
<td>and(Fr)</td>
<td><p>(φ ∧ ψ) is true(Fr)</p>
<p>if and only if both <em>φ</em> and <em>ψ</em> are true (Fr)</p></td>
</tr>
<tr class="odd">
<td class="en">∨</td>
<td class="en">disjunction</td>
<td class="en">or</td>
<td class="en"><p>(φ ∨ ψ) is true</p>
<p>if and only if at least one of either φ or ψ is true</p></td>
<td>∨</td>
<td>disjunction(Fr)</td>
<td>or(Fr)</td>
<td><p>(φ ∨ ψ) is true (Fr)</p>
<p>if and only if at least one of either φ or ψ is true (Fr)</p></td>
</tr>
</tbody>
</table>

### Display of hierarchy

| ---------------------------------------------- | ---------------------------- | ---------------------------------------- | --------------- | ----- | ----------------------- |
|E1       |<span class="en">CRM Entity</span> `E1_Entité_CRM`|                                          |                 |       |                         |
|E2       | \-                           |<span class="en">Temporal Entity</span> `E2_Entité_temporelle`|                 |       |                         |
|E3 | \-                           | \-                                       |<span class="en">Condition State</span>|       |                         |
|E4 | \-                           | \-                                       |<span class="en">Period         </span>|       |                         |
|E5 | \-                           | \-                                       | \-              |<span class="en">Event</span>|                         |
|E7 | \-                           | \-                                       | \-              | \-    |<span class="en">Activity</span> `E7_Activité`|

## Basic Concepts

<h3 id="des-relations-evenementielles"><span class="en heading">Relations with Events - </span>Des relations évènementielles</h3>

<table class="text">
<colgroup>
<col style="width: 50%">
</colgroup>
<tbody>
<tr>
<td class="en"><p>Figure 1 illustrates the minimal properties in the CIDOC CRM for documenting “what has happened”, the central pattern of the Model. Let us first consider the class E1 CRM Entity, the formal top class of the model. It primarily serves a technical purpose to aggregate the ontologically meaningful concepts of the model. It declares however two important properties of general validity and distinct features of the Model: P1 is identified by, with range E41 Appellation, makes the fundamental ontological distinction between the identity of a particular and an identifier (see section “Reality, Knowledge Bases and CIDOC CRM” above), and in practice allows for describing a discourse about resolving historical ambiguities of names and reconciliation of multiple identifiers. The property P2 has type, with range E55 Type, constitutes a practical interface for refining classes by terminologies, being often volatile, as detailed in the section “About Types” below.</p>
<iframe frameborder="0" style="width:100%;height:400px;" src="https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Copy%20of%20CRM_7.1-IntroductionDiagrammes#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1ZnD-tK4rB0LQDB6-O6mfxd7XJGrXwYQj%26export%3Ddownload"></iframe>
<p><em>Figure 1: High Level Properties and Classes of CIDOC CRM</em></p>
<p>
All classes in figure 1 are direct or indirect subclasses of E1 CRM Entity, but for better readability, only the “subclass of” -link from E2 Temporal Entity is shown. The latter comprises phenomena that continuously occur over some time-span (E52 Time-Span) in the natural time dimension, but some of them may not be confined to specific area, such as a marriage status.</p>
</td>
<td><p>La figure 1 illustre les propriétés minimales pour documenter « ce qui s'est produit », à savoir le patron fondamental du CIDOC CRM. La classe E1_Entité_CRM est la classe à la tête de la hiérarchie du modèle; elle a pour fonction de fédérer les concepts ontologiquement signifiants du modèle. De plus, cette classe déclare deux propriétés essentielles à la validité générale et aux caractéristiques distinctes du CIDOC CRM:</p> 
<ul>
<li>
<p>P1_est_identifié_par avec pour portée E41_Appellation établit une distinction ontologique fondamentale entre l'identité d'un particulier et son identifiant (voir la section De la réalité, des bases de connaissance, et du CIDOC CRM), ce qui permet de décrire un discours solutionnant des ambiguïtés historiques de noms ainsi que de réconcilier de multiples identifiants;</p>
</li>
<li>
<p>P2_a_pour_type avec pour portée E55_Type constitue une interface pratique pour rafiner des classes par le biais de terminologies, lesquelles sont souvent fluctuantes (voir la section Des types).</p>
</li>
</ul>
<iframe frameborder="1" style="width:100%;height:400px;" src="https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&page-id=jxFYM2qpOWzRNXlSE76c&title=Copy%20of%20CRM_7.1-IntroductionDiagrammes#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1ZnD-tK4rB0LQDB6-O6mfxd7XJGrXwYQj%26export%3Ddownload"></iframe>
<p><em>Figure 1 : Propriétés et classes de haut-niveau du CIDOC CRM</em></p>
<p>
Toutes les classes de la figure 1 sont des sous-classes directes ou indirectes de E1_Entité_CRM, mais à des fins de lisibilité seuls les liens de sous-classe depuis E2_Entité_temporelle sont illustrés.</p>
<p>
La classe E2_Entité_temporelle comprend des phénomènes qui se produisent de manière continue sur une étendue de temps déterminée (E52_Intervalle_temporel) dans la dimension naturelle du temps bien que certains de ces phénomènes puissent de pas être confinés à une aire spécifique (p. ex. le statut d'être une personne mariée). 
</p>
</td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr class="odd">
<th><em>Note traducteur</em></th>
<td><span class="empty-cell">Invisible placeholder content for empty cells to control the width of the heading colums.</span></td>
</tr>
<tr class="even">
<th><em>Références</em></th>
<td></td>
</tr>
</tbody>
</table>