### Modèles structurés pour le traitement de l'information musicale écrite

**PhD proposal at EDITE doctoral school**

**Supervisor**: Florent Jacquemard

- florent.jacquemard@inria.fr
- https://jacquema.gitlabpages.inria.fr

**Laboratory**: INRIA Paris, Action Exploratoire Codex

Le champ pluridisciplinaire du Music Information Retrieval (MIR) [1] est concerné par le traitement, l'analyse, l'organisation et l'accès à l'information musicale dans des contenus sous différents formats: enregistrement audio, enregistrement symboliques (MIDI), partitions musicales...
Les approches développées dans ce domaine s'appuient sur des modèles acoustiques et des modèles langages, ces derniers étant le plus souvent basés sur des représentations séquentielles du contenu musical (suites de notes avec attributs de hauteur et durée). Cependant, la notation musicale, vecteur fondamental dans la pratique musicale depuis des siècles, est un format graphique beaucoup plus structuré que de simples chaînes de caractères. Elle décrit en effet une organisation hiérarchique de l'information mélodique [2] et harmonique [3] en groupes rythmiques, phrases *etc*, des relations locales et non-locales utiles à l'étude et l'interpretation de pièces.

Dans le cadre du problème de la transcription musicale [4,5], nous utilisons des modèles structurés en arbres comme représentation intermédiaire. Nous considérerons durant cette thèse la définition et l'usage de modèles similaires, structurés en arbres ou graphes et proches de la notation musicale, dans le cadre d'autres problèmes de MIR, par exemple:

- la définition de métriques de similarité et la recherche de motifs caractéristiques,

- la construction d'index pour accélérer la recherche d'information dans les bases de partitions,

- la comparaison structurelle entre partitions, 
la comparaison quantitative de passage en terme de complexité notationelle,

- l'utilisation de référentiel unique (normalisation) pour la conversion entre formats d'encodages de partitions musicales, et application dans le cadre de la construction de datasets...

L'application à des cas d'études en musicologie calculatoire sera étudiée en coopération avec des musicologues de Sorbonne Université.

#### Références

[1] Roadmap for Music Information ReSearch.
      http://openaccess.city.ac.uk/2763/1/MIRES_Roadmap_ver_1.0.0.pdf
      https://ismir.net

[2] Melodic Identification Using Probabilistic Tree Automata. José F. Bernabeu, Jorge Calera-Rubio, José Iñesta, and David Rizo. Journal of New Music Research 40(2), 2011.

[3] Towards a generative syntax of tonal harmony. Martin Rohrmeier. Journal of Mathematics and Music 5(1), 2011.

[4] A Parse-based Framework for Coupled Rhythm Quantization and Score Structuring. F. Foscarin, F. Jacquemard, P. Rigaux, and M. Sakai. 7th International Conference on Mathematics and Computation in Music (MCM 2019). see also https://qparse.gitlabpages.inria.fr 

[5] A diff procedure for music score files. Francesco Foscarin, Raphaël Fournier-S'Niehotta, Florent Jacquemard. 6th Int. Conf. on Digital Libraries for Musicology (DLfM), and 20th conf. of the Int. Soc. for Music Information Retrieval (ISMIR), 2019.

