# **Géovisualisation de Alexia Rousseau, juin 2026**
## **Les fours banals (Entremont et vallée du Trient)**
### 1. Contexte du projet

Ce projet s'inscrit dans le cadre du cours Géovisualisation et traitement de l'information de Christian Kaiser (Université de Lausanne). L'objectif est de créer une visualisation, tout en intégrant les notions et concepts abordés durant les séances. Au fil de ce document de présentation, ces acquis théoriques permettront de nourrir la discussion et la justification des différents choix (représentation, interactivité, communication graphique, efficacité, facilité d'utilisation...)

Ce projet s'inscrit également dans le cours de Projet tutoré de Laine Chanteloup et Emmanuel Reynard. Mon équipe et moi avons été mandatés afin d'effectuer un inventaire et un projet de valorisation des fours banals dans la région de l'Entremont et de la vallée du Trient. Ainsi, la présente visualisation est créée en guise de support au projet de valorisation. 

#### 1.1 Objectifs de la visualisation

La visualisation a pour **premier objectif** de partager l'histoire des fours banals (FB). C'est d'abord une visée communicationnelle qui propulse ce projet. Cette histoire est par ailleurs partagée par le biais des informations recueillies lors des 29 entretiens effectués avec les associations et consortages qui gèrent les fours banals de la région.

Un **second objectif** de ce projet est de créer du lien entre les fours banals. Il a été mentionné que l'histoire des fours, se trouvant parfois à seulement quelques kilomètres, étaient inconnues. Ainsi, ce projet a pour objectif de communiquer des informations historiques sur les fours. 

#### 1.1.1 Questions 

Ainsi, la visualisation tente de répondre aux questions suivantes :
- Qu'est-ce qu'un four banal ?
- Quelle est l'implication historique des fours banals dans l'Entremont et la vallée du Trient ?
- Quelles sont les principales tendances d'évolution des fours banals dans l'Entremont et la vallée du Trient ?
- Quelles sont les pratiques actuelles des fours banals dans l'Entremont et la vallée du Trient ?

#### 1.2 Importance de cette visualisation







#### 1.3 Définition du public cible

