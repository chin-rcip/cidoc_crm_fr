---
layout: page
title: Index
permalink: /ressources/index
sidebar: index
tab: ressources
date: 2021-06-03
---

> *Avertissement : Cette traduction en français du CIDOC CRM est en cours.<br><br>La documentation présentée ici est un travail actuellement en cours. À ce titre, bien qu’elle soit publiquement disponible, elle ne constitue en rien une publication officielle et des changements y sont apportés sur une base régulière. Par conséquent, il est préférable d’attendre une publication officielle de l’entièreté du contenu du CIDOC CRM avant d’implémenter cette traduction.*

> *Disclaimer: This French Translation of the CIDOC CRM is currently in progress.<br><br>The documentation hereby accessible is a work in progress. As such, although it is publically released, it does not constitute an official publication and changes are made on an ongoing basis. Therefore, it is preferable to wait for an official publication of the entire content of CIDOC CRM before implementing this translation.*

## Notes méthodologiques {#notes-methodologiques}

Lors de la traduction des entités, des principes d’uniformisation, de concordance et de rationalisation ont été priorisés de sorte que le Groupe de traduction a utilisé (dans la mesure du possible) :

  - les mêmes termes (uniformisation); 

  - les mêmes temps (concordance); 

  - les mêmes styles (nom pour les classes, verbe conjugué au masculin singulier pour les propriétés) d’une entité à l’autre; 

  - les appellations courtes plutôt que longues (rationalisation). 

Dans de rares cas, CIDOC CRM a dérogé de sa propre norme de nommage des propriétés en utilisant l’imparfait (*was*) plutôt que le passé composé (*had*). Le Groupe de traduction a fait le choix de conserver le passé composé qui précise que ce dont il est question est dans un passé *absolu* plutôt que *relatif* (ce qui est conforme avec les définitions concernées). Cette question fera l’objet d’une discussion avec le CRM SIG prochainement. 

## Methodological Notes

Principles of uniformity, consistency, and rationalization have been prioritized in the translation of the following entity labels. As much as possible, the Translation Group has opted to use: 

  - the same terms (uniformity);

  - the same tense (consistency);

  - the same styles (names for classes, masculine singular conjugation for property verbs) across entities; 

  - shorter rather than longer appellations (rationalization). 

In rare cases, CIDOC CRM has not followed its property naming standard by using the past tense (was) rather than the past perfect (had). The Translation Group has elected to use the *passé composé* throughout as it indicates that the subject is in an *absolute* past rather than a *relative* one (which is consistent with the definitions this pertains to). This issue will be discussed with the CRM SIG eventually.

## CIDOC CRM - EN/FR

