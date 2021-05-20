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




