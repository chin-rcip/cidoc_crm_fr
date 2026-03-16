---
layout: page
title: 9. Les classes et propriétés du FRBRoo transférées au CRMsoc
titleEn: 9. FRBRoo Classes and Properties transferred to CRMsoc - 9. Les classes et propriétés du FRBRoo transférées au CRMsoc
permalink: /lrmoo/v1.0/frbroo_crmsoc/les-classes-et-proprietes-du-frbroo-transferees-au-crmsoc
sidebar: lrmoo_v10
group: frbroo_crmsoc
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
<p>The classes and properties declared in this section were declared in FRBR<sub>OO</sub> version 2.4 and have not been deprecated. However, they are not necessary for an implementation of LRM<sub>OO</sub>. They should be implemented as a transition mechanism for implementations of the superseded model FRBR<sub>OO</sub> version 2.4 that require them. They are intended to be transferred to CRMsoc.</p>
</td>
<td>
<p>Les classes et propriétés déclarées dans cette section ont été déclarées dans la version 2.4 des <em>Fonctionnalités requises des notices bibliographiques, orientation objet </em>(FRBR<sub>OO</sub>) et n’ont jamais été dépréciées. Elles ne sont néanmoins pas nécessaires à une implémentation du <em>Modèle conceptuel pour l’information bibliographique, orientation objet</em> (LRM<sub>OO</sub>). Elles devraient éventuellement être transférées au <em>Modèle conceptuel de référence pour les phénomènes sociaux</em> (CRM<sub>SOC</sub>) et devraient être implémentées à titre transitionnel pour l’implémentation du modèle FRBR<sub>OO</sub> 2.4, maintenant remplacé, qui en exige l’utilisation. </p>
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

<p><em><span class="en">Table 10. FRBR<sub>OO</sub> Classes transferred to CRM<sub>SOC</sub> - </span><span>Tableau 10 : Classes du FRBR<sub>OO</sub> transférées à CRM<sub>SOC</sub></span></em></p>

<table>
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
<p>Nom de la classe</p>
</th>
</tr>
<tr>
<td>
<p>F38</p>
</td>
<td>
<p class="en block">Character</p>
<p class="en block">~~~~~</p>
<p>Personne fictive</p>
</td>
</tr>
<tr>
<td>
<p>F51</p>
</td>
<td>
<p class="en block">Pursuit</p>
<p class="en block">~~~~~</p>
<p>Pratique</p>
</td>
</tr>
<tr>
<td>
<p>F52</p>
</td>
<td>
<p class="en block">Name Use Activity</p>
<p class="en block">~~~~~</p>
<p>Activité d’utilisation du nom</p>
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
<p><em></em></p>
<p><em></em></p>
</td>
</tr>
</tbody>
</table>

<p><em><span class="en">Table 11. FRBR<sub>OO</sub> Properties transferred to CRM<sub>SOC</sub> - </span><span>Tableau 11 : Propriétés du FRBR<sub>OO</sub> transférées à CRM<sub>SOC</sub></span></em></p>

