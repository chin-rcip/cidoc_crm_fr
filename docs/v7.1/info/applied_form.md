---
layout: page
title:  Application formelle
titleEn: Applied Form - Application formelle
permalink: /v7.1/information/application-formelle
sidebar: v71
group: info
date: 2021-06-03
---

**Date de création** : 2020-20-10

**Dernière mise à jour** : 2021-06-03

<div class="lang-buttons">
  <button id="fr" class="activate">FR</button>
  <button id="en-fr">EN-FR</button>
</div>

<table class="text">
<colgroup>
<col style="width: 50%">
</colgroup>
<tbody>
<tr>
<td class="en"><p>The CIDOC CRM is an ontology in the sense used in computer science. It has been expressed as an object-oriented semantic model, in the hope that this formulation will be comprehensible to both documentation experts and information scientists alike, while at the same time being readily converted to machine-readable formats such as RDF Schema or OWL. It can be implemented in Relational or Object-Oriented schema. CIDOC CRM instances can also be encoded in RDF, JSON LD, XML, OWL among and others</p>
<p>Although the definition of the CIDOC CRM provided here is complete, it is an intentionally compact and concise presentation of the CIDOC CRM’s 81 classes and 160 unique properties. It does not attempt to articulate the inheritance of properties by subclasses throughout the class hierarchy (this would require the declaration of several thousand properties, as opposed to 160). However, this definition does contain all of the information necessary to infer and automatically generate a full declaration of all properties, including inherited properties.</p></td>
<td><p>Le CIDOC CRM est une ontologie (dans le sens informatique du terme) prenant la forme d’un modèle sémantique orienté-objet destiné à la conversion vers des formats lisibles par des machines (p. ex. <a href="https://www.w3.org/RDF/"><strong>RDF</strong></a> Schema, <a href="https://www.w3.org/OWL/"><strong>OWL</strong></a>), mais formulé afin d’être compris tant par les informaticiens que par les experts de la documentation. Son implémentation peut être faite sous forme de schémas relationnels ou orientés-objets et les instances de CIDOC CRM peuvent notamment être encodées en RDF, <a href="https://json-ld.org/"><strong>JSON-LD</strong></a>, <a href="https://www.w3.org/XML/"><strong>XML</strong></a> ou OWL.</p>
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
<colgroup>
<col style="width: 50%">
</colgroup>
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
<td><p>Bien qu’elles n’étayent pas de définitions exhaustives, les présentations succinctes et mono-hiérarchiques des classes et des propriétés contribuent à la navigation dans le CIDOC CRM et à la compréhension de celui-ci. Puisque le CIDOC CRM est poly-hiérarchique, la présentation mono-hiérarchique formelle découle d’une expansion descendante de toutes les relations <code class="language-plaintext highlighter-rouge">estUn</code> indépendamment de la présence d’un concept ailleurs dans ladite hiérarchie.</p>
<p>La hiérarchie de classes présentée ci-bas reprend la forme suivante :</p>
<ul>
<li>
<p>Chaque ligne commence avec un identifiant de classe unique composé d’un nombre précédé de la lettre « E » (qui signalait autrefois une « entité”, bien que le terme « classe » soit maintenant préféré).</p>
</li>
<li>
<p>Une série de traits d’union (« - ») suit cet identifiant de classe unique et indique la position de la classe dans la hiérarchie <code class="language-plaintext highlighter-rouge">estUn</code>.</p>
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
<p>Une série de traits d’union (« - ») suit cet identifiant de propriété unique et indique la position de la propriété dans la hiérarchie <code class="language-plaintext highlighter-rouge">estUn</code>.</p>
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

> *Avertissement : Cette traduction en français du CIDOC CRM est en cours.<br><br>La documentation présentée ici est un travail actuellement en cours. À ce titre, bien qu’elle soit publiquement disponible, elle ne constitue en rien une publication officielle et des changements y sont apportés sur une base régulière. Par conséquent, il est préférable d’attendre une publication officielle de l’entièreté du contenu du CIDOC CRM avant d’implémenter cette traduction.*

<blockquote class="en block">
	<p>
		<em>Disclaimer: This French Translation of the CIDOC CRM is currently in progress.<br><br>
The documentation hereby accessible is a work in progress. As such, although it is publically released, it does not constitute an official publication and changes are made on an ongoing basis. Therefore, it is preferable to wait for an official publication of the entire content of CIDOC CRM before implementing this translation.
</em>
	</p>
</blockquote>

|**<span class="en">Class id - </span>Identifiant unique de classe**|||||||||||
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
|E22|-|-|-|-|-|-|<span class="en">Human-Made Object </span>`E22_Objet_élaboré_par_l’humain`||||
|E24|-|-|-|-|-|<span class="en">Physical Human-Made Thing </span>`E24_Chose_matérielle_élaborée_par_l’humain`|||||
|E22|-|-|-|-|-|-|<span class="en"><em>Human-Made Object  </em></span>*`E22_Objet_élaboré_par_l’humain`*          ||||
|E25|-|-|-|-|-|-|<span class="en">Human-Made Feature </span>`E25_Caractéristique_élaborée_par_l’humain`||||
|E78|-|-|-|-|-|-|<span class="en">Curated Holding </span>`E78_Collection`||||
|E26|-|-|-|-|-|<span class="en">Physical Feature </span>`E26_Caractéristique_physique`|||||
|E27|-|-|-|-|-|-|<span class="en">Site </span>`E27_Site`||||
|E25|-|-|-|-|-|-|<span class="en"><em>Human-Made Feature  </em></span>*`E25_Caractéristique_élaborée_par_l’humain`*    ||||
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
|E71|-|-|-|<span class="en">Human-Made Thing </span>`E71_Chose_élaborée_par_l’humain`|||||||
|E24|-|-|-|-|<span class="en"><em>Physical Human-Made Thing  </em></span>*`E24_Chose_matérielle_élaborée_par_l’humain`* ||||||
|E22|-|-|-|-|-|<span class="en"><em>Human-Made Object  </em></span>*`E22_Objet_élaboré_par_l’humain`*          |||||
|E25|-|-|-|-|-|<span class="en"><em>Human-Made Feature  </em></span>*`E25_Caractéristique_élaborée_par_l’humain`*    |||||
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
|E39|-|-|<span class="en">Actor </span>`E39_Actant`||||||||
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

> *Avertissement : Cette traduction en français du CIDOC CRM est en cours.<br><br>La documentation présentée ici est un travail actuellement en cours. À ce titre, bien qu’elle soit publiquement disponible, elle ne constitue en rien une publication officielle et des changements y sont apportés sur une base régulière. Par conséquent, il est préférable d’attendre une publication officielle de l’entièreté du contenu du CIDOC CRM avant d’implémenter cette traduction.*

<blockquote class="en block">
	<p>
		<em>Disclaimer: This French Translation of the CIDOC CRM is currently in progress.<br><br>
The documentation hereby accessible is a work in progress. As such, although it is publically released, it does not constitute an official publication and changes are made on an ongoing basis. Therefore, it is preferable to wait for an official publication of the entire content of CIDOC CRM before implementing this translation.
</em>
	</p>
