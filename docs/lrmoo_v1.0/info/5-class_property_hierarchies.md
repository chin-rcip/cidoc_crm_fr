---
layout: page
title: 5. Hiérarchie de classes et de propriétés
titleEn: 5. Class and Property Hierarchies - 5. Hiérarchie de classes et de propriétés
permalink: /lrmoo/v1.0/hierarchie-de-classes-et-de-proprietes
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
<p>Although they do not provide comprehensive definitions, compact monohierarchical presentations of the class and property isA hierarchies have been found to significantly aid in the comprehension and navigation of models in the CIDOC CRM family, and are therefore provided below.</p>
<p>The class hierarchies presented below have the following format:</p>
<ul><li><p>Each line begins with a unique class identifier, consisting of a number preceded by the letter “F”.</p>
</li>
<li><p>A series of em dashes (“—”) follows the unique class identifier, indicating the hierarchical position of the class in the isA hierarchy.</p>
</li>
<li><p>The English label of the class appears to the right of the em dashes.</p>
</li>
<li><p>The index is ordered by hierarchical level, in a “depth first” manner, from the smaller to the larger subhierarchies.</p>
</li>
<li><p>Classes that appear in more than one position in the class hierarchy as a result of multiple inheritance are shown first in roman typeface, then in italic typeface.</p>
</li></ul>
<p>The property hierarchies presented below have the following format:</p>
<ul><li><p>Each line begins with a unique property identifier, consisting of a number preceded by the letter “R”.</p>
</li>
<li><p>A series of em dashes (“—”) follows the unique property identifier, indicating the hierarchical position of the property in the isA hierarchy.</p>
</li>
<li><p>The English label of the property appears to the right of the em dashes, followed by its inverse name in parentheses for reading in the range to domain direction.</p>
</li>
<li><p>The domain class for which the property is declared.</p>
</li>
<li><p>The range class that the property references.</p>
</li>
<li><p>The index is ordered by hierarchical level, in a “depth first” manner, from the smaller to the larger subhierarchies, and by property number between equal siblings.</p>
</li>
<li><p>Properties that appear in more than one position in the property hierarchy as a result of multiple inheritance are shown in an italic typeface.</p>
</li></ul>
<p>In the LRM<sub>OO</sub> class and property hierarchies aligned with CIDOC CRM class and property hierarchies, distinct layouts are used for classes and properties from LRM<sub>OO</sub>, on the one hand, and for classes and properties from CIDOC CRM, on the other hand.</p>
</td>
<td>
<p>Bien qu’elles n’étayent pas de définitions exhaustives, les présentations succinctes et mono-hiérarchiques des classes et des propriétés contribuent à la navigation dans les modèles du <em>Modèle conceptuel de référence du Comité international pour la documentation du Conseil international des musées</em> (CIDOC CRM) et à la compréhension de ceux-ci. </p>
<p>La hiérarchie de classes présentée ci-bas reprend la forme suivante : </p>
<ul><li><p>Chaque ligne commence avec un identifiant de classe unique composé d’un nombre précédé de la lettre « F ». </p>
</li>
<li><p>Une série de tirets cadratins (« — ») suit cet identifiant de classe unique et indique la position de la classe dans la hiérarchie <code class="language-plaintext highlighter-rouge">estUn</code>. </p>
</li>
<li><p>L’étiquette (en français) de la classe se trouve à droite des tirets cadratins. </p>
</li>
<li><p>L’index est ordonné selon les niveaux hiérarchiques avec une approche de « parcours en profondeur » depuis les sous-hiérarchies les plus petites vers les plus larges. </p>
</li>
<li><p>L’apparition de classes dans de multiples positions dans la hiérarchie des classes en raison d’héritages multiples est signalée par l’usage des italiques. </p>
</li></ul>
<p>La hiérarchie des propriétés présentée ci-bas reprend la forme suivante : </p>
<ul><li><p>Chaque ligne commence avec un identifiant de propriété unique composé d’un nombre précédé de la lettre « R ». </p>
</li>
<li><p>Une série de tirets cadratins (« — ») suit cet identifiant de propriété unique et indique la position de la propriété dans la hiérarchie <code class="language-plaintext highlighter-rouge">estUn</code>. </p>
</li>
<li><p>L’étiquette (en français) de la propriété se trouve à droite des tirets cadratins, suivi par le nom de la propriété inverse entre parenthèses (aux fins de lecture depuis la portée vers le domaine). </p>
</li>
<li><p>L’index est ordonné selon les niveaux hiérarchiques avec une approche de « parcours en profondeur » depuis les sous-hiérarchies les plus petites vers les plus larges, puis par numéro de propriété dans le cas de propriétés-sœurs égales. </p>
</li>
<li><p>L’apparition de propriétés dans de multiples positions dans la hiérarchie des propriétés en raison d’héritages multiples est signalée par l’usage des italiques. </p>
</li></ul>
<p>Dans les hiérarchies de classes et de propriétés du <em>Modèle conceptuel pour l’information bibliographique, orientation objet</em> (LRM<sub>OO</sub>) et du CIDOC CRM, des mises en page distinctes sont utilisées aux fins de lisibilité. </p>
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
<p>Cette traduction est adaptée de la définition miroir de la section « <a href="https://cidoc-crm-fr.info/v7.1.3/information/hierarchies-de-classes-et-de-proprietes"><span class="underline">Hiérarchie de classes et de propriétés</span></a> » du CIDOC CRM.</p>
</td>
</tr>
<tr>
<th style="width:15%"><p><em>Références</em></p>
</th>
<td colspan="1">
<p>CIDOC CRM Special Interest Group. « CIDOC CRM Version 7.1.3 ». Traduit par Frédéric Bricaud, Camille Crevier-Lalonde, Stephen Hart, Karine Léonard Brouillet, Marie-Elaine Mathieu, Philippe Michon, Marielle St-Germain, et Marie-Pier Blain. Traduction en français du CIDOC CRM, 23 août 2024.<a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline"> </span></a><a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline">https://cidoc-crm-fr.info/v7.1.3/information/introduction</span></a>.</p>
</td>
</tr>
</tbody>
</table>

<h2 id="hierarchie-de-classes-lrmoo"><span class="en heading">5.1. LRMoo Class Hierarchy - </span>5.1. Hiérarchie de classes LRMoo</h2>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>The labels in italics indicate the second or subsequent listing of a class that appears in more than one place in the hierarchy.</p>
<p><em>Table 3. LRM</em><sub><em>OO</em></sub><em> Class Hierarchy</em></p>
</td>
<td>
<p>Les étiquettes en italiques indiquent la mention récurrente d’une classe qui apparaît ailleurs dans la hiérarchie. </p>
<p><em>Tableau 3 : Hiérarchie de classes LRM</em><sub><em>OO</em></sub></p>
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

<table id="lrmoo-class-hierarchy-table">
  <tbody>
    <tr>
      <th>
        <p class="en block">ID</p>
        <p class="en block">~~~~~</p>
        <p>Identifiant</p></th>
      <th>
        <p class="en block">LRM<sub>OO</sub> Class Name</p>
        <p class="en block">~~~~~</p>
        <p>LRM<sub>OO</sub> Nom de classe</p></th>
      <th>
        <p class="en block">LRM<sub>OO</sub> Subclass Name</p>
        <p class="en block">~~~~~</p>
        <p>LRM<sub>OO</sub> Nom de sous-classe</p></th>
    </tr>
    <tr>
      <td>F1</td>
      <td>
        <p class="en block">Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p></td>
      <td></td>
      </tr>
    <tr>
      <td>F18</td>
      <td>-</td>
      <td>
        <p class="en block">F18 Serial Work [PRESS<sub>OO</sub>]</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F18_Œuvre_de_publication_en_série</code></p></td>
      </tr>
    <tr>
      <td>F2</td>
      <td>
        <p class="en block">Expression</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F2_Expression</code></p></td>
      <td></td>
      </tr>
    <tr>
      <td>F3</td>
      <td>
        <p class="en block">Manifestation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F3_Manifestation</code></p></td>
      <td></td>
      </tr>
    <tr>
      <td>F5</td>
      <td>
        <p class="en block">Item</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F5_Item</code></p></td>
      <td></td>
      </tr>
    <tr>
      <td>F12</td>
      <td>
        <p class="en block">Nomen</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F12_Nomen</code></p></td>
      <td></td>
      </tr>
    <tr>
      <td>F27</td>
      <td>
        <p class="en block">Work Creation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F27_Création_d’œuvre</code></p></td>
      <td></td>
      </tr>
    <tr>
      <td>F28</td>
      <td>
        <p class="en block">Expression Creation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F28_Création_d’expression</code></p></td>
      <td></td>
      </tr>
    <tr>
      <td>F30</td>
      <td>
        <p class="en block">Manifestation Creation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F30_Création_de_manifestation</code></p></td>
      <td></td>
      </tr>
    <tr>
      <td>F33</td>
      <td>-</td>
      <td>
        <p class="en block">Reproduction Event</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F33_Évènement_de_reproduction</code></p></td>
      </tr>
    <tr>
      <td>F31</td>
      <td>
        <p class="en block">Performance</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F31_Performance</code></p></td>
      <td></td>
      </tr>
    <tr>
      <td>F32</td>
      <td>
        <p class="en block">Item Production Event</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F32_Évènement_de_production_d’item</code></p></td>
      <td></td>
      </tr>
    <tr>
      <td>F33</td>
      <td>
        <p class="en block"><em>Reproduction Event </em></p>
        <p class="en block">~~~~~</p>
        <p><em><code class="language-plaintext highlighter-rouge">F33_Évènement_de_reproduction</code></em></p></td>
      <td></td>
      </tr>
    <tr>
      <td>F36</td>
      <td>
        <p class="en block">Script Conversion</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F36_Conversion_de_script</code></p></td>
      <td></td>
      </tr>
    <tr>
      <td>F55</td>
      <td>
        <p class="en block">Collective Agent</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F55_Agent_collectif</code></p></td>
      <td></td>
      </tr>
    <tr>
      <td>F11</td>
      <td>-</td>
      <td>
        <p class="en block">Corporate Body</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F11_Personne_morale</code></p></td>
      </tr>
    <tr>
      <td>F39</td>
      <td>-</td>
      <td>
        <p class="en block">Family</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F39_Famille</code></p></td>
      </tr>
  </tbody>
</table>

<h2 id="hierarchie-de-classes-lrmoo-alignee-avec-les-sections-pertinentes-de-la-hierarchie-de-classes-du-cidoccrm"><span class="en heading">5.2. LRM<sub>OO</sub> class hierarchy, aligned with portions of the CIDOC CRM class hierarchy - </span>5.2. Hiérarchie de classes LRMoo alignée avec les sections pertinentes de la hiérarchie de classes du CIDOC CRM</h2>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>LRM<sub>OO</sub> class hierarchy with CIDOC CRM 7.1.3 direct superclasses added as the first columns. The labels in italics indicate the second or subsequent listing of a class that appears in more than one place in the hierarchy.</p>
<p><em>Table 4. LRM</em><sub><em>OO</em></sub><em> Class Hierarchy aligned with CIDOC CRM</em></p>
</td>
<td>
<p>Ce tableau représente la hiérarchie de classes LRM<sub>OO</sub> avec les super-classes correspondantes du CIDOC CRM 7.1.3 indiquées dans la première colonne. Les étiquettes en italiques indiquent la mention récurrente d’une classe qui apparaît ailleurs dans la hiérarchie. </p>
<p><em>Tableau 4 : Hiérarchie de classes LRM</em><sub><em>OO</em></sub><em> alignée avec le CIDOC CRM</em></p>
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

