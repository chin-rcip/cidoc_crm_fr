---
layout: page
title: LRMoo Version 1.0
titleEn: LRMoo Version 1.0
permalink: /lrmoo/v1.0/introduction
sidebar: lrmoo_v10
tab: versions
date: 2026-02-09
---

**Date de création** : 2026-02-09

**Dernière mise à jour** : 2026-02-09

<div class="lang-buttons">
 <button id="fr" class="activate">FR</button>
 <button id="en-fr">EN-FR</button>
</div>

<h2><span class="en heading">1. Introduction - </span>1. Introduction</h2>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>This document contains a comprehensive description of the object-oriented definition of the IFLA Library Reference Model (IFLA LRM), a model in the form of a formal ontology interpreting IFLA LRM. IFLA LRM was approved as an IFLA standard in August 2017. IFLA LRM consolidates and succeeds the three models in the IFLA FR family of conceptual models (FRBR, FRAD, FRSAD).</p>
<p>Now superseded, FRBR<sub>OO</sub> version 2.4, approved as an IFLA standard in 2016, reflected the three IFLA entity-relationship models in the FR family in a formulation designed as a compatible extension to the museum community’s model, the CIDOC Conceptual Reference Model (CIDOC CRM). The role of the LRM<sub>OO</sub> model is to provide a similar equivalent for IFLA LRM.</p>
<p>LRM<sub>OO</sub> is developed from FRBR<sub>OO</sub> version 2.4, but taking into account decisions made in IFLA LRM, continuing the mutual influence and cycles of development between the models (Riva & Žumer 2018). In keeping with its aim to provide an object-oriented rendering of IFLA LRM, LRM<sub>OO</sub> is a core model at a high-level of generality, reducing specialised subclasses and properties in comparison to FRBR<sub>OO.</sub> Examples have also been thoroughly revised throughout (Riva, Žumer & Aalberg 2022).</p>
<p>A major release of CIDOC CRM in 2022 (version 7.1.2) was the basis for the 2023 update of its corresponding ISO standard (ISO 21127:2023 Information and documentation – A reference ontology for the interchange of cultural heritage information[1]). Minor corrections noted during the ISO process resulted in the official CIDOC CRM release (version 7.1.3) in February 2024. LRM<sub>OO</sub> is also taking the opportunity to integrate this latest CRM release, including modifications to terminology and style that have been recently adopted in the CRM family.</p>
<p>The document comprises the following sections:</p>
<ul><li><p>Section 1, Introduction, describes the rationale, history and methodology of the development of this model.</p>
</li>
<li><p>Section 2, Scope, clarifies both what the model includes and what is not included.</p>
</li>
<li><p>Section 3, Status, provides information relating to the formal adoption process of the document.</p>
</li>
<li><p>Section 4, Description of the Model, explains the model in context from a functional perspective with the help of a comprehensive graphical representation of all constructs, and describes the format conventions for the formal specifications found in sections 6 and 7.</p>
</li>
<li><p>Section 5, Class and Property Hierarchies, puts LRM<sub>OO</sub> in context with CIDOC CRM. Since the object-oriented model reuses, wherever appropriate, large parts of ISO 21127, the CIDOC Conceptual Reference Model, this section also provides a comprehensive list of all constructs used from CIDOC CRM version 7.1.3. Some of these constructs appear only in the mapping in section 8 and not in sections 6 and 7, because they are generic in nature.</p>
</li>
<li><p>Sections 6 and 7 list the complete class and property definitions that make up the model. Whereas the description in section 4 serves an overall understanding, these sections are the reference for the individual declarations.</p>
</li>
<li><p>Section 8 provides the mapping of the IFLA LRM entity-relationship model to the object-oriented model LRM<sub>OO</sub>. This section defines the transition from one form to the other, and serves as information for further understanding of the intended meaning of the object-oriented definition. It is also a proof that the object-oriented form is an alternative view of the IFLA LRM model, and a proof of completeness of the object-oriented form with respect to the original.</p>
</li>
<li><p>Section 9 provides a temporary home for classes and properties declared in FRBR<sub>OO</sub> that are intended to transition to the CRM family model CRMsoc, the model for Social Phenomena, which is under development.</p>
</li>
<li><p>Section 10 lists all classes and properties declared in the superseded model FRBR<sub>OO</sub> version 2.4 and aligns them with the LRM<sub>OO</sub> model, and provides migration instructions.</p>
</li>
<li><p>Section 11 provides a brief bibliography.</p>
</li></ul>
<hr><p>[1] ISO 21127:2014 was based on CIDOC CRM version 5.0.4 (December 2011).</p>
</td>
<td>
<p>Ce document contient une description exhaustive de la définition orientée-objet du <em>Modèle conceptuel pour l’information bibliographique</em> de la Fédération internationale des associations et institutions de bibliothèques (IFLA LRM). Celle-ci constitue une modélisation ontologique formelle interprétant le IFLA LRM, lequel a été approuvé en tant que standard IFLA en août 2017 et consolide trois modèles conceptuels de l’ensemble « FR » d’IFLA auxquels il succède : <em>Fonctionnalités requises des notices bibliographiques </em>(FRBR), <em>Fonctionnalités requises des données d’autorité</em> (FRAD), et <em>Fonctionnalités requises des données d’autorité matière</em> (FRSAD). </p>
<p>La version 2.4 du FRBR<sub>OO </sub>– approuvée à titre de standard IFLA en 2016 et maintenant remplacée – reflétait ces trois modèles entité-relation de l’ensemble « FR » et était construit comme une extension compatible du <em>Modèle conceptuel de référence du Comité international pour la documentation du Conseil international des musées</em> (CIDOC CRM). Le rôle du modèle <em>Modèle conceptuel pour l’information bibliographique, orientation objet</em> (LRM<sub>OO</sub>) est de fournir un équivalent pour l’IFLA LRM. </p>
<p>LRM<sub>OO</sub> découle de la version 2.4 de FRBR<sub>OO</sub>, mais prend en considération les décisions du IFLA LRM et l’influence des modèles et de leurs cycles de développement respectifs les uns sur les autres (Riva & Žumer 2018). En adéquation avec son objectif d’offrir une interprétation orientée-objet du IFLA LRM, LRM<sub>OO</sub> est un modèle dont le degré de généralité est élevé, qui réduit les sous-classes et propriétés spécialisées de FRBR<sub>OO</sub>, et dont les exemples ont été adaptés (Riva, Žumer & Aalberg 2022). </p>
<p>La publication de la version 7.1.2 du CIDOC CRM en 2022 a permis de dériver le standard correspondant de l’Organisation internationale de normalisation (ISO) <em>ISO 21127:2023 Information et documentation. Une ontologie de référence pour l’échange d’information culturelle et patrimoniale.</em><sup>1</sup> Des corrections mineures apportées tout au long du processus de révision ISO ont mené à une version miroir (7.1.3) du CIDOC CRM en février 2024. LRM<sub>OO</sub> intègre ces récents ajustements, y compris les modifications terminologiques et de style qui ont récemment été adoptées dans l’ensemble des modèles du CIDOC.</p>
<p>Ce document comprend les sections suivantes :</p>
<ul><li><p><em>Section 1 – Introduction</em> décrit le raisonnement, l’historique et la méthodologie du développement de ce modèle ;</p>
</li>
<li><p><a href="https://cidoc-crm-fr.info/lrmoo/v1.0/champ-application"><span class="underline"><em>Section 2 – Champ d’application</em></span></a> clarifie ce que le modèle inclut et n’inclut pas ;</p>
</li>
<li><p><a href="https://cidoc-crm-fr.info/lrmoo/v1.0/statut"><span class="underline"><em>Section 3 – Statut</em></span></a> fournit de l’information sur le processus formel d’adoption du document ;</p>
</li>
<li><p><a href="https://cidoc-crm-fr.info/lrmoo/v1.0/description-du-modele"><span class="underline"><em>Section 4 – Description du modèle</em></span></a> explique le modèle dans une perspective fonctionnelle à l’aide d’une représentation graphique des construits, en plus de décrire les conventions de formatage des spécifications qui se trouvent dans les sections 6 et 7 ;</p>
</li>
<li><p><a href="https://cidoc-crm-fr.info/lrmoo/v1.0/hierarchie-de-classes-et-de-proprietes"><span class="underline"><em>Section 5 – Hiérarchies des classes et des propriétés</em></span></a><em> </em>place le LRM<sub>OO</sub> dans le contexte du CIDOC CRM (ISO 21127 / CIDOC CRM 7.1.3) dont il reprend beaucoup de construits, et fait la liste de ceux qui sont réutilisés et qui se retrouvent soit en section 6 et 7, soit dans les tableaux de mise en correspondance de la section 8 lorsqu’ils sont de nature générique ; </p>
</li>
<li><p><a href="https://cidoc-crm-fr.info/lrmoo/v1.0/classes/declaration-des-classes-du-lrmoo"><span class="underline"><em>Sections 6</em></span></a> <em>et</em> <a href="https://cidoc-crm-fr.info/lrmoo/v1.0/proprietes/declaration-des-proprietes-du-lrmoo"><span class="underline"><em>7</em></span></a> fournissent les définitions des classes et propriétés qui constituent le modèle (n.b. alors que les descriptions de la section 4 « Description du modèle » permettent une compréhension générale, ces sections agissent à titre de référence pour les déclarations individuelles) ;</p>
</li>
<li><p><a href="https://cidoc-crm-fr.info/lrmoo/v1.0/mise-en-correspondance-iflalrm-lrmoo"><span class="underline"><em>Section 8</em></span></a> met en correspondance le modèle entité-relation IFLA LRM avec le modèle orienté-objet LRM<sub>OO</sub>, définit les transitions de l’un à l’autre, et permet de mieux comprendre les complexités de la définition orientée-objet (ce qui soutient l’idée que le LRM<sub>OO</sub> est en fait une perspective alternative du IFLA LRM dont la forme orientée-objet a la même complétude que l’original) ;</p>
</li>
<li><p><a href="https://cidoc-crm-fr.info/lrmoo/v1.0/classes-et-proprietes-frbroo-transferees-au-crmsoc"><span class="underline"><em>Section 9</em></span></a> est un emplacement temporaire où sont documentées les classes et propriétés déclarées dans le FRBR<sub>OO</sub> qui seront éventuellement absorbées par le <em>Modèle conceptuel de référence pour les phénomènes sociaux</em> (CRM<sub>SOC</sub>) actuellement en cours de développement ;</p>
</li>
<li><p><a href="https://cidoc-crm-fr.info/lrmoo/v1.0/migration-du-frbroo-vers-le-lrmoo"><span class="underline"><em>Section 10</em></span></a><em> </em>énumère les classes et propriétés déclarées dans la version 2.4 du FRBR<sub>OO</sub>, les aligne avec le LRM<sub>OO</sub>, et fournit des instructions de migration ;</p>
</li>
<li><p><a href="https://cidoc-crm-fr.info/lrmoo/v1.0/bibliographie-du-lrmoo"><span class="underline"><em>Section 11</em></span></a> fournit une brève bibliographie. </p>
</li></ul>
<hr><p><sup>1</sup> <em>ISO 21127:2014</em> était fondé sur la version 5.0.4 du CIDOC CRM datant de décembre 2011.</p>
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
<p>Les versions francisées des modèles FRBR, FRAD et FRSAD sont tirées du site de la Bibliothèque nationale de France. </p>
</td>
</tr>
<tr>
<th style="width:15%"><p><em>Références</em></p>
</th>
<td colspan="1">
<p>Bibliothèque nationale de France. « Modèles FRBR, FRAD et FRSAD ». BnF. Consulté le 24 septembre 2024.<a href="https://www.bnf.fr/fr/modeles-frbr-frad-et-frsad"><span class="underline"> </span></a><a href="https://www.bnf.fr/fr/modeles-frbr-frad-et-frsad"><span class="underline">https://www.bnf.fr/fr/modeles-frbr-frad-et-frsad</span></a>.</p>
<p>Riva, Pat, Patrick Le Bœuf, et Maja Žumer. <em>Un modèle conceptuel pour l’information bibliographique</em>. Traduit par Aude Le Moullec-Rieu, Françoise Leresche, Frédéric Puyrenier, et Mélanie Roche. Committee Publications. La Haye, NL: Fédération internationale des associations et institutions de bibliothèques (IFLA), 2021.<a href="https://repository.ifla.org/server/api/core/bitstreams/b395a0a0-c9b8-49c6-8919-9befda0c40ed/content"><span class="underline"> </span></a><a href="https://repository.ifla.org/server/api/core/bitstreams/b395a0a0-c9b8-49c6-8919-9befda0c40ed/content"><span class="underline">https://repository.ifla.org/server/api/core/bitstreams/b395a0a0-c9b8-49c6-8919-9befda0c40ed/content</span></a>.</p>
</td>
</tr>
</tbody>
</table>

