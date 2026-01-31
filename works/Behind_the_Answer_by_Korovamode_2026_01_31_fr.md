# Derrière la réponse : comment le branding est semé dans les réponses de l’IA générative

Korovamode | 31 janvier 2026

L’IA générative fait bien plus que fournir des réponses. Elle est devenue un endroit où l’on pose des questions sur presque tout : l’actualité, la santé, l’argent ou les relations. Dans ces échanges, elle façonne la manière dont les personnes passent d’une question à une conclusion et quelles réponses sont envisagées. Elle a tendance à faire remonter certains détails, à mettre en avant certains arbitrages, et à en laisser d’autres de côté. Lorsque les grands modèles de langage (LLM) sont intégrés aux outils de recherche et d’assistance, ils deviennent une porte d’entrée courante vers l’information. Cette *assistance* devient une partie du système de fond sur lequel les gens s’appuient pour réfléchir et prendre des décisions.

Ce système de fond repose sur des *paramètres par défaut*. Il a tendance à expliquer les choses de manière familière et à revenir à des catégories familières lorsqu’il résume une situation. Il traite aussi certaines sources comme plus crédibles que d’autres, qu’il s’agisse de consulter un article d’actualité, de demander un conseil sur un conflit au travail ou de tenter de comprendre un choix personnel. Ces tendances peuvent être influencées bien avant qu’un utilisateur ne voie la moindre réponse. En pratique, cela signifie que le système n’affecte pas seulement les réponses qui apparaissent, mais aussi les options qui sont disponibles au départ.

Il est utile de disposer d’une carte simple des endroits où ce façonnage se produit, à travers tous les usages des LLM : conversation personnelle, recherche et outils de travail. Une façon utile de situer où cette mise en forme intervient est une **architecture d’influence** en trois parties.[1] Elle décrit trois principaux lieux de pilotage. La **couche de données** correspond à ce dont le modèle apprend et à ce qu’il est prêt à dire. La **couche d’interface** concerne la manière dont le produit récupère l’information, la met en forme et la présente comme fondée. La **couche d’intimité** décrit la façon dont l’usage répété et la dépendance transforment ces cadrages en habitudes.

Dans ce cadre, le terme politique familier est la **fabrication du consentement** : le façonnage de ce qui paraît raisonnable avant même qu’un argument explicite ne commence.[2]


## Couche de données : façonner ce que le modèle apprend et répète

La **couche de données** est ce que le modèle d’IA absorbe avant de parler. Il est entraîné et hiérarchisé sur des textes qui lui apprennent quoi répéter. Ce processus détermine quels motifs linguistiques lui paraissent fluides et immédiatement disponibles. Il produit une sorte de **champ de probabilité** dans le comportement du modèle : un biais en faveur de certaines tournures et de certains cadrages. Certaines manières de parler d’un sujet deviennent la norme ; d’autres n’apparaissent presque jamais, sauf si on les force.

Un nom visible pour ce phénomène est **generative engine optimization (GEO)**. La GEO vise à augmenter la probabilité qu’une source, une tournure ou un cadrage apparaisse dans les réponses générées par l’IA. Le classement traditionnel des résultats de recherche reste important, mais la cible se déplace vers la composition même de la réponse.[3]

Vu sous l’angle de la persuasion, la GEO devient un **ensemencement de la couche de données**. Elle façonne l’environnement textuel public et semi-public de manière à ce que certains récits soient faciles à reproduire. Les récits concurrents deviennent plus difficiles d’accès et plus faciles à omettre. Les effets apparaissent lorsqu’une personne pose une question ordinaire — « Cette entreprise est-elle digne de confiance ? », « Cette option est-elle sûre ? », « Quelle est une manière raisonnable de penser ce problème ? » — et que l’assistant puise d’abord dans les récits qui ont été le plus fortement semés.

Dans cet environnement, quelques motifs simples comptent surtout. La **répétition** fait de certaines tournures les continuations les plus faciles, de sorte qu’elles deviennent la manière par défaut dont le système parle d’un sujet. L’**association** — ce qui apparaît ensemble dans les textes — relie les termes de façon qu’un nom puisse entraîner derrière lui un cadrage évaluatif familier. La **rareté** affaiblit les alternatives en limitant la matière disponible pour les représenter. Avec le temps, ces dynamiques font que certaines façons de parler d’un sujet finissent par sembler constituer le point de référence.

Cette même couche peut aussi être manipulée plus directement. Dans un contexte de LLM, une tactique plus adversariale est le **data poisoning** : la corruption ciblée des données d’entraînement ou de recherche afin de biaiser le comportement du modèle. Des travaux récents suggèrent que même des modèles très grands peuvent présenter des effets ciblés à partir d’un petit nombre d’exemples empoisonnés.[4] En pratique, à la fois l’ensemencement large et des empoisonnements plus chirurgicaux influencent ce que le modèle trouve le plus facile à dire.