</blockquote>

|**<span class="en">Property id - </span> Identifiant unique de propriété**|**<span class="en">Property Name - </span> Nom de la propriété**||||||**<span class="en">Entity Domain - </span> Domaine**|**<span class="en">Entity Range - </span> Portée**|
|P1|<span class="en">is identified by (identifies) </span>`P1_est_identifié_par (identifie)`||||||<span class="en">E1 CRM Entity </span>`E1_Entité_CRM`|<span class="en">E41 Appellation </span>`E41_Appellation`|
|P48|-|<span class="en">has preferred identifier (is preferred identifier of) </span>`P48_a_pour_identifiant_préférentiel (est_identifiant_préférentiel_de)`|||||<span class="en">E1 CRM Entity </span>`E1_Entité_CRM`|<span class="en">E42 Identifier </span>`E42_Identifiant`|
|P102|-|<span class="en">has title (is title of) </span>`P102_a_pour_titre (est_titre_de)`|||||<span class="en">E71 Human-Made Thing </span>`E71_Chose_élaborée_par_l’humain`|<span class="en">E35 Title </span>`E35_Titre`|
|P1i|<span class="en">identifies </span>`P1i_identifie`||||||<span class="en">E41 Appellation </span>`E41_Appellation`|<span class="en">E1 CRM Entity </span>`E1_Entité_CRM`|
|P168|-|<span class="en">place is defined by (defines place) </span>`P168_lieu_défini_par (définit_le_lieu)`|||||<span class="en">E53 Place </span>`E53_Lieu`|<span class="en">E94 Space Primitive </span>`E94_Primitive_spatiale`|
|P169|-|<span class="en">defines spacetime volume (spacetime volume is defined by) </span>`P169_volume_spatio-temporel_défini_par (définit_le_volume_spatio-temporel)`|||||<span class="en">E95 Spacetime Primitive </span>`E95_Primitive_spatio-temporelle`|<span class="en">E92 Spacetime Volume </span>`E92_Volume_spatio-temporel`|
|P170|-|<span class="en">defines time (time is defined by) </span>`P170_temps_défini_par (définit_le_temps)`|||||<span class="en">E61 Time Primitive </span>`E61_Primitive_temporelle`|<span class="en">E52 Time-Span </span>`E52_Intervalle_temporel `|
|P2|<span class="en">has type (is type of) </span>`P2_a_pour_type (est_type_de)`||||||<span class="en">E1 CRM Entity </span>`E1_Entité_CRM`|<span class="en">E55 Type </span>`E55_Type`|
|P137|-|<span class="en">exemplifies (is exemplified by) </span>`P137_exemplifie (est_exemplifié_par)`|||||<span class="en">E1 CRM Entity </span>`E1_Entité_CRM`|<span class="en">E55 Type </span>`E55_Type`|
|P177|-|<span class="en">assigned property type </span>`P177_a_attribué_le_type_de_propriété `|||||<span class="en">E13 Attribute Assignment </span>`E13_Attribution`|<span class="en">E55 Type </span>`E55_Type`|
|P3|<span class="en">has note </span>`P3_a_pour_note`||||||<span class="en">E1 CRM Entity </span>`E1_Entité_CRM`|<span class="en">E62 String </span>`E62_Chaîne_de_caractères`|
|P79|-|<span class="en">beginning is qualified by </span>`P79_a_son_début_qualifié_par`|||||<span class="en">E52 Time-Span </span>`E52_Intervalle_temporel `|<span class="en">E62 String </span>`E62_Chaîne_de_caractères`|
|P80|-|<span class="en">end is qualified by </span>`P80_a_sa_fin_qualifiée_par`|||||<span class="en">E52 Time-Span </span>`E52_Intervalle_temporel `|<span class="en">E62 String </span>`E62_Chaîne_de_caractères`|
|P190|-|<span class="en">has symbolic content </span>`P190_a_pour_contenu_symbolique`|||||<span class="en">E90 Symbolic Object </span>`E90_Objet_symbolique`|<span class="en">E62 String </span>`E62_Chaîne_de_caractères`|
|P4|<span class="en">has time-span (is time-span of) </span>`P4_a_pour_intervalle_temporel (est_l’intervalle_temporel_de)`||||||<span class="en">E2 Temporal Entity </span>`E2_Entité_temporelle`|<span class="en">E52 Time-Span </span>`E52_Intervalle_temporel `|
|P5|<span class="en">consists of (forms part of) </span>`P5_consiste_en (fait_partie_de)`||||||<span class="en">E3 Condition State </span>`E3_État_matériel`|<span class="en">E3 Condition State </span>`E3_État_matériel`|
|P7|<span class="en">took place at (witnessed) </span>`P7_a_eu_lieu_dans (a_été_témoin_de)`||||||<span class="en">E4 Period </span>`E4_Période`|<span class="en">E53 Place </span>`E53_Lieu`|
|P8|<span class="en">took place on or within (witnessed) </span>`P8_a_eu_lieu (a_été_témoin_de)`||||||<span class="en">E4 Period </span>`E4_Période`|<span class="en">E18 Physical Thing </span>`E18_Chose_matérielle`|
|P12|<span class="en">occured in the presence of (was present at) </span>`P12_a_eu_lieu_en_présence_de (a_été_présent_à)`||||||<span class="en">E5 Event </span>`E5_Évènement`|<span class="en">E77 Persistent Item </span>`E77_Entité_persistante`|
|P111|-|<span class="en">added (was added by) </span>`P111_a_ajouté (a_été_ajouté_par)`|||||<span class="en">E79 Part Addition </span>`E79_Ajout_d’élément`|<span class="en">E18 Physical Thing </span>`E18_Chose_matérielle`|
|P113|-|<span class="en">removed (was removed by) </span>`P113_a_retiré (a_été_retiré_par)`|||||<span class="en">P80 Part Removal </span>`E80_Retrait_d’élément`|<span class="en">E18 Physical Thing </span>`E18_Chose_matérielle`|
|P11|-|<span class="en">had participant (participated in) </span>`P11_a_eu_pour_actant_participant (a_participé_à)`|||||<span class="en">E5 Event </span>`E5_Évènement`|<span class="en">E39 Actor </span>`E39_Actant`|
|P14|-|-|<span class="en">carried out by (performed) </span>`P14_a_été_effectué_par (a_effectué)`||||<span class="en">E7 Activity </span>`E7_Activité`|<span class="en">E39 Actor </span>`E39_Actant`|
|P22|-|-|-|<span class="en">transferred title to (acquired title through) </span>`P22_a_transféré_le_titre_de_propriété_à (a_acquis_le_titre_de_propriété_par)`|||<span class="en">E8 Acquisition </span>`E8_Acquisition`|<span class="en">E39 Actor </span>`E39_Actant`|
|P23|-|-|-|<span class="en">transferred title from (surrendered title through) </span>`P23_a_transféré_le_titre_de_propriété_de (a_cédé_le_titre_de_propriété_à)`|||<span class="en">E8 Acquisition </span>`E8_Acquisition`|<span class="en">E39 Actor </span>`E39_Actant`|
|P28|-|-|-|<span class="en">Custody surrendered by (surrendered custody through) </span>`P28_a_mis_fin_à_la_garde_par (a_cédé_la_garde_par)`|||<span class="en">E10 Transfer of Custody </span>`E10_Transfert_de_la_garde`|<span class="en">E39 Actor </span>`E39_Actant`|
|P29|-|-|-|<span class="en">custody received by (received custody through) </span>`P29_a_confié_la_garde_par (a_reçu_la_garde_par)`|||<span class="en">E10 Transfer of Custody </span>`E10_Transfert_de_la_garde`|<span class="en">E39 Actor </span>`E39_Actant`|
|P96|-|-|<span class="en">by mother (gave birth) </span>`P96_de_mère (a_donné_naissance_à)`||||<span class="en">E67 Birth </span>`E67_Naissance`|<span class="en">E21 Person </span>`E21_Personne`|
|P99|-|-|<span class="en">dissolved (was dissolved by) </span>`P99_a_dissous (a_été_dissous_par)`||||<span class="en">E68 Dissolution </span>`E68_Dissolution`|<span class="en">E74 Group </span>`E74_Groupe`|
|P143|-|-|<span class="en">joined (was joined by) </span>`P143_a_fait_adhérer (a_adhéré_par)`||||<span class="en">E85 Joining </span>`E85_Adhésion`|<span class="en">E39 Actor </span>`E39_Actant`|
|P144|-|-|<span class="en">joined with (gained memeber by) </span>`P144_a_fait_adhérer_à (a_accueilli_un_membre_par)`||||<span class="en">E85 Joining </span>`E85_Adhésion`|<span class="en">E74 Group </span>`E74_Groupe`|
|P145|-|-|<span class="en">separated (left by) </span>`P145_a_dissocié_de (s’est_dissocié_par)`||||<span class="en">E86 Leaving </span>`E86_Départ`|<span class="en">E39 Actor </span>`E39_Actant`|
|P146|-|-|<span class="en">separated from (lost member by) </span>`P146_s’est_dissocié_par (a_perdu_un_membre_par)`||||<span class="en">E86 Leaving </span>`E86_Départ`|<span class="en">E74 Group </span>`E74_Groupe`|
|P151|-|-|<span class="en">was formed from (participated in) </span>`P151_a_été_formé_à_partir_de (a_participé_à)`||||<span class="en">E66 Formation </span>`E66_Formation`|<span class="en">E74 Group </span>`E74_Groupe`|
|P16|-|<span class="en">used specific object (was used for) </span>`P16_a_mobilisé_l’objet_spécifique (a_été_mobilisé_pour)`|||||<span class="en">E7 Activity </span>`E7_Activité`|<span class="en">E70 Thing </span>`E70_Chose`|
|P33|-|-|<span class="en">used specific technique (was used by) </span>`P33_a_mobilisé_comme_technique_spécifique (a_été_une_technique_spécifique_mise_en_œuvre_dans)`||||<span class="en">E7 Activity </span>`E7_Activité`|<span class="en">E29 Design or Procedure </span>`E29_Conceptualisation_ou_procédure`|
|P111|-|-|<span class="en">added (as added by) </span>`P111_a_ajouté (a_été_ajouté_par)`||||<span class="en">E79 Part Addition </span>`E79_Ajout_d’élément`|<span class="en">E18 Physical Thing </span>`E18_Chose_matérielle`|
|P142|-|-|<span class="en">used constituent (was used in) </span>`P142_a_mobilisé_comme_élément (a_été_mobilisé_dans)`||||<span class="en">E15 Identifier Assignment </span>`E15_Attribution_d’identifiant`|<span class="en">E90 Symbolic Object </span>`E90_Objet_symbolique`|
|P25|-|<span class="en">moved (moved by) </span>`P25_a_déplacé (a_été_déplacé_par)`|||||<span class="en">E9 Move </span>`E9_Déplacement`|<span class="en">E19 Physical Object </span>`E19_Objet_matériel`|
|P31|-|<span class="en">has modified (was modified by) </span>`P31_a_modifié (a_été_modifié_par)`|||||<span class="en">E11 Modification </span>`E11_Modification`|<span class="en">E18 Physical Thing </span>`E18_Chose_matérielle`|
|P108|-|-|<span class="en">has produced (was produced by) </span>`P108_a_produit (a_été_produit_par)`||||<span class="en">E12 Production </span>`E12_Production`|<span class="en">E24 Physical Human-Made Thing </span>`E24_Chose_matérielle_élaborée_par_l’humain`|
|P110|-|-|<span class="en">augmented (was augmented by) </span>`P110_a_augmenté (a_été_augmenté_par)`||||<span class="en">E79 Part Addition </span>`E79_Ajout_d’élément`|<span class="en">E24 Physical Human-Made Thing </span>`E24_Chose_matérielle_élaborée_par_l’humain`|
|P112|-|-|<span class="en">diminished (was diminished by) </span>`P112_a_diminué (a_été_diminué_par)`||||<span class="en">P80 Part Removal </span>`E80_Retrait_d’élément`|<span class="en">E24 Physical Human-Made Thing </span>`E24_Chose_matérielle_élaborée_par_l’humain`|
|P92|-|<span class="en">brought into existence (was brought into existence by) </span>`P92_a_fait_exister (a_commencé_à_exister_par)`|||||<span class="en">E63 Beginning of Existence </span>`E63_Début_d’existence`|<span class="en">E77 Persistent Item </span>`E77_Entité_persistante`|
|P94|-|-|<span class="en">has created (was creates by) </span>`P94_a_créé (a_été_créé_par)`||||<span class="en">E65 Creation </span>`E65_Création`|<span class="en">E28 Conceptual Object </span>`E28_Objet_conceptuel`|
|P135|-|-|-|<span class="en">created type (was created by) </span>`P135_a_créé_le_type (a_été_créé_par)`|||<span class="en">E83 Type Creation </span>`E83_Création_de_type`|<span class="en">E55 Type </span>`E55_Type`|
|P95|-|-|<span class="en">has formed (was formed by) </span>`P95_a_fondé (a_été_fondé_par)`||||<span class="en">E66 Formation </span>`E66_Formation`|<span class="en">E74 Group </span>`E74_Groupe`|
|P98|-|-|<span class="en">brought into life (was born) </span>`P98_a_donné_vie_à (a_été_dissous_par)`||||<span class="en">E67 Birth </span>`E67_Naissance`|<span class="en">E21 Person </span>`E21_Personne`|
|P108|-|-|<span class="en">has produced (was produced by) </span>`P108_a_produit (a_été_produit_par)`||||<span class="en">E12 Production </span>`E12_Production`|<span class="en">E24 Physical Human-Made Thing </span>`E24_Chose_matérielle_élaborée_par_l’humain`|
|P123|-|-|<span class="en">resulted in (resutled from) </span>`P123_a_eu_pour_résultat (a_résulté_de)`||||<span class="en">E81 Transformation </span>`E81_Transformation`|<span class="en">E77 Persistent Item </span>`E77_Entité_persistante`|
|P93|-|<span class="en">took out of existence (was taken out of existence by) </span>`P93_a_mis_fin_à_l’existence_de (a_cessé_d’exister_par)`|||||<span class="en">E64 End of Existence </span>`E64_Fin_d’existence`|<span class="en">E77 Persistent Item </span>`E77_Entité_persistante`|
|P13|-|-|<span class="en">destroyed (was destroyed by) </span>`P13_a_détruit (a_été_détruit_par)`||||<span class="en">E6 Destruction </span>`E6_Destruction`|<span class="en">E18 Physical Thing </span>`E18_Chose_matérielle`|
|P99|-|-|<span class="en">dissolved (was dissolved by) </span>`P99_a_dissous (a_été_dissous_par)`||||<span class="en">E68 Dissolution </span>`E68_Dissolution`|<span class="en">E74 Group </span>`E74_Groupe`|
|P100|-|-|<span class="en">was death of (died in) </span>`P100_a_été_la_mort_de (est_mort_par)`||||<span class="en">E69 Death </span>`E69_Mort`|<span class="en">E21 Person </span>`E21_Personne`|
|P124|-|-|<span class="en">transformed (was transformed by) </span>`P124_a_transformé (a_été_transformé_par)`||||<span class="en">E81 Transformation </span>`E81_Transformation`|<span class="en">E77 Persistent Item </span>`E77_Entité_persistante`|
|P15|<span class="en">was influenced by (influenced) </span>`P15_a_été_influencé_par (a_influencé)`||||||<span class="en">E7 Activity </span>`E7_Activité`|<span class="en">E1 CRM Entity </span>`E1_Entité_CRM`|
|P16|-|<span class="en">used specific object (was used for) </span>`P16_a_mobilisé_l’objet_spécifique (a_été_mobilisé_pour)`|||||<span class="en">E7 Activity </span>`E7_Activité`|<span class="en">E70 Thing </span>`E70_Chose`|
|P33|-|-|<span class="en">used specific technique (was used by) </span>`P33_a_mobilisé_comme_technique_spécifique (a_été_une_technique_spécifique_mise_en_œuvre_dans)`||||<span class="en">E11 Modification </span>`E11_Modification`|<span class="en">E29 Design or Procedure </span>`E29_Conceptualisation_ou_procédure`|
|P111|-|-|<span class="en">added (was added by) </span>`P111_a_ajouté (a_été_ajouté_par)`||||<span class="en">E79 Part Addition </span>`E79_Ajout_d’élément`|<span class="en">E18 Physical Thing </span>`E18_Chose_matérielle`|
|P142|-|-|<span class="en">used constituent (was used in) </span>`P142_a_mobilisé_comme_élément (a_été_mobilisé_dans)`||||<span class="en">E15 Identifier Assignment </span>`E15_Attribution_d’identifiant`|<span class="en">E90 Symbolic Object </span>`E90_Objet_symbolique`|
|P17|-|<span class="en">was motivated by (motivated) </span>`P17_a_été_motivé_par (a_motivé)`|||||<span class="en">E7 Activity </span>`E7_Activité`|<span class="en">E1 CRM Entity </span>`E1_Entité_CRM`|
|P134|-|<span class="en">continued (was continued by) </span>`P134_a_continué (a_été_continué_par)`|||||<span class="en">E7 Activity </span>`E7_Activité`|<span class="en">E7 Activity </span>`E7_Activité`|
|P136|-|<span class="en">was based on (supported type creation) </span>`P136_a_été_fondé_sur (a_fondé_la_création_du_type)`|||||<span class="en">E83 Type Creation </span>`E83_Création_de_type`|<span class="en">E1 CRM Entity </span>`E1_Entité_CRM`|
|P19|<span class="en">was intended use of (was made for) </span>`P19_a_été_l’usage_prévu_de (a_été_élaboré_pour)`||||||<span class="en">E7 Activity </span>`E7_Activité`|<span class="en">E71 Human-Made Thing </span>`E71_Chose_élaborée_par_l’humain`|
|P20|<span class="en">has specific purpose (was purpose of) </span>`P20_a_eu_pour_finalité_spécifique (a_été_finalité_de)`||||||<span class="en">E7 Activity </span>`E7_Activité`|<span class="en">E5 Event </span>`E5_Évènement`|
|P21|<span class="en">had general purpose (was purpose of) </span>`P21_a_eu_pour_finalité_générale (a_été_finalité_de)`||||||<span class="en">E7 Activity </span>`E7_Activité`|<span class="en">E55 Type </span>`E55_Type`|
|P24|<span class="en">transferred title of (changed ownership through) </span>`P24_a_transféré_le_titre_de_propriété_du (a_changé_de_propriétaire_par)`||||||<span class="en">E8 Acquisition </span>`E8_Acquisition`|<span class="en">E18 Physical Thing </span>`E18_Chose_matérielle`|
|P26|<span class="en">moved to (was destination of) </span>`P26_a_déplacé_à (a_été_la_destination_de)`||||||<span class="en">E9 Move </span>`E9_Déplacement`|<span class="en">E53 Place </span>`E53_Lieu`|
|P27|<span class="en">moved from (was origin of) </span>`P27_a_déplacé_depuis (a_été_le_point_de_départ_de)`||||||<span class="en">E9 Move </span>`E9_Déplacement`|<span class="en">E53 Place </span>`E53_Lieu`|
|P30|<span class="en">transferred custody of (custody transferred through) </span>`P30_a_transféré_la_garde_de (a_été_l’objet_d’un_transfert_de_garde_par)`||||||<span class="en">E10 Transfer of Custody </span>`E10_Transfert_de_la_garde`|<span class="en">E18 Physical Thing </span>`E18_Chose_matérielle`|
|P43|<span class="en">has dimension (is dimension of) </span>`P43_a_pour_dimension (est_dimension_de)`||||||<span class="en">E70 Thing </span>`E70_Chose`|<span class="en">E54 Dimension </span>`E54_Dimension`|
|P44|<span class="en">has condition (is condition of) </span>`P44_a_pour_état_matériel (est_état_matériel_de)`||||||<span class="en">E18 Physical Thing </span>`E18_Chose_matérielle`|<span class="en">E3 Condition State </span>`E3_État_matériel`|
|P45|<span class="en">consists of (is incorporated in) </span>`P45_consiste_en (inclut)`||||||<span class="en">E18 Physical Thing </span>`E18_Chose_matérielle`|<span class="en">E57 Material </span>`E57_Matériau`|
|P49|<span class="en">has former or current keeper (is former or current keeper of) </span>`P49_a_pour_actant_détenteur_actuel_ou_antérieur (est_actant_détenteur_actuel_ou_antérieur_de)`||||||<span class="en">E18 Physical Thing </span>`E18_Chose_matérielle`|<span class="en">E39 Actor </span>`E39_Actant`|
|P50|-|<span class="en">has current keeper (is current keeper of) </span>`P50_a_pour_actant_détenteur_actuel (est_actant_détenteur_actuel_de)`|||||<span class="en">E18 Physical Thing </span>`E18_Chose_matérielle`|<span class="en">E39 Actor </span>`E39_Actant`|
|P109|-|<span class="en">has current or former curator (is current or former curator of) </span>`P109_a_pour_actant_en_charge_de_la_collection_actuellement_ou_antérieurement (est_actuellement_ou_antérieurement_en_charge_de_la_collection_de)`|||||<span class="en">E78 Curated Holding </span>`E78_Collection`|<span class="en">E39 Actor </span>`E39_Actant`|
|P51|<span class="en">has former or current owner (is former or current owner of) </span>`P51_a_pour_propriétaire_actuel_ou_antérieur (est_propriétaire_actuel_ou_antérieur_de)`||||||<span class="en">E18 Physical Thing </span>`E18_Chose_matérielle`|<span class="en">E39 Actor </span>`E39_Actant`|
|P52|-|<span class="en">has current owner (is current owner of) </span>`P52_a_pour_propriétaire_actuel (est_propriétaire_actuel_de)`|||||<span class="en">E18 Physical Thing </span>`E18_Chose_matérielle`|<span class="en">E39 Actor </span>`E39_Actant`|
|P53|<span class="en">has former or current location (is former or current location of) </span>`P53_a_pour_localisation_actuelle_ou_antérieure (est_localisation_actuelle_ou_antérieure_de)`||||||<span class="en">E18 Physical Thing </span>`E18_Chose_matérielle`|<span class="en">E53 Place </span>`E53_Lieu`|
|P55|-|<span class="en">has current location (currently holds) </span>`P55_a_actuellement_pour_localisation (est_actuellement_localisation_de)`|||||<span class="en">E19 Physical Object </span>`E19_Objet_matériel`|<span class="en">E53 Place </span>`E53_Lieu`|
|P156|-|<span class="en">occupies (is occupied by) </span>`P156_occupe (est_occupé_par)`|||||<span class="en">E18 Physical Thing </span>`E18_Chose_matérielle`|<span class="en">E53 Place </span>`E53_Lieu`|
|P54|<span class="en">has current permanent location (is current permanent location of) </span>`P54_a_actuellement_pour_localisation_fixe (est_actuellement_localisation_fixe_de)`||||||<span class="en">E19 Physical Object </span>`E19_Objet_matériel`|<span class="en">E53 Place </span>`E53_Lieu`|
|P57|<span class="en">has number of parts </span>`P57_a_pour_nombre_d’éléments`||||||<span class="en">E19 Physical Object </span>`E19_Objet_matériel`|<span class="en">E60 Number </span>`E60_Nombre`|
|P59|<span class="en">has section (is located on or within) </span>`P59_a_pour_section (se_situe_sur_ou_dans)`||||||<span class="en">E18 Physical Thing </span>`E18_Chose_matérielle`|<span class="en">E53 Place </span>`E53_Lieu`|
|P62|<span class="en">depicts (is depicted by) </span>`P62_illustre (est_illustré_par)`||||||<span class="en">E24 Physical Human-Made Thing </span>`E24_Chose_matérielle_élaborée_par_l’humain`|<span class="en">E1 CRM Entity </span>`E1_Entité_CRM`|
|P67|<span class="en">refers to (is referred to by) </span>`P67_renvoie_à (fait_l’objet_d’un_renvoi_par)`||||||<span class="en">E89 Propositional Object </span>`E89_Objet_propositionnel`|<span class="en">E1 CRM Entity </span>`E1_Entité_CRM`|
|P68|-|<span class="en">foresees use of (use foreseen by) </span>`P68_prévoit_l’usage_de (usage_prévu_de)`|||||<span class="en">E29 Design or Procedure </span>`E29_Conceptualisation_ou_procédure`|<span class="en">E57 Material </span>`E57_Matériau`|
|P70|-|<span class="en">documents (is documented in) </span>`P70_documente (est_documenté_dans)`|||||<span class="en">E31 Document </span>`E31_Document`|<span class="en">E1 CRM Entity </span>`E1_Entité_CRM`|
|P71|-|<span class="en">lists (is listed in) </span>`P71_énumère (est_énuméré_par)`|||||<span class="en">E32 Authority Document </span>`E32_Document_de_référence`|<span class="en">E1 CRM Entity </span>`E1_Entité_CRM`|
|P129|-|<span class="en">is about (is subject of) </span>`P129_a_pour_sujet (est_sujet_de)`|||||<span class="en">E89 Propositional Object </span>`E89_Objet_propositionnel`|<span class="en">E1 CRM Entity </span>`E1_Entité_CRM`|
|P138|-|<span class="en">represents (has representation) </span>`P138_représente (est_représenté_par)`|||||<span class="en">E36 Visual Item </span>`E36_Entité_visuelle`|<span class="en">E1 CRM Entity </span>`E1_Entité_CRM`|
|P69|<span class="en">has association with (is associated with) </span>`P69_est_associé_à`||||||<span class="en">E29 Design or Procedure </span>`E29_Conceptualisation_ou_procédure`|<span class="en">E29 Design or Procedure </span>`E29_Conceptualisation_ou_procédure`|
|P72|<span class="en">has language (is language of) </span>`P72_a_pour_langue (est_la_langue_de)`||||||<span class="en">E33 Linguistic Object </span>`E33_Objet_linguistique`|<span class="en">E56 Language </span>`E56_Langue`|
|P74|<span class="en">has current or former residence (is current or former residence of) </span>`P74_a_pour_résidence_actuelle_ou_antérieure (est_résidence_actuelle_ou_antérieure_de)`||||||<span class="en">E39 Actor </span>`E39_Actant`|<span class="en">E53 Place </span>`E53_Lieu`|
|P75|<span class="en">possesses (is possessed by) </span>`P75_possède (est_possédé_par)`||||||<span class="en">E39 Actor </span>`E39_Actant`|<span class="en">E30 Right </span>`E30_Droit`|
|P76|<span class="en">has contact point (provides access to) </span>`P76_a_pour_coordonnées (permet_de_contacter)`||||||<span class="en">E39 Actor </span>`E39_Actant`|<span class="en">E41 Appellation </span>`E41_Appellation`|
|P81|<span class="en">ongoing throughout </span>`P81_a_couvert`||||||<span class="en">E52 Time-Span </span>`E52_Intervalle_temporel `|<span class="en">E61 Time Primitive </span>`E61_Primitive_temporelle`|
|P82|<span class="en">at some time within </span>`P82_a_eu_lieu_durant`||||||<span class="en">E52 Time-Span </span>`E52_Intervalle_temporel `|<span class="en">E61 Time Primitive </span>`E61_Primitive_temporelle`|
|P86|<span class="en">falls within (contains) </span>`P86_s’insère_dans (inclut)`||||||<span class="en">E52 Time-Span </span>`E52_Intervalle_temporel `|<span class="en">E52 Time-Span </span>`E52_Intervalle_temporel `|
|P89|<span class="en">falls within (contains) </span>`P89_s’insère_dans (inclut)`||||||<span class="en">E53 Place </span>`E53_Lieu`|<span class="en">E53 Place </span>`E53_Lieu`|
|P90|<span class="en">has value </span>`P90_a_pour_valeur`||||||<span class="en">E54 Dimension </span>`E54_Dimension`|<span class="en">E60 Number </span>`E60_Nombre`|
|P91|<span class="en">has unit (is unit of) </span>`P91_a_pour_unité_de_mesure (est_l’unité_de_mesure_de)`||||||<span class="en">E54 Dimension </span>`E54_Dimension`|<span class="en">E58 Measurement Unit </span>`E58_Unité_de_mesure`|
|P180|-|<span class="en">has currency </span>`P180_a_pour_monnaie (était_la_monnaie_de)`|||||<span class="en">E97 Monetary Amount </span>`E97_Valeur_monétaire`|<span class="en">E98 Currency </span>`E98_Monnaie`|
|P97|<span class="en">from father (was father for) </span>`P97_de_père (a_été_père_pour)`||||||<span class="en">E67 Birth </span>`E67_Naissance`|<span class="en">E21 Person </span>`E21_Personne`|
|P101|<span class="en">had as general use (was use of) </span>`P101_a_eu_pour_usage_général (a_été_l’usage_général_de)`||||||<span class="en">E70 Thing </span>`E70_Chose`|<span class="en">E55 Type </span>`E55_Type`|
|P103|<span class="en">was intended for (was intention of) </span>`P103_a_eu_pour_raison_d’être (a_été_raison_d’être_de)`||||||<span class="en">E71 Human-Made Thing </span>`E71_Chose_élaborée_par_l’humain`|<span class="en">E55 Type </span>`E55_Type`|
|P104|<span class="en">is subject to (applies to) </span>`P104_est_soumis_à (s’applique_à)`||||||<span class="en">E72 Legal Object </span>`E72_Objet_juridique`|<span class="en">E30 Right </span>`E30_Droit`|
|P105|<span class="en">right held by (has right on) </span>`P105_droit_détenu_par (détient_un_droit_sur)`||||||<span class="en">E72 Legal Object </span>`E72_Objet_juridique`|<span class="en">E39 Actor </span>`E39_Actant`|
|P52|-|<span class="en">has current owner (is current owner of) </span>`P52_a_pour_propriétaire_actuel (est_propriétaire_actuel_de)`|||||<span class="en">E18 Physical Thing </span>`E18_Chose_matérielle`|<span class="en">E39 Actor </span>`E39_Actant`|
|P106|<span class="en">is composed of (forms part of) </span>`P106_est_composé_de (fait_partie_de)`||||||<span class="en">E90 Symbolic Object </span>`E90_Objet_symbolique`|<span class="en">E90 Symbolic Object </span>`E90_Objet_symbolique`|
|P165|-|<span class="en">incorporates (is incorporated in) </span>`P165_inclut (est_inclus_dans)`|||||<span class="en">E73 Information Object </span>`E73_Objet_informationnel`|<span class="en">E90 Symbolic Object </span>`E90_Objet_symbolique`|
|P107|<span class="en">has current or former member (is current or former member of) </span>`P107_a_pour_membre_actuel_ou_antérieur (est_membre_actuel_ou_antérieur_de)`||||||<span class="en">E74 Group </span>`E74_Groupe`|<span class="en">E39 Actor </span>`E39_Actant`|
|P121|<span class="en">overlaps with </span>`P121_se_superpose_partiellement_à`||||||<span class="en">E53 Place </span>`E53_Lieu`|<span class="en">E53 Place </span>`E53_Lieu`|
|P122|<span class="en">borders with </span>`P122_est_limitrophe_de`||||||<span class="en">E53 Place </span>`E53_Lieu`|<span class="en">E53 Place </span>`E53_Lieu`|
|P125|<span class="en">used object of type (was type of object used in) </span>`P125_a_mobilisé_un_objet_du_type (a_été_le_type_d’objet_employé_pour)`||||||<span class="en">E7 Activity </span>`E7_Activité`|<span class="en">E55 Type </span>`E55_Type`|
|P32|-|<span class="en">used general technique (was technique of) </span>`P32_a_mobilisé_comme_technique_générale (a_été_une_technique_générale_mise_en_œuvre_dans)`|||||<span class="en">E7 Activity </span>`E7_Activité`|<span class="en">E55 Type </span>`E55_Type`|
|P126|<span class="en">employed (was employed in) </span>`P126_a_employé (a_été_employé_dans)`||||||<span class="en">E11 Modification </span>`E11_Modification`|<span class="en">E57 Material </span>`E57_Matériau`|
|P127|<span class="en">has broader term (has narrower term) </span>`P127_a_pour_terme_général (a_pour_terme_spécifique)`||||||<span class="en">E55 Type </span>`E55_Type`|<span class="en">E55 Type </span>`E55_Type`|
|P130|<span class="en">shows freatures of (features are also found on) </span>`P130_présente_des_caractéristiques de (a_des_caractéristiques_également_présentes_sur)`||||||<span class="en">E70 Thing </span>`E70_Chose`|<span class="en">E70 Thing </span>`E70_Chose`|
|P73i|-|<span class="en">is translation of </span>`P73i_est_traduction_de`|||||<span class="en">E33 Linguistic Object </span>`E33_Objet_linguistique`|<span class="en">E33 Linguistic Object </span>`E33_Objet_linguistique`|
|P128|-|<span class="en">carries (is carried by) </span>`P128_est_support_de (a_pour_support)`|||||<span class="en">E18 Physical Thing </span>`E18_Chose_matérielle`|<span class="en">E90 Symbolic Object </span>`E90_Objet_symbolique`|
|P65|-||<span class="en">shows visual item (is shown by) </span>`P65_représente_l’entité_visuelle (est_représenté_par)`||||<span class="en">E24 Physical Human-Made Thing </span>`E24_Chose_matérielle_élaborée_par_l’humain `|<span class="en">E36 Visual Item </span>`E36_Entité_visuelle`|
|P132|<span class="en">spatiotemporally ocerlaps with </span>`P132_se_superpose_spatio-temporellement_et_partiellement`||||||<span class="en">E92 Spacetime Volume </span>`E92_Volume_spatio-temporel`|<span class="en">E92 Spacetime Volume </span>`E92_Volume_spatio-temporel`|
|P10|-|<span class="en">falls within (contains) </span>`P10_s’insère_dans_le_cours_de (contient)`|||||<span class="en">E92 Spacetime Volume </span>`E92_Volume_spatio-temporel`|<span class="en">E92 Spacetime Volume </span>`E92_Volume_spatio-temporel`|
|P9i|-||<span class="en">forms part of </span>`P9i_fait_partie_de`||||<span class="en">E4 Period </span>`E4_Période`|<span class="en">E4 Period </span>`E4_Période`|
|P166|-||<span class="en">was a presence of (has presence) </span>`P166_a_été_une_présence_de (a_eu_pour_présence)`||||<span class="en">E93 Presence </span>`E93_Présence`|<span class="en">E92 Spacetime Volume </span>`E92_Volume_spatio-temporel`|
|P9|-|<span class="en">consists of (forns part of) </span>`P9_comprend (fait_partie_de)`|||||<span class="en">E4 Period </span>`E4_Période`|<span class="en">E4 Period </span>`E4_Période`|
|P46|<span class="en">is composed of (forms part of) </span>`P46_est_composé_de (fait_partie_de)`||||||<span class="en">E18 Physical Thing </span>`E18_Chose_matérielle`|<span class="en">E18 Physical Thing </span>`E18_Chose_matérielle`|
|P56|-|<span class="en">bears feature (is found on) </span>`P56_a_pour_caractéristique (se_trouve_sur)`|||||<span class="en">E19 Physical Object </span>`E19_Objet_matériel`|<span class="en">E26 Physical Feature </span>`E26_Caractéristique_physique`|
|P133|<span class="en">is separated from </span>`P133_est_distinct_spatio-temporellement_de`||||||<span class="en">E92 Spacetime Volume </span>`E92_Volume_spatio-temporel`|<span class="en">E92 Spacetime Volume </span>`E92_Volume_spatio-temporel`|
|P139|<span class="en">has alternative form </span>`P139_a_pour_forme_alternative`||||||<span class="en">E41 Appellation </span>`E41_Appellation`|<span class="en">E41 Appellation </span>`E41_Appellation`|
|P140|<span class="en">assigned attribute to (was attributed by) </span>`P140_a_attribué_à (a_été_attribué_par)`||||||<span class="en">E13 Attribute Assignment </span>`E13_Attribution`|<span class="en">E1 CRM Entity </span>`E1_Entité_CRM`|
|P34||<span class="en">concerned (was assessed by) </span>`P34_a_porté_sur (a_été_évalué_lors_de)`|||||<span class="en">E14 Condition Assessment </span>`E14_Évaluation_d’état_matériel`|<span class="en">E18 Physical Thing </span>`E18_Chose_matérielle`|
|P39||<span class="en">measured (was measured by) </span>`P39_a_mesuré (a_été_mesuré_lors_de)`|||||<span class="en">E16 Measurement </span>`E16_Mesurage`|<span class="en">E1 CRM Entity </span>`E1_Entité_CRM`|
|P41||<span class="en">classified (was classified by) </span>`P41_a_classifié (a_été_classifié_lors_de)`|||||<span class="en">E17 Type Assignment </span>`E17_Attribution_de_type`|<span class="en">E1 CRM Entity </span>`E1_Entité_CRM`|
|P141|<span class="en">assigned (was assigned by) </span>`P141_a_attribué (a_été_attribué_par)`||||||<span class="en">E13 Attribute Assignment </span>`E13_Attribution`|<span class="en">E1 CRM Entity </span>`E1_Entité_CRM`|
|P35|-|<span class="en">has identified (identified by) </span>`P35_a_identifié (a_été_identifié_lors_de)`|||||<span class="en">E14 Condition Assessment </span>`E14_Évaluation_d’état_matériel`|<span class="en">E3 Condition State </span>`E3_État_matériel`|
|P37|-|<span class="en">assigned (was assigned by) </span>`P37_a_attribué (a_été_attribué_lors_de)`|||||<span class="en">E15 Identifier Assignment </span>`E15_Attribution_d’identifiant`|<span class="en">E42 identifier </span>`E42_Identifiant`|
|P38|-|<span class="en">deassigned (was designed by) </span>`P38_a_retiré_l’attribution_de (a_été_retiré_lors_de)`|||||<span class="en">E15 Identifier Assignment </span>`E15_Attribution_d’identifiant`|<span class="en">E42 identifier </span>`E42_Identifiant`|
|P40|-|<span class="en">observed dimension (was observed in) </span>`P40_a_relevé_comme_dimension (a_été_relevé_lors_de)`|||||<span class="en">E16 Measurement </span>`E16_Mesurage`|<span class="en">E54 Dimension </span>`E54_Dimension`|
|P42|-|<span class="en">assigned (was assigned by) </span>`P42_a_attribué (a_été_attribué_lors_de)`|||||<span class="en">E17 Type Assignment </span>`E17_Attribution_de_type`|<span class="en">E55 Type </span>`E55_Type`|
|P147|<span class="en">curated (was curated by) </span>`P147_a_géré (a_été_géré_par)`||||||<span class="en">E87 Curation Activity </span>`E87_Activité_curatoriale`|<span class="en">E78 Curated Holding </span>`E78_Collection`|
|P148|<span class="en">has component (is component of) </span>`P148_a_pour_composant (est_composant_de)`||||||<span class="en">E89 Propositional Object </span>`E89_Objet_propositionnel`|<span class="en">E89 Propositional Object </span>`E89_Objet_propositionnel`|
|P150|<span class="en">defines typical parts of (defines typical wholes for) </span>`P150_définit_les_éléments_typiques_de (définit_l’ensemble_typique_pour)`||||||<span class="en">E55 Type </span>`E55_Type`|<span class="en">E55 Type </span>`E55_Type`|
|P152|<span class="en">has parent (is parent of) </span>`P152_a_pour_parent (est_parent_de)`||||||<span class="en">E21 Person </span>`E21_Personne`|<span class="en">E21 Person </span>`E21_Personne`|
|P157|<span class="en">is at rest relative to (provides reference space for) </span>`P157_est_à_l’arrêt_par_rapport_à (procure_un_espace_de_référence_pour)`||||||<span class="en">E53 Place </span>`E53_Lieu`|<span class="en">E18 Physical Thing </span>`E18_Chose_matérielle`|
|P59i|-|<span class="en">is located on or within </span>`P59i_se_situe_sur_ou_dans`|||||<span class="en">E53 Place </span>`E53_Lieu`|<span class="en">E18 Physical Thing </span>`E18_Chose_matérielle`|
|P156i|-|<span class="en">is occupied by </span>`P156i_est_occupé_par`|||||<span class="en">E53 Place </span>`E53_Lieu`|<span class="en">E18 Physical Thing </span>`E18_Chose_matérielle`|
|P160|<span class="en">has temporal projection </span>`P160_a_pour_projection_temporelle (est_la_projection_temporelle_de)`||||||<span class="en">E92 Spacetime Volume </span>`E92_Volume_spatio-temporel`|<span class="en">E52 Time-Span </span>`E52_Intervalle_temporel `|
|P164|-|<span class="en">is temporally specified by (temporally specifies) </span>`P164_durant (était_l’intervalle_temporel_de)`|||||<span class="en">E93 Presence </span>`E93_Présence`|<span class="en">E52 Time-Span </span>`E52_Intervalle_temporel `|
|P161|<span class="en">has spatial projection </span>`P161_a_pour_projection_spatiale (est_la_projection_spatiale_de)`||||||<span class="en">E92 Spacetime Volume </span>`E92_Volume_spatio-temporel`|<span class="en">E53 Place </span>`E53_Lieu`|
|P167|<span class="en">was within (includes) </span>`P167_à (a_été_le_lieu_de)`||||||<span class="en">E93 Presence </span>`E93_Présence`|<span class="en">E53 Place </span>`E53_Lieu`|
|P171|<span class="en">at some place within </span>`P171_a_eu_lieu_quelque_part_dans`||||||<span class="en">E53 Place </span>`E53_Lieu`|<span class="en">E94 Space Primitive </span>`E94_Primitive_spatiale`|
|P172|<span class="en">contains </span>`P172_contient`||||||<span class="en">E53 Place </span>`E53_Lieu`|<span class="en">E94 Space Primitive </span>`E94_Primitive_spatiale`|
|P173|<span class="en">starts before or with the end of (ends after the start of) </span>`P173_commence_avant_ou_au_moment_de_la_fin_de (se_termine_après_ou_au_moment_du_début_de)`||||||<span class="en">E2 Temporal Entity </span>`E2_Entité_temporelle`|<span class="en">E2 Temporal Entity </span>`E2_Entité_temporelle`|
|P174|-|<span class="en">starts before the end of (ends after the start of) </span>`P174_commence_avant_la_fin_de (se_termine_après_le_début_de)`|||||<span class="en">E2 Temporal Entity </span>`E2_Entité_temporelle`|<span class="en">E2 Temporal Entity </span>`E2_Entité_temporelle`|
|P134|-|-|<span class="en">continued (was continued by) </span>`P134_a_continué (a_été_continué_par)`||||<span class="en">E7 Activity </span>`E7_Activité`|<span class="en">E7 Activity </span>`E7_Activité`|
|P184|-|-|<span class="en">ends before or with the end of (ends with or after the end of) </span>`P184_se_termine_avant_ou_au_moment_de_la_fin_de (se_termine_au_moment_ou_après_la_fin_de)`||||<span class="en">E2 Temporal Entity </span>`E2_Entité_temporelle`|<span class="en">E2 Temporal Entity </span>`E2_Entité_temporelle`|
|P185|-|-|-|<span class="en">ends before the end of (ends after the end of) </span>`P185_se_termine_avant_la_fin_de (se_termine_après_la_fin_de) `|||<span class="en">E2 Temporal Entity </span>`E2_Entité_temporelle`|<span class="en">E2 Temporal Entity </span>`E2_Entité_temporelle`|
|P182|-|-|-|-|<span class="en">ends before or at the start of (starts after or with the start of) </span>`P182_se_termine_avant_ou_au_moment_du_début_de (commence_après_ou_au_moment_de_la_fin_de)`||<span class="en">E2 Temporal Entity </span>`E2_Entité_temporelle`|<span class="en">E2 Temporal Entity </span>`E2_Entité_temporelle`|
|P175|-|-|<span class="en">starts before or with the start of (starts after or with the start of) </span>`P175_commence_avant_ou_au_moment_du_début_de (commence_après_ou_au_moment_du_début_de)`||||<span class="en">E2 Temporal Entity </span>`E2_Entité_temporelle`|<span class="en">E2 Temporal Entity </span>`E2_Entité_temporelle`|
|P176|-|-|-|<span class="en">starts before the start of (starts after the start of) </span>`P176_commence_avant_le_début_de (commence_après_le_début_de)`|||<span class="en">E2 Temporal Entity </span>`E2_Entité_temporelle`|<span class="en">E2 Temporal Entity </span>`E2_Entité_temporelle`|
|P182|-|-|-|-|<span class="en">ends before or at the start of (starts after or with the end of) </span>`P182_se_termine_avant_ou_au_moment_du_début_de (commence_après_ou_au_moment_de_la_fin_de)`||<span class="en">E2 Temporal Entity </span>`E2_Entité_temporelle`|<span class="en">E2 Temporal Entity </span>`E2_Entité_temporelle`|
|P183|-|-|-|-|-|<span class="en">ends before the start of (starts after the end of) </span>`P183_se_termine_avant_le_début_de (commence_après_la_fin_de)`|<span class="en">E2 Temporal Entity </span>`E2_Entité_temporelle`|<span class="en">E2 Temporal Entity </span>`E2_Entité_temporelle`|
|P179|<span class="en">had sales price (was sales price of) </span>`P179_a_eu_pour_prix_de_vente (a_été_le_prix_de_vente_de)`||||||<span class="en">E96 Purchase </span>`E96_Achat`|<span class="en">E97 Monetary Amount </span>`E97_Valeur_monétaire`|
|P186|<span class="en">produced thing of product type (is produced by) </span>`P186_a_produit_une_chose_du_type (est_produit_par)`||||||<span class="en">E12 Production </span>`E12_Production`|<span class="en">E99 Product Type </span>`E99_Modèle_de_produit`|
|P187|<span class="en">has production plan (is production plan for) </span> `P187_a_pour_plan_de_production (est_le_plan_de_production_de)`||||||<span class="en">E99 Product Type </span>`E99_Modèle_de_produit`|<span class="en">E29 Deisgn or Procedure </span>`E29_Conceptualisation_ou_procédure`|
|P188|<span class="en">requires production tool (is production tool for) </span> `P188_nécessite_l’outil (est_l’outil_de_production_de) `||||||<span class="en">E99 Product Type </span>`E99_Modèle_de_produit`|<span class="en">E19 Physical Object </span>`E19_Objet_matériel`|
|P189|<span class="en">approximates </span>`P189_approxime (est_approximé_par)`||||||<span class="en">E53 Place </span>`E53_Lieu`|<span class="en">E53 Place </span>`E53_Lieu`|
|P191|<span class="en">had duration (was duration of) </span>`P191_a_eu_pour_durée (était_la_durée_de)`||||||<span class="en">E52 Time-Span </span>`E52_Intervalle_temporel `|<span class="en">E54 Dimension </span>`E54_Dimension`|
|P195|<span class="en">was a presence of (has presence) </span>`P195_a_été_une_présence_de (a_eu_pour_présence) `||||||<span class="en">E93 Presence </span>`E93_Présence`|<span class="en">E18 Physical Thing </span>`E18_Chose_matérielle`|
|P196|<span class="en">defines (is defined by) </span>`P196_définit (est_défini_par)`||||||<span class="en">E18 Physical Thing </span>`E18_Chose_matérielle`|<span class="en">E92 Spacetime Volume </span>`E92_Volume_spatio-temporel`|
|P197|<span class="en">covered parts of (was partially covered by) </span>`197_a_couvert_des_parties_de (a_été_partiellement_couvert_par)`||||||<span class="en">E93 Presence </span>`E93_Présence`|<span class="en">E53 Place </span>`E53_Lieu`|
|P198|<span class="en">holds or supports (is held or supported by) </span>`P198_contient_ou_soutient (est_contenu_ou_soutenu_par)`||||||<span class="en">E18 Physical Thing </span>`E18_Chose_matérielle`|<span class="en">E18 Physical Thing </span>`E18_Chose_matérielle`|

