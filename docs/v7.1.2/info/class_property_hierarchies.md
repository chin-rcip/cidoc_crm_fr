---
layout: page
title: Hiérarchies de classes et de propriétés
titleEn: Class & Property Hierarchies - Hiérarchies de classes et de propriétés
permalink: /v7.1.2/information/hierarchies-de-classes-et-de-proprietes
sidebar: v712
group: information
date: 2023-11-08
---

**Date de création** : 2023-11-08

**Dernière mise à jour** : 2023-11-08

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
<p>Although they do not provide comprehensive definitions, compact mono-hierarchical presentations of the class and property IsA hierarchies have been found to significantly aid comprehension and navigation of the CIDOC CRM. Since the CRM is poly-hierarchical, a mono-hierarchical presentation form is achieved by a top-down expansion of all inverse IsA relations regardless whether a concept has already be presented at another place in the same hierarchy. This form is provided below.</p>
<p>The class hierarchy presented below has the following format:</p>
<ul><li><p>Each line begins with a unique class identifier, consisting of a number preceded by the letter “E” (originally denoting “entity,” although now replaced by convention with the term “class”).</p>
</li>
<li><p>A series of hyphens (“-”) follows the unique class identifier, indicating the hierarchical position of the class in the IsA hierarchy.</p>
</li>
<li><p>The English name of the class appears to the right of the hyphens.</p>
</li>
<li><p>The index is ordered by hierarchical level, in a “depth first” manner, from the smaller to the larger subhierarchies.</p>
</li>
<li><p>Classes that appear in more than one position in the class hierarchy as a result of multiple inheritance are shown in an italic typeface.</p>
</li></ul>
<p>The property hierarchy presented below has the following format:</p>
<ul><li><p>Each line begins with a unique property identifier, consisting of a number preceded by the letter “P” (for “property”).</p>
</li>
<li><p>A series of hyphens (“-”) follows the unique property identifier, indicating the hierarchical position of the property in the IsA hierarchy.</p>
</li>
<li><p>The English name of the property appears to the right of the hyphens, followed by its inverse name in parentheses for reading in the range to domain direction.</p>
</li>
<li><p>The domain class for which the property is declared.</p>
</li>
<li><p>The range class that the property references.</p>
</li>
<li><p>The index is ordered by hierarchical level, in a “depth first” manner, from the smaller to the larger subhierarchies, and by property number between equal siblings.</p>
</li>
<li><p>Properties that appear in more than one position in the property hierarchy as a result of multiple inheritance are shown in an italic typeface.</p>
</li></ul>
</td>
<td>
<p>Bien qu’elles n’étayent pas de définitions exhaustives, les présentations succinctes et mono-hiérarchiques des classes et des propriétés contribuent à la navigation dans le CIDOC CRM et à la compréhension de celui-ci. Puisque le CIDOC CRM est poly-hiérarchique, la présentation mono-hiérarchique formelle découle d’une expansion descendante de toutes les relations <code class="language-plaintext highlighter-rouge">estUn</code> indépendamment de la présence d’un concept ailleurs dans ladite hiérarchie. </p>
<p>La hiérarchie de classes présentée ci-bas reprend la forme suivante : </p>
<ul><li><p>Chaque ligne commence avec un identifiant de classe unique composé d’un nombre précédé de la lettre « E » (qui signalait autrefois une « entité », bien que le terme « classe » soit maintenant préféré). </p>
</li>
<li><p>Une série de traits d’union (« - ») suit cet identifiant de classe unique et indique la position de la classe dans la hiérarchie <code class="language-plaintext highlighter-rouge">estUn</code>. </p>
</li>
<li><p>Le nom de la classe se trouve à droite des traits d’union. </p>
</li>
<li><p>L’index est ordonné selon les niveaux hiérarchiques avec une approche de « parcours en profondeur » depuis les sous-hiérarchies les plus petites vers les plus larges. </p>
</li>
<li><p>L’apparition de classes dans de multiples positions dans la hiérarchie des classes en raison d’héritages multiples est signalée par l’usage des italiques. </p>
</li></ul>
<p>La hiérarchie des propriétés présentée ci-bas reprend la forme suivante : </p>
<ul><li><p>Chaque ligne commence avec un identifiant de propriété unique composé d’un nombre précédé de la lettre « P » (pour « propriété »). </p>
</li>
<li><p>Une série de traits d’union (« - ») suit cet identifiant de propriété unique et indique la position de la propriété dans la hiérarchie <code class="language-plaintext highlighter-rouge">estUn</code>. </p>
</li>
<li><p>Le nom de la propriété se trouve à droite des traits d’union, suivi par le nom de la propriété inverse entre parenthèses (aux fins de lecture depuis la portée vers le domaine). </p>
</li>
<li><p>L’index est ordonné selon les niveaux hiérarchiques avec une approche de « parcours en profondeur » depuis les sous-hiérarchies les plus petites vers les plus larges, puis par numéro de propriété dans le cas de propriétés-soeurs égales. </p>
</li>
<li><p>L’apparition de propriétés dans de multiples positions dans la hiérarchie des propriétés en raison d’héritages multiples est signalée par l’usage des italiques. </p>
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
<p><em></em></p>
</td>
</tr>
</tbody>
</table>

<h2 id="liste-hierarchisee-des-classes-du-cidoc-crm"><span class="en heading">CIDOC CRM Class Hierarchy - </span>Liste hiérarchisée des classes du CIDOC CRM</h2>