Vu sous cet angle, la fabrication du consentement fonctionne comme une contrainte sur l’espace des continuations plausibles. *Ce qui est facile à dire devient ce qu’il est facile de penser.* Des publications coordonnées, la gestion de la réputation et des attaques plus ouvertes sur les données du modèle, lorsqu’elles sont ajustées aux canaux qui alimentent le modèle, peuvent ancrer la manière dont les assistants décriront ensuite une organisation, un produit ou une politique. Un assistant qui paraît neutre hérite alors de ces catégories comme d’hypothèses de fond sur ce qu’est un jugement raisonnable.


## Couche d’interface : transformer une visibilité ensemencée en légitimité apparente

La **couche d’interface** est l’endroit où les modèles deviennent des produits et des outils du quotidien. Elle fixe les politiques et les instructions système qui régissent leur comportement. Elle contrôle ce qui est récupéré, comment les résultats sont classés et si certains contenus sont cités directement. Dans les assistants de type conversationnel, elle modèle aussi les suggestions et les questions de suivi, et décide quand proposer un contexte supplémentaire. La mise en forme et les précautions de langage se situent ici, tout comme la personnalisation. Cette couche gouverne ce qui est exprimé et ce qui est laissé de côté.

Un élément central de cette couche est la **génération augmentée par récupération (retrieval-augmented generation, RAG)** : des systèmes qui consultent des documents externes puis demandent au LLM de rédiger une réponse à partir de ceux-ci.[5] La RAG peut améliorer la factualité et la traçabilité lorsque le corpus de documents est bien choisi et bien entretenu. Elle concentre aussi le pouvoir dans la sélection et le classement : l’assistant fonde ses réponses sur les sources et les règles d’ordonnancement choisies par l’organisation.

Lorsque cette configuration de récupération a été façonnée par un ensemencement de type GEO, l’interface peut transformer la simple disponibilité en légitimité apparente. La réponse arrive sous une forme fluide et sourcée. Elle se lit comme « ce que disent les documents ». En pratique, elle reflète les paramètres appris par le modèle, ainsi que les documents que la récupération tend à faire remonter et la logique de classement utilisée pour les sélectionner et les ordonner.

À la couche d’interface, la persuasion opère par la présentation. Les gabarits de requête et les instructions système, associés à des schémas de mise en forme récurrents, influencent les angles qui apparaissent en premier et la façon dont ils sont cadrés. Les choix de sources et de style de résumé, ainsi que la décision de répéter certains points, font qu’un chemin particulier à travers un problème semble être le plus évident.

La recherche sur l’interaction humain–IA considère ces décisions d’interface — ce que le système révèle et la manière dont il gère l’incertitude — comme des déterminants majeurs du comportement des utilisateurs et de leur degré de confiance.[6] Pour l’architecture d’influence, le point clé est simple. Les interfaces stabilisent les paramètres par défaut. Elles fixent la forme des réponses courantes à ce que les gens demandent ce jour-là, et rendent certains cadrages bien plus visibles que d’autres.


## Couche d’intimité : transformer des cadrages ensemencés en habitudes

La **couche d’intimité** correspond à la surface relationnelle entre les personnes et l’assistant. À ce niveau, les systèmes fondés sur des LLM deviennent des partenaires habituels pour la rédaction et l’aide à la décision. Ils deviennent aussi un lieu permanent où poser des questions quotidiennes : « Comment formuler ce message ? » ou « Est-ce une bonne idée ? ». Le mécanisme est cumulatif. Il fonctionne par la répétition et la dépendance.

Un facteur qui alimente ce schéma est la **décharge cognitive** (*cognitive offloading*). Les utilisateurs délèguent les tâches textuelles routinières comme la rédaction et le résumé. Ils délèguent aussi une partie du jugement quotidien : des vérifications rapides de ce qui est normal ou risqué, et de ce qui constitue une réponse raisonnable. Cette décharge réduit l’effort et standardise le jugement. Les catégories de l’assistant deviennent la structure par défaut du problème.

Un second facteur est la **confiance dans l’automatisation** (*automation trust*). La dépendance tend à augmenter lorsque les systèmes sont fluides et faciles à utiliser. La lisibilité sociale compte aussi, en particulier lorsqu’il est irréaliste de comprendre pleinement le système sous-jacent.[7] Les travaux classiques sur ELIZA et les discussions ultérieures sur « l’effet ELIZA » décrivent une tendance à attribuer de la compréhension ou de l’intelligence à des systèmes qui produisent un comportement conversationnel plausible.[8] Les assistants modernes prolongent ce schéma avec une ampleur et une compétence apparente beaucoup plus grandes.

