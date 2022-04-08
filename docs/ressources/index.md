---
layout: page
title: Index
permalink: /ressources/index
sidebar: index
tab: ressources
date: 2022-04-07
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

|CODE|EN|FR|Note|
|---|---|---|---|
|E1|CRM Entity|Entité CRM|`E1_Entité_CRM`|
|E2|Temporal Entity|Entité temporelle|`E2_Entité_temporelle`|
|E3|Condition State|État matériel|`E3_État_matériel`<br>Condition est un terme qui porte sur une situation factuelle reposant sur d'autres faits alors que l'état porte sur une situation à un moment donné.|
|E4|Period|Période|`E4_Période`|
|E5|Event|Évènement|`E5_Évènement`|
|E6|Destruction|Destruction|`E6_Destruction`|
|E7|Activity|Activité|`E7_Activité`|
|E8|Acquisition|Acquisition|`E8_Acquisition`|
|E9|Move|Déplacement|`E9_Déplacement`|
|E10|Transfer of Custody|Transfert de la garde|`E10_Transfert_de_la_garde`<br>À l'heure actuelle, la seule traduction officielle sur Termium concerne l'immobilier donc c'est une équivalence à valider ou officiellement établir. Ceci dit, il semble y avoir un concept légal en France qui en ferait une traduction valable.|
|E11|Modification|Modification|`E11_Modification`|
|E12|Production|Production|`E12_Production`|
|E13|Attribute Assignment|Assignation d’attribut|`E13_Assignation_d’attribut`|
|E14|Condition Assessment|Évaluation d'état matériel|`E14_Évaluation_d’état_matériel`|
|E15|Identifier Assignment|Assignation d'identifiant|`E15_Assignation_d’identifiant`<br>Il semble préférable d'utiliser Identifiant pour référer au code unique désignant une chose ou une personne puisqu'un Identificateur est un symbole employé pour représenter une variable ou une fonction et que ce terme pourra s'avérer utile ailleurs dans l'effort de traduction, soit afin de désigner de tels symboles, ou lorsque viendra le temps de qualifier d'autres éléments.|
|E16|Measurement|Mesurage|`E16_Mesurage`|
|E17|Type Assignment|Assignation de type|`E17_Assignation_de_type`|
|E18|Physical Thing|Chose Matérielle|`E18_Chose_matérielle`<br>Physical thing sera traduit par chose matérielle qui comprend Physical Object-Objet matériel donc pour être cohérents on utilisera Physical Item - entité matérielle.|
|E19|Physical Object|Objet matériel|`E19_Objet_matériel`|
|E20|Biological Object|Objet biologique|`E20_Objet_biologique`|
|E21|Person|Personne|`E21_Personne`|
|E22|Human-Made Object|Objet élaborée par l’humain|`E22_Objet_élaboré_par_l’humain`<br>La fabrication repose sur le fait d'utiliser des matières premières de manière à imiter un original tandis que le façonnement reflète le fait qu'il s'agit d'une chose faite par l'humain reposant sur le fait d'utiliser des matières premières, ce qui est plus près de la définition originale. <br>Toutefois, le terme « Human-Made » est parfois employé dans des contextes où il n’y a pas de référence à l’emploi de matière dans la création d’une chose (notamment l’entité E71_Human-Made_Thing). Il est donc préférable, dans un souci de cohérence, de le traduire par « élaboré par l’humain ».|
|E24|Physical Human-Made Thing|Chose matérielle élaborée par l’humain|`E24_Chose_matérielle_élaborée_par_l’humain`<br>Le terme « Human-Made » est parfois employé dans des contextes où il n’y a pas de référence à l’emploie de matière dans la création d’une chose (notamment l’entité E71_Human-Made_Thing). Il est donc préférable, dans un souci de cohérence, de le traduire par « élaboré par l’humain ».|
|E25|Human-Made Feature|Caractéristique élaborée par l’humain|`E25_Caractéristique_élaborée_par_l’humain`<br>Le terme « Human-Made » est parfois employé dans des contextes où il n’y a pas de référence à l’emploie de matière dans la création d’une chose (notamment l’entité E71_Human-Made_Thing). Il est donc préférable, dans un souci de cohérence, de le traduire par « élaboré par l’humain ».|
|E26|Physical Feature|Caractéristique physique|`E26_Caractéristique_physique`|
|E27|Site|Site|`E27_Site`|
|E28|Conceptual Object|Objet conceptuel|`E28_Objet_conceptuel`|
|E29|Design or Procedure|Conceptualisation ou procédure|`E29_Conceptualisation_ou_procédure`<br>Le terme « conceptualisation » a été préféré à « conception » car cette dernière inclut à la fois le processus d’idéation mentale (concevoir une idée) et le résultat de ce processus, alors que la « conceptualisation » signale qu’il s’agit d’organiser des concepts sans que ce qui en résulte ne soit déterminant, ce qui est plus près de la définition originale de la classe. |
|E30|Right|Droit|`E30_Droit`|
|E31|Document|Document|`E31_Document`|
|E32|Authority Document|Document de référence|`E32_Document_de_référence`|
|E33|Linguistic Object|Objet linguistique|`E33_Objet_linguistique`|
|E34|Inscription|Inscription|`E34_Inscription`|
|E35|Title|Titre|`E35_Titre`|
|E36|Visual Item|Entité visuelle|`E36_Entité_visuelle`|
|E37|Mark|Marque|`E37_Marque`|
|E39|Actor|Actant|`E39_Actant`<br>L'introduction de CIDOC CRM fait usage du terme Agent pour référer à des entités actantes qui ne sont pas définies comme des personnes ou des groupes. Il semble donc préférable de s'en tenir à Acteur ici afin d'utiliser Agent autre part.<br>Toutefois, le terme « Acteur » n’étant pas inclusif, et pour éviter d’employer la forme « Acteur·rice·x » plus difficile à lire, il est préférable d’utiliser le terme « Actant », sa définition étant très proche de celle d’« Acteur ».|
|E41|Appellation|Appellation|`E41_Appellation`|
|E42|Identifier|Identifiant|`E42_Identifiant`|
|E52|Time-Span|Intervalle temporel|`E52_Intervalle_temporel`<br>Laps de temps est une redite puisqu'un laps est l'écoulement du temps durant un intervalle. Il semble préférable d'adopter une graphie plus proche de la forme originale. Ceci est en outre cohérent avec les autres appellations temporelles.|
|E53|Place|Lieu|`E53_Lieu`|
|E54|Dimension|Dimension|`E54_Dimension`|
|E55|Type|Type|`E55_Type`|
|E56|Language|Langue|`E56_Langue`|
|E57|Material|Matériau|`E57_Matériau`|
|E58|Measurement Unit|Unité de mesure|`E58_Unité_de_mesure`|
|E59|Primitive Value|Valeur primitive|`E59_Valeur_primitive`|
|E60|Number|Nombre|`E60_Nombre`|
|E61|Time Primitive|Primitive temporelle|`E61_Primitive_temporelle`|
|E62|String|Chaîne de caractères|`E62_Chaîne_de_caractères`|
|E63|Beginning of Existence|Début d'existence|`E63_Début_d’existence`|
|E64|End of Existence|Fin d'existence|`E64_Fin_d’existence`|
|E65|Creation|Création|`E65_Création`|
|E66|Formation|Formation|`E66_Formation`|
|E67|Birth|Naissance|`E67_Naissance`|
|E68|Dissolution|Dissolution|`E68_Dissolution`|
|E69|Death|Mort|`E69_Mort`|
|E70|Thing|Chose|`E70_Chose`|
|E71|Human-Made Thing|Chose élaborée par l’humain|`E71_Chose_élaborée_par_l’humain`<br>Les termes « fabriqué » et « façonné » portent le sens d’emploie de matière dans la création d’une chose, ce qui n'inclut pas tous les cas d’utilisation de cette entité, comme par exemple la création d’un poème. Il est donc préférable de traduire le terme « Human-Made » par « élaboré par l’humain », plus inclusif.|
|E72|Legal Object|Objet juridique|`E72_Objet_juridique`<br>La définition se rapporte au droit (juridique) plutôt qu'à ce qui s'y conforme (légal).|
|E73|Information Object|Objet informationnel|`E73_Objet_informationnel`|
|E74|Group|Groupe|`E74_Groupe`|
|E77|Persistent Item|Entité persistante|`E77_Entité_persistante`|
|E78|Curated Holding|Collection|`E78_Collection`|
|E79|Part Addition|Ajout d'élément|`E79_Ajout_d’élément`<br>La définition de la classe précise qu'il s'agit bien d'ajouter une partie physique à un objet, ce qui semble plus près de la définition d'ajout.|
|E80|Part Removal|Retrait d’élément|`E80_Retrait_d’élément`<br>La définition de la classe précise qu'il s'agit bien de retirer une partie physique à un objet, ce qui semble plus près de la définition de retrait.|
|E81|Transformation|Transformation|`E81_Transformation`|
|E83|Type Creation|Création de type|`E83_Création_de_type`|
|E85|Joining|Adhésion|`E85_Adhésion`<br>Puisque la classe réfère à des personnes dotées d'intentionnalité, il semble plus juste d'utiliser le terme adhésion puisque l'intégration peut faire référence à des objets intégrés à des ensembles.|
|E86|Leaving|Départ|`E86_Départ`|
|E87|Curation Activity|Activité curatoriale|`E87_Activité_curatoriale`<br>Puisqu'il s'agit des activités ayant trait à la collection et non pas seulement à sa conservation (preservation), il semble préférable ici d'utiliser l'adjectif « curatoriale » qui est fréquemment utilisé dans le milieu muséal au sens anglophone du terme « curatorial ». |
|E89|Propositional Object|Objet propositionnel|`E89_Objet_propositionnel`|
|E90|Symbolic Object|Objet symbolique|`E90_Objet_symbolique`|
|E92|Spacetime Volume|Volume spatio-temporel|`E92_Volume_spatio-temporel`<br>L'utilisation de "spatio-temporel" est cohérente avec les autres choix faits dans la traduction (Intervalle Temporel, etc.).|
|E93|Presence|Présence|`E93_Présence`|
|E94|Space Primitive|Primitive spatiale|`E94_Primitive_spatiale`<br>Cette formulation est cohérente avec les autres choix de la traduction (Primitive Temporelle, Primitive Spatio-Temporelle, Volume Spatio-Temporel).|
|E95|Spacetime Primitive|Primitive spatio-temporelle|`E95_Primitive_spatio-temporelle`<br>Cette formulation est cohérente avec les autres choix de la traduction (Primitive Temporelle, Primitive Spatiale, Volume Spatio-Temporel).|
|E96|Purchase|Achat|`E96_Achat`|
|E97|Monetary Amount|Valeur monétaire|`E97_Valeur_monétaire`<br>En français, le caractère économique et mesurable d'un bien est reflété dans l'utilisation du terme valeur associé à la monnaie de sorte qu'il n'y a pas d'ambiguïté quant à l'aspect quantitatif et que l'expression d'usage semble plus proche de la définition originale qu'une traduction littérale.|
|E98|Currency|Monnaie|`E98_Monnaie`|
|E99|Product Type|Modèle de produit|`E99_Modèle_de_produit`<br>Le terme modèle est celui qui est le plus proche de la définition de cette classe. Cependant, puisque le terme est utilisé dans d'autres contextes au sein de la spécification CIDOC CRM, le nom "Modèle de Produit" semble préférable.|
|P1|is identified by (identifies)|est identifié par (identifie)|`P1_est_identifié_par (identifie)`|
|P2|has type (is type of)|a pour type (est le type de)|`P2_a_pour_type (est_le_type_de)`<br>Puisque la plupart du temps le type est appliqué à l'information pour la classifier et qu'il n'est pas inhérent, il semble préférable d'utiliser une formulation plus proche de l'assignation.<br>Cette formulation est cohérente avec les autres choix de la traduction (a pour note, a pour durée, etc.)|
|P3|has note|a pour note|`P3_a_pour_note`|
|P4|has time-span (is time-span of)|a pour intervalle temporel (est l'intervalle temporel de)|`P4_a_pour_intervalle_temporel (est_l’intervalle_temporel_de)`|
|P5|consists of (forms part of)|comprend (fait partie de)|`P5_comprend (fait_partie_de)`<br>Consister implique généralement que toutes les parties qui forment un tout sont énumérées, ce qui n'est pas le cas selon la définition actuelle de sorte que comprendre semble préférable.|
|P7|took place at (witnessed)|a eu lieu dans (a été témoin de)|`P7_a_eu_lieu_dans (a_été_témoin_de)`|
|P8|took place on or within (witnessed)|a eu lieu à (a été témoin de)|`P8_a_eu_lieu_à (a_été_témoin_de)`|
|P9|consists of (forms part of)|comprend (fait partie de)|`P9_comprend (fait_partie_de)`<br>Consister implique généralement que toutes les parties qui forment un tout sont énumérées, ce qui n'est pas le cas selon la définition actuelle de sorte que comprendre semble préférable.|
|P10|falls within (contains)|s’insère dans (contient)|`P10_s’insère_dans (contient)`|
|P11|had participant (participated in)|a eu pour actant participant (a participé à)|`P11_a_eu_pour_actant_participant (a_participé_à)`<br>Puisque l'action est précise et achevée ("instances of E53 Place and E52 Time-Span where and when these events happened provide us with constraints about the presence of the related instances of E39 Actor in the past") plutôt que d'être en cours, l'utilisation du passé composé semble préférable à l'imparfait.|
|P12|occurred in the presence of (was present at)|a eu lieu en présence de (a été présent à)|`P12_a_eu_lieu_en_présence_de (a_été_présent_à)`<br>La locution "a eu lieu" est cohérente avec le reste de la traduction (a eu lieu dans, a eu lieu à).<br>Puisque l'action est précise et achevée ("instance of E53 Place and the instance of E52 Time-Span where and when these events happened provide us with constraints about the presence of the related instance E77 Persistent Item in the past") plutôt que d'être en cours, l'utilisation du passé composé semble préférable à l'imparfait.|
|P13|destroyed (was destroyed by)|a détruit (a été détruit par)|`P13_a_détruit (a_été_détruit_par)`|
|P14|carried out by (performed)|a été effectué par (a effectué)|`P14_a_été_effectué_par (a_effectué)`<br>À des fins de cohérence, il semble préférable d'utiliser le verbe effectuer tant pour l'un que pour l'autre. Qui plus est, c'est un terme plus proche de la définition qui implique une causalité (légale ou autre).|
|P15|was influenced by (influenced)|a été influencé par (a influencé)|`P15_a_été_influencé_par (a_influencé)`|
|P16|used specific object (was used for)|a mobilisé l'objet spécifique (a été mobilisé pour)|`P16_a_mobilisé_l’objet_spécifique (a_été_mobilisé_pour)`|
|P17|was motivated by (motivated)|a été motivé par (a motivé)|`P17_a_été_motivé_par (a_motivé)`|
|P19|was intended use of (was made for):|a été l'usage prévu de (a été élaboré pour)|`P19_a_été_l’usage_prévu_de (a_été_élaboré_pour)`<br>Cette formulation est cohérente avec le reste de la traduction (P19, P68).|
|P20|had specific purpose (was purpose of)|a eu pour finalité spécifique (a été la finalité de)|`P20_a_eu_pour_finalité_spécifique (a_été_la_finalité_de)`<br>Le but implique une intention que des activités n'ont pas (puisque c'est l'actant qui est doté d'intention).|
|P21|had general purpose (was purpose of)|a eu pour finalité générale (a été la finalité de)|`P21_a_eu_pour_finalité_générale (a_été_la_finalité_de)`|
|P22|transferred title to (acquired title through)|a transféré le titre de propriété à (a acquis le titre de propriété par)|`P22_a_transféré_le_titre_de_propriété_à (a_acquis_le_titre_de_propriété_par)`<br>Le transfert, l'acquisition et la cession sont des termes plus proches de la réalité juridique et semblent donc plus appropriés.|
|P23|transferred title from (surrendered title through)|a transféré le titre de propriété de (a cédé le titre de propriété à)|`P23_a_transféré_le_titre_de_propriété_de (a_cédé_le_titre_de_propriété_à)`<br>Le transfert, l'acquisition et la cession sont des termes plus proches de la réalité juridique et semblent donc plus appropriés.|
|P24|transferred title of (changed ownership through)|a transféré le titre de propriété du (a changé de propriétaire par)|`P24_a_transféré_le_titre_de_propriété_du (a_changé_de_propriétaire_par)`<br>Le transfert, l'acquisition et la cession sont des termes plus proches de la réalité juridique et semblent donc plus appropriés.|
|P25|moved (moved by)|a déplacé (a été déplacé par)|`P25_a_déplacé (a_été_déplacé_par)`|
|P26|moved to (was destination of)|a déplacé vers (a été la destination de)|`P26_a_déplacé_vers (a_été_la_destination_de)`|
|P27|moved from (was origin of)|a déplacé depuis (a été le point de départ de)|`P27_a_déplacé_depuis (a_été_le_point_de_départ_de)`|
|P28|custody surrendered by (surrendered custody through)|a mis fin à la garde par (a cédé la garde par)|`P28_a_mis_fin_à_la_garde_par (a_cédé_la_garde_par)`<br>L'utilisation du terme par est cohérente avec les autres propositions et plus simple.|
|P29|custody received by (received custody through)|a confié la garde par (a reçu la garde par)|`P29_a_confié_la_garde_par (a_reçu_la_garde_par)`<br>L'utilisation du terme par est cohérente avec les autres propositions et plus simple.|
|P30|transferred custody of (custody transferred through)|a transféré la garde de (a été l’objet d’un transfert de garde par)|`P30_a_transféré_la_garde_de (a_été_l’objet_d’un_transfert_de_garde_par)`<br>L'utilisation du terme par est cohérente avec les autres propositions et plus simple.|
|P31|has modified (was modified by)|a modifié (a été modifié par)|`P31_a_modifié (a_été_modifié_par)`|
|P32|used general technique (was technique of)|a mobilisé comme technique générale (a été la technique générale mise en œuvre dans)|`P32_a_mobilisé_comme_technique_générale (a_été_la_technique_générale_mise_en_œuvre_dans)`<br>Une technique spécifique plutôt que la puisqu'il est possible que ce ne soit pas la seule.<br>Générique est un anglicisme de sorte que nous avons préféré générale.|
|P33|used specific technique (was used by)|a mobilisé comme technique spécifique (a été la technique spécifique mise en œuvre dans)|`P33_a_mobilisé_comme_technique_spécifique (a_été_la_technique_spécifique_mise_en_œuvre_dans)`<br>Une technique spécifique plutôt que la puisqu'il est possible que ce ne soit pas la seule.|
|P34|concerned (was assessed by)|a porté sur (a été évalué par)|`P34_a_porté_sur (a_été_évalué_par)`|
|P35|has identified (was identified by)|a identifié (a été identifié par)|`P35_a_identifié (a_été_identifié_par)`|
|P37|assigned (was assigned by)|a assigné (a été assigné par)|`P37_a_assigné (a_été_assigné_par)`|
|P38|deassigned (was deassigned by)|a retiré l'assignation de (a été retiré  par)|`P38_a_retiré_l’assignation_de (a_été_retiré_par)`|
|P39|measured (was measured by)|a mesuré (a été mesuré par)|`P39_a_mesuré (a_été_mesuré_par)`|
|P40|observed dimension (was observed in)|a relevé comme dimension (a été relevé par)|`P40_a_relevé_comme_dimension (a_été_relevé_par)`|
|P41|classified (was classified by)|a classifié (a été classifié par)|`P41_a_classifié (a_été_classifié_par)`|
|P42|assigned (was assigned by)|a assigné (a été assigné par)|`P42_a_assigné (a_été_assigné_par)`|
|P43|has dimension (is dimension of)|a pour dimension (est la dimension de)|`P43_a_pour_dimension (est_la_dimension_de)`|
|P44|has condition (is condition of)|a pour état matériel (est l’état matériel de)|`P44_a_pour_état_matériel (est_l’état_matériel_de)`|
|P45|consists of (is incorporated in)|comprend (est inclus dans)|`P45_comprend (est_inclus_dans)`<br>Cette formulation est cohérente avec le reste de la traduction (P5 "consists of (forms part of); consiste en (fait partie de)").<br>Cette formulation est cohérente avec le reste de la traduction (P46 "is composed of (forms part of); est composé de (fait partie de)").<br>Cette formulation est cohérente avec le reste de la traduction (P165 "incorporates (is incorporated in); inclut (est inclus dans)").|
|P46|is composed of (forms part of)|est composé de (fait partie de)|`P46_est_composé_de (fait_partie_de)`<br>Cette formulation est cohérente avec le reste de la traduction (P5 "consists of (forms part of); consiste en (fait partie de)").<br>Cette formulation est cohérente avec le reste de la traduction (P45 "consists of (is incorporated in); comprend (est inclus dans)").|
|P48|has preferred identifier (is preferred identifier of)|a pour identifiant préférentiel (est l’identifiant préférentiel de)|`P48_a_pour_identifiant_préférentiel (est_l’identifiant_préférentiel_de)`|
|P49|has former or current keeper (is former or current keeper of)|a pour actant détenteur actuel ou antérieur (est l’actant détenteur actuel ou antérieur de)|`P49_a_pour_actant_détenteur_actuel_ou_antérieur (est_l’actant_détenteur_actuel_ou_antérieur_de)`<br>L'utilisation du terme détenteur semble préférable dans la mesure où il reconnaît à la fois la responsabilité légale ainsi que la détention de l'objet, ce à quoi le terme "keeper" fait allusion (en plus de la définition qui parle de "custody" et non pas de "responsibility"|
|P50|has current keeper (is current keeper of)|a pour actant détenteur actuel (est l’actant détenteur actuel de)|`P50_a_pour_actant_détenteur_actuel (est_l’actant_détenteur_actuel_de)`<br>L'utilisation du terme détenteur semble préférable dans la mesure où il reconnaît à la fois la responsabilité légale ainsi que la détention de l'objet, ce à quoi le terme "keeper" fait allusion (en plus de la définition qui parle de "custody" et non pas de "responsibility"|
|P51|has former or current owner (is former or current owner of)|a pour propriétaire actuel ou antérieur (est l’actant propriétaire actuel ou antérieur de)|`P51_a_pour_propriétaire_actuel_ou_antérieur (est_l’actant_propriétaire_actuel_ou_antérieur_de)`|
|P52|has current owner (is current owner of)|a pour propriétaire actuel (est l’actant propriétaire actuel de)|`P52_a_pour_propriétaire_actuel (est_l’actant_propriétaire_actuel_de)`|
|P53|has former or current location (is former or current location of)|a pour localisation actuelle ou antérieure (est la localisation actuelle ou antérieure de)|`P53_a_pour_localisation_actuelle_ou_antérieure (est_la_localisation_actuelle_ou_antérieure_de)`|
|P54|has current permanent location (is current permanent location of)|a actuellement pour localisation fixe (est actuellement la localisation fixe de)|`P54_a_actuellement_pour_localisation_fixe (est_actuellement_la_localisation_fixe_de)`<br>Lorsqu'il s'agit d'une adresse/d'un emplacement, l'usage de "fixe" plutôt que "permanent" est recommandé car il fait référence à l'état durable de l'emplacement plutôt qu'à son caractère durable.|
|P55|has current location (currently holds)|a actuellement pour localisation (est actuellement la localisation de)|`P55_a_actuellement_pour_localisation (est_actuellement_la_localisation_de)`|
|P56|bears feature (is found on)|a pour caractéristique (se trouve sur)|`P56_a_pour_caractéristique (se_trouve_sur)`<br>L'utilisation d'une formulation cohérente entre P56, P57, P59, etc. semble appropriée.|
|P57|has number of parts|a pour nombre d'éléments|`P57_a_pour_nombre_d’éléments`<br>L'utilisation d'une formulation cohérente entre P56, P57, P59, etc. semble appropriée. Puisque la propriété fait référence à des parties distinctes, il apparaît justifié de parler d'éléments.|
|P59|has section (is located on or within)|a pour section (se situe sur ou dans)|`P59_a_pour_section (se_situe_sur_ou_dans)`<br>L'utilisation d'une formulation cohérente entre P56, P57, P59, etc. semble appropriée.|
|P62|depicts (is depicted by)|illustre (est illustré par)|`P62_illustre (est_illustré_par)`<br>Le terme figurer dans le sens de l'illustration est limité aux œuvres d'art alors que la définition est plus large.<br>P62.1_mode_d'illustration dans intro.|
|P65|shows visual item (is shown by)|représente l'entité visuelle (est représenté par)|`P65_représente_l’entité_visuelle (est_représenté_par)`<br>Cette traduction est cohérente avec celle de E36 Entité Visuelle.<br>Le terme représenté est préférable au terme présenter dans la mesure où aucune des deux entités actantes n'a d'intentionnalité.|
|P67|refers to (is referred to by)|renvoie à (fait l'objet d'un renvoi par)|`P67_renvoie_à (fait_l’objet_d’un_renvoi_par)`|
|P68|foresees use of (use foreseen by)|prévoit l'usage de (usage prévu de)|`P68_prévoit_l’usage_de (usage_prévu_de)`<br>Cette formulation est cohérente avec le reste de la traduction (P19, P68).|
|P69|has association with (is associated with)|est associé à|`P69_est_associé_à`|
|P70|documents (is documented in)|documente (est documenté dans)|`P70_documente (est_documenté_dans)`|
|P71|lists (is listed in)|énumère (est énuméré par)|`P71_énumère (est_énuméré_par)`|
|P72|has language (is language of)|a pour langue (est la langue de)|`P72_a_pour_langue (est_la_langue_de)`|
|P73|has translation (is translation of)|a pour traduction (est traduction de)|`P73_a_pour_traduction (est_traduction_de)`|
|P74|has current or former residence (is current or former residence of)|a pour résidence actuelle ou antérieure (est la résidence actuelle ou antérieure de)|`P74_a_pour_résidence_actuelle_ou_antérieure (est_la_résidence_actuelle_ou_antérieure_de)`|
|P75|possesses (is possessed by)|possède (est possédé par)|`P75_possède (est_possédé_par)`|
|P76|has contact point (provides access to)|a pour coordonnées (permet de contacter)|`P76_a_pour_coordonnées (permet_de_contacter)`|
|P79|beginning is qualified by|a son début qualifié par|`P79_a_son_début_qualifié_par`|
|P80|end is qualified by|a sa fin qualifiée par|`P80_a_sa_fin_qualifiée_par`|
|P81|ongoing throughout|a couvert|`P81_a_couvert`|
|P82|at some time within|a eu lieu durant|`P82_a_eu_lieu_durant`|
|P86|falls within (contains)|s’insère dans (contient)|`P86_s’insère_dans (contient)`|
|P89|falls within (contains)|s’insère dans (contient)|`P89_s’insère_dans (contient)`|
|P90|has value|a pour valeur|`P90_a_pour_valeur`|
|P91|has unit (is unit of)|a pour unité de mesure (est l’unité de mesure de)|`P91_a_pour_unité_de_mesure (est_l’unité_de_mesure_de)`<br>L'utilisation du terme unité sans qualificatif peut faire allusion à un élément unitaire d'un tout (p. ex. une dimension de 30 cm a trois unités de 10 cm).|
|P92|brought into existence (was brought into existence by)|a fait exister (a commencé à exister par)|`P92_a_fait_exister (a_commencé_à_exister_par)`|
|P93|took out of existence (was taken out of existence by)|a mis fin à l'existence de (a cessé d'exister par)|`P93_a_mis_fin_à_l’existence_de (a_cessé_d’exister_par)`|
|P94|has created (was created by)|a créé (a été créé par)|`P94_a_créé (a_été_créé_par)`|
|P95|has formed (was formed by)|a fondé (a été fondé par)|`P95_a_fondé (a_été_fondé_par)`|
|P96|by mother (gave birth)|de mère (a donné naissance à)|`P96_de_mère (a_donné_naissance_à)`|
|P97|from father (was father for)|de père (a été le père pour)|`P97_de_père (a_été_le_père_pour)`|
|P98|brought into life (was born)|a donné vie à (est né)|`P98_a_donné_vie_à (est_né)`|
|P99|dissolved (was dissolved by)|a dissous (a été dissous par)|`P99_a_dissous (a_été_dissous_par)`|
|P100|was death of (died in)|a été la mort de (est mort par)|`P100_a_été_la_mort_de (est_mort_par)`|
|P101|had as general use (was use of)|a eu pour usage général (a été l'usage général de)|`P101_a_eu_pour_usage_général (a_été_l’usage_général_de)`<br>L'utilisation d'usage est cohérente avec le reste de la traduction.|
|P102|has title (is title of)|a pour titre (est le titre de)|`P102_a_pour_titre (est_le_titre_de)`|
|P103|was intended for (was intention of)|a eu pour raison d'être (a été la raison d'être de)|`P103_a_eu_pour_raison_d’être (a_été_la_raison_d’être_de)`|
|P104|is subject to (applies to)|est soumis à (s’applique à)|`P104_est_soumis_à (s’applique_à)`|
|P105|right held by (has right on)|droit détenu par (détient le droit sur)|`P105_droit_détenu_par (détient_le_droit_sur)`|
|P106|is composed of (forms part of)|est composé de (fait partie de)|`P106_est_composé_de (fait_partie_de)`|
|P107|has current or former member (is current or former member of)|a pour membre actuel ou antérieur (est le membre actuel ou antérieur de)|`P107_a_pour_membre_actuel_ou_antérieur (est_le_membre_actuel_ou_antérieur_de)`|
|P108|has produced (was produced by)|a produit (a été produit par)|`P108_a_produit (a_été_produit_par)`|
|P109|has current or former curator (is current or former curator of)|P109 a pour actant en charge de la collection actuellement ou antérieurement (est actuellement ou antérieurement en charge de la collection de)|`P109_a_pour_actant_en_charge_de_la_collection_actuellement_ou_antérieurement (est_actuellement_ou_antérieurement_en_charge_de_la_collection_de)`|
|P110|augmented (was augmented by)|a augmenté (a été augmenté par)|`P110_a_augmenté (a_été_augmenté_par)`|
|P111|added (was added by)|a ajouté (a été ajouté par)|`P111_a_ajouté (a_été_ajouté_par)`|
|P112|diminished (was diminished by)|a diminué (a été diminué par)|`P112_a_diminué (a_été_diminué_par)`|
|P113|removed (was removed by)|a retiré (a été retiré par)|`P113_a_retiré (a_été_retiré_par)`<br>Cette formulation est cohérente avec la traduction de E80 Retrait d'Élément.|
|P121|overlaps with|se superpose partiellement à|`P121_se_superpose_partiellement_à`<br>Il semble préférable de ne pas utiliser "recouvrir" qui implique qu'une entité est appliquée sur l'autre qu'elle couvre entièrement.|
|P122|borders with|est limitrophe de|`P122_est_limitrophe_de`|
|P123|resulted in (resulted from)|a eu pour résultat (a résulté de)|`P123_a_eu_pour_résultat (a_résulté_de)`|
|P124|transformed (was transformed by)|a transformé (a été transformé par)|`P124_a_transformé (a_été_transformé_par)`|
|P125|used object of type (was type of object used in)|a mobilisé l'objet du type (a été le type d’objet employé pour)|`P125_a_mobilisé_l'objet_du_type (a_été_le_type_d’objet_employé_pour)`|
|P126|employed (was employed in)|a employé (a été employé dans)|`P126_a_employé (a_été_employé_dans)`|
|P127|has broader term (has narrower term)|a pour terme général (a pour terme spécifique)|`P127_a_pour_terme_général (a_pour_terme_spécifique)`|
|P128|carries (is carried by)|est le support de (a pour support)|`P128_est_le_support_de (a_pour_support)`|
|P129|is about (is subject of)|a pour sujet (est le sujet de)|`P129_a_pour_sujet (est_le_sujet_de)`|
|P130|shows features of (features are also found on)|présente les caractéristiques de (a les caractéristiques aussi présentes sur)|`P130_présente_les_caractéristiques de (a_les_caractéristiques_aussi_présentes_sur)`|
|P132|spatiotemporally overlaps with|se superpose spatio-temporellement et partiellement|`P132_se_superpose_spatio-temporellement_et_partiellement`<br>Il semble préférable de ne pas utiliser "recouvrir" qui implique qu'une entité est appliquée sur l'autre qu'elle couvre entièrement.|
|P133|is spatiotemporally separated from|est distinct spatio-temporellement de|`P133_est_distinct_spatio-temporellement_de`<br>Le terme "separated" ici semble faire référence à l'état d'un ensemble et non au fait de le disjoindre, il semble donc préférable d'utiliser distinct.|
|P134|continued (was continued by)|a continué (a été continué par)|`P134_a_continué (a_été_continué_par)`|
|P135|created type (was created by)|a créé le type (a été créé par)|`P135_a_créé_le_type (a_été_créé_par)`|
|P136|was based on (supported type creation)|a été fondé sur (a fondé la création du type)|`P136_a_été_fondé_sur (a_fondé_la_création_du_type)`|
|P137|exemplifies (is exemplified by)|exemplifie (est exemplifié par)|`P137_exemplifie (est_exemplifié_par)`|
|P138|represents (has representation)|représente (est représenté par)|`P138_représente (est_représenté_par)`|
|P139|has alternative form|a pour forme alternative|`P139_a_pour_forme_alternative`|
|P140|assigned attribute to (was attributed by)|a assigné l’attribut à (a reçu l’attribut par)|`P140_a_assigné_l’attribut_à (a_reçu_l’attribut_par)`|
|P141|assigned (was assigned by)|a assigné (a été assigné par)|`P141_a_assigné (a_été_assigné_par)`|
|P142|used constituent (was used in)|a mobilisé comme élément (a été mobilisé dans)|`P142_a_mobilisé_comme_élément (a_été_mobilisé_dans)`|
|P143|joined (was joined by)|a fait adhérer (a adhéré par)|`P143_a_fait_adhérer (a_adhéré_par)`<br>Cette formulation est cohérente avec E85 Adhésion.|
|P144|joined with (gained member by)|a fait adhérer à (a accueilli le membre par)|`P144_a_fait_adhérer_à (a_accueilli_le_membre_par)`|
|P145|separated (left by)|a dissocié (est dissocié par)|`P145_a_dissocié (est_dissocié_par)`|
|P146|separated from (lost member by)|a dissocié de (a perdu le membre par)|`P146_a_dissocié_de (a_perdu_le_membre_par)`|
|P147|curated (was curated by)|a géré (a été géré par)|`P147_a_géré (a_été_géré_par)`|
|P148|has component (is component of)|a pour composant (est le composant de)|`P148_a_pour_composant (est_le_composant_de)`<br>Cette formulation est cohérente avec P106 est composé de, etc.|
|P150|defines typical parts of (defines typical wholes for)|définit les éléments typiques de (définit l'ensemble typique pour)|`P150_définit_les_éléments_typiques_de (définit_l’ensemble_typique_pour)`|
|P151|was formed from (participated in)|a été formé à partir de (a participé à)|`P151_a_été_formé_à_partir_de (a_participé_à)`|
|P152|has parent (is parent of)|a pour parent (est le parent de)|`P152_a_pour_parent (est_le_parent_de)`|
|P156|occupies (is occupied by)|occupe (est occupé par)|`P156_occupe (est_occupé_par)`|
|P157|is at rest relative to (provides reference space for)|est à l'arrêt par rapport à (procure l’espace de référence pour)|`P157_est_à_l’arrêt_par_rapport_à (procure_l’espace_de_référence_pour)`|
|P160|has temporal projection (is temporal projection of)|a pour projection temporelle (est la projection temporelle de)|`P160_a_pour_projection_temporelle (est_la_projection_temporelle_de)`|
|P161|has spatial projection (is spatial projection of)|a pour projection spatiale (est la projection spatiale de)|`P161_a_pour_projection_spatiale (est_la_projection_spatiale_de)`|
|P164|is temporally specified by (temporally specifies) |est temporellement spécifié par (était l'intervalle temporel de)|`P164_est_temporellement_spécifié_par (était_l’intervalle_temporel_de)`|
|P165|incorporates (is incorporated in)|inclut (est inclus dans)|`P165_inclut (est_inclus_dans)`<br>Cette formulation est cohérente avec la traduction de P5, P45, P86, P89.|
|P166|was a presence of (had presence)|a été une présence de (a eu pour présence)|`P166_a_été_une_présence_de (a_eu_pour_présence)`<br>Cette formulation est cohérente avec la traduction de P195.|
|P167|was within (includes)|s’inscrivait dans (comporte)|`P167_s’inscrivait_dans (comporte)`|
|P168|place is defined by (defines place)|lieu défini par (définit le lieu)|`P168_lieu_défini_par (définit_le_lieu)`|
|P169|defines spacetime volume (spacetime volume is defined by)|volume spatio-temporel défini par (définit le volume spatio-temporel)|`P169_volume_spatio-temporel_défini_par (définit_le_volume_spatio-temporel)`|
|P170|defines time (time is defined by)|temps défini par (définit le temps)|`P170_temps_défini_par (définit_le_temps)`|
|P171|at some place within|a eu lieu quelque part dans|`P171_a_eu_lieu_quelque_part_dans`|
|P172|contains|contient|`P172_contient`|
|P173|starts before or with the end of (ends after or with the start of)|commence avant ou au moment de la fin de (se termine après ou au moment du début de)|`P173_commence_avant_ou_au_moment_de_la_fin_de (se_termine_après_ou_au_moment_du_début_de)`|
|P174|starts before the end of (ends after the start of)|commence avant la fin de (se termine après le début de)|`P174_commence_avant_la_fin_de (se_termine_après_le_début_de)`|
|P175|starts before or with the start of (starts after or with the start of)|commence avant ou au moment du début de (commence après ou au moment du début de)|`P175_commence_avant_ou_au_moment_du_début_de (commence_après_ou_au_moment_du_début_de)`|
|P176|starts before the start of (starts after the start of)|commence avant le début de (commence après le début de)|`P176_commence_avant_le_début_de (commence_après_le_début_de)`|
|P177|assigned property of type (is type of property assigned)|a assigné le type de propriété (est le type de la propriété assigné)|`P177_a_assigné_le_type_de_propriété (est le type de la propriété assigné)`|
|P179|had sales price (was sales price of)|a eu pour prix de vente (a été le prix de vente de)|`P179_a_eu_pour_prix_de_vente (a_été_le_prix_de_vente_de)`|
|P180|has currency (was currency of)|a pour monnaie (était la monnaie de)|`P180_a_pour_monnaie (était_la_monnaie_de)`|
|P181|has amount|a pour quantité|`P181_a_pour_quantité`|
|P182|ends before or with the start of (starts after or with the end of)|se termine avant ou au moment du début de (commence après ou au moment de la fin de)|`P182_se_termine_avant_ou_au_moment_du_début_de (commence_après_ou_au_moment_de_la_fin_de)`|
|P183|ends before the start of (starts after the end of)|se termine avant le début de (commence après la fin de)|`P183_se_termine_avant_le_début_de (commence_après_la_fin_de)`|
|P184|ends before or with the end of (ends with or after the end of)|se termine avant ou au moment de la fin de (se termine au moment de ou après la fin de)|`P184_se_termine_avant_ou_au_moment_de_la_fin_de (se_termine_au_moment_ou_après_la_fin_de)`|
|P185|ends before the end of (ends after the end of)|se termine avant la fin de (se termine après la fin de)|`P185_se_termine_avant_la_fin_de (se_termine_après_la_fin_de)`|
|P186|produced thing of product type (is produced by)|a produit la chose du type (est produit par)|`P186_a_produit_la_chose_du_type (est_produit_par)`|
|P187|has production plan (is production plan for)|a pour plan de production (est le plan de production de)|`P187_a_pour_plan_de_production (est_le_plan_de_production_de)`|
|P188|requires production tool (is production tool for)|nécessite l'outil (est l'outil de production de)|`P188_nécessite_l’outil (est_l’outil_de_production_de)`|
|P189|approximates (is approximated by)|approxime (est approximé par)|`P189_approxime (est_approximé_par)`|
|P190|has symbolic content|a pour contenu symbolique|`P190_a_pour_contenu_symbolique`|
|P191|had duration (was duration of)|a eu pour durée (était la durée de)|`P191_a_eu_pour_durée (était_la_durée_de)`|
|P195|was a presence of (had presence)|a été une présence de (a eu pour présence)|`P195_a_été_une_présence_de (a_eu_pour_présence)`<br>Cette formulation est cohérente avec P166.|
|P196|defines (is defined by)|définit (est défini par)|`P196_définit (est_défini_par)`|
|P197|covered parts of (was partially covered by)|a couvert des parties de (a été partiellement couvert par)|`P197_a_couvert_des_parties_de (a_été_partiellement_couvert_par)`<br>Ici le terme "parts" ne fait pas référence à des éléments (contrairement à P57 et P150), mais à une portion, ou partie, couverte.|
|P198|holds or supports (is held or supported by)|contient ou soutient (est détenu ou soutenu par)|`P198_contient_ou_soutient (est_contenu_ou_soutenu_par)`<br>"Contient" est le terme le plus approprié car cette propriété s’applique à des objets qui renferment quelque chose.|
|PC0|Typed CRM Property|Propriété CRM typée|`PC0_Propriété_CRM_typée`|
|P01|has domain (is domain of)|a pour domaine (est le domaine de)|`P01_a_pour_domaine (est_le_domaine_de)`|
|P02|has range (is range of)|a pour portée (est la portée de)|`P02_a_pour_portée (est_la_portée_de)`|
|P03|has range literal|a pour portée littérale|`P03_a_pour_portée_littérale`|
|PC3|has note|a pour note|`PC3_a_pour_note`|
|P3.1|has type|a pour type|`P3.1_a_pour_type`|
|PC14|carried out by|a été effectué par|`PC14_a_été_effectué_par`|
|P14.1|in the role of|dans le rôle de|`P14.1_dans_le_rôle_de`|
|PC16|used specific object|a mobilisé l'objet spécifique (a été mobilisé pour)|`PC16_a_mobilisé_l’objet_spécifique (a_été_mobilisé_pour)`|
|P16.1|mode of use|mode d'utilisation|`P16.1_mode_d’utilisation`|
|PC19|was intended use of|était l'usage prévu de (a été élaboré pour)|`PC19_était_l’usage_prévu_de (a_été_élaboré_pour)`|
|P19.1|mode of use|mode d'utilisation|`P19.1_mode_d’utilisation`|
|PC62|depicts|illustre|`PC62_illustre`|
|P62.1|mode of depiction|mode d'illustration|`P62.1_mode_d’illustration`|
|PC67|refers to|renvoie à|`PC67_renvoie_à`|
|P67.1|has type|a pour type|`P67.1_a_pour_type`|
|PC69|is associated with|est associé à|`PC69_est_associé_à`|
|P69.1|has type|a pour type|`P69.1_a_pour_type`|
|PC102|has title|a pour titre|`PC102_a_pour_titre`|
|P102.1|has type|a pour type|`P102.1_a_pour_type`|
|PC107|has current or former member|a pour membre actuel ou antérieur (est le membre actuel ou antérieur de)|`PC107_a_pour_membre_actuel_ou_antérieur (est_le_membre_actuel_ou_antérieur_de)`|
|P107.1|kind of member|sorte de membre|`P107.1_sorte_de_membre`|
|PC130|shows features of|présente les caractéristiques de|`PC130_présente_les_caractéristiques_de`|
|P130.1|kind of similarity|sorte de similarité|`P130.1_sorte_de_similarité`|
|PC136|was based on|était basé sur|`PC136_était_basé_sur`|
|P136.1|in the taxonomic role|dans le rôle taxonomique de|`P136.1_dans_le_rôle_taxonomique_de`|
|PC137|exemplifies|exemplifie|`PC137_exemplifie`|
|P137.1|in the taxonomic role|dans le rôle taxonomique de|`P137.1_dans_le_rôle_taxonomique_de`|
|PC138|represents|représente|`PC138_représente`|
|P138.1|mode of representation|mode de représentation|`P138.1_mode_de_représentation`|
|PC139|has alternative form|a pour forme alternative|`PC139_a_pour_forme_alternative`|
|P139.1|has type|a pour type|`P139.1_a_pour_type`|
|PC144|joined with|a fait adhérer à|`PC144_a_fait_adhérer_à`|
|P144.1|kind of member|sorte de membre|`P144.1_sorte_de_membre`|
