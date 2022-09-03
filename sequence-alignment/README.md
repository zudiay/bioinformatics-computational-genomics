# Sequence Alignment

The Needleman-Wunsch global sequence alignment algorithm and the Smith-Waterman local sequence alignment algorithm are implemented. 
The algorithms are implemented for both linear and affine gap penalty. They take two amino
acid sequences, gap penalty type (i.e. linear or affine), gap opening, and gap extension penalties as
input, and should output the maximum alignment score of these sequences, as well as the alignment
achieving this maximum score. For match and mismatch, the [BLOSUM62 scoring matrix](http://www.ncbi.nlm.nih.gov/Class/BLAST/BLOSUM62.txt) is used.
The gap opening penalty is taken as 11 and the gap extension penalty as 1.

<i> Developed for CMPE 484, Bioinformatics and Computational Genomics projects, Spring 2022 <i>
