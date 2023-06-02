# Distances entre partitions musicales numériques

Projet de recherche doctoral  
École Doctorale EDITE

- **Domaine scientifique:** Sciences et technologies de l'information et de la communication
- **Directeur de thèse:** [Florent Jacquemard](https://jacquema.gitlabpages.inria.fr) (Inria-Paris (ED-130)). 

### Contexte

L'identification des différences entre deux partitions musicales (sous forme de documents XML), ainsi que la définition de métriques de similarité adaptées à de tels documents, sont des problèmes difficiles en extraction d'information musicale symbolique.
Des mesures de similarités mélodiques ont été proposées, la plus citée étant la distance d'édition de Mongeau & Sankoff [1,2]. Elles sont employées dans des domaines tels que la musicologie calculatoire (par exemple pour l'identification de passages similaires), ou la recherche d'information dans les bases de partitions musicales numériques (par exemple pour la recherche approximée sur la base d'un motif). Ces mesures, portant sur des représentations par chaines de caractères d'extraits monophoniques, ne capturent que très partiellement l'information contenue dans une partitions musicales.  
Il est en effet largement admis que la notation musicale représente, bien au-delà de simple suites de notes, une organisation *hiérarchique* d'informations mélodique, harmonique, rhythmique, induite par des dépendances non-locales entre les objets musicaux [3]. Ces aspects structurels sont essentiels à l'interpretation et à l'analyse de pièces, et ne peuvent  être ignorés pour une comparaison compréhensive de partitions.  
Par ailleurs, les distances pour la comparaison de documents textuels ne sont pas applicables directement aux partitions musicales numériques, en raison de la verbosité, la redondance et l'ambiguité des formats d'échanges les plus répandus (musicXML et MEI). 

### Objectifs

Tout d'abord, l'étude de mesures de similarité mélodique, définies sur des *chaînes de caractères*, constitue un sujet de recherche en soi, avec un certain nombre de problèmes ouverts [2]. Des études théoriques restent nécessaires pour concevoir des algorithmiques efficaces pour l'évaluation de mesures et pour leur exploitation à la recherche approximée  et la détection de similarités dans une partition ou une collection.

Au delà, ces mesures devront être étendues pour prendre en compte les aspects structurels des partitions musicales numériques mentionnés plus haut. Nous pourrons nous appuyer sur une représentation intermédiaire abstraite que nous développons depuis plusieurs années dans le cadre de travaux sur la transcription musicale [4]. Une partition musicale y est représentée sous forme d'un *arbre étiqueté*, dont la forme capture en particulier des dépendances hiérarchiques et temporelles. Sur cette base, une distance entre documents musicaux peut être définie par exemple comme une distance d'édition dédiée, opérant sur des arbres étiquetés ou des chaines ou une combinaison des deux. Nous pourrons nous inspirer d'approches appliquées aux documents textes ou données biologiques [5-7], des adaptations importantes restant toutefois nécessaires suivant un objectif de pertinence musicale. 

Ces résultats seront appliqués à des problèmes tels que l'interrogation approximée de collections de partitions numériques, le développement d'outils pour l'écriture musicale collaborative et les systèmes de gestion des versions (cf. des premiers pas obtenus dans [5]) et à la musicologie calculatoire, en particulier musicologie de corpus, en collaboration avec des spécialiste de ce domaine.

### Candidature

Les candidats titulaires d'un master (ou équivalent international) en informatique, intéressés par la recherche d'informations musicales, sont bienvenus. Ce projet demande un certain goût pour les problèmes théoriques, et de la créativité dans la réflexion et la programmation. Des connaissances préalables en algorithmique des séquences et des arbres et sur la notation musicale sont un atout important mais non nécessaire.  
La thèse se déroulera au laboratoire Cedric du CNAM, Paris.  
Les candidatures se font via https://myedb.edite-de-paris.fr  
Pour plus d'informations sur le processus de candidature:  
https://www.edite-de-paris.fr/lancement-de-la-campagne-edite-2023
ou contacter florent.jacquemard@inria.fr

### Références

[1] M. Mongeau, D. Sankoff.
Comparison of musical sequences.
Computers and the Humanities 24 (3) 161–175.w, 1990.

[2] M. Giraud, F. Jacquemard.
Weighted Automata Computation of Edit Distances with Consolidations and Fragmentations.
Information and Computation vol. 282, Elsevier, 2022.

[3] S. Koelsch, M. Rohrmeier, R. Torrecuso, S. Jentschke.
Processing of Hierarchical Syntactic Structure in Music.
Proceedings of the National Academy of Sciences 110.38, 2013.

[4] F. Foscarin, F. Jacquemard, P. Rigaux, M. Sakai.
A Parse-based Framework for Coupled Rhythm Quantization and Score Structuring
Mathematics and Computation in Music (MCM), Springer LNCS vol. 11502, 2019.

[5] M. Mohri.
Edit-distance of weighted automata: General definitions and algorithms.
Int. Journal of Foundations of Computer Science 14 (06) (2003) 957–982. 

[6] S. Schwarz, M. Pawlik, N. Augsten.
A New Perspective on the Tree Edit Distance. 
Similarity Search and Applications (SISAP), Springer LNCS vol. 10609, 2017. 

[7] M. Kusner, Y. Sun, N. Kolkin, K. Weinberger.
From Word Embeddings To Document Distances.
Proceedings of the 32nd International Conference on Machine Learning, PMLR 37:957-966, 2015.

[8] F. Foscarin, F. Jacquemard, R. Fournier-S’niehotta.
A diff procedure for music score files.
6th International Conference on Digital Libraries for Musicology, 2019.