<table id="lrmoo-crm-class-hierarchy-table">
  <tbody>
    <tr>
      <th>
        <p class="en block">ID</p><p class="en block">~~~~~</p><p>Identifiant</p></th>
      <th>
        <p class="en block">CRM Class Name</p><p class="en block">~~~~~</p><p>CRM Nom de classe</p></th>
      <th>
        <p class="en block">ID</p><p class="en block">~~~~~</p><p>Identifiant</p></th>
      <th>
        <p class="en block">LRM<sub>OO</sub> Class Name</p><p class="en block">~~~~~</p><p>LRM<sub>OO</sub> Nom de classe</p></th>
      <th>
        <p class="en block">LRM<sub>OO</sub> Subclass Name</p><p class="en block">~~~~~</p><p>LRM<sub>OO</sub> Nom de sous-classe</p></th>
    </tr>
    <tr>
      <td>E89</td>
      <td>
        <p class="en block">Propositional Object</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">E89_Objet_propositionnel</code></p>
      </td>
      <td>F1</td>
      <td>
        <p class="en block">Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
      </td>
      <td></td>
      </tr>
    <tr>
      <td></td>
      <td></td>
      <td>F18</td>
      <td>-</td>
      <td>
        <p class="en block">F18 Serial Work [PRESS<sub>OO</sub>]</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F18_Œuvre_de_publication_en_série</code></p>
      </td>
      </tr>
    <tr>
      <td>E73</td>
      <td>
        <p class="en block">Information Object</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">E73_Objet_informationnel</code></p>
      </td>
      <td>F2</td>
      <td>
        <p class="en block">Expression</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F2_Expression</code></p>
      </td>
      <td></td>
      </tr>
    <tr>
      <td>E73</td>
      <td>
        <p class="en block">Information Object</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">E73_Objet_informationnel</code></p>
      </td>
      <td>F3</td>
      <td>
        <p class="en block">Manifestation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F3_Manifestation</code></p>
      </td>
      <td></td>
      </tr>
    <tr>
      <td>E24</td>
      <td>
        <p class="en block">Physical Human-Made Thing</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">E24_Chose_matérielle_élaborée_par_l’humain</code></p>
      </td>
      <td>F5</td>
      <td>
        <p class="en block">Item</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F5_Item</code></p>
      </td>
      <td></td>
      </tr>
    <tr>
      <td>E89</td>
      <td>
        <p class="en block">Propositional Object</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">E89_Objet_propositionnel</code></p>
      </td>
      <td>F12</td>
      <td>
        <p class="en block">Nomen</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F12_Nomen</code></p>
      </td>
      <td></td>
      </tr>
    <tr>
      <td>E65</td>
      <td>
        <p class="en block">Creation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">E65_Création</code></p>
      </td>
      <td>F27</td>
      <td>
        <p class="en block">Work Creation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F27_Création_d’œuvre</code></p>
      </td>
      <td></td>
      </tr>
    <tr>
      <td>E65</td>
      <td>
        <p class="en block">Creation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">E65_Création</code></p>
      </td>
      <td>F28</td>
      <td>
        <p class="en block">Expression Creation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F28_Création_d’expression</code></p>
      </td>
      <td></td>
      </tr>
    <tr>
      <td>E65</td>
      <td>
        <p class="en block">Creation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">E65_Création</code></p>
      </td>
      <td>F30</td>
      <td>
        <p class="en block">Manifestation Creation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F30_Création_de_manifestation</code></p>
      </td>
      <td></td>
      </tr>
    <tr>
      <td></td>
      <td></td>
      <td>F33</td>
      <td>-</td>
      <td>
        <p class="en block">Reproduction Event</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F33_Évènement_de_reproduction</code></p>
      </td>
      </tr>
    <tr>
      <td>E12</td>
      <td>
        <p class="en block">Production</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">E12_Production</code></p>
      </td>
      <td>F28</td>
      <td>
        <p class="en block"><em>Expression Creation</em></p>
        <p class="en block">~~~~~</p>
        <p><em><code class="language-plaintext highlighter-rouge">F28_Création_d’expression</code></em></p>
      </td>
      <td></td>
      </tr>
    <tr>
      <td>E12</td>
      <td>
        <p class="en block">Production</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">E12_Production</code></p>
      </td>
      <td>F30</td>
      <td>
        <p class="en block"><em>Manifestation Creation</em></p>
        <p class="en block">~~~~~</p>
        <p><em><code class="language-plaintext highlighter-rouge">F30_Création_de_manifestation</code></em></p>
      </td>
      <td></td>
      </tr>
    <tr>
      <td></td>
      <td></td>
      <td>F33</td>
      <td>-</td>
      <td>
        <p class="en block"><em>Reproduction Event</em></p>
        <p class="en block">~~~~~</p>
        <p><em><code class="language-plaintext highlighter-rouge">F33_Évènement_de_reproduction</code></em></p>
      </td>
      </tr>
    <tr>
      <td>E7</td>
      <td>
        <p class="en block">Activity</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">E7_Activité</code></p>
      </td>
      <td>F31</td>
      <td>
        <p class="en block">Performance</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F31_Performance</code></p>
      </td>
      <td></td>
      </tr>
    <tr>
      <td>E12</td>
      <td>
        <p class="en block">Production</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">E12_Production</code></p>
      </td>
      <td>F32</td>
      <td>
        <p class="en block">Item Production Event</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F32_Évènement_de_production_d’item</code></p>
      </td>
      <td></td>
      </tr>
    <tr>
      <td>E12</td>
      <td>
        <p class="en block">Production</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">E12_Production</code></p>
      </td>
      <td>F33</td>
      <td>
        <p class="en block"><em>Reproduction Event</em></p>
        <p class="en block">~~~~~</p>
        <p><em><code class="language-plaintext highlighter-rouge">F33_Évènement_de_reproduction</code></em></p>
      </td>
      <td></td>
      </tr>
    <tr>
      <td>E29</td>
      <td>
        <p class="en block">Design or Procedure</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">E29_Conceptualisation_ou_procédure</code></p>
      </td>
      <td>F36</td>
      <td>
        <p class="en block">Script Conversion</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F36_Conversion_de_script</code></p>
      </td>
      <td></td>
      </tr>
    <tr>
      <td>E74</td>
      <td>
        <p class="en block">Group</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">E74_Groupe</code></p>
      </td>
      <td>F55</td>
      <td>
        <p class="en block">Collective Agent</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F55_Agent_collectif</code></p>
      </td>
      <td></td>
      </tr>
    <tr>
      <td></td>
      <td></td>
      <td>F11</td>
      <td>-</td>
      <td>
        <p class="en block">Corporate Body</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F11_Personne_morale</code></p>
      </td>
      </tr>
    <tr>
      <td></td>
      <td></td>
      <td>F39</td>
      <td>-</td>
      <td>
        <p class="en block">Family</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F39_Famille</code></p>
      </td>
      </tr>
  </tbody>
</table>

<h2 id="liste-des-classes-du-cidoccrm-utilisees-dans-le-lrmoo"><span class="en heading">5.3. List of CIDOC CRM classes used in LRM<sub>OO</sub> - </span>5.3. Liste des classes du CIDOC CRM utilisées dans le LRM<sub>OO</sub></h2>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>The list in this section identifies the classes in CIDOC CRM version 7.1.3 referred to by LRM<sub>OO</sub>. In addition to classes that appear as the range of LRM<sub>OO</sub> properties, relevant uses include: appearance in the mapping from IFLA LRM in section 8 or as an element of a path in a mapping statement, reference as immediate superclass of classes defined in the model, or as the domain or range of referred CRM properties.</p>
<p></p>
<p><em>Table 5. CIDOC CRM Classes used in LRM<sub>OO</sub></em></p>
</td>
<td>
<p>Cette liste identifie les classes de la version 7.1.3 du CIDOC CRM auxquelles réfère le LRM<sub>OO</sub>, notamment : </p>
<ul><li><p>comme portée de propriétés du LRM<sub>OO </sub>; </p>
</li>
<li><p>dans le cadre de la mise en correspondance entre le <em>Modèle conceptuel pour l’information bibliographique</em> de la Fédération internationale des associations et institutions de bibliothèques (IFLA LRM) et le LRM<sub>OO</sub>, laquelle est présentée en section 8 « <a href="https://cidoc-crm-fr.info/lrmoo/v1.0/mise-en-correspondance-iflalrm-lrmoo"><span class="underline">Mise en correspondance du IFLA LRM au LRM</span></a><sub><a href="https://cidoc-crm-fr.info/lrmoo/v1.0/mise-en-correspondance-iflalrm-lrmoo"><span class="underline">OO</span></a></sub> » ; </p>
</li>
<li><p>en tant qu’élément du chemin sémantique d’une mise en correspondance ; </p>
</li>
<li><p>à titre de référence à une super-classe immédiate de classes définies dans le LRM<sub>OO </sub>; </p>
</li>
<li><p>comme domaine ou portée de propriétés du CIDOC CRM auxquelles il est fait référence. <em></em></p>
</li></ul>
<p></p>
<p><em>Tableau 5 : Classes CIDOC CRM utilisées dans LRM<sub>OO</sub></em></p>
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


