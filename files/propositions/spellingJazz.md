# Pitch Spelling Jazz
## proposition de stage de recherche
### Contexte
En musique, une hauteur de note peut être représentée simplement par le numéro de touche correspondant sur un clavier de piano. C’est la convention utilisée par exemple dans le standard MIDI. Dans la notation musicale occidentale, les hauteurs sont représentées par un nom de note et un modificateur de un ou plusieurs demi tons, positif ou négatif (note par des dièses ou bémols). Si la première représentation est univoque, dans le cas de la seconde, on peut avoir plusieurs noms pour la même note (enharmoniques, par exemple do dièse et ré bémol).
Le problème du Pitch Spelling (sans traduction française a notre connaissance) consiste, à partir d’une série de numéros de notes MIDI à inférer des noms correspondants en notation musicale, d’une manière cohérente et conforme à la pratique traditionnelle.  Ce problème n’est pas trivial car le choix entre enharmoniques dépend du contexte (mouvement, contexte tonal...).

Plusieurs solutions ont été proposées dans la littérature [1-5], voir [6] pour un aperçu plus complet, ou [7] pour une approche plus récente par apprentissage. 
Dans le cadre de travaux en transcription musicale [9], nous avons également mis au point un algorithme de programmation dynamique [8] qui a l'avantage d'être simple et efficace. Cet algorithme évalue conjointement le pitch-spelling et la tonalité d'un morceau. Les premières expériences ont montré de bon résultats sur des extraits classiques.
### Objectif
Ce stage vise à étendre l’approche [8] au répertoire jazz, en particulier aux transcriptions de soli. L'algorithme [8] infère un contexte tonal local, dans un mode majeur ou mineur harmonique. Le but sera de prendre également en compte d'autres modes fréquents en jazz.
Une évaluation sera conduite sur des lignes de basses et des transcriptions de soli [10,11]. 
### Mots clef
extraction d'information musicale, pitch spelling, transcription musicale
### Lieu de travail et gratification
Le stage se déroulera au laboratoire CÉDRIC du Conservatoire des Arts et Métiers (CNAM), Paris, et sera encadré par Florent Jacquemard.
Une gratification incluant le remboursement de la moitié du coût de transport sera envisagée suivant la durée du stage.
### Contact
Merci d’envoyer votre demande accompagnée d’un CV à florent.jacquemard@inria.fr 
### References
[1] Emilios Cambouropoulos 
    From MIDI to traditional musical notation.
    Proceedings of the AAAI Workshop on Artificial Intelligence and Music: Towards Formal Models for Composition, Performance and Analysis. Vol. 30. 2000.

[2] Emilios Cambouropoulos
    Pitch Spelling: A Computational Model.
    Music Perception, 20(4), 2003.

[3] Elaine Chew and Yun-Ching Chen
    Real-Time Pitch Spelling Using the Spiral Array
    Computer Music Journal, 29(2), 2005.

[4] Aline K. Honingh
     Compactness in the Euler-Lattice: A Parsimonious Pitch Spelling Model 
     Musicae Sientiae 13(1), Sagepub, 2009
https://doi.org/10.1177/1029864909013001005

[5] David Meredith
    The ps13 Pitch-Spelling Algorithm.
    Journal of New Music Research 35(2):121-159. 2006.

[6]  David Meredith, Geraint A. Wiggins
     Comparing pitch spelling algorithms
     in Proceedings of the International Conference on Music Information Retrieval, ISMIR 2006.

[7] Francesco Foscarin, Nicolas Audebert, Raphaël Fournier-S'Niehotta
     PKSpell: Data-Driven Pitch Spelling and Key Signature Estimation
     in Proceedings of the International Conference on Music Information Retrieval, ISMIR 2021.
     
[8] https://gitlab.inria.fr/pse/pse  (travail en cours)

[9] https://qparse.gitlabpages.inria.fr

[10] Martin Pfleiderer et al.
       Inside the Jazzomat: New Perspectives for Jazz Research
       Schott Music GmbH, 2017.

[11] Dave Foster, Simon Dixon
       Filosax: A Dataset of Annotated Jazz Saxophone Recordings
        in Proceedings of the International Conference on Music Information Retrieval, ISMIR 2021.