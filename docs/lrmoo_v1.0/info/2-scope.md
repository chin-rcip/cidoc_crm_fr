---
layout: page
title: 2. Champ d’application
titleEn: 2. Scope - 2. Champ d’application
permalink: /lrmoo/v1.0/champ-application
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
<p>LRM<sub>OO</sub> takes its functional scope from the scope of the IFLA Library Reference Model. It aims to be a high-level conceptual reference model for bibliographic information managed by libraries of all kinds. As with IFLA LRM, it covers bibliographic data, which is broadly understood to include metadata traditionally considered strictly bibliographic as well as metadata viewed as name or subject authority data. Basic holdings information, to the extent that it appears in IFLA LRM, is included via constructs existing in CIDOC CRM. However, administrative metadata used to manage the internal functions of libraries and bibliographic agencies is excluded from the scope of LRM<sub>OO</sub>, as it is also excluded by both IFLA LRM and CIDOC CRM.</p>
<p>The LRM<sub>OO</sub> model includes all classes and properties required, in addition to classes and properties already declared in CIDOC CRM, to express the concepts covered by IFLA LRM. Classes that are exact equivalences of CIDOC CRM classes are not declared within LRM<sub>OO</sub>, even when those classes are required as direct equivalences to IFLA LRM classes. LRM<sub>OO</sub> is strictly an extension of CIDOC CRM and cannot be implemented without using key classes and properties from CIDOC CRM.</p>
<p>LRM<sub>OO</sub> only expands on IFLA LRM in a few limited areas. The situation where a work incorporates a pre-existing work so that all of its expressions must include an expression of the first work is modelled with two specific properties, <em>R75 incorporates (is incorporated in)</em> between the works and <em>R74 uses expression of (has expression used in)</em> between the expressions. Additionally, LRM<sub>OO</sub> provides for grouping works that share a common concept, such as being set in the same fictional universe, an idea that has often been discussed under the term “superwork”, through the property <em>R10 is member of (has member)</em> which links a work to the CIDOC CRM class E28 Conceptual Object. And finally, LRM<sub>OO</sub> includes modelling of performances with the class F31 Performance and the property <em>R80 performed (is performed in)</em> to link the performance event to the work performed. Recording performances is one type of expression creation and this is expressed with the property <em>R81 recorded (is recorded in)</em>.</p>
<p>LRM<sub>OO</sub> is designed as an extension to the CIDOC CRM model which opens a route to semantic interoperability and exchange of data with other communities in the wider heritage sector. The family of models that use CIDOC CRM as a base is diverse and growing. The development methodology ensures each new family model is compatible, which allows for multiple extensions to be adopted together, based on the needs of the implementation.</p>
<p>LRM<sub>OO</sub> does not include refinements for particular types of resources. All these aspects can be fully represented with more general supertypes in LRM<sub>OO</sub> or CIDOC CRM. Any extensions to IFLA LRM for resource types could be the object of further extensions to LRM<sub>OO</sub>.</p>
<p>LRM<sub>OO</sub> is a conceptual model and as such is primarily intended for a technical audience engaged in designing and implementing data structures that include bibliographic information, in particular when this is with the intention of enabling integration with data from other heritage communities. The adoption of object-oriented techniques makes the model suited for working with linked data and semantic web technologies. This document presumes basic familiarity with conceptual modelling and particularly with object-oriented formulations, the conventions adopted in CIDOC CRM and with IFLA LRM.</p>
</td>
<td>
<p>Le <em>Modèle conceptuel pour l’information bibliographique, orientation objet </em>(LRM<sub>OO</sub>) tire son champ d’application de celui du <em>Modèle conceptuel pour l’information bibliographique</em> de la Fédération internationale des associations et institutions de bibliothèques (IFLA LRM). Il a pour objectif d’offrir un modèle conceptuel de référence à haut niveau pour l’information bibliographique que gèrent les bibliothèques de tous genres. Comme IFLA LRM, il couvre les données bibliographiques, ce qui inclut les métadonnées bibliographiques ainsi que les données d’autorité relatives aux noms et aux sujets. Les informations de base sur les collections, dans la mesure où elles sont traitées dans IFLA LRM, sont aussi couvertes par le LRM<sub>OO</sub> par le biais de construits existant dans le <em>Modèle conceptuel de référence du Comité international pour la documentation du Conseil international des musées</em> (CIDOC CRM). Par contre, les métadonnées administratives destinées à la gestion des fonctions internes des bibliothèques et agences bibliographiques sont exclues du champ d’application du LRM<sub>OO</sub> du fait qu’elles sont aussi exclues du IFLA LRM et du CIDOC CRM. </p>
<p>Le modèle LRM<sub>OO</sub> inclut toutes les classes et propriétés nécessaires à l’expression des concepts du IFLA LRM, en plus de celles qui sont déjà déclarées dans le CIDOC CRM. Les classes qui sont parfaitement équivalentes à leur déclaration dans le CIDOC CRM ne sont pas déclarées dans LRM<sub>OO</sub>, et ce même si elles sont nécessaires à une équivalence avec les classes du IFLA LRM. LRM<sub>OO</sub> est une extension du CIDOC CRM et ne peut pas être implémentée sans en utiliser les classes et propriétés essentielles. </p>
<p>LRM<sub>OO</sub> n’élabore sur IFLA LRM que dans certains cas où cela s’est avéré nécessaire lorsque : </p>
<ul><li><p>Une œuvre intègre une œuvre pré-existante de telle manière que toutes ses expressions doivent inclure une expression de la première, deux propriétés spécifiques sont alors utilisées : <code class="language-plaintext highlighter-rouge">R75_incorpore (est_inclus_dans)</code> entre les œuvres, et <code class="language-plaintext highlighter-rouge">R74_utilise_l’expression_de (a_l’expression_utilisée_dans)</code> entre les expressions. </p>
</li>
<li><p>Des ensembles d’œuvres partageant un concept commun (p. ex. le fait d’être situées dans un même univers fictif), parfois qualifiés de « super-œuvres », sont traités par le biais de la propriété <code class="language-plaintext highlighter-rouge">R10_est_composant_de (a_pour_composant)</code> qui lie une œuvre à la classe du CIDOC CRM <code class="language-plaintext highlighter-rouge">E28_Objet_conceptuel</code>. </p>
</li>
<li><p>Une performance en tant qu’évènement doit être liée à celle-ci en tant qu’œuvre performée par le biais de la classe <code class="language-plaintext highlighter-rouge">F31_Performance</code> et de la propriété <code class="language-plaintext highlighter-rouge">R80_a_interprété (est_interprété_dans)</code>, sachant que l’enregistrement d’une performance est aussi un type de création d’expression (<code class="language-plaintext highlighter-rouge">F28_Création_d’expression</code>) s’appuyant sur la propriété <code class="language-plaintext highlighter-rouge">R81_enregistré (est_enregistré_dans)</code>. </p>
</li></ul>
<p>LRM<sub>OO</sub> est une extension du CIDOC CRM qui permet l’interopérabilité sémantique et l’échange de données avec d’autres communautés du secteur patrimonial. L’ensemble des modèles qui relèvent du CIDOC CRM est de plus en plus diversifié et croissant, et la méthodologie de développement assure que chaque nouvel ensemble de modèles soit compatible afin que plusieurs extensions puissent être adoptées les unes avec les autres en fonction des besoins d’implémentation spécifiques à chaque cas. </p>
<p>LRM<sub>OO</sub> n’inclut pas de précisions en fonction de types de ressources particuliers. Tous ces aspects peuvent être pleinement représentés par le biais de « super-types » généraux du LRM<sub>OO</sub> ou du CIDOC CRM. Toute extension du IFLA LRM relative aux types de ressources pourrait faire l’objet d’extensions futures de LRM<sub>OO</sub>. </p>
<p>LRM<sub>OO</sub> est un modèle conceptuel : il s’adresse principalement à une audience spécialisée dotée de compétences techniques qui cherche à mettre en place et à implémenter des structures de données comportant de l’information bibliographique, en particulier lorsque cette audience a l’intention de soutenir l’intégration de données d’autres communautés patrimoniales. L’adoption de techniques orientées-objet permet l’utilisation du modèle dans le contexte des données ouvertes et liées et des technologies du web sémantique. Ce document prend pour acquis une familiarité avec la modélisation conceptuelle adoptant des formulations orientées-objet, avec les conventions du CIDOC CRM, et avec le IFLA LRM. </p>
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
<p>Riva, Pat, Patrick Le Bœuf, et Maja Žumer. <em>Un modèle conceptuel pour l’information bibliographique</em>. Traduit par Aude Le Moullec-Rieu, Françoise Leresche, Frédéric Puyrenier, et Mélanie Roche. Committee Publications. La Haye, NL: Fédération internationale des associations et institutions de bibliothèques (IFLA), 2021.<a href="https://repository.ifla.org/server/api/core/bitstreams/b395a0a0-c9b8-49c6-8919-9befda0c40ed/content"><span class="underline"> </span></a><a href="https://repository.ifla.org/server/api/core/bitstreams/b395a0a0-c9b8-49c6-8919-9befda0c40ed/content"><span class="underline">https://repository.ifla.org/server/api/core/bitstreams/b395a0a0-c9b8-49c6-8919-9befda0c40ed/content</span></a>.<em></em></p>
</td>
</tr>
</tbody>
</table>

