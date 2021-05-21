---
layout: page
title:  Application formelle
titleEn: Applied Form - Application formelle
permalink: /v7.1/information/application-formelle
sidebar: v71
group: info
---

**Date de création** : 2020-20-10

**Dernière mise à jour** : 2021-05-05

<div class="lang-buttons">
  <button id="fr" class="activate">FR</button>
  <button id="en-fr">EN-FR</button>
</div>

<table class="text">
<tbody>
<tr>
<td class="en"><p>The CIDOC CRM is an ontology in the sense used in computer science. It has been expressed as an object-oriented semantic model, in the hope that this formulation will be comprehensible to both documentation experts and information scientists alike, while at the same time being readily converted to machine-readable formats such as RDF Schema or OWL. It can be implemented in Relational or Object-Oriented schema. CIDOC CRM instances can also be encoded in RDF, JSON LD, XML, OWL among and others</p>
<p>Although the definition of the CIDOC CRM provided here is complete, it is an intentionally compact and concise presentation of the CIDOC CRM’s 81 classes and 160 unique properties. It does not attempt to articulate the inheritance of properties by subclasses throughout the class hierarchy (this would require the declaration of several thousand properties, as opposed to 160). However, this definition does contain all of the information necessary to infer and automatically generate a full declaration of all properties, including inherited properties.</p></td>
<td><p>Le CIDOC CRM est une ontologie (dans le sens informatique du terme) prenant la forme d’un modèle sémantique orienté-objet destiné à la conversion vers des formats lisibles par des machines (p. ex. <a href="https://www.w3.org/RDF/">RDF</a> Schema, <a href="https://www.w3.org/OWL/">OWL</a>), mais formulé afin d’être compris tant par les informaticiens que par les experts de la documentation. Son implémentation peut être faite sous forme de schémas relationnels ou orientés-objets et les instances de CIDOC CRM peuvent notamment être encodées en RDF, <a href="https://json-ld.org/">JSON-LD</a>, <a href="https://www.w3.org/XML/">XML</a> ou OWL.</p>
<p>La définition ci-présentée du CIDOC CRM est complète, bien qu’elle demeure une présentation intentionnellement concise et succincte de ses 81 classes et 160 propriétés uniques. Celle-ci n’a donc pas pour objectif de décliner l’héritage des propriétés par sous-classes à travers la hiérarchie des classes (ce qui exigerait la déclaration de plusieurs milliers de propriétés plutôt que de 160). Par contre, cette définition contient toute l’information nécessaire à l’inférence et à la génération automatique d’une déclaration complète des propriétés, ce qui inclut les propriétés héritées.</p></td>
</tr>
</tbody>
</table>
<table>
<tbody>
<tr class="odd">
<th><em>Note traducteur</em></th>
<td></td>
</tr>
<tr class="even">
<th><em>Références</em></th>
<td><p>JSON-LD Working Group. 2014. « JSON-LD - JSON for Linking Data ». JSON-LD. 16 janvier 2014. <a href="https://json-ld.org/">https://json-ld.org/</a>.</p>
<p>OWL Working Group. 2012. « OWL - Semantic Web Standards ». W3C. 11 décembre 2012. <a href="https://www.w3.org/OWL/">https://www.w3.org/OWL/</a>.</p>
<p>RDF Working Group. 2014. « RDF - Semantic Web Standards ». W3C. 25 février 2014. <a href="https://www.w3.org/RDF/">https://www.w3.org/RDF/</a>.</p>
<p>XML Working Group. 2016. « Extensible Markup Language (XML) ». W3C. 11 octobre 2016. <a href="https://www.w3.org/XML/">https://www.w3.org/XML/</a>.</p></td>
</tr>
</tbody>
</table>


<h2 id="hierarchies-de-classes-et-de-proprietes"><span class="en heading">Class & Property Hierarchies - </span>Hiérarchies de classes et de propriétés</h2>