<table id="cidoc-crm-class-hierarchy-table">
  <tbody>
    <tr>
      <td colspan="11"><strong><span class="en">Class id - </span>Identifiant unique de classe</strong></td>
      </tr>
    <tr>
      <td>E1</td>
      <td colspan="10"><span class="en">CRM Entity </span><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></td>
      </tr>
    <tr>
      <td>E2</td>
      <td>-</td>
      <td colspan="9"><span class="en">Temporal Entity </span><code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code></td>
      </tr>
    <tr>
      <td>E3</td>
      <td>-</td>
      <td>-</td>
      <td colspan="8"><span class="en">Condition State </span><code class="language-plaintext highlighter-rouge">E3_État_matériel</code></td>
      </tr>
    <tr>
      <td>E4</td>
      <td>-</td>
      <td>-</td>
      <td colspan="8"><span class="en">Period </span><code class="language-plaintext highlighter-rouge">E4_Période</code></td>
      </tr>
    <tr>
      <td>E5</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="7"><span class="en">Event </span><code class="language-plaintext highlighter-rouge">E5_Évènement</code></td>
      </tr>
    <tr>
      <td>E7</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="6"><span class="en">Activity </span><code class="language-plaintext highlighter-rouge">E7_Activité</code></td>
      </tr>
    <tr>
      <td>E8</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en">Acquisition </span><code class="language-plaintext highlighter-rouge">E8_Acquisition</code></td>
      </tr>
    <tr>
      <td>E96</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">Purchase </span><code class="language-plaintext highlighter-rouge">E96_Achat</code></td>
      </tr>
    <tr>
      <td>E9</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en">Move </span><code class="language-plaintext highlighter-rouge">E9_Déplacement</code></td>
      </tr>
    <tr>
      <td>E10</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en">Transfer of Custody </span><code class="language-plaintext highlighter-rouge">E10_Transfert_de_la_garde</code></td>
      </tr>
    <tr>
      <td>E11</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en">Modification </span><code class="language-plaintext highlighter-rouge">E11_Modification</code></td>
      </tr>
    <tr>
      <td>E12</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">Production </span><code class="language-plaintext highlighter-rouge">E12_Production</code></td>
      </tr>
    <tr>
      <td>E79</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">Part Addition </span><code class="language-plaintext highlighter-rouge">E79_Ajout_d’élément</code></td>
      </tr>
    <tr>
      <td>E80</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">Part Removal </span><code class="language-plaintext highlighter-rouge">E80_Retrait_d’élément</code></td>
      </tr>
    <tr>
      <td>E13</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en">Attribute Assignment </span><code class="language-plaintext highlighter-rouge">E13_Assignation_d’attribut</code></td>
      </tr>
    <tr>
      <td>E14</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">Condition Assesment </span><code class="language-plaintext highlighter-rouge">E14_Évaluation_d’état_matériel</code></td>
      </tr>
    <tr>
      <td>E15</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">Identifier Assignment </span><code class="language-plaintext highlighter-rouge">E15_Assignation_d’identifiant</code></td>
      </tr>
    <tr>
      <td>E16</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">Measurement </span><code class="language-plaintext highlighter-rouge">E16_Mesurage</code></td>
      </tr>
    <tr>
      <td>E17</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">Type Assignment </span><code class="language-plaintext highlighter-rouge">E17_Assignation_de_type</code></td>
      </tr>
    <tr>
      <td>E65</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en">Creation </span><code class="language-plaintext highlighter-rouge">E65_Création</code></td>
      </tr>
    <tr>
      <td>E83</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">Type Creation </span><code class="language-plaintext highlighter-rouge">E83_Création_de_type</code></td>
      </tr>
    <tr>
      <td>E66</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en">Formation </span><code class="language-plaintext highlighter-rouge">E66_Formation</code></td>
      </tr>
    <tr>
      <td>E85</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en">Joining </span><code class="language-plaintext highlighter-rouge">E85_Adhésion</code></td>
      </tr>
    <tr>
      <td>E86</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en">Leaving </span><code class="language-plaintext highlighter-rouge">E86_Départ</code></td>
      </tr>
    <tr>
      <td>E87</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en">Curation Activity </span><code class="language-plaintext highlighter-rouge">E87_Activité_curatoriale</code></td>
      </tr>
    <tr>
      <td>E63</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="6"><span class="en">Beginning of Existence </span><code class="language-plaintext highlighter-rouge">E63_Début_d’existence</code></td>
      </tr>
    <tr>
      <td>E67</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en">Birth </span><code class="language-plaintext highlighter-rouge">E67_Naissance</code></td>
      </tr>
    <tr>
      <td>E81</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en">Transformation </span><code class="language-plaintext highlighter-rouge">E81_Transformation</code></td>
      </tr>
    <tr>
      <td>E12</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en"><em>Production </em></span><em><code class="language-plaintext highlighter-rouge">E12_Production</code></em></td>
      </tr>
    <tr>
      <td>E65</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en"><em>Creation </em></span><em><code class="language-plaintext highlighter-rouge">E65_Création</code></em></td>
      </tr>
    <tr>
      <td>E83</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en"><em>Type Creation </em></span><em><code class="language-plaintext highlighter-rouge">E83_Création_de_type</code></em></td>
      </tr>
    <tr>
      <td>E66</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en"><em>Formation </em></span><em><code class="language-plaintext highlighter-rouge">E66_Formation</code></em></td>
      </tr>
    <tr>
      <td>E64</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="6"><span class="en">End of Existence </span><code class="language-plaintext highlighter-rouge">E64_Fin_d’existence</code></td>
      </tr>
    <tr>
      <td>E6</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en">Destruction </span><code class="language-plaintext highlighter-rouge">E6_Destruction</code></td>
      </tr>
    <tr>
      <td>E68</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en">Dissolution </span><code class="language-plaintext highlighter-rouge">E68_Dissolution</code></td>
      </tr>
    <tr>
      <td>E69</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en">Death </span><code class="language-plaintext highlighter-rouge">E69_Mort</code></td>
      </tr>
    <tr>
      <td>E81</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en"><em>Transformation </em></span><em><code class="language-plaintext highlighter-rouge">E81_Transformation</code></em></td>
      </tr>
    <tr>
      <td>E77</td>
      <td>-</td>
      <td colspan="9"><span class="en">Persistent Item </span><code class="language-plaintext highlighter-rouge">E77_Entité_persistante</code></td>
      </tr>
    <tr>
      <td>E70</td>
      <td>-</td>
      <td>-</td>
      <td colspan="8"><span class="en">Thing </span><code class="language-plaintext highlighter-rouge">E70_Chose</code></td>
      </tr>
    <tr>
      <td>E72</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="7"><span class="en">Legal Object </span><code class="language-plaintext highlighter-rouge">E72_Objet_juridique</code></td>
      </tr>
    <tr>
      <td>E18</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="6"><span class="en">Physical Thing </span><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></td>
      </tr>
    <tr>
      <td>E19</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en">Physical Object </span><code class="language-plaintext highlighter-rouge">E19_Objet_matériel</code></td>
      </tr>
    <tr>
      <td>E20</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">Biological Object </span><code class="language-plaintext highlighter-rouge">E20_Objet_biologique</code></td>
      </tr>
    <tr>
      <td>E21</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="3"><span class="en">Person </span><code class="language-plaintext highlighter-rouge">E21_Personne</code></td>
      </tr>
    <tr>
      <td>E22</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">Human-Made Object </span><code class="language-plaintext highlighter-rouge">E22_Objet_élaboré_par_l’humain</code></td>
      </tr>
    <tr>
      <td>E24</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en">Physical Human-Made Thing </span><code class="language-plaintext highlighter-rouge">E24_Chose_matérielle_élaborée_par_l’humain</code></td>
      </tr>
    <tr>
      <td>E22</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en"><em>Human-Made Object  </em></span><em><code class="language-plaintext highlighter-rouge">E22_Objet_élaboré_par_l’humain</code></em></td>
      </tr>
    <tr>
      <td>E25</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">Human-Made Feature </span><code class="language-plaintext highlighter-rouge">E25_Caractéristique_élaborée_par_l’humain</code></td>
      </tr>
    <tr>
      <td>E78</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">Curated Holding </span><code class="language-plaintext highlighter-rouge">E78_Collection</code></td>
      </tr>
    <tr>
      <td>E26</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en">Physical Feature </span><code class="language-plaintext highlighter-rouge">E26_Caractéristique_physique</code></td>
      </tr>
    <tr>
      <td>E27</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">Site </span><code class="language-plaintext highlighter-rouge">E27_Site</code></td>
      </tr>
    <tr>
      <td>E25</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en"><em>Human-Made Feature  </em></span><em><code class="language-plaintext highlighter-rouge">E25_Caractéristique_élaborée_par_l’humain</code></em></td>
      </tr>
    <tr>
      <td>E90</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="6"><span class="en">Symbolic Object </span><code class="language-plaintext highlighter-rouge">E90_Objet_symbolique</code></td>
      </tr>
    <tr>
      <td>E73</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en">Information Object </span><code class="language-plaintext highlighter-rouge">E73_Objet_informationnel</code></td>
      </tr>
    <tr>
      <td>E29</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">Design or Procedure </span><code class="language-plaintext highlighter-rouge">E29_Conceptualisation_ou_procédure</code></td>
      </tr>
    <tr>
      <td>E31</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">Document </span><code class="language-plaintext highlighter-rouge">E31_Document</code></td>
      </tr>
    <tr>
      <td>E32</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="3"><span class="en">Authority Document </span><code class="language-plaintext highlighter-rouge">E32_Document_de_référence</code></td>
      </tr>
    <tr>
      <td>E33</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">Linguistic Object </span><code class="language-plaintext highlighter-rouge">E33_Objet_linguistique</code></td>
      </tr>
    <tr>
      <td>E34</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="3"><span class="en">Inscription </span><code class="language-plaintext highlighter-rouge">E34_Inscription</code></td>
      </tr>
    <tr>
      <td>E35</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="3"><span class="en">Title </span><code class="language-plaintext highlighter-rouge">E35_Titre</code></td>
      </tr>
    <tr>
      <td>E36</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">Visual Item </span><code class="language-plaintext highlighter-rouge">E36_Entité_visuelle</code></td>
      </tr>
    <tr>
      <td>E37</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="3"><span class="en">Mark </span><code class="language-plaintext highlighter-rouge">E37_Marque</code></td>
      </tr>
    <tr>
      <td>E34</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="2"><span class="en">Inscription </span><code class="language-plaintext highlighter-rouge">E34_Inscription</code></td>
      </tr>
    <tr>
      <td>E41</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en">Appellation </span><code class="language-plaintext highlighter-rouge">E41_Appellation</code></td>
      </tr>
    <tr>
      <td>E42</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">Identifier </span><code class="language-plaintext highlighter-rouge">E42_Identifiant</code></td>
      </tr>
    <tr>
      <td>E35</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">Title </span><code class="language-plaintext highlighter-rouge">E35_Titre</code></td>
      </tr>
    <tr>
      <td>E95</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">Spacetime Primitive </span><code class="language-plaintext highlighter-rouge">E95_Primitive_spatio-temporelle</code></td>
      </tr>
    <tr>
      <td>E94</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">Space Primitive </span><code class="language-plaintext highlighter-rouge">E94_Primitive_spatiale</code></td>
      </tr>
    <tr>
      <td>E61</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">Time Primitive </span><code class="language-plaintext highlighter-rouge">E61_Primitive_temporelle</code></td>
      </tr>
    <tr>
      <td>E71</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="7"><span class="en">Human-Made Thing </span><code class="language-plaintext highlighter-rouge">E71_Chose_élaborée_par_l’humain</code></td>
      </tr>
    <tr>
      <td>E24</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="6"><span class="en"><em>Physical Human-Made Thing  </em></span><em><code class="language-plaintext highlighter-rouge">E24_Chose_matérielle_élaborée_par_l’humain</code></em></td>
      </tr>
    <tr>
      <td>E22</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en"><em>Human-Made Object  </em></span><em><code class="language-plaintext highlighter-rouge">E22_Objet_élaboré_par_l’humain</code></em></td>
      </tr>
    <tr>
      <td>E25</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en"><em>Human-Made Feature  </em></span><em><code class="language-plaintext highlighter-rouge">E25_Caractéristique_élaborée_par_l’humain</code></em></td>
      </tr>
    <tr>
      <td>E78</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en"><em>Curated Holding  </em></span><em><code class="language-plaintext highlighter-rouge">E78_Collection</code></em></td>
      </tr>
    <tr>
      <td>E28</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="6"><span class="en">Conceptual Object </span><code class="language-plaintext highlighter-rouge">E28_Objet_conceptuel</code></td>
      </tr>
    <tr>
      <td>E90</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en"><em>Symbolique Object  </em></span><em><code class="language-plaintext highlighter-rouge">E90_Objet_symbolique</code></em></td>
      </tr>
    <tr>
      <td>E73</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en"><em>Information Object  </em></span><em><code class="language-plaintext highlighter-rouge">E73_Objet_informationnel</code></em></td>
      </tr>
    <tr>
      <td>E29</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="3"><span class="en"><em>Design or Procedure  </em></span><em><code class="language-plaintext highlighter-rouge">E29_Conceptualisation_ou_procédure</code></em></td>
      </tr>
    <tr>
      <td>E31</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="3"><span class="en"><em>Document  </em></span><em><code class="language-plaintext highlighter-rouge">E31_Document</code></em></td>
      </tr>
    <tr>
      <td>E32</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="2"><span class="en"><em>Authority Document  </em></span><em><code class="language-plaintext highlighter-rouge">E32_Document_de_référence</code></em></td>
      </tr>
    <tr>
      <td>E33</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="3"><span class="en"><em>Linguistic Object  </em></span><em><code class="language-plaintext highlighter-rouge">E33_Objet_linguistique</code></em></td>
      </tr>
    <tr>
      <td>E34</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="2"><span class="en"><em>Inscription  </em></span><em><code class="language-plaintext highlighter-rouge">E34_Inscription</code></em></td>
      </tr>
    <tr>
      <td>E35</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="2"><span class="en"><em>Title  </em></span><em><code class="language-plaintext highlighter-rouge">E35_Titre</code></em></td>
      </tr>
    <tr>
      <td>E36</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="3"><span class="en"><em>Visual Item  </em></span><em><code class="language-plaintext highlighter-rouge">E36_Entité_visuelle</code></em></td>
      </tr>
    <tr>
      <td>E37</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="2"><span class="en"><em>Mark  </em></span><em><code class="language-plaintext highlighter-rouge">E37_Marque</code></em></td>
      </tr>
    <tr>
      <td>E34</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="1"><span class="en"><em>Inscription  </em></span><em><code class="language-plaintext highlighter-rouge">E34_Inscription</code></em></td>
    </tr>
    <tr>
      <td>E41</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en"><em>Appellation  </em></span><em><code class="language-plaintext highlighter-rouge">E41_Appellation</code></em></td>
      </tr>
    <tr>
      <td>E42</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="3"><span class="en"><em>Identifier  </em></span><em><code class="language-plaintext highlighter-rouge">E42_Identifiant</code></em></td>
      </tr>
    <tr>
      <td>E35</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="3"><span class="en"><em>Title  </em></span><em><code class="language-plaintext highlighter-rouge">E35_Titre</code></em></td>
      </tr>
    <tr>
      <td>E95</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="3"><span class="en"><em>Spacetime Primitive  </em></span><em><code class="language-plaintext highlighter-rouge">E95_Primitive_spatio-temporelle</code></em></td>
      </tr>
    <tr>
      <td>E94</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="3"><span class="en"><em>Space Primitive  </em></span><em><code class="language-plaintext highlighter-rouge">E94_Primitive_spatiale</code></em></td>
      </tr>
    <tr>
      <td>E61</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="3"><span class="en"><em>Time Primitive  </em></span><em><code class="language-plaintext highlighter-rouge">E61_Primitive_temporelle</code></em></td>
      </tr>
    <tr>
      <td>E89</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en">Propositional Object </span><code class="language-plaintext highlighter-rouge">E89_Objet_propositionnel</code></td>
      </tr>
    <tr>
      <td>E73</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en"><em>Information Object  </em></span><em><code class="language-plaintext highlighter-rouge">E73_Objet_informationnel</code></em></td>
      </tr>
    <tr>
      <td>E29</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="3"><span class="en"><em>Design or Procedure  </em></span><em><code class="language-plaintext highlighter-rouge">E29_Conceptualisation_ou_procédure</code></em></td>
      </tr>
    <tr>
      <td>E31</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="3"><span class="en"><em>Document  </em></span><em><code class="language-plaintext highlighter-rouge">E31_Document</code></em></td>
      </tr>
    <tr>
      <td>E32</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="2"><span class="en"><em>Authority Document  </em></span><em><code class="language-plaintext highlighter-rouge">E32_Document_de_référence</code></em></td>
      </tr>
    <tr>
      <td>E33</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="3"><span class="en"><em>Linguistic Object  </em></span><em><code class="language-plaintext highlighter-rouge">E33_Objet_linguistique</code></em></td>
      </tr>
    <tr>
      <td>E34</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="2"><span class="en"><em>Inscription  </em></span><em><code class="language-plaintext highlighter-rouge">E34_Inscription</code></em></td>
      </tr>
    <tr>
      <td>E35</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="2"><span class="en"><em>Title  </em></span><em><code class="language-plaintext highlighter-rouge">E35_Titre</code></em></td>
      </tr>
    <tr>
      <td>E36</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="3"><span class="en"><em>Visual Item  </em></span><em><code class="language-plaintext highlighter-rouge">E36_Entité_visuelle</code></em></td>
      </tr>
    <tr>
      <td>E37</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="2"><span class="en"><em>Mark  </em></span><em><code class="language-plaintext highlighter-rouge">E37_Marque</code></em></td>
      </tr>
    <tr>
      <td>E34</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="1"><span class="en"><em>Inscription  </em></span><em><code class="language-plaintext highlighter-rouge">E34_Inscription</code></em></td>
    </tr>
    <tr>
      <td>E30</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">Right </span><code class="language-plaintext highlighter-rouge">E30_Droit</code></td>
      </tr>
    <tr>
      <td>E55</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en">Type </span><code class="language-plaintext highlighter-rouge">E55_Type</code></td>
      </tr>
    <tr>
      <td>E56</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">Language </span><code class="language-plaintext highlighter-rouge">E56_Langue</code></td>
      </tr>
    <tr>
      <td>E57</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">Material </span><code class="language-plaintext highlighter-rouge">E57_Matériau</code></td>
      </tr>
    <tr>
      <td>E58</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">Measurement Unit </span><code class="language-plaintext highlighter-rouge">E58_Unité_de_mesure</code></td>
      </tr>
    <tr>
      <td>E98</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="3"><span class="en">Currency </span><code class="language-plaintext highlighter-rouge">E98_Unité_monétaire</code></td>
      </tr>
    <tr>
      <td>E99</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">Product Type </span><code class="language-plaintext highlighter-rouge">E99_Modèle_de_produit</code></td>
      </tr>
    <tr>
      <td>E39</td>
      <td>-</td>
      <td>-</td>
      <td colspan="8"><span class="en">Actor </span><code class="language-plaintext highlighter-rouge">E39_Actant</code></td>
      </tr>
    <tr>
      <td>E74</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="7"><span class="en">Group </span><code class="language-plaintext highlighter-rouge">E74_Groupe</code></td>
      </tr>
    <tr>
      <td>E21</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="7"><span class="en"><em>Person  </em></span><em><code class="language-plaintext highlighter-rouge">E21_Personne</code></em></td>
      </tr>
    <tr>
      <td>E52</td>
      <td>-</td>
      <td colspan="9"><span class="en">Time-Span </span><code class="language-plaintext highlighter-rouge">E52_Intervalle_temporel</code></td>
      </tr>
    <tr>
      <td>E53</td>
      <td>-</td>
      <td colspan="9"><span class="en">Place </span><code class="language-plaintext highlighter-rouge">E53_Lieu</code></td>
      </tr>
    <tr>
      <td>E54</td>
      <td>-</td>
      <td colspan="9"><span class="en">Dimension </span><code class="language-plaintext highlighter-rouge">E54_Dimension</code></td>
      </tr>
    <tr>
      <td>E97</td>
      <td>-</td>
      <td>-</td>
      <td colspan="8"><span class="en">Monetary Amount </span><code class="language-plaintext highlighter-rouge">E97_Valeur_monétaire</code></td>
      </tr>
    <tr>
      <td>E92</td>
      <td>-</td>
      <td colspan="9"><span class="en">Spacetime Volume </span><code class="language-plaintext highlighter-rouge">E92_Volume_spatio-temporel</code></td>
      </tr>
    <tr>
      <td>E4</td>
      <td>-</td>
      <td>-</td>
      <td colspan="8"><span class="en"><em>Period  </em></span><em><code class="language-plaintext highlighter-rouge">E4_Période</code></em></td>
      </tr>
    <tr>
      <td>E5</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="7"><span class="en"><em>Event  </em></span><em><code class="language-plaintext highlighter-rouge">E5_Évènement</code></em></td>
      </tr>
    <tr>
      <td>E7</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="6"><span class="en"><em>Activity  </em></span><em><code class="language-plaintext highlighter-rouge">E7_Activité</code></em></td>
      </tr>
    <tr>
      <td>E8</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en"><em>Acquisition  </em></span><em><code class="language-plaintext highlighter-rouge">E8_Acquisition</code></em></td>
      </tr>
    <tr>
      <td>E96</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en"><em>Purchase  </em></span><em><code class="language-plaintext highlighter-rouge">E96_Achat</code></em></td>
      </tr>
    <tr>
      <td>E9</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en"><em>Move  </em></span><em><code class="language-plaintext highlighter-rouge">E9_Déplacement</code></em></td>
      </tr>
    <tr>
      <td>E10</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en"><em>Transfer of Custody  </em></span><em><code class="language-plaintext highlighter-rouge">E10_Transfert_de_la_garde</code></em></td>
      </tr>
    <tr>
      <td>E11</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en"><em>Modification  </em></span><em><code class="language-plaintext highlighter-rouge">E11_Modification</code></em></td>
      </tr>
    <tr>
      <td>E12</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en"><em>Production  </em></span><em><code class="language-plaintext highlighter-rouge">E12_Production</code></em></td>
      </tr>
    <tr>
      <td>E79</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en"><em>Part Addition  </em></span><em><code class="language-plaintext highlighter-rouge">E79_Ajout_d’élément</code></em></td>
      </tr>
    <tr>
      <td>E80</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en"><em>Part Removal  </em></span><em><code class="language-plaintext highlighter-rouge">E80_Retrait_d’élément</code></em></td>
      </tr>
    <tr>
      <td>E13</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en"><em>Attribute Assignment  </em></span><em><code class="language-plaintext highlighter-rouge">E13_Assignation_d’attribut</code></em></td>
      </tr>
    <tr>
      <td>E14</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en"><em>Condition Assessment  </em></span><em><code class="language-plaintext highlighter-rouge">E14_Évaluation_d’état_matériel</code></em></td>
      </tr>
    <tr>
      <td>E15</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en"><em>Identifier Assignment  </em></span><em><code class="language-plaintext highlighter-rouge">E15_Assignation_d’identifiant</code></em></td>
      </tr>
    <tr>
      <td>E16</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en"><em>Measurement  </em></span><em><code class="language-plaintext highlighter-rouge">E16_Mesurage</code></em></td>
      </tr>
    <tr>
      <td>E17</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en"><em>Type Assignment  </em></span><em><code class="language-plaintext highlighter-rouge">E17_Assignation_de_type</code></em></td>
      </tr>
    <tr>
      <td>E65</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en"><em>Creation  </em></span><em><code class="language-plaintext highlighter-rouge">E65_Création</code></em></td>
      </tr>
    <tr>
      <td>E83</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en"><em>Type Creation  </em></span><em><code class="language-plaintext highlighter-rouge">E83_Création_de_type</code></em></td>
      </tr>
    <tr>
      <td>E66</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en"><em>Formation  </em></span><em><code class="language-plaintext highlighter-rouge">E66_Formation</code></em></td>
      </tr>
    <tr>
      <td>E85</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en"><em>Joining  </em></span><em><code class="language-plaintext highlighter-rouge">E85_Adhésion</code></em></td>
      </tr>
    <tr>
      <td>E86</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en"><em>Leaving  </em></span><em><code class="language-plaintext highlighter-rouge">E86_Départ</code></em></td>
      </tr>
    <tr>
      <td>E87</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en"><em>Curation Activity  </em></span><em><code class="language-plaintext highlighter-rouge">E87_Activité_curatoriale</code></em></td>
      </tr>
    <tr>
      <td>E63</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="6"><span class="en"><em>Beginning of Existence  </em></span><em><code class="language-plaintext highlighter-rouge">E63_Début_d’existence</code></em></td>
      </tr>
    <tr>
      <td>E67</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en"><em>Birth  </em></span><em><code class="language-plaintext highlighter-rouge">E67_Naissance</code></em></td>
      </tr>
    <tr>
      <td>E81</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en"><em>Transformation  </em></span><em><code class="language-plaintext highlighter-rouge">E81_Transformation</code></em></td>
      </tr>
    <tr>
      <td>E12</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en"><em>Production  </em></span><em><code class="language-plaintext highlighter-rouge">E12_Production</code></em></td>
      </tr>
    <tr>
      <td>E65</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en"><em>Creation  </em></span><em><code class="language-plaintext highlighter-rouge">E65_Création</code></em></td>
      </tr>
    <tr>
      <td>E83</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en"><em>Type Creation  </em></span><em><code class="language-plaintext highlighter-rouge">E83_Création_de_type</code></em></td>
      </tr>
    <tr>
      <td>E66</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en"><em>Formation  </em></span><em><code class="language-plaintext highlighter-rouge">E66_Formation</code></em></td>
      </tr>
    <tr>
      <td>E64</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="6"><span class="en"><em>End of Existence  </em></span><em><code class="language-plaintext highlighter-rouge">E64_Fin_d’existence</code></em></td>
      </tr>
    <tr>
      <td>E6</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en"><em>Destruction  </em></span><em><code class="language-plaintext highlighter-rouge">E6_Destruction</code></em></td>
      </tr>
    <tr>
      <td>E68</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en"><em>Dissolution  </em></span><em><code class="language-plaintext highlighter-rouge">E68_Dissolution</code></em></td>
      </tr>
    <tr>
      <td>E69</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en"><em>Death  </em></span><em><code class="language-plaintext highlighter-rouge">E69_Mort</code></em></td>
      </tr>
    <tr>
      <td>E81</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="5"><span class="en"><em>Transformation  </em></span><em><code class="language-plaintext highlighter-rouge">E81_Transformation</code></em></td>
      </tr>
    <tr>
      <td>E93</td>
      <td>-</td>
      <td>-</td>
      <td colspan="8"><span class="en">Presence </span><code class="language-plaintext highlighter-rouge">E93_Présence</code></td>
      </tr>
    <tr>
      <td>E59</td>
      <td>-</td>
      <td colspan="9"><span class="en">Primitive Value </span><code class="language-plaintext highlighter-rouge">E59_Valeur_primitive</code></td>
      </tr>
    <tr>
      <td>E60</td>
      <td>-</td>
      <td>-</td>
      <td colspan="8"><span class="en">Number </span><code class="language-plaintext highlighter-rouge">E60_Nombre</code></td>
      </tr>
    <tr>
      <td>E61</td>
      <td>-</td>
      <td>-</td>
      <td colspan="8"><span class="en"><em>Time Primitive  </em></span><em><code class="language-plaintext highlighter-rouge">E61_Primitive_temporelle</code></em></td>
      </tr>
    <tr>
      <td>E62</td>
      <td>-</td>
      <td>-</td>
      <td colspan="8"><span class="en">String </span><code class="language-plaintext highlighter-rouge">E62_Chaîne_de_caractères</code></td>
      </tr>
    <tr>
      <td>E94</td>
      <td>-</td>
      <td>-</td>
      <td colspan="8"><span class="en"><em>Space Primitive  </em></span><em><code class="language-plaintext highlighter-rouge">E94_Primitive_spatiale</code></em></td>
      </tr>
    <tr>
      <td>E95</td>
      <td>-</td>
      <td>-</td>
      <td colspan="8"><span class="en"><em>Spacetime Primitive  </em></span><em><code class="language-plaintext highlighter-rouge">E95_Primitive_spatio-temporelle</code></em></td>
      </tr>
  </tbody>
