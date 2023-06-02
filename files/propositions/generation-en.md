# Grammar Generative Models for Music Notation Processing
Doctoral research project
EDITE Paris Doctoral School

### Context
Deep generative models have been successfully applied in many learning experiments with digital data, such as images or audio.
In the field of music, they can also be used to generate symbolic representations, in the context of problems such as automatic music generation or transcription [1-3]. A significant challenge for generating structured symbolic data in general is obtaining *well-formed results*.
This is especially true in the case of music. It is indeed widely accepted that musical notation represents, well beyond simple sequences of notes, a hierarchical organization of melodic and harmonic information, inducing non-local dependencies between musical objects [4]. A good representation of this information is essential for the interpretation and analysis of music pieces.

The authors of [5] study the case of structured symbolic data that can be represented by syntactic trees of a context-free grammar, and propose a treatment using a variational auto-encoder (VAE) which directly encodes and decodes these syntactical trees, for a given grammar, in order to obtain syntactically valid data - the encoding is a computational linear representation of the grammar (to produce a tree). This approach has given good results in the field of molecular synthesis.

### Objectives
The objective of this thesis is the study of the application of the latter approach to the case of musical notation.
We will rely for this on a tree model of musical notation that we develop as an intermediate representation for the treatment of problems such as musical transcription, the search for information in the databases of scores and the analysis of scores [6- 7].
Appropriate adaptations of this tree model, grammars generating such trees [6] and appropriate tree transformations [8] should be designed for the targeted application. A corpus of trees will be constituted from partitions in XML format and data augmentation techniques, and applied for model training.

The main intended application is the transcription of piano performances recorded in the symbolic MIDI format. We can use in this context large databases of piano scores in XML format and corresponding MIDI performances (whether recordings of real musicians on electronic keyboards or artificial performances). The problem of automatic generation can also be approached, for example by imitation (of other scores) or to produce a summary,
or from a description of the desired piece.

### Application
We welcome candidates with a master’s degree (or international equivalent) in computer science, who are curious about applied machine learning in music information retrieval. This project requires creative thinking and programming. Prior machine learning experience and knowledge in music notation is an important merit.  
The thesis will take place at the Cedric laboratory of the CNAM, Paris, France. 
Applications shall be made via https://myedb.edite-de-paris.fr  
For more informations about the application process, please consult 
https://www.edite-de-paris.fr/lancement-de-la-campagne-edite-2023
or contact florent.jacquemard@inria.fr

### References
[1] Jean-Pierre Briot, Gaëtan Hadjeres, and François Pachet.
Deep Learning Techniques for Music Generation.
Vol. 1 series Computational Synthesis and Creative Systems, Springer, 2020.

[2] Cheng-Zhi Anna Huang et al.
Music Transformer.
arXiv preprint arXiv:1809.04281 2018.

[3] Masahiro Suzuki.
Score Transformer: Generating Musical Score from Note-level Representation.
ACM Multimedia Asia. 2021.

[4] Stefan Koelsch, et al.
Processing of Hierarchical Syntactic Structure in Music.
Proceedings of the National Academy of Sciences 110.38, 2013.

[5] Matt J. Kusner, Brooks Paige, and José Miguel Hernández-Lobato.
Grammar Variational Autoencoder.
International conference on machine learning. PMLR, 2017.

[6] Francesco Foscarin et al.
A Parse-based Framework for Coupled Rhythm Quantization and Score Structuring.
7th International Conference on Mathematics and Computation in Music (MCM 2019).
see also <https://qparse.gitlabpages.inria.fr>

[7] Tiange Zhu et al.
A Framework for Content-Based Search in Large Music Collections.
Big Data and Cognitive Computing, 6 (1): 23, 2022.

[8] Florent Jacquemard, Pierre Donat-Bouillud, Jean Bresson.
A Structural Theory of Rhythm Notation Based on Tree Representations and Term Rewriting.
5th International Conference on Mathematics and Computation in Music (MCM) 2015.
