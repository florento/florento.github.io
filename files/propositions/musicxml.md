## Export MusicXML d'une representation intermédiaire de partitions musicales
## Proposition de stage de recherche
### Contexte
Il existe de nombreux encodages pour les partitions musicales numériques: formats texte (abc, kern**, Lilypond...), ou structurés (MusicXML, MEI...). Ils ont été conçus pour pour différent usages: écriture, rendu, échange, sauvegarde. Cependant, aucun n'est adapté à toutes les tâches d’extraction d'information musicale, comme en particulier la transformation de partitions, l'analyse musicologique, recherche et indexation dans des collections (base de partitions numériques)...

Dans le cadre de travaux sur les collections de partitions et la transcription musicale, nous utilisons une représentation intermédiaire (RI) [1] abstraite, afin d’être à même de raisonner sur une partition ou un corpus, indépendamment  de l'encodage des documents. Une partition en RI peut être exportée à l'heure actuelle (en autre) en un fichier XML au format MEI [2].
### Objectif
Ce stage a pour but le développement d'une sortie, depuis la représentation intermédiaire ci-dessus, vers l'encodage MusicXML [3], un format ouvert standard pour l'échange de partition numériques supporté par la plupart des éditeurs de partitions. On s'appuiera pour cela sur la librairie C++ libMusicXML [4]. Le développement sera fait en C++.
Des tests seront réalisés à partir d'un benchmark de partitions contenant des traits de notation particuliers, dans un environnement Python, via un binding pybind11 existant.
De bonnes connaissances de la programmation C++ et de la notation musicale [5] sont nécessaires pour ce stage de développement.

### Mots clef
extraction d'information musicale, XML, encodages de partitions musicales, transcription musicale
### Lieu de travail et gratification
Le stage se déroulera au laboratoire CÉDRIC du Conservatoire des Arts et Métiers (CNAM), Paris, et sera encadré par Florent Jacquemard.
Une gratification incluant le remboursement de la moitié du coût de transport sera envisagée suivant la durée du stage.
### Contact
Merci d’envoyer votre demande accompagnée d’un CV à florent.jacquemard@inria.fr 
### References

[1] Fred Chow
    The Challenge of Cross-language Interoperability
    ACM queue, volume 11, issue 10, 2013  

[2] https://music-encoding.org

[3] Michael Good
     MusicXML and Repertoire Development
     MakeMusic 

[4] Dominique Fober
     MusicXML library https://github.com/grame-cncm/libmusicxml
     GRAME
     
[5] Elaine Gould
     Behind Bars: The Definitive Guide to Music Notation
     Faber Music, 2012.