<table>
<thead>
<tr class="header">
<th><strong>CODE</strong></th>
<th><strong>EN</strong></th>
<th><strong>FR</strong></th>
<th><strong>Note</strong></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td>E1</td>
<td>CRM Entity</td>
<td>Entité CRM</td>
<td><code class="language-plaintext highlighter-rouge">E1_Entité_CRM</code> </td>
</tr>
<tr class="even">
<td>E2</td>
<td>Temporal Entity</td>
<td>Entité temporelle</td>
<td><code class="language-plaintext highlighter-rouge">E2_Entité_temporelle</code> </td>
</tr>
<tr class="odd">
<td>E3</td>
<td>Condition State</td>
<td>État matériel</td>
<td><p><code class="language-plaintext highlighter-rouge">E3_État_matériel</code> </p>
<p>Condition est un terme qui porte sur une situation factuelle reposant sur d'autres faits alors que l'état porte sur une situation à un moment donné.</p></td>
</tr>
<tr class="even">
<td>E4</td>
<td>Period</td>
<td>Période</td>
<td><code class="language-plaintext highlighter-rouge">E4_Période</code> </td>
</tr>
<tr class="odd">
<td>E5</td>
<td>Event</td>
<td>Évènement</td>
<td><code class="language-plaintext highlighter-rouge">E5_Évènement</code> </td>
</tr>
<tr class="even">
<td>E6</td>
<td>Destruction</td>
<td>Destruction</td>
<td><code class="language-plaintext highlighter-rouge">E6_Destruction</code> </td>
</tr>
<tr class="odd">
<td>E7</td>
<td>Activity</td>
<td>Activité</td>
<td><code class="language-plaintext highlighter-rouge">E7_Activité</code> </td>
</tr>
<tr class="even">
<td>E8</td>
<td>Acquisition</td>
<td>Acquisition</td>
<td><code class="language-plaintext highlighter-rouge">E8_Acquisition</code> </td>
</tr>
<tr class="odd">
<td>E9</td>
<td>Move</td>
<td>Déplacement</td>
<td><code class="language-plaintext highlighter-rouge">E9_Déplacement</code> </td>
</tr>
<tr class="even">
<td>E10</td>
<td>Transfer of Custody</td>
<td>Transfert de la garde</td>
<td><p><code class="language-plaintext highlighter-rouge">E10_Transfert_de_la_garde</code> </p>
<p>À l'heure actuelle, la seule traduction officielle sur <a href="https://www.btb.termiumplus.gc.ca/tpv2alpha/alpha-fra.html?lang=fra&amp;i=1&amp;index=alt&amp;srchtxt=CUSTODIANSHIP%20TRANSFER"><strong>Termium</strong></a> concerne l'immobilier donc c'est une équivalence à valider ou officiellement établir. Ceci dit, il semble y avoir un <a href="https://cours-de-droit.net/la-garde-de-la-chose-et-le-gardien-article-1242-du-code-civil-a148631084/"><strong>concept légal</strong></a> en France qui en ferait une traduction valable.</p></td>
</tr>
<tr class="odd">
<td>E11</td>
<td>Modification</td>
<td>Modification</td>
<td><code class="language-plaintext highlighter-rouge">E11_Modification</code></td>
</tr>
<tr class="even">
<td>E12</td>
<td>Production</td>
<td>Production</td>
<td><code class="language-plaintext highlighter-rouge">E12_Production</code> </td>
</tr>
<tr class="odd">
<td>E13</td>
<td>Attribute Assignment</td>
<td>Attribution</td>
<td><p><code class="language-plaintext highlighter-rouge">E13_Attribution</code> </p>
<p>Puisqu'il s'agit d'attribuer un attribut (une formulation redondante) et que la nature de ce qui est attribué dans la version francophone (c.-à-d. attribuer) est indiqué dans la formulation, il semble préférable de simplifier.</p></td>
</tr>
<tr class="even">
<td>E14</td>
<td>Condition Assessment</td>
<td>Évaluation d'état matériel</td>
<td><code class="language-plaintext highlighter-rouge">E14_Évaluation_d’état_matériel</code> </td>
</tr>
<tr class="odd">
<td>E15</td>
<td>Identifier Assignment</td>
<td>Attribution d'identifiant</td>
<td><p><code class="language-plaintext highlighter-rouge">E15_Attribution_d’identifiant</code> </p>
<p>Il semble préférable d'utiliser Identifiant pour référer au code unique désignant une chose ou une personne puisqu'un Identificateur est un symbole employé pour représenter une variable ou une fonction et que ce terme pourra s'avérer utile ailleurs dans l'effort de traduction, soit afin de désigner de tels symboles, ou lorsque viendra le temps de qualifier d'autres éléments.</p></td>
</tr>
<tr class="even">
<td>E16</td>
<td>Measurement</td>
<td>Mesurage</td>
<td><code class="language-plaintext highlighter-rouge">E16_Mesurage</code> </td>
</tr>
<tr class="odd">
<td>E17</td>
<td>Type Assignment</td>
<td>Attribution de type</td>
<td><code class="language-plaintext highlighter-rouge">E17_Attribution_de_type</code> </td>
</tr>
<tr class="even">
<td>E18</td>
<td>Physical Thing</td>
<td>Chose Matérielle</td>
<td><p><code class="language-plaintext highlighter-rouge">E18_Chose_matérielle</code> </p>
<p>Physical thing sera traduit par chose matérielle qui comprend Physical Object-Objet matériel donc pour être cohérents on utilisera Physical Item - entité matérielle.</p></td>
</tr>
<tr class="odd">
<td>E19</td>
<td>Physical Object</td>
<td>Objet matériel</td>
<td><code class="language-plaintext highlighter-rouge">E19_Objet_matériel</code> </td>
</tr>
<tr class="even">
<td>E20</td>
<td>Biological Object</td>
<td>Objet biologique</td>
<td><code class="language-plaintext highlighter-rouge">E20_Objet_biologique</code> </td>
</tr>
<tr class="odd">
<td>E21</td>
<td>Person</td>
<td>Personne</td>
<td><code class="language-plaintext highlighter-rouge">E21_Personne</code> </td>
</tr>
<tr class="even">
<td>E22</td>
<td>Human-Made Object</td>
<td>Objet élaboré par l’humain</td>
<td><p><code class="language-plaintext highlighter-rouge">E22_Objet_élaboré_par_l’humain</code> </p>
<p>La fabrication repose sur le fait d'utiliser des matières premières de manière à imiter un original alors que le façonnement reflète le fait qu'il s'agit d'une chose faite par l'humain sans reposer sur le fait d'utiliser des matières premières, ce qui est plus près de la définition originale. Ce terme a été préféré à « fabriqué » car il signale la notion de fabrication faite par l’humain plus précisément alors que la « fabrication » en général pourrait relever d’autres agents. </p></td>
</tr>
<tr class="odd">
<td>E24</td>
<td>Physical Human-Made Thing</td>
<td>Chose matérielle élaborée par l’humain</td>
<td><p><code class="language-plaintext highlighter-rouge">E24_Chose_matérielle_élaborée_par_l’humain</code> </p>
<p>La fabrication repose sur le fait d'utiliser des matières premières de manière à imiter un original alors que le façonnement reflète le fait qu'il s'agit d'une chose faite par l'humain sans reposer sur le fait d'utiliser des matières premières, ce qui est plus près de la définition originale.</p></td>
</tr>
<tr class="even">
<td>E25</td>
<td>Human-Made Feature</td>
<td>Caractéristique élaborée par l’humain</td>
<td><p><code class="language-plaintext highlighter-rouge">E25_Caractéristique_élaborée_par_l’humain</code> </p>
<p>La fabrication repose sur le fait d'utiliser des matières premières de manière à imiter un original alors que le façonnement reflète le fait qu'il s'agit d'une chose faite par l'humain sans reposer sur le fait d'utiliser des matières premières, ce qui est plus près de la définition originale.</p></td>
</tr>
<tr class="odd">
<td>E26</td>
<td>Physical Feature</td>
<td>Caractéristique physique</td>
<td><code class="language-plaintext highlighter-rouge">E26_Caractéristique_physique</code> </td>
</tr>
<tr class="even">
<td>E27</td>
<td>Site</td>
<td>Site</td>
<td><code class="language-plaintext highlighter-rouge">E27_Site</code> </td>
</tr>
<tr class="odd">
<td>E28</td>
<td>Conceptual Object</td>
<td>Objet conceptuel</td>
<td><code class="language-plaintext highlighter-rouge">E28_Objet_conceptuel</code> </td>
</tr>
<tr class="even">
<td>E29</td>
<td>Design or Procedure</td>
<td>Conceptualisation ou procédure</td>
<td><p><code class="language-plaintext highlighter-rouge">E29_Conceptualisation_ou_procédure</code> </p>
<p>Le terme « conceptualisation » a été préféré à « conception » car cette dernière inclut à la fois le processus d’idéation mentale (concevoir une idée) et le résultat de ce processus, alors que la « conceptualisation » signale qu’il s’agit d’organiser des concepts sans que ce qui en résulte ne soit déterminant, ce qui est plus près de la définition originale de la classe. </p></td>
</tr>
<tr class="odd">
<td>E30</td>
<td>Right</td>
<td>Droit</td>
<td><code class="language-plaintext highlighter-rouge">E30_Droit</code> </td>
</tr>
<tr class="even">
<td>E31</td>
<td>Document</td>
<td>Document</td>
<td><code class="language-plaintext highlighter-rouge">E31_Document</code> </td>
</tr>
<tr class="odd">
<td>E32</td>
<td>Authority Document</td>
<td>Document de référence</td>
<td><code class="language-plaintext highlighter-rouge">E32_Document_de_référence</code> </td>
</tr>
<tr class="even">
<td>E33</td>
<td>Linguistic Object</td>
<td>Objet linguistique</td>
<td><code class="language-plaintext highlighter-rouge">E33_Objet_linguistique</code> </td>
</tr>
<tr class="odd">
<td>E34</td>
<td>Inscription</td>
<td>Inscription</td>
<td><code class="language-plaintext highlighter-rouge">E34_Inscription</code> </td>
</tr>
<tr class="even">
<td>E35</td>
<td>Title</td>
<td>Titre</td>
<td><code class="language-plaintext highlighter-rouge">E35_Titre</code> </td>
</tr>
<tr class="odd">
<td>E36</td>
<td>Visual Item</td>
<td>Entité visuelle</td>
<td><code class="language-plaintext highlighter-rouge">E36_Entité_visuelle</code> </td>
</tr>
<tr class="even">
<td>E37</td>
<td>Mark</td>
<td>Marque</td>
<td><code class="language-plaintext highlighter-rouge">E37_Marque</code> </td>
</tr>
<tr class="odd">
<td>E39</td>
<td>Actor</td>
<td>Acteur</td>
<td><p><code class="language-plaintext highlighter-rouge">E39_Actant</code> </p>
<p>L'introduction de CIDOC CRM fait usage du terme Agent pour référer à des entités actantes qui ne sont pas définies comme des personnes ou des groupes. Il semble donc préférable de s'en tenir à Acteur ici afin d'utiliser Agent autre part.</p></td>
</tr>
<tr class="even">
<td>E41</td>
<td>Appellation</td>
<td>Appellation</td>
<td><code class="language-plaintext highlighter-rouge">E41_Appellation</code> </td>
</tr>
<tr class="odd">
<td>E42</td>
<td>Identifier</td>
<td>Identifiant</td>
<td><code class="language-plaintext highlighter-rouge">E42_Identifiant</code> </td>
</tr>
<tr class="even">
<td>E52</td>
<td>Time-Span</td>
<td>Intervalle temporel</td>
<td><p><code class="language-plaintext highlighter-rouge">E52_Intervalle_temporel</code> </p>
<p>Laps de temps est une redite puisqu'un laps est l'écoulement du temps durant un intervalle. Il semble préférable d'adopter une graphie plus proche de la forme originale. Ceci est en outre cohérent avec les autres appellations temporelles.</p></td>
</tr>
<tr class="odd">
<td>E53</td>
<td>Place</td>
<td>Lieu</td>
<td><code class="language-plaintext highlighter-rouge">E53_Lieu</code> </td>
</tr>
<tr class="even">
<td>E54</td>
<td>Dimension</td>
<td>Dimension</td>
<td><code class="language-plaintext highlighter-rouge">E54_Dimension</code> </td>
</tr>
<tr class="odd">
<td>E55</td>
<td>Type</td>
<td>Type</td>
<td><code class="language-plaintext highlighter-rouge">E55_Type</code> </td>
</tr>
<tr class="even">
<td>E56</td>
<td>Language</td>
<td>Langue</td>
<td><code class="language-plaintext highlighter-rouge">E56_Langue</code> </td>
</tr>
<tr class="odd">
<td>E57</td>
<td>Material</td>
<td>Matériau</td>
<td><code class="language-plaintext highlighter-rouge">E57_Matériau</code> </td>
</tr>
<tr class="even">
<td>E58</td>
<td>Measurement Unit</td>
<td>Unité de mesure</td>
<td><code class="language-plaintext highlighter-rouge">E58_Unité_de_mesure</code> </td>
</tr>
<tr class="odd">
<td>E59</td>
<td>Primitive Value</td>
<td>Valeur primitive</td>
<td><code class="language-plaintext highlighter-rouge">E59_Valeur_primitive</code> </td>
</tr>
<tr class="even">
<td>E60</td>
<td>Number</td>
<td>Nombre</td>
<td><code class="language-plaintext highlighter-rouge">E60_Nombre</code> </td>
</tr>
<tr class="odd">
<td>E61</td>
<td>Time Primitive</td>
<td>Primitive temporelle</td>
<td><code class="language-plaintext highlighter-rouge">E61_Primitive_temporelle</code> </td>
</tr>
<tr class="even">
<td>E62</td>
<td>String</td>
<td>Chaîne de caractères</td>
<td><code class="language-plaintext highlighter-rouge">E62_Chaîne_de_caractères</code> </td>
</tr>
<tr class="odd">
<td>E63</td>
<td>Beginning of Existence</td>
<td>Début d'existence</td>
<td><code class="language-plaintext highlighter-rouge">E63_Début_d’existence</code> </td>
</tr>
<tr class="even">
<td>E64</td>
<td>End of Existence</td>
<td>Fin d'existence</td>
<td><code class="language-plaintext highlighter-rouge">E64_Fin_d’existence</code> </td>
</tr>
<tr class="odd">
<td>E65</td>
<td>Creation</td>
<td>Création</td>
<td><code class="language-plaintext highlighter-rouge">E65_Création</code> </td>
</tr>
<tr class="even">
<td>E66</td>
<td>Formation</td>
<td>Formation</td>
<td><code class="language-plaintext highlighter-rouge">E66_Formation</code> </td>
</tr>
<tr class="odd">
<td>E67</td>
<td>Birth</td>
<td>Naissance</td>
<td><code class="language-plaintext highlighter-rouge">E67_Naissance</code> </td>
</tr>
<tr class="even">
<td>E68</td>
<td>Dissolution</td>
<td>Dissolution</td>
<td><code class="language-plaintext highlighter-rouge">E68_Dissolution</code> </td>
</tr>
<tr class="odd">
<td>E69</td>
<td>Death</td>
<td>Mort</td>
<td><code class="language-plaintext highlighter-rouge">E69_Mort</code> </td>
</tr>
<tr class="even">
<td>E70</td>
<td>Thing</td>
<td>Chose</td>
<td><code class="language-plaintext highlighter-rouge">E70_Chose</code> </td>
</tr>
<tr class="odd">
<td>E71</td>
<td>Human-Made Thing</td>
<td>Chose élaborée par l’humain</td>
<td><p><code class="language-plaintext highlighter-rouge">E71_Chose_élaborée_par_l’humain</code> </p>
<p>L'utilisation du terme façonnée est cohérente avec les autres appellations comparables.</p></td>
</tr>
<tr class="even">
<td>E72</td>
<td>Legal Object</td>
<td>Objet juridique</td>
<td><p><code class="language-plaintext highlighter-rouge">E72_Objet_juridique</code> </p>
<p>La définition se rapporte au droit (juridique) plutôt qu'à ce qui s'y conforme (légal).</p></td>
</tr>
<tr class="odd">
<td>E73</td>
<td>Information Object</td>
<td>Objet informationnel</td>
<td><code class="language-plaintext highlighter-rouge">E73_Objet_informationnel</code> </td>
</tr>
<tr class="even">
<td>E74</td>
<td>Group</td>
<td>Groupe</td>
<td><code class="language-plaintext highlighter-rouge">E74_Groupe</code> </td>
</tr>
<tr class="odd">
<td>E77</td>
<td>Persistent Item</td>
<td>Entité persistante</td>
<td><code class="language-plaintext highlighter-rouge">E77_Entité_persistante</code> </td>
</tr>
<tr class="even">
<td>E78</td>
<td>Curated Holding</td>
<td>Collection</td>
<td><code class="language-plaintext highlighter-rouge">E78_Collection</code> </td>
</tr>
<tr class="odd">
<td>E79</td>
<td>Part Addition</td>
<td>Ajout d'élément</td>
<td><p><code class="language-plaintext highlighter-rouge">E79_Ajout_d’élément</code> </p>
<p>La définition de la classe précise qu'il s'agit bien d'ajouter une partie physique à un objet, ce qui semble plus près de la définition d'ajout.</p></td>
</tr>
<tr class="even">
<td>E80</td>
<td>Part Removal</td>
<td>Retrait d’élément</td>
<td><p><code class="language-plaintext highlighter-rouge">E80_Retrait_d’élément</code> </p>
<p>La définition de la classe précise qu'il s'agit bien de retirer une partie physique à un objet, ce qui semble plus près de la définition de retrait.</p></td>
</tr>
<tr class="odd">
<td>E81</td>
<td>Transformation</td>
<td>Transformation</td>
<td><code class="language-plaintext highlighter-rouge">E81_Transformation</code> </td>
</tr>
<tr class="even">
<td>E83</td>
<td>Type Creation</td>
<td>Création de type</td>
<td><code class="language-plaintext highlighter-rouge">E83_Création_de_type</code> </td>
</tr>
<tr class="odd">
<td>E85</td>
<td>Joining</td>
<td>Adhésion</td>
<td><p><code class="language-plaintext highlighter-rouge">E85_Adhésion</code> </p>
<p>Puisque la classe réfère à des personnes dotées d'intentionnalité, il semble plus juste d'utiliser le terme adhésion puisque l'intégration peut faire référence à des objets intégrés à des ensembles.</p></td>
</tr>
<tr class="even">
<td>E86</td>
<td>Leaving</td>
<td>Départ</td>
<td><code class="language-plaintext highlighter-rouge">E86_Départ</code> </td>
</tr>
<tr class="odd">
<td>E87</td>
<td>Curation Activity</td>
<td>Activité curatoriale</td>
<td><p><code class="language-plaintext highlighter-rouge">E87_Activité_curatoriale</code> </p>
<p>Puisqu'il s'agit des activités ayant trait à la collection et non pas seulement à sa conservation (<em>preservation</em>), il semble préférable ici d'utiliser l'adjectif « curatoriale » qui est fréquemment utilisé dans le milieu muséal au sens anglophone du terme « curatorial ». </p></td>
</tr>
<tr class="even">
<td>E89</td>
<td>Propositional Object</td>
<td>Objet propositionnel</td>
<td><code class="language-plaintext highlighter-rouge">E89_Objet_propositionnel</code> </td>
</tr>
<tr class="odd">
<td>E90</td>
<td>Symbolic Object</td>
<td>Objet symbolique</td>
<td><code class="language-plaintext highlighter-rouge">E90_Objet_symbolique</code> </td>
</tr>
<tr class="even">
<td>E92</td>
<td>Spacetime Volume</td>
<td>Volume spatio-temporel</td>
<td><p><code class="language-plaintext highlighter-rouge">E92_Volume_spatio</code>-temporel </p>
<p>L'utilisation de "spatio-temporel" est cohérente avec les autres choix faits dans la traduction (Intervalle Temporel, etc.).</p></td>
</tr>
<tr class="odd">
<td>E93</td>
<td>Presence</td>
<td>Présence</td>
<td><code class="language-plaintext highlighter-rouge">E93_Présence</code> </td>
</tr>
<tr class="even">
<td>E94</td>
<td>Space Primitive</td>
<td>Primitive spatiale</td>
<td><p><code class="language-plaintext highlighter-rouge">E94_Primitive_spatiale</code> </p>
<p>Cette formulation est cohérente avec les autres choix de la traduction (Primitive Temporelle, Primitive Spatio-Temporelle, Volume Spatio-Temporel).</p></td>
</tr>
<tr class="odd">
<td>E95</td>
<td>Spacetime Primitive</td>
<td>Primitive spatio-temporelle</td>
<td><p><code class="language-plaintext highlighter-rouge">E95_Primitive_spatio</code>-temporelle </p>
<p>Cette formulation est cohérente avec les autres choix de la traduction (Primitive Temporelle, Primitive Spatiale, Volume Spatio-Temporel).</p></td>
</tr>
<tr class="even">
<td>E96</td>
<td>Purchase</td>
<td>Achat</td>
<td><code class="language-plaintext highlighter-rouge">E96_Achat</code> </td>
</tr>
<tr class="odd">
<td>E97</td>
<td>Monetary Amount</td>
<td>Valeur monétaire</td>
<td><p><code class="language-plaintext highlighter-rouge">E97_Valeur_monétaire</code> </p>
<p>En français, le caractère économique et mesurable d'un bien est reflété dans l'utilisation du terme valeur associé à la monnaie de sorte qu'il n'y a pas d'ambiguïté quant à l'aspect quantitatif et que l'expression d'usage semble plus proche de la définition originale qu'une traduction littérale.</p></td>
</tr>
<tr class="even">
<td>E98</td>
<td>Currency</td>
<td>Monnaie</td>
<td><code class="language-plaintext highlighter-rouge">E98_Monnaie</code> </td>
</tr>
<tr class="odd">
<td>E99</td>
<td>Product Type</td>
<td>Modèle de produit</td>
<td><p><code class="language-plaintext highlighter-rouge">E99_Modèle_de_produit</code> </p>
<p>Le terme modèle est celui qui est le plus proche de la définition de cette classe. Cependant, puisque le terme est utilisé dans d'autres contextes au sein de la spécification CIDOC CRM, le nom "Modèle de Produit" semble préférable.</p></td>
</tr>
<tr class="even">
<td>P1</td>
<td>is identified by (identifies)</td>
<td>est identifié par (identifie)</td>
<td><code class="language-plaintext highlighter-rouge">P1_est_identifié_par (identifie)</code> </td>
</tr>
<tr class="odd">
<td>P2</td>
<td>has type (is type of)</td>
<td>a pour type (est type de)</td>
<td><p><code class="language-plaintext highlighter-rouge">P2_a_pour_type (est_type_de)</code> </p>
<p>Puisque la plupart du temps le type est appliqué à l'information pour la classifier et qu'il n'est pas inhérent, il semble préférable d'utiliser une formulation plus proche de l'assignation.</p>
<p>Cette formulation est cohérente avec les autres choix de la traduction (a pour note, a pour durée, etc.)</p></td>
</tr>
<tr class="even">
<td>P3</td>
<td>has note</td>
<td>a pour note</td>
<td><code class="language-plaintext highlighter-rouge">P3_a_pour_note</code> </td>
</tr>
<tr class="odd">
<td>P4</td>
<td>has time-span (is time-span of)</td>
<td>a pour intervalle temporel (est l'intervalle temporel de)</td>
<td><code class="language-plaintext highlighter-rouge">P4_a_pour_intervalle_temporel (est_l'intervalle_temporel_de)</code> </td>
</tr>
<tr class="even">
<td>P5</td>
<td>consists of (forms part of)</td>
<td>consiste en (fait partie de)</td>
<td><p><code class="language-plaintext highlighter-rouge">P5_consiste_en (fait_partie_de)</code> </p>
<p>Cette formulation est cohérente avec le reste de la traduction (P45 "consists of (forms part of); consiste en (inclut)").</p>
<p>Cette formulation est cohérente avec le reste de la traduction (P5 "consists of (forms part of); consiste en (fait partie de)").</p></td>
</tr>
<tr class="odd">
<td>P7</td>
<td>took place at (witnessed)</td>
<td>a eu lieu dans (a été témoin de)</td>
<td><code class="language-plaintext highlighter-rouge">P7_a_eu_lieu_dans (a_été_témoin_de)</code> </td>
</tr>
<tr class="even">
<td>P8</td>
<td>took place on or within (witnessed)</td>
<td>a eu lieu à (a été témoin de)</td>
<td><code class="language-plaintext highlighter-rouge">P8_a_eu_lieu (a_été_témoin_de)</code> </td>
</tr>
<tr class="odd">
<td>P9</td>
<td>consists of (forms part of)</td>
<td>comprend (fait partie de)</td>
<td><p><code class="language-plaintext highlighter-rouge">P9_comprend (fait_partie_de)</code> </p>
<p>Consister implique généralement que toutes les parties qui forment un tout sont énumérées, ce qui n'est pas le cas selon la définition actuelle de sorte que comprendre semble préférable.</p></td>
</tr>
<tr class="even">
<td>P10</td>
<td>falls within (contains)</td>
<td>s’insère dans le cours de (contient)</td>
<td><code class="language-plaintext highlighter-rouge">P10_s’insère_dans_le_cours_de (contient)</code> </td>
</tr>
<tr class="odd">
<td>P11</td>
<td>had participant (participated in)</td>
<td>a eu pour actant participant (a participé à)</td>
<td><p><code class="language-plaintext highlighter-rouge">P11_a_eu_pour_actant_participant (a_participé_à)</code> </p>
<p>Puisque l'action est précise et achevée ("<em>instances of E53 Place and E52 Time-Span where and when these events happened provide us with constraints about the presence of the related instances of E39 Actor in the past</em>") plutôt que d'être en cours, l'utilisation du passé composé semble préférable à l'imparfait.</p></td>
</tr>
<tr class="even">
<td>P12</td>
<td>occurred in the presence of (was present at)</td>
<td>a eu lieu en présence de (a été présent à)</td>
<td><p><code class="language-plaintext highlighter-rouge">P12_a_eu_lieu_en_présence_de (a_été_présent_à)</code> </p>
<p>La locution "a eu lieu" est cohérente avec le reste de la traduction (a eu lieu dans, a eu lieu à).</p>
<p>Puisque l'action est précise et achevée ("instance of E53 Place and the instance of E52 Time-Span where and when these events happened provide us with constraints about the presence of the related instance E77 Persistent Item in the past") plutôt que d'être en cours, l'utilisation du passé composé semble préférable à l'imparfait.</p></td>
</tr>
<tr class="odd">
<td>P13</td>
<td>destroyed (was destroyed by)</td>
<td>a détruit (a été détruit par)</td>
<td><code class="language-plaintext highlighter-rouge">P13_a_détruit (a_été_détruit_par)</code> </td>
</tr>
<tr class="even">
<td>P14</td>
<td>carried out by (performed)</td>
<td>a été effectué par (a effectué)</td>
<td><p><code class="language-plaintext highlighter-rouge">P14_a_été_effectué_par (a_effectué)</code> </p>
<p>À des fins de cohérence, il semble préférable d'utiliser le verbe effectuer tant pour l'un que pour l'autre. Qui plus est, c'est un terme plus proche de la définition qui implique une causalité (légale ou autre).</p></td>
</tr>
<tr class="odd">
<td>P15</td>
<td>was influenced by (influenced)</td>
<td>a été influencé par (a influencé)</td>
<td><code class="language-plaintext highlighter-rouge">P15_a_été_influencé_par (a_influencé)</code> </td>
</tr>
<tr class="even">
<td>P16</td>
<td>used specific object (was used for)</td>
<td>a mobilisé l'objet spécifique (a été mobilisé pour)</td>
<td><code class="language-plaintext highlighter-rouge">P16_a_mobilisé_l’objet_spécifique (a_été_mobilisé_pour)</code> </td>
</tr>
<tr class="odd">
<td>P17</td>
<td>was motivated by (motivated)</td>
<td>a été motivé par (a motivé)</td>
<td><code class="language-plaintext highlighter-rouge">P17_a_été_motivé_par (a_motivé)</code> </td>
</tr>
<tr class="even">
<td>P19</td>
<td>was intended use of (was made for):</td>
<td>a été l'usage prévu de (a été élaboré pour)</td>
<td><p><code class="language-plaintext highlighter-rouge">P19_a_été_l’usage_prévu_de (a_été_élaboré_pour)</code> </p>
<p>Cette formulation est cohérente avec le reste de la traduction (P19, P68).</p></td>
</tr>
<tr class="odd">
<td>P20</td>
<td>had specific purpose (was purpose of)</td>
<td>a eu pour finalité spécifique (a été finalité de)</td>
<td><p><code class="language-plaintext highlighter-rouge">P20_a_eu_pour_finalité_spécifique (a_été_finalité_de)</code> </p>
<p>Le but implique une intention que des activités n'ont pas (puisque c'est l'acteur qui est doté d'intention).</p></td>
</tr>
<tr class="even">
<td>P21</td>
<td>had general purpose (was purpose of)</td>
<td>a eu pour finalité générale (a été finalité de)</td>
<td><code class="language-plaintext highlighter-rouge">P21_a_eu_pour_finalité_générale (a_été_finalité_de)</code> </td>
</tr>
<tr class="odd">
<td>P22</td>
<td>transferred title to (acquired title through)</td>
<td>a transféré le titre de propriété à (a acquis le titre de propriété par)</td>
<td><p><code class="language-plaintext highlighter-rouge">P22_a_transféré_le_titre_de_propriété_à (a_acquis_le_titre_de_propriété_par)</code> </p>
<p>Le transfert, l'acquisition et la cession sont des termes plus proches de la réalité juridique et semblent donc plus appropriés.</p></td>
</tr>
<tr class="even">
<td>P23</td>
<td>transferred title from (surrendered title through)</td>
<td>a transféré le titre de propriété de (a cédé le titre de propriété à)</td>
<td><p><code class="language-plaintext highlighter-rouge">P23_a_transféré_le_titre_de_propriété_de (a_cédé_le_titre_de_propriété_à)</code> </p>
<p>Le transfert, l'acquisition et la cession sont des termes plus proches de la réalité juridique et semblent donc plus appropriés.</p></td>
</tr>
<tr class="odd">
<td>P24</td>
<td>transferred title of (changed ownership through)</td>
<td>a transféré le titre de propriété du (a changé de propriétaire par)</td>
<td><p><code class="language-plaintext highlighter-rouge">P24_a_transféré_le_titre_de_propriété_du (a_changé_de_propriétaire_par)</code> </p>
<p>Le transfert, l'acquisition et la cession sont des termes plus proches de la réalité juridique et semblent donc plus appropriés.</p></td>
</tr>
<tr class="even">
<td>P25</td>
<td>moved (moved by)</td>
<td>a déplacé (a été déplacé par)</td>
<td><code class="language-plaintext highlighter-rouge">P25_a_déplacé (a_été_déplacé_par)</code> </td>
</tr>
<tr class="odd">
<td>P26</td>
<td>moved to (was destination of)</td>
<td>a déplacé à (a été la destination de)</td>
<td><code class="language-plaintext highlighter-rouge">P26_a_déplacé_à (a_été_la_destination_de)</code> </td>
</tr>
<tr class="even">
<td>P27</td>
<td>moved from (was origin of)</td>
<td>a déplacé depuis (a été le point de départ de)</td>
<td><code class="language-plaintext highlighter-rouge">P27_a_déplacé_depuis (a_été_le_point_de_départ_de)</code> </td>
</tr>
<tr class="odd">
<td>P28</td>
<td>custody surrendered by (surrendered custody through)</td>
<td>a mis fin à la garde par (a cédé la garde par)</td>
<td><p><code class="language-plaintext highlighter-rouge">P28_a_mis_fin_à_la_garde_par (a_cédé_la_garde_par)</code> </p>
<p>L'utilisation du terme par est cohérent avec les autres propositions et plus simple.</p></td>
</tr>
<tr class="even">
<td>P29</td>
<td>custody received by (received custody through)</td>
<td>a confié la garde par (a reçu la garde par)</td>
<td><p><code class="language-plaintext highlighter-rouge">P29_a_confié_la_garde_par (a_reçu_la_garde_par)</code> </p>
<p>L'utilisation du terme par est cohérent avec les autres propositions et plus simple.</p></td>
</tr>
<tr class="odd">
<td>P30</td>
<td>transferred custody of (custody transferred through)</td>
<td>a transféré la garde de (a été l’objet d’un transfert de garde par)</td>
<td><p><code class="language-plaintext highlighter-rouge">P30_a_transféré_la_garde_de (a_été_l’objet_d’un_transfert_de_garde_par)</code> </p>
<p>L'utilisation du terme par est cohérent avec les autres propositions et plus simple.</p></td>
</tr>
<tr class="even">
<td>P31</td>
<td>has modified (was modified by)</td>
<td>a modifié (a été modifié par)</td>
<td><code class="language-plaintext highlighter-rouge">P31_a_modifié (a_été_modifié_par)</code> </td>
</tr>
<tr class="odd">
<td>P32</td>
<td>used general technique (was technique of)</td>
<td>a mobilisé comme technique générale (a été une technique générale mise en œuvre dans)</td>
<td><p><code class="language-plaintext highlighter-rouge">P32_a_mobilisé_comme_technique_générale (a_été_une_technique_générale_mise_en_œuvre_dans)</code> </p>
<p>Une technique spécifique plutôt que la puisqu'il est possible que ce ne soit pas la seule.</p>
<p>Générique est un anglicisme de sorte que nous avons préféré générale.</p></td>
</tr>
<tr class="even">
<td>P33</td>
<td>used specific technique (was used by)</td>
<td>a mobilisé comme technique spécifique (a été une technique spécifique mise en œuvre dans)</td>
<td><p><code class="language-plaintext highlighter-rouge">P33_a_mobilisé_comme_technique_spécifique (a_été_une_technique_spécifique_mise_en_œuvre_dans)</code> </p>
<p>Une technique spécifique plutôt que la puisqu'il est possible que ce ne soit pas la seule.</p></td>
</tr>
<tr class="odd">
<td>P34</td>
<td>concerned (was assessed by)</td>
<td>a porté sur (a été évalué lors de)</td>
<td><p><code class="language-plaintext highlighter-rouge">P34_a_porté_sur (a_été_évalué_lors_de)</code> </p>
<p>Puisqu'il s'agit de l'évènement et non de la personne, lors de semble plus approprié et cohérent avec le reste de la traduction.</p></td>
</tr>
<tr class="even">
<td>P35</td>
<td>has identified (was identified by)</td>
<td>a identifié (a été identifié lors de)</td>
<td><p><code class="language-plaintext highlighter-rouge">P35_a_identifié (a_été_identifié_lors_de)</code> </p>
<p>Puisqu'il s'agit de l'évènement et non de la personne, lors de semble plus approprié et cohérent avec le reste de la traduction.</p></td>
</tr>
<tr class="odd">
<td>P37</td>
<td>assigned (was assigned by)</td>
<td>a attribué (a été attribué lors de)</td>
<td><p><code class="language-plaintext highlighter-rouge">P37_a_attribué (a_été_attribué_lors_de)</code> </p>
<p>Puisqu'il s'agit de l'évènement et non de la personne, lors de semble plus approprié et cohérent avec le reste de la traduction.</p></td>
</tr>
<tr class="even">
<td>P38</td>
<td>deassigned (was deassigned by)</td>
<td>a retiré l’attribution de (a été retiré lors de)</td>
<td><p><code class="language-plaintext highlighter-rouge">P38_a_retiré_l’attribution_de (a_été_retiré_lors_de)</code> </p>
<p>Puisqu'il s'agit de l'évènement et non de la personne, lors de semble plus approprié et cohérent avec le reste de la traduction.</p></td>
</tr>
<tr class="odd">
<td>P39</td>
<td>measured (was measured by)</td>
<td>a mesuré (a été mesuré lors de)</td>
<td><p><code class="language-plaintext highlighter-rouge">P39_a_mesuré (a_été_mesuré_lors_de)</code> </p>
<p>Puisqu'il s'agit de l'évènement et non de la personne, lors de semble plus approprié et cohérent avec le reste de la traduction.</p></td>
</tr>
<tr class="even">
<td>P40</td>
<td>observed dimension (was observed in)</td>
<td>a relevé comme dimension (a été relevé lors de)</td>
<td><p><code class="language-plaintext highlighter-rouge">P40_a_relevé_comme_dimension (a_été_relevé_lors_de)</code> </p>
<p>Puisqu'il s'agit de l'évènement et non de la personne, lors de semble plus approprié et cohérent avec le reste de la traduction.</p></td>
</tr>
<tr class="odd">
<td>P41</td>
<td>classified (was classified by)</td>
<td>a classifié (a été classifié lors de)</td>
<td><p><code class="language-plaintext highlighter-rouge">P41_a_classifié (a_été_classifié_lors_de)</code> </p>
<p>Puisqu'il s'agit de l'évènement et non de la personne, lors de semble plus approprié et cohérent avec le reste de la traduction.</p></td>
</tr>
<tr class="even">
<td>P42</td>
<td>assigned (was assigned by)</td>
<td>a attribué (a été attribué lors de)</td>
<td><p><code class="language-plaintext highlighter-rouge">P42_a_attribué (a_été_attribué_lors_de)</code> </p>
<p>Puisqu'il s'agit de l'évènement et non de la personne, lors de semble plus approprié et cohérent avec le reste de la traduction.</p></td>
</tr>
<tr class="odd">
<td>P43</td>
<td>has dimension (is dimension of)</td>
<td>a pour dimension (est dimension de)</td>
<td><code class="language-plaintext highlighter-rouge">P43_a_pour_dimension (est_dimension_de)</code> </td>
</tr>
<tr class="even">
<td>P44</td>
<td>has condition (is condition of)</td>
<td>a pour état matériel (est état matériel de)</td>
<td><code class="language-plaintext highlighter-rouge">P44_a_pour_état_matériel (est_état_matériel_de)</code> </td>
</tr>
<tr class="odd">
<td>P45</td>
<td>consists of (is incorporated in)</td>
<td>consiste en (inclut)</td>
<td><p><code class="language-plaintext highlighter-rouge">P45_consiste_en (inclut)</code> </p>
<p>Cette formulation est cohérente avec le reste de la traduction (P5 "consists of (forms part of); consiste en (fait partie de)").</p>
<p>Cette formulation est cohérente avec le reste de la traduction (P46 "is composed of (forms part of); est composé de (fait partie de)").</p></td>
</tr>
<tr class="even">
<td>P46</td>
<td>is composed of (forms part of)</td>
<td>est composé de (fait partie de)</td>
<td><p><code class="language-plaintext highlighter-rouge">P46_est_composé_de (fait_partie_de)</code> </p>
<p>Cette formulation est cohérente avec le reste de la traduction (P5 "consists of (forms part of); consiste en (fait partie de)").</p>
<p>Cette formulation est cohérente avec le reste de la traduction (P45 "is consists of (forms part of); consiste en (inclut)").</p></td>
</tr>
<tr class="odd">
<td>P48</td>
<td>has preferred identifier (is preferred identifier of)</td>
<td>a pour identifiant préférentiel (est identifiant préférentiel de)</td>
<td><code class="language-plaintext highlighter-rouge">P48_a_pour_identifiant_préférentiel (est_identifiant_préférentiel_de)</code> </td>
</tr>
<tr class="even">
<td>P49</td>
<td>has former or current keeper (is former or current keeper of)</td>
<td>a pour actant détenteur actuel ou antérieur (est actant détenteur actuel ou antérieur de)</td>
<td><p><code class="language-plaintext highlighter-rouge">P49_a_pour_actant_détenteur_actuel_ou_antérieur (est_actant_détenteur_actuel_ou_antérieur_de)</code> </p>
<p>L'utilisation du terme détenteur semble préférable dans la mesure où il reconnaît à la fois la responsabilité légale ainsi que la détention de l'objet, ce à quoi le terme "keeper" fait allusion (en plus de la définition qui parle de "custody" et non pas de "responsibility"</p></td>
</tr>
<tr class="odd">
<td>P50</td>
<td>has current keeper (is current keeper of)</td>
<td>a pour actant détenteur actuel (est actant détenteur actuel de)</td>
<td><p><code class="language-plaintext highlighter-rouge">P50_a_pour_actant_détenteur_actuel (est_actant_détenteur_actuel_de)</code> </p>
<p>L'utilisation du terme détenteur semble préférable dans la mesure où il reconnaît à la fois la responsabilité légale ainsi que la détention de l'objet, ce à quoi le terme "keeper" fait allusion (en plus de la définition qui parle de "custody" et non pas de "responsibility"</p></td>
</tr>
<tr class="even">
<td>P51</td>
<td>has former or current owner (is former or current owner of)</td>
<td>a pour propriétaire actuel ou antérieur (est propriétaire actuel ou antérieur de)</td>
<td><code class="language-plaintext highlighter-rouge">P51_a_pour_propriétaire_actuel_ou_antérieur (est_propriétaire_actuel_ou_antérieur_de)</code> </td>
</tr>
<tr class="odd">
<td>P52</td>
<td>has current owner (is current owner of)</td>
<td>a pour propriétaire actuel (est propriétaire actuel de)</td>
<td><code class="language-plaintext highlighter-rouge">P52_a_pour_propriétaire_actuel (est_propriétaire_actuel_de)</code> </td>
</tr>
<tr class="even">
<td>P53</td>
<td>has former or current location (is former or current location of)</td>
<td>a pour localisation actuelle ou antérieure (est localisation actuelle ou antérieure de)</td>
<td><code class="language-plaintext highlighter-rouge">P53_a_pour_localisation_actuelle_ou_antérieure (est_localisation_actuelle_ou_antérieure_de)</code> </td>
</tr>
<tr class="odd">
<td>P54</td>
<td>has current permanent location (is current permanent location of)</td>
<td>a actuellement pour localisation fixe (est actuellement localisation fixe de)</td>
<td><p><code class="language-plaintext highlighter-rouge">P54_a_actuellement_pour_localisation_fixe (est_actuellement_localisation_fixe_de)</code> </p>
<p>Lorsqu'il s'agit d'une adresse/d'un emplacement, l'usage de "fixe" plutôt que "permanent" est recommandé car il fait référence à l'état durable de l'emplacement plutôt qu'à son caractère durable.</p></td>
</tr>
<tr class="even">
<td>P55</td>
<td>has current location (currently holds)</td>
<td>a actuellement pour localisation (est actuellement localisation de)</td>
<td><code class="language-plaintext highlighter-rouge">P55_a_actuellement_pour_localisation (est_actuellement_localisation_de)</code> </td>
</tr>
<tr class="odd">
<td>P56</td>
<td>bears feature (is found on)</td>
<td>a pour caractéristique (se trouve sur)</td>
<td><p><code class="language-plaintext highlighter-rouge">P56_a_pour_caractéristique (se_trouve_sur)</code> </p>
<p>L'utilisation d'une formulation cohérente entre P56, P57, P59, etc. semble appropriée.</p></td>
</tr>
<tr class="even">
<td>P57</td>
<td>has number of parts</td>
<td>a pour nombre d'éléments</td>
<td><p><code class="language-plaintext highlighter-rouge">P57_a_pour_nombre_d’éléments</code> </p>
<p>L'utilisation d'une formulation cohérente entre P56, P57, P59, etc. semble appropriée. Puisque la propriété fait référence à des parties distinctes, il apparaît justifié de parler d'éléments.</p></td>
</tr>
<tr class="odd">
<td>P59</td>
<td>has section (is located on or within)</td>
<td>a pour section (se situe sur ou dans)</td>
<td><p><code class="language-plaintext highlighter-rouge">P59_a_pour_section (se_situe_sur_ou_dans)</code> </p>
<p>L'utilisation d'une formulation cohérente entre P56, P57, P59, etc. semble appropriée.</p></td>
</tr>
<tr class="even">
<td>P62</td>
<td>depicts (is depicted by)</td>
<td>illustre (est illustré par)</td>
<td><p><code class="language-plaintext highlighter-rouge">P62_illustre (est_illustré_par)</code> </p>
<p>Le terme figurer dans le sens de l'illustration est limité aux œuvres d'art alors que la définition est plus large.</p></td>
</tr>
<tr class="odd">
<td>P65</td>
<td>shows visual item (is shown by)</td>
<td>représente l'entité visuelle (est représenté par)</td>
<td><p><code class="language-plaintext highlighter-rouge">P65_représente_l’entité_visuelle (est_représenté_par)</code> </p>
<p>Cette traduction est cohérente avec celle de E36 Entité Visuelle.</p>
<p>Le terme représenté est préférable au terme présenter dans la mesure où aucune des deux entités actantes n'a d'intentionnalité.</p></td>
</tr>
<tr class="even">
<td>P67</td>
<td>refers to (is referred to by)</td>
<td>renvoie à (fait l'objet d'un renvoi par)</td>
<td><code class="language-plaintext highlighter-rouge">P67_renvoie_à (fait_l'objet_d'un_renvoi_par)</code> </td>
</tr>
<tr class="odd">
<td>P68</td>
<td>foresees use of (use foreseen by)</td>
<td>prévoit l'usage de (usage prévu de)</td>
<td><p><code class="language-plaintext highlighter-rouge">P68_prévoit_l’usage_de (usage_prévu_de)</code> </p>
<p>Cette formulation est cohérente avec le reste de la traduction (P19, P68).</p></td>
</tr>
<tr class="even">
<td>P69</td>
<td>has association with (is associated with)</td>
<td>est associé à</td>
<td><code class="language-plaintext highlighter-rouge">P69_est_associé_à</code> </td>
</tr>
<tr class="odd">
<td>P70</td>
<td>documents (is documented in)</td>
<td>documente (est documenté dans)</td>
<td><code class="language-plaintext highlighter-rouge">P70_documente (est_documenté_dans)</code> </td>
</tr>
<tr class="even">
<td>P71</td>
<td>lists (is listed in)</td>
<td>énumère (est énuméré par)</td>
<td><code class="language-plaintext highlighter-rouge">P71_énumère (est_énuméré_par)</code> </td>
</tr>
<tr class="odd">
<td>P72</td>
<td>has language (is language of)</td>
<td>a pour langue (est la langue de)</td>
<td><code class="language-plaintext highlighter-rouge">P72_a_pour_langue (est_la_langue_de)</code> </td>
</tr>
<tr class="even">
<td>P73</td>
<td>has translation (is translation of)</td>
<td>a pour traduction (est traduction de)</td>
<td><code class="language-plaintext highlighter-rouge">P73_a_pour_traduction (est_traduction_de)</code> </td>
</tr>
<tr class="odd">
<td>P74</td>
<td>has current or former residence (is current or former residence of)</td>
<td>a pour résidence actuelle ou antérieure (est résidence actuelle ou antérieure de)</td>
<td><code class="language-plaintext highlighter-rouge">P74_a_pour_résidence_actuelle_ou_antérieure (est_résidence_actuelle_ou_antérieure_de)</code> </td>
</tr>
<tr class="even">
<td>P75</td>
<td>possesses (is possessed by)</td>
<td>possède (est possédé par)</td>
<td><code class="language-plaintext highlighter-rouge">P75_possède (est_possédé_par)</code> </td>
</tr>
<tr class="odd">
<td>P76</td>
<td>has contact point (provides access to)</td>
<td>a pour coordonnées (permet de contacter)</td>
<td><code class="language-plaintext highlighter-rouge">P76_a_pour_coordonnées (permet_de_contacter)</code> </td>
</tr>
<tr class="even">
<td>P79</td>
<td>beginning is qualified by</td>
<td>a son début qualifié par</td>
<td><code class="language-plaintext highlighter-rouge">P79_a_son_début_qualifié_par</code> </td>
</tr>
<tr class="odd">
<td>P80</td>
<td>end is qualified by</td>
<td>a sa fin qualifiée par</td>
<td><code class="language-plaintext highlighter-rouge">P80_a_sa_fin_qualifiée_par</code> </td>
</tr>
<tr class="even">
<td>P81</td>
<td>ongoing throughout</td>
<td>a couvert</td>
<td><code class="language-plaintext highlighter-rouge">P81_a_couvert</code> </td>
</tr>
<tr class="odd">
<td>P82</td>
<td>at some time within</td>
<td>a eu lieu durant</td>
<td><code class="language-plaintext highlighter-rouge">P82_a_eu_lieu_durant</code> </td>
</tr>
<tr class="even">
<td>P86</td>
<td>falls within (contains)</td>
<td>s’insère dans (inclut)</td>
<td><code class="language-plaintext highlighter-rouge">P86_s’insère_dans (inclut)</code> </td>
</tr>
<tr class="odd">
<td>P89</td>
<td>falls within (contains)</td>
<td>s’insère dans (inclut)</td>
<td><code class="language-plaintext highlighter-rouge">P89_s’insère_dans (inclut)</code> </td>
</tr>
<tr class="even">
<td>P90</td>
<td>has value</td>
<td>a pour valeur</td>
<td><code class="language-plaintext highlighter-rouge">P90_a_pour_valeur</code> </td>
</tr>
<tr class="odd">
<td>P91</td>
<td>has unit (is unit of)</td>
<td>a pour unité de mesure (est l’unité de mesure de)</td>
<td><p><code class="language-plaintext highlighter-rouge">P91_a_pour_unité_de_mesure (est_l’unité_de_mesure_de)</code> </p>
<p>L'utilisation du terme unité sans qualificatif peut faire allusion à un élément unitaire d'un tout (p. ex. une dimension de 30 cm a trois unités de 10 cm).</p></td>
</tr>
<tr class="even">
<td>P92</td>
<td>brought into existence (was brought into existence by)</td>
<td>a fait exister (a commencé à exister par)</td>
<td><code class="language-plaintext highlighter-rouge">P92_a_fait_exister (a_commencé_à_exister_par)</code> </td>
</tr>
<tr class="odd">
<td>P93</td>
<td>took out of existence (was taken out of existence by)</td>
<td>a mis fin à l'existence de (a cessé d'exister par)</td>
<td><code class="language-plaintext highlighter-rouge">P93_a_mis_fin_à_l’existence_de (a_cessé_d'exister_par)</code> </td>
</tr>
<tr class="even">
<td>P94</td>
<td>has created (was created by)</td>
<td>a créé (a été créé par)</td>
<td><code class="language-plaintext highlighter-rouge">P94_a_créé (a_été_créé_par)</code> </td>
</tr>
<tr class="odd">
<td>P95</td>
<td>has formed (was formed by)</td>
<td>a fondé (a été fondé par)</td>
<td><code class="language-plaintext highlighter-rouge">P95_a_fondé (a_été_fondé_par)</code> </td>
</tr>
<tr class="even">
<td>P96</td>
<td>by mother (gave birth)</td>
<td>de mère (a donné naissance à)</td>
<td><code class="language-plaintext highlighter-rouge">P96_de_mère (a_donné_naissance_à)</code> </td>
</tr>
<tr class="odd">
<td>P97</td>
<td>from father (was father for)</td>
<td>de père (a été père pour)</td>
<td><code class="language-plaintext highlighter-rouge">P97_de_père (a_été_père_pour)</code> </td>
</tr>
<tr class="even">
<td>P98</td>
<td>brought into life (was born)</td>
<td>a donné vie à (est né)</td>
<td><code class="language-plaintext highlighter-rouge">P98_a_donné_vie_à (est_né)</code> </td>
</tr>
<tr class="odd">
<td>P99</td>
<td>dissolved (was dissolved by)</td>
<td>a dissout (a été dissout par)</td>
<td><code class="language-plaintext highlighter-rouge">P99_a_dissout (a_été_dissout_par)</code> </td>
</tr>
<tr class="even">
<td>P100</td>
<td>was death of (died in)</td>
<td>a été la mort de (est mort par)</td>
<td><code class="language-plaintext highlighter-rouge">P100_a_été_la_mort_de (est_mort_par)</code> </td>
</tr>
<tr class="odd">
<td>P101</td>
<td>had as general use (was use of)</td>
<td>a eu pour usage général (a été l'usage général de)</td>
<td><p><code class="language-plaintext highlighter-rouge">P101_a_eu_pour_usage_général (a_été_l'usage_général_de)</code> </p>
<p>L'utilisation d'usage est cohérente avec le reste de la traduction.</p></td>
</tr>
<tr class="even">
<td>P102</td>
<td>has title (is title of)</td>
<td>a pour titre (est titre de)</td>
<td><code class="language-plaintext highlighter-rouge">P102_a_pour_titre (est_titre_de)</code> </td>
</tr>
<tr class="odd">
<td>P103</td>
<td>was intended for (was intention of)</td>
<td>a eu pour raison d'être (a été raison d'être de)</td>
<td><code class="language-plaintext highlighter-rouge">P103_a_eu_pour_raison_d’être (a_été_raison_d'être_de)</code> </td>
</tr>
<tr class="even">
<td>P104</td>
<td>is subject to (applies to)</td>
<td>est soumis à (s’applique à)</td>
<td><code class="language-plaintext highlighter-rouge">P104_est_soumis_à (s’applique_à)</code> </td>
</tr>
<tr class="odd">
<td>P105</td>
<td>right held by (has right on)</td>
<td>droit détenu par (détient un droit sur)</td>
<td><code class="language-plaintext highlighter-rouge">P105_droit_détenu_par (détient_un_droit_sur)</code> </td>
</tr>
<tr class="even">
<td>P106</td>
<td>is composed of (forms part of)</td>
<td>est composé de (fait partie de)</td>
<td><code class="language-plaintext highlighter-rouge">P106_est_composé_de (fait_partie_de)</code> </td>
</tr>
<tr class="odd">
<td>P107</td>
<td>has current or former member (is current or former member of)</td>
<td>a pour membre actuel ou antérieur (est membre actuel ou antérieur de)</td>
<td><code class="language-plaintext highlighter-rouge">P107_a_pour_membre_actuel_ou_antérieur (est_membre_actuel_ou_antérieur_de)</code> </td>
</tr>
<tr class="even">
<td>P108</td>
<td>has produced (was produced by)</td>
<td>a produit (a été produit par)</td>
<td><code class="language-plaintext highlighter-rouge">P108_a_produit (a_été_produit_par)</code> </td>
</tr>
<tr class="odd">
<td>P109</td>
<td>has current or former curator (is current or former curator of)</td>
<td>a pour actant en charge de la collection actuellement ou antérieurement (est actuellement ou antérieurement en charge de la collection de)</td>
<td><code class="language-plaintext highlighter-rouge">P109_a_pour_actant_en_charge_de_la_collection_actuellement_ou_antérieurement (est_actuellement_ou_antérieurement_en_charge_de_la_collection_de)</code> </td>
</tr>
<tr class="even">
<td>P110</td>
<td>augmented (was augmented by)</td>
<td>a augmenté (a été augmenté par)</td>
<td><code class="language-plaintext highlighter-rouge">P110_a_augmenté (a_été_augmenté_par)</code> </td>
</tr>
<tr class="odd">
<td>P111</td>
<td>added (was added by)</td>
<td>a ajouté (a été ajouté par)</td>
<td><code class="language-plaintext highlighter-rouge">P111_a_ajouté (a_été_ajouté_par)</code> </td>
</tr>
<tr class="even">
<td>P112</td>
<td>diminished (was diminished by)</td>
<td>a diminué (a été diminué par)</td>
<td><code class="language-plaintext highlighter-rouge">P112_a_diminué (a_été_diminué_par)</code> </td>
</tr>
<tr class="odd">
<td>P113</td>
<td>removed (was removed by)</td>
<td>a retiré (a été retiré par)</td>
<td><p><code class="language-plaintext highlighter-rouge">P113_a_retiré (a_été_retiré_par)</code> </p>
<p>Cette formulation est cohérente avec la traduction de E80 Retrait d'Élément.</p></td>
</tr>
<tr class="even">
<td>P121</td>
<td>overlaps with</td>
<td>se superpose partiellement à</td>
<td><p><code class="language-plaintext highlighter-rouge">P121_se_superpose_partiellement_à</code> </p>
<p>Il semble préférable de ne pas utiliser "recouvrir" qui implique qu'une entité est appliquée sur l'autre qu'elle couvre entièrement.</p></td>
</tr>
<tr class="odd">
<td>P122</td>
<td>borders with</td>
<td>est limitrophe de</td>
<td><code class="language-plaintext highlighter-rouge">P122_est_limitrophe_de</code> </td>
</tr>
<tr class="even">
<td>P123</td>
<td>resulted in (resulted from)</td>
<td>a eu pour résultat (a résulté de)</td>
<td><code class="language-plaintext highlighter-rouge">P123_a_eu_pour_résultat (a_résulté_de)</code> </td>
</tr>
<tr class="odd">
<td>P124</td>
<td>transformed (was transformed by)</td>
<td>a transformé (a été transformé par)</td>
<td><code class="language-plaintext highlighter-rouge">P124_a_transformé (a_été_transformé_par)</code> </td>
</tr>
<tr class="even">
<td>P125</td>
<td>used object of type (was type of object used in)</td>
<td>a mobilisé un objet du type (a été le type d’objet employé pour)</td>
<td><code class="language-plaintext highlighter-rouge">P125_a_mobilisé_un_objet_du_type (a_été_le_type_d’objet_employé_pour)</code> </td>
</tr>
<tr class="odd">
<td>P126</td>
<td>employed (was employed in)</td>
<td>a employé (a été employé dans)</td>
<td><code class="language-plaintext highlighter-rouge">P126_a_employé (a_été_employé_dans)</code> </td>
</tr>
<tr class="even">
<td>P127</td>
<td>has broader term (has narrower term)</td>
<td>a pour terme général (a pour terme spécifique)</td>
<td><code class="language-plaintext highlighter-rouge">P127_a_pour_terme_général (a_pour_terme_spécifique)</code> </td>
</tr>
<tr class="odd">
<td>P128</td>
<td>carries (is carried by)</td>
<td>est support de (a pour support)</td>
<td><code class="language-plaintext highlighter-rouge">P128_est_support_de (a_pour_support)</code> </td>
</tr>
<tr class="even">
<td>P129</td>
<td>is about (is subject of)</td>
<td>a pour sujet (est sujet de)</td>
<td><code class="language-plaintext highlighter-rouge">P129_a_pour_sujet (est_sujet_de)</code> </td>
</tr>
<tr class="odd">
<td>P130</td>
<td>shows features of (features are also found on)</td>
<td>présente des caractéristiques de (a des caractéristiques également présentes sur)</td>
<td><code class="language-plaintext highlighter-rouge">P130_présente_des_caractéristiques (a_des_caractéristiques_également_présentes_sur)</code> de (a_des_caractéristiques_également_présentes_sur) </td>
</tr>
<tr class="even">
<td>P132</td>
<td>spatiotemporally overlaps with</td>
<td>se superpose spatio-temporellement et partiellement</td>
<td><p><code class="language-plaintext highlighter-rouge">P132_se_superpose_spatio</code>-temporellement_et_partiellement </p>
<p>Il semble préférable de ne pas utiliser "recouvrir" qui implique qu'une entité est appliquée sur l'autre qu'elle couvre entièrement.</p></td>
</tr>
<tr class="odd">
<td>P133</td>
<td>is spatiotemporally separated from</td>
<td>est distinct spatio-temporellement de</td>
<td><p><code class="language-plaintext highlighter-rouge">P133_est_distinct_spatio</code>-temporellement_de </p>
<p>Le terme "separated" ici semble faire référence à l'état d'un ensemble et non au fait de le disjoindre, il semble donc préférable d'utiliser distinct.</p></td>
</tr>
<tr class="even">
<td>P134</td>
<td>continued (was continued by)</td>
<td>a continué (a été continué par)</td>
<td><code class="language-plaintext highlighter-rouge">P134_a_continué (a_été_continué_par)</code> </td>
</tr>
<tr class="odd">
<td>P135</td>
<td>created type (was created by)</td>
<td>a créé le type (a été créé par)</td>
<td><code class="language-plaintext highlighter-rouge">P135_a_créé_le_type (a_été_créé_par)</code> </td>
</tr>
<tr class="even">
<td>P136</td>
<td>was based on (supported type creation)</td>
<td>a été fondé sur (a fondé la création du type)</td>
<td><code class="language-plaintext highlighter-rouge">P136_a_été_fondé_sur (a_fondé_la_création_du_type)</code> </td>
</tr>
<tr class="odd">
<td>P137</td>
<td>exemplifies (is exemplified by)</td>
<td>exemplifie (est exemplifié par)</td>
<td><code class="language-plaintext highlighter-rouge">P137_exemplifie (est_exemplifié_par)</code> </td>
</tr>
<tr class="even">
<td>P138</td>
<td>represents (has representation)</td>
<td>représente (est représenté par)</td>
<td><code class="language-plaintext highlighter-rouge">P138_représente (est_représenté_par)</code> </td>
</tr>
<tr class="odd">
<td>P139</td>
<td>has alternative form</td>
<td>a pour forme alternative</td>
<td><code class="language-plaintext highlighter-rouge">P139_a_pour_forme_alternative</code> </td>
</tr>
<tr class="even">
<td>P140</td>
<td>assigned attribute to (was attributed by)</td>
<td>a attribué à (a été attribué par)</td>
<td><code class="language-plaintext highlighter-rouge">P140_a_attribué_à (a_été_attribué_par)</code> </td>
</tr>
<tr class="odd">
<td>P141</td>
<td>assigned (was assigned by)</td>
<td>a attribué (a été attribué par)</td>
<td><code class="language-plaintext highlighter-rouge">P141_a_attribué (a_été_attribué_par)</code> </td>
</tr>
<tr class="even">
<td>P142</td>
<td>used constituent (was used in)</td>
<td>a mobilisé comme élément (a été mobilisé dans)</td>
<td><code class="language-plaintext highlighter-rouge">P142_a_mobilisé_comme_élément (a_été_mobilisé_dans)</code> </td>
</tr>
<tr class="odd">
<td>P143</td>
<td>joined (was joined by)</td>
<td>a fait adhérer (a adhéré par)</td>
<td><p><code class="language-plaintext highlighter-rouge">P143_a_fait_adhérer (a_adhéré_par)</code> </p>
<p>Cette formulation est cohérente avec E85 Adhésion.</p></td>
</tr>
<tr class="even">
<td>P144</td>
<td>joined with (gained member by)</td>
<td>a fait adhérer à (a accueilli un membre par)</td>
<td><code class="language-plaintext highlighter-rouge">P144_a_fait_adhérer_à (a_accueilli_un_membre_par)</code> </td>
</tr>
<tr class="odd">
<td>P145</td>
<td>separated (left by)</td>
<td>a dissocié de (s'est dissocié par)</td>
<td><code class="language-plaintext highlighter-rouge">P145_a_dissocié_de (s'est_dissocié_par)</code> </td>
</tr>
<tr class="even">
<td>P146</td>
<td>separated from (lost member by)</td>
<td>s'est dissocié par (a perdu un membre par)</td>
<td><code class="language-plaintext highlighter-rouge">P146_s’est_dissocié_par (a_perdu_un_membre_par)</code> </td>
</tr>
<tr class="odd">
<td>P147</td>
<td>curated (was curated by)</td>
<td>a géré (a été géré par)</td>
<td><code class="language-plaintext highlighter-rouge">P147_a_géré (a_été_géré_par)</code> </td>
</tr>
<tr class="even">
<td>P148</td>
<td>has component (is component of)</td>
<td>a pour composant (est composant de)</td>
<td><p><code class="language-plaintext highlighter-rouge">P148_a_pour_composant (est_composant_de)</code> </p>
<p>Cette formulation est cohérente avec P106 est composé de, etc.</p></td>
</tr>
<tr class="odd">
<td>P150</td>
<td>defines typical parts of (defines typical wholes for)</td>
<td>définit les éléments typiques de (définit l'ensemble typique pour)</td>
<td><code class="language-plaintext highlighter-rouge">P150_définit_les_éléments_typiques_de (définit_l'ensemble_typique_pour)</code> </td>
</tr>
<tr class="even">
<td>P151</td>
<td>was formed from (participated in)</td>
<td>a été formé de (a participé à)</td>
<td><code class="language-plaintext highlighter-rouge">P151_a_été_formé_de (a_participé_à)</code> </td>
</tr>
<tr class="odd">
<td>P152</td>
<td>has parent (is parent of)</td>
<td>a pour parent (est parent de)</td>
<td><code class="language-plaintext highlighter-rouge">P152_a_pour_parent (est_parent_de)</code> </td>
</tr>
<tr class="even">
<td>P156</td>
<td>occupies (is occupied by)</td>
<td>occupe (est occupé par)</td>
<td><code class="language-plaintext highlighter-rouge">P156_occupe (est_occupé_par)</code> </td>
</tr>
<tr class="odd">
<td>P157</td>
<td>is at rest relative to (provides reference space for)</td>
<td>est à l'arrêt par rapport à (procure un espace de référence pour)</td>
<td><code class="language-plaintext highlighter-rouge">P157_est_à_l’arrêt_par_rapport_à (procure_un_espace_de_référence_pour)</code> </td>
</tr>
<tr class="even">
<td>P160</td>
<td>has temporal projection (is temporal projection of)</td>
<td>a pour projection temporelle (est la projection temporelle de)</td>
<td><code class="language-plaintext highlighter-rouge">P160_a_pour_projection_temporelle (est_la_projection_temporelle_de)</code> </td>
</tr>
<tr class="odd">
<td>P161</td>
<td>has spatial projection (is spatial projection of)</td>
<td>a pour projection spatiale (est la projection spatiale de)</td>
<td><code class="language-plaintext highlighter-rouge">P161_a_pour_projection_spatiale (est_la_projection_spatiale_de)</code> </td>
</tr>
<tr class="even">
<td>P164</td>
<td>during (was time-span of)</td>
<td>durant (était l'intervalle temporel de)</td>
<td><code class="language-plaintext highlighter-rouge">P164_durant (était_l'intervalle_temporel_de)</code> </td>
</tr>
<tr class="odd">
<td>P165</td>
<td>incorporates (is incorporated in)</td>
<td>inclut (est inclus dans)</td>
<td><p><code class="language-plaintext highlighter-rouge">P165_inclut (est_inclus_dans)</code> </p>
<p>Cette formulation est cohérente avec la traduction de P5, P45, P86, P89.</p></td>
</tr>
<tr class="even">
<td>P166</td>
<td>was a presence of (had presence)</td>
<td>a été une présence de (a eu pour présence)</td>
<td><p><code class="language-plaintext highlighter-rouge">P166_a_été_une_présence_de (a_eu_pour_présence)</code> </p>
<p>Cette formulation est cohérente avec la traduction de P195.</p></td>
</tr>
<tr class="odd">
<td>P167</td>
<td>at (was place of)</td>
<td>à (a été le lieu de)</td>
<td><code class="language-plaintext highlighter-rouge">P167_à (a_été_le_lieu_de)</code> </td>
</tr>
<tr class="even">
<td>P168</td>
<td>place is defined by (defines place)</td>
<td>lieu défini par (définit le lieu)</td>
<td><code class="language-plaintext highlighter-rouge">P168_lieu_défini_par (définit_le_lieu)</code> </td>
</tr>
<tr class="odd">
<td>P169</td>
<td>defines spacetime volume (spacetime volume is defined by)</td>
<td>volume spatio-temporel défini par (définit le volume spatio-temporel )</td>
<td><code class="language-plaintext highlighter-rouge">P169_volume_spatio (définit_le_volume_spatio-temporel_)</code>-temporel_défini_par (définit_le_volume_spatio-temporel) </td>
</tr>
<tr class="even">
<td>P170</td>
<td>defines time (time is defined by)</td>
<td>temps défini par (définit le temps)</td>
<td><code class="language-plaintext highlighter-rouge">P170_temps_défini_par (définit_le_temps)</code> </td>
</tr>
<tr class="odd">
<td>P171</td>
<td>at some place within</td>
<td>a eu lieu quelque part dans</td>
<td><code class="language-plaintext highlighter-rouge">P171_a_eu_lieu_quelque_part_dans</code> </td>
</tr>
<tr class="even">
<td>P172</td>
<td>contains</td>
<td>contient</td>
<td><code class="language-plaintext highlighter-rouge">P172_contient</code> </td>
</tr>
<tr class="odd">
<td>P173</td>
<td>starts before or with the end of (ends after or with the start of)</td>
<td>commence avant ou au moment de la fin de (se termine après ou au moment du début de)</td>
<td><code class="language-plaintext highlighter-rouge">P173_commence_avant_ou_au_moment_de_la_fin_de (se_termine_après_ou_au_moment_du_début_de)</code> </td>
</tr>
<tr class="even">
<td>P174</td>
<td>starts before the end of (ends after the start of)</td>
<td>commence avant la fin de (se termine après le début de)</td>
<td><code class="language-plaintext highlighter-rouge">P174_commence_avant_la_fin_de (se_termine_après_le_début_de)</code> </td>
</tr>
<tr class="odd">
<td>P175</td>
<td>starts before or with the start of (starts after or with the start of)</td>
<td>commence avant ou au moment du début de (commence après ou au moment du début de)</td>
<td><code class="language-plaintext highlighter-rouge">P175_commence_avant_ou_au_moment_du_début_de (commence_après_ou_au_moment_du_début_de)</code> </td>
</tr>
<tr class="even">
<td>P176</td>
<td>starts before the start of (starts after the start of)</td>
<td>commence avant le début de (commence après le début de)</td>
<td><code class="language-plaintext highlighter-rouge">P176_commence_avant_le_début_de (commence_après_le_début_de)</code> </td>
</tr>
<tr class="odd">
<td>P177</td>
<td>assigned property type</td>
<td>a attribué le type de propriété</td>
<td><code class="language-plaintext highlighter-rouge">P177_a_attribué_le_type_de_propriété</code> </td>
</tr>
<tr class="even">
<td>P179</td>
<td>had sales price (was sales price of)</td>
<td>a eu pour prix de vente (a été le prix de vente de)</td>
<td><code class="language-plaintext highlighter-rouge">P179_a_eu_pour_prix_de_vente (a_été_le_prix_de_vente_de)</code> </td>
</tr>
<tr class="odd">
<td>P180</td>
<td>has currency (was currency of)</td>
<td>a pour monnaie (était la monnaie de)</td>
<td><code class="language-plaintext highlighter-rouge">P180_a_pour_monnaie (était_la_monnaie_de)</code> </td>
</tr>
<tr class="even">
<td>P181</td>
<td>has amount</td>
<td>a pour quantité</td>
<td><code class="language-plaintext highlighter-rouge">P181_a_pour_quantité</code> </td>
</tr>
<tr class="odd">
<td>P182</td>
<td>ends before or with the start of (starts after or with the end of)</td>
<td>se termine avant ou au moment du début de (commence après ou au moment de la fin de)</td>
<td><code class="language-plaintext highlighter-rouge">P182_se_termine_avant_ou_au_moment_du_début_de (commence_après_ou_au_moment_de_la_fin_de)</code> </td>
</tr>
<tr class="even">
<td>P183</td>
<td>ends before the start of (starts after the end of)</td>
<td>se termine avant le début de (commence après la fin de)</td>
<td><code class="language-plaintext highlighter-rouge">P183_se_termine_avant_le_début_de (commence_après_la_fin_de)</code> </td>
</tr>
<tr class="odd">
<td>P184</td>
<td>ends before or with the end of (ends with or after the end of)</td>
<td>se termine avant ou au moment de la fin de (se termine au moment de ou après la fin de)</td>
<td><code class="language-plaintext highlighter-rouge">P184_se_termine_avant_ou_au_moment_de_la_fin_de (se_termine_au_moment_de_ou_après_la_fin_de)</code> </td>
</tr>
<tr class="even">
<td>P185</td>
<td>ends before the end of (ends after the end of)</td>
<td>se termine avant la fin de (se termine après la fin de)</td>
<td><code class="language-plaintext highlighter-rouge">P185_se_termine_avant_la_fin_de (se_termine_après_la_fin_de)</code> </td>
</tr>
<tr class="odd">
<td>P186</td>
<td>produced thing of product type (is produced by)</td>
<td>a produit une chose du type (est produit par)</td>
<td><code class="language-plaintext highlighter-rouge">P186_a_produit_une_chose_du_type (est_produit_par)</code> </td>
</tr>
<tr class="even">
<td>P187</td>
<td>has production plan (is production plan for)</td>
<td>a pour plan de production (est le plan de production de)</td>
<td><code class="language-plaintext highlighter-rouge">P187_a_pour_plan_de_production (est_le_plan_de_production_de)</code> </td>
</tr>
<tr class="odd">
<td>P188</td>
<td>requires production tool (is production tool for)</td>
<td>nécessite l'outil (est l'outil de production de)</td>
<td><code class="language-plaintext highlighter-rouge">P188_nécessite_l’outil (est_l'outil_de_production_de)</code> </td>
</tr>
<tr class="even">
<td>P189</td>
<td>approximates (is approximated by)</td>
<td>approxime (est approximé par)</td>
<td><code class="language-plaintext highlighter-rouge">P189_approxime (est_approximé_par)</code> </td>
</tr>
<tr class="odd">
<td>P190</td>
<td>has symbolic content</td>
<td>a pour contenu symbolique</td>
<td><code class="language-plaintext highlighter-rouge">P190_a_pour_contenu_symbolique</code> </td>
</tr>
<tr class="even">
<td>P191</td>
<td>had duration (was duration of)</td>
<td>a eu pour durée (était la durée de)</td>
<td><code class="language-plaintext highlighter-rouge">P191_a_eu_pour_durée (était_la_durée_de)</code> </td>
</tr>
<tr class="odd">
<td>P195</td>
<td>was a presence of (had presence)</td>
<td>a été une présence de (a eu pour présence)</td>
<td><p><code class="language-plaintext highlighter-rouge">P195_a_été_une_présence_de (a_eu_pour_présence)</code> </p>
<p>Cette formulation est cohérente avec P166.</p></td>
</tr>
<tr class="even">
<td>P196</td>
<td>defines (is defined by)</td>
<td>définit (est défini par)</td>
<td><code class="language-plaintext highlighter-rouge">P196_définit (est_défini_par)</code> </td>
</tr>
<tr class="odd">
<td>P197</td>
<td>covered parts of (was partially covered by)</td>
<td>a couvert des parties de (a été partiellement couvert par)</td>
<td><p><code class="language-plaintext highlighter-rouge">P197_a_couvert_des_parties_de (a_été_partiellement_couvert_par)</code> </p>
<p>Ici le terme "parts" ne fait pas référence à des éléments (contrairement à P57 et P150), mais à une portion, ou partie, couverte.</p>
</td>
</tr>
<tr class="even">
<td>P198</td>
<td>holds or supports (is held or supported by)</td>
<td>contient ou soutient (est détenu ou soutenu par)</td>
<td><p><code class="language-plaintext highlighter-rouge">P198_contient_ou_soutient (est_détenu_ou_soutenu_par)</code> </p>
<p>"Contient" est le terme le plus approprié car cette propriété s’applique à des objets qui renferment quelque chose</p>
</td>
</tr>
<tr class="odd">
<td>PC0</td>
<td>typed CRM Entity</td>
<td>A été typé entité CRM</td>
<td><code class="language-plaintext highlighter-rouge">PC0_A_été_typé_entité_CRM</code> </td>
</tr>
<tr class="even">
<td>P01</td>
<td>has domain (is domain of)</td>
<td>a pour domaine (est le domaine de)</td>
<td><code class="language-plaintext highlighter-rouge">P01_a_pour_domaine (est_le_domaine_de)</code> </td>
</tr>
<tr class="odd">
<td>P02</td>
<td>has range (is range of)</td>
<td>a pour portée (est la portée de)</td>
<td><code class="language-plaintext highlighter-rouge">P02_a_pour_portée (est_la_portée_de)</code> </td>
</tr>
<tr class="even">
<td>P03</td>
<td>has range literal</td>
<td>a pour portée littérale</td>
<td><code class="language-plaintext highlighter-rouge">P03_a_pour_portée_littérale</code> </td>
</tr>
<tr class="odd">
<td>PC3</td>
<td>has note</td>
<td>A pour note</td>
<td><code class="language-plaintext highlighter-rouge">PC3_A_pour_note</code> </td>
</tr>
<tr class="even">
<td>P3.1</td>
<td>has type</td>
<td>a pour type</td>
<td><code class="language-plaintext highlighter-rouge">P3.1_a_pour_type</code> </td>
</tr>
<tr class="odd">
<td>PC14</td>
<td>carried out by</td>
<td>A été effectué par</td>
<td><code class="language-plaintext highlighter-rouge">PC14_A_été_effectué_par</code> </td>
</tr>
<tr class="even">
<td>P14.1</td>
<td>in the role of</td>
<td>dans le rôle de</td>
<td><code class="language-plaintext highlighter-rouge">P14.1_dans_le_rôle_de</code> </td>
</tr>
<tr class="odd">
<td>PC16</td>
<td>used specific object</td>
<td>A mobilisé l'objet spécifique (A été mobilisé pour)</td>
<td><code class="language-plaintext highlighter-rouge">PC16_A_mobilisé_l’objet_spécifique (A_été_mobilisé_pour)</code> </td>
</tr>
<tr class="even">
<td>P16.1</td>
<td>mode of use</td>
<td>mode d'utilisation</td>
<td><code class="language-plaintext highlighter-rouge">P16.1_mode_d’utilisation</code> </td>
</tr>
<tr class="odd">
<td>PC19</td>
<td>was intended use of</td>
<td>Était l'usage prévu de (A été élaboré pour)</td>
<td><code class="language-plaintext highlighter-rouge">PC19_Était_l’usage_prévu_de (A_été_élaboré_pour)</code> </td>
</tr>
<tr class="even">
<td>P19.1</td>
<td>mode of use</td>
<td>mode d'utilisation</td>
<td><code class="language-plaintext highlighter-rouge">P19.1_mode_d’utilisation</code> </td>
</tr>
<tr class="odd">
<td>PC62</td>
<td>depicts</td>
<td>Illustre</td>
<td><code class="language-plaintext highlighter-rouge">PC62_Illustre</code> </td>
</tr>
<tr class="even">
<td>P62.1</td>
<td>mode of depiction</td>
<td>mode d'illustration</td>
<td><code class="language-plaintext highlighter-rouge">P62.1_mode_d’illustration</code> </td>
</tr>
<tr class="odd">
<td>PC67</td>
<td>refers to</td>
<td>Renvoie à</td>
<td><code class="language-plaintext highlighter-rouge">PC67_Renvoie_à</code> </td>
</tr>
<tr class="even">
<td>P67.1</td>
<td>has type</td>
<td>a pour type</td>
<td><code class="language-plaintext highlighter-rouge">P67.1_a_pour_type</code> </td>
</tr>
<tr class="odd">
<td>PC69</td>
<td>is associated with</td>
<td>Est associé à</td>
<td><code class="language-plaintext highlighter-rouge">PC69_Est_associé_à</code> </td>
</tr>
<tr class="even">
<td>P69.1</td>
<td>has type</td>
<td>a pour type</td>
<td><code class="language-plaintext highlighter-rouge">P69.1_a_pour_type</code> </td>
</tr>
<tr class="odd">
<td>PC102</td>
<td>has title</td>
<td>A pour titre</td>
<td><code class="language-plaintext highlighter-rouge">PC102_A_pour_titre</code> </td>
</tr>
<tr class="even">
<td>P102.1</td>
<td>has type</td>
<td>a pour type</td>
<td><code class="language-plaintext highlighter-rouge">P102.1_a_pour_type</code> </td>
</tr>
<tr class="odd">
<td>PC107</td>
<td>has current or former member</td>
<td>A pour membre actuel ou antérieur (Est membre actuel ou antérieur de)</td>
<td><code class="language-plaintext highlighter-rouge">PC107_A_pour_membre_actuel_ou_antérieur (Est_membre_actuel_ou_antérieur_de)</code> </td>
</tr>
<tr class="even">
<td>P107.1</td>
<td>kind of member</td>
<td>sorte de membre</td>
<td><code class="language-plaintext highlighter-rouge">P107.1_sorte_de_membre</code> </td>
</tr>
<tr class="odd">
<td>PC130</td>
<td>shows features of</td>
<td>Présente des caractéristiques de</td>
<td><code class="language-plaintext highlighter-rouge">PC130_Présente_des_caractéristiques_de</code> </td>
</tr>
<tr class="even">
<td>P130.1</td>
<td>kind of similarity</td>
<td>sorte de similarité</td>
<td><code class="language-plaintext highlighter-rouge">P130.1_sorte_de_similarité</code> </td>
</tr>
<tr class="odd">
<td>PC136</td>
<td>was based on</td>
<td>Était basé sur</td>
<td><code class="language-plaintext highlighter-rouge">PC136_Était_basé_sur</code> </td>
</tr>
<tr class="even">
<td>P136.1</td>
<td>in the taxonomic role</td>
<td>dans le rôle taxonomique de</td>
<td><code class="language-plaintext highlighter-rouge">P136.1_dans_le_rôle_taxonomique_de</code> </td>
</tr>
<tr class="odd">
<td>PC137</td>
<td>exemplifies</td>
<td>Exemplifie</td>
<td><code class="language-plaintext highlighter-rouge">PC137_Exemplifie</code> </td>
</tr>
<tr class="even">
<td>P137.1</td>
<td>in the taxonomic role</td>
<td>dans le rôle taxonomique de</td>
<td><code class="language-plaintext highlighter-rouge">P137.1_dans_le_rôle_taxonomique_de</code> </td>
</tr>
<tr class="odd">
<td>PC138</td>
<td>represents</td>
<td>Représente</td>
<td><code class="language-plaintext highlighter-rouge">PC138_Représente</code> </td>
</tr>
<tr class="even">
<td>P138.1</td>
<td>mode of representation</td>
<td>mode de représentation</td>
<td><code class="language-plaintext highlighter-rouge">P138.1_mode_de_représentation</code> </td>
</tr>
<tr class="odd">
<td>PC139</td>
<td>has alternative form</td>
<td>A pour forme alternative</td>
<td><code class="language-plaintext highlighter-rouge">PC139_A_pour_forme_alternative</code> </td>
</tr>
<tr class="even">
<td>P139.1</td>
<td>has type</td>
<td>a pour type</td>
<td><code class="language-plaintext highlighter-rouge">P139.1_a_pour_type</code> </td>
</tr>
<tr class="odd">
<td>PC144</td>
<td>joined with</td>
<td>A fait adhérer à</td>
<td><code class="language-plaintext highlighter-rouge">PC144_A_fait_adhérer_à</code> </td>
</tr>
<tr class="even">
<td>P144.1</td>
<td>kind of member</td>
<td>sorte de membre</td>
<td><code class="language-plaintext highlighter-rouge">P144.1_sorte_de_membre</code> </td>
</tr>
</tbody>
</table>