</table>

<h2 id="liste-hierarchisee-des-proprietes-du-cidoc-crm"><span class="en heading">CIDOC CRM Property Hierarchy - </span>Liste hiérarchisée des propriétés du CIDOC CRM</h2>

<table id="cidoc-crm-property-hierarchy-table">
  <tbody>
    <tr>
      <td><strong><span class="en">Property id - </span>Identifiant unique de propriété</strong></td>
      <td colspan="6"><strong><span class="en">Property Name - </span>Nom de la propriété</strong></td>
      <td><strong><span class="en">Entity Domain - </span>Domaine</strong></td>
      <td><strong><span class="en">Entity Range - </span>Portée</strong></td>
    </tr>
    <tr>
      <td>P1</td>
      <td colspan="6"><span class="en">is identified by (identifies) </span><code class="language-plaintext highlighter-rouge">P1_est_identifié_par (identifie)</code></td>
      <td><span class="en">E1 CRM Entity </span><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></td>
      <td><span class="en">E41 Appellation </span><code class="language-plaintext highlighter-rouge">E41_Appellation</code></td>
    </tr>
    <tr>
      <td>P48</td>
      <td>-</td>
      <td colspan="5"><span class="en">has preferred identifier (is preferred identifier of) </span><code class="language-plaintext highlighter-rouge">P48_a_pour_identifiant_préférentiel (est_l’identifiant_préférentiel_de)</code></td>
      <td><span class="en">E1 CRM Entity </span><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></td>
      <td><span class="en">E42 Identifier </span><code class="language-plaintext highlighter-rouge">E42_Identifiant</code></td>
    </tr>
    <tr>
      <td>P102</td>
      <td>-</td>
      <td colspan="5"><span class="en">has title (is title of) </span><code class="language-plaintext highlighter-rouge">P102_a_pour_titre (est_le_titre_de)</code></td>
      <td><span class="en">E71 Human-Made Thing </span><code class="language-plaintext highlighter-rouge">E71_Chose_élaborée_par_l’humain</code></td>
      <td><span class="en">E35 Title </span><code class="language-plaintext highlighter-rouge">E35_Titre</code></td>
    </tr>
    <tr>
      <td>P168</td>
      <td>-</td>
      <td colspan="5"><span class="en">place is defined by (defines place) </span><code class="language-plaintext highlighter-rouge">P168_lieu_défini_par (définit_le_lieu)</code></td>
      <td><span class="en">E53 Place </span><code class="language-plaintext highlighter-rouge">E53_Lieu</code></td>
      <td><span class="en">E94 Space Primitive </span><code class="language-plaintext highlighter-rouge">E94_Primitive_spatiale</code></td>
    </tr>
    <tr>
      <td>P169i</td>
      <td>-</td>
      <td colspan="5"><span class="en">spacetime volume is defined by (defines spacetime volume) </span><code class="language-plaintext highlighter-rouge">P169i_volume_spatio-temporel_défini_par (définit_le_volume_spatio-temporel)</code></td>
      <td><span class="en">E92 Spacetime Volume </span><code class="language-plaintext highlighter-rouge">E92_Volume_spatio-temporel</code></td>
      <td><span class="en">E95 Spacetime Primitive </span><code class="language-plaintext highlighter-rouge">E95_Primitive_spatio-temporelle</code></td>
    </tr>
    <tr>
      <td>P170i</td>
      <td>-</td>
      <td colspan="5"><span class="en">time is defined by (defines time) </span><code class="language-plaintext highlighter-rouge">P170i_temps_défini_par (définit_le_temps)</code></td>
      <td><span class="en">E52 Time-Span </span><code class="language-plaintext highlighter-rouge">E52_Intervalle_temporel </code></td>
      <td><span class="en">E61 Time Primitive </span><code class="language-plaintext highlighter-rouge">E61_Primitive_temporelle</code></td>
    </tr>
    <tr>
      <td>P2</td>
      <td colspan="6"><span class="en">has type (is type of) </span><code class="language-plaintext highlighter-rouge">P2_a_pour_type (est_le_type_de)</code></td>
      <td><span class="en">E1 CRM Entity </span><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></td>
      <td><span class="en">E55 Type </span><code class="language-plaintext highlighter-rouge">E55_Type</code></td>
    </tr>
    <tr>
      <td>P137</td>
      <td>-</td>
      <td colspan="5"><span class="en">exemplifies (is exemplified by) </span><code class="language-plaintext highlighter-rouge">P137_exemplifie (est_exemplifié_par)</code></td>
      <td><span class="en">E1 CRM Entity </span><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></td>
      <td><span class="en">E55 Type </span><code class="language-plaintext highlighter-rouge">E55_Type</code></td>
    </tr>
    <tr>
      <td>P177</td>
      <td>-</td>
      <td colspan="5"><span class="en">assigned property type </span><code class="language-plaintext highlighter-rouge">P177_a_assigné_le_type_de_propriété (est le type de la propriété assigné) </code></td>
      <td><span class="en">E13 Attribute Assignment </span><code class="language-plaintext highlighter-rouge">E13_Assignation_d’attribut</code></td>
      <td><span class="en">E55 Type </span><code class="language-plaintext highlighter-rouge">E55_Type</code></td>
    </tr>
    <tr>
      <td>P3</td>
      <td colspan="6"><span class="en">has note </span><code class="language-plaintext highlighter-rouge">P3_a_pour_note</code></td>
      <td><span class="en">E1 CRM Entity </span><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></td>
      <td><span class="en">E62 String </span><code class="language-plaintext highlighter-rouge">E62_Chaîne_de_caractères</code></td>
    </tr>
    <tr>
      <td>P79</td>
      <td>-</td>
      <td colspan="5"><span class="en">beginning is qualified by </span><code class="language-plaintext highlighter-rouge">P79_a_son_début_qualifié_par</code></td>
      <td><span class="en">E52 Time-Span </span><code class="language-plaintext highlighter-rouge">E52_Intervalle_temporel </code></td>
      <td><span class="en">E62 String </span><code class="language-plaintext highlighter-rouge">E62_Chaîne_de_caractères</code></td>
    </tr>
    <tr>
      <td>P80</td>
      <td>-</td>
      <td colspan="5"><span class="en">end is qualified by </span><code class="language-plaintext highlighter-rouge">P80_a_sa_fin_qualifiée_par</code></td>
      <td><span class="en">E52 Time-Span </span><code class="language-plaintext highlighter-rouge">E52_Intervalle_temporel </code></td>
      <td><span class="en">E62 String </span><code class="language-plaintext highlighter-rouge">E62_Chaîne_de_caractères</code></td>
    </tr>
    <tr>
      <td>P190</td>
      <td>-</td>
      <td colspan="5"><span class="en">has symbolic content </span><code class="language-plaintext highlighter-rouge">P190_a_pour_contenu_symbolique</code></td>
      <td><span class="en">E90 Symbolic Object </span><code class="language-plaintext highlighter-rouge">E90_Objet_symbolique</code></td>
      <td><span class="en">E62 String </span><code class="language-plaintext highlighter-rouge">E62_Chaîne_de_caractères</code></td>
    </tr>
    <tr>
      <td>P4</td>
      <td colspan="6"><span class="en">has time-span (is time-span of) </span><code class="language-plaintext highlighter-rouge">P4_a_pour_intervalle_temporel (est_l’intervalle_temporel_de)</code></td>
      <td><span class="en">E2 Temporal Entity </span><code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code></td>
      <td><span class="en">E52 Time-Span </span><code class="language-plaintext highlighter-rouge">E52_Intervalle_temporel </code></td>
    </tr>
    <tr>
      <td>P5</td>
      <td colspan="6"><span class="en">consists of (forms part of) </span><code class="language-plaintext highlighter-rouge">P5_comprend (fait_partie_de)</code></td>
      <td><span class="en">E3 Condition State </span><code class="language-plaintext highlighter-rouge">E3_État_matériel</code></td>
      <td><span class="en">E3 Condition State </span><code class="language-plaintext highlighter-rouge">E3_État_matériel</code></td>
    </tr>
    <tr>
      <td>P7</td>
      <td colspan="6"><span class="en">took place at (witnessed) </span><code class="language-plaintext highlighter-rouge">P7_a_eu_lieu_dans (a_été_témoin_de)</code></td>
      <td><span class="en">E4 Period </span><code class="language-plaintext highlighter-rouge">E4_Période</code></td>
      <td><span class="en">E53 Place </span><code class="language-plaintext highlighter-rouge">E53_Lieu</code></td>
    </tr>
    <tr>
      <td>P8</td>
      <td colspan="6"><span class="en">took place on or within (witnessed) </span><code class="language-plaintext highlighter-rouge">P8_a_eu_lieu (a_été_témoin_de)</code></td>
      <td><span class="en">E4 Period </span><code class="language-plaintext highlighter-rouge">E4_Période</code></td>
      <td><span class="en">E18 Physical Thing </span><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></td>
    </tr>
    <tr>
      <td>P12</td>
      <td colspan="6"><span class="en">occured in the presence of (was present at) </span><code class="language-plaintext highlighter-rouge">P12_a_eu_lieu_en_présence_de (a_été_présent_à)</code></td>
      <td><span class="en">E5 Event </span><code class="language-plaintext highlighter-rouge">E5_Évènement</code></td>
      <td><span class="en">E77 Persistent Item </span><code class="language-plaintext highlighter-rouge">E77_Entité_persistante</code></td>
    </tr>
    <tr>
      <td>P111</td>
      <td>-</td>
      <td colspan="5"><span class="en">added (was added by) </span><code class="language-plaintext highlighter-rouge">P111_a_ajouté (a_été_ajouté_par)</code></td>
      <td><span class="en">E79 Part Addition </span><code class="language-plaintext highlighter-rouge">E79_Ajout_d’élément</code></td>
      <td><span class="en">E18 Physical Thing </span><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></td>
    </tr>
    <tr>
      <td>P113</td>
      <td>-</td>
      <td colspan="5"><span class="en">removed (was removed by) </span><code class="language-plaintext highlighter-rouge">P113_a_retiré (a_été_retiré_par)</code></td>
      <td><span class="en">P80 Part Removal </span><code class="language-plaintext highlighter-rouge">E80_Retrait_d’élément</code></td>
      <td><span class="en">E18 Physical Thing </span><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></td>
    </tr>
    <tr>
      <td>P11</td>
      <td>-</td>
      <td colspan="5"><span class="en">had participant (participated in) </span><code class="language-plaintext highlighter-rouge">P11_a_eu_pour_actant_participant (a_participé_à)</code></td>
      <td><span class="en">E5 Event </span><code class="language-plaintext highlighter-rouge">E5_Évènement</code></td>
      <td><span class="en">E39 Actor </span><code class="language-plaintext highlighter-rouge">E39_Actant</code></td>
    </tr>
    <tr>
      <td>P14</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">carried out by (performed) </span><code class="language-plaintext highlighter-rouge">P14_a_été_effectué_par (a_effectué)</code></td>
      <td><span class="en">E7 Activity </span><code class="language-plaintext highlighter-rouge">E7_Activité</code></td>
      <td><span class="en">E39 Actor </span><code class="language-plaintext highlighter-rouge">E39_Actant</code></td>
    </tr>
    <tr>
      <td>P22</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="3"><span class="en">transferred title to (acquired title through) </span><code class="language-plaintext highlighter-rouge">P22_a_transféré_le_titre_de_propriété_à (a_acquis_le_titre_de_propriété_par)</code></td>
      <td><span class="en">E8 Acquisition </span><code class="language-plaintext highlighter-rouge">E8_Acquisition</code></td>
      <td><span class="en">E39 Actor </span><code class="language-plaintext highlighter-rouge">E39_Actant</code></td>
    </tr>
    <tr>
      <td>P23</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="3"><span class="en">transferred title from (surrendered title through) </span><code class="language-plaintext highlighter-rouge">P23_a_transféré_le_titre_de_propriété_de (a_cédé_le_titre_de_propriété_à)</code></td>
      <td><span class="en">E8 Acquisition </span><code class="language-plaintext highlighter-rouge">E8_Acquisition</code></td>
      <td><span class="en">E39 Actor </span><code class="language-plaintext highlighter-rouge">E39_Actant</code></td>
    </tr>
    <tr>
      <td>P28</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="3"><span class="en">Custody surrendered by (surrendered custody through) </span><code class="language-plaintext highlighter-rouge">P28_a_mis_fin_à_la_garde_par (a_cédé_la_garde_par)</code></td>
      <td><span class="en">E10 Transfer of Custody </span><code class="language-plaintext highlighter-rouge">E10_Transfert_de_la_garde</code></td>
      <td><span class="en">E39 Actor </span><code class="language-plaintext highlighter-rouge">E39_Actant</code></td>
    </tr>
    <tr>
      <td>P29</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="3"><span class="en">custody received by (received custody through) </span><code class="language-plaintext highlighter-rouge">P29_a_confié_la_garde_par (a_reçu_la_garde_par)</code></td>
      <td><span class="en">E10 Transfer of Custody </span><code class="language-plaintext highlighter-rouge">E10_Transfert_de_la_garde</code></td>
      <td><span class="en">E39 Actor </span><code class="language-plaintext highlighter-rouge">E39_Actant</code></td>
    </tr>
    <tr>
      <td>P96</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">by mother (gave birth) </span><code class="language-plaintext highlighter-rouge">P96_de_mère (a_donné_naissance_à)</code></td>
      <td><span class="en">E67 Birth </span><code class="language-plaintext highlighter-rouge">E67_Naissance</code></td>
      <td><span class="en">E21 Person </span><code class="language-plaintext highlighter-rouge">E21_Personne</code></td>
    </tr>
    <tr>
      <td>P99</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">dissolved (was dissolved by) </span><code class="language-plaintext highlighter-rouge">P99_a_dissous (a_été_dissous_par)</code></td>
      <td><span class="en">E68 Dissolution </span><code class="language-plaintext highlighter-rouge">E68_Dissolution</code></td>
      <td><span class="en">E74 Group </span><code class="language-plaintext highlighter-rouge">E74_Groupe</code></td>
    </tr>
    <tr>
      <td>P143</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">joined (was joined by) </span><code class="language-plaintext highlighter-rouge">P143_a_fait_adhérer (a_adhéré_par)</code></td>
      <td><span class="en">E85 Joining </span><code class="language-plaintext highlighter-rouge">E85_Adhésion</code></td>
      <td><span class="en">E39 Actor </span><code class="language-plaintext highlighter-rouge">E39_Actant</code></td>
    </tr>
    <tr>
      <td>P144</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">joined with (gained memeber by) </span><code class="language-plaintext highlighter-rouge">P144_a_fait_adhérer_à (a_accueilli_le_membre_par)</code></td>
      <td><span class="en">E85 Joining </span><code class="language-plaintext highlighter-rouge">E85_Adhésion</code></td>
      <td><span class="en">E74 Group </span><code class="language-plaintext highlighter-rouge">E74_Groupe</code></td>
    </tr>
    <tr>
      <td>P145</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">separated (left by) </span><code class="language-plaintext highlighter-rouge">P145_a_dissocié (est_dissocié_par)</code></td>
      <td><span class="en">E86 Leaving </span><code class="language-plaintext highlighter-rouge">E86_Départ</code></td>
      <td><span class="en">E39 Actor </span><code class="language-plaintext highlighter-rouge">E39_Actant</code></td>
    </tr>
    <tr>
      <td>P146</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">separated from (lost member by) </span><code class="language-plaintext highlighter-rouge">P146_a_dissocié_de (a_perdu_le_membre_par)</code></td>
      <td><span class="en">E86 Leaving </span><code class="language-plaintext highlighter-rouge">E86_Départ</code></td>
      <td><span class="en">E74 Group </span><code class="language-plaintext highlighter-rouge">E74_Groupe</code></td>
    </tr>
    <tr>
      <td>P151</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">was formed from (participated in) </span><code class="language-plaintext highlighter-rouge">P151_a_été_formé_à_partir_de (a_participé_à)</code></td>
      <td><span class="en">E66 Formation </span><code class="language-plaintext highlighter-rouge">E66_Formation</code></td>
      <td><span class="en">E74 Group </span><code class="language-plaintext highlighter-rouge">E74_Groupe</code></td>
    </tr>
    <tr>
      <td>P16</td>
      <td>-</td>
      <td colspan="5"><span class="en">used specific object (was used for) </span><code class="language-plaintext highlighter-rouge">P16_a_mobilisé_l’objet_spécifique (a_été_mobilisé_pour)</code></td>
      <td><span class="en">E7 Activity </span><code class="language-plaintext highlighter-rouge">E7_Activité</code></td>
      <td><span class="en">E70 Thing </span><code class="language-plaintext highlighter-rouge">E70_Chose</code></td>
    </tr>
    <tr>
      <td>P33</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">used specific technique (was used by) </span><code class="language-plaintext highlighter-rouge">P33_a_mobilisé_comme_technique_spécifique (a_été_la_technique_spécifique_mise_en_œuvre_dans)</code></td>
      <td><span class="en">E7 Activity </span><code class="language-plaintext highlighter-rouge">E7_Activité</code></td>
      <td><span class="en">E29 Design or Procedure </span><code class="language-plaintext highlighter-rouge">E29_Conceptualisation_ou_procédure</code></td>
    </tr>
    <tr>
      <td>P111</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">added (as added by) </span><code class="language-plaintext highlighter-rouge">P111_a_ajouté (a_été_ajouté_par)</code></td>
      <td><span class="en">E79 Part Addition </span><code class="language-plaintext highlighter-rouge">E79_Ajout_d’élément</code></td>
      <td><span class="en">E18 Physical Thing </span><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></td>
    </tr>
    <tr>
      <td>P142</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">used constituent (was used in) </span><code class="language-plaintext highlighter-rouge">P142_a_mobilisé_comme_élément (a_été_mobilisé_dans)</code></td>
      <td><span class="en">E15 Identifier Assignment </span><code class="language-plaintext highlighter-rouge">E15_Assignation_d’identifiant</code></td>
      <td><span class="en">E90 Symbolic Object </span><code class="language-plaintext highlighter-rouge">E90_Objet_symbolique</code></td>
    </tr>
    <tr>
      <td>P25</td>
      <td>-</td>
      <td colspan="5"><span class="en">moved (moved by) </span><code class="language-plaintext highlighter-rouge">P25_a_déplacé (a_été_déplacé_par)</code></td>
      <td><span class="en">E9 Move </span><code class="language-plaintext highlighter-rouge">E9_Déplacement</code></td>
      <td><span class="en">E19 Physical Object </span><code class="language-plaintext highlighter-rouge">E19_Objet_matériel</code></td>
    </tr>
    <tr>
      <td>P31</td>
      <td>-</td>
      <td colspan="5"><span class="en">has modified (was modified by) </span><code class="language-plaintext highlighter-rouge">P31_a_modifié (a_été_modifié_par)</code></td>
      <td><span class="en">E11 Modification </span><code class="language-plaintext highlighter-rouge">E11_Modification</code></td>
      <td><span class="en">E18 Physical Thing </span><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></td>
    </tr>
    <tr>
      <td>P108</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">has produced (was produced by) </span><code class="language-plaintext highlighter-rouge">P108_a_produit (a_été_produit_par)</code></td>
      <td><span class="en">E12 Production </span><code class="language-plaintext highlighter-rouge">E12_Production</code></td>
      <td><span class="en">E24 Physical Human-Made Thing </span><code class="language-plaintext highlighter-rouge">E24_Chose_matérielle_élaborée_par_l’humain</code></td>
    </tr>
    <tr>
      <td>P110</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">augmented (was augmented by) </span><code class="language-plaintext highlighter-rouge">P110_a_augmenté (a_été_augmenté_par)</code></td>
      <td><span class="en">E79 Part Addition </span><code class="language-plaintext highlighter-rouge">E79_Ajout_d’élément</code></td>
      <td><span class="en">E24 Physical Human-Made Thing </span><code class="language-plaintext highlighter-rouge">E24_Chose_matérielle_élaborée_par_l’humain</code></td>
    </tr>
    <tr>
      <td>P112</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">diminished (was diminished by) </span><code class="language-plaintext highlighter-rouge">P112_a_diminué (a_été_diminué_par)</code></td>
      <td><span class="en">P80 Part Removal </span><code class="language-plaintext highlighter-rouge">E80_Retrait_d’élément</code></td>
      <td><span class="en">E24 Physical Human-Made Thing </span><code class="language-plaintext highlighter-rouge">E24_Chose_matérielle_élaborée_par_l’humain</code></td>
    </tr>
    <tr>
      <td>P92</td>
      <td>-</td>
      <td colspan="5"><span class="en">brought into existence (was brought into existence by) </span><code class="language-plaintext highlighter-rouge">P92_a_fait_exister (a_commencé_à_exister_par)</code></td>
      <td><span class="en">E63 Beginning of Existence </span><code class="language-plaintext highlighter-rouge">E63_Début_d’existence</code></td>
      <td><span class="en">E77 Persistent Item </span><code class="language-plaintext highlighter-rouge">E77_Entité_persistante</code></td>
    </tr>
    <tr>
      <td>P94</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">has created (was creates by) </span><code class="language-plaintext highlighter-rouge">P94_a_créé (a_été_créé_par)</code></td>
      <td><span class="en">E65 Creation </span><code class="language-plaintext highlighter-rouge">E65_Création</code></td>
      <td><span class="en">E28 Conceptual Object </span><code class="language-plaintext highlighter-rouge">E28_Objet_conceptuel</code></td>
    </tr>
    <tr>
      <td>P135</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="3"><span class="en">created type (was created by) </span><code class="language-plaintext highlighter-rouge">P135_a_créé_le_type (a_été_créé_par)</code></td>
      <td><span class="en">E83 Type Creation </span><code class="language-plaintext highlighter-rouge">E83_Création_de_type</code></td>
      <td><span class="en">E55 Type </span><code class="language-plaintext highlighter-rouge">E55_Type</code></td>
    </tr>
    <tr>
      <td>P95</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">has formed (was formed by) </span><code class="language-plaintext highlighter-rouge">P95_a_fondé (a_été_fondé_par)</code></td>
      <td><span class="en">E66 Formation </span><code class="language-plaintext highlighter-rouge">E66_Formation</code></td>
      <td><span class="en">E74 Group </span><code class="language-plaintext highlighter-rouge">E74_Groupe</code></td>
    </tr>
    <tr>
      <td>P98</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">brought into life (was born) </span><code class="language-plaintext highlighter-rouge">P98_a_donné_vie_à (a_été_dissous_par)</code></td>
      <td><span class="en">E67 Birth </span><code class="language-plaintext highlighter-rouge">E67_Naissance</code></td>
      <td><span class="en">E21 Person </span><code class="language-plaintext highlighter-rouge">E21_Personne</code></td>
    </tr>
    <tr>
      <td>P108</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">has produced (was produced by) </span><code class="language-plaintext highlighter-rouge">P108_a_produit (a_été_produit_par)</code></td>
      <td><span class="en">E12 Production </span><code class="language-plaintext highlighter-rouge">E12_Production</code></td>
      <td><span class="en">E24 Physical Human-Made Thing </span><code class="language-plaintext highlighter-rouge">E24_Chose_matérielle_élaborée_par_l’humain</code></td>
    </tr>
    <tr>
      <td>P123</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">resulted in (resutled from) </span><code class="language-plaintext highlighter-rouge">P123_a_eu_pour_résultat (a_résulté_de)</code></td>
      <td><span class="en">E81 Transformation </span><code class="language-plaintext highlighter-rouge">E81_Transformation</code></td>
      <td><span class="en">E77 Persistent Item </span><code class="language-plaintext highlighter-rouge">E77_Entité_persistante</code></td>
    </tr>
    <tr>
      <td>P93</td>
      <td>-</td>
      <td colspan="5"><span class="en">took out of existence (was taken out of existence by) </span><code class="language-plaintext highlighter-rouge">P93_a_mis_fin_à_l’existence_de (a_cessé_d’exister_par)</code></td>
      <td><span class="en">E64 End of Existence </span><code class="language-plaintext highlighter-rouge">E64_Fin_d’existence</code></td>
      <td><span class="en">E77 Persistent Item </span><code class="language-plaintext highlighter-rouge">E77_Entité_persistante</code></td>
    </tr>
    <tr>
      <td>P13</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">destroyed (was destroyed by) </span><code class="language-plaintext highlighter-rouge">P13_a_détruit (a_été_détruit_par)</code></td>
      <td><span class="en">E6 Destruction </span><code class="language-plaintext highlighter-rouge">E6_Destruction</code></td>
      <td><span class="en">E18 Physical Thing </span><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></td>
    </tr>
    <tr>
      <td>P99</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">dissolved (was dissolved by) </span><code class="language-plaintext highlighter-rouge">P99_a_dissous (a_été_dissous_par)</code></td>
      <td><span class="en">E68 Dissolution </span><code class="language-plaintext highlighter-rouge">E68_Dissolution</code></td>
      <td><span class="en">E74 Group </span><code class="language-plaintext highlighter-rouge">E74_Groupe</code></td>
    </tr>
    <tr>
      <td>P100</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">was death of (died in) </span><code class="language-plaintext highlighter-rouge">P100_a_été_la_mort_de (est_mort_par)</code></td>
      <td><span class="en">E69 Death </span><code class="language-plaintext highlighter-rouge">E69_Mort</code></td>
      <td><span class="en">E21 Person </span><code class="language-plaintext highlighter-rouge">E21_Personne</code></td>
    </tr>
    <tr>
      <td>P124</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">transformed (was transformed by) </span><code class="language-plaintext highlighter-rouge">P124_a_transformé (a_été_transformé_par)</code></td>
      <td><span class="en">E81 Transformation </span><code class="language-plaintext highlighter-rouge">E81_Transformation</code></td>
      <td><span class="en">E77 Persistent Item </span><code class="language-plaintext highlighter-rouge">E77_Entité_persistante</code></td>
    </tr>
    <tr>
      <td>P15</td>
      <td colspan="6"><span class="en">was influenced by (influenced) </span><code class="language-plaintext highlighter-rouge">P15_a_été_influencé_par (a_influencé)</code></td>
      <td><span class="en">E7 Activity </span><code class="language-plaintext highlighter-rouge">E7_Activité</code></td>
      <td><span class="en">E1 CRM Entity </span><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></td>
    </tr>
    <tr>
      <td>P16</td>
      <td>-</td>
      <td colspan="5"><span class="en">used specific object (was used for) </span><code class="language-plaintext highlighter-rouge">P16_a_mobilisé_l’objet_spécifique (a_été_mobilisé_pour)</code></td>
      <td><span class="en">E7 Activity </span><code class="language-plaintext highlighter-rouge">E7_Activité</code></td>
      <td><span class="en">E70 Thing </span><code class="language-plaintext highlighter-rouge">E70_Chose</code></td>
    </tr>
    <tr>
      <td>P33</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">used specific technique (was used by) </span><code class="language-plaintext highlighter-rouge">P33_a_mobilisé_comme_technique_spécifique (a_été_la_technique_spécifique_mise_en_œuvre_dans)</code></td>
      <td><span class="en">E11 Modification </span><code class="language-plaintext highlighter-rouge">E11_Modification</code></td>
      <td><span class="en">E29 Design or Procedure </span><code class="language-plaintext highlighter-rouge">E29_Conceptualisation_ou_procédure</code></td>
    </tr>
    <tr>
      <td>P111</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">added (was added by) </span><code class="language-plaintext highlighter-rouge">P111_a_ajouté (a_été_ajouté_par)</code></td>
      <td><span class="en">E79 Part Addition </span><code class="language-plaintext highlighter-rouge">E79_Ajout_d’élément</code></td>
      <td><span class="en">E18 Physical Thing </span><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></td>
    </tr>
    <tr>
      <td>P142</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">used constituent (was used in) </span><code class="language-plaintext highlighter-rouge">P142_a_mobilisé_comme_élément (a_été_mobilisé_dans)</code></td>
      <td><span class="en">E15 Identifier Assignment </span><code class="language-plaintext highlighter-rouge">E15_Assignation_d’identifiant</code></td>
      <td><span class="en">E90 Symbolic Object </span><code class="language-plaintext highlighter-rouge">E90_Objet_symbolique</code></td>
    </tr>
    <tr>
      <td>P17</td>
      <td>-</td>
      <td colspan="5"><span class="en">was motivated by (motivated) </span><code class="language-plaintext highlighter-rouge">P17_a_été_motivé_par (a_motivé)</code></td>
      <td><span class="en">E7 Activity </span><code class="language-plaintext highlighter-rouge">E7_Activité</code></td>
      <td><span class="en">E1 CRM Entity </span><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></td>
    </tr>
    <tr>
      <td>P134</td>
      <td>-</td>
      <td colspan="5"><span class="en">continued (was continued by) </span><code class="language-plaintext highlighter-rouge">P134_a_continué (a_été_continué_par)</code></td>
      <td><span class="en">E7 Activity </span><code class="language-plaintext highlighter-rouge">E7_Activité</code></td>
      <td><span class="en">E7 Activity </span><code class="language-plaintext highlighter-rouge">E7_Activité</code></td>
    </tr>
    <tr>
      <td>P136</td>
      <td>-</td>
      <td colspan="5"><span class="en">was based on (supported type creation) </span><code class="language-plaintext highlighter-rouge">P136_a_été_fondé_sur (a_fondé_la_création_du_type)</code></td>
      <td><span class="en">E83 Type Creation </span><code class="language-plaintext highlighter-rouge">E83_Création_de_type</code></td>
      <td><span class="en">E1 CRM Entity </span><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></td>
    </tr>
    <tr>
      <td>P19</td>
      <td colspan="6"><span class="en">was intended use of (was made for) </span><code class="language-plaintext highlighter-rouge">P19_a_été_l’usage_prévu_de (a_été_élaboré_pour)</code></td>
      <td><span class="en">E7 Activity </span><code class="language-plaintext highlighter-rouge">E7_Activité</code></td>
      <td><span class="en">E71 Human-Made Thing </span><code class="language-plaintext highlighter-rouge">E71_Chose_élaborée_par_l’humain</code></td>
    </tr>
    <tr>
      <td>P20</td>
      <td colspan="6"><span class="en">has specific purpose (was purpose of) </span><code class="language-plaintext highlighter-rouge">P20_a_eu_pour_finalité_spécifique (a_été_la_finalité_de)</code></td>
      <td><span class="en">E7 Activity </span><code class="language-plaintext highlighter-rouge">E7_Activité</code></td>
      <td><span class="en">E5 Event </span><code class="language-plaintext highlighter-rouge">E5_Évènement</code></td>
    </tr>
    <tr>
      <td>P21</td>
      <td colspan="6"><span class="en">had general purpose (was purpose of) </span><code class="language-plaintext highlighter-rouge">P21_a_eu_pour_finalité_générale (a_été_la_finalité_de)</code></td>
      <td><span class="en">E7 Activity </span><code class="language-plaintext highlighter-rouge">E7_Activité</code></td>
      <td><span class="en">E55 Type </span><code class="language-plaintext highlighter-rouge">E55_Type</code></td>
    </tr>
    <tr>
      <td>P24</td>
      <td colspan="6"><span class="en">transferred title of (changed ownership through) </span><code class="language-plaintext highlighter-rouge">P24_a_transféré_le_titre_de_propriété_de (a_changé_de_propriétaire_par)</code></td>
      <td><span class="en">E8 Acquisition </span><code class="language-plaintext highlighter-rouge">E8_Acquisition</code></td>
      <td><span class="en">E18 Physical Thing </span><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></td>
    </tr>
    <tr>
      <td>P26</td>
      <td colspan="6"><span class="en">moved to (was destination of) </span><code class="language-plaintext highlighter-rouge">P26_a_déplacé_à (a_été_la_destination_de)</code></td>
      <td><span class="en">E9 Move </span><code class="language-plaintext highlighter-rouge">E9_Déplacement</code></td>
      <td><span class="en">E53 Place </span><code class="language-plaintext highlighter-rouge">E53_Lieu</code></td>
    </tr>
    <tr>
      <td>P27</td>
      <td colspan="6"><span class="en">moved from (was origin of) </span><code class="language-plaintext highlighter-rouge">P27_a_déplacé_depuis (a_été_le_point_de_départ_de)</code></td>
      <td><span class="en">E9 Move </span><code class="language-plaintext highlighter-rouge">E9_Déplacement</code></td>
      <td><span class="en">E53 Place </span><code class="language-plaintext highlighter-rouge">E53_Lieu</code></td>
    </tr>
    <tr>
      <td>P30</td>
      <td colspan="6"><span class="en">transferred custody of (custody transferred through) </span><code class="language-plaintext highlighter-rouge">P30_a_transféré_la_garde_de (a_été_l’objet_d’un_transfert_de_garde_par)</code></td>
      <td><span class="en">E10 Transfer of Custody </span><code class="language-plaintext highlighter-rouge">E10_Transfert_de_la_garde</code></td>
      <td><span class="en">E18 Physical Thing </span><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></td>
    </tr>
    <tr>
      <td>P43</td>
      <td colspan="6"><span class="en">has dimension (is dimension of) </span><code class="language-plaintext highlighter-rouge">P43_a_pour_dimension (est_la_dimension_de)</code></td>
      <td><span class="en">E70 Thing </span><code class="language-plaintext highlighter-rouge">E70_Chose</code></td>
      <td><span class="en">E54 Dimension </span><code class="language-plaintext highlighter-rouge">E54_Dimension</code></td>
    </tr>
    <tr>
      <td>P44</td>
      <td colspan="6"><span class="en">has condition (is condition of) </span><code class="language-plaintext highlighter-rouge">P44_a_pour_état_matériel (est_l’état_matériel_de)</code></td>
      <td><span class="en">E18 Physical Thing </span><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></td>
      <td><span class="en">E3 Condition State </span><code class="language-plaintext highlighter-rouge">E3_État_matériel</code></td>
    </tr>
    <tr>
      <td>P45</td>
      <td colspan="6"><span class="en">consists of (is incorporated in) </span><code class="language-plaintext highlighter-rouge">P45_comprend (est_inclus_dans)</code></td>
      <td><span class="en">E18 Physical Thing </span><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></td>
      <td><span class="en">E57 Material </span><code class="language-plaintext highlighter-rouge">E57_Matériau</code></td>
    </tr>
    <tr>
      <td>P49</td>
      <td colspan="6"><span class="en">has former or current keeper (is former or current keeper of) </span><code class="language-plaintext highlighter-rouge">P49_a_pour_actant_détenteur_actuel_ou_antérieur (est_l’actant_détenteur_actuel_ou_antérieur_de)</code></td>
      <td><span class="en">E18 Physical Thing </span><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></td>
      <td><span class="en">E39 Actor </span><code class="language-plaintext highlighter-rouge">E39_Actant</code></td>
    </tr>
    <tr>
      <td>P50</td>
      <td>-</td>
      <td colspan="5"><span class="en">has current keeper (is current keeper of) </span><code class="language-plaintext highlighter-rouge">P50_a_pour_actant_détenteur_actuel (est_l’actant_détenteur_actuel_de)</code></td>
      <td><span class="en">E18 Physical Thing </span><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></td>
      <td><span class="en">E39 Actor </span><code class="language-plaintext highlighter-rouge">E39_Actant</code></td>
    </tr>
    <tr>
      <td>P109</td>
      <td>-</td>
      <td colspan="5"><span class="en">has current or former curator (is current or former curator of) </span><code class="language-plaintext highlighter-rouge">P109_a_pour_responsable_actuel_ou_antérieur_de_la_collection (est_responsable_actuel_ou_antérieur_de_la_collection)</code></td>
      <td><span class="en">E78 Curated Holding </span><code class="language-plaintext highlighter-rouge">E78_Collection</code></td>
      <td><span class="en">E39 Actor </span><code class="language-plaintext highlighter-rouge">E39_Actant</code></td>
    </tr>
    <tr>
      <td>P51</td>
      <td colspan="6"><span class="en">has former or current owner (is former or current owner of) </span><code class="language-plaintext highlighter-rouge">P51_a_pour_propriétaire_actuel_ou_antérieur (est_l’actant_propriétaire_actuel_ou_antérieur_de)</code></td>
      <td><span class="en">E18 Physical Thing </span><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></td>
      <td><span class="en">E39 Actor </span><code class="language-plaintext highlighter-rouge">E39_Actant</code></td>
    </tr>
    <tr>
      <td>P52</td>
      <td>-</td>
      <td colspan="5"><span class="en">has current owner (is current owner of) </span><code class="language-plaintext highlighter-rouge">P52_a_pour_propriétaire_actuel (est_l’actant_propriétaire_actuel_de)</code></td>
      <td><span class="en">E18 Physical Thing </span><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></td>
      <td><span class="en">E39 Actor </span><code class="language-plaintext highlighter-rouge">E39_Actant</code></td>
    </tr>
    <tr>
      <td>P53</td>
      <td colspan="6"><span class="en">has former or current location (is former or current location of) </span><code class="language-plaintext highlighter-rouge">P53_a_pour_localisation_actuelle_ou_antérieure (est_la_localisation_actuelle_ou_antérieure_de)</code></td>
      <td><span class="en">E18 Physical Thing </span><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></td>
      <td><span class="en">E53 Place </span><code class="language-plaintext highlighter-rouge">E53_Lieu</code></td>
    </tr>
    <tr>
      <td>P55</td>
      <td>-</td>
      <td colspan="5"><span class="en">has current location (currently holds) </span><code class="language-plaintext highlighter-rouge">P55_a_actuellement_pour_localisation (est_actuellement_la_localisation_de)</code></td>
      <td><span class="en">E19 Physical Object </span><code class="language-plaintext highlighter-rouge">E19_Objet_matériel</code></td>
      <td><span class="en">E53 Place </span><code class="language-plaintext highlighter-rouge">E53_Lieu</code></td>
    </tr>
    <tr>
      <td>P156</td>
      <td>-</td>
      <td colspan="5"><span class="en">occupies (is occupied by) </span><code class="language-plaintext highlighter-rouge">P156_occupe (est_occupé_par)</code></td>
      <td><span class="en">E18 Physical Thing </span><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></td>
      <td><span class="en">E53 Place </span><code class="language-plaintext highlighter-rouge">E53_Lieu</code></td>
    </tr>
    <tr>
      <td>P54</td>
      <td colspan="6"><span class="en">has current permanent location (is current permanent location of) </span><code class="language-plaintext highlighter-rouge">P54_a_actuellement_pour_localisation_fixe (est_actuellement_la_localisation_fixe_de)</code></td>
      <td><span class="en">E19 Physical Object </span><code class="language-plaintext highlighter-rouge">E19_Objet_matériel</code></td>
      <td><span class="en">E53 Place </span><code class="language-plaintext highlighter-rouge">E53_Lieu</code></td>
    </tr>
    <tr>
      <td>P57</td>
      <td colspan="6"><span class="en">has number of parts </span><code class="language-plaintext highlighter-rouge">P57_a_pour_nombre_d’éléments</code></td>
      <td><span class="en">E19 Physical Object </span><code class="language-plaintext highlighter-rouge">E19_Objet_matériel</code></td>
      <td><span class="en">E60 Number </span><code class="language-plaintext highlighter-rouge">E60_Nombre</code></td>
    </tr>
    <tr>
      <td>P59</td>
      <td colspan="6"><span class="en">has section (is located on or within) </span><code class="language-plaintext highlighter-rouge">P59_a_pour_section (se_situe_sur_ou_dans)</code></td>
      <td><span class="en">E18 Physical Thing </span><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></td>
      <td><span class="en">E53 Place </span><code class="language-plaintext highlighter-rouge">E53_Lieu</code></td>
    </tr>
    <tr>
      <td>P62</td>
      <td colspan="6"><span class="en">depicts (is depicted by) </span><code class="language-plaintext highlighter-rouge">P62_illustre (est_illustré_par)</code></td>
      <td><span class="en">E24 Physical Human-Made Thing </span><code class="language-plaintext highlighter-rouge">E24_Chose_matérielle_élaborée_par_l’humain</code></td>
      <td><span class="en">E1 CRM Entity </span><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></td>
    </tr>
    <tr>
      <td>P67</td>
      <td colspan="6"><span class="en">refers to (is referred to by) </span><code class="language-plaintext highlighter-rouge">P67_renvoie_à (fait_l’objet_d’un_renvoi_par)</code></td>
      <td><span class="en">E89 Propositional Object </span><code class="language-plaintext highlighter-rouge">E89_Objet_propositionnel</code></td>
      <td><span class="en">E1 CRM Entity </span><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></td>
    </tr>
    <tr>
      <td>P68</td>
      <td>-</td>
      <td colspan="5"><span class="en">foresees use of (use foreseen by) </span><code class="language-plaintext highlighter-rouge">P68_prévoit_l’usage_de (usage_prévu_de)</code></td>
      <td><span class="en">E29 Design or Procedure </span><code class="language-plaintext highlighter-rouge">E29_Conceptualisation_ou_procédure</code></td>
      <td><span class="en">E57 Material </span><code class="language-plaintext highlighter-rouge">E57_Matériau</code></td>
    </tr>
    <tr>
      <td>P70</td>
      <td>-</td>
      <td colspan="5"><span class="en">documents (is documented in) </span><code class="language-plaintext highlighter-rouge">P70_documente (est_documenté_dans)</code></td>
      <td><span class="en">E31 Document </span><code class="language-plaintext highlighter-rouge">E31_Document</code></td>
      <td><span class="en">E1 CRM Entity </span><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></td>
    </tr>
    <tr>
      <td>P71</td>
      <td>-</td>
      <td colspan="5"><span class="en">lists (is listed in) </span><code class="language-plaintext highlighter-rouge">P71_énumère (est_énuméré_par)</code></td>
      <td><span class="en">E32 Authority Document </span><code class="language-plaintext highlighter-rouge">E32_Document_de_référence</code></td>
      <td><span class="en">E1 CRM Entity </span><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></td>
    </tr>
    <tr>
      <td>P129</td>
      <td>-</td>
      <td colspan="5"><span class="en">is about (is subject of) </span><code class="language-plaintext highlighter-rouge">P129_a_pour_sujet (est_le_sujet_de)</code></td>
      <td><span class="en">E89 Propositional Object </span><code class="language-plaintext highlighter-rouge">E89_Objet_propositionnel</code></td>
      <td><span class="en">E1 CRM Entity </span><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></td>
    </tr>
    <tr>
      <td>P138</td>
      <td>-</td>
      <td colspan="5"><span class="en">represents (has representation) </span><code class="language-plaintext highlighter-rouge">P138_représente (est_représenté_par)</code></td>
      <td><span class="en">E36 Visual Item </span><code class="language-plaintext highlighter-rouge">E36_Entité_visuelle</code></td>
      <td><span class="en">E1 CRM Entity </span><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></td>
    </tr>
    <tr>
      <td>P69</td>
      <td colspan="6"><span class="en">has association with (is associated with) </span><code class="language-plaintext highlighter-rouge">P69_est_associé_à (est_associé_à)</code></td>
      <td><span class="en">E29 Design or Procedure </span><code class="language-plaintext highlighter-rouge">E29_Conceptualisation_ou_procédure</code></td>
      <td><span class="en">E29 Design or Procedure </span><code class="language-plaintext highlighter-rouge">E29_Conceptualisation_ou_procédure</code></td>
    </tr>
    <tr>
      <td>P72</td>
      <td colspan="6"><span class="en">has language (is language of) </span><code class="language-plaintext highlighter-rouge">P72_a_pour_langue (est_la_langue_de)</code></td>
      <td><span class="en">E33 Linguistic Object </span><code class="language-plaintext highlighter-rouge">E33_Objet_linguistique</code></td>
      <td><span class="en">E56 Language </span><code class="language-plaintext highlighter-rouge">E56_Langue</code></td>
    </tr>
    <tr>
      <td>P74</td>
      <td colspan="6"><span class="en">has current or former residence (is current or former residence of) </span><code class="language-plaintext highlighter-rouge">P74_a_pour_résidence_actuelle_ou_antérieure (est_la_résidence_actuelle_ou_antérieure_de)</code></td>
      <td><span class="en">E39 Actor </span><code class="language-plaintext highlighter-rouge">E39_Actant</code></td>
      <td><span class="en">E53 Place </span><code class="language-plaintext highlighter-rouge">E53_Lieu</code></td>
    </tr>
    <tr>
      <td>P75</td>
      <td colspan="6"><span class="en">possesses (is possessed by) </span><code class="language-plaintext highlighter-rouge">P75_possède (est_possédé_par)</code></td>
      <td><span class="en">E39 Actor </span><code class="language-plaintext highlighter-rouge">E39_Actant</code></td>
      <td><span class="en">E30 Right </span><code class="language-plaintext highlighter-rouge">E30_Droit</code></td>
    </tr>
    <tr>
      <td>P76</td>
      <td colspan="6"><span class="en">has contact point (provides access to) </span><code class="language-plaintext highlighter-rouge">P76_a_pour_coordonnées (permet_de_contacter)</code></td>
      <td><span class="en">E39 Actor </span><code class="language-plaintext highlighter-rouge">E39_Actant</code></td>
      <td><span class="en">E41 Appellation </span><code class="language-plaintext highlighter-rouge">E41_Appellation</code></td>
    </tr>
    <tr>
      <td>P81</td>
      <td colspan="6"><span class="en">ongoing throughout </span><code class="language-plaintext highlighter-rouge">P81_a_couvert</code></td>
      <td><span class="en">E52 Time-Span </span><code class="language-plaintext highlighter-rouge">E52_Intervalle_temporel </code></td>
      <td><span class="en">E61 Time Primitive </span><code class="language-plaintext highlighter-rouge">E61_Primitive_temporelle</code></td>
    </tr>
    <tr>
      <td>P82</td>
      <td colspan="6"><span class="en">at some time within </span><code class="language-plaintext highlighter-rouge">P82_a_eu_lieu_durant</code></td>
      <td><span class="en">E52 Time-Span </span><code class="language-plaintext highlighter-rouge">E52_Intervalle_temporel </code></td>
      <td><span class="en">E61 Time Primitive </span><code class="language-plaintext highlighter-rouge">E61_Primitive_temporelle</code></td>
    </tr>
    <tr>
      <td>P86</td>
      <td colspan="6"><span class="en">falls within (contains) </span><code class="language-plaintext highlighter-rouge">P86_s’insère_dans (contient)</code></td>
      <td><span class="en">E52 Time-Span </span><code class="language-plaintext highlighter-rouge">E52_Intervalle_temporel </code></td>
      <td><span class="en">E52 Time-Span </span><code class="language-plaintext highlighter-rouge">E52_Intervalle_temporel </code></td>
    </tr>
    <tr>
      <td>P89</td>
      <td colspan="6"><span class="en">falls within (contains) </span><code class="language-plaintext highlighter-rouge">P89_s’insère_dans (contient)</code></td>
      <td><span class="en">E53 Place </span><code class="language-plaintext highlighter-rouge">E53_Lieu</code></td>
      <td><span class="en">E53 Place </span><code class="language-plaintext highlighter-rouge">E53_Lieu</code></td>
    </tr>
    <tr>
      <td>P90</td>
      <td colspan="6"><span class="en">has value </span><code class="language-plaintext highlighter-rouge">P90_a_pour_valeur</code></td>
      <td><span class="en">E54 Dimension </span><code class="language-plaintext highlighter-rouge">E54_Dimension</code></td>
      <td><span class="en">E60 Number </span><code class="language-plaintext highlighter-rouge">E60_Nombre</code></td>
    </tr>
    <tr>
      <td>P91</td>
      <td colspan="6"><span class="en">has unit (is unit of) </span><code class="language-plaintext highlighter-rouge">P91_a_pour_unité_de_mesure (est_l’unité_de_mesure_de)</code></td>
      <td><span class="en">E54 Dimension </span><code class="language-plaintext highlighter-rouge">E54_Dimension</code></td>
      <td><span class="en">E58 Measurement Unit </span><code class="language-plaintext highlighter-rouge">E58_Unité_de_mesure</code></td>
    </tr>
    <tr>
      <td>P180</td>
      <td>-</td>
      <td colspan="5"><span class="en">has currency </span><code class="language-plaintext highlighter-rouge">P180a_pour_unité_monétaire (était_l'unité_monétaire_de)</code></td>
      <td><span class="en">E97 Monetary Amount </span><code class="language-plaintext highlighter-rouge">E97_Valeur_monétaire</code></td>
      <td><span class="en">E98 Currency </span><code class="language-plaintext highlighter-rouge">E98_Unité_monétaire</code></td>
    </tr>
    <tr>
      <td>P97</td>
      <td colspan="6"><span class="en">from father (was father for) </span><code class="language-plaintext highlighter-rouge">P97_de_père (a_été_le_père_pour)</code></td>
      <td><span class="en">E67 Birth </span><code class="language-plaintext highlighter-rouge">E67_Naissance</code></td>
      <td><span class="en">E21 Person </span><code class="language-plaintext highlighter-rouge">E21_Personne</code></td>
    </tr>
    <tr>
      <td>P101</td>
      <td colspan="6"><span class="en">had as general use (was use of) </span><code class="language-plaintext highlighter-rouge">P101_a_eu_pour_usage_général (a_été_l’usage_général_de)</code></td>
      <td><span class="en">E70 Thing </span><code class="language-plaintext highlighter-rouge">E70_Chose</code></td>
      <td><span class="en">E55 Type </span><code class="language-plaintext highlighter-rouge">E55_Type</code></td>
    </tr>
    <tr>
      <td>P103</td>
      <td colspan="6"><span class="en">was intended for (was intention of) </span><code class="language-plaintext highlighter-rouge">P103_a_eu_pour_raison_d’être (a_été_la_raison_d’être_de)</code></td>
      <td><span class="en">E71 Human-Made Thing </span><code class="language-plaintext highlighter-rouge">E71_Chose_élaborée_par_l’humain</code></td>
      <td><span class="en">E55 Type </span><code class="language-plaintext highlighter-rouge">E55_Type</code></td>
    </tr>
    <tr>
      <td>P104</td>
      <td colspan="6"><span class="en">is subject to (applies to) </span><code class="language-plaintext highlighter-rouge">P104_est_soumis_à (s’applique_à)</code></td>
      <td><span class="en">E72 Legal Object </span><code class="language-plaintext highlighter-rouge">E72_Objet_juridique</code></td>
      <td><span class="en">E30 Right </span><code class="language-plaintext highlighter-rouge">E30_Droit</code></td>
    </tr>
    <tr>
      <td>P105</td>
      <td colspan="6"><span class="en">right held by (has right on) </span><code class="language-plaintext highlighter-rouge">P105_droit_détenu_par (détient_le_droit_sur)</code></td>
      <td><span class="en">E72 Legal Object </span><code class="language-plaintext highlighter-rouge">E72_Objet_juridique</code></td>
      <td><span class="en">E39 Actor </span><code class="language-plaintext highlighter-rouge">E39_Actant</code></td>
    </tr>
    <tr>
      <td>P52</td>
      <td>-</td>
      <td colspan="5"><span class="en">has current owner (is current owner of) </span><code class="language-plaintext highlighter-rouge">P52_a_pour_propriétaire_actuel (est_l’actant_propriétaire_actuel_de)</code></td>
      <td><span class="en">E18 Physical Thing </span><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></td>
      <td><span class="en">E39 Actor </span><code class="language-plaintext highlighter-rouge">E39_Actant</code></td>
    </tr>
    <tr>
      <td>P106</td>
      <td colspan="6"><span class="en">is composed of (forms part of) </span><code class="language-plaintext highlighter-rouge">P106_est_composé_de (fait_partie_de)</code></td>
      <td><span class="en">E90 Symbolic Object </span><code class="language-plaintext highlighter-rouge">E90_Objet_symbolique</code></td>
      <td><span class="en">E90 Symbolic Object </span><code class="language-plaintext highlighter-rouge">E90_Objet_symbolique</code></td>
    </tr>
    <tr>
      <td>P165</td>
      <td>-</td>
      <td colspan="5"><span class="en">incorporates (is incorporated in) </span><code class="language-plaintext highlighter-rouge">P165_inclut (est_inclus_dans)</code></td>
      <td><span class="en">E73 Information Object </span><code class="language-plaintext highlighter-rouge">E73_Objet_informationnel</code></td>
      <td><span class="en">E90 Symbolic Object </span><code class="language-plaintext highlighter-rouge">E90_Objet_symbolique</code></td>
    </tr>
    <tr>
      <td>P107</td>
      <td colspan="6"><span class="en">has current or former member (is current or former member of) </span><code class="language-plaintext highlighter-rouge">P107_a_pour_membre_actuel_ou_antérieur (est_le_membre_actuel_ou_antérieur_de)</code></td>
      <td><span class="en">E74 Group </span><code class="language-plaintext highlighter-rouge">E74_Groupe</code></td>
      <td><span class="en">E39 Actor </span><code class="language-plaintext highlighter-rouge">E39_Actant</code></td>
    </tr>
    <tr>
      <td>P121</td>
      <td colspan="6"><span class="en">overlaps with </span><code class="language-plaintext highlighter-rouge">P121_se_superpose_partiellement_à</code></td>
      <td><span class="en">E53 Place </span><code class="language-plaintext highlighter-rouge">E53_Lieu</code></td>
      <td><span class="en">E53 Place </span><code class="language-plaintext highlighter-rouge">E53_Lieu</code></td>
    </tr>
    <tr>
      <td>P122</td>
      <td colspan="6"><span class="en">borders with </span><code class="language-plaintext highlighter-rouge">P122_est_limitrophe_de</code></td>
      <td><span class="en">E53 Place </span><code class="language-plaintext highlighter-rouge">E53_Lieu</code></td>
      <td><span class="en">E53 Place </span><code class="language-plaintext highlighter-rouge">E53_Lieu</code></td>
    </tr>
    <tr>
      <td>P125</td>
      <td colspan="6"><span class="en">used object of type (was type of object used in) </span><code class="language-plaintext highlighter-rouge">P125_a_mobilisé_l’objet_du_type (a_été_le_type_d’objet_employé_pour)</code></td>
      <td><span class="en">E7 Activity </span><code class="language-plaintext highlighter-rouge">E7_Activité</code></td>
      <td><span class="en">E55 Type </span><code class="language-plaintext highlighter-rouge">E55_Type</code></td>
    </tr>
    <tr>
      <td>P32</td>
      <td>-</td>
      <td colspan="5"><span class="en">used general technique (was technique of) </span><code class="language-plaintext highlighter-rouge">P32_a_mobilisé_comme_technique_générale (a_été_la_technique_générale_mise_en_œuvre_dans)</code></td>
      <td><span class="en">E7 Activity </span><code class="language-plaintext highlighter-rouge">E7_Activité</code></td>
      <td><span class="en">E55 Type </span><code class="language-plaintext highlighter-rouge">E55_Type</code></td>
    </tr>
    <tr>
      <td>P126</td>
      <td colspan="6"><span class="en">employed (was employed in) </span><code class="language-plaintext highlighter-rouge">P126_a_employé (a_été_employé_dans)</code></td>
      <td><span class="en">E11 Modification </span><code class="language-plaintext highlighter-rouge">E11_Modification</code></td>
      <td><span class="en">E57 Material </span><code class="language-plaintext highlighter-rouge">E57_Matériau</code></td>
    </tr>
    <tr>
      <td>P127</td>
      <td colspan="6"><span class="en">has broader term (has narrower term) </span><code class="language-plaintext highlighter-rouge">P127_a_pour_terme_général (a_pour_terme_spécifique)</code></td>
      <td><span class="en">E55 Type </span><code class="language-plaintext highlighter-rouge">E55_Type</code></td>
      <td><span class="en">E55 Type </span><code class="language-plaintext highlighter-rouge">E55_Type</code></td>
    </tr>
    <tr>
      <td>P130</td>
      <td colspan="6"><span class="en">shows freatures of (features are also found on) </span><code class="language-plaintext highlighter-rouge">P130_présente_les_caractéristiques_de (a_les_caractéristiques_aussi_présentes_sur)</code></td>
      <td><span class="en">E70 Thing </span><code class="language-plaintext highlighter-rouge">E70_Chose</code></td>
      <td><span class="en">E70 Thing </span><code class="language-plaintext highlighter-rouge">E70_Chose</code></td>
    </tr>
    <tr>
      <td>P73i</td>
      <td>-</td>
      <td colspan="5"><span class="en">is translation of </span><code class="language-plaintext highlighter-rouge">P73i_est_traduction_de</code></td>
      <td><span class="en">E33 Linguistic Object </span><code class="language-plaintext highlighter-rouge">E33_Objet_linguistique</code></td>
      <td><span class="en">E33 Linguistic Object </span><code class="language-plaintext highlighter-rouge">E33_Objet_linguistique</code></td>
    </tr>
    <tr>
      <td>P128</td>
      <td>-</td>
      <td colspan="5"><span class="en">carries (is carried by) </span><code class="language-plaintext highlighter-rouge">P128_est_le_support_de (a_pour_support)</code></td>
      <td><span class="en">E18 Physical Thing </span><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></td>
      <td><span class="en">E90 Symbolic Object </span><code class="language-plaintext highlighter-rouge">E90_Objet_symbolique</code></td>
    </tr>
    <tr>
      <td>P65</td>
      <td>-</td>
      <td> </td>
      <td colspan="4"><span class="en">shows visual item (is shown by) </span><code class="language-plaintext highlighter-rouge">P65_représente_l’entité_visuelle (est_représenté_par)</code></td>
      <td><span class="en">E24 Physical Human-Made Thing </span><code class="language-plaintext highlighter-rouge">E24_Chose_matérielle_élaborée_par_l’humain </code></td>
      <td><span class="en">E36 Visual Item </span><code class="language-plaintext highlighter-rouge">E36_Entité_visuelle</code></td>
    </tr>
    <tr>
      <td>P132</td>
      <td colspan="6"><span class="en">spatiotemporally ocerlaps with </span><code class="language-plaintext highlighter-rouge">P132_recoupe_spatio-temporellement</code></td>
      <td><span class="en">E92 Spacetime Volume </span><code class="language-plaintext highlighter-rouge">E92_Volume_spatio-temporel</code></td>
      <td><span class="en">E92 Spacetime Volume </span><code class="language-plaintext highlighter-rouge">E92_Volume_spatio-temporel</code></td>
    </tr>
    <tr>
      <td>P10</td>
      <td>-</td>
      <td colspan="5"><span class="en">falls within (contains) </span><code class="language-plaintext highlighter-rouge">P10_s’insère_dans (contient)</code></td>
      <td><span class="en">E92 Spacetime Volume </span><code class="language-plaintext highlighter-rouge">E92_Volume_spatio-temporel</code></td>
      <td><span class="en">E92 Spacetime Volume </span><code class="language-plaintext highlighter-rouge">E92_Volume_spatio-temporel</code></td>
    </tr>
    <tr>
      <td>P166</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">was a presence of (has presence) </span><code class="language-plaintext highlighter-rouge">P166_a_été_une_présence_de (a_eu_pour_présence)</code></td>
      <td><span class="en">E93 Presence </span><code class="language-plaintext highlighter-rouge">E93_Présence</code></td>
      <td><span class="en">E92 Spacetime Volume </span><code class="language-plaintext highlighter-rouge">E92_Volume_spatio-temporel</code></td>
    </tr>
    <tr>
      <td>P46</td>
      <td colspan="6"><span class="en">is composed of (forms part of) </span><code class="language-plaintext highlighter-rouge">P46_est_composé_de (fait_partie_de)</code></td>
      <td><span class="en">E18 Physical Thing </span><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></td>
      <td><span class="en">E18 Physical Thing </span><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></td>
    </tr>
    <tr>
      <td>P56</td>
      <td>-</td>
      <td colspan="5"><span class="en">bears feature (is found on) </span><code class="language-plaintext highlighter-rouge">P56_a_pour_caractéristique (se_trouve_sur)</code></td>
      <td><span class="en">E19 Physical Object </span><code class="language-plaintext highlighter-rouge">E19_Objet_matériel</code></td>
      <td><span class="en">E26 Physical Feature </span><code class="language-plaintext highlighter-rouge">E26_Caractéristique_physique</code></td>
    </tr>
    <tr>
      <td>P133</td>
      <td colspan="6"><span class="en">is separated from </span><code class="language-plaintext highlighter-rouge">P133_est_distinct_spatio-temporellement_de</code></td>
      <td><span class="en">E92 Spacetime Volume </span><code class="language-plaintext highlighter-rouge">E92_Volume_spatio-temporel</code></td>
      <td><span class="en">E92 Spacetime Volume </span><code class="language-plaintext highlighter-rouge">E92_Volume_spatio-temporel</code></td>
    </tr>
    <tr>
      <td>P139</td>
      <td colspan="6"><span class="en">has alternative form </span><code class="language-plaintext highlighter-rouge">P139_a_pour_forme_alternative</code></td>
      <td><span class="en">E41 Appellation </span><code class="language-plaintext highlighter-rouge">E41_Appellation</code></td>
      <td><span class="en">E41 Appellation </span><code class="language-plaintext highlighter-rouge">E41_Appellation</code></td>
    </tr>
    <tr>
      <td>P140</td>
      <td colspan="6"><span class="en">assigned attribute to (was attributed by) </span><code class="language-plaintext highlighter-rouge">P140_a_assigné_l’attribut_à (a_reçu_l’attribut_par)</code></td>
      <td><span class="en">E13 Attribute Assignment </span><code class="language-plaintext highlighter-rouge">E13_Assignation_d’attribut</code></td>
      <td><span class="en">E1 CRM Entity </span><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></td>
    </tr>
    <tr>
      <td>P34</td>
      <td> </td>
      <td colspan="5"><span class="en">concerned (was assessed by) </span><code class="language-plaintext highlighter-rouge">P34_a_porté_sur (a_été_évalué_par)</code></td>
      <td><span class="en">E14 Condition Assessment </span><code class="language-plaintext highlighter-rouge">E14_Évaluation_d’état_matériel</code></td>
      <td><span class="en">E18 Physical Thing </span><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></td>
    </tr>
    <tr>
      <td>P39</td>
      <td> </td>
      <td colspan="5"><span class="en">measured (was measured by) </span><code class="language-plaintext highlighter-rouge">P39_a_mesuré (a_été_mesuré_par)</code></td>
      <td><span class="en">E16 Measurement </span><code class="language-plaintext highlighter-rouge">E16_Mesurage</code></td>
      <td><span class="en">E1 CRM Entity </span><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></td>
    </tr>
    <tr>
      <td>P41</td>
      <td> </td>
      <td colspan="5"><span class="en">classified (was classified by) </span><code class="language-plaintext highlighter-rouge">P41_a_classifié (a_été_classifié_par)</code></td>
      <td><span class="en">E17 Type Assignment </span><code class="language-plaintext highlighter-rouge">E17_Assignation_de_type</code></td>
      <td><span class="en">E1 CRM Entity </span><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></td>
    </tr>
    <tr>
      <td>P141</td>
      <td colspan="6"><span class="en">assigned (was assigned by) </span><code class="language-plaintext highlighter-rouge">P141_a_assigné (a_été_assigné_par)</code></td>
      <td><span class="en">E13 Attribute Assignment </span><code class="language-plaintext highlighter-rouge">E13_Assignation_d’attribut</code></td>
      <td><span class="en">E1 CRM Entity </span><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></td>
    </tr>
    <tr>
      <td>P35</td>
      <td>-</td>
      <td colspan="5"><span class="en">has identified (identified by) </span><code class="language-plaintext highlighter-rouge">P35_a_identifié (a_été_identifié_par)</code></td>
      <td><span class="en">E14 Condition Assessment </span><code class="language-plaintext highlighter-rouge">E14_Évaluation_d’état_matériel</code></td>
      <td><span class="en">E3 Condition State </span><code class="language-plaintext highlighter-rouge">E3_État_matériel</code></td>
    </tr>
    <tr>
      <td>P37</td>
      <td>-</td>
      <td colspan="5"><span class="en">assigned (was assigned by) </span><code class="language-plaintext highlighter-rouge">P37_a_assigné (a_été_assigné_par)</code></td>
      <td><span class="en">E15 Identifier Assignment </span><code class="language-plaintext highlighter-rouge">E15_Assignation_d’identifiant</code></td>
      <td><span class="en">E42 identifier </span><code class="language-plaintext highlighter-rouge">E42_Identifiant</code></td>
    </tr>
    <tr>
      <td>P38</td>
      <td>-</td>
      <td colspan="5"><span class="en">deassigned (was designed by) </span><code class="language-plaintext highlighter-rouge">P38_a_retiré_l’assignation_de (a_été_retiré_par)</code></td>
      <td><span class="en">E15 Identifier Assignment </span><code class="language-plaintext highlighter-rouge">E15_Assignation_d’identifiant</code></td>
      <td><span class="en">E42 identifier </span><code class="language-plaintext highlighter-rouge">E42_Identifiant</code></td>
    </tr>
    <tr>
      <td>P40</td>
      <td>-</td>
      <td colspan="5"><span class="en">observed dimension (was observed in) </span><code class="language-plaintext highlighter-rouge">P40_a_relevé_comme_dimension (a_été_relevé_par)</code></td>
      <td><span class="en">E16 Measurement </span><code class="language-plaintext highlighter-rouge">E16_Mesurage</code></td>
      <td><span class="en">E54 Dimension </span><code class="language-plaintext highlighter-rouge">E54_Dimension</code></td>
    </tr>
    <tr>
      <td>P42</td>
      <td>-</td>
      <td colspan="5"><span class="en">assigned (was assigned by) </span><code class="language-plaintext highlighter-rouge">P42_a_assigné (a_été_assigné_par)</code></td>
      <td><span class="en">E17 Type Assignment </span><code class="language-plaintext highlighter-rouge">E17_Assignation_de_type</code></td>
      <td><span class="en">E55 Type </span><code class="language-plaintext highlighter-rouge">E55_Type</code></td>
    </tr>
    <tr>
      <td>P147</td>
      <td colspan="6"><span class="en">curated (was curated by) </span><code class="language-plaintext highlighter-rouge">P147_a_géré (a_été_géré_par)</code></td>
      <td><span class="en">E87 Curation Activity </span><code class="language-plaintext highlighter-rouge">E87_Activité_curatoriale</code></td>
      <td><span class="en">E78 Curated Holding </span><code class="language-plaintext highlighter-rouge">E78_Collection</code></td>
    </tr>
    <tr>
      <td>P148</td>
      <td colspan="6"><span class="en">has component (is component of) </span><code class="language-plaintext highlighter-rouge">P148_a_pour_composant (est_le_composant_de)</code></td>
      <td><span class="en">E89 Propositional Object </span><code class="language-plaintext highlighter-rouge">E89_Objet_propositionnel</code></td>
      <td><span class="en">E89 Propositional Object </span><code class="language-plaintext highlighter-rouge">E89_Objet_propositionnel</code></td>
    </tr>
    <tr>
      <td>P150</td>
      <td colspan="6"><span class="en">defines typical parts of (defines typical wholes for) </span><code class="language-plaintext highlighter-rouge">P150_définit_les_éléments_typiques_de (définit_l’ensemble_typique_pour)</code></td>
      <td><span class="en">E55 Type </span><code class="language-plaintext highlighter-rouge">E55_Type</code></td>
      <td><span class="en">E55 Type </span><code class="language-plaintext highlighter-rouge">E55_Type</code></td>
    </tr>
    <tr>
      <td>P152</td>
      <td colspan="6"><span class="en">has parent (is parent of) </span><code class="language-plaintext highlighter-rouge">P152_a_pour_parent (est_le_parent_de)</code></td>
      <td><span class="en">E21 Person </span><code class="language-plaintext highlighter-rouge">E21_Personne</code></td>
      <td><span class="en">E21 Person </span><code class="language-plaintext highlighter-rouge">E21_Personne</code></td>
    </tr>
    <tr>
      <td>P157</td>
      <td colspan="6"><span class="en">is at rest relative to (provides reference space for) </span><code class="language-plaintext highlighter-rouge">P157_est_à_l’arrêt_par_rapport_à (procure_l’espace_de_référence_pour)</code></td>
      <td><span class="en">E53 Place </span><code class="language-plaintext highlighter-rouge">E53_Lieu</code></td>
      <td><span class="en">E18 Physical Thing </span><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></td>
    </tr>
    <tr>
      <td>P59i</td>
      <td>-</td>
      <td colspan="5"><span class="en">is located on or within </span><code class="language-plaintext highlighter-rouge">P59i_se_situe_sur_ou_dans</code></td>
      <td><span class="en">E53 Place </span><code class="language-plaintext highlighter-rouge">E53_Lieu</code></td>
      <td><span class="en">E18 Physical Thing </span><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></td>
    </tr>
    <tr>
      <td>P156i</td>
      <td>-</td>
      <td colspan="5"><span class="en">is occupied by </span><code class="language-plaintext highlighter-rouge">P156i_est_occupé_par</code></td>
      <td><span class="en">E53 Place </span><code class="language-plaintext highlighter-rouge">E53_Lieu</code></td>
      <td><span class="en">E18 Physical Thing </span><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></td>
    </tr>
    <tr>
      <td>P160</td>
      <td colspan="6"><span class="en">has temporal projection </span><code class="language-plaintext highlighter-rouge">P160_a_pour_projection_temporelle (est_la_projection_temporelle_de)</code></td>
      <td><span class="en">E92 Spacetime Volume </span><code class="language-plaintext highlighter-rouge">E92_Volume_spatio-temporel</code></td>
      <td><span class="en">E52 Time-Span </span><code class="language-plaintext highlighter-rouge">E52_Intervalle_temporel </code></td>
    </tr>
    <tr>
      <td>P164</td>
      <td>-</td>
      <td colspan="5"><span class="en">is temporally specified by (temporally specifies) </span><code class="language-plaintext highlighter-rouge">P164_est_temporellement_spécifié_par (spécifie_temporellement)</code></td>
      <td><span class="en">E93 Presence </span><code class="language-plaintext highlighter-rouge">E93_Présence</code></td>
      <td><span class="en">E52 Time-Span </span><code class="language-plaintext highlighter-rouge">E52_Intervalle_temporel </code></td>
    </tr>
    <tr>
      <td>P161</td>
      <td colspan="6"><span class="en">has spatial projection </span><code class="language-plaintext highlighter-rouge">P161_a_pour_projection_spatiale (est_la_projection_spatiale_de)</code></td>
      <td><span class="en">E92 Spacetime Volume </span><code class="language-plaintext highlighter-rouge">E92_Volume_spatio-temporel</code></td>
      <td><span class="en">E53 Place </span><code class="language-plaintext highlighter-rouge">E53_Lieu</code></td>
    </tr>
    <tr>
      <td>P167</td>
      <td colspan="6"><span class="en">was within (includes) </span><code class="language-plaintext highlighter-rouge">P167_s’inscrivait_dans (comporte)</code></td>
      <td><span class="en">E93 Presence </span><code class="language-plaintext highlighter-rouge">E93_Présence</code></td>
      <td><span class="en">E53 Place </span><code class="language-plaintext highlighter-rouge">E53_Lieu</code></td>
    </tr>
    <tr>
      <td>P171</td>
      <td colspan="6"><span class="en">at some place within </span><code class="language-plaintext highlighter-rouge">P171_quelque_part_dans</code></td>
      <td><span class="en">E53 Place </span><code class="language-plaintext highlighter-rouge">E53_Lieu</code></td>
      <td><span class="en">E94 Space Primitive </span><code class="language-plaintext highlighter-rouge">E94_Primitive_spatiale</code></td>
    </tr>
    <tr>
      <td>P172</td>
      <td colspan="6"><span class="en">contains </span><code class="language-plaintext highlighter-rouge">P172_contient</code></td>
      <td><span class="en">E53 Place </span><code class="language-plaintext highlighter-rouge">E53_Lieu</code></td>
      <td><span class="en">E94 Space Primitive </span><code class="language-plaintext highlighter-rouge">E94_Primitive_spatiale</code></td>
    </tr>
    <tr>
      <td>P173</td>
      <td colspan="6"><span class="en">starts before or with the end of (ends after the start of) </span><code class="language-plaintext highlighter-rouge">P173_commence_avant_ou_au_moment_de_la_fin_de (se_termine_après_ou_au_moment_du_début_de)</code></td>
      <td><span class="en">E2 Temporal Entity </span><code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code></td>
      <td><span class="en">E2 Temporal Entity </span><code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code></td>
    </tr>
    <tr>
      <td>P174</td>
      <td>-</td>
      <td colspan="5"><span class="en">starts before the end of (ends after the start of) </span><code class="language-plaintext highlighter-rouge">P174_commence_avant_la_fin_de (se_termine_après_le_début_de)</code></td>
      <td><span class="en">E2 Temporal Entity </span><code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code></td>
      <td><span class="en">E2 Temporal Entity </span><code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code></td>
    </tr>
    <tr>
      <td>P184</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">ends before or with the end of (ends with or after the end of) </span><code class="language-plaintext highlighter-rouge">P184_se_termine_avant_ou_au_moment_de_la_fin_de (se_termine_au_moment_ou_après_la_fin_de)</code></td>
      <td><span class="en">E2 Temporal Entity </span><code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code></td>
      <td><span class="en">E2 Temporal Entity </span><code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code></td>
    </tr>
    <tr>
      <td>P185</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="3"><span class="en">ends before the end of (ends after the end of) </span><code class="language-plaintext highlighter-rouge">P185_se_termine_avant_la_fin_de (se_termine_après_la_fin_de) </code></td>
      <td><span class="en">E2 Temporal Entity </span><code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code></td>
      <td><span class="en">E2 Temporal Entity </span><code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code></td>
    </tr>
    <tr>
      <td>P182</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="2"><span class="en">ends before or at the start of (starts after or with the start of) </span><code class="language-plaintext highlighter-rouge">P182_se_termine_avant_ou_au_moment_du_début_de (commence_après_ou_au_moment_de_la_fin_de)</code></td>
      <td><span class="en">E2 Temporal Entity </span><code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code></td>
      <td><span class="en">E2 Temporal Entity </span><code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code></td>
    </tr>
    <tr>
      <td>P175</td>
      <td>-</td>
      <td>-</td>
      <td colspan="4"><span class="en">starts before or with the start of (starts after or with the start of) </span><code class="language-plaintext highlighter-rouge">P175_commence_avant_ou_au_moment_du_début_de (commence_après_ou_au_moment_du_début_de)</code></td>
      <td><span class="en">E2 Temporal Entity </span><code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code></td>
      <td><span class="en">E2 Temporal Entity </span><code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code></td>
    </tr>
    <tr>
      <td>P176</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="3"><span class="en">starts before the start of (starts after the start of) </span><code class="language-plaintext highlighter-rouge">P176_commence_avant_le_début_de (commence_après_le_début_de)</code></td>
      <td><span class="en">E2 Temporal Entity </span><code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code></td>
      <td><span class="en">E2 Temporal Entity </span><code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code></td>
    </tr>
    <tr>
      <td>P134i</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="2"><em><span class="en">was continued by </span><code class="language-plaintext highlighter-rouge">P134_a_été_continué_par</code></em></td>
      <td><em><span class="en">E7 Activity </span><code class="language-plaintext highlighter-rouge">E7_Activité</code></em></td>
      <td><em><span class="en">E7 Activity </span><code class="language-plaintext highlighter-rouge">E7_Activité</code></em></td>
    </tr>
    <tr>
      <td>P182</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="2"><em><span class="en">ends before or at the start of (starts after or with the end of) </span><code class="language-plaintext highlighter-rouge">P182_se_termine_avant_ou_au_moment_du_début_de (commence_après_ou_au_moment_de_la_fin_de)</code></em></td>
      <td><em><span class="en">E2 Temporal Entity </span><code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code></em></td>
      <td><em><span class="en">E2 Temporal Entity </span><code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code></em></td>
    </tr>
    <tr>
      <td>P183</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td>-</td>
      <td colspan="1"><em><span class="en">ends before the start of (starts after the end of) </span><code class="language-plaintext highlighter-rouge">P183_se_termine_avant_le_début_de (commence_après_la_fin_de)</code></em></td>
      <td><em><span class="en">E2 Temporal Entity </span><code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code></em></td>
      <td><em><span class="en">E2 Temporal Entity </span><code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code></em></td>
    </tr>
    <tr>
      <td>P179</td>
      <td colspan="6"><span class="en">had sales price (was sales price of) </span><code class="language-plaintext highlighter-rouge">P179_a_eu_pour_prix_de_vente (a_été_le_prix_de_vente_de)</code></td>
      <td><span class="en">E96 Purchase </span><code class="language-plaintext highlighter-rouge">E96_Achat</code></td>
      <td><span class="en">E97 Monetary Amount </span><code class="language-plaintext highlighter-rouge">E97_Valeur_monétaire</code></td>
    </tr>
    <tr>
      <td>P186</td>
      <td colspan="6"><span class="en">produced thing of product type (is produced by) </span><code class="language-plaintext highlighter-rouge">P186_a_produit_la_chose_du_type (est_produit_par)</code></td>
      <td><span class="en">E12 Production </span><code class="language-plaintext highlighter-rouge">E12_Production</code></td>
      <td><span class="en">E99 Product Type </span><code class="language-plaintext highlighter-rouge">E99_Modèle_de_produit</code></td>
    </tr>
    <tr>
      <td>P187</td>
      <td colspan="6"><span class="en">has production plan (is production plan for) </span> <code class="language-plaintext highlighter-rouge">P187_a_pour_plan_de_production (est_le_plan_de_production_de)</code></td>
      <td><span class="en">E99 Product Type </span><code class="language-plaintext highlighter-rouge">E99_Modèle_de_produit</code></td>
      <td><span class="en">E29 Deisgn or Procedure </span><code class="language-plaintext highlighter-rouge">E29_Conceptualisation_ou_procédure</code></td>
    </tr>
    <tr>
      <td>P188</td>
      <td colspan="6"><span class="en">requires production tool (is production tool for) </span> <code class="language-plaintext highlighter-rouge">P188_nécessite_l’outil (est_l’outil_de_production_de) </code></td>
      <td><span class="en">E99 Product Type </span><code class="language-plaintext highlighter-rouge">E99_Modèle_de_produit</code></td>
      <td><span class="en">E19 Physical Object </span><code class="language-plaintext highlighter-rouge">E19_Objet_matériel</code></td>
    </tr>
    <tr>
      <td>P189</td>
      <td colspan="6"><span class="en">approximates </span><code class="language-plaintext highlighter-rouge">P189_approxime (est_approximé_par)</code></td>
      <td><span class="en">E53 Place </span><code class="language-plaintext highlighter-rouge">E53_Lieu</code></td>
      <td><span class="en">E53 Place </span><code class="language-plaintext highlighter-rouge">E53_Lieu</code></td>
    </tr>
    <tr>
      <td>P191</td>
      <td colspan="6"><span class="en">had duration (was duration of) </span><code class="language-plaintext highlighter-rouge">P191_a_eu_pour_durée (était_la_durée_de)</code></td>
      <td><span class="en">E52 Time-Span </span><code class="language-plaintext highlighter-rouge">E52_Intervalle_temporel </code></td>
      <td><span class="en">E54 Dimension </span><code class="language-plaintext highlighter-rouge">E54_Dimension</code></td>
    </tr>
    <tr>
      <td>P195</td>
      <td colspan="6"><span class="en">was a presence of (has presence) </span><code class="language-plaintext highlighter-rouge">P195_a_été_une_présence_de (a_eu_pour_présence) </code></td>
      <td><span class="en">E93 Presence </span><code class="language-plaintext highlighter-rouge">E93_Présence</code></td>
      <td><span class="en">E18 Physical Thing </span><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></td>
    </tr>
    <tr>
      <td>P196</td>
      <td colspan="6"><span class="en">defines (is defined by) </span><code class="language-plaintext highlighter-rouge">P196_définit (est_défini_par)</code></td>
      <td><span class="en">E18 Physical Thing </span><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></td>
      <td><span class="en">E92 Spacetime Volume </span><code class="language-plaintext highlighter-rouge">E92_Volume_spatio-temporel</code></td>
    </tr>
    <tr>
      <td>P197</td>
      <td colspan="6"><span class="en">covered parts of (was partially covered by) </span><code class="language-plaintext highlighter-rouge">197_a_couvert_des_parties_de (a_été_partiellement_couvert_par)</code></td>
      <td><span class="en">E93 Presence </span><code class="language-plaintext highlighter-rouge">E93_Présence</code></td>
      <td><span class="en">E53 Place </span><code class="language-plaintext highlighter-rouge">E53_Lieu</code></td>
    </tr>
    <tr>
      <td>P198</td>
      <td colspan="6"><span class="en">holds or supports (is held or supported by) </span><code class="language-plaintext highlighter-rouge">P198_contient_ou_soutient (est_contenu_ou_soutenu_par)</code></td>
      <td><span class="en">E18 Physical Thing </span><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></td>
      <td><span class="en">E18 Physical Thing </span><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></td>
    </tr>
  </tbody>
</table>

<h3 id="proprietes-de-proprietes-du-cidoc-crm-proprietes-1"><span class="en heading">CIDOC CRM Properties of Properties (.1 Properties) - </span>Propriétés de propriétés du CIDOC CRM (propriétés .1)</h3>

<table id="cidoc-crm-properties-of-properties-table">
  <tbody>
    <tr>
      <td><strong><span class="en">Property id - </span>Identifiant unique de propriété</strong></td>
      <td colspan="2"><strong><span class="en">Property Name - </span>Nom de la propriété</strong></td>
      <td><strong><span class="en">Property Domain - </span>Domaine</strong></td>
      <td><strong><span class="en">Entity Range - </span>Portée</strong></td>
    </tr>
    <tr>
      <td>P3.1</td>
      <td colspan="2"><span class="en">has type </span><code class="language-plaintext highlighter-rouge">P3.1_a_pour_type</code></td>
      <td><span class="en">E1 CRM Entity. <strong>P3 has note</strong>: E62 String </span><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code>. <code class="language-plaintext highlighter-rouge"><strong>P3_a_pour_note</strong></code> : <code class="language-plaintext highlighter-rouge">E62_Chaîne_de_caractères</code></td>
      <td><span class="en">E55 Type </span><code class="language-plaintext highlighter-rouge">E55_Type</code></td>
    </tr>
    <tr>
      <td>P14.1</td>
      <td colspan="2"><span class="en">in the role of </span><code class="language-plaintext highlighter-rouge">P14.1_dans_le_rôle_de</code></td>
      <td><span class="en">E7 Activity. <strong>P14 carried out by (performed)</strong>: E39 Actor </span><code class="language-plaintext highlighter-rouge">E7_Activité</code>. <code class="language-plaintext highlighter-rouge"><strong>P14_a_été_effectué_par (a_effectué)</strong></code> : <code class="language-plaintext highlighter-rouge">E39_Actant</code></td>
      <td><span class="en">E55 Type </span><code class="language-plaintext highlighter-rouge">E55_Type</code></td>
    </tr>
    <tr>
      <td>P16.1</td>
      <td colspan="2"><span class="en">mode of use </span><code class="language-plaintext highlighter-rouge">P16.1_mode_d’utilisation</code></td>
      <td><span class="en">E7 Activity. <strong>P16 used specific object (was used for)</strong>: E70 Thing </span><code class="language-plaintext highlighter-rouge">E7_Activité</code>. <code class="language-plaintext highlighter-rouge"><strong>P16_a_mobilisé_l’objet_spécifique (a_été_mobilisé_pour)</strong></code> : <code class="language-plaintext highlighter-rouge">E70_Chose</code></td>
      <td><span class="en">E55 Type </span><code class="language-plaintext highlighter-rouge">E55_Type</code></td>
    </tr>
    <tr>
      <td>P19.1</td>
      <td colspan="2"><span class="en">mode of use </span><code class="language-plaintext highlighter-rouge">P19.1_mode_d’utilisation</code></td>
      <td><span class="en">E7 Activity. <strong>P19 was intended use of (was made for)</strong>: E71 Human-Made Thing </span><code class="language-plaintext highlighter-rouge">E7_Activité</code>. <code class="language-plaintext highlighter-rouge"><strong>P19_a_été_l’usage_prévu_de (a_été_élaboré_pour)</strong></code> : <code class="language-plaintext highlighter-rouge">E71_Chose_élaborée_par_l’humain</code></td>
      <td><span class="en">E55 Type </span><code class="language-plaintext highlighter-rouge">E55_Type</code></td>
    </tr>
    <tr>
      <td>P62.1</td>
      <td colspan="2"><span class="en">mode of depiction </span><code class="language-plaintext highlighter-rouge">P3.1_a_pour_type</code></td>
      <td><span class="en">E24 Physical Human-Made Thing. <strong>P62 depicts (is depicted by)</strong>: E1 CRM Entity </span><code class="language-plaintext highlighter-rouge">E24_Chose_matérielle_élaborée_par_l’humain</code>. <code class="language-plaintext highlighter-rouge"><strong>P62_illustre (est_illustré_par)</strong></code> : <code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></td>
      <td><span class="en">E55 Type </span><code class="language-plaintext highlighter-rouge">E55_Type</code></td>
    </tr>
    <tr>
      <td>P67.1</td>
      <td colspan="2"><span class="en">has type </span><code class="language-plaintext highlighter-rouge">P67.1_a_pour_type</code></td>
      <td><span class="en">E89 Propositional Object. <strong>P67 refers to (is referred to by)</strong>: E1 CRM Entity </span><code class="language-plaintext highlighter-rouge">E89_Objet_propositionnel</code>. <code class="language-plaintext highlighter-rouge"><strong>P67_renvoie_à (fait_l’objet_d’un_renvoi_par)</strong></code> : <code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></td>
      <td><span class="en">E55 Type </span><code class="language-plaintext highlighter-rouge">E55_Type</code></td>
    </tr>
    <tr>
      <td>P138.1</td>
      <td>-</td>
      <td><span class="en">has mode of representation </span><code class="language-plaintext highlighter-rouge">P138.1_mode_de_représentation</code></td>
      <td><span class="en">E36 Visual Item. <strong>P138 represents (has representation)</strong>: E1 CRM Entity </span><code class="language-plaintext highlighter-rouge">E36_Entité_visuelle</code>. <code class="language-plaintext highlighter-rouge"><strong>P138_représente (est_représenté_par)</strong></code> : <code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></td>
      <td><span class="en">E55 Type </span><code class="language-plaintext highlighter-rouge">E55_Type</code></td>
    </tr>
    <tr>
      <td>P69.1</td>
      <td colspan="2"><span class="en">has type </span><code class="language-plaintext highlighter-rouge">P69.1_a_pour_type</code></td>
      <td><span class="en">E29 Design or Procedure. <strong>P69 has association with (is associated with)</strong>: E29 Design or Procedure </span><code class="language-plaintext highlighter-rouge">E29_Conceptualisation_ou_procédure</code>. <code class="language-plaintext highlighter-rouge"><strong>P69_est_associé_à (est_associé_à)</strong></code> : <code class="language-plaintext highlighter-rouge">E29_Conceptualisation_ou_procédure</code></td>
      <td><span class="en">E55 Type </span><code class="language-plaintext highlighter-rouge">E55_Type</code></td>
    </tr>
    <tr>
      <td>P102.1</td>
      <td colspan="2"><span class="en">{{ site.data.entities['P102.1']['en'] }} </span><code class="language-plaintext highlighter-rouge">{{ site.data.entities['P102.1']['fr_code'] }}</code></td>
      <td><span class="en">{{ site.data.entities['E71']['en_code'] }}. <strong>{{ site.data.entities['P102']['en_code'] }}</strong>: {{ site.data.entities['E35']['en_code'] }} </span><code class="language-plaintext highlighter-rouge">{{ site.data.entities['E71']['fr_code'] }}</code>. <code class="language-plaintext highlighter-rouge"><strong>{{ site.data.entities['E102']['fr_code'] }}</strong></code> : <code class="language-plaintext highlighter-rouge">{{ site.data.entities['E35']['fr_code'] }}</code></td>
      <td><span class="en">E55 Type </span><code class="language-plaintext highlighter-rouge">E55_Type</code></td>
    </tr>
    <tr>
      <td>P107.1</td>
      <td colspan="2"><span class="en">{{ site.data.entities['P107.1']['en'] }} </span><code class="language-plaintext highlighter-rouge">{{ site.data.entities['P107.1']['fr_code'] }}</code></td>
      <td><span class="en">{{ site.data.entities['E74']['en_code'] }}. <strong>{{ site.data.entities['P107']['en_code'] }}</strong>: {{ site.data.entities['E39']['en_code'] }} </span><code class="language-plaintext highlighter-rouge">{{ site.data.entities['E74']['fr_code'] }}</code>. <code class="language-plaintext highlighter-rouge"><strong>{{ site.data.entities['P107']['fr_code'] }}</strong></code> : <code class="language-plaintext highlighter-rouge">{{ site.data.entities['E39']['fr_code'] }}</code></td>
      <td><span class="en">E55 Type </span><code class="language-plaintext highlighter-rouge">E55_Type</code></td>
    </tr>
    <tr>
      <td>P136.1</td>
      <td colspan="2"><span class="en">{{ site.data.entities['P136.1']['en'] }} </span><code class="language-plaintext highlighter-rouge">{{ site.data.entities['P136.1']['fr_code'] }}</code></td>
      <td><span class="en">{{ site.data.entities['E83']['en_code'] }}. <strong>{{ site.data.entities['P136']['en_code'] }}</strong>: {{ site.data.entities['E1']['en_code'] }} </span><code class="language-plaintext highlighter-rouge">{{ site.data.entities['E83']['fr_code'] }}</code>. <code class="language-plaintext highlighter-rouge"><strong>{{ site.data.entities['P136']['fr_code'] }}</strong></code> : <code class="language-plaintext highlighter-rouge">{{ site.data.entities['E1']['fr_code'] }}</code></td>
      <td><span class="en">E55 Type </span><code class="language-plaintext highlighter-rouge">E55_Type</code></td>
    </tr>
    <tr>
      <td>P130.1</td>
      <td colspan="2"><span class="en">{{ site.data.entities['P130.1']['en'] }} </span><code class="language-plaintext highlighter-rouge">{{ site.data.entities['P130.1']['fr_code'] }}</code></td>
      <td><span class="en">{{ site.data.entities['E70']['en_code'] }}. <strong>{{ site.data.entities['P130']['en_code'] }}</strong>: {{ site.data.entities['E70']['en_code'] }} </span><code class="language-plaintext highlighter-rouge">{{ site.data.entities['E70']['fr_code'] }}</code>. <code class="language-plaintext highlighter-rouge"><strong>{{ site.data.entities['P130']['fr_code'] }}</strong></code> : <code class="language-plaintext highlighter-rouge">{{ site.data.entities['E70']['fr_code'] }}</code></td>
      <td><span class="en">E55 Type </span><code class="language-plaintext highlighter-rouge">E55_Type</code></td>
    </tr>
    <tr>
      <td>P137.1</td>
      <td colspan="2"><span class="en">{{ site.data.entities['P137.1']['en'] }} </span><code class="language-plaintext highlighter-rouge">{{ site.data.entities['P137.1']['fr_code'] }}</code></td>
      <td><span class="en">{{ site.data.entities['E1']['en_code'] }}. <strong>{{ site.data.entities['P137']['en_code'] }}</strong>: {{ site.data.entities['E55']['en_code'] }} </span><code class="language-plaintext highlighter-rouge">{{ site.data.entities['E1']['fr_code'] }}</code>. <code class="language-plaintext highlighter-rouge"><strong>{{ site.data.entities['P137']['fr_code'] }}</strong></code> : <code class="language-plaintext highlighter-rouge">{{ site.data.entities['E55']['fr_code'] }}</code></td>
      <td><span class="en">E55 Type </span><code class="language-plaintext highlighter-rouge">E55_Type</code></td>
    </tr>
    <tr>
      <td>P139.1</td>
      <td colspan="2"><span class="en">{{ site.data.entities['P139.1']['en'] }} </span><code class="language-plaintext highlighter-rouge">{{ site.data.entities['P139.1']['fr_code'] }}</code></td>
      <td><span class="en">{{ site.data.entities['E41']['en_code'] }}. <strong>{{ site.data.entities['P139']['en_code'] }}</strong>: {{ site.data.entities['E41']['en_code'] }} </span><code class="language-plaintext highlighter-rouge">{{ site.data.entities['E41']['fr_code'] }}</code>. <code class="language-plaintext highlighter-rouge"><strong>{{ site.data.entities['P139']['fr_code'] }}</strong></code> : <code class="language-plaintext highlighter-rouge">{{ site.data.entities['E41']['fr_code'] }}</code></td>
      <td><span class="en">E55 Type </span><code class="language-plaintext highlighter-rouge">E55_Type</code></td>
    </tr>
    <tr>
      <td>P144.1</td>
      <td colspan="2"><span class="en">{{ site.data.entities['P144.1']['en'] }} </span><code class="language-plaintext highlighter-rouge">{{ site.data.entities['P144.1']['fr_code'] }}</code></td>
      <td><span class="en">{{ site.data.entities['E85']['en_code'] }}. <strong>{{ site.data.entities['P144']['en_code'] }}</strong>: {{ site.data.entities['E74']['en_code'] }} </span><code class="language-plaintext highlighter-rouge">{{ site.data.entities['E85']['fr_code'] }}</code>. <code class="language-plaintext highlighter-rouge"><strong>{{ site.data.entities['P144']['fr_code'] }}</strong></code> : <code class="language-plaintext highlighter-rouge">{{ site.data.entities['E74']['fr_code'] }}</code></td>
      <td><span class="en">E55 Type </span><code class="language-plaintext highlighter-rouge">E55_Type</code></td>
    </tr>
    <tr>
      <td>P189.1</td>
      <td colspan="2"><span class="en">{{ site.data.entities['P189.1']['en'] }} </span><code class="language-plaintext highlighter-rouge">{{ site.data.entities['P189.1']['fr_code'] }}</code></td>
      <td><span class="en">{{ site.data.entities['E53']['en_code'] }}. <strong>{{ site.data.entities['P189']['en_code'] }}</strong>: {{ site.data.entities['E53']['en_code'] }} </span><code class="language-plaintext highlighter-rouge">{{ site.data.entities['E53']['fr_code'] }}</code>. <code class="language-plaintext highlighter-rouge"><strong>{{ site.data.entities['P189']['fr_code'] }}</strong></code> : <code class="language-plaintext highlighter-rouge">{{ site.data.entities['E53']['fr_code'] }}</code></td>
      <td><span class="en">E55 Type </span><code class="language-plaintext highlighter-rouge">E55_Type</code></td>
    </tr>
</tbody>
</table>