<table class="text">
<tbody>
<tr>
<th>
<p class="en block">Class ID</p>
<p class="en block">~~~~~</p>
<p>Identifiant de classe</p>
</th>
<th>
<p class="en block">Class Name</p>
<p class="en block">~~~~~</p>
<p>Nom de classe</p>
</th>
</tr>
<tr>
<td>
<p>E1</p>
</td>
<td>
<p class="en block">CRM Entity</p>
<p class="en block">~~~~~</p>
<p>Entité CRM</p>
</td>
</tr>
<tr>
<td>
<p>E4</p>
</td>
<td>
<p class="en block">Period</p>
<p class="en block">~~~~~</p>
<p>Période</p>
</td>
</tr>
<tr>
<td>
<p>E7</p>
</td>
<td>
<p class="en block">Activity</p>
<p class="en block">~~~~~</p>
<p>Activité</p>
</td>
</tr>
<tr>
<td>
<p>E11</p>
</td>
<td>
<p class="en block">Modification</p>
<p class="en block">~~~~~</p>
<p>Modification</p>
</td>
</tr>
<tr>
<td>
<p>E12</p>
</td>
<td>
<p class="en block">Production</p>
<p class="en block">~~~~~</p>
<p>Production</p>
</td>
</tr>
<tr>
<td>
<p>E13</p>
</td>
<td>
<p class="en block">Attribute Assignment</p>
<p class="en block">~~~~~</p>
<p>Assignation d’attribut</p>
</td>
</tr>
<tr>
<td>
<p>E18</p>
</td>
<td>
<p class="en block">Physical Thing</p>
<p class="en block">~~~~~</p>
<p>Chose matérielle</p>
</td>
</tr>
<tr>
<td>
<p>E19</p>
</td>
<td>
<p class="en block">Physical Object</p>
<p class="en block">~~~~~</p>
<p>Objet matériel</p>
</td>
</tr>
<tr>
<td>
<p>E21</p>
</td>
<td>
<p class="en block">Person</p>
<p class="en block">~~~~~</p>
<p>Personne</p>
</td>
</tr>
<tr>
<td>
<p>E22</p>
</td>
<td>
<p class="en block">Human-Made Object</p>
<p class="en block">~~~~~</p>
<p>Objet élaboré par l’humain</p>
</td>
</tr>
<tr>
<td>
<p>E24</p>
</td>
<td>
<p class="en block">Physical Human-Made Thing</p>
<p class="en block">~~~~~</p>
<p>Chose matérielle élaborée par l’humain</p>
</td>
</tr>
<tr>
<td>
<p>E25</p>
</td>
<td>
<p class="en block">Human-Made Feature</p>
<p class="en block">~~~~~</p>
<p>Caractéristique élaborée par l’humain</p>
</td>
</tr>
<tr>
<td>
<p>E28</p>
</td>
<td>
<p class="en block">Conceptual Object</p>
<p class="en block">~~~~~</p>
<p>Objet conceptuel</p>
</td>
</tr>
<tr>
<td>
<p>E29</p>
</td>
<td>
<p class="en block">Design or Procedure</p>
<p class="en block">~~~~~</p>
<p>Conceptualisation ou procédure</p>
</td>
</tr>
<tr>
<td>
<p>E30</p>
</td>
<td>
<p class="en block">Right</p>
<p class="en block">~~~~~</p>
<p>Droit</p>
</td>
</tr>
<tr>
<td>
<p>E33</p>
</td>
<td>
<p class="en block">Linguistic Object</p>
<p class="en block">~~~~~</p>
<p>Objet linguistique</p>
</td>
</tr>
<tr>
<td>
<p>E36</p>
</td>
<td>
<p class="en block">Visual Item</p>
<p class="en block">~~~~~</p>
<p>Entité visuelle</p>
</td>
</tr>
<tr>
<td>
<p>E39</p>
</td>
<td>
<p class="en block">Actor</p>
<p class="en block">~~~~~</p>
<p>Actant</p>
</td>
</tr>
<tr>
<td>
<p>E41</p>
</td>
<td>
<p class="en block">Appellation</p>
<p class="en block">~~~~~</p>
<p>Appellation</p>
</td>
</tr>
<tr>
<td>
<p>E52</p>
</td>
<td>
<p class="en block">Time-span</p>
<p class="en block">~~~~~</p>
<p>Intervalle temporel</p>
</td>
</tr>
<tr>
<td>
<p>E53</p>
</td>
<td>
<p class="en block">Place</p>
<p class="en block">~~~~~</p>
<p>Lieu</p>
</td>
</tr>
<tr>
<td>
<p>E54</p>
</td>
<td>
<p class="en block">Dimension</p>
<p class="en block">~~~~~</p>
<p>Dimension</p>
</td>
</tr>
<tr>
<td>
<p>E55</p>
</td>
<td>
<p class="en block">Type</p>
<p class="en block">~~~~~</p>
<p>Type</p>
</td>
</tr>
<tr>
<td>
<p>E56</p>
</td>
<td>
<p class="en block">Language</p>
<p class="en block">~~~~~</p>
<p>Langue</p>
</td>
</tr>
<tr>
<td>
<p>E58</p>
</td>
<td>
<p class="en block">Measurement Unit</p>
<p class="en block">~~~~~</p>
<p>Unité de mesure</p>
</td>
</tr>
<tr>
<td>
<p>E60</p>
</td>
<td>
<p class="en block">Number</p>
<p class="en block">~~~~~</p>
<p>Nombre</p>
</td>
</tr>
<tr>
<td>
<p>E61</p>
</td>
<td>
<p class="en block">Time Primitive</p>
<p class="en block">~~~~~</p>
<p>Primitive temporelle</p>
</td>
</tr>
<tr>
<td>
<p>E62</p>
</td>
<td>
<p class="en block">String</p>
<p class="en block">~~~~~</p>
<p>Chaîne de caractères</p>
</td>
</tr>
<tr>
<td>
<p>E65</p>
</td>
<td>
<p class="en block">Creation</p>
<p class="en block">~~~~~</p>
<p>Création</p>
</td>
</tr>
<tr>
<td>
<p>E66</p>
</td>
<td>
<p class="en block">Formation</p>
<p class="en block">~~~~~</p>
<p>Formation</p>
</td>
</tr>
<tr>
<td>
<p>E70</p>
</td>
<td>
<p class="en block">Thing</p>
<p class="en block">~~~~~</p>
<p>Chose</p>
</td>
</tr>
<tr>
<td>
<p>E73</p>
</td>
<td>
<p class="en block">Information Object</p>
<p class="en block">~~~~~</p>
<p>Objet informationnel</p>
</td>
</tr>
<tr>
<td>
<p>E74</p>
</td>
<td>
<p class="en block">Group</p>
<p class="en block">~~~~~</p>
<p>Groupe</p>
</td>
</tr>
<tr>
<td>
<p>E78</p>
</td>
<td>
<p class="en block">Curated Holding</p>
<p class="en block">~~~~~</p>
<p>Collection</p>
</td>
</tr>
<tr>
<td>
<p>E89</p>
</td>
<td>
<p class="en block">Propositional Object</p>
<p class="en block">~~~~~</p>
<p>Objet propositionnel</p>
</td>
</tr>
<tr>
<td>
<p>E90</p>
</td>
<td>
<p class="en block">Symbolic Object</p>
<p class="en block">~~~~~</p>
<p>Objet symbolique</p>
</td>
</tr>
<tr>
<td>
<p>E94</p>
</td>
<td>
<p class="en block">Space Primitive</p>
<p class="en block">~~~~~</p>
<p>Primitive spatiale</p>
</td>
</tr>
<tr>
<td>
<p>E99</p>
</td>
<td>
<p class="en block">Product Type</p>
<p class="en block">~~~~~</p>
<p>Modèle de produit</p>
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
<p>CIDOC CRM Special Interest Group. 2024. « CIDOC CRM Version 7.1.3 ». Traduit par Marie-Pier Blain, Frédéric Bricaud, Camille Crevier-Lalonde, Stephen Hart, Karine Léonard Brouillet, Marie-Elaine Mathieu, Philippe Michon, et Marielle St-Germain. Traduction en français du CIDOC CRM. 28 août 2024.<a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline"> </span></a><a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline">https://cidoc-crm-fr.info/v7.1.3/information/introduction</span></a>.</p>
</td>
</tr>
</tbody>
</table>

<h2 id="hierarchie-de-proprietes-du-lrmoo"><span class="en heading">5.4. LRM<sub>OO</sub> property hierarchy - </span>5.4. Hiérarchie de propriétés du LRM<sub>OO</sub></h2>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>Range classes from CIDOC CRM are in bold.</p>
<p><em>Table 6. LRM</em><sub><em>OO</em></sub><em> Property Hierarchy</em></p>
</td>
<td>
<p>Les classes de portée issues du CIDOC CRM sont en gras. </p>
<p><em>Tableau 6 : Hiérarchie de propriétés du LRM</em><sub><em>OO</em></sub><em></em></p>
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

