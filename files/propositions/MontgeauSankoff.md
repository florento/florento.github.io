# Implantation et évaluation d'une distance de similarité mélodique
## Proposition de stage de recherche

### Contexte
De manière générale, les distances d'édition calculent une mesure de similarité entre deux séquences de symbole [1]. Elles sont employées en NLP pour comparer des textes, et en biologie, par exemple pour comparer des protéines, vues comme des séquences sur l'alphabet à 20 caractères des acides aminés [2]. Elles sont définies comme le nombre minimal d'opérations élémentaires (éventuellement pondérées) pour transformer la première séquence en la seconde. Dans le cas de la distance de Levenshtein [3], ces opérations sont l'insertion, la suppression, ou la substitution d'un symbole.

Dans le domaines des humanités numériques, les distances d'édition sont fondamentales en recherche d'information musicale (MIR), pour mesurer la similarité mélodique dans la musique écrite. Dans un article fondateur [4], Montgeau et Sankoff proposent une extension de la distance de Levenshtein avec des opérations de  compression (remplacement de plusieurs symboles par un seul) et expansion (opération inverse) similaires à celles de mesures issues de procédures de *Dynamic Time Wrapping* pour le traitement de la parole. 
Cette distance n'est pas calculable en général [5]. Un algorithme fondé sur des équation récursives de programmation dynamique, proposé dans [4] et souvent utilisé dans la littérature MIR en calcule une approximation. Dans [5], nous proposons des méthodes pour calculer des restrictions, intuitivement ne prenant en compte que les expansions, ce qui correspond au passage d'un thème à une variation, ou que les compression, pour le passage d'une variation à un thème. Ces méthodes s'appuient sur des constructions d'automates, suivant [6], et sont à l'heure actuelle restées à l'état théorique

### Objectifs
Le premier objectif du stage est théorique, il s'agit de réécrire les constructions de [5] sous la forme d'équation récursives, afin de définir des algorithmes de programmation dynamique pour le calcul de la mesure de Montgeau et Sankoff (des restrictions considérées).
Le deuxième objectif est l'implantation de ces algorithmes en C++ ou Python.
Enfin, le troisième objectif sera de conduire des expérimentations sur une base ad-hoc contenant des exemples de variations sur un thème, et de comparer les résultats obtenus par rapport à l'algorithme approximatif proposé dans [4].

### Mots clef
distances d'édition, similarité mélodique, extraction d'information musicale, musicologie calculatoire

### Lieu de travail et gratification
Le stage se déroulera au laboratoire CÉDRIC du Conservatoire des Arts et Métiers (CNAM), Paris, et sera encadré par Florent Jacquemard.
Une gratification incluant le remboursement de la moitié du coût de transport est envisagée, suivant la durée du stage.

### Contact
Merci d’envoyer votre demande accompagnée d’un CV à florent.jacquemard@inria.fr 

### References

[1] D. Gusfield
Algorithms on Strings, Trees, and Sequences
Cambridge University Press, 1997

[2] S. Henikoff, J. Henikoff
    Amino acid substitution matrices from protein blocks
    PNAS 89 , 10915–10919, 1992.

[3] R. A. Wagner, M. J. Fischer
    The string-to-string correction problem
    Journal of the ACM (JACM) 21 (1) (1974) 168–173.

[4] M. Mongeau, D. Sankoff
    Comparison of musical sequences
    Computers and the Humanities 24 (3) 161–175.w, 1990.

[5] M. Giraud, F. Jacquemard
    Weighted Automata Computation of Edit Distances with Consolidations and Fragmentations
    Information and Computation vol. 282, Elsevier, 2022.

[6] M. Mohri
    Edit-distance of weighted automata: General definitions and algorithms
    Int. Journal of Foundations of Computer Science 14 (06) (2003) 957–982.

