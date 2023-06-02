# Digital Music Score Distances

Doctoral research project
EDITE Paris Doctoral School

### Context

The identification of differences between two musical scores (in the form of XML documents), as well as the definition of similarity metrics adapted to such documents, are difficult problems in the extraction of symbolic musical information.
Measures of melodic similarity have been proposed, the most cited being the edit distance of Mongeau & Sankoff [1,2]. They are used in fields such as computational musicology (for example for the identification of similar passages), or the search for information in the databases of digital musical scores (for example for the approximate search on the basis of a pattern ). These measurements, relating to representations by character strings of monophonic extracts, capture only very partially the information contained in a musical score.  
It is indeed widely accepted that musical notation represents, well beyond simple sequences of notes, a *hierarchical* organization of melodic, harmonic, rhythmic information, induced by non-local dependencies between musical objects [3] . These structural aspects are essential to the interpretation and analysis of pieces, and cannot be ignored for a comprehensive comparison of scores.  
Moreover, the distances for the comparison of textual documents are not directly applicable to digital musical scores, due to the verbosity, redundancy and ambiguity of the most widespread exchange formats (musicXML and MEI).

### Objectives

First of all, the study of measures of melodic similarity, defined on *character strings*, constitutes a subject of research in itself, with several open problems [2]. Theoretical studies remain necessary to design efficient algorithms for the evaluation of measurements and for their use in the approximate search and the detection of similarities in a score or a collection.

Beyond that, these measures will have to be extended to take into account the structural aspects of digital musical scores mentioned above. We will be able to rely on an abstract Intermediate Representation that we have been developing for several years in the context of music transcription [4]. A musical score is represented there in the form of a *labeled tree*, the shape of which captures in particular hierarchical and temporal dependencies. On this basis, a distance between musical documents can be defined for example as a dedicated edit distance, operating on labeled trees or chains or a combination of both. We will be able to draw inspiration from approaches applied to text documents or biological data [5-7], although significant adaptations remain necessary according to an objective of musical relevance.

These results will be applied to problems such as the approximate querying of digital sheet music collections, the development of tools for collaborative music writing and version management systems (cf. first steps obtained in [5]) and computational musicology, in particular corpus musicology, in collaboration with specialists in this field.

### Application

Candidates with a master's degree in computer science, interested in finding musical information, are welcome. This project requires a certain taste for theoretical matters, and creativity in thinking and programming. Prior knowledge of sequence and tree algorithms and musical notation is an important asset but not neca requirement.  
The thesis will take place at the Cedric laboratory of the CNAM, Paris.  
Applications shall be made via https://myedb.edite-de-paris.fr  
For more information on the application process:
https://www.edite-de-paris.fr/lancement-de-la-campagne-edite-2023
or contact florent.jacquemard@inria.fr

### References

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