<table id="lrmoo-property-hierarchy-table">
  <tbody>
    <tr>
      <th colspan="2"><p class="en block">ID</p><p class="en block">~~~~~</p><p>Identifiant</p></th>
      <th><p class="en block">Property Name</p><p class="en block">~~~~~</p><p>Nom de la propriété</p></th>
      <th><p class="en block">Class - Domain</p><p class="en block">~~~~~</p><p>Classe - Domaine</p></th>
      <th><p class="en block">Class - Range</p><p class="en block">~~~~~</p><p>Classe - Portée</p></th>
    </tr>
    <tr>
      <td><p>R1</p></td>
      <td></td>
      <td>
        <p class="en block">is logical successor of (has successor)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R1_a_pour_successeur_logique (a_pour_successeur)</code></p>
      </td>
      <td>
        <p class="en block">F1 Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
      </td>
      <td>
        <p class="en block">F1 Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
      </td>
    </tr>
    <tr>
      <td><p>R3</p></td>
      <td></td>
      <td>
        <p class="en block">is realised in (realises)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R3_est_réalisé_dans (réalise)</code></p>
      </td>
      <td>
        <p class="en block">F1 Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
      </td>
      <td>
        <p class="en block">F2 Expression</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F2_Expression</code></p>
      </td>
    </tr>
    <tr>
      <td><p>R4</p></td>
      <td></td>
      <td>
        <p class="en block">embodies (is embodied in)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R4_incarne (est_incarné_dans)</code></p>
      </td>
      <td>
        <p class="en block">F3 Manifestation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F3_Manifestation</code></p>
      </td>
      <td>
        <p class="en block">F2 Expression</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F2_Expression</code></p>
      </td>
    </tr>
    <tr>
      <td><p>R5</p></td>
      <td></td>
      <td>
        <p class="en block">has component (is component of)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R5_a_pour_composant (est_le_composant_de)</code></p>
      </td>
      <td>
        <p class="en block">F2 Expression</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F2_Expression</code></p>
      </td>
      <td>
        <p class="en block">F2 Expression</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F2_Expression</code></p>
      </td>
    </tr>
    <tr>
      <td><p>R7</p></td>
      <td></td>
      <td>
        <p class="en block">exemplifies (is exemplified by)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R7_exemplifie (est_exemplifié_par)</code></p>
      </td>
      <td>
        <p class="en block">F5 Item</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F5_Item</code></p>
      </td>
      <td>
        <p class="en block">F3 Manifestation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F3_Manifestation</code></p>
      </td>
    </tr>
    <tr>
      <td><p>R8</p></td>
      <td></td>
      <td>
        <p class="en block">combines (is combined to form)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R8_consiste_en (fait_partie_de)</code></p>
      </td>
      <td>
        <p class="en block">F12 Nomen</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F12_Nomen</code></p>
      </td>
      <td>
        <p class="en block">F12 Nomen</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F12_Nomen</code></p>
      </td>
    </tr>
    <tr>
      <td><p>R10</p></td>
      <td></td>
      <td>
        <p class="en block">is member of (has member)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R10_est_composant_de (a_pour_composant)</code></p>
      </td>
      <td>
        <p class="en block">F1 Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
      </td>
      <td>
        <p class="en block"><strong>E28 Conceptual Object</strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E28_Objet_conceptuel</code></strong></p>
      </td>
    </tr>
    <tr>
      <td><p>R11</p></td>
      <td></td>
      <td>
        <p class="en block">has issuing rule (is issuing rule of) [PRESSOO]</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R11_a_pour_règle_d'émission (est_la_règle_d'émission_de)</code></p>
      </td>
      <td>
        <p class="en block">F18 Serial Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F18_Œuvre_de_publication_en_série</code></p>
      </td>
      <td>
        <p class="en block"><strong>E29 Design or Procedure</strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E29_Conceptualisation_ou_procédure</code></strong></p>
      </td>
    </tr>
    <tr>
      <td><p>R15</p></td>
      <td></td>
      <td>
        <p class="en block">has fragment (is fragment of)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R15_a_pour_fragment (est_un_fragment_de)</code></p>
      </td>
      <td>
        <p class="en block">F2 Expression</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F2_Expression</code></p>
      </td>
      <td>
        <p class="en block"><strong>E90 Symbolic Object</strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E90_Objet_symbolique</code></strong></p>
      </td>
    </tr>
    <tr>
      <td><p>R16</p></td>
      <td></td>
      <td>
        <p class="en block">created (was created by)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R16_a_créé (a_été_créé_par)</code></p>
      </td>
      <td>
        <p class="en block">F27 Work Creation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F27_Création_d’œuvre</code></p>
      </td>
      <td>
        <p class="en block">F1 Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
      </td>
    </tr>
    <tr>
      <td><p>R17</p></td>
      <td></td>
      <td>
        <p class="en block">created (was created by)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R17_a_créé (a_été_créé_par)</code></p>
      </td>
      <td>
        <p class="en block">F28 Expression Creation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F28_Création_d’expression</code></p>
      </td>
      <td>
        <p class="en block">F2 Expression</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F2_Expression</code></p>
      </td>
    </tr>
    <tr>
      <td><p>R19</p></td>
      <td></td>
      <td>
        <p class="en block">created a realisation of (was realised through)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R19_a_créé_une_réalisation_de (a_été_réalisé_à_travers)</code></p>
      </td>
      <td>
        <p class="en block">F28 Expression Creation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F28_Création_d’expression</code></p>
      </td>
      <td>
        <p class="en block">F1 Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
      </td>
    </tr>
    <tr>
      <td><p>R24</p></td>
      <td></td>
      <td>
        <p class="en block">created (was created through)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R24_a_créé (a_été_créé_à_travers)</code></p>
      </td>
      <td>
        <p class="en block">F30 Manifestation Creation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F30_Création_de_manifestation</code></p>
      </td>
      <td>
        <p class="en block">F3 Manifestation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F3_Manifestation</code></p>
      </td>
    </tr>
    <tr>
      <td><p>R27</p></td>
      <td></td>
      <td>
        <p class="en block">materialized (was materialized by)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R27_a_matérialisé (a_été_matérialisé_par)</code></p>
      </td>
      <td>
        <p class="en block">F32 Item Production Event</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F32_Évènement_de_production_d’item</code></p>
      </td>
      <td>
        <p class="en block">F3 Manifestation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F3_Manifestation</code></p>
      </td>
    </tr>
    <tr>
      <td><p>R28</p></td>
      <td></td>
      <td>
        <p class="en block">produced (was produced by)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R28_a_produit (a_été_produit_par)</code></p>
      </td>
      <td>
        <p class="en block">F32 Item Production Event</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F32_Évènement_de_production_d’item</code></p>
      </td>
      <td>
        <p class="en block">F5 Item</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F5_Item</code></p>
      </td>
    </tr>
    <tr>
      <td><p>R29</p></td>
      <td></td>
      <td>
        <p class="en block">reproduced object (was object reproduced by)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R29_objet_reproduit (était_l'objet_reproduit_par)</code></p>
      </td>
      <td>
        <p class="en block">F33 Reproduction Event</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F33_Évènement_de_reproduction</code></p>
      </td>
      <td>
        <p class="en block">F5 Item</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F5_Item</code></p>
      </td>
    </tr>
    <tr>
      <td><p>R30</p></td>
      <td></td>
      <td>
        <p class="en block">reproduced publication (was publication reproduced by)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R30_publication_reproduite (était_la_publication_reproduite_par)</code></p>
      </td>
      <td>
        <p class="en block">F33 Reproduction Event</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F33_Évènement_de_reproduction</code></p>
      </td>
      <td>
        <p class="en block">F3 Manifestation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F3_Manifestation</code></p>
      </td>
    </tr>
    <tr>
      <td><p>R33</p></td>
      <td></td>
      <td>
        <p class="en block">has string</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R33_a_pour_chaîne_de_caractères</code></p>
      </td>
      <td>
        <p class="en block">F12 Nomen</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F12_Nomen</code></p>
      </td>
      <td>
        <p class="en block"><strong>E62 String</strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E62_Chaîne_de_caractères</code></strong></p>
      </td>
    </tr>
    <tr>
      <td><p>R35</p></td>
      <td></td>
      <td>
        <p class="en block">is specified by (specifies)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R35_est_specifié_par</code></p>
      </td>
      <td>
        <p class="en block">F12 Nomen</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F12_Nomen</code></p>
      </td>
      <td>
        <p class="en block">F2 Expression</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F2_Expression</code></p>
      </td>
    </tr>
    <tr>
      <td><p>R36</p></td>
      <td></td>
      <td>
        <p class="en block">uses script conversion (is script conversion used in)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R36_utilise_la_conversion_de_script (est_la_conversion_de_script_utilisée_dans)</code></p>
      </td>
      <td>
        <p class="en block">F12 Nomen</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F12_Nomen</code></p>
      </td>
      <td>
        <p class="en block">F36 Script Conversion</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F36_Conversion_de_script</code></p>
      </td>
    </tr>
    <tr>
      <td><p>R54</p></td>
      <td></td>
      <td>
        <p class="en block">has language (is language of)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R54_a_pour_langue (est_la_langue_de)</code></p>
      </td>
      <td>
        <p class="en block">F12 Nomen</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F12_Nomen</code></p>
      </td>
      <td>
        <p class="en block"><strong>E56 Language</strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E56_Langue</code></strong></p>
      </td>
    </tr>
    <tr>
      <td><p>R56</p></td>
      <td></td>
      <td>
        <p class="en block">has related form (is related form of)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R56_a_pour_forme_connexe (est_la_forme_connexe_de)</code></p>
      </td>
      <td>
        <p class="en block">F12 Nomen</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F12_Nomen</code></p>
      </td>
      <td>
        <p class="en block">F12 Nomen</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F12_Nomen</code></p>
      </td>
    </tr>
    <tr>
      <td><p>R67</p></td>
      <td></td>
      <td>
        <p class="en block">has part (forms part of)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R67_a_pour_élément (fait_partie_de)</code></p>
      </td>
      <td>
        <p class="en block">F1 Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
      </td>
      <td>
        <p class="en block">F1 Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
      </td>
    </tr>
    <tr>
      <td><p>R68</p></td>
      <td></td>
      <td>
        <p class="en block">is inspired by (is inspiration for)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R68_est_inspiré_de (est_source_d'inspiration_pour)</code></p>
      </td>
      <td>
        <p class="en block">F1 Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
      </td>
      <td>
        <p class="en block">F1 Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
      </td>
    </tr>
    <tr>
      <td><p>-</p></td>
      <td><p>R2</p></td>
      <td>
        <p class="en block">is derivative of (has derivative)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R2_est_dérivé_de (a_pour_dérivé)</code></p>
      </td>
      <td>
        <p class="en block">F1 Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
      </td>
      <td>
        <p class="en block">F1 Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
      </td>
    </tr>
    <tr>
      <td><p>R69</p></td>
      <td></td>
      <td>
        <p class="en block">has physical form (is physical form of)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R69_a_pour_forme_physique (est_forme_physique_de)</code></p>
      </td>
      <td>
        <p class="en block">F3 Manifestation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F3_Manifestation</code></p>
      </td>
      <td>
        <p class="en block"><strong>E55 Type</strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E55_Type</code></strong></p>
      </td>
    </tr>
    <tr>
      <td><p>R70</p></td>
      <td></td>
      <td>
        <p class="en block">has dimension (is dimension of) </p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R70_a_pour_dimension (est_la_dimension_de)</code></p>
      </td>
      <td>
        <p class="en block">F3 Manifestation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F3_Manifestation</code></p>
      </td>
      <td>
        <p class="en block"><strong>E54 Dimension</strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E54_Dimension</code></strong></p>
      </td>
    </tr>
    <tr>
      <td><p>R71</p></td>
      <td></td>
      <td>
        <p class="en block">has part (is part of) </p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R71_a_pour_élément (fait_partie_de)</code></p>
      </td>
      <td>
        <p class="en block">F3 Manifestation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F3_Manifestation</code></p>
      </td>
      <td>
        <p class="en block">F3 Manifestation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F3_Manifestation</code></p>
      </td>
    </tr>
    <tr>
      <td><p>R73</p></td>
      <td></td>
      <td>
        <p class="en block">takes representative attribute from (bears representative attribute for)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R73_prend_l'attribut_représentatif_de (porte_l'attribut_représentatif_pour)</code></p>
      </td>
      <td>
        <p class="en block">F1 Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
      </td>
      <td>
        <p class="en block">F2 Expression</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F2_Expression</code></p>
      </td>
    </tr>
    <tr>
      <td><p>R74</p></td>
      <td></td>
      <td>
        <p class="en block">uses expression of (has expression used in)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R74_utilise_l’expression_de (a_l’expression_utilisée_dans)</code></p>
      </td>
      <td>
        <p class="en block">F1 Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
      </td>
      <td>
        <p class="en block">F1 Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
      </td>
    </tr>
    <tr>
      <td><p>R75</p></td>
      <td></td>
      <td>
        <p class="en block">incorporates (is incorporated in)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R75_incorpore (est_inclus_dans)</code></p>
      </td>
      <td>
        <p class="en block">F2 Expression</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F2_Expression</code></p>
      </td>
      <td>
        <p class="en block">F2 Expression</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F2_Expression</code></p>
      </td>
    </tr>
    <tr>
      <td><p>R76</p></td>
      <td></td>
      <td>
        <p class="en block">is derivative of (has derivative) </p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R76_est_dérivé_de (a_pour_dérivé)</code></p>
      </td>
      <td>
        <p class="en block">F2 Expression</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F2_Expression</code></p>
      </td>
      <td>
        <p class="en block">F2 Expression</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F2_Expression</code></p>
      </td>
    </tr>
    <tr>
      <td><p>R77</p></td>
      <td></td>
      <td>
        <p class="en block">accompanies or complements (is accompanied or complemented by)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R77_accompagne_ou_complémente (est_accompagné_ou_complémenté_de)</code></p>
      </td>
      <td>
        <p class="en block">F1 Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
      </td>
      <td>
        <p class="en block">F1 Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
      </td>
    </tr>
    <tr>
      <td><p>R78</p></td>
      <td></td>
      <td>
        <p class="en block">has alternate</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R78_a_pour_présentation_alternative</code></p>
      </td>
      <td>
        <p class="en block">F3 Manifestation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F3_Manifestation</code></p>
      </td>
      <td>
        <p class="en block">F3 Manifestation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F3_Manifestation</code></p>
      </td>
    </tr>
    <tr>
      <td><p>R79</p></td>
      <td></td>
      <td>
        <p class="en block">has representative expression attribute (is representative expression attribute of)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R79_a_l’attribut_d’expression_représentatif (est_l’attribut_d’expression_représentatif_de)</code></p>
      </td>
      <td>
        <p class="en block">F1 Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
      </td>
      <td>
        <p class="en block"><strong>E55 Type</strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E55_Type</code></strong></p>
      </td>
    </tr>
    <tr>
      <td><p>R80</p></td>
      <td></td>
      <td>
        <p class="en block">performed (is performed in)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R80_a_interprété (est_interprété_dans)</code></p>
      </td>
      <td>
        <p class="en block">F31 Performance</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F31_Performance</code></p>
      </td>
      <td>
        <p class="en block">F1 Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
      </td>
    </tr>
    <tr>
      <td><p>R81</p></td>
      <td></td>
      <td>
        <p class="en block">recorded (is recorded in)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R81_enregistré (est_enregistré_dans)</code></p>
      </td>
      <td>
        <p class="en block">F28 Expression Creation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F28_Création_d’expression</code></p>
      </td>
      <td>
        <p class="en block">F31 Performance</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F31_Performance</code></p>
      </td>
    </tr>
  </tbody>
</table>

<h2 id="hierarchie-de-proprietes-lrmoo-alignee-avec-les-sections-pertinentes-de-la-hierarchie-de-proprietes-du-cidoccrm"><span class="en heading">5.5. LRM<sub>OO</sub> property hierarchy, aligned with portions of the CIDOC CRM property hierarchy - </span>5.5. Hiérarchie de propriétés LRM<sub>OO</sub> alignée avec les sections pertinentes de la hiérarchie de propriétés du CIDOC CRM</h2>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>The CIDOC CRM 7.1.3 direct superproperty of each of the LRM<sub>OO </sub>properties is inserted in the immediately preceding line. When a CIDOC CRM property appears a second or subsequent time in the table, its property ID is given in italics. LRM<sub>OO</sub> properties that are defined as shortcuts do not appear in this table. The table also does not include LRM<sub>OO</sub> properties that are noted as being outside of CIDOC CRM scope.</p>
<p><em>Table 7. LRM</em><sub><em>OO</em></sub><em> Property Hierarchy aligned with CIDOC CRM</em></p>
</td>
<td>
<p>Pour chaque propriété du LRMoo, la super-propriété directe du CIDOC CRM (7.1.3) associée est indiquée dans la ligne précédente immédiate. </p>
<p>Lorsqu’une propriété du CIDOC CRM apparaît plus d’une fois dans le tableau, son identifiant de propriété est indiqué en italiques. </p>
<p>Les propriétés LRMoo définies comme des raccourcis n’apparaissent pas ici, de même que les propriétés LRMoo qui dépassent le champ d’application du CIDOC CRM. </p>
<p><em>Tableau 7 : Hiérarchie de propriétés LRM</em><sub><em>OO</em></sub><em> alignée avec le CIDOC CRM</em></p>
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

<table id="lrmoo-crm-property-hierarchy-table">
  <tbody>
    <tr>
      <th colspan="2"><p class="en block">Property ID</p><p class="en block">~~~~~</p><p>Identifiant de propriété</p></th>
      <th><p class="en block">Property Name</p><p class="en block">~~~~~</p><p>Nom de la propriété</p></th>
      <th><p class="en block">Class - Domain</p><p class="en block">~~~~~</p><p>Classe - Domaine</p></th>
      <th><p class="en block">Class - Range</p><p class="en block">~~~~~</p><p>Classe - Portée</p></th>
    </tr>
    <tr>
      <td>P130</td>
      <td></td>
      <td>
        <p class="en block">shows freatures of (features are also found on) </p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">P130_présente_les_caractéristiques_de (a_les_caractéristiques_aussi_présentes_sur)</code></p>
      </td>
      <td>
        <p class="en block"><strong>E70 Thing </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E70_Chose</code></strong></p>
      </td>
      <td>
        <p class="en block"><strong>E70 Thing </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E70_Chose</code></strong></p>
      </td>
    </tr>
    <tr>
      <td>-</td>
      <td><p>R1</p></td>
      <td>
        <p class="en block">is logical successor of (has successor)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R1_a_pour_successeur_logique (a_pour_successeur)</code></p>
      </td>
      <td>
        <p class="en block">F1 Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
      </td>
      <td>
        <p class="en block">F1 Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
      </td>
    </tr>
    <tr>
      <td>-</td>
      <td><p>R3</p></td>
      <td>
        <p class="en block">is realised in (realises)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R3_est_réalisé_dans (réalise)</code></p>
      </td>
      <td>
        <p class="en block">F1 Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
      </td>
      <td>
        <p class="en block">F2 Expression</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F2_Expression</code></p>
      </td>
    </tr>
    <tr>
      <td>P165</td>
      <td></td>
      <td>
        <p class="en block">incorporates (is incorporated in) </p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">P165_inclut (est_inclus_dans)</code></p>
      </td>
      <td>
        <p class="en block"><strong>E73 Information Object </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E73_Objet_informationnel</code></strong></p>
      </td>
      <td>
        <p class="en block"><strong>E90 Symbolic Object </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E90_Objet_symbolique</code></strong></p>
      </td>
    </tr>
    <tr>
      <td>-</td>
      <td><p>R4</p></td>
      <td>
        <p class="en block">embodies (is embodied in)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R4_incarne (est_incarné_dans)</code></p>
      </td>
      <td>
        <p class="en block">F3 Manifestation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F3_Manifestation</code></p>
      </td>
      <td>
        <p class="en block">F2 Expression</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F2_Expression</code></p>
      </td>
    </tr>
    <tr>
      <td>P148</td>
      <td></td>
      <td>
        <p class="en block">has component (is component of) </p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">P148_a_pour_composant (est_le_composant_de)</code></p>
      </td>
      <td>
        <p class="en block"><strong>E89 Propositional Object </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E89_Objet_propositionnel</code></strong></p>
      </td>
      <td>
        <p class="en block"><strong>E89 Propositional Object </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E89_Objet_propositionnel</code></strong></p>
      </td>
    </tr>
    <tr>
      <td>-</td>
      <td><p>R5</p></td>
      <td>
        <p class="en block">has component (is component of)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R5_a_pour_composant (est_le_composant_de)</code></p>
      </td>
      <td>
        <p class="en block">F2 Expression</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F2_Expression</code></p>
      </td>
      <td>
        <p class="en block">F2 Expression</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F2_Expression</code></p>
      </td>
    </tr>
    <tr>
      <td>P128</td>
      <td></td>
      <td>
        <p class="en block">carries (is carried by) </p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">P128_est_le_support_de (a_pour_support)</code></p>
      </td>
      <td>
        <p class="en block"><strong>E18 Physical Thing </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></strong></p>
      </td>
      <td>
        <p class="en block"><strong>E90 Symbolic Object </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E90_Objet_symbolique</code></strong></p>
      </td>
    </tr>
    <tr>
      <td>-</td>
      <td><p>R7</p></td>
      <td>
        <p class="en block">exemplifies (is exemplified by)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R7_exemplifie (est_exemplifié_par)</code></p>
      </td>
      <td>
        <p class="en block">F5 Item</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F5_Item</code></p>
      </td>
      <td>
        <p class="en block">F3 Manifestation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F3_Manifestation</code></p>
      </td>
    </tr>
    <tr>
      <td>P106</td>
      <td></td>
      <td>
        <p class="en block">is composed of (forms part of) </p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">P106_est_composé_de (fait_partie_de)</code></p>
      </td>
      <td>
        <p class="en block"><strong>E90 Symbolic Object </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E90_Objet_symbolique</code></strong></p>
      </td>
      <td>
        <p class="en block"><strong>E90 Symbolic Object </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E90_Objet_symbolique</code></strong></p>
      </td>
    </tr>
    <tr>
      <td>-</td>
      <td><p>R15</p></td>
      <td>
        <p class="en block">has fragment (is fragment of)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R15_a_pour_fragment (est_un_fragment_de)</code></p>
      </td>
      <td>
        <p class="en block">F2 Expression</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F2_Expression</code></p>
      </td>
      <td>
        <p class="en block"><strong>E90 Symbolic Object</strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E90_Objet_symbolique</code></strong></p>
      </td>
    </tr>
    <tr>
      <td>P94</td>
      <td></td>
      <td>
        <p class="en block">has created (was creates by) </p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">P94_a_créé (a_été_créé_par)</code></p>
      </td>
      <td>
        <p class="en block"><strong>E65 Creation </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E65_Création</code></strong></p>
      </td>
      <td>
        <p class="en block"><strong>E28 Conceptual Object </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E28_Objet_conceptuel</code></strong></p>
      </td>
    </tr>
    <tr>
      <td>-</td>
      <td><p>R16</p></td>
      <td>
        <p class="en block">created (was created by)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R16_a_créé (a_été_créé_par)</code></p>
      </td>
      <td>
        <p class="en block">F27 Work Creation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F27_Création_d’œuvre</code></p>
      </td>
      <td>
        <p class="en block">F1 Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
      </td>
    </tr>
    <tr>
      <td>-</td>
      <td><p>R17</p></td>
      <td>
        <p class="en block">created (was created by)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R17_a_créé (a_été_créé_par)</code></p>
      </td>
      <td>
        <p class="en block">F28 Expression Creation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F28_Création_d’expression</code></p>
      </td>
      <td>
        <p class="en block">F2 Expression</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F2_Expression</code></p>
      </td>
    </tr>
    <tr>
      <td>P16</td>
      <td></td>
      <td>
        <p class="en block">used specific object (was used for) </p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">P16_a_mobilisé_l’objet_spécifique (a_été_mobilisé_pour)</code></p>
      </td>
      <td>
        <p class="en block"><strong>E7 Activity </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E7_Activité</code></strong></p>
      </td>
      <td>
        <p class="en block"><strong>E70 Thing </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E70_Chose</code></strong></p>
      </td>
    </tr>
    <tr>
      <td>-</td>
      <td><p>R19</p></td>
      <td>
        <p class="en block">created a realisation of (was realised through)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R19_a_créé_une_réalisation_de (a_été_réalisé_à_travers)</code></p>
      </td>
      <td>
        <p class="en block">F28 Expression Creation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F28_Création_d’expression</code></p>
      </td>
      <td>
        <p class="en block">F1 Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
      </td>
    </tr>
    <tr>
      <td><em>P94</em></td>
      <td></td>
      <td>
        <p class="en block">has created (was creates by) </p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">P94_a_créé (a_été_créé_par)</code></p>
      </td>
      <td>
        <p class="en block"><strong>E65 Creation </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E65_Création</code></strong></p>
      </td>
      <td>
        <p class="en block"><strong>E28 Conceptual Object </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E28_Objet_conceptuel</code></strong></p>
      </td>
    </tr>
    <tr>
      <td>-</td>
      <td><p>R24</p></td>
      <td>
        <p class="en block">created (was created through)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R24_a_créé (a_été_créé_à_travers)</code></p>
      </td>
      <td>
        <p class="en block">F30 Manifestation Creation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F30_Création_de_manifestation</code></p>
      </td>
      <td>
        <p class="en block">F3 Manifestation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F3_Manifestation</code></p>
      </td>
    </tr>
    <tr>
      <td><em>P16</em></td>
      <td></td>
      <td>
        <p class="en block">used specific object (was used for) </p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">P16_a_mobilisé_l’objet_spécifique (a_été_mobilisé_pour)</code></p>
      </td>
      <td>
        <p class="en block"><strong>E7 Activity </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E7_Activité</code></strong></p>
      </td>
      <td>
        <p class="en block"><strong>E70 Thing </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E70_Chose</code></strong></p>
      </td>
    </tr>
    <tr>
      <td>-</td>
      <td><p>R27</p></td>
      <td>
        <p class="en block">materialized (was materialized by)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R27_a_matérialisé (a_été_matérialisé_par)</code></p>
      </td>
      <td>
        <p class="en block">F32 Item Production Event</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F32_Évènement_de_production_d’item</code></p>
      </td>
      <td>
        <p class="en block">F3 Manifestation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F3_Manifestation</code></p>
      </td>
    </tr>
    <tr>
      <td>P108</td>
      <td></td>
      <td>
        <p class="en block">has produced (was produced by) </p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">P108_a_produit (a_été_produit_par)</code></p>
      </td>
      <td>
        <p class="en block"><strong>E12 Production </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E12_Production</code></strong></p>
      </td>
      <td>
        <p class="en block"><strong>E24 Physical Human-Made Thing </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E24_Chose_matérielle_élaborée_par_l’humain</code></strong></p>
      </td>
    </tr>
    <tr>
      <td>-</td>
      <td><p>R28</p></td>
      <td>
        <p class="en block">produced (was produced by)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R28_a_produit (a_été_produit_par)</code></p>
      </td>
      <td>
        <p class="en block">F32 Item Production Event</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F32_Évènement_de_production_d’item</code></p>
      </td>
      <td>
        <p class="en block">F5 Item</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F5_Item</code></p>
      </td>
    </tr>
    <tr>
      <td><em>P16</em></td>
      <td></td>
      <td>
        <p class="en block">used specific object (was used for) </p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">P16_a_mobilisé_l’objet_spécifique (a_été_mobilisé_pour)</code></p>
      </td>
      <td>
        <p class="en block"><strong>E7 Activity </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E7_Activité</code></strong></p>
      </td>
      <td>
        <p class="en block"><strong>E70 Thing </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E70_Chose</code></strong></p>
      </td>
    </tr>
    <tr>
      <td>-</td>
      <td><p>R29</p></td>
      <td>
        <p class="en block">reproduced object (was object reproduced by)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R29_objet_reproduit (était_l'objet_reproduit_par)</code></p>
      </td>
      <td>
        <p class="en block">F33 Reproduction Event</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F33_Évènement_de_reproduction</code></p>
      </td>
      <td>
        <p class="en block">F5 Item</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F5_Item</code></p>
      </td>
    </tr>
    <tr>
      <td>-</td>
      <td><p>R30</p></td>
      <td>
        <p class="en block">reproduced publication (was publication reproduced by)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R30_publication_reproduite (était_la_publication_reproduite_par)</code></p>
      </td>
      <td>
        <p class="en block">F33 Reproduction Event</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F33_Évènement_de_reproduction</code></p>
      </td>
      <td>
        <p class="en block">F3 Manifestation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F3_Manifestation</code></p>
      </td>
    </tr>
    <tr>
      <td>P3</td>
      <td></td>
      <td>
        <p class="en block">has note </p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">P3_a_pour_note</code></p>
      </td>
      <td>
        <p class="en block"><strong>E1 CRM Entity </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></strong></p>
      </td>
      <td>
        <p class="en block"><strong>E62 String </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E62_Chaîne_de_caractères</code></strong></p>
      </td>
    </tr>
    <tr>
      <td>-</td>
      <td><p>R33</p></td>
      <td>
        <p class="en block">has string</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R33_a_pour_chaîne_de_caractères</code></p>
      </td>
      <td>
        <p class="en block">F12 Nomen</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F12_Nomen</code></p>
      </td>
      <td>
        <p class="en block"><strong>E62 String</strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E62_Chaîne_de_caractères</code></strong></p>
      </td>
    </tr>
    <tr>
      <td>P67i</td>
      <td></td>
      <td>
        <p class="en block">is referred to by</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">P67_fait_l’objet_d’un_renvoi_par</code></p>
      </td>
      <td>
        <p class="en block"><strong>E1 CRM Entity </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></strong></p>
      </td>
      <td>
        <p class="en block"><strong>E89 Propositional Object </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E89_Objet_propositionnel</code></strong></p>
      </td>
    </tr>
    <tr>
      <td>-</td>
      <td><p>R35</p></td>
      <td>
        <p class="en block">is specified by (specifies)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R35_est_specifié_par</code></p>
      </td>
      <td>
        <p class="en block">F12 Nomen</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F12_Nomen</code></p>
      </td>
      <td>
        <p class="en block">F2 Expression</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F2_Expression</code></p>
      </td>
    </tr>
    <tr>
      <td>P2</td>
      <td></td>
      <td>
        <p class="en block">has type </p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">P2_a_pour_type</code></p>
      </td>
      <td>
        <p class="en block"><strong>E1 CRM Entity </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></strong></p>
      </td>
      <td>
        <p class="en block"><strong>E55 Type </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E55_Type</code></strong></p>
      </td>
    </tr>
    <tr>
      <td>-</td>
      <td><p>R54</p></td>
      <td>
        <p class="en block">has language (is language of)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R54_a_pour_langue (est_la_langue_de)</code></p>
      </td>
      <td>
        <p class="en block">F12 Nomen</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F12_Nomen</code></p>
      </td>
      <td>
        <p class="en block"><strong>E56 Language</strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E56_Langue</code></strong></p>
      </td>
    </tr>
    <tr>
      <td><em>P148</em></td>
      <td></td>
      <td>
        <p class="en block">has component (is component of) </p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">P148_a_pour_composant (est_le_composant_de)</code></p>
      </td>
      <td>
        <p class="en block"><strong>E89 Propositional Object </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E89_Objet_propositionnel</code></strong></p>
      </td>
      <td>
        <p class="en block"><strong>E89 Propositional Object </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E89_Objet_propositionnel</code></strong></p>
      </td>
    </tr>
    <tr>
      <td>-</td>
      <td><p>R67</p></td>
      <td>
        <p class="en block">has part (forms part of)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R67_a_pour_élément (fait_partie_de)</code></p>
      </td>
      <td>
        <p class="en block">F1 Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
      </td>
      <td>
        <p class="en block">F1 Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
      </td>
    </tr>
    <tr>
      <td><em>P130</em></td>
      <td></td>
      <td>
        <p class="en block">shows freatures of (features are also found on) </p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">P130_présente_les_caractéristiques_de (a_les_caractéristiques_aussi_présentes_sur)</code></p>
      </td>
      <td>
        <p class="en block"><strong>E70 Thing </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E70_Chose</code></strong></p>
      </td>
      <td>
        <p class="en block"><strong>E70 Thing </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E70_Chose</code></strong></p>
      </td>
    </tr>
    <tr>
      <td>-</td>
      <td><p>R68</p></td>
      <td>
        <p class="en block">is inspired by (is inspiration for)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R68_est_inspiré_de (est_source_d'inspiration_pour)</code></p>
      </td>
      <td>
        <p class="en block">F1 Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
      </td>
      <td>
        <p class="en block">F1 Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
      </td>
    </tr>
    <tr>
      <td><p>--</p></td>
      <td><p>R2</p></td>
      <td>
        <p class="en block">is derivative of (has derivative)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R2_est_dérivé_de (a_pour_dérivé)</code></p>
      </td>
      <td>
        <p class="en block">F1 Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
      </td>
      <td>
        <p class="en block">F1 Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
      </td>
    </tr>
    <tr>
      <td><em>P2</em></td>
      <td></td>
      <td>
        <p class="en block">has type </p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">P2_a_pour_type</code></p>
      </td>
      <td>
        <p class="en block"><strong>E1 CRM Entity </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></strong></p>
      </td>
      <td>
        <p class="en block"><strong>E55 Type </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E55_Type</code></strong></p>
      </td>
    </tr>
    <tr>
      <td>-</td>
      <td><p>R69</p></td>
      <td>
        <p class="en block">has physical form (is physical form of)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R69_a_pour_forme_physique (est_forme_physique_de)</code></p>
      </td>
      <td>
        <p class="en block">F3 Manifestation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F3_Manifestation</code></p>
      </td>
      <td>
        <p class="en block"><strong>E55 Type</strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E55_Type</code></strong></p>
      </td>
    </tr>
    <tr>
      <td>P43</td>
      <td></td>
      <td>
        <p class="en block">has dimension (is dimension of) </p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">P43_a_pour_dimension (est_la_dimension_de)</code></p>
      </td>
      <td>
        <p class="en block"><strong>E70 Thing </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E70_Chose</code></strong></p>
      </td>
      <td>
        <p class="en block"><strong>E54 Dimension </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E54_Dimension</code></strong></p>
      </td>
    </tr>
    <tr>
      <td>-</td>
      <td><p>R70</p></td>
      <td>
        <p class="en block">has dimension (is dimension of) </p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R70_a_pour_dimension (est_la_dimension_de)</code></p>
      </td>
      <td>
        <p class="en block">F3 Manifestation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F3_Manifestation</code></p>
      </td>
      <td>
        <p class="en block"><strong>E54 Dimension</strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E54_Dimension</code></strong></p>
      </td>
    </tr>
    <tr>
      <td><em>P148</em></td>
      <td></td>
      <td>
        <p class="en block">has component (is component of) </p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">P148_a_pour_composant (est_le_composant_de)</code></p>
      </td>
      <td>
        <p class="en block"><strong>E89 Propositional Object </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E89_Objet_propositionnel</code></strong></p>
      </td>
      <td>
        <p class="en block"><strong>E89 Propositional Object </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E89_Objet_propositionnel</code></strong></p>
      </td>
    </tr>
    <tr>
      <td>-</td>
      <td><p>R71</p></td>
      <td>
        <p class="en block">has part (is part of) </p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R71_a_pour_élément (fait_partie_de)</code></p>
      </td>
      <td>
        <p class="en block">F3 Manifestation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F3_Manifestation</code></p>
      </td>
      <td>
        <p class="en block">F3 Manifestation</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F3_Manifestation</code></p>
      </td>
    </tr>
    <tr>
      <td><em>P130</em></td>
      <td></td>
      <td>
        <p class="en block">shows freatures of (features are also found on) </p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">P130_présente_les_caractéristiques_de (a_les_caractéristiques_aussi_présentes_sur)</code></p>
      </td>
      <td>
        <p class="en block"><strong>E70 Thing </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E70_Chose</code></strong></p>
      </td>
      <td>
        <p class="en block"><strong>E70 Thing </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E70_Chose</code></strong></p>
      </td>
    </tr>
    <tr>
      <td>-</td>
      <td><p>R74</p></td>
      <td>
        <p class="en block">uses expression of (has expression used in)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R74_utilise_l’expression_de (a_l’expression_utilisée_dans)</code></p>
      </td>
      <td>
        <p class="en block">F1 Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
      </td>
      <td>
        <p class="en block">F1 Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
      </td>
    </tr>
    <tr>
      <td><em>P165</em></td>
      <td></td>
      <td>
        <p class="en block">incorporates (is incorporated in) </p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">P165_inclut (est_inclus_dans)</code></p>
      </td>
      <td>
        <p class="en block"><strong>E73 Information Object </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E73_Objet_informationnel</code></strong></p>
      </td>
      <td>
        <p class="en block"><strong>E90 Symbolic Object </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E90_Objet_symbolique</code></strong></p>
      </td>
    </tr>
    <tr>
      <td>-</td>
      <td><p>R75</p></td>
      <td>
        <p class="en block">incorporates (is incorporated in)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R75_incorpore (est_inclus_dans)</code></p>
      </td>
      <td>
        <p class="en block">F2 Expression</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F2_Expression</code></p>
      </td>
      <td>
        <p class="en block">F2 Expression</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F2_Expression</code></p>
      </td>
    </tr>
    <tr>
      <td><em>P130</em></td>
      <td></td>
      <td>
        <p class="en block">shows freatures of (features are also found on) </p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">P130_présente_les_caractéristiques_de (a_les_caractéristiques_aussi_présentes_sur)</code></p>
      </td>
      <td>
        <p class="en block"><strong>E70 Thing </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E70_Chose</code></strong></p>
      </td>
      <td>
        <p class="en block"><strong>E70 Thing </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E70_Chose</code></strong></p>
      </td>
    </tr>
    <tr>
      <td>-</td>
      <td><p>R76</p></td>
      <td>
        <p class="en block">is derivative of (has derivative) </p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R76_est_dérivé_de (a_pour_dérivé)</code></p>
      </td>
      <td>
        <p class="en block">F2 Expression</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F2_Expression</code></p>
      </td>
      <td>
        <p class="en block">F2 Expression</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F2_Expression</code></p>
      </td>
    </tr>
    <tr>
      <td><em>P2</em></td>
      <td></td>
      <td>
        <p class="en block">has type </p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">P2_a_pour_type</code></p>
      </td>
      <td>
        <p class="en block"><strong>E1 CRM Entity </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></strong></p>
      </td>
      <td>
        <p class="en block"><strong>E55 Type </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E55_Type</code></strong></p>
      </td>
    </tr>
    <tr>
      <td>-</td>
      <td><p>R79</p></td>
      <td>
        <p class="en block">has representative expression attribute (is representative expression attribute of)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R79_a_l’attribut_d’expression_représentatif (est_l’attribut_d’expression_représentatif_de)</code></p>
      </td>
      <td>
        <p class="en block">F1 Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
      </td>
      <td>
        <p class="en block"><strong>E55 Type</strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E55_Type</code></strong></p>
      </td>
    </tr>
    <tr>
      <td><em>P130</em></td>
      <td></td>
      <td>
        <p class="en block">shows freatures of (features are also found on) </p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">P130_présente_les_caractéristiques_de (a_les_caractéristiques_aussi_présentes_sur)</code></p>
      </td>
      <td>
        <p class="en block"><strong>E70 Thing </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E70_Chose</code></strong></p>
      </td>
      <td>
        <p class="en block"><strong>E70 Thing </strong></p>
        <p class="en block">~~~~~</p>
        <p><strong><code class="language-plaintext highlighter-rouge">E70_Chose</code></strong></p>
      </td>
    </tr>
    <tr>
      <td>-</td>
      <td><p>R80</p></td>
      <td>
        <p class="en block">performed (is performed in)</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">R80_a_interprété (est_interprété_dans)</code></p>
      </td>
      <td>
        <p class="en block">F31 Performance</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F31_Performance</code></p>
      </td>
      <td>
        <p class="en block">F1 Work</p>
        <p class="en block">~~~~~</p>
        <p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
      </td>
    </tr>
  </tbody>
</table>

<h2 id="proprietes-de-proprietes-du-lrmoo-(proprietes.1)"><span class="en heading">5.6. LRM<sub>OO</sub> Properties of Properties (.1 Properties) - </span>5.6. Propriétés de propriétés du LRM<sub>OO</sub> (propriétés « .1 »)</h2>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>Properties of properties have an LRM<sub>OO</sub> property as their domain and the CIDOC CRM class E55 Type as their range. The domain property is presented in full with its own domain and range classes.<em></em></p>
<p><em>Table 8. LRM<sub>OO</sub> .1 Properties</em></p> 
</td>
<td>
<p>Les propriétés de propriétés ont pour domaine une propriété LRM<sub>OO</sub> et pour portée la classe CIDOC CRM <code class="language-plaintext highlighter-rouge">E55_Type</code>. La propriété-domaine est présentée dans son intégralité (c.-à-d. avec ses propres classes de domaine et de portée). </p>
<p><em>Tableau 8 : Propriétés « .1 » du LRM<sub>OO</sub></em></p>
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

<table class="text">
<tbody>
<tr>
<th>
<p class="en block">Property ID</p>
<p class="en block">~~~~~</p>
<p>Identifiant de propriété</p>
</th>
<th>
<p class="en block">Property Name</p>
<p class="en block">~~~~~</p>
<p>Nom de propriété</p>
</th>
<th>
<p class="en block">Property – Domain</p>
<p class="en block">~~~~~</p>
<p>Propriété – domaine</p>
</th>
<th>
<p class="en block">Class – Range</p>
<p class="en block">~~~~~</p>
<p>Classe – portée</p>
</th>
</tr>
<tr>
<td>
<p>R2.1</p>
</td>
<td>
<p class="en block">has type</p>
<p class="en block">~~~~~</p>
<p>a pour type</p>
</td>
<td>
<p class="en block">F1 Work. R2<strong> is derivative of (has derivative)</strong>: F1 Work</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F1_Œuvre</code>. <strong><code class="language-plaintext highlighter-rouge">R2_est_dérivé_de (a_pour_dérivé)</code></strong> : <code class="language-plaintext highlighter-rouge">F1_Œuvre</code></p>
</td>
<td>
<p class="en block"><strong>E55 Type</strong></p>
<p class="en block">~~~~~</p>
<p><strong><code class="language-plaintext highlighter-rouge">E55_Type</code></strong></p>
</td>
</tr>
<tr>
<td>
<p>R56.1</p>
</td>
<td>
<p class="en block">has type</p>
<p class="en block">~~~~~</p>
<p>a pour type</p>
</td>
<td>
<p class="en block">F12 Nomen: R56<strong> has related form (is related form of)</strong>: F12 Nomen</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F12_Nomen</code>. <strong><code class="language-plaintext highlighter-rouge">R56_a_pour_forme_connexe (est_la_forme_connexe_de)</code></strong> : <code class="language-plaintext highlighter-rouge">F12_Nomen</code></p>
</td>
<td>
<p class="en block"><strong>E55 Type</strong></p>
<p class="en block">~~~~~</p>
<p><strong><code class="language-plaintext highlighter-rouge">E55_Type</code></strong></p>
</td>
</tr>
<tr>
<td>
<p>R76.1</p>
</td>
<td>
<p class="en block">has type</p>
<p class="en block">~~~~~</p>
<p>a pour type</p>
</td>
<td>
<p class="en block">F2 Expression. R76<strong> is derivative of (has derivative)</strong>: F2 Expression</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F2_Expression</code>. <strong><code class="language-plaintext highlighter-rouge">R76_est_dérivé_de (a_pour_dérivé)</code></strong> : <code class="language-plaintext highlighter-rouge">F2_Expression</code></p>
</td>
<td>
<p class="en block"><strong>E55 Type</strong></p>
<p class="en block">~~~~~</p>
<p><strong><code class="language-plaintext highlighter-rouge">E55_Type</code></strong></p>
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

<h2 id="liste-des-proprietes-du-cidoccrm-utilisees-dans-lrmoo"><span class="en heading">5.7. List of CIDOC CRM properties used in LRM<sub>OO</sub> - </span>5.7. Liste des propriétés du CIDOC CRM utilisées dans LRM<sub>OO</sub></h2>

<table class="text">
<colgroup>
<col style="width:50%">
</colgroup>
<tbody>
<tr>
<td class="en">
<p>The list in this section identifies the properties in CIDOC CRM version 7.1.3 referred to by LRM<sub>OO</sub>. Relevant uses include: appearance in the mapping from IFLA LRM in section 8 or as an element of a path in a mapping statement, reference as immediate superproperty of properties defined in the model, or in a path appearing in a property declaration.<sub><em></em></sub></p>
<p></p>
<p>Table 9. CIDOC CRM Properties used in LRM<sub>OO</sub></p>
</td>
<td>
<p>Cette liste identifie les propriétés de la version 7.1.3 du CIDOC CRM auxquelles réfère le LRM<sub>OO</sub>, notamment : </p>
<ul><li><p>dans le cadre de la mise en correspondance entre le IFLA LRM et le LRM<sub>OO</sub>, laquelle est présentée en section 8 « <a href="https://cidoc-crm-fr.info/lrmoo/v1.0/mise-en-correspondance-iflalrm-lrmoo"><span class="underline">Mise en correspondance du IFLA LRM au LRM</span></a><sub><a href="https://cidoc-crm-fr.info/lrmoo/v1.0/mise-en-correspondance-iflalrm-lrmoo"><span class="underline">OO</span></a></sub> » ; </p>
</li>
<li><p>en tant qu’élément du chemin sémantique d’une mise en correspondance ; </p>
</li>
<li><p>à titre de référence à une super-propriété immédiate de propriétés définies dans le LRM<sub>OO </sub> ; </p>
</li>
<li><p>dans le chemin sémantique de la déclaration d’une propriété. </p>
</li></ul>
<p></p>
<p>Tableau 9 : Propriétés du CIDOC CRM utilisées dans LRM<sub>OO</sub></p>
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

<table>
    <tbody>
        <tr>
            <th>
                <p class="en block">Property ID</p>
                <p class="en block">~~~~~</p>
                <p>Identifiant de propriété</p>
            </th>
            <th>
                <p class="en block">Property Name</p>
                <p class="en block">~~~~~</p>
                <p>Nom de propriété</p>
            </th>
            <th>
                <p class="en block">Class – Domain</p>
                <p class="en block">~~~~~</p>
                <p>Classe – domaine</p>
            </th>
            <th>
                <p class="en block">Class – Range</p>
                <p class="en block">~~~~~</p>
                <p>Classe – portée</p>
            </th>
        </tr>
        <tr>
            <td>
                <p>P2</p>
            </td>
            <td>
                <p class="en block">has type (is type of)</p>
                <p class="en block">~~~~~</p>
                <p>a pour type (est le type de)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E1 CRM Entity</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E55 Type</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E55_Type</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P3</p>
            </td>
            <td>
                <p class="en block">has note </p>
                <p class="en block">~~~~~</p>
                <p>a pour note</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E1 CRM Entity</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E62 String</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E62_Chaîne_de_caractères</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P9</p>
            </td>
            <td>
                <p class="en block">consists of (forms part of)</p>
                <p class="en block">~~~~~</p>
                <p>comprend (fait partie de)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E4 Period</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E4_Période</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E4 Period</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E4_Période</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P14</p>
            </td>
            <td>
                <p class="en block">carried out by (performed)</p>
                <p class="en block">~~~~~</p>
                <p>a été effectué par (a effectué)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E7 Activity</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E7_Activité</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E39 Actor</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E39_Actant</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P15</p>
            </td>
            <td>
                <p class="en block">was influenced by (influenced)</p>
                <p class="en block">~~~~~</p>
                <p>a été influencé par (a influencé)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E7 Activity</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E7_Activité</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E1 CRM Entity</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P16</p>
            </td>
            <td>
                <p class="en block">used specific object (was used for)</p>
                <p class="en block">~~~~~</p>
                <p>a mobilisé l’objet spécifique (a été mobilisé pour)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E7 Activity</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E7_Activité</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E70 Thing</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E70_Chose</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P19</p>
            </td>
            <td>
                <p class="en block">was intended use of (was made for)</p>
                <p class="en block">~~~~~</p>
                <p>a été l’usage prévu de (a été élaboré pour)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E7 Activity</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E7_Activité</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E71 Human-Made Thing</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E71_Chose_élaborée_par_l’humain</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P31</p>
            </td>
            <td>
                <p class="en block">has modified (was modified by)</p>
                <p class="en block">~~~~~</p>
                <p>a modifié (a été modifié par) </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E11 Modification</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E11_Modification</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E18 Physical Thing</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P33</p>
            </td>
            <td>
                <p class="en block">used specific technique (was used by)</p>
                <p class="en block">~~~~~</p>
                <p>a mobilisé comme technique spécifique (a été la technique spécifique mise en œuvre dans)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E7 Activity</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E7_Activité</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E29 Design or Procedure</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E29_Conceptualisation_ou_procédure</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P43</p>
            </td>
            <td>
                <p class="en block">has dimension (is dimension of)</p>
                <p class="en block">~~~~~</p>
                <p>a pour dimension (est la dimension de)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E70 Thing</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E70_Chose</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E54 Dimension</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E54_Dimension</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P46</p>
            </td>
            <td>
                <p class="en block">is composed of (forms part of)</p>
                <p class="en block">~~~~~</p>
                <p>est composé de (fait partie de)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E18 Physical Thing</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E18 Physical Thing</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P49</p>
            </td>
            <td>
                <p class="en block">has former or current keeper (is former or current keeper of)</p>
                <p class="en block">~~~~~</p>
                <p>a pour actant détenteur actuel ou antérieur (est l’actant détenteur actuel ou antérieur de)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E18 Physical Thing</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E39 Actor</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E39_Actant</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P50</p>
            </td>
            <td>
                <p class="en block">has current keeper (is current keeper of)</p>
                <p class="en block">~~~~~</p>
                <p>a pour actant détenteur actuel (est l'actant détenteur actuel de)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E18 Physical Thing</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E39 Actor</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E39_Actant</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P51</p>
            </td>
            <td>
                <p class="en block">has former or current owner (is former or current owner of)</p>
                <p class="en block">~~~~~</p>
                <p>a pour propriétaire actuel ou antérieur (est l’actant propriétaire actuel ou antérieur de)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E18 Physical Thing</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E39 Actor</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E39_Actant</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P54</p>
            </td>
            <td>
                <p class="en block">has current permanent location (is current permanent location of)</p>
                <p class="en block">~~~~~</p>
                <p>a actuellement pour localisation fixe (est actuellement la localisation fixe de)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E19 Physical Object</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E19_Objet_matériel</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E53 Place</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E53_Lieu</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P55</p>
            </td>
            <td>
                <p class="en block">has current location (currently holds)</p>
                <p class="en block">~~~~~</p>
                <p>a actuellement pour localisation (est actuellement la localisation de)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E19 Physical Object</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E19_Objet_matériel</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E53 Place</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E53_Lieu</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P67</p>
            </td>
            <td>
                <p class="en block">refers to (is referred to by)</p>
                <p class="en block">~~~~~</p>
                <p>renvoie à (fait l’objet d’un renvoi par)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E89 Propositional Object</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E89_Objet_propositionnel</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E1 CRM Entity</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P72</p>
            </td>
            <td>
                <p class="en block">has language (is language of)</p>
                <p class="en block">~~~~~</p>
                <p>a pour langue (est la langue de)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E33 Linguistic Object</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E33_Objet_linguistique</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E56 Language</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E56_Langue</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P75</p>
            </td>
            <td>
                <p class="en block">possessed (is possessed by)</p>
                <p class="en block">~~~~~</p>
                <p>possède (est possédé par)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E39 Actor</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E39_Actant</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E30 Right</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E30_Droit</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P76</p>
            </td>
            <td>
                <p class="en block">has contact point (provides access to)</p>
                <p class="en block">~~~~~</p>
                <p>a pour coordonnées (permet de contacter)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E39 Actor</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E39_Actant</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E41 Appellation</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E41_Appellation</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P82</p>
            </td>
            <td>
                <p class="en block">at some time within</p>
                <p class="en block">~~~~~</p>
                <p>a eu lieu durant</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E52 Time-span</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E52_Intervalle_temporel</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E61 Time Primitive</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E61_Primitive_temporelle</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P86</p>
            </td>
            <td>
                <p class="en block">falls within (contains)</p>
                <p class="en block">~~~~~</p>
                <p>s’insère dans (contient)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E52 Time-span</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E52_Intervalle_temporel</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E52 Time-span</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E52_Intervalle_temporel</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P89</p>
            </td>
            <td>
                <p class="en block">falls within (contains)</p>
                <p class="en block">~~~~~</p>
                <p>s’insère dans (contient)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E53 Place</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E53_Lieu</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E53 Place</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E53_Lieu</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P90</p>
            </td>
            <td>
                <p class="en block">has value</p>
                <p class="en block">~~~~~</p>
                <p>a pour valeur</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E54 Dimension</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E54_Dimension</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E60 Number</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E60_Nombre</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P91</p>
            </td>
            <td>
                <p class="en block">has unit (is unit of)</p>
                <p class="en block">~~~~~</p>
                <p>a pour unité de mesure (est l’unité de mesure de)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E54 Dimension</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E54_Dimension</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E58 Measurement Unit</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E58_Unité_de_mesure</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P94</p>
            </td>
            <td>
                <p class="en block">has created (was created by)</p>
                <p class="en block">~~~~~</p>
                <p>a créé (a été créé par)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E65 Creation</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E65_Création</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E28 Conceptual Object</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E28_Objet_conceptuel</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P103</p>
            </td>
            <td>
                <p class="en block">was intended for (was intention of)</p>
                <p class="en block">~~~~~</p>
                <p>a eu pour raison d’être (a été la raison d’être de)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E71 Human-Made Thing</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E71_Chose_élaborée_par_l’humain</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E55 Type</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E55_Type</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P104</p>
            </td>
            <td>
                <p class="en block">is subject to (applies to)</p>
                <p class="en block">~~~~~</p>
                <p>est soumis à (s’applique à)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E72 Legal Object</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E72_Objet_juridique</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E30 Right</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E30_Droit</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P106</p>
            </td>
            <td>
                <p class="en block">is composed of (forms part of)</p>
                <p class="en block">~~~~~</p>
                <p>est composé de (fait partie de)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E90 Symbolic Object</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E90_Objet_symbolique</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E90 Symbolic Object</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E90_Objet_symbolique</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P107</p>
            </td>
            <td>
                <p class="en block">has current or former member (is current or former member of)</p>
                <p class="en block">~~~~~</p>
                <p>a pour membre actuel ou antérieur (est le membre actuel ou antérieur de)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E74 Group</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E74_Groupe</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E39 Actor</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E39_Actant</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P108</p>
            </td>
            <td>
                <p class="en block">has produced (was produced by)</p>
                <p class="en block">~~~~~</p>
                <p>a produit (a été produit par)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E12 Production</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E12_Production</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E24 Physical Human-Made Thing</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E24_Chose_matérielle_élaborée_par_l’humain</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P109</p>
            </td>
            <td>
                <p class="en block">has current or former curator (is current or former curator of)</p>
                <p class="en block">~~~~~</p>
                <p>a pour responsable actuel ou antérieur de la collection (est responsable actuel ou antérieur de la collection)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E78 Curated Holding</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E78_Collection</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E39 Actor</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E39_Actant</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P125</p>
            </td>
            <td>
                <p class="en block">used object of type (was type of object used in)</p>
                <p class="en block">~~~~~</p>
                <p>a mobilisé l’objet du type (a été le type d’objet employé pour)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E7 Activity</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E7_Activité</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E55 Type</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E55_Type</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P128</p>
            </td>
            <td>
                <p class="en block">carries (is carried by)</p>
                <p class="en block">~~~~~</p>
                <p>est le support de (a pour support)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E18 Physical Thing</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E90 Symbolic Object</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E90_Objet_symbolique</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P129</p>
            </td>
            <td>
                <p class="en block">is about (is subject of)</p>
                <p class="en block">~~~~~</p>
                <p>a pour sujet (est le sujet de)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E89 Propositional Object</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E89_Objet_propositionnel</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E1 CRM Entity</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P130</p>
            </td>
            <td>
                <p class="en block">shows features of (features are also found on)</p>
                <p class="en block">~~~~~</p>
                <p>présente les caractéristiques de (a les caractéristiques aussi présentes sur)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E70 Thing</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E70_Chose</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E70 Thing</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E70_Chose</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P140</p>
            </td>
            <td>
                <p class="en block">assigned attribute to (was attributed by)</p>
                <p class="en block">~~~~~</p>
                <p>a assigné l’attribut à (a reçu l’attribut par)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E13 Attribute Assignment</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E13_Assignation_d’attribut</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E1 CRM Entity</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P141</p>
            </td>
            <td>
                <p class="en block">assigned (was assigned by)</p>
                <p class="en block">~~~~~</p>
                <p>a assigné (a été assigné par)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E13 Attribute Assignment</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E13_Assignation_d’attribut</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E1 CRM Entity</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P148</p>
            </td>
            <td>
                <p class="en block">has component (is component of)</p>
                <p class="en block">~~~~~</p>
                <p>a pour composant (est le composant de)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E89 Propositional Object</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E89_Objet_propositionnel</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E89 Propositional Object</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E89_Objet_propositionnel</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P151</p>
            </td>
            <td>
                <p class="en block">was formed from (participated in)</p>
                <p class="en block">~~~~~</p>
                <p>a été formé à partir de (a participé à)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E66 Formation</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E66_Formation</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E74 Group</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E74_Groupe</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P165</p>
            </td>
            <td>
                <p class="en block">incorporates (is incorporated in)</p>
                <p class="en block">~~~~~</p>
                <p>inclut (est inclus dans)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E73 Information Object</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E73_Objet_informationnel</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E90 Symbolic Object</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E90_Objet_symbolique</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P168</p>
            </td>
            <td>
                <p class="en block">place is defined by (defines place)</p>
                <p class="en block">~~~~~</p>
                <p>lieu défini par (définit le lieu)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E53 Place</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E53_Lieu</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E94 Space Primitive</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E94_Primitive_spatiale</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P170</p>
            </td>
            <td>
                <p class="en block">defines time (time is defined by)</p>
                <p class="en block">~~~~~</p>
                <p>définit le temps (temps défini par)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E61 Time Primitive</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E61_Primitive_temporelle</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E52 Time-span</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E52_Intervalle_temporel</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P186</p>
            </td>
            <td>
                <p class="en block">produced things of product type (is produced by)</p>
                <p class="en block">~~~~~</p>
                <p>a produit la chose du type (est produit par)</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E12 Production</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E12_Production</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E99 Product Type</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E99_Modèle_de_produit</code></strong>
                </p>
            </td>
        </tr>
        <tr>
            <td>
                <p>P190</p>
            </td>
            <td>
                <p class="en block">has symbolic content (is symbolic content of)</p>
                <p class="en block">~~~~~</p>
                <p>a pour contenu symbolique</p>
            </td>
            <td>
                <p class="en block">
                    <strong>E90 Symbolic Object</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E90_Objet_symbolique</code></strong>
                </p>
            </td>
            <td>
                <p class="en block">
                    <strong>E62 String</strong>
                </p>
                <p class="en block">~~~~~</p>
                <p>
                    <strong><code class="language-plaintext highlighter-rouge">E62_Chaîne_de_caractères</code></strong>
                </p>
            </td>
        </tr>
    </tbody>
</table>