<table class="text">
<tbody>
<tr>
<td class="en"><p>Although they do not provide comprehensive definitions, compact mono-hierarchical presentations of the class and property IsA hierarchies have been found to significantly aid comprehension and navigation of the CIDOC CRM. Since the CRM is poly-hierarchical, a mono-hierarchical presentation form is achieved by a top-down expansion of all inverse IsA relations regardless whether a concept has already be presented at another place in the same hierarchy. This form is provided below.</p>
<p>The class hierarchy presented below has the following format:</p>
<ul>
<li>
<p>Each line begins with a unique class identifier, consisting of a number preceded by the letter “E” (originally denoting “entity,” although now replaced by convention with the term “class”).</p>
</li>
<li>
<p>A series of hyphens (“-”) follows the unique class identifier, indicating the hierarchical position of the class in the IsA hierarchy.</p>
</li>
<li>
<p>The English name of the class appears to the right of the hyphens.</p>
</li>
<li>
<p>The index is ordered by hierarchical level, in a “depth first” manner, from the smaller to the larger subhierarchies.</p>
</li>
<li>
<p>Classes that appear in more than one position in the class hierarchy as a result of multiple inheritance are shown in an italic typeface.</p>
</li>
</ul>
<p>The property hierarchy presented below has the following format:</p>
<ul>
<li>
<p>Each line begins with a unique property identifier, consisting of a number preceded by the letter “P” (for “property”).</p>
</li>
<li>
<p>A series of hyphens (“-”) follows the unique property identifier, indicating the hierarchical position of the property in the IsA hierarchy.</p>
</li>
<li>
<p>The English name of the property appears to the right of the hyphens, followed by its inverse name in parentheses for reading in the range to domain direction.</p>
</li>
</ul>
<ul>
<li>
<p>The domain class for which the property is declared.</p>
</li>
<li>
<p>The range class that the property references.</p>
</li>
<li>
<p>The index is ordered by hierarchical level, in a “depth first” manner, from the smaller to the larger subhierarchies, and by property number between equal siblings.</p>
</li>
<li>
<p>Properties that appear in more than one position in the property hierarchy as a result of multiple inheritance are shown in an italic typeface.</p>
</li>
</ul></td>
<td><p>Bien qu’elles n’étayent pas de définitions exhaustives, les présentations succinctes et mono-hiérarchiques des classes et des propriétés contribuent à la navigation dans le CIDOC CRM et à la compréhension de celui-ci. Puisque le CIDOC CRM est poly-hiérarchique, la présentation mono-hiérarchique formelle découle d’une expansion descendante de toutes les relations estUn indépendamment de la présence d’un concept ailleurs dans ladite hiérarchie.</p>
<p>La hiérarchie de classes présentée ci-bas reprend la forme suivante :</p>
<ul>
<li>
<p>Chaque ligne commence avec un identifiant de classe unique composé d’un nombre précédé de la lettre « E » (qui signalait autrefois une « entité”, bien que le terme « classe » soit maintenant préféré).</p>
</li>
<li>
<p>Une série de traits d’union (« - ») suit cet identifiant de classe unique et indique la position de la classe dans la hiérarchie estUn.</p>
</li>
<li>
<p>Le nom de la classe se trouve à droite des traits d’union.</p>
</li>
<li>
<p>L’index est ordonné selon les niveaux hiérarchiques avec une approche de « parcours en profondeur » depuis les sous-hiérarchies les plus petites vers les plus larges.</p>
</li>
<li>
<p>L’apparition de classes dans de multiples positions dans la hiérarchie des classes en raison d’héritages multiples est signalée par l’usage des italiques.</p>
</li>
</ul>
<p>La hiérarchie des propriétés présentée ci-bas reprend la forme suivante :</p>
<ul>
<li>
<p>Chaque ligne commence avec un identifiant de propriété unique composé d’un nombre précédé de la lettre « P » (pour « propriété »).</p>
</li>
<li>
<p>Une série de traits d’union (« - ») suit cet identifiant de propriété unique et indique la position de la propriété dans la hiérarchie estUn.</p>
</li>
<li>
<p>Le nom de la propriété se trouve à droite des traits d’union, suivi par le nom de la propriété inverse entre parenthèses (à des fins de lecture depuis la portée vers le domaine).</p>
</li>
<li>
<p>L’index est ordonné selon les niveaux hiérarchiques avec une approche de « parcours en profondeur » depuis les sous-hiérarchies les plus petites vers les plus larges, puis par numéro de propriété dans le cas de propriétés-soeurs égales.</p>
</li>
<li>
<p>L’apparition de propriétés dans de multiples positions dans la hiérarchie des propriétés en raison d’héritages multiples est signalée par l’usage des italiques.</p>
</li>
</ul></td>
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