La définition du public cible est essentielle afin d'affiner la visualisation. De façon plus large, le public cible comprend des gens qui s'intéressent au four banal (membres d'associations, consortages), des gens qui veulent en apprendre sur les pratiques (nouvel·le habitant·e de la région), des historien·ne·s s'intéressant au patrimoine. 

Ce public cible n'est pas nécessairement à l'aise avec l'informatique. Ainsi, la visée communicationnelle, et non exploratoire, est mise de l'avant. 

Les tableaux suivants présentent les personas, en vue de la théorie et de l'exemple des personas abordés lors de la séance du 25.03.

**Personas 1 : Jean (65 ans), retraité, peu de connaissance en informatique** 
| **Caractéristiques** | **Objectifs** | **Attentes** |
|:-------|:-------|:-------|
|Résident du village des Marécottes depuis qu'il est né  | Connaître ce qui est fait au four à pain du village du Trétien  | Informations historiques sur les fours|
| Membre de l'association des amies du four à pain de la Lenaire  | Partager des informations avec ses proches non connaisseurs des FB |Plateforme simple d'usage, lisible et ludique |

**Personas 2 : Louise (29 ans), professeure à Martigny, bonne connaissance en informatique**
|**Caractéristiques** |**Objectifs** |**Attentes** |
|:-------|:-------|:-------|
|Habite en Valais depuis 5 ans  | Connaître l'histoire des fours banals de la région | Informations historiques sur les fours|
|Intéressée par le patrimoine alimentaire valaisan  | Organiser une excursion avec ses élèves afin de visiter un four banal | Contenu vulgarisé et présence d'images |

**Personas 3 : Nelly (55 ans), historienne, bonne connaissance en informatique**
|**Caractéristiques**|**Objectifs**|**Attentes**|
|:-------|:-------|:-------|
|Habite en Valais depuis 10 ans | S'intéresse à la gouvernance des fours | Localisation précise des fours |
|Spécialiste du patrimoine valaisan  | Informations historiques afin de rédiger un article sur le patrimoine alimentaire | Présence d'image de qualité |

**Personas 4 : Julian (34 ans), travailleur saisonnier, bonne connaissance en informatique**
| **Caractéristiques** | **Objectifs** | **Attentes** |
|:-------|:-------|:-------|
|Habite en Valais depuis 1 ans |En apprendre sur les fours banals|Visualisation mémorable et compréhensible|
|Curieux de s'imprégner de la culture de son domicile  | Comprendre l'importance des fours dans l'histoire du village |Informations sur la participation |

### 2. Planification et réflexion sur la visualisation

Cette section comprend des réflexions faites au préalable et durant la création de la visualisation, concernant la sémiologie, l'interaction, la communication graphique...

#### 2.1 Réflexions théoriques 

Selon le cube de la géovisualisation (MacEachren, 1994), mon projet se situe vers les extrémités de chaque axe (figure 1). Les différents axes seront expliqués en détail:
- Task: dans ce cas, la visualisation a une visée de communication, et non d'exploration. Le public cible n'est pas nécessairement à l'aise avec l'exploration, et le but est plutôt de communiquer une histoire. 
- Domain: la visualisation s'inscrit dans une présentation de données connues. Elle ne permet pas la révélation de données inconnues. Ainsi, elle se situe vers la gauche de l'axe Domain.
- Human-map interaction: l'interaction avec la visualisation est faible, mais pas absente. Le format Storymaps permet la présentation d'image cliquable et le déroulement de l'information vers le bas. Ainsi, il est possible de se déplacer à même la visualisation. En lien avec le public cible, cette faible interaction est pertinente, puisque le public n'est pas nécessairement connaisseur en informatique. En revanche, l'information et les images présentent seront possiblement téléchargeables pour le public intéressé.
- Collaboration context: Le public ciblé, comme décrit plus haut, comprend différents profils, tous non experts. Ainsi, sur l'axe vertical, la visualisation se situe plutôt vers le haut.

<div align="center">
<img src="images/theorie/cube_geovis.png" width="500" />
**Figure 1 : Cube de la géovisualisaton**
</div>

La visualisation a pour but d'être un projet de communication, facile à lire et ludique. Le public se retrouvant sur la page, bien qu'intéressée, doit se faire attraper par la visualisation et souhaiter en apprendre davantage. Ainsi, l'esthétisme est important. De plus, afin d'attirer l'oeil, les couleurs sont importantes. Pour capter l'attention du lecteur, je souhaite également choisir minutieusement les informations à partager, en essayant d'avoir un minimum de diversité, tout en gardant une structure compréhensible. 

Dans ce sens, la lisibilité et l'accessibilité sont tout autant importantes. Comme cette visualisation sera partagée et promue lors d'une exposition, il est important qu'elle soit facilement visualisable sur un téléphone. Durant le processus de création de la Storymaps, il y a la possibilité de la visualiser sur téléphone (portrait et paysage). La visualisation doit également être lisible et intéressante en format web. Enfin, les tâches que l'utilisateur·ice doit accomplir (lecture, visualisation de photos) doivent être facile à accomplir. Il ne devrait pas y avoir besoin d'indications (ou peu).  

Le choix de la visualisation à l'aide d'une Storymaps est venu instinctivement dans l'optique où je souhaitais raconter une histoire et partager de l'information. La forme souhaitée de type récit ou livret de communication se transpose bien sûr la Storymaps. Cette fonctionnalité de ArcGIS permet de créer un récit numérique, en intégrant des cartes et images. D'autres fonctionnalités sont possibles, mais pour ce projet je me concentrerai sur ces deux options. En revanche, il est important de noter que les fonctionnalités de Storymaps sont restreintes. 


#### 2.2 Réflexions pratiques


Ainsi, les éléments historiques à intégrer dans la visualisation seraient :


<div align="center">


| **À intégrer** | **Question** | **Objectif**|
|:-------|:-------|:-------|
|Définition d'un four banal |1| 1|
|Importance historique | 2 | 1|
|Carte avec localisation des fours| Élément de contexte| 1|


</div>



Puis, en fonction des fours choisis, intégrer des informations précises sur ceux-ci : 


<div align="center">


| **À intégrer** | **Question** |  **Objectif**|
|:-------|:-------|:-------|
|Nom du four et emplacement |Éléments de contexte |2|
|Description des pratiques| 4 |2|
|Évolution du four| 4 |1 et 2|


</div>


### 3. Réflexions et processus de création


#### 3.1 Réflexions sur la visualisation en StoryMaps


Ma réflexion a évolué quant à l'intégration d'une carte de l'emplacement des fours. Au départ, j'ai cru bon d'insérer une carte avec l'emplacement de chacun des fours avec lesquels l'équipe s'est entretenue (voir figure 3). J'ai créé une carte dans Express Map (carte en ligne, créer à même la StoryMaps). Par contre, les options sont limitées : 
- la légende n'apparait pas directement quand tu défiles sur la carte (elle est cachée dans le coin en bas et on doit cliquer), 
- il n'y a pas la possibilité de cliquer sur un four et ça mène directement au four plus bas


<div align="center">
<img src="images/theorie/carte.png" width="500" />


**Figure 3 : Carte créée dans Express Map (ArcGIS)**
</div>


Comme abordé ci-dessus, les premières idées d'éléments à intégrer ont été le texte et les images. Parmi les images, j'ai songé à créer des frises chronologiques pour suivre l'évolution d'un four à pain précis (figure 4). Cette ligne du temps comprend les périodes en fonction et les périodes d'arrêt du four à pain, tout en intégrant les grands évènements tels que les rénovations. 


<div align="center">
<img src="images/frise/marecotte2.png" width="500" />


**Figure 4 : Exemple de frise chronologique**


</div>


En revanche, cette frise chronologique vient scinder l'enchainement naturel et intéressant de la Storymaps, en ajouter une lecture d'élément temporel horizontale dans le déroulement vertical. Ainsi, bien que j'avais déjà créé trois frises chronologiques, je ne sais toujours pas si je vais intégrer ces informations de cette façon.



#### 3.2 Réflexions sur la visualisation en HTML


J'avais commencé ma StoryMaps (prototype) en prenant des bribes de fichiers à gauche et à droite. Par contre, en créant ce document synthèse, j'ai rapidement réalisé qu'il serait préférable d'avoir un fichier de texte avec tous les éléments que je souhaite intégrer. Ainsi, le fichier [infos](infos) comprend les éléments de texte à intégrer dans ma visualisation, en fonction des tableaux définis en section 2.2.


J'ai essayé de penser à une autre façon de partager l'information. Afin de tester autre chose, j'ai demandé à Claude.IA de créer un code avec la requête : "Je veux un code en HTML qui donne une page comme l'image (images/claude/demande_essai_html). Le but est d'avoir un titre, suivi de deux zones de texte, suivi d'un espace pour insérer des images (3 images une à côté de l'autre). Je veux pouvoir cliquer sur l'image, et qu'il y aille un pop-up qui apparaisse (et je puisse écrire une info)". Ensuite, d'autres requêtes ont suivi afin de peaufiner cette idée (je veux ajouter au-dessus de chacune des images un titre, centré sur l'image).


Dans la suite de ce document et afin de mieux comprendre ce dont il est question (géographiquement), j'ai songé à ajouter une carte au départ, avec des éléments cliquables qui mènent à la commune précise. Ainsi, la requête : "Est-il possible, au début, d'insérer une carte avec des points cliquables ? Et ces points pourraient référer aux différentes sections plus bas dans le document ?" a été demandé à ClaudeIA. Sa réponse a suggéré l'intégration d'une carte statique, avec l'ajout de point. Ainsi, la question est désormais de trouver une carte assez précise pour situé l'utilisateur·ice, tout en ne le surchargeant pas d'informations.


Afin de classer les fours par communes, j'ai demandé à Claude.IA un code : je veux un code qui ressemble au code pour les images cliquables (ci-dessus). J'ai besoin de : un code qui inclut 12 images (4 lignes de 3 images), un code de 9 images (3 lignes de 3 images),un code de 4 images (2 lignes de 2 images - centré) et un code de 1 image (centré). Le code ne donnait pas les images que je souhaitais, j'ai redemandé un code avec 4 lignes, 3 images par lignes. En ajoutant les images, j'ai réalisé que pour la commune d'Orsières, il y avait 11 fours (et non 12). J'ai demandé à Claude : "dans la section ORSIÈRES, je veux enlever le titre 12 (il n'y en a pas). Les deux autres images de cette ligne doivent être centrées." La même manipulation a été demandée pour Bagnes (8 fours au lieu de 9). De plus, j'ai demandé à Claude : "Est-ce possible dans le style de faire que les images sont toutes du même format ? Format 3:2." Et il a ajouté une règle CSS. De plus, les règles CSS étaient différentes pour différentes sections (ajout de différents codes et styles de façon éclectiques au cours de la création de cette section). J'ai demandé à Claude d'uniformiser les styles.


Après réflexion sur la forme décrite ci-dessus, je trouvais que de seulement voir l'image et de devoir effectuer un clic (sans savoir qu'il était possible) n'était pas vraiment dans une visée d'accompagnation de l'utilisateur·ice (figure 5). Ainsi, j'ai songé à ajouter le début de mon texte directement sous l'image, qui se terminerait par ... *Lire la suite*, d'une différente couleur (bleu pâle) incitant ainsi à cliquer. De plus, afin d'intégrer des informations (en guise de réponse aux questions), je vais intégrer une section Évolution, visible lors du clic, qui comprend la frise chronologique. Actuellement, lors du clic, seul un texte apparait et il serait bon de mieux structurer cette partie afin qu'elle soit plus compréhensible (figure 6).


<div align="center">
<img src="images/claude/img_fours.png" width="300" />


**Figure 5 : Mise en forme imprécise**
</div>


<div align="center">
<img src="images/claude/img_popup.png" width="300" />


**Figure 6 : Manque de clarté dans le pop-up**
</div>


Afin de mettre en oeuvre ces changements, j'ai demandé à ClaudeIA "je veux mettre le début (2 lignes) de chacun des textes directement sous l'image (texte actuellement seulement visible au pop-up), sur la page principale. Je veux que ce texte se termine par "lire la suite...", pour inciter le public à cliquer. Tu peux faire un test avec le premier élément (La Rosière)". Le résultat était satisfaisant (figure 7), mais j'ai fait une seconde requête afin de raccourcir le texte visible (140 à 120 caractères, puis 50 caractères).


<div align="center">
<img src="images/claude/lire_la_suite.png" width="300" />


**Figure 7 : Intégration Lire la suite**
</div>


Afin de modifier le pop up, j'ai effectué la requête : "Je veux diviser le pop up en plusieurs sections. Je veux avoir les sous-titres : Pratiques actuelles et Évolution. Le texte actuel se trouverait sous le sous-titre Pratiques actuelles. Sous le sous-titre Évolution, il y aurait place à insérer une image. Tu peux faire un test avec le four de la Rosière." Le résultat était satisfaisant, mais lors de l'ouverture du pop-up, la mise en page ne permettait pas de lire toute l'information ni de défiler... J'ai essayé de mettre les images une à côté de l'autre, mais je n'aime pas mieux (lisibilité de la frise chronologique fiable). J'ai réalisé que le problème était le format de la frise. L'image n'était pas du tout cadrée correctement. Je crois qu'en la cadrant correctement, elle sera lisible dans le format vertical du pop-up. J'ai ensuite demandé à ClaudeIA d'implémenter le même format pour tous les autres fours. Enfin, je trouvais que la frise n'était toujours pas très visible, j'ai demandé à ClaudeIA qu'elle soit cliquable (pour la voir en plus grande). Et le background était noir, donc on voyait mal (car c'est un fichier sans fond - texte noir sur noir, était problématique) et j'ai modifié le fond en blanc. Ensuite, j'ai rajouté une fonction que toutes les pop ups sont du même format, et un défilement, afin d'uniformiser (avec une requête à ClaudeIA).


J'ai fait la requête à ClaudeIA "Voici un site web que j'ai créé. Pouvez-vous me faire des commentaires (contenu et format) ?". Ses réponses contenaient des améliorations quant aux entretiens (non mis en valeur), à la partie introductive (longue) et au format (pas de bouton retour en haut, historique trop long, pas de coupure avec la carte). Ainsi, ClaudeIA a créé.
1. Code (HTML et css) pour les différentes sections de la partie historique
1. Code (HTML, css et js) pour le bouton retour en haut
1. Code (html, css) pour insérer une bannière qui structure la page. 


J'ai ensuite demandé comment la carte pouvait être améliorée (comment est-ce que je pourrais améliorer cette carte pour qu'elle soit plus compréhensible ?). Ses réponses contenaient des points d'améliorations concernant la légende (absente), le contexte géographique (absent), la symbologie (incompréhensible). J'ai ensuite retravaillé la carte sur QGIS et Affinity afin de produire une carte plus structurée (figure 8).