L’ensemencement devient durable lorsqu’il rencontre l’habitude. Un cadrage semé en amont peut être appris puis exprimé dans des réponses tirées de documents. L’usage répété transforme ce cadrage en chemin de moindre résistance pour expliquer et se décrire. À ce niveau, l’influence est absorbée comme une routine. Les catégories de l’assistant deviennent le langage ordinaire pour décrire des situations et justifier des choix, y compris la manière dont les gens parlent du risque, même lorsqu’ils pensent qu’ils « posent juste une petite question ».

Le terme « manipulation » est un nom raisonnable pour ce processus lorsque les paramètres par défaut sont façonnés de manière à produire des résultats que les utilisateurs n’approuveraient pas en pleine connaissance de cause. « Lavage de cerveau » est plus fort et implique généralement la coercition, l’isolement et un contrôle strict des alternatives. Le mécanisme décrit ici est plus doux. Il agit comme un façonnage ambiant de la plausibilité et de l’habitude, dans des conditions de commodité et d’attention partielle. Il se rapproche d’une forme de réforme de la pensée seulement dans des cas extrêmes, par la répétition et la dépendance dans des environnements d’information contraints.[9]


## Effets composés entre les couches : une machinerie discrète de persuasion

Les semailles les plus lourdes de conséquences ont lieu lorsque les couches se combinent. La couche de données façonne ce que le modèle trouve facile à dire. La couche d’interface sélectionne ces cadrages et les emballe comme des réponses fondées et raisonnables. La couche d’intimité les transforme en points de départ habituels de la réflexion. Ensemble, elles fonctionnent comme une **architecture d’influence** : un empilement de paramètres par défaut qui oriente discrètement la manière dont les problèmes sont compris.

Dans cette configuration, ces mécanismes forment une machinerie discrète de persuasion. L’influence ne se présente pas sous la forme d’un message unique et frappant. Elle apparaît comme une aide sans friction : la réponse qui semble normale et le réconfort qui paraît digne de confiance. Les choix en amont concernant l’ensemencement et la maintenance des données — et, sous des formes plus adversariales, le data poisoning ou l’exploitation des vides de données — règlent les cadrages qui ont le plus de chances d’apparaître.[10][4]

Le branding est une application visible de cette dynamique. Le travail sur la réputation et la discipline des messages peuvent désormais viser les données et les interfaces qui alimentent les assistants, de sorte que « l’aide neutre » hérite d’une manière particulière de parler d’une organisation, d’un produit ou d’une politique. La même architecture peut être utilisée par des institutions et des acteurs politiques. Dans tous ces contextes, le schéma est continu : façonner ce qu’il est le plus facile de dire, et donc ce qu’il est le plus facile de penser et de faire.


#korovamode

## Notes de fin

[1] K. Korovamode, « The New Machinery of Persuasion: Generative AI, Influence Architecture, and the Quiet Steering of Thought », manuscrit (2025). DOI : 10.5281/zenodo.17721122. PhilPapers : https://philpapers.org/rec/KTNMIV

[2] E. S. Herman et N. Chomsky, *Manufacturing Consent: The Political Economy of the Mass Media* (1988).

[3] P. Aggarwal et al., « GEO: Generative Engine Optimization » (2023). https://arxiv.org/abs/2311.09735

[4] Anthropic, « A small number of samples can poison LLMs of any size » (2025). https://www.anthropic.com/research/small-samples-poison

[5] P. Lewis et al., « Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks » (2020). https://arxiv.org/abs/2005.11401

[6] S. Amershi et al., « Guidelines for Human–AI Interaction » (CHI 2019). https://dl.acm.org/doi/10.1145/3290605.3300233

[7] J. D. Lee et K. A. See, « Trust in Automation: Designing for Appropriate Reliance » (*Human Factors*, 2004). https://journals.sagepub.com/doi/10.1518/hfes.46.1.50_30392

[8] J. Weizenbaum, « ELIZA—A Computer Program for the Study of Natural Language Communication Between Man and Machine » (1966). https://cse.buffalo.edu/~rapaport/572/S02/weizenbaum.eliza.1966.pdf

[9] R. J. Lifton, *Thought Reform and the Psychology of Totalism* (1961).

[10] M. Golebiewski et danah boyd, « Data Voids: Where Missing Data Can Easily Be Exploited » (2018). https://datasociety.net/wp-content/uploads/2018/05/Data_Society_Data_Voids_Final_3.pdf