<h3 id="hierarchies-de-classes"><span class="en heading">Classes - </span>Classes</h3>

|Code|||||||||||
|---- |:------------------------: |:-------------------------------------------: |:----------------------------------------------------: |:-----------------------------------: |:---------------------------------------------------------: |:-------------------------------------------------------: |:------------------------------------------------------: |:--------------------------------------------------------: |:----------------------------------------------: |:-----------------------------: |
|E1|<span class="en">CRM Entity </span>`E1_Entité_CRM`||||||||||
|E2|-|<span class="en">Temporal Entity </span>`E2_Entité_temporelle`|||||||||
|E3|-|-|<span class="en">Condition State </span>`E3_État_matériel`||||||||
|E4|-|-|<span class="en">Period </span>`E4_Période`||||||||
|E5|-|-|-|<span class="en">Event </span>`E5_Évènement`|||||||
|E7|-|-|-|-|<span class="en">Activity </span>`E7_Activité`||||||
|E8|-|-|-|-|-|<span class="en">Acquisition </span>`E8_Acquisition`|||||
|E96|-|-|-|-|-|-|<span class="en">Purchase </span>`E96_Achat`||||
|E9|-|-|-|-|-|<span class="en">Move </span>`E9_Déplacement`|||||
|E10|-|-|-|-|-|<span class="en">Transfer of Custody </span>`E10_Transfert_de_la_garde`|||||
|E11|-|-|-|-|-|<span class="en">Modification </span>`E11_Modification`|||||
|E12|-|-|-|-|-|-|<span class="en">Production </span>`E12_Production`||||
|E79|-|-|-|-|-|-|<span class="en">Part Addition </span>`E79_Ajout_d’élément`||||
|E80|-|-|-|-|-|-|<span class="en">Part Removal </span>`E80_Retrait_d’élément`||||
|E13|-|-|-|-|-|<span class="en">Attribute Assignment </span>`E13_Attribution`|||||
|E14|-|-|-|-|-|-|<span class="en">Condition Assesment </span>`E14_Évaluation_d’état_matériel`||||
|E15|-|-|-|-|-|-|<span class="en">Identifier Assignment </span>`E15_Attribution_d’identifiant`||||
|E16|-|-|-|-|-|-|<span class="en">Measurement </span>`E16_Mesurage`||||
|E17|-|-|-|-|-|-|<span class="en">Type Assignment </span>`E17_Attribution_de_type`||||
|E65|-|-|-|-|-|<span class="en">Creation </span>`E65_Création`|||||
|E83|-|-|-|-|-|-|<span class="en">Type Creation </span>`E83_Création_de_type`||||
|E66|-|-|-|-|-|<span class="en">Formation </span>`E66_Formation`|||||
|E85|-|-|-|-|-|<span class="en">Joining </span>`E85_Adhésion`|||||
|E86|-|-|-|-|-|<span class="en">Leaving </span>`E86_Départ`|||||
|E87|-|-|-|-|-|<span class="en">Curation Activity </span>`E87_Activité_curatoriale`|||||
|E63|-|-|-|-|<span class="en">Beginning of Existence </span>`E63_Début_d’existence`||||||
|E67|-|-|-|-|-|<span class="en">Birth </span>`E67_Naissance`|||||
|E81|-|-|-|-|-|<span class="en">Transformation </span>`E81_Transformation`|||||
|E12|-|-|-|-|-|<span class="en"><em>Production </em></span>*`E12_Production`*              |||||
|E65|-|-|-|-|-|<span class="en"><em>Creation </em></span>*`E65_Création`*                |||||
|E83|-|-|-|-|-||<span class="en"><em>Type Creation </em></span>*`E83_Création_de_type`*         ||||
|E66|-|-|-|-|-|<span class="en"><em>Formation </em></span>*`E66_Formation`*               |||||
|E64|-|-|-|-|<span class="en">End of Existence </span>`E64_Fin_d’existence`||||||
|E6|-|-|-|-|-|<span class="en">Destruction </span>`E6_Destruction`|||||
|E68|-|-|-|-|-|<span class="en">Dissolution </span>`E68_Dissolution`|||||
|E69|-|-|-|-|-|<span class="en">Death </span>`E69_Mort`|||||
|E81|-|-|-|-|-|<span class="en"><em>Transformation </em></span>*`E81_Transformation`*          |||||
|E77|-|<span class="en">Persistent Item </span>`E77_Entité_persistante`|||||||||
|E70|-|-|<span class="en">Thing </span>`E70_Chose`||||||||
|E72|-|-|-|<span class="en">Legal Object </span>`E72_Objet_juridique`|||||||
|E18|-|-|-|-|<span class="en">Physical Thing </span>`E18_Chose_matérielle`||||||
|E19|-|-|-|-|-|<span class="en">Physical Object </span>`E19_Objet_matériel`|||||
|E20|-|-|-|-|-|-|<span class="en">Biological Object </span>`E20_Objet_biologique`||||
|E21|-|-|-|-|-|-|-|<span class="en">Person </span>`E21_Personne`|||
|E22|-|-|-|-|-|-|<span class="en">Human-Made Object </span>`E22_Objet_façonné`||||
|E24|-|-|-|-|-|<span class="en">Physical Human-Made Thing </span>`E24_Chose_matérielle_façonnée`|||||
|E22|-|-|-|-|-|-|<span class="en"><em>Human-Made Object  </em></span>*`E22_Objet_façonné`*          ||||
|E25|-|-|-|-|-|-|<span class="en">Human-Made Feature </span>`E25_Caractéristique_façonnée`||||
|E78|-|-|-|-|-|-|<span class="en">Curated Holding </span>`E78_Collection`||||
|E26|-|-|-|-|-|<span class="en">Physical Feature </span>`E26_Caractéristique_physique`|||||
|E27|-|-|-|-|-|-|<span class="en">Site </span>`E27_Site`||||
|E25|-|-|-|-|-|-|<span class="en"><em>Human-Made Feature  </em></span>*`E25_Caractéristique_façonnée`*    ||||
|E90|-|-|-|-|<span class="en">Symbolic Object E90_Objet_symbolique             ||||||
|E73|-|-|-|-|-|<span class="en">Information Object </span>`E73_Objet_informationnel`|||||
|E29|-|-|-|-|-|-|<span class="en">Design or Procedure </span>`E29_Conceptualisation_ou_procédure`||||
|E31|-|-|-|-|-|-|<span class="en">Document </span>`E31_Document`||||
|E32|-|-|-|-|-|-|-|<span class="en">Authority Document </span>`E32_Document_de_référence`|||
|E33|-|-|-|-|-|-|<span class="en">Linguistic Object </span>`E33_Objet_linguistique`||||
|E34|-|-|-|-|-|-|-|<span class="en">Inscription </span>`E34_Inscription`|||
|E35|-|-|-|-|-|-|-|<span class="en">Title </span>`E35_Titre`|||
|E36|-|-|-|-|-|-|<span class="en">Visual Item </span>`E36_Entité_visuelle`||||
|E37|-|-|-|-|-|-|-|<span class="en">Mark </span>`E37_Marque`|||
|E34|-|-|-|-|-|-|-|-|<span class="en">Inscription </span>`E34_Inscription`||
|E41|-|-|-|-|-|<span class="en">Appellation E41_Appellation                |||||
|E42|-|-|-|-|-|-|<span class="en">Identifier </span>`E42_Identifiant`||||
|E35|-|-|-|-|-|-|<span class="en">Title </span>`E35_Titre`||||
|E95|-|-|-|-|-|-|<span class="en">Spacetime Primitive </span>`E95_Primitive_spatio-temporelle`||||
|E94|-|-|-|-|-|-|<span class="en">Space Primitive </span>`E94_Primitive_spatiale`||||
|E61|-|-|-|-|-|-|<span class="en">Time Primitive </span>`E61_Primitive_temporelle`||||
|E71|-|-|-|<span class="en">Human-Made Thing </span>`E71_Chose_façonnée`|||||||
|E24|-|-|-|-|<span class="en"><em>Physical Human-Made Thing  </em></span>*`E24_Chose_matérielle_façonnée`* ||||||
|E22|-|-|-|-|-|<span class="en"><em>Human-Made Object  </em></span>*`E22_Objet_façonné`*          |||||
|E25|-|-|-|-|-|<span class="en"><em>Human-Made Feature  </em></span>*`E25_Caractéristique_façonnée`*    |||||
|E78|-|-|-|-|-|<span class="en"><em>Curated Holding  </em></span>*`E78_Collection`*             |||||
|E28|-|-|-|-|<span class="en">Conceptual Object </span>`E28_Objet_conceptuel`||||||
|E90|-|-|-|-|-|<span class="en"><em>Symbolique Object  </em></span>*`E90_Objet_symbolique`*         |||||
|E73|-|-|-|-|-|-|<span class="en"><em>Information Object  </em></span>*`E73_Objet_informationnel`*      ||||
|E29|-|-|-|-|-|-|-|<span class="en"><em>Design or Procedure  </em></span>*`E29_Conceptualisation_ou_procédure`* |||
|E31|-|-|-|-|-|-|-|<span class="en"><em>Document  </em></span>*`E31_Document`*                  |||
|E32|-|-|-|-|-|-|-|-|<span class="en"><em>Authority Document  </em></span>*`E32_Document_de_référence`* ||
|E33|-|-|-|-|-|-|-|<span class="en"><em>Linguistic Object  </em></span>*`E33_Objet_linguistique`*        |||
|E34|-|-|-|-|-|-|-|-|<span class="en"><em>Inscription  </em></span>*`E34_Inscription`*          ||
|E35|-|-|-|-|-|-|-|-|<span class="en"><em>Title  </em></span>*`E35_Titre`*                ||
|E36|-|-|-|-|-|-|-|<span class="en"><em>Visual Item  </em></span>*`E36_Entité_visuelle`*             |||
|E37|-|-|-|-|-|-|-|-|<span class="en"><em>Mark  </em></span>*`E37_Marque`*                ||
|E34|-|-|-|-|-|-|-|-|-|<span class="en"><em>Inscription  </em></span>*`E34_Inscription`* |
|E41|-|-|-|-|-|-|<span class="en"><em>Appellation  </em></span>*`E41_Appellation`*              ||||
|E42|-|-|-|-|-|-|-|<span class="en"><em>Identifier  </em></span>*`E42_Identifiant`*               |||
|E35|-|-|-|-|-|-|-|<span class="en"><em>Title  </em></span>*`E35_Titre`*                     |||
|E95|-|-|-|-|-|-|-|<span class="en"><em>Spacetime Primitive  </em></span>*`E95_Primitive_spatio-temporelle`*   |||
|E94|-|-|-|-|-|-|-|<span class="en"><em>Space Primitive  </em></span>*`E94_Primitive_spatiale`*         |||
|E61|-|-|-|-|-|-|-|<span class="en"><em>Time Primitive  </em></span>*`E61_Primitive_temporelle`*         |||
|E89|-|-|-|-|-|<span class="en">Propositional Object </span>`E89_Objet_propositionnel`|||||
|E73|-|-|-|-|-|-|<span class="en"><em>Information Object  </em></span>*`E73_Objet_informationnel`*      ||||
|E29|-|-|-|-|-|-|-|<span class="en"><em>Design or Procedure  </em></span>*`E29_Conceptualisation_ou_procédure`* |||
|E31|-|-|-|-|-|-|-|<span class="en"><em>Document  </em></span>*`E31_Document`*                  |||
|E32|-|-|-|-|-|-|-|-|<span class="en"><em>Authority Document  </em></span>*`E32_Document_de_référence`* ||
|E33|-|-|-|-|-|-|-|<span class="en"><em>Linguistic Object  </em></span>*`E33_Objet_linguistique`*        |||
|E34|-|-|-|-|-|-|-|-|<span class="en"><em>Inscription  </em></span>*`E34_Inscription`*          ||
|E35|-|-|-|-|-|-|-|-|<span class="en"><em>Title  </em></span>*`E35_Titre`*                ||
|E36|-|-|-|-|-|-|-|<span class="en"><em>Visual Item  </em></span>*`E36_Entité_visuelle`*             |||
|E37|-|-|-|-|-|-|-|-|<span class="en"><em>Mark  </em></span>*`E37_Marque`*                ||
|E34|-|-|-|-|-|-|-|-|-|<span class="en"><em>Inscription  </em></span>*`E34_Inscription`* |
|E30|-|-|-|-|-|-|<span class="en">Right </span>`E30_Droit`||||
|E55|-|-|-|-|-|<span class="en">Type </span>`E55_Type`|||||
|E56|-|-|-|-|-|-|<span class="en">Language </span>`E56_Langue`||||
|E57|-|-|-|-|-|-|<span class="en">Material </span>`E57_Matériau`||||
|E58|-|-|-|-|-|-|<span class="en">Measurement Unit </span>`E58_Unité_de_mesure`||||
|E98|-|-|-|-|-|-|-|<span class="en">Currency </span>`E98_Monnaie`|||
|E99|-|-|-|-|-|-|<span class="en">Product Type </span>`E99_Modèle_de_produit`||||
|E39|-|-|<span class="en">Actor </span>`E39_Acteur`||||||||
|E74|-|-|-|<span class="en">Group </span>`E74_Groupe`|||||||
|E21|-|-|-|<span class="en"><em>Person  </em></span>*`E21_Personne`*        |||||||
|E52|-|<span class="en">Time-Span </span>`E52_Intervalle_temporel`|||||||||
|E53|-|<span class="en">Place </span>`E53_Lieu`|||||||||
|E54|-|<span class="en">Dimension </span>`E54_Dimension`|||||||||
|E97|-|-|<span class="en">Monetary Amount </span>`E97_Valeur_monétaire`||||||||
|E92|-|<span class="en">Spacetime Volume </span>`E92_Volume_spatio-temporel`|||||||||
|E4|-|-|<span class="en"><em>Period  </em></span>*`E4_Période`*                  ||||||||
|E5|-|-|-|<span class="en"><em>Event  </em></span>*`E5_Évènement`*         |||||||
|E7|-|-|-|-|<span class="en"><em>Activity  </em></span>*`E7_Activité`*                   ||||||
|E8|-|-|-|-|-|<span class="en"><em>Acquisition  </em></span>*`E8_Acquisition`*               |||||
|E96|-|-|-|-|-|-|<span class="en"><em>Purchase  </em></span>*`E96_Achat`*                  ||||
|E9|-|-|-|-|-|<span class="en"><em>Move  </em></span>*`E9_Déplacement`*                  |||||
|E10|-|-|-|-|-|<span class="en"><em>Transfer of Custody  </em></span>*`E10_Transfert_de_la_garde`*     |||||
|E11|-|-|-|-|-|<span class="en"><em>Modification  </em></span>*`E11_Modification`*             |||||
|E12|-|-|-|-|-|-|<span class="en"><em>Production  </em></span>*`E12_Production`*               ||||
|E79|-|-|-|-|-|-|<span class="en"><em>Part Addition  </em></span>*`E79_Ajout_d’élément`*           ||||
|E80|-|-|-|-|-|-|<span class="en"><em>Part Removal  </em></span>*`E80_Retrait_d’élément`*          ||||
|E13|-|-|-|-|-|<span class="en"><em>Attribute Assignment  </em></span>*`E13_Attribution`*          |||||
|E14|-|-|-|-|-|-|<span class="en"><em>Condition Assessment  </em></span>*`E14_Évaluation_d’état_matériel`*  ||||
|E15|-|-|-|-|-|-|<span class="en"><em>Identifier Assignment  </em></span>*`E15_Attribution_d’identifiant`*  ||||
|E16|-|-|-|-|-|-|<span class="en"><em>Measurement  </em></span>*`E16_Mesurage`*               ||||
|E17|-|-|-|-|-|-|<span class="en"><em>Type Assignment  </em></span>*`E17_Attribution_de_type`*        ||||
|E65|-|-|-|-|-|<span class="en"><em>Creation  </em></span>*`E65_Création`*                 |||||
|E83|-|-|-|-|-|-|<span class="en"><em>Type Creation  </em></span>*`E83_Création_de_type`*          ||||
|E66|-|-|-|-|-|<span class="en"><em>Formation  </em></span>*`E66_Formation`*                |||||
|E85|-|-|-|-|-|<span class="en"><em>Joining  </em></span>*`E85_Adhésion`*                  |||||
|E86|-|-|-|-|-|<span class="en"><em>Leaving  </em></span>*`E86_Départ`*                   |||||
|E87|-|-|-|-|-|<span class="en"><em>Curation Activity  </em></span>*`E87_Activité_curatoriale`*       |||||
|E63|-|-|-|-|<span class="en"><em>Beginning of Existence  </em></span>*`E63_Début_d’existence`*       ||||||
|E67|-|-|-|-|-|<span class="en"><em>Birth  </em></span>*`E67_Naissance`*                  |||||
|E81|-|-|-|-|-|<span class="en"><em>Transformation  </em></span>*`E81_Transformation`*           |||||
|E12|-|-|-|-|-|<span class="en"><em>Production  </em></span>*`E12_Production`*               |||||
|E65|-|-|-|-|-|<span class="en"><em>Creation  </em></span>*`E65_Création`*                 |||||
|E83|-|-|-|-|-|-|<span class="en"><em>Type Creation  </em></span>*`E83_Création_de_type`*          ||||
|E66|-|-|-|-|-|<span class="en"><em>Formation  </em></span>*`E66_Formation`*                |||||
|E64|-|-|-|-|<span class="en"><em>End of Existence  </em></span>*`E64_Fin_d’existence`*           ||||||
|E6|-|-|-|-|-|<span class="en"><em>Destruction  </em></span>*`E6_Destruction`*               |||||
|E68|-|-|-|-|-|<span class="en"><em>Dissolution  </em></span>*`E68_Dissolution`*              |||||
|E69|-|-|-|-|-|<span class="en"><em>Death  </em></span>*`E69_Mort`*                     |||||
|E81|-|-|-|-|-|<span class="en"><em>Transformation  </em></span>*`E81_Transformation`*           |||||
|E93|-|-|<span class="en">Presence </span>`E93_Présence`||||||||
|E59|-|<span class="en">Primitive Value </span>`E59_Valeur_primitive`|||||||||
|E60|-|-|<span class="en">Number </span>`E60_Nombre`||||||||
|E61|-|-|<span class="en"><em>Time Primitive  </em></span>*`E61_Primitive_temporelle`*       ||||||||
|E62|-|-|<span class="en">String </span>`E62_Chaîne_de_caractères`||||||||
|E94|-|-|<span class="en"><em>Space Primitive  </em></span>*`E94_Primitive_spatiale`*       ||||||||
|E95|-|-|<span class="en"><em>Spacetime Primitive  </em></span>*`E95_Primitive_spatio-temporelle`* ||||||||


<h3 id="hierarchies-de-proprietes"><span class="en heading">Properties - </span>Propriétés</h3>