<div align="center">
<img src="images/theorie/carte_q2.jpg" width="700" />


**Figure 8 : Évolution de la carte**
</div>


Enfin, j'ai ajouté des onglets en haut qui réfère aux communes, suite à la demande à Claude : "créer un code à intégrer qui permet d'avoir toutes les communes en haut, qui s'affiche en permanence". Cela permet de structurer et aussi de créer une structure du site, à même sa structure verticale de défilement 


### 4. Visualisation réalisée


#### 4.1 Description de la visualisation réalisée


La visualisation a d'abord été conceptualisée et réalisée sous la forme d'une StoryMaps, une fonctionnalité de ArcGIS.  
Ensuite, comme défini plus haut, le projet a été transféré en HTML. La visualisation réalisée comprendre une courte description du contexte du projet, puis défini les fours banals. Ensuite, une section concernant l'importance historique est présente, en s'intéressant à l'évolution depuis le Moyen Âge. Dans une optique de structuration du site, une image ainsi qu'une bande "statistiques" sont présentes. 


La visualisation comprend une carte statique, mais avec des clics possibles. 


La dernière partie comprend une liste de tous les fours présents. Les différentes sections représentent les communes. Ainsi, une certaine catégorisation peut être effectuée, permettant de déceler des tendances.


Chaque section comprend les différents fours actifs (allant de 1 à 11). Chaque four comprend une photo,puis une description des pratiques actuelles, suivi d'un espace pour insérer une frise. En revanche, ces sections ne sont pas complètes pour chaque four. Seulement de four banal La Rosière (Orsières) comprend la frise chronologique. 