<table>
<tbody>
<tr>
<th>
<p class="en block"><strong>Property ID</strong></p>
<p class="en block">~~~~~</p>
<p><strong>Identifiant de propriété</strong></p>
</th>
<th>
<p class="en block"><strong>Property Name</strong></p>
<p class="en block">~~~~~</p>
<p><strong>Nom de propriété</strong></p>
</th>
<th>
<p class="en block"><strong>Class – Domain</strong></p>
<p class="en block">~~~~~</p>
<p><strong>Classe – domaine</strong></p>
</th>
<th>
<p class="en block"><strong>Class – Range</strong></p>
<p class="en block">~~~~~</p>
<p><strong>Classe – portée</strong></p>
</th>
</tr>
<tr>
<td>
<p>R57</p>
</td>
<td>
<p class="en block">is based on (is basis for)</p>
<p class="en block">~~~~~</p>
<p>est fondé sur (est la base de)</p>
</td>
<td>
<p class="en block">F38 Character</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F38_Personne_fictive</code></p>
</td>
<td>
<p class="en block"><strong>E39 Actor</strong></p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">E39_Actant</code></p>
</td>
</tr>
<tr>
<td>
<p>R58</p>
</td>
<td>
<p class="en block">has fictional member (is fictional member of)</p>
<p class="en block">~~~~~</p>
<p>a pour membre fictif (est le membre fictif de)</p>
</td>
<td>
<p class="en block">F38 Character</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F38_Personne_fictive</code></p>
</td>
<td>
<p class="en block">F38 Character</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F38_Personne_fictive</code></p>
</td>
</tr>
<tr>
<td>
<p>R59</p>
</td>
<td>
<p class="en block">had typical subject (was typical subject of)</p>
<p class="en block">~~~~~</p>
<p>avait pour sujet de la pratique (était le sujet de la pratique de)</p>
</td>
<td>
<p class="en block">F51 Pursuit</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F51_Pratique</code></p>
</td>
<td>
<p class="en block"><strong>E1 CRM Entity</strong></p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></p>
</td>
</tr>
<tr>
<td>
<p>R60</p>
</td>
<td>
<p class="en block">used to use language (was language used by)</p>
<p class="en block">~~~~~</p>
<p>utilisait pour langage (était le langage utilisé par)</p>
</td>
<td>
<p class="en block">F51 Pursuit</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F51_Pratique</code></p>
</td>
<td>
<p class="en block"><strong>E56 Language</strong></p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">E56_Langue</code></p>
</td>
</tr>
<tr>
<td>
<p>R61</p>
</td>
<td>
<p class="en block">occurred in kind of context (was kind of context for)</p>
<p class="en block">~~~~~</p>
<p>s’est produit dans le type de contexte (était le type de contexte de)</p>
</td>
<td>
<p class="en block">F52 Name Use Activity</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F52_Activité_d’utilisation_du_nom</code></p>
</td>
<td>
<p class="en block"><strong>E55 Type</strong></p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">E55_Type</code></p>
</td>
</tr>
<tr>
<td>
<p>R62</p>
</td>
<td>
<p class="en block">was used for membership in (was context for)</p>
<p class="en block">~~~~~</p>
<p>a été utilisé pour l’adhésion à (était le contexte de)</p>
</td>
<td>
<p class="en block">F52 Name Use Activity</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F52_Activité_d’utilisation_du_nom</code></p>
</td>
<td>
<p class="en block"><strong>E74 Group</strong></p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">E74_Groupe</code></p>
</td>
</tr>
<tr>
<td>
<p>R63</p>
</td>
<td>
<p class="en block">named (was named by)</p>
<p class="en block">~~~~~</p>
<p>a nommé (a été nommé par)</p>
</td>
<td>
<p class="en block">F52 Name Use Activity</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F52_Activité_d’utilisation_du_nom</code></p>
</td>
<td>
<p class="en block"><strong>E1 CRM Entity</strong></p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code></p>
</td>
</tr>
<tr>
<td>
<p>R64</p>
</td>
<td>
<p class="en block">used name (was name used by)</p>
<p class="en block">~~~~~</p>
<p>a utilisé pour nom (était le nom utilisé par)</p>
</td>
<td>
<p class="en block">F52 Name Use Activity</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F52_Activité_d’utilisation_du_nom</code></p>
</td>
<td>
<p class="en block"><strong>E41 Appellation</strong></p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">E41_Appellation</code></p>
</td>
</tr>
</tbody>
</table>

<p><em><span class="en">Table 12. FRBR<sub>OO</sub> .1 Properties transferred to CRM<sub>SOC</sub> - </span><span>Tableau 12 : Propriétés « .1 » du FRBR<sub>OO</sub> transférées à CRM<sub>SOC</sub></span></em></p>

<table>
<tbody>
<tr>
<th>
<p class="en block"><strong>Property ID</strong></p>
<p class="en block">~~~~~</p>
<p><strong>Identifiant de propriété</strong></p>
</th>
<th>
<p class="en block"><strong>Property Name</strong></p>
<p class="en block">~~~~~</p>
<p><strong>Nom de propriété</strong></p>
</th>
<th>
<p class="en block"><strong>Property – Domain</strong></p>
<p class="en block">~~~~~</p>
<p><strong>Propriété – domaine</strong></p>
</th>
<th>
<p class="en block"><strong>Class – Range</strong></p>
<p class="en block">~~~~~</p>
<p><strong>Classe – portée</strong></p>
</th>
</tr>
<tr>
<td>
<p>R60.1</p>
</td>
<td>
<p class="en block">has type of use</p>
<p class="en block">~~~~~</p>
<p>a pour type d’usage</p>
</td>
<td>
<p class="en block">F51 Pursuit. R60 used to use language (was language used by): E56 Language</p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">F51_Pratique</code>. <code class="language-plaintext highlighter-rouge">R60_utilisait_la_langue (était_la_langue_utilisée_par)</code> : <code class="language-plaintext highlighter-rouge">E56_Langue</code></p>
</td>
<td>
<p class="en block"><strong>E55 Type</strong></p>
<p class="en block">~~~~~</p>
<p><code class="language-plaintext highlighter-rouge">E55_Type</code></p>
</td>
</tr>
<tr>
<th><p><em>Note de traduction</em></p>
</th>
<td colspan="3">
</td>
</tr>
<tr>
<th><p><em>Références</em></p>
</th>
<td colspan="3">
<p><em></em></p>
</td>
</tr>
</tbody>
</table>

