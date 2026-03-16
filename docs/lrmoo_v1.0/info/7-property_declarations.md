---
layout: page
title: 7. Déclaration des propriétés du LRMoo
titleEn: 7. LRMoo Property Declarations - 7. Déclaration des propriétés du LRMoo
permalink: /lrmoo/v1.0/proprietes/declaration-des-proprietes-du-lrmoo
sidebar: lrmoo_v10
group: proprietes
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
<p>The properties of LRM<sub>OO</sub> are comprehensively declared in this section using the following format:</p>
<ul><li><p>Property labels are presented as headings in bold face, preceded by unique property identifiers.</p>
</li>
<li><p>The line “Domain:” declares the class for which the property is defined.</p>
</li>
<li><p>The line “Range:” declares the class to which the property points, or that provides the values for the property.</p>
</li>
<li><p>The line “Shortcut of:” declares the chain of CIDOC CRM and/or LRM<sub>OO</sub> properties of which the LRM<sub>OO</sub> property is a shortcut, whenever it cannot be simply declared as a subproperty of a pre-existing property (note however that when an LRM<sub>OO</sub> property is <em>both</em> a subproperty of a pre-existing property <em>and</em> a shortcut, the detailed path of which it is a shortcut is only mentioned in the scope note).</p>
</li>
<li><p>The line “Inverse shortcut of:” declares the chain of CIDOC CRM and/or LRM<sub>OO</sub> properties that are implied by the LRM<sub>OO</sub> property, whenever it cannot be simply declared as a subproperty of a pre-existing property. That is, if the LRM<sub>OO</sub> property holds, the path also holds, however, the path alone is not sufficient to imply that the LRM<sub>OO</sub> property holds.</p>
</li>
<li><p>The line “Subproperty of:” is a cross-reference to any superproperties the property may have, in either CIDOC CRM or LRM<sub>OO</sub>. All LRM<sub>OO</sub> properties that fall under the scope of the CIDOC CRM are, either directly or indirectly, subproperties of at least one CIDOC CRM property. However, this line remains empty for LRM<sub>OO</sub> properties that are shortcuts or inverse shortcuts of more developed paths that involve CIDOC CRM properties and/or their LRM<sub>OO</sub> subproperties.</p>
</li>
<li><p>The line “Superproperty of:” is a cross-reference to any subproperties the property may have.</p>
</li>
<li><p>The line “Quantification:” declares the possible number of occurrences for domain and range class instances for the property. Possible values are enumerated in section 4.4.</p>
</li>
<li><p>The label “Scope note:” precedes the textual definition of the concept the property represents.</p>
</li>
<li><p>The label “Properties:” introduces any properties the property may have (.1 properties).</p>
</li>
<li><p>The label “Examples:” precedes a list of examples of instances of this property.</p>
</li>
<li><p>In some cases the superproperty of a property may be listed as <em>Outside of CIDOC CRM Scope</em>. This indicates that the property that should be its superproperty is outside of the coverage of CIDOC CRM.</p>
</li></ul>
</td>
<td>
<p>Les propriétés du <em>Modèle conceptuel pour l’information bibliographique, orientation objet </em>(LRM<sub>OO</sub>) sont déclarées ici selon la forme suivante : </p>
<ul><li><p>Les étiquettes de propriété sont présentées comme des titres en gras précédés de l’identifiant unique de la propriété.</p>
</li>
<li><p>La ligne « Domaine : » déclare la classe pour laquelle la propriété est définie.</p>
</li>
<li><p>La ligne « Portée : » déclare la classe vers laquelle la propriété pointe ou celle qui fournit les valeurs de la propriété.</p>
</li>
<li><p>La ligne « Raccourci de : » déclare la suite de propriétés du <em>Modèle conceptuel de référence du Comité international pour la documentation du Conseil international des musées</em> (CIDOC CRM) ou du LRM<sub>OO</sub> dont la propriété LRM<sub>OO</sub> est un raccourci lorsqu’elle ne peut pas être simplement déclarée sous-propriété d’une propriété existante (lorsqu’une propriété LRM<sub>OO</sub> est à la fois une sous-propriété d’une propriété existante et d’un raccourci, le chemin sémantique détaillé dont c’est un raccourci n’est mentionné que dans la note d’application).</p>
</li>
<li><p>La ligne « Raccourci inverse de : » déclare la suite de propriétés du CIDOC CRM ou du LRM<sub>OO</sub> qui mobilise la propriété LRM<sub>OO</sub> lorsqu’elle ne peut pas être simplement déclarée sous-propriété d’une propriété existante. Ainsi, si une propriété LRM<sub>OO</sub> est valide, ce chemin sémantique est lui aussi valide. Cependant, le chemin sémantique lui-même n’est pas suffisant pour déterminer que la propriété LRM<sub>OO</sub> est valide. </p>
</li>
<li><p>La ligne « Sous-propriété de : » est un co-référencement des super-propriétés que peut avoir la propriété, que ce soit dans le CIDOC CRM ou le LRM<sub>OO</sub>. Toutes les propriétés du LRM<sub>OO</sub> qui sont dans le champ d’application du CIDOC CRM sont directement ou indirectement des sous-propriétés d’au moins une propriété du CIDOC CRM. Par contre, aucune information ne se trouve dans cette ligne lorsque les propriétés LRM<sub>OO</sub> sont des raccourcis ou raccourcis inverses de chemins sémantiques plus développés impliquant des propriétés du CIDOC CRM ou leur sous-propriétés du LRM<sub>OO</sub>. </p>
</li>
<li><p>La ligne « Super-propriété de : » est un co-référencement des sous-propriétés que peut avoir la propriété.</p>
</li>
<li><p>La ligne « Quantification : » déclare le nombre possible d’occurrences d’instances de la classe de domaine et de la classe de portée pour la propriété (les valeurs possibles sont énumérées dans la section « <a href="https://cidoc-crm-fr.info/lrmoo/v1.0/description-du-modele#quantificateurs-de-proprietes"><span class="underline">Quantificateurs de propriétés</span></a> »). </p>
</li>
<li><p>L’étiquette « Note d’application : » précède la définition textuelle du concept que représente la propriété.</p>
</li>
<li><p>L’étiquette « Propriétés : » introduit les propriétés de la propriété (propriétés « .1 ») lorsque celle-ci en possède.</p>
</li>
<li><p>L’étiquette « Exemples : » précède une liste d’exemples d’instances de la propriété qui illustre comment elle devrait être utilisée, de plus : </p>
</li>
<li><p>Si l’exemple illustre aussi l’instance d’une sous-propriété de la propriété, l’identifiant unique de cette sous-classe est indiqué entre parenthèses. </p>
</li>
<li><p>Si l’exemple illustre l’instanciation de deux propriétés, l’identifiant unique de chacune est indiqué entre parenthèses. </p>
</li>
<li><p>Dans certains cas, la super-propriété d’une propriété peut être qualifiée de propriété dépassant le champ d’application du CIDOC CRM. Ceci indique que la propriété qui devrait être sa super-propriété outrepasse le champ d’application du CIDOC CRM.</p>
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
<p>Cette traduction est adaptée de la section miroir « <a href="https://cidoc-crm-fr.info/v7.1.3/proprietes/declaration-des-proprietes-du-cidoccrm"><span class="underline">Déclaration des propriétés du CIDOC CRM</span></a> » du CIDOC CRM.</p>
</td>
</tr>
<tr>
<th style="width:15%"><p><em>Références</em></p>
</th>
<td colspan="1">
<p>CIDOC CRM Special Interest Group. « CIDOC CRM Version 7.1.3 ». Traduit par Frédéric Bricaud, Camille Crevier-Lalonde, Stephen Hart, Karine Léonard Brouillet, Marie-Elaine Mathieu, Philippe Michon, Marielle St-Germain, et Marie-Pier Blain. Traduction en français du CIDOC CRM, 23 août 2024.<a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline"> </span></a><a href="https://cidoc-crm-fr.info/v7.1.3/information/introduction"><span class="underline">https://cidoc-crm-fr.info/v7.1.3/information/introduction</span></a>.<em></em></p>
</td>
</tr>
</tbody>
</table>

