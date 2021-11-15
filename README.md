This is a code in a R markdown format *clonal_group_analysis.Rmd*, used for analysis of B cell clonal lineages and visualisation of results in the study "Memory persistence and positively selected transition to antibody-secreting subsets in longitudinal lGH repertoires". An easy way to look at the code and to check its ouput is to open *clonal_group_analysis.html* or *clonal_group_analysis.pdf* files.

The code assumes, that the working directory contains following objects:

**whole_reperotires** - whole repertoires in the format of MiXCR output;
 
**alignments** - alignments of B-cell clonal lineages with the predicted MRCA and germline sequences in FASTA format;

**trees** - phylogenetic trees of B-cell lineages with the germline sequence as an outgroup in newick format;

**G-MRCA** - aligments of the germline sequence with MRCA in FASTA format;

**timepoint.csv** - correspondence of the number of sampling time points to real dates for eacg donor;

**table_of_repeats.rds** - the list of clonotypes with the same BCR sequence, but came from different time point / cell subsets / isotypes. 

In a direcories, presented, there are just a few corresponding example files, to show the format used.