La visualisation se lit comme une histoire, avec l'entièreté des informations sur la même page. Certes, les espaces réservés à chaque four sont cliquables, mais un X est présent afin d'être facilement refermable.


#### 4.2 Évaluation de la visualisation 


Cette présente section permet une évaluation de la visualisation. L'évaluation est effectué en fonction de la visualisation finale (si chacune des sections présentes était remplie). Par le fait qu'il reste encore quelques entretiens à effectuer et par manque de temps, la section Évolution de chaque four (frise chronologique) est incomplète, et il y a un grand manque de photos. Ces sections d'ici la fin du projet tutoré mentionné au début de ce document, seront complétés. 



#### 4.2.1 Points forts


La visualisation réalisée répond partiellement aux objectifs (1. partager l'histoire des fours banals et 2. créer du lien). En effet, la visée communicationnelle du projet est atteinte. Le site web se lit comme un livre, et le fait que toutes les informations soient sur la même page permet une fluidité. De plus, bien qu'incomplet pour l'instant, les différentes rubriques insérées dans chaque four permettent de partager les informations recueillies lors des 29 entretiens. 


Concernant les questions, la visualisation répond encore une fois partiellement.


<div align="center">


| **Question** | **Intégration** | 
|:-------|:-------|
|Qu'est-ce qu'un four banal ? |Répondue en section : Une petite définition... |
|Quel est l'implication historique des fours banals dans l'Entremont et la vallée du Trient ?| Répondue en section : Et pourquoi on en parle encore à ce jour ? |
|Quelles sont les principales tendances d'évolution des fours banals dans l'Entremont et la vallée du Trient ?| Partiellement répondue. |
|Quelles sont les pratiques actuelles des fours banals dans l'Entremont et la vallée du Trient ?| Répondue pour chaque four. |


</div>


En ce qui concerne l'efficience de la visualisation, elle est efficace. Elle permet une bonne compréhension de l'information, sans être complètement surchargée. Les titres et sous-titres aident à mettre l'emphase sur ce qui est important. Selon moi, la tâche de l'utilisateur·ice est facile à accomplir, dans le sens que le but est de connaitre l'histoire (noté au départ), puis il est possible de déroulé vers les fours précis. Bien que l'information ne soit pas mentionnée au départ, le menu horizontal avec les noms des communes permet de déduire que ces communes seront abordées. 




#### 4.2.2 Points faibles


Le second objectif, soit de créer du lien avec les fours, est partiellement atteint. Bien qu'il est possible de mieux comprendre les pratiques et l'évolution de chaque four, il n'y a pas de dispositif ou informations précises sur les contacts de chacun d'entre eux. Ainsi, la création de lien est moins atteinte.


Comme mentionné au tableau ci-dessus, la question des tendances a été partiellement répondue. En effet, bien que les tendances seront perceptibles pour chaque four (section Évolution dans le pop-up), il n'y a pas nécessairement de tendances générales. 


Une lacune concerne l'accessibilité à l'information sur les fours. Il aurait été pertinent d'ingérer l'information sans la nécessité du clic et pop-up, mais comme il y avait 29 fours à couvrir, j'ai opté pour une page plus courte, intégrant des clics.


Concernant la carte, selon MacEachren (1995), la sémiologie utilisée pour représenter a une efficacité tirant davantage vers le moyen à faible. La saturation de couleur n'est pas la plus efficace, et je ne crois pas avoir utilisé les meilleures couleurs non plus. Bien que je voulais que ce soit esthétique, je crois que j'ai passé à côté d'une façon de transmettre l'information claire. Je crois que la carte permet de comprendre quelle est la région à l'étude (les communes), mais la distinction entre les caractéristiques (fours actifs) des différentes communes est peu claire. De plus, l'ajout de point cliquable peut venir déjouer le lecteur et biaiser sa compréhension, comme la description ne se trouve pas dans la légende. L'idée de créer des points de différentes grosseurs pour représenter le nombre de fours a également été songée, puisque cela se situe haut dans l'efficacité des variables visuelles (MacEachren, 1995), mais n'a pas été réalisé par manque de temps. Cela a créé une double symbologie sur la carte (symbol map et chloropleth map - Munzner, 2014)



#### 4.2.3 Évaluation selon les personas


Afin de comprendre si la visualisation est fonctionnelle, je vais réévaluer en fonction des besoins des personas créés plus tôt. La colonne **Satisfaction** a été ajoutée.


**Personas 1 : Jean (65 ans), retraité, peu de connaissance en informatique** 
| **Caractéristiques** | **Objectifs** | **Attentes** | **Satisfaction**|
|:-------|:-------|:-------|:-------|
|Résident du village des Marécottes depuis qu'il est né  | Connaître ce qui est fait au four à pain du village du Trétien  | Informations historiques sur les fours | Introduction contextuelle satisfaisante et accessible |
| Membre de l'association des amies du four à pain de la Lenaire  | Partager des informations avec ses proches non connaisseurs des FB |Plateforme simple d'usage, lisible et ludique |Carte statique interactive difficile d'usage, lien vers la vraie carte interactive difficile à manoeuvrer|


**Personas 2 : Louise (29 ans), professeure à Martigny, bonne connaissance en informatique**
|**Caractéristiques** |**Objectifs** |**Attentes** | **Satisfaction**|
|:-------|:-------|:-------|:-------|
|Habite en Valais depuis 5 ans  | Connaître l'histoire des fours banals de la région | Informations historiques sur les fours| Informations historiques présentes|
|Intéressée par le patrimoine alimentaire valaisan  | Organiser une excursion avec ses élèves afin de visiter un four banal | Contenu vulgarisé et présence d'images | Contenu vulgarisé et accessible, mais manque d'information précise concernant les fournées (impossibilité de planifier une excursion) |


**Personas 3 : Nelly (55 ans), historienne, bonne connaissance en informatique**
|**Caractéristiques**|**Objectifs**|**Attentes**|**Satisfaction**|
|:-------|:-------|:-------|:-------|
|Habite en Valais depuis 10 ans | S'intéressent à la gouvernance des fours | Localisation précise des fours | Localisation complexe à trouver (suivre un autre lien) |
|Spécialiste du patrimoine valaisan  | Informations historiques afin de rédiger un article sur le patrimoine alimentaire | Présence d'image de qualité | Présence d'image, mais peu variée et seulement une par fours | 


**Personas 4 : Julian (34 ans), travailleur saisonnier, bonne connaissance en informatique**
| **Caractéristiques** | **Objectifs** | **Attentes** |**Satisfaction**|
|:-------|:-------|:-------|:-------|
|Habite en Valais depuis 1 ans |En apprendre sur les fours banals|Visualisation mémorable et compréhensible| Visualisation compréhensible facilement|
|Curieux de s'imprégner de la culture de son domicile  | Comprendre l'importance des fours dans l'histoire du village |Informations sur la participation |Informations sur la participation et les moments (imprécis) de fournées|


Pour conclure, les utilisateurs·ices fictifs·ves sont partiellement satisfait·es de la visualisation. Les visées communicationnelles et historiques sont présentes, mais des informations très précises sur les fours sont manquantes (quand précisément sont les fournées, qui contacter), venant diminué la satisfaction d'un public historien. De plus, les modalités et fonctionnalités de la carte, et le lien vers une seconde carte, sont difficiles d'usage. 


#### 4.3 Résultats des tests utilisateurs·ices

Une utilisatrice a testé la carte, et a relevé un point important. La section sur les différentes communes et les fours actifs est trop longue, et nécessiterait quelconque séparation afin de structuré l'histoire. Cela tend à être redondant et peut être passé au côté d'informations intéressantes. 




### 5. Discussion et conclusion


### Bibliographique


MacEachren, A. M. (1994). Visualization in Modern Cartography: Setting the Agenda. In Modern Cartography Series (Ced., pp. 1-12). (Modern Cartography Series; Vol. 2, No. C). DOI:10.1016/B978-0-08-042415-6.50008-9 


MacEachren, A. (1995). How maps work: Representation, Visualization & Design. Guildford Press.


Munzner, T. (2014). Chapter 8. Spatial Data I: Geographic Maps. Visualization Analysis and Design. A K Peters/CRC Press


### Déclaration d'intelligence artificielle


Les différentes requêtes à ClaudeIA ont été insérées tout au long du document. 
Je certifie que ce sont les seules demandes qui ont été effectuées dans le cadre de ce projet. 
Le reste des idées, textes et design sont le fruit de mon